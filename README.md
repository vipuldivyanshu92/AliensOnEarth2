AliensOnEarth2
==============

Pure console application for Aliens Registration 

To run this , got to the classes folder and execute the following

from the classes folder run 

> java Main

or 

from the classes folder run

Main.jar

To compile java classes use the following 

> javac -cp ../PDF.jar -d ../classes *.java

This will create the new .class files in classes folder

These can be then executed with 

> java Main 

Adding plugins for export format

1. add the new export format lass to the sources folder

2. add the display name string for that export format in Utils.java in the createExportMenu string array at the end

3. add a case statement invoking the export function and pass the values variable(it holds alineds reg. data) inside the createExportMenu function of Main.java
