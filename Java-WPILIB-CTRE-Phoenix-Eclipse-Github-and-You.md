# Java, WPILib, Eclipse, Github, and You

Getting a WPIlib project created via RobotBuilder, uploaded to github, working in eclipse, and not losing your sanity is tricky.  This documents my forays into getting all of this working simulateously on more than one computer..

Prerequsities:
- Patience
- A decent enough understanding of how WPIlib works so you can make a project in robot builder
- The following installed:
  - Eclipse for Java
  - WPIlib (installed via Eclipse): [Installation instructions](https://wpilib.screenstepslive.com/s/currentCS/m/getting_started/l/599679-installing-eclipse-c-java#installing-the-development-plugins-option-1-online-install)
  - "Phoenix" for the Cross the Road Electronics CAN interface (e.g., using Talon SRX or Pigeon IMU): 
    - [Phoenix Framework (Eclipse stuff)](http://www.ctr-electronics.com/hro.html#product_tabs_technical_resources)
      - Install the newest version of the CTRE Phoenix Framework installer to be able to code CTRE stuff in Eclipse
    - [Firmware files for the TalonSRX/VictorSPX](http://www.ctr-electronics.com/talon-srx.html#product_tabs_technical_resources)
    - [CTRE Software Reference Guide](https://github.com/CrossTheRoadElec/Phoenix-Documentation/blob/master/README.md)
    - [Installing "Phoenix" on your roboRio](https://github.com/CrossTheRoadElec/Phoenix-Documentation#installing-phoenix-framework-onto-your-frc-robot)
    - After I updated WPIlib, I reinstalled the CTRE Phoenix software...  
      - Where are the libraries located after install?  
      - How does Eclipse know where to find them?
      - It's a mystery to everyone.
  - 
  
# Questions:
  - Is it possible to not have the classpath issues in Eclipse after making a new project..?  Or was this just because I updated WPIlib to 2018.2.2 ?
  - Now TalonSRX doesn't work after updating WPIlib?  Do I have to reinstall everything every time?
  - Also, why can's I save files???  Well..  I can now..?
  
# More to come later
