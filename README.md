# Pi5/PiZero Setup Scripts
Scripts that set up a Raspberry Pi 5 or Pi Zero 2 W as a companion computer for an ArduPilot flight controller. Both install mavlink-router, ZeroTier, Tailscale and iPhone USB tethering. The Pi 5 script also sets up a Quectel LTE modem and an RTSP stream from a USB camera.

*Prerequisites:*

* [ ] Raspberry Pi5/Zero w/Raspberry Pi OS (Desktop or Headless)
* [ ] Active internet connection
* [ ] ArduPilot enabled flight controller
      
## Getting started:

  * Inside the Raspberry Pi run these commands to clone and build the repo and associated libraries:
  
    ```
    sudo apt-get install git
    git clone https://github.com/Overhead-Intelligence/oi-pi-setup-scripts.git    
    cd oi-pi-setup-scripts
    ```
### Getting started cont. Raspberry Pi 5

  ```
    sudo chmod +x oi-pi5-setup.sh
    ./oi-pi5-setup.sh
  ```
  Please Reboot after script finishes
    
### Getting started cont. Raspberry Pi Zero 2W

  ```
    sudo chmod +x oi-pizero-setup.sh
    ./oi-pizero-setup.sh
  ```
  Please Reboot after script finishes
    

  


