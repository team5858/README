# How to configure your computer for FRC

## Make sure you have python37 or better installed

  - Go to https://www/python.org/downloads/
  - Push the button for "Download Python3.x.x". This downloads the installer. 
  - Run the installer.
  - Add the python scripts directory to your path. You'll need this for `pip3` and `robotpy-installer`. On my machine it is `C:\Users\tophe\appdata\Local\Programs\Python\Python37-32\Scripts`.

At the Windows Command prompt:
```
py


update/install the FRC software on your computer

  - Uninstall the National Instruments software
  - www.ni.com/download/ ... pick the current zip
  - unzip and run
  
# How to update/install the RobotPy libraries

  - pip3 install --upgrade pyfrc
  
# Install the CTRE libs locally (for the simulator)

  - pip3 install -U robotpy-ctre
  - install the CTRE lifeboat exe to configure CAN and succh
  
# Install RobotPy installer (used to flash the RoboRIO)
  - pip3 install robotpy-installer
