//README

This project tries out Gradle Ant integration and works with it

build.xml - show that with ant call in place things dont work
bild.working.xml - convers the ant call target to depends and then things start to work

Also, note if your build.xml has any parallel tasks it will not work, you need to take out parallelTask
as per my testing


How to Use this project
This project can be extended to add the all tricks need for  gradle and Ant Integration to work.
You are welcome to clone and contribute

How to Run the project

0. edit build.gradle to point to appropriate ant build..
1. to run the ant build, 
gradle helloAnt


