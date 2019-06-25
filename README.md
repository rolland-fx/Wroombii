# Wroomba32

Adapted from : https://github.com/cybrox/wroomba

To setup :
- follow this (until step 9 to validate correct working state) : https://docs.espressif.com/projects/esp-idf/en/latest/get-started/#get-started-setup-toolchain
- as per now, a small fix is needed to compile the project :
copy "mdns_private.h" from esp-idf/component/mdns/private_include to esp-idf/component/mdns/include
- change tty (or equivalent) to the correct serial port 
- make flash 

this is it !
