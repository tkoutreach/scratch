# RaspberryPi preparation
1.	Chance Language to Japanese:
    - Go to Menu > Preferences > Raspberry Pi Configuration 
    - Set Location > Language (ja), Country (JP), Character Set (UTF-8) > OK > Set Timezone > Japan 
    - restart Pi
    
2.	Wifi setting 
    - Use GUI to connect to Open_Internet 
    - Open browser and go to “google.com” 
    - Read the use term and click agree
    
3.	Keyboard Japanese input:
    - Go to Terminal 
    - “sudo apt-get update” 
    - “sudo apt-get install fcitx-mozc” 
    - Reboot Pi
4.	Change display setting: 
    - Go to Menu > Preferences > Raspberry Pi Configuration > Overscan > Disabled
    
5.	Change sound setting to Analog (*depends on a monitor): 
    - Plug in headset in pi 
    - Right click the sound icon and choose Analog
    - Go to LXTerminal 
    - Test “ aplay /usr/share/sounds/alsa/Front_Center.wav” 
    
6.	Camera setting:
    - Go to Terminal
    - “sudo raspi-config”
    - choose 5 Interfacing options 
    - choose P1 Camera
    - enter
    - click yes 
    - Reboot Pi

7.	Install Scratch2MCPI:
    - Go to LXTerminal 
    - “sudo curl http://scratch2mcpi.github.io/install.sh | sh” 
    - confirm the icon is created on desktop 
    - Launch Minecraft 
    - press Tab key 
    - Launch Scratch2MCPI 
    - confirm connection on Minecraft screen
    - send an event from Scratch
8.	Download scratch games to desktop
    - Go to LXTerminal 
    - “cd Desktop” 
    - “git clone https://github.com/tkoutreach/scratch.git”


# Scratch 
## Introduce to Scratch (1:10pm - 1:50pm, 40 min)
1. Let’s start scratch(10min) 
https://www.nhk.or.jp/sougou/programming/?das_id=D0005180302_00000

2. Tutorial - Scratch command(20min)
https://github.com/tkoutreach/scratch/blob/master/tutorial/tutorial.md

    - Motion
    - Look
    - Sound(?)
    - Events
    - Control
    - Sensing
    - Operators
    - Variables

3. Making programs!(10min)

## Making game(1:50pm - 2:50pm, 60 min)

