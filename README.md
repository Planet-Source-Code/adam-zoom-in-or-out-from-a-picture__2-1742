<div align="center">

## Zoom in or out from a picture\.


</div>

### Description

This is the code for the IE5 zoom in/out menu. If you have IE5, go into "C:\windows\web\zoomin.html" or "C:\windows\web\zoomout.html" to get it from there. Just make sure to open it up with a text editor, not your browser.

Remember: I did not make this code, microsoft did.
 
### More Info
 
nope


<span>             |<span>
---                |---
**Submitted On**   |
**By**             |[Adam](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByAuthor/adam.md)
**Level**          |Intermediate
**User Rating**    |4.5 (9 globes from 2 users)
**Compatibility**  |
**Category**       |[Graphics](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByCategory/graphics__2-75.md)
**World**          |[Java](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByWorld/java.md)
**Archive File**   |[](https://github.com/Planet-Source-Code/adam-zoom-in-or-out-from-a-picture__2-1742/archive/master.zip)





### Source Code

```
<!--Zoom In--!>
<HTML>
<SCRIPT LANGUAGE="JavaScript" defer>
var parentwin = external.menuArguments;
var doc = parentwin.document;
var w;
var h;
L_Alert_Message = "You must right-click on an image to Zoom.";
if ( parentwin.event.srcElement.tagName == "IMG" )
{
	h = parentwin.event.srcElement.height * 2;
	parentwin.event.srcElement.height = h;
	w = parentwin.event.srcElement.width * 2;
	parentwin.event.srcElement.width = w;
}
else
	alert (L_Alert_Message);
</SCRIPT>
</HTML>
<!--End Zoom In--!>
<!--Zoom Out--!>
<HTML>
<SCRIPT LANGUAGE="JavaScript" defer>
var parentwin = external.menuArguments;
var doc = parentwin.document;
var w;
var h;
L_Alert_Message = "You must right-click on an image to Zoom.";
if ( parentwin.event.srcElement.tagName == "IMG" )
{
	h = parentwin.event.srcElement.height / 2;
	parentwin.event.srcElement.height = h;
	w = parentwin.event.srcElement.width / 2;
	parentwin.event.srcElement.width = w;
}
else
	alert (L_Alert_Message);
</SCRIPT>
</HTML>
<!--End Zoom Out--!>
```

