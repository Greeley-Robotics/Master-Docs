# Horace Greeley FRC Software Department

# 

# Slack

We will be using Slack to communicate, a more professional version of Discord.

Please sign up and join the Greeley Robotics slack community: [Link](https://join.slack.com/t/greeleyrobotics/shared_invite/zt-2c4vo9oyv-q0DLAcy~X5aSNY3IfWu11Q)

# 

# Github

Github is used for version control and collaboration. It lets you and others work together on projects from anywhere.

1. Create a Github account

2. Signup for the Github Student Developer Pack

1. [https://education.github.com/pack](https://education.github.com/pack)

3. If you are not in the Greeley Robotics organization([link](https://github.com/Greeley-Robotics)) message me on Slack and provide your Github username

For more information on Github, check out their guide: [https://docs.github.com/en/get-started/quickstart/hello-world](https://docs.github.com/en/get-started/quickstart/hello-world)

# 

# Intro to Git

If you are using Apple or Linux, you already have it pre downloaded on your computer.

![](/images/Svs_Image_1.png)

# 

# 

# 

# VSCode Installation

Visual Studio Code is one of the most popular code editors that supports debugging, task running, and version control.

## Download VSCode

1. Go to [https://code.visualstudio.com/](https://code.visualstudio.com/) and scroll down

2. Choose option compatible with your computer

![](/images/kz5_Image_2.png)

## Install Java

There are two options

1. More Consistent Option - Install Coding Pack

1. Skip Download VSCode

2. Less Consistent Option - Install Java Extension

2. Do this if you already have VSCode installed on your computer

3. Go to extensions in VSCode

4. Search for ?Extension Pack for Java?, should be from Microsoft

5. Install and Reload

[https://code.visualstudio.com/docs/languages/java](https://code.visualstudio.com/docs/languages/java)

For option 2, if Java doesn?t run, the solution is to download the Java JDK.

[https://www.oracle.com/java/technological logies/downloads/#jdk21-windows](https://www.oracle.com/java/technologies/downloads/#jdk21-windows)

Make sure to choose the compatible option for your device.

After installation, restart VSCode and Java should work.

# Collaborative Coding

## VSCode Live Share

1. Go to extensions in VSCode

2. Search for Live Share and install

![](/images/rvH_Image_3.png)

There are two options. Either to join or share a live session.

1. Join: click on shared link

2. Share: click on share button, click invite participants, and share the link

## Github

VSCode comes built in with Github integration.

1. Click on Clone Repository

2. Select Clone from Github

3. Popup message, select Allow

4. Authorize VSCode for your account

![](/images/L1k_Image_4.png)

# FRC Game Tools

FRC Game Tools is a software bundle that includes the FRC Driver Station and FRC Utilities. These components are required for FRC teams to configure and control robots and communicate with the field.

Install Link: [https://www.ni.com/en/support/downloads/drivers/download.frc-game-tools.html#479842](https://www.ni.com/en/support/downloads/drivers/download.frc-game-tools.html#479842)

1. Download offline or online version

2. After download navigate to the NI Installer

3. Click on all the agreements and install

4. Create an NI account to access tool

# WPILib Installation

[https://docs.wpilib.org/en/stable/docs/zero-to-robot/step-2/index.html](https://docs.wpilib.org/en/stable/docs/zero-to-robot/step-2/index.html)

## What is WPILib?

[https://docs.wpilib.org/en/stable/docs/software/what-is-wpilib.html](https://docs.wpilib.org/en/stable/docs/software/what-is-wpilib.html)

The WPI Robotics Library (WPILib) is the standard software library provided for teams to write code for their FRC? robots.

Languages: WPILibJ for Java, and WPILibC for C++

Prerequisites: Windows 10 & 11, 64 bit,

macOS 11 or higher, both Intel and Arm,

Ubuntu 22.04, 64 bit

## How to install?

1. Download VSCode

2. Navigate to the extensions tab on the left side

3. Search and download WPlLib

4. Refresh/restart VSCode and you should see an icon on the top right

**If the above does not work, you must install the WPILib Installer. It includes a VSCode preloaded with the Java JDK and WPILib.**

[https://docs.wpilib.org/en/stable/docs/zero-to-robot/step-2/wpilib-setup.html](https://docs.wpilib.org/en/stable/docs/zero-to-robot/step-2/wpilib-setup.html)

# 

# 

# 

# 

# WPlLib Commands

In VSCode, you can use the keyboard command ?Command+Shift+P?(macOS) or ?Ctrl+Shift+P?(Windows) to access the command palette. Here are some important WPILib commands.

- **WPILib: Build Robot Code** - Builds open project using GradleRIO

- **WPILib: Create a new project** - Create a new robot project

- **WPILib: Cancel currently running tasks** - Cancel any tasks the WPILib extension is currently running

- **WPILib: Change Auto Save On Deploy Setting** - Change whether files are saved automatically when doing a Deploy. This defaults to Enabled.

- **WPILib: Change Auto Start RioLog on Deploy Setting** - Change whether RioLog starts automatically on deploy. This defaults to Enabled.

- **WPILib: Change Desktop Support Enabled Setting** - Change whether building robot code on Desktop is enabled. Enable this for test and simulation purposes. This defaults to Desktop Support off.

- **WPILib: Change Language Setting** - Change whether the currently open project is C++ or Java.

- **WPILib: Change Run Commands Except Deploy/Debug in Offline Mode Setting** - Change whether GradleRIO is running in Online Mode for commands other then deploy/debug (will attempt to automatically pull dependencies from online). Defaults to enabled (online mode).

- **WPILib: Change Run Deploy/Debug Command in Offline Mode Setting** - Change whether GradleRIO is running in Online Mode for deploy/debug (will attempt to automatically pull dependencies from online). Defaults to disabled (offline mode).

- **WPILib: Change Select Default Simulate Extension Setting** - Change whether simulation extensions are enabled by default (all simulation extensions defined in `build.gradle` will be enabled)

- **WPILib: Change Skip Tests On Deploy Setting** - Change whether to skip tests on deploy. Defaults to disabled (tests are run on deploy)

- **WPILib: Change Stop Simulation on Entry Setting** - Change whether to stop robot code on entry when running simulation. Defaults to disabled (don?t stop on entry).

- **WPILib: Change Use WinDbg Preview (From Store) as Windows Debugger Setting** - Change whether to use the VS Code debugger or WinDbg Preview (from Windows Store).

- **WPILib: Check for WPILib Updates** - Check for an update to the WPILib GradleRIO version for the project. This does not update the Visual Studio Code extension, tools, or offline dependencies. Users are strongly recommended to use the [offline wpilib installer](https://docs.wpilib.org/en/stable/docs/zero-to-robot/step-2/wpilib-setup.html)

- **WPILib: Debug Robot Code** - Build and deploy robot code to roboRIO in debug mode and start debugging

- **WPILib: Deploy Robot Code** - Build and deploy robot code to roboRIO

- **WPILib: Hardware Sim Robot Code** - This builds the current robot code project on your PC and starts it running in simulation using hardware attached to the comupter rather then pure software simulation. Requires vendor support.

- **WPILib: Import a WPILib 2020/2021/2022 Gradle Project** - Open a wizard to help you create a new project from a existing VS Code Gradle project from 2020-2022. Further documentation is at [importing gradle project](https://docs.wpilib.org/en/stable/docs/software/vscode-overview/importing-gradle-project.html)

- **WPILib: Install tools from GradleRIO** - Install the WPILib Java tools (e.g. SmartDashboard, Shuffleboard, etc.). Note that this is done by default by the offline installer

- **WPILib: Manage Vendor Libraries** - Install/update 3rd party libraries

- **WPILib: Open API Documentation** - Opens either the WPILib Javadocs or C++ Doxygen documentation

- **WPILib: Open Project Information** - Opens a widget with project information (Project version, extension version, etc.)

- **WPILib: Open WPILib Command Palette** - This command is used to open a WPILib Command Palette (equivalent of hitting `Ctrl+Shift+P` and typing `WPILib`)

- **WPILib: Open WPILib Help** - This opens a simple page which links to the WPILib documentation (this site)

- **WPILib: Reset Ask for WPILib Updates Flag**- This will clear the flag on the current project, allowing you to re-prompt to update a project to the latest WPILib version if you previously chose to not update.

- **WPILib: Run a command in Gradle** - This lets you run an arbitrary command in the GradleRIO command environment

- **WPILib: Set Team Number** - Used to modify the team number associated with a project. This is only needed if you need to change the team number from the one initially specified when creating the project.

- **WPILib: Set VS Code Java Home to FRC Home** - Set the VS Code Java Home variable to point to the Java Home discovered by the FRC extension. This is needed if not using the offline installer to make sure the intellisense settings are in sync with the WPILib build settings.

- **WPILib: Show Log Folder** - Shows the folder where the WPILib extension stores internal logs. This may be useful when debugging/reporting an extension issue to the WPILib developers

- **WPILib: Simulate Robot Code** - This builds the current robot code project on your PC and starts it running in simulation. This requires Desktop Support to be set to Enabled.

- **WPILib: Start RioLog** - This starts the RioLog display used to view console output from a robot program

- **WPILib: Start Tool** - This allows you to launch WPILib tools (e.g. SmartDashboard, Shuffleboard, etc.) from inside VS Code

- **WPILib: Test Robot Code** - This builds the current robot code project and runs any created tests. This requires Desktop Support to be set to Enabled.

# 

# Base Class

To start a project using one of the WPILib robot program templates, users must first choose a base class for their robot. Users subclass these base classes to create their primary `Robot` class, which controls the main flow of the robot program. 

The recommended base class is *TimedRobot.*

* The *`TimedRobot`* class is the base class recommended for most users. It provides control of the robot program through a collection of *`init()`*, *`periodic()`*, and *`exit()`* methods, which are called by WPILib during specific robot states (e.g. autonomous or teleoperated). During these calls, your code typically polls each input device and acts according to the data it receives. For instance, you would typically determine the position of the joystick and state of the joystick buttons on each call and act accordingly. The *`TimedRobot`* class also provides an example of retrieving autonomous routines through SendableChooser*

```
import edu.wpi.first.wpilibj.TimedRobot;/** * The VM is configured to automatically run this class, and to call the functions corresponding to * each mode, as described in the TimedRobot documentation. If you change the name of this class or * the package after creating this project, you must also update the build.gradle file in the * project. */public class Robot extends TimedRobot {    /**     * This function is run when the robot is first started up and should be used for any     * initialization code.     */    @Override    public void robotInit() {}    @Override    public void robotPeriodic() {}    @Override    public void autonomousInit() {}    @Override    public void autonomousPeriodic() {}    @Override    public void teleopInit() {}    @Override    public void teleopPeriodic() {}    @Override    public void disabledInit() {}    @Override    public void disabledPeriodic() {}    @Override    public void testInit() {}    @Override    public void testPeriodic() {}    @Override    public void simulationInit() {}    @Override    public void simulationPeriodic() {}}
```
Periodic methods are called every 20 ms by default. This can be changed by calling the superclass constructor with the new desired update rate.

```
public Robot() {  super(0.03); // Periodic methods will now be called every 30 ms.}
```
# Creating New WPlLib Project

1. Go to VSCode and open command palette using ?Command+Shift+P? or ?Ctrl+Shift+P?

![](/images/x2A_Image_5.png)

3. You will see a ?New Project Creator Window?

1. **Project Type**: The kind of project we wish to create. This can be an example project, or one of the project templates provided by WPILib. Templates exist for each of the robot base classes. Additionally, a template exists for [Command-based](https://docs.wpilib.org/en/stable/docs/software/commandbased/what-is-command-based.html#what-is-command-based-programming) projects, which are built on the TimedRobot base class but include a number of additional features - this type of robot program is highly recommended for new teams.

2. **Language**: Language (C++ or Java) used for project

3. **Base Folder**: Specifies the type of template that will be used.

4. **Project Location**: Folder in which the robot project will be located.

5. **Project Name**: The name of the robot project. Also specifies the name that the project folder will be given if the Create New Folder box is checked.

6. **Create a New Folder**: If this is checked, a new folder will be created to hold the project within the previously-specified folder. If it is not checked, the project will be located directly in the previously-specified folder. An error will be thrown if the folder is not empty and this is not checked.

7. **Team Number**: The team number for the project, which will be used for package names within the project and to locate the robot when deploying code.

8. **Enable Desktop Support**: Enables unit test and simulation. While WPILib supports this, third party software libraries may not. If libraries do not support desktop, then your code may not compile or may crash. It should be left unchecked unless unit testing or simulation is needed and all libraries support it.

![](/images/0Mj_Image_6.png)

# 

# Installing 3rd Party Libraries

What are vendor dependencies?

Vendor Dependencies are a way for vendors, ex) REV, to add their software library to robots.This library can control motor controllers and other devices. Vendor dependencies are installed on a per-project basis. A [JSON](https://docs.wpilib.org/en/stable/docs/software/frc-glossary.html#term-JSON) file describing the vendor library is installed on your system to `~/wpilib/YYYY/vendordeps` (where YYYY is the year and ~ is `C:\Users\Public` on Windows).

Installation

1. Open command palette and type WPlLib, or click on the WPILib Icon on top right

2. Type ?Manage Vendor Libraries?, and select it

3. Select desired libraries to add and hit OK

# 

# Building and Deploying Code

Robot projects must be compiled (?built?) and deployed in order to run on the roboRIO. Since the code is not compiled natively on the robot controller, this is known as ?cross-compilation.?

To build and deploy a robot project, do one of:

1. Open the Command Palette and enter/select ?Build Robot Code?

2. Open the shortcut menu indicated by the ellipses in the top right corner of the VS Code window and select ?Build Robot Code?

3. Right-click on the build.gradle file in the project hierarchy and select ?Build Robot Code?

If successful, we will see a ?Build Successful? message (1) and the RioLog will open with the console output from the robot program as it runs (2).

# 

# Console Output

The two ways of looking at console output are are through the Console Viewer in the FRC Driver Station and the Rioplug plugin in VSCode

## Console Viewer

![](/images/yBi_Image_7.png)

To open Console Viewer, first open the FRC? Driver Station. Then, click on the gear at the top of the message viewer window (1) and select ?View Console?.

![](/images/spV_Image_8.png)

## Rioplug Plugin

?Ctrl+Shift+P? and type *WPILib: Start Riolog*

![](/images/QjE_Image_9.png)

- **Pause/Resume Display** - This will pause/resume the display. 

- **Discard/Accept Incoming** - This will toggle whether to accept new packets. When packets are being discarded the display will be paused and all packets received will be discarded. Clicking the button again will resume receiving packets.

- **Clear** - This will clear the current contents of the display.

- **Don?t Show/Show Prints** - This shows or hides messages categorized as print statements

- **Switch to Viewer** - This switches to viewer for saved log files

- **Don?t Show/Show Warnings** - This shows or hides messages categorized as warnings

- **Disconnect/Reconnect** - This disconnects or reconnects to the console stream

- **Show/Don?t Show Timestamps** - Shows or hides timestamps on messages in the window

- **Save Log** - Copies the log contents into a file you can save and view or open later with the RioLog viewer (see Switch to Viewer above)

- **Set Team Number** - Sets the team number of the roboRIO to connect to the console stream on, set automatically if RioLog is launched by the deploy process

# Debugging

Press `Ctrl+Shift+P` and type `WPILib` or click on the **WPILib Menu Item** to open the Command palette with WPILib pre-populated. Type Debug and select the Debug Robot Code menu item to start debugging. The code will download to the roboRIO and begin debugging.

# ShuffleBoard

ShuffleBoard is a dashboard for FRC C++ and Java programs.

![](/images/mMc_Image_10.png)

1. **Sources area**: Here are data sources from which you can choose values from NetworkTables, a publish-subscribe messaging system to communicate data between programs, or other sources to display by dragging a value into one of the tabs

2. **Tab panes**: This is where your data is displayed from the robot or other sources. In this example it is Test-mode subsystems that are shown here in the LiveWindow tab. This area can show any number of tabbed windows, and each window has its own set of properties like grid size and auto-populate.

3. **Record/playback controls**: set of media-like controls where you can playback the current session to see historical data

## Start Shuffleboard

![](/images/Hlv_Image_11.png)

2 Best Ways to start ShuffleBoard:

1. You can automatically start it when the Driver Station starts by setting the ?Dashboard Type? to Shuffleboard in the settings tab

2. You can start from with Visual Studio Code by pressing Ctrl+Shift+P and type ?WPILib? or click the WPILib logo in the top right to launch the WPILib Command Palette. Select Start Tool, then select Shuffleboard.

## Get Robot Data on Dashboard

Ex) See a field displayed with the label ?Joystick X value? and a value of the X value of the joystick. Each time this line of code is executed, a new joystick value will be sent to Shuffleboard

```
SmartDashboard.putNumber("Joystick X value", joystick1.getX());
```
Often debugging or monitoring the status of a robot involves writing a number of values to the console and watching them stream by. With Shuffleboard you can put values to a GUI that is automatically constructed based on your program. As values are updated, the corresponding GUI element changes value - there is no need to try to catch numbers streaming by on the screen.

```
protected void execute() {    SmartDashboard.putBoolean("Bridge Limit", bridgeTipper.atBridge());    SmartDashboard.putNumber("Bridge Angle", bridgeTipper.getPosition());    SmartDashboard.putNumber("Swerve Angle", drivetrain.getSwerveAngle());    SmartDashboard.putNumber("Left Drive Encoder", drivetrain.getLeftEncoder());    SmartDashboard.putNumber("Right Drive Encoder", drivetrain.getRightEncoder());    SmartDashboard.putNumber("Turret Pot", turret.getCurrentAngle());    SmartDashboard.putNumber("Turret Pot Voltage", turret.getAverageVoltage());    SmartDashboard.putNumber("RPM", shooter.getRPM());}
```
![](/images/mhu_Image_12.png)

- Numeric types such as char, int, long, float or double call SmartDashboard.putNumber(?dashboard-name?, value).

- String types call SmartDashboard.putString(?dashboard-name?, value)

- Boolean types call SmartDashboard.putBoolean(?dashboard-name?, value)

## Camera Stream

![](/images/47z_Image_13.png)

## Creating a graph

![](/images/JaH_Image_14.png)

Recordings

![](/images/o28_Image_15.png)

Play/load Recordings

![](/images/jFJ_Image_16.png)

Creating and Using Tabs

Creating

```
ShuffleboardTab tab = Shuffleboard.getTab("Tab Title");
```
Opening

```
Shuffleboard.selectTab("Tab Title");
```
Cons

- Not saved in the Shuffleboard save file

- No support for autopopulation

- Users are expected to specify the tab contents in their robot program

- Have a special color to differentiate from normal tabs

## Sending Data to Tabs

```
Shuffleboard.getTab("Numbers").add("Pi", 3.14);
```
Updating

```
class VisionCalculator {   private ShuffleboardTab tab = Shuffleboard.getTab("Vision");   private NetworkTableEntry distanceEntry =       tab.add("Distance to target", 0)          .getEntry();   public void calculate() {     double distance = ...;     distanceEntry.setDouble(distance);   } }
Call getEntry() after defining the value, then update it when needed or in a periodic function


Retrieving Data
class DriveBase extends Subsystem {
   private ShuffleboardTab tab = Shuffleboard.getTab("Drive");
   private NetworkTableEntry maxSpeed =
       tab.add("Max Speed", 1)
          .getEntry();

   private DifferentialDrive robotDrive = ...;

   public void drive(double left, double right) {
     // Retrieve the maximum speed from the dashboard
     double max = maxSpeed.getDouble(1.0);
     robotDrive.tankDrive(left * max, right * max);
   }
}
.getDouble() gets the value at the Max Speed widget.

```
## Specify Widget Properties

`Shuffleboard.``getTab``(``"Drive"``)`

`    ``.``add``(``"Max Speed"``,`` ``1``)`

`    ``.``withWidget``(BuiltInWidgets.``kNumberSlider``)`

`    ``.``withProperties``(Map.``of``(``"min"``,`` ``0``,`` ``"max"``,`` ``1``))`` ``// specify widget properties here`

`    ``.``getEntry``();`

Using .withProperties(), we can specify the specifics of the widget. In this case, it is a slider. The default slider is -1 to 1, which may cause problems, so we can change it to 0 to 1.

# Telemetry

## What is Telemetry?

Telemetry is the process of collecting, transmitting, and analyzing data from remote or inaccessible sources. Recording and viewing telemetry data is a crucial part of the engineering process - accurate telemetry data helps you tune your robot to perform optimally, and is indispensable for debugging your robot when it fails to perform as expected.

Advantages over dashboards:

1. Recording data on the robot means more data can be collected because of the lessened presence of bandwidth limitations

2. All the recorded data can be very accurately timestamped

3. WPILib has integrated support for on-robot recording of telemetry data via the DataLogManager and DataLog classes and provides a tool for downloading data log files and converting them to CSV.

## Sendables

The *Sendable* interface is able to register value listeners that automatically send data to the dashboard - and, in some cases, receive values back. Many WPILib classes (such as [Commands](https://docs.wpilib.org/en/stable/docs/software/dashboards/shuffleboard/advanced-usage/shuffleboard-commands-subsystems.html#commands-and-subsystems)) already implement Sendable, and so can be sent to the dashboard without any user modification. The Sendable interface contains only one method: initSendable. Implementing classes override this method to perform the binding of in-code data values to structured [JSON](https://docs.wpilib.org/en/stable/docs/software/frc-glossary.html#term-JSON) data, which is then automatically sent to the robot dashboard via NetworkTables. 

To send a Sendable object to your dashboard: use *putData* method:

`SmartDashboard.``putData``(``"Arm PID"``,`` ``armPIDController);`

## Data Logs

By default, no data is recorded on the robot. The *DataLogManager* class provides a convenient wrapper around the lower-level *DataLog* class for on-robot recording of telemetry data into data logs.

Data Logs are similar to Network Tables, but their data types cannot be changed once created, they are unidirectional(*DataLog* can only write, *DataLogReader* can only read), and a series of timestamped records.

It provides automatic data log file management.  It automatically cleans up old files when disk space is low and renames the file based either on current date/time or competition match number. The data file will be saved to a USB flash drive if one is attached, or to /home/lvuser otherwise.

Log files are initially named *FRC_TBD_{random}.wpilog* until the DS connects. After the DS(Driver Station) connects, the log file is renamed to *FRC_yyyyMMdd_HHmmss.wpilog* (where the date/time is UTC). If the FMS is connected and provides a match number, the log file is renamed to *FRC_yyyyMMdd_HHmmss_{event}_{match}.wpilog*.

On startup, all existing log files where a DS has not been connected will be deleted. If there is less than 50 MB of free space on the target storage, FRC_ log files are deleted (oldest to newest) until there is 50 MB free OR there are 10 files remaining.

Will record all Network Table changes to datalog:

`import`` ``edu.wpi.first.wpilibj.DataLogManager``;`

```
// Starts recording to data log
`DataLogManager.``start``();`

```

DataLogManager provides a convenience function (DataLogManager.log()) for logging of text messages to the messages entry in the data log. The message is also printed to standard output, so this can be a replacement for System.out.println().

DataLogManager also records the current roboRIO system time (in UTC) to the data log every ~5 seconds to the systemTime entry in the data log. This can be used to (roughly) synchronize the data log with other records such as DS logs or match video.

Logging Joystick Data

By default, joystick data isn?t logged. The code below logs iit:

`import`` ``edu.wpi.first.wpilibj.DataLogManager``;`

`import`` ``edu.wpi.first.wpilibj.DriverStation``;`

```
// Starts recording to data log
`DataLogManager.``start``();`


// Record both DS control and joystick data
`DriverStation.``startDataLog``(DataLogManager.``getLog``());`


// (alternatively) Record only DS control data
`DriverStation.``startDataLog``(DataLogManager.``getLog``(),`` ``false``);`

```

Custom Data Logging

`import`` ``edu.wpi.first.util.datalog.BooleanLogEntry``;`

`import`` ``edu.wpi.first.util.datalog.DataLog``;`

`import`` ``edu.wpi.first.util.datalog.DoubleLogEntry``;`

`import`` ``edu.wpi.first.util.datalog.StringLogEntry``;`

`import`` ``edu.wpi.first.wpilibj.DataLogManager``;`

`BooleanLogEntry`` ``myBooleanLog;`

`DoubleLogEntry`` ``myDoubleLog;`

`StringLogEntry`` ``myStringLog;`

`public`` ``void`` ``robotInit``()`` ``{`

`  ``// Starts recording to data log`

`  ``DataLogManager.``start``();`

`  ``// Set up custom log entries`

`  ``DataLog`` ``log`` ``=`` ``DataLogManager.``getLog``();`

`  ``myBooleanLog`` ``=`` ``new`` ``BooleanLogEntry(log,`` ``"/my/boolean"``);`

`  ``myDoubleLog`` ``=`` ``new`` ``DoubleLogEntry(log,`` ``"/my/double"``);`

`  ``myStringLog`` ``=`` ``new`` ``StringLogEntry(log,`` ``"/my/string"``);`

```
}

`public`` ``void`` ``teleopPeriodic``()`` ``{`

`  ``if`` ``(...)`` ``{`

`    ``// Only log when necessary`

`    ``myBooleanLog.``append``(``true``);`

`    ``myDoubleLog.``append``(``3.5``);`

`    ``myStringLog.``append``(``"wow!"``);`

`  ``}`

}
```

Download Datalogs

For when the data logs are not stored on USB drive and on roboRIO integrated flash memory.

To facilitate this, the DataLogTool desktop application integrates a SFTP client for downloading data log files from a network device (e.g. roboRIO or coprocessor) to the local computer.

This process consists of four steps:

1. Connect to roboRIO or coprocessor

2. Navigate to remote directory and select what files to download

3. Select download folder

4. Download files and optionally delete remote files after downloading

![](/images/t80_Image_17.png)

![](/images/2Eo_Image_18.png)

![](/images/E0j_Image_19.png)

Convert Data Logs to CSV

Data logs are binary, so converting them to CSV will improve readability.

![](/images/9qo_Image_20.png)

## Third Party Telemetry Libraries

- [AdvantageScope](https://github.com/Mechanical-Advantage/AdvantageScope): Data visualization tool for [NetworkTables](https://docs.wpilib.org/en/stable/docs/software/networktables/networktables-intro.html#what-is-networktables), [WPILib data logs](https://docs.wpilib.org/en/stable/docs/software/telemetry/datalog.html#on-robot-telemetry-recording-into-data-logs), and [Driver Station logs](https://docs.wpilib.org/en/stable/docs/software/driverstation/driver-station-log-viewer.html#driver-station-log-file-viewer).

- [AdvantageKit](https://github.com/Mechanical-Advantage/AdvantageKit) (Java only): ?Log everything?-based logging framework with hooks for replaying logged data in [simulation](https://docs.wpilib.org/en/stable/docs/software/wpilib-tools/robot-simulation/introduction.html#introduction-to-robot-simulation).

- [Oblog](https://github.com/Oblarg/Oblog) (Java only): Minimalistic annotation-based API for Shuffleboard (or plain NetworkTables) telemetry.

# Hardware APIs

## Motors

Motor Controllers are responsible for making your motors and therefore your robot move. These are the legal controllers as of 2023.

- DMC 60/DMC 60c Motor Controller (P/N: 410-334-1, 410-334-2)

- Jaguar Motor Controller (P/N: MDL-BDC, MDL-BDC24, and 217-3367) connected to PWM only

- Nidec Dynamo BLDC Motor with Controller to control integral actuator only (P/N 840205-000, am-3740)

- SD540 Motor Controller (P/N: SD540x1, SD540x2, SD540x4, SD540Bx1, SD540Bx2, SD540Bx4, SD540C)

- Spark Motor Controller (P/N: REV-11-1200, am-4260)

- Spark MAX Motor Controller (P/N: REV-11-2158, am-4261)

- Talon FX Motor Controller (P/N: 217-6515, 19-708850, am-6515, am-6515_Short) for controlling integral Falcon 500 only

- Talon Motor Controller (P/N: CTRE_Talon, CTRE_Talon_SR, and am-2195)

- Talon SRX Motor Controller (P/N: 217-8080, am-2854, 14-838288)

- Venom Motor with Controller (P/N BDC-10001) for controlling integral motor only?

- Victor 884 Motor Controller (P/N: VICTOR-884-12/12)

- Victor 888 Motor Controller (P/N: 217-2769)

- Victor SP Motor Controller (P/N: 217-9090, am-2855, 14-868380)

- Victor SPX Motor Controller (P/N: 217-9191, 17-868388, am-3748)

Motor controllers are either CAN or PWM. A CAN controller can send more detailed status information back to the roboRIO, while a PWM controller can only be set to a single value. PWM and CAN controllers can be controlled using the same methods. All approved motor controllers have WPI classes provided for them.

`Spark`` ``spark`` ``=`` ``new`` ``Spark(``0``);`` ``// 0 is the RIO PWM port this is connected to`

`spark.``set``(``-0.75``);`` ``// the % output of the motor, between -1 and 1`

`VictorSP`` ``victor`` ``=`` ``new`` ``VictorSP(``0``);`` ``// 0 is the RIO PWM port this is connected to`

`victor.``set``(``0.6``);`` ``// the % output of the motor, between -1 and 1`

## Pulse Width Modification(PWM)

PWM can refer to both the input signal and method the controller uses to control motor speed. To do so, the controller must vary the perceived input voltage of the motor. The controller switches the full input voltage on and off very quickly.

Controllers signaling for input involves signals with a period of either 5ms or 10ms and a midpoint pulse width of 1.5ms.

Raw and Scaled Values

In general, all of the motor controller classes in WPILib take a scaled -1.0 to 1.0 value as the output to an actuator. The PWM module in the FPGA on the roboRIO is capable of generating PWM signals with periods of 5, 10, or 20ms and can vary the pulse width in 2000 steps of ~.001ms each around the midpoint (1000 steps in each direction around the midpoint). The raw values sent to this module are in this 0-2000 range with 0 being a special case which holds the signal low (disabled). The class for each motor controller contains information about what the typical bound values (min, max and each side of the deadband) are as well as the typical midpoint. WPILib can then use these values to map the scaled value into the proper range for the motor controller. This allows for the code to switch seamlessly between different types of controllers and abstracts out the details of the specific signaling.

Motor Calibration

The values WPILib uses for scaling are approximate based on measurement of a number of samples of each controller type. Due to a variety of factors, the timing of an individual motor controller may vary slightly. In order to definitively eliminate ?humming? (midpoint signal interpreted as slight movement in one direction) and drive the controller all the way to each extreme, calibrating the controllers is still recommended. In general, the calibration procedure for each controller involves putting the controller into calibration mode then driving the input signal to each extreme, then back to the midpoint.

## Motor Controls

Inversions

The right side of drivetrains are not inverted by default. The code below does so for a PWMSparkMax controller:

`PWMSparkMax`` ``m_motorRight`` ``=`` ``new`` ``PWMSparkMax(``0``);`

```
@Override
`public`` ``void`` ``robotInit``()`` ``{`

`   ``m_motorRight.``setInverted``(``true``);`

}
```

Squaring Inputs

When driving robots, it is often desirable to manipulate the joystick inputs such that the robot has finer control at low speeds while still using the full output range. One way to accomplish this is by squaring the joystick input, then reapplying the sign. By default the Differential Drive class will square the inputs. If this is not desired (e.g. if passing values in from a PIDController), use one of the drive methods with the squaredInputs parameter and set it to false.

Input Deadbands

By default, the Differential Drive class applies an input deadband of 0.02. This means that input values with a magnitude below 0.02 (after any squaring as described above) will be set to 0. In most cases these small inputs result from imperfect joystick centering and are not sufficient to cause drivetrain movement, the deadband helps reduce unnecessary motor heating that may result from applying these small values to the drivetrain. To change the deadband, use the setDeadband() method.

Maximum Output

Sometimes drivers feel that their drivetrain is driving too fast and want to limit the output. This can be accomplished with the setMaxOutput() method. This maximum output is multiplied by the result of the previous drive functions like deadband and squared inputs.

Motor Safety

These mechanisms are used as ?watchdogs?, to disable mechanisms that may potentially be harmful to themselves, the robot, people, or surroundings. Examples of mechanisms that should be Motor Safety Enabled are drive trains and arms. By default Differential Drive and Mecanum Drive objects have it enabled.

The Motor Safety feature operates by maintaining a timer that tracks how long it has been since the feed() method has been called for that actuator. Code in the Driver Station class initiates a comparison of these timers to the timeout values for any actuator with safety enabled every 5 received packets (100ms nominal). The set() methods of each motor controller class and the set() and setAngle() methods of the servo class call feed() to indicate that the output of the actuator has been updated.

`exampleJaguar.``setSafetyEnabled``(``true``);`

`exampleJaguar.``setSafetyEnabled``(``false``);`

`exampleJaguar.``setExpiration``(``.1``);`

`exampleJaguar.``feed``()`

Axis Conventions

Drive classes use NWU(North-West-Up). The positive X axis points ahead, the positive Y axis points left, and the positive Z axis points up.

Joysticks use NEU(North-East-Down). The positive X axis points ahead, the positive Y axis points right, and the positive Z axis points down.

Using Differential Drive

Method provided for control of ?skid-steer? and ?west coast? drivetrains, such as the kit of parts from registration. Initializing a Differential Drive: 

`public`` ``class`` ``Robot`` ``{`

`    ``Spark`` ``m_left`` ``=`` ``new`` ``Spark(``1``);`

`    ``Spark`` ``m_right`` ``=`` ``new`` ``Spark(``2``);`

`    ``DifferentialDrive`` ``m_drive`` ``=`` ``new`` ``DifferentialDrive(m_left,`` ``m_right);`

`    ``public`` ``void`` ``robotInit``()`` ``{`

`        ``m_left.``setInverted``(``true``);`` ``// if you want to invert motor outputs, you must do so here`

`    ``}`

Multi-Motor Differential Drive with Motor Controller Groups

In order to use multiple motors, each side has to be collected in a single *MotorController*, using the *MotorControllerGroup* class. To use even more motors, create more controller instances and pass to MotorControllerGroup constructor. 4 motor, 2 per side drivetrain: 

`public`` ``class`` ``Robot`` ``{`

`    ``Spark`` ``m_frontLeft`` ``=`` ``new`` ``Spark(``1``);`

`    ``Spark`` ``m_rearLeft`` ``=`` ``new`` ``Spark(``2``);`

`    ``MotorControllerGroup`` ``m_left`` ``=`` ``new`` ``MotorControllerGroup(m_frontLeft,`` ``m_rearLeft);`

`    ``Spark`` ``m_frontRight`` ``=`` ``new`` ``Spark(``3``);`

`    ``Spark`` ``m_rearRight`` ``=`` ``new`` ``Spark(``4``);`

`    ``MotorControllerGroup`` ``m_right`` ``=`` ``new`` ``MotorControllerGroup(m_frontRight,`` ``m_rearRight);`

`    ``DifferentialDrive`` ``m_drive`` ``=`` ``new`` ``DifferentialDrive(m_left,`` ``m_right);`

`    ``public`` ``void`` ``robotInit``()`` ``{`

`        ``m_left.``setInverted``(``true``);`` ``// if you want to invert the entire side you can do so here`

`    ``}`

Drive Modes

The three default modes

- Tank Drive, which controls the left and right side independently

- Arcade Drive, which controls a forward and turn speed

- Curvature Drive, a subset of Arcade Drive, which makes your robot handle like a car with constant-curvature turns.

`public`` ``void`` ``teleopPeriodic``()`` ``{`

`    ``// Tank drive with a given left and right rates`

`    ``myDrive.``tankDrive``(``-``leftStick.``getY``(),`` ``-``rightStick.``getY``());`

`    ``// Arcade drive with a given forward and turn rate`

`    ``myDrive.``arcadeDrive``(``-``driveStick.``getY``(),`` ``-``driveStick.``getX``());`

`    ``// Curvature drive with a given forward and turn rate, as well as a button for turning in-place.`

`    ``myDrive.``curvatureDrive``(``-``driveStick.``getY``(),`` ``-``driveStick.``getX``(),`` ``driveStick.``getButton``(``1``));`

```
}










# 

# 

# 

# 

# 

# 

# 

# 

# 

# 

# 

# 

# 

# 

# 

# 

# 

# 

# 

# 

# 

# Programming

```

## Git Version Control

Git is a Distributed Version Control System used for tracking changes in code. It allows for separation of testing environments into different branches, ability to manage different commits, etc.

Download links:

- [Windows](https://git-scm.com/download/win)

- [macOS](https://git-scm.com/download/mac)

- [Linux](https://git-scm.com/download/linux)

Some Important Vocabulary:

- **Repository**: the data structure of your code, including a .git folder in the root directory

- **Commit**: a particular saved state of the repository, which includes all files and additions

- **Branch**: a means of grouping a set of commits. Each branch has a unique history. This is primarily used for separating development and stable branches.

- **Push**: update the remote repository with your local changes

- **Pull**: update your local repository with the remote changes

- **Clone**: retrieve a local copy of a repository to modify

- **Fork**: duplicate a pre-existing repository to modify, and to compare against the original

- **Merge**: combine various changes from different branches/commits/forks into a single history

Refer to this link for more information on Git and Github: [https://docs.wpilib.org/en/stable/docs/software/basic-programming/git-getting-started.html](https://docs.wpilib.org/en/stable/docs/software/basic-programming/git-getting-started.html)

## Joysticks

A joystick can be used with the Driver Station program to control the robot. Almost any ?controller? that can be recognized by Windows can be used as a joystick. Each axis of the controller ranges from -1 to 1.

*Joystick* class

`Joystick`` ``exampleJoystick`` ``=`` ``new`` ``Joystick(``0``);`` ``// 0 is the USB Port to be used as indicated on the Driver Station`

![](/images/vNp_Image_21.png)

The `Joystick` class is designed to make using a flight joystick to operate the robot significantly easier. Depending on the flight joystick, the user may need to set the specific X, Y, Z, and Throttle channels that your flight joystick uses. This class offers special methods for accessing the angle and magnitude of the flight joystick.

*XboxController* Class

`XboxController`` ``exampleXbox`` ``=`` ``new`` ``XboxController(``0``);`` ``// 0 is the USB Port to be used as indicated on the Driver Station`

![](/images/vR7_Image_22.png)

The `XboxController` class provides named methods (e.g. `getXButton`, `getXButtonPressed`, `getXButtonReleased`) for each of the buttons, and the indices can be accessed with `XboxController.Button.kX.value`. The rumble feature of the controller can be controlled by using `XboxController.setRumble(GenericHID.RumbleType.kRightRumble, value)`. Many users do a split stick arcade drive that uses the left stick for just forwards / backwards and the right stick for left / right turning.

*PS4Controller* Class

`PS4Controller`` ``examplePS4`` ``=`` ``new`` ``PS4Controller(``0``);`` ``// 0 is the USB Port to be used as indicated on the Driver Station`

![](/images/Kqy_Image_23.png)

The `PS4Controller` class provides named methods (e.g. `getSquareButton`, `getSquareButtonPressed`, `getSquareButtonReleased`) for each of the buttons, and the indices can be accessed with `PS4Controller.Button.kSquare.value`. The rumble feature of the controller can be controlled by using `PS4Controller.setRumble(GenericHID.RumbleType.kRightRumble, value)`.

Button Usage

`if`` ``(joystick.``getRawButtonPressed``(``0``))`` ``{`

`   ``turnIntakeOn();`` ``// When pressed the intake turns on`

```
}
`if`` ``(joystick.``getRawButtonReleased``(``0``))`` ``{`

`   ``turnIntakeOff();`` ``// When released the intake turns off`

}

OR

`if`` ``(joystick.``getRawButton``(``0``))`` ``{`

`   ``turnIntakeOn();`

`}`` ``else`` ``{`

`   ``turnIntakeOff();`

}
```

Toggle Button

`boolean`` ``toggle`` ``=`` ``false``;`

`if`` ``(joystick.``getRawButtonPressed``(``0``))`` ``{`

`   ``if`` ``(toggle)`` ``{`

`      ``// Current state is true so turn off`

`      ``retractIntake();`

`      ``toggle`` ``=`` ``false``;`

`   ``}`` ``else`` ``{`

`      ``// Current state is false so turn on`

`      ``deployIntake();`

`      ``toggle`` ``=`` ``true``;`

`   ``}`

```
}
```

## Robot Preferences

` ``public`` ``static`` ``final`` ``String`` ``kArmPositionKey`` ``=`` ``"ArmPosition"``;`

` ``public`` ``static`` ``final`` ``String`` ``kArmPKey`` ``=`` ``"ArmP"``;`

` ``// The P gain for the PID controller that drives this arm.`

` ``public`` ``static`` ``final`` ``double`` ``kDefaultArmKp`` ``=`` ``50.0``;`

` ``public`` ``static`` ``final`` ``double`` ``kDefaultArmSetpointDegrees`` ``=`` ``75.0``;`

` ``// The P gain for the PID controller that drives this arm.`

` ``private`` ``double`` ``m_armKp`` ``=`` ``Constants.``kDefaultArmKp``;`

` ``private`` ``double`` ``m_armSetpointDegrees`` ``=`` ``Constants.``kDefaultArmSetpointDegrees``;`

`  ``/** Subsystem constructor. */`

` ``public`` ``Arm``()`` ``{`

`    ``// Set the Arm position setpoint and P constant to Preferences if the keys don't already exist`

`   ``Preferences.``initDouble``(Constants.``kArmPositionKey``,`` ``m_armSetpointDegrees);`

`   ``Preferences.``initDouble``(Constants.``kArmPKey``,`` ``m_armKp);`

```
}












# Hardware Components

![](/images/K2r_Image_24.png)

```

## NI RoboRio

The [NI-roboRIO](https://docs.wpilib.org/en/stable/docs/software/roborio-info/roborio-introduction.html#roborio-introduction) is the main robot controller used for FRC. The roboRIO serves as the ?brain? for the robot running team-generated code that commands all of the other hardware.

![](/images/Fz4_Image_25.png)

## CTRE Power Distribution Panel

The [CTRE Power Distribution Panel](https://docs.wpilib.org/en/stable/docs/software/can-devices/power-distribution-module.html#power-distribution-module) (PDP) is designed to distribute power from a 12VDC battery to various robot components through auto-resetting circuit breakers and a small number of special function fused connections. The PDP provides 8 output pairs rated for 40A continuous current and 8 pairs rated for 30A continuous current. The PDP provides dedicated 12V connectors for the roboRIO, as well as connectors for the Voltage Regulator Module and Pneumatics Control Module. It also includes a CAN interface for logging current, temperature, and battery voltage. For more detailed information, see the [PDP User Manual](https://store.ctr-electronics.com/content/user-manual/PDP%20User%27s%20Guide.pdf).

![](/images/PH3_Image_26.png)

## CTRE Voltage Regulator Module

The CTRE Voltage Regulator Module (VRM) is an independent module that is powered by 12 volts. The device is wired to a dedicated connector on the PDP. The module has multiple regulated 12V and 5V outputs. The purpose of the VRM is to provide regulated power for the robot radio, custom circuits, and IP vision cameras. For more information, see the [VRM User Manual](https://store.ctr-electronics.com/content/user-manual/VRM%20User%27s%20Guide.pdf).

![](/images/R1E_Image_27.png)

## OM5P-AC Radio

![](/images/7Po_Image_28.png)

## 120A Circuit Breaker

The 120A Main Circuit Breaker serves two roles on the robot: the main robot power switch and a protection device for downstream robot wiring and components. The 120A circuit breaker is wired to the positive terminals of the robot battery and Power Distribution boards. For more information, see the [Cooper Bussmann 18X Series Datasheet (PN: 185120F](https://www.mouser.com/datasheet/2/87/BUS_Tns_DS_18X_CIRCUITBREAKER-515519.pdf)

![](/images/iCI_Image_29.png)

## Snap Action Circuit Breakers

The Snap Action circuit breakers, [MX5 series](http://www.snapaction.net/pdf/MX5%20Spec%20Sheet.pdf) and [VB3 Series](http://www.snapaction.net/pdf/vb3.pdf), are used with the Power Distribution Panel to limit current to branch circuits. The ratings on these circuit breakers are for continuous current, and temporary peak values can be considerably higher.

![](/images/VmN_Image_30.png)

## Robot Battery

The power supply for an FRC robot is a single 12V 18Ah Sealed Lead Acid (SLA) battery, capable of meeting the high current demands of an FRC robot. For more information, see the [Robot Battery page.](https://docs.wpilib.org/en/stable/docs/hardware/hardware-basics/robot-battery.html#robot-battery-basics)

![](/images/nBS_Image_31.png)

## Robot Signal Light

The Robot Signal Light (RSL) is required to be the Allen-Bradley 855PB-B12ME522. It is directly controlled by the roboRIO and will flash when enabled and stay solid while disabled.

![](/images/PUD_Image_32.png)

## CTRE Pneumatics Control Module

The [CTRE Pneumatics Control Module](https://docs.wpilib.org/en/stable/docs/software/can-devices/pneumatics-control-module.html#pneumatics-control-module) (PCM) contains all of the inputs and outputs required to operate 12V or 24V pneumatic solenoids and the on board compressor. The PCM contains an input for the pressure sensor and will control the compressor automatically when the robot is enabled and a solenoid has been created in the code. For more information see the [PCM User Manual](https://store.ctr-electronics.com/content/user-manual/PCM%20User%27s%20Guide.pdf).

![](/images/hJd_Image_33.png)

## SPARK MAX Motor Controller

The [SPARK MAX Motor Controller](https://www.revrobotics.com/rev-11-2158/) is an advanced brushed and brushless DC motor controller from REV Robotics. When using CAN bus or USB control, the SPARK MAX uses input from limit switches, encoders, and other sensors, including the integrated encoder of the REV NEO Brushless Motor, to perform advanced control modes. The SPARK MAX can be controlled over PWM, CAN or USB (for configuration/testing only). For more information, see the [SPARK MAX User?s Manual](https://docs.revrobotics.com/sparkmax/).

![](/images/mm6_Image_34.png)

## Venom Motor Controller

The [Venom Motor Controller](https://www.playingwithfusion.com/productview.php?pdid=99) is integrated into a motor based on the original CIM. Speed, current, temperature, and position are all measured onboard, enabling advanced control modes without complicated sensing and wiring schemes.

![](/images/IXB_Image_35.png)

# 

# 

# Glossary

accelerometer - A common sensor used to measure acceleration in one or more axes.

auto - The first phase of each match is called Autonomous (auto) and consists of the robot?s running pre-programmed instructions.

back-EMF - In electric motors, the force generated by the interaction of spinning magnets in a coil of wire which opposes spinning motion.

boolean - A form of data with only two possible values (true or false), intended to represent the two truth values of logic and Boolean algebra.

call stack - A specially-organized region of memory which helps the program keep track of what function it is in. As each function calls another, the call point is recorded and added to the top of the structure, forming a ?stack? of references. Additionally, local variables will also be stored in this stack.

central limit theorem - A core concept in probability which states that when many independent variables are added up, the result tends to look like a ?normal? (or Gaussian) distribution, regardless of whether the independent variables themselves are normally distributed.

Classical Mechanics - The branch of physics which studies and describes the motion of relatively large, relatively slow objects.

COTS - Commercial off the shelf, a standard (i.e. not custom order) part commonly available from a vendor to all teams for purchase.

composition - A formal software term for building (or ?composing?) software entities out of smaller component entities.

CRTP - Continuously Recurring Template Pattern - A software idiom in which a class X` derives from a class template instantiation using X` itself as a template argument.

C++ - One of the three officially supported programming languages.

declarative programming - A style of software which focuses on describing what a program should do, rather than how it gets done.

dependency injection - A software design pattern where each class receives all objects it depends upon.

deprecated - Software that has been replaced and will no longer receive new features.

design pattern - A particular, intentionally-chosen style of organizing code.

DHCP - Dynamic Host Configuration Protocol, the protocol that allows a central device to assign unique IP addresses to all other devices.

encapsulation - A software design pattern which uses a class to hide the implementation details of other classes.

entry - In NetworkTables, a combined publisher and subscriber.

enumeration - A list of all elements of a set, typically used to refer to a set of pre-defined values.

event-driven programming - A style of programming where certain parts of code generate ?events? as a result of some input, and other parts of code listen for and respond to these events.

floating point - A method for approximating real numbers in computer-based arithmetic.

FMS - Field Management System, the electronics core responsible for sensing and controlling the FIRST Robotics Competition field.

FPGA - Field-programmable gate array - a specialized integrated circuit consisting of many digital logic elements.

GradleRIO - The mechanism that powers the deployment of robot code to the roboRIO.

gyroscope - A device that measures rate of rotation.

heading - The direction the robot is pointed, usually expressed as an angle in degrees.

imperative programming - A style of programming that focuses on what the code should be doing, step by step, every loop.

IMU - Inertial Measurement Unit, a sensor that combines both an accelerometer and a gyroscope into a single sensor.

Java - One of the three officially supported programming languages.

JSON - JavaScript Object Notation. A standardized way of organizing data into named values.

KOP - Kit of Parts, the collection of items listed on the Kickoff Kit checklists.

KOP chassis - The KOP contains a drive base (chassis) distributed to every team as part of the KOP.

LabVIEW - One of the three officially supported programming languages.

NetworkTables - A publish-subscribe messaging system to communicate data between programs.

mass - The amount of matter in a physical object.

moment of inertia - The property of an object that describes both how much mass it has, and how that mass is distributed relative to a certain axis of rotation.

mutable - An object that can be modified after it is created.

permanent-magnet DC motor - The classification of all legal motors for the FIRST robotics competition.

persistent - In NetworkTables, a topic that is saved to a file by the server and restored at startup.

property - In NetworkTables, named information (metadata) about a topic stored and updated separately from the topic?s data.

publisher - In NetworkTables, an object that defines a topic and creates and sends timestamped data values.

pose - The collection of position and rotation information that describes how a rigid body is oriented in space.

RAII - Resource Acquisition Is Initialization; a language behavior in C++ where holding a resource is tied to object lifetime.

retro-reflection - The property of reflecting incoming light back at the same angle it came in at.

recursive composition - A type of composition in which the composite object may contain components of the same type as itself.

retained - In NetworkTables, a topic that is kept alive by the server even after all publishers stop publishing.

serialized - The property of a data organization scheme that allows the description of the data to be sent in order, byte by byte, over some communication channel.

simulation - A way for teams to test their code without having an actual robot available.

software library - A collection of code that can be imported into and used by other software.

solenoid valve - An airflow-controlling valve which is actuated by a small electromagnet.

state machine - A programming construct that divides a problem into many discrete, well-defined, mutually-exclusive ?states?.

subscriber - In NetworkTables, an object that receives timestamped data value updates to one or more topics.

telemetry - The process of recording and sending real-time data about the performance of your robot to a real-time readout or log file.

teleop - The second phase of each match is called the Teleoperated Period (teleop) and consists of drivers controlling their robots.

topic - In NetworkTables, a named data channel.

torque - A force applied at a distance from some axis of rotation.

trajectory - A smooth curve, with velocities and accelerations at each point along the curve, connecting two endpoints on the field.

transitory - In NetworkTables, a topic that will disappear after the last publisher stops publishing.
