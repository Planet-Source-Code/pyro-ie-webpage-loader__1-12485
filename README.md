<div align="center">

## IE Webpage Loader


</div>

### Description

Type in a URL, and this example will open Internet Explorer, with the given URL.
 
### More Info
 
1 Command button

ShellX Command


<span>             |<span>
---                |---
**Submitted On**   |
**By**             |[PyRo](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByAuthor/pyro.md)
**Level**          |Beginner
**User Rating**    |3.7 (22 globes from 6 users)
**Compatibility**  |VB 4\.0 \(16\-bit\), VB 4\.0 \(32\-bit\), VB 5\.0, VB 6\.0, VB Script
**Category**       |[Internet/ HTML](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByCategory/internet-html__1-34.md)
**World**          |[Visual Basic](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByWorld/visual-basic.md)
**Archive File**   |[](https://github.com/Planet-Source-Code/pyro-ie-webpage-loader__1-12485/archive/master.zip)





### Source Code

```
Private Sub Command1_Click()
PageLocation$ = Text1.Text
ShellX = Shell("explorer.exe " + PageLocation$)
End Sub
```

