# ps4-to-midi
A Python application that transforms a PlayStation 4 controller into a tactile and intuitive MIDI device. 
Designed for musicians, educators, and enthusiasts, this tool allows the PS4 controller to interface with digital audio workstations and other MIDI-compatible software, 

current usage: Controlling synths, adjusting volumes, tweaking parameters.

## Python Requirements
1. pygame
2. mido

## MacOS
1. Create "ps4" port in the device "IAC Driver" 

        "Audio MIDI Setup" > "Window" > "Show MIDI Studio" > "IAC Driver" > "Ports"
    Check "Device is online"
2. Connect a ps4 controller (Some other gamepads also work fine with MacOS, though for some of them there are specific tricks to establish the connection)
3. Run app.py (Make sure that MIDI output works by pressing some buttons. An output in console window should appear)
4. Launch your DAW and search for "IAC Driver (ps4)"
5. Have fun!
