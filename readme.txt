you need 
-Devkit esp-wroom-32
-ESP-Pprog plate(FTDI)

1)download and install ESP_IDF Tools
2)create folder "esp" on C:/esp, open cmd->cd C:/esp -> git clone --recursive https://github.com/espressif/esp-idf.git
3)add IDF_PATH on the system variables (name IDF_PATH; folder C:/esp/esp-idf)
4)add on system variables Path (C:\esp\.espressif\tools\openocd-esp32\v0.10.0-esp32-20200709\openocd-esp32\bin)
"note"
Use your drive name and your paths
5)install python on C:\esp\
6)add on system variables Path(C:\esp\.espressif\tools\idf-python\3.8.7)
"note"
Use your drive name, your paths and versions python
7)run cmd -> write "python -m pip install --user -r %IDF_PATH%/requirements.txt" +enter
8)add on system variables Path C:\esp\.espressif\tools\cmake\3.16.4\bin
9)insert Esp-prog
10)download zadiag
11)select list all devices> select Dual rs-232 interface-0(Win USb ->replace)
12)instal vscode, add c/c++ intellSense and Native Debug
13)open vscode, open folde -> esp/esp-idf/example/get_started/hello_world/ 
14)add my json files to folder
15)edit json for your paths
16)add on system variables C:\esp\.espressif\tools\xtensa-esp32-elf\esp-2020r3-8.4.0\xtensa-esp32-elf\bin
17)Run terminal and write "idf.py build"
17)after building the project, select run and debug


