# ExcelDNAExample
Example Excel DNA add-in for reference\
Demonstrates some useful/common functionality for Excel DNA add-ins (ie. multithreaded function callbacks, returning to main thread for COM object model operations, custom cell functions, custom UI)
![image](https://user-images.githubusercontent.com/7013902/155989182-c76cccc6-88f0-47ba-95cb-f04719f5c9a5.png)

Notes for building and running:
* Set your "Start external program" path to    <span style="color:blue">some *blue* text</span>.
* Set your "Command line arguments" to   **/x "ExcelDNAExample-AddIn64.xll"** 
This makes VS run Excel with your plugin when you press play.