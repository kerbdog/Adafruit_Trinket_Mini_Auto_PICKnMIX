# Adafruit_Trinket_Mini_Auto_PICKnMIX
Auto-start PICKnMIX with Adafruit Trinket Mini 3v/5v PCB
## Adafruit Trinket Mini 3v/5v Auto PICKnMIX for MVS 161 in 1 (Banana Cart)

PICKnMIX is a feature of UniBIOS v4.0 for the NeoGeo AES and MVS, created by Razoola http://unibios.free.fr/picknmix.html
It allows the 161 in 1 (Banana Cart) to act like a multislot system, enabling a attract/demo mode showing the 98 unique/working games and a menu system to select each one.  This mod allows the MVS system to start by default into PICKnMIX mode by holding the Start button on power up

By GeorgeSpinner, with super tiny LED status indicator mod by KeRbDoG

Start button will be held for 5 seconds with POWER ON, the Red LED indicator on the Trinket will show when the button is being held

If any button wired to pin 2 is held during POWER ON sequence, the regular 161 in 1 menu will be displayed

How to setup:
  - PWR - JAMMA PIN 3
  - GND - JAMMA PIN 1
  - 0   - JAMMA PIN 17
  - 2   - JAMMA PIN 25

In the above setup - The Holding the D button during POWER ON will skip PICKnMIX

### Does NOT work with standard Adafruit Trinket Mini 3v/5v bootloader (takes more than 2 seconds before code executes)
Must use Bootloader found here: https://forums.adafruit.com/download/file.php?id=34218 (trinketloader_skippow25.zip) 

#### To do
  - See how this can be adapted for AES HW wise -KeRbDoG
