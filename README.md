# QA-Exam

This is my Exam Results.
I used IntelliJ IDEA Community Edition 2021.2


1. Unzip all the .zip file (chromedriver.zip, jar files.zip and QA_Test.zip) and paste it in My Documents and Create Selenium Folder.
2. Install and Open IntelliJ IntelliJ IDEA Community Edition 2021.2
   - Download IDE at https://www.jetbrains.com/idea/download/#section=windows -> Community -> Download
   - Open the ideaIC-2021.2.exe->Run->Next->Next
   - In Installation Options
   - In "Update PATH Variable"
   - please check: the add "bin" folder to the PATH
   - In Update Context Menu: please check: Add Open Folder as Project 
   - click Next and Install.
   - After Install, I selected "I want to manually reboot later" and Finish.
   
   Note: 
   - Locate C:\Users\ < name of pc > \Documents\Selenium\QA_Test\src\com\company\Main.java
   - in line 13 of Main.java: System.setProperty("webdriver.chrome.driver","< location of chromedriver in your computer >\\chromedriver.exe");
   
   This is line 13 on my side: <Main.java>
   System.setProperty("webdriver.chrome.driver","C:\\Users\\pc1\\Documents\\Selenium\\chromedriver\\chromedriver.exe");

3. Install Java SDK 16. 
   - link: https://www.oracle.com/java/technologies/javase-jdk16-downloads.html -> Windows x64 Installer -> jdk-16.0.2_windows-x64_bin.exe
   - Check the checkbox then download.
   - Open the jdk-16.0.2_windows-x64_bin.exe. Next->Next->Wait to install then Close.
   - Check the version of java version. Start->cmd-> "java -version". It should be "16.0.2" 2021-07-20
   - Start->search "Environment" then click, "System Properties" should pop-up. Then click "Environment Variables".
   - In the lower part of the window. Look for "Path" in "System Variables" and click "Edit", then click "New" and locate the JDK 16. Then click OK
     here is my sample path on my computer "C:\Program Files\Java\jdk-16.0.2\bin"
4. Open the IDE. IntelliJ IDEA Community Edition 2021.2
   - Locate the QA_Test.jar or QA_Test.iml
   - C:\Users\<pc_name>\Documents\Selenium\QATest\out\artifacts\QA_Test.jar or
     C:\Users\pc1\Documents\Selenium\QA_Test\QA_Test.iml
   - And drag QA_Test.jar or QA_Test.iml to your IDE IntelliJ IDEA Community Edition 2021.2 and wait for the file to open. And then Run.

5. I dont have idea in the last Scenario: "Given that the page finishes loading. Then the clientWidth of the property images must be exactly 300px".

And that's all. I did my best. I hope I met your expectations. Thank you!
