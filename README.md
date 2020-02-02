# javaFxTemplate
This template uses java 11, javafx 11 and gradle with the javafx plugin.

### Use with plain gradle:
- Clone the project copy it or whatever
- `./gradlew run`
or just run the gradle un task

### Use with Intelij:
- New Project from Version Source control-> git
- Open Project 
- Right click build.gradle and click "Import gradle project"
- Right click RunThisClass.java and select run

### Use Eclipse(Warning Eclipse Gradle integration is shit):
- Clone the project copy it or whatever
- Open Project
- Window -> Show View-> Other -> Gradle Tasks- > Import a Gradle project
- Make sure your systems default jdk is java 11 or set the java home in the gradle settings under Project-> Properties ->Gradle -> Java Home to a jdk 11
- Run the RunThisClass

# If u want to use java fx without this template and without gradle:

For eclipse get yourself https://wiki.eclipse.org/Efxclipse/Tutorials .
Or in Intelij you can just click New Project-> Java FX
