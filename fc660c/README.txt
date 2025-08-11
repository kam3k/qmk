The json file is ready by https://config.qmk.fm to configure layout of an fc660c keyboard.

Steps:
1. Upload json file to the above website, make any changes, compile and download hex
2. Also download JSON and put in this repo
3. Install dfu-programmer
4. Press button under keyboard
5. sudo dfu-programmer atmega32u4 erase
6. sudo dfu-programmer atmega32u4 flash <hex file>
7. sudo dfu-programmer atmega32u4 reset
