# INSTRUCTIONS

## Init
Download <a href="ConsoleApp1.exe" >ConsoleApp1.exe</a> "ConsoleApp1.exe" or please your Application into target computer. Example: C:\ConsoleApp1.exe
## Init Registers
Download adn run <a href="CustomURLProtocol.exe" >CustomURLProtocol.exe</a> "CustomURLProtocol.exe" 
###  Fill Filds 
Protocol Name: MyCompanyProtocol

Company Name: MyCompany

Application Path: your Application path in target computer Example: C:\ConsoleApp1.exe

Click Create then Click Test to test it, this will add registers to target computer.

## Place code into webpage 
Place 

```
<xmp><a href="MyCompanyProtocol: commandtype=getPrinterList" >Run My App</a></xmp>
```

Where application params can be attcahed like in example "MyCompanyProtocol: commandtype=getPrinterList" in a href