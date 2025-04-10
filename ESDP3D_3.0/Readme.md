Thanks to the great project [ESP3D](https://github.com/luc-github/ESP3D), SD WiFi Pro has more possibilities. For detailed configuration and usage details, please refer to the [ESP3D wiki website](https://esp3d.io/).

With ESP3D you can get the following main features:

- WebDav
- FTP
- Websever with WebUI
- OLED screen support
- Printer control via serial port

Here is a packaged firmware source code example(\ESDP3D_3.0\soure code\ESP3D-3.0.7z), which can be directly opened with Vscode+Platform.IO for compilation and downloading.
At the same time, two configuration files required by the firmware are also provided: platformio.ini and configuration.h, which define the pin allocation and device information of SD WiFi Pro, making it easy to pull the latest ESP3D source code for compilation. These two files can also refer to the SD WiFi Pro schematics and are generated using the [ESP3D configuration tool](https://luc-github.github.io/).

If you don't want to compile it yourself, you can use the one-key downloader (SWP-ESP-V3.0-one-key-upload) in the folder to automatically download the pre-compiled firmware to SD WiFi Pro.





感谢[ESP3D](https://github.com/luc-github/ESP3D)这个伟大的项目，使得SD WiFi Pro有了更多的可能。详细的配置和使用细节可以参考[ESP3D的wiki网站](https://esp3d.io/)。

通过ESP3D你可以获得以下主要功能：

- WebDav

- FTP

- Websever with WebUI

- OLED screen support

- 通过串口控制打印机

这里提供了一份打包好的固件源码实例(\ESDP3D_3.0\soure code\ESP3D-3.0.7z)，可以使用Vscode+Platform.IO直接打开进行编译并下载，
同时，也提供了固件必须的两个配置文件platformio.ini，configuration.h，里面定义了SD WiFi Pro的pin分配和设备信息，便于拉取最新的ESP3D源码进行编译。这两个文件也可以参考SD WiFi Pro原理图，使用[ESP3D配置工具](https://luc-github.github.io/)生成。

如果不想自己编译的，可以使用文件夹下的一键下载程序（SWP-ESP-V3.0-one-key-upload），自动下载预编译好的固件到SD WiFi Pro。



## Default Configuration      
Default Settings:    
* Access Point: ESP3D    
* PW:12345678   
* Authentification: WPA     
* IP: 192.168.0.1   
* Baud rate: 115200   
* Web port:80 
* Data port: 8888     
if Authentication is enabled :
* User: admin   
* Password: admin   
* User:user   
* Password: user 