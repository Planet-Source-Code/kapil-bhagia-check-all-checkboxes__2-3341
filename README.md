<div align="center">

## Check All checkboxes


</div>

### Description

To check all check boxes on the web page
 
### More Info
 
Takes the master checkbox control name, and checks/ unchecks other check boxes on the web page depending on the master check box status


<span>             |<span>
---                |---
**Submitted On**   |
**By**             |[Kapil Bhagia](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByAuthor/kapil-bhagia.md)
**Level**          |Intermediate
**User Rating**    |4.4 (22 globes from 5 users)
**Compatibility**  |
**Category**       |[Controls/ Forms/ Graphics/ Menus](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByCategory/controls-forms-graphics-menus__2-59.md)
**World**          |[Java](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByWorld/java.md)
**Archive File**   |[](https://github.com/Planet-Source-Code/kapil-bhagia-check-all-checkboxes__2-3341/archive/master.zip)





### Source Code

```
function gCheckAll(chk)
	{
	for (var i=0;i < document.forms[0].elements.length;i++)
		{
			var e = document.forms[0].elements[i];
			if (e.type == "checkbox")
			{
				e.checked = chk.checked
			}
		}
	}
```

