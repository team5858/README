# How to reflash the roborio

  - Launch image tool
  - Update firmware
  - Reformat roboRIO
  

# How to program the wifi router (radio) for the current year

https://wpilib.screenstepslive.com/s/currentCS/m/getting_started/l/144986-programming-your-radio

Scroll down to "Download the software" and pick the current ZIP. The ZIP contains the PC executable.

# How to configure your computer for FRC

These steps come from https://robotpy.readthedocs.io/en/stable/index.html

## Make sure you have python37 or better installed

At the Windows Command prompt, make sure the versions are correct:
```
pip3 --version

py --version
```
Do you see Python3.7 or better? If so, skip to the next step. Otherwise:

  - Go to https://www/python.org/downloads/
  - Push the button for "Download Python3.x.x". This downloads the installer. 
  - Run the installer.
  - Add the python scripts directory to your path. You'll need this for `pip3` and `robotpy-installer`. On my machine it is `C:\Users\tophe\appdata\Local\Programs\Python\Python37-32\Scripts`.
  - Close any command prompts and retry the checks above

## Install the FRC Update Suite on your laptop

This gets you the Driver Station and the RoboRIO tool.

If you have the `RoboRIO Imaging Tool` and `FRC Driver Station` on your desktop, then open them and verify the version. If they are correct then skip to the next step. Otherwise:

  - As of this writing, the desirecd version is 19.0
  - Uninstall previous versions of `National Instruments` software
  - Go to  www.ni.com/download/ ... pick the current zip
  - unzip and run
  
## Install or update RobotPy libraries

  - pip3 install --upgrade pyfrc
  - verify the install at the command prompt with the command `robotpy-installer`
  - pip3 install -U robotpy-ctre
  - you might need to download/install the CTRE Lifeboat PC application to configure CAN and run CAN diagnostics

# Pushing RobotPy to the RoboRIO

  - robotpy-installer download-robotpy

  - Connect your RoboRIO and PC to the router  
  - robotpy-installer install-robotpy
  - robotpy-installer download-opkg python37-robotpy-ctre
  - robotpy-installer install-opkg python37-robotpy-ctre
  
