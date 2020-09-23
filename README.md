<div align="center">

## The Most Simple Credit \- Scroller


</div>

### Description

This code will easily let any user create simple, yet effective credit scroller. This is so effectively easy, that any novice can create it. I created this code because I tried the other source code on this site, and I found it difficult to follow.
 
### More Info
 


<span>             |<span>
---                |---
**Submitted On**   |
**By**             |[silverx10](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByAuthor/silverx10.md)
**Level**          |Unknown
**User Rating**    |6.0 (605 globes from 101 users)
**Compatibility**  |VB 3\.0, VB 4\.0 \(16\-bit\), VB 4\.0 \(32\-bit\), VB 5\.0, VB 6\.0
**Category**       |[Miscellaneous](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByCategory/miscellaneous__1-1.md)
**World**          |[Visual Basic](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByWorld/visual-basic.md)
**Archive File**   |[](https://github.com/Planet-Source-Code/silverx10-the-most-simple-credit-scroller__1-1229/archive/master.zip)





### Source Code

```
1) Create a new project (Standard EXE).
2) Place a label on the form at the bottom with whichever BackColor you set the form's BackColor to, and leave all the other properties alone except these:
 A) Alignment: 2 - Center
 B) Caption: This is a sample scroller.
3) On the form, place two picture boxes (one on top of the form, and one on the bottom) with these properties set. (Leave all others alone.)
 A) BackColor: &H80000012&
 B) BorderStyle: 0 - None
 NOTE: Be sure that the picture box is covering the label.
4) Place a timer on the form, and set the interval to '1'. And inside the timer, copy and paste this code:
 Label1.Top = (Label1.Top - 20)
 If Label1.Top = 0 Then '0 is the location topmost form coordinate
    Label1.Top = Me.Height
 End If
5) Run and test the program. Viola! You now have created the most simple scroller program available! If you have any problems with this code, which you shouldn't, please e-mail me at: madcat47@hotmail.com
```

