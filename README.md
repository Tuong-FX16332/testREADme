# ambi_factory_fw_esp32
For factory testing

Guides for running

Step 1: Download  and Install Arduino IDE: 

	Recommend: newest version (Arduino IDE 2.0),
	you can download at this page https://docs.arduino.cc/software/ide-v2
	
	
Step 2: Install ESP32C3 board: 
//----------------------------------------------------------------------------------------------------------
	File -> Preferences -> add this link "https://raw.githubusercontent.com/espressif/arduino-esp32/gh-pages/package_esp32_dev_index.json" to Additional Boards Manager URLs -> OK.
//------------------------------------------------------------------------------------------------
	Tools -> Boards -> Boards Manager -> search for "ESP32" -> install esp32 (by Espressif Systems).
//------------------------------------------------------------------------
	After installed, tools -> Boards -> ESP32Arduino -> ESP32c3 Dev Module
		
Step 3: Add library:
//---------------------------------------------------------------------------------------------------
	Sketch -> include library -> add .zip library -> go to <EVT_MiniV2> folder -> library_here -> add. 
//-------------------------------------------
	Sensirion_Core.zip and IRremoteESP8266.zip
		
Step 4: Choose partition for ESP32C3:
//---------------------------------------
	Tools -> Partition Scheme -> Huge App
	
Step 5: Choose Serial port connected to ESP32c3 board:
//---------------------------------------------
	tools -> port -> choose your connected port 

Step 6: Build and Run:
//--------------------------------------------------------------------------------
	click Upload and wait until it done :>
