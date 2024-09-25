0. Make a folder "C:\jetbraincrack" and copy the "enc-sniarbtej-2024.2.4.jar" to this folder

1. Open the file with ".vmoptions" extension with notepad. this file is in installation directory("C:\Program Files\JetBrains\<program name>\bin"). add this line at the end:

-javaagent:C:\jetbraincrack\enc-sniarbtej-2024.2.4.jar

3.Open powershell as admin and go to the this folder "C:\jetbraincrack" then Generate the specified key with this command:

java -jar enc-sniarbtej-2024.2.4.jar -genkey -id=Downloadly -user=Downloadly >> key.txt

4. Open the program and use the license in key.txt to activate the software ( everything after "Your license key is:")

*****************
 you need to insall java to run the command. if you do not want to install java, you can Run the command below. change program name to you'r specific jetbrain program (in "C:\jetbraincrack" folder):

&'C:\Program Files\JetBrains\PyCharm 2024.1.4\bin\java.exe' -jar enc-sniarbtej-2024.2.4.jar -genkey -id=Downloadly -user=Downloadly >> key.txt

*****************
====================
www.downloadly.ir