# Programming Training

Hello everyone, this is pre-season programming training to anyone who might be interested in programming this upcoming season.


# Expected outcomes
- Download WPILib
- Setup Git/GitHub
- Learn the Basics of Java
- Learn the Basics of Command Based
- Code a robot (without a robot)

# Meeting 1: Getting Started

## Software Installation / Setup 
- Download [WPILib](https://docs.wpilib.org/en/latest/docs/zero-to-robot/step-2/index.html)
- Download GitHub Desktop (Not git-bash (for now) Simplicity is nice) 
- Set up GitHub Accounts
- Setup VSCode (Included with WPILib)
- Get familiar with the VSCode IDE
  - [VSCode in 100 Seconds](https://www.youtube.com/watch?v=KMxo3T_MTvY)
- Basics of Git and best practices
  - 

### Further information / Links
- [GitHub Desktop Installation Guide](https://docs.github.com/en/desktop/installing-and-authenticating-to-github-desktop/installing-github-desktop)


# Meeting 2 - 3: Java
- Learn the basics of Java
  - [3847 Spectrum Intro to Java Slides](https://docs.google.com/presentation/d/1MxjAYEkdW9MVuQUSKM9xFdQ3vQl-1MXcdd2jdfOI_KY/edit?usp=sharing)
- Learn best practices as well when writing code

### Further Information / Links
- [CodeCademy Java](https://www.codecademy.com/learn/learn-java)
- [W3School Java](https://www.w3schools.com/java/)

# Meeting 4: Docs / Parts

## Learn how to navigate different documentation
- WPILib Java Docs (add link later)
- CTRE 
  - [Phoenix 6](https://v6.docs.ctr-electronics.com/en/latest/)
- REV Robotics
  - [REV Software Docs](https://docs.revrobotics.com/sparkmax/software-resources/spark-max-api-information)

## Learn Command Based Framework
- Learn how subsystems and commands work
- Robot Container structure

## Learn what different parts are
- Identify different motors (TalonFX / SparkMAX)
- Basics of the robot control system
  - RoboRIO
  - Encoders
  - CAN
  - etc

### Further Information
- [3847 Intro to FRC Control System](https://docs.google.com/presentation/d/1U8EKEZv5Km__JKcN2SpE7tU8HjkMOnHZUupBr-Zo96M/edit#slide=id.p)
- [3847 Overview of FRC Programming](https://docs.google.com/presentation/d/e/2PACX-1vRC037jwjNSnJN47Sut_juVnw0Ds6HQF1Jrwlx2t-1F6xo2s3G6tx7XU7Q0-xzG7ihGxwnhlGDvChz6/pub?start=false&loop=false&delayms=3000#slide=id.p)



## Learn how to code parts of the control system with WPILib and other tools
- Identify Motors / Encoders
- Get methods for parts (Ex. `getSpeed();` from a TalonFX)
- Set methods for parts (Ex. `setSpeed();` from a TalonFX)
- Etc

# Meeting 5 till: Putting it together 
- Will be assigned a mechanism per member (or however)

## 2022 Rapid React Intake
Control: 
- Xbox Controller

Robot: 
- Pneumatically actuated Intake
  - REV Pneumatic Controller
  - Goal: Make the Pneumatics actuate out when the left bumper button is held
- 2 KrakenX60 Motors
  - CTRE TalonFX Motor Controller
  - Main Goal: Make the Motors spin by setting the speed when the left bumper button is held
    - Optional goal: Make the intake stop when it detects a ball in it

