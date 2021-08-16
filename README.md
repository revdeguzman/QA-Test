# QA-Exam

This is my Exam Results.
I used IntelliJ IDEA Community Edition 2021.2


1. Unzip all the .zip file (chromedriver.rar, jar files.rar) and paste it in My Documents and Create Selenium Folder.
2. Install and Open IntelliJ IntelliJ IDEA Community Edition 2021.2
   - Download IDE at https://www.jetbrains.com/idea/download/#section=windows -> Community -> Download

3. Install Java SDK 16. 
   - link: https://www.oracle.com/java/technologies/javase-jdk16-downloads.html -> Windows x64 Installer -> jdk-16.0.2_windows-x64_bin.exe
   - Check the checkbox then download.
   - Check the version of java version. Start->cmd-> "java -version". It should be "16.0.2" 2021-07-20
   - Start->search "Environment" then click, "System Properties" should pop-up. Then click "Environment Variables".
   - In the lower part of the window. Look for "Path" in "System Variables" and click "Edit", then click "New" and locate the JDK 16. Then click OK
     here is my sample path on my computer "C:\Program Files\Java\jdk-16.0.2\bin"

4. Open the IDE. IntelliJ IDEA Community Edition 2021.2
   - click "Open" on the upper right of the screen.
   - Locate the project in C:/Users/<name of pc>/Documents/Selenium/qaexam/src/com/company/Main.java

5. After opening the Main.java, locate the packages.
   - File->Project Structure->Project->Select the SDK. Im using SDK 16 version 16.0.2
   - Then click Modules->Dependencies->Click "Add (+)" select JARs or Directories.
   - Locate the .jar files in C:/Users/<name of pc>/Documents/Selenium/jar files/
   - Select all the 7 .jar files and click OK.
