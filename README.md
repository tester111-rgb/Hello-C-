# Hello-C-
1. Dowload VSCode : https://code.visualstudio.com/
             1.1 extension
                  c/c++ extensionpack,
                  code runner (setting >>run in terminal/save file before run/ Excutor map >>cpp": "clear )
   
3. Dowload ;Chocolatey : https://chocolatey.org/install
               go to ;Install Chocolatey for Individual Use:
             2.1  ใช้ command >>> วาง window powershell or terminal addmin run ด้วย addmin
   
              Set-ExecutionPolicy Bypass -Scope Process -Force; [System.Net.ServicePointManager]::SecurityProtocol = [System.Net.ServicePointManager]::SecurityProtocol -bor 3072; iex ((New-Object System.Net.WebClient).DownloadString('https://community.chocolatey.org/install.ps1'))
                  
2.2 Test ใช้ command >>>   
              
              choco --version
   
   ถอนการติดตั้ง Remove-Item -Recurse -Force "C:\ProgramData\chocolatey"
   ตรวจสอบว่าถอนการติดตั้งแล้ว choco
              2.3  ใช้ choco ติดตั้ง mingw  .ใช้ command >>> choco install mingw
   ได้มาจาก community >>> https://community.chocolatey.org/packages?q=mingw
              2.4 ปิดเครื่อง
              2.5 ทดสอบว่าติดตั้ง mingw แล้ว ใช้ command g++ --version
   

   
MinGW : https://sourceforge.net/projects/mingw/ 

https://www.sourcetreeapp.com/
