<div align="center">

## StopTextBoxFromBeeping


</div>

### Description

Show how to make a text box not beep but do something else when I hit the Enter key. This code example makes nothing happen, for an extended period of time:
 
### More Info
 


<span>             |<span>
---                |---
**Submitted On**   |
**By**             |[VB FAQ](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByAuthor/vb-faq.md)
**Level**          |Unknown
**User Rating**    |4.2 (161 globes from 38 users)
**Compatibility**  |VB 3\.0, VB 4\.0 \(16\-bit\), VB 4\.0 \(32\-bit\), VB 5\.0, VB 6\.0
**Category**       |[Custom Controls/ Forms/  Menus](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByCategory/custom-controls-forms-menus__1-4.md)
**World**          |[Visual Basic](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByWorld/visual-basic.md)
**Archive File**   |[](https://github.com/Planet-Source-Code/vb-faq-stoptextboxfrombeeping__1-69/archive/master.zip)





### Source Code

```
Sub Text1_KeyPress (KeyAscii As Integer)
If KeyAscii = 13 Then '13 is Key_Return
KeyAscii = 0
End If
End Sub
```

