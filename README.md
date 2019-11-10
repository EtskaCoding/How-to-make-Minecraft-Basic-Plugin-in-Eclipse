*Lesson-1*

First we need start Eclipse IDE

Second create new Java Project
Go to File > New > Java Project
Write porject name and click Finish

Download Spigot 1.8.8
https://cdn.getbukkit.org/spigot/spigot-1.8.8-R0.1-SNAPSHOT-latest.jar
Create directory on your computer (Desktop Recommended)
Put Spigot in folder
Go to Eclipse IDE
Right click a project folder
Select Properties > Java Build Path >  Add External JARs
And go our spigot folder and add it
Click Apply And Close

Douple click your project
Press src with mouse right button
Select New > Package
Name package to me.(your name).(your project name)
Click Finish

Press your package with mouse right button
Select New > Class
Name Class to Your class name (Example Main or Core)
Click Finish

Your Project is now open
Okey lets write in line 3
Your line 3 should look like this **public class (Your Class) extends JavaPlugin {**
Press ctrl + shift + o to import JavaPlugin

Press your project with mouse right button
Select New > File
Name it **plugin.yml**

Write this text in plugin.yml
name: (Your Plugin Name)
main: (Your Package Name).(Your Main Class Name)
version: (Plugin version)
author: (Your name)
description: (Plugin Description)

Plugin exporting
Press your project with mouse right button
Press Export > Java > JAR File
Click Next
Select import location
Click Finish

Ready :)
