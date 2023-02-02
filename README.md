# ModBus Slave(Master)

Using ESP32 , webserver

1. include https://ajax.googleapis.com/ajax/libs/jquery/3.2.1/jquery.min.js file into code.  
   not anymore upload into esp32 flash memory.
2. Upload html list.

- index.html
- for upload http://<url>/loginIndex
- for fileUpload http://<url>/upload 


3. For Debugging  
   Udp Moniter port is 1235

- nc -ul -p 1235 or
- nc -ul -p 1235 | hexdump -C

4. developer template 
   https://github.com/platformio/platform-espressif32/tree/develop/boards
   using esp-wrover-kit.json
   modify flash to 800000 and save as esp-wrover-kit_8M.json

