# KlipperConfigurations
My personal Klipper configuration files for my 3d printer(s)

## Klipper Screen
Since I am using DSI I need the following...
```cli
sudo wget https://datasheets.raspberrypi.com/cmio/dt-blob-disp1-cam1.bin -O /boot/dt-blob.bin
```
### Kiauh
💾 Download and use KIAUH

📢 Disclaimer: Usage of this script happens at your own risk!

Step 1:
    To download this script, it is necessary to have git installed. If you don't have git already installed, or if you are unsure, run the following command:
```
sudo apt-get update && sudo apt-get install git -y
```
Step 2:
    Once git is installed, use the following command to download KIAUH into your home-directory:
```
cd ~ && git clone https://github.com/dw-0/kiauh.git
```
Step 3:
    Finally, start KIAUH by running the next command:
```
./kiauh/kiauh.sh
```
Step 4:
    You should now find yourself in the main menu of KIAUH. You will see several actions to choose from depending on what you want to do. To choose an action, simply type the corresponding number into the "Perform action" prompt and confirm by hitting ENTER.

## KAMP
```
 cd
 
 git clone https://github.com/kyleisah/Klipper-Adaptive-Meshing-Purging.git
 
 ln -s ~/Klipper-Adaptive-Meshing-Purging/Configuration printer_data/config/KAMP

 cp ~/Klipper-Adaptive-Meshing-Purging/Configuration/KAMP_Settings.cfg ~/printer_data/config/KAMP_Settings.cfg
```
