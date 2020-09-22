<div align="center">

## Printing PDF in \.Net


</div>

### Description

Enable you to print a pdf using the shell command
 
### More Info
 


<span>             |<span>
---                |---
**Submitted On**   |
**By**             |[Chad](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByAuthor/chad.md)
**Level**          |Beginner
**User Rating**    |4.0 (16 globes from 4 users)
**Compatibility**  |VB\.NET
**Category**       |[Documents/ Frames](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByCategory/documents-frames__10-27.md)
**World**          |[\.Net \(C\#, VB\.net\)](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByWorld/net-c-vb-net.md)
**Archive File**   |[](https://github.com/Planet-Source-Code/chad-printing-pdf-in-net__10-4046/archive/master.zip)

### API Declarations

Thanks to Tony for this code!


### Source Code

```
Dim psiPrint As New System.Diagnostics.ProcessStartInfo()
psiPrint.Verb = "print"
psiPrint.WindowStyle = ProcessWindowStyle.Hidden
psiPrint.FileName = "C:\MyFile.pdf"
psiPrint.UseShellExecute = True
System.Diagnostics.Process.Start(psiPrint)
```

