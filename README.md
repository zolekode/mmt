# mmt
#### Mac OS Installation - Quick Guide (Could probably work for Windows too.)
Disclaimer: The official installation guide is found here: https://uniformal.github.io/doc/setup/. I merely show the steps that worked for me. Refer to the official guide in case you have trouble installing MMT.

#### Steps

1. Install Java version 8, 9 or 11: https://developer.ibm.com/javasdk/downloads/ (I installed Java 8. Note that, there are other java distributions on other websites e.g Oracle https://www.oracle.com/technetwork/java/javase/downloads/index.html)

2. Install Scala-sbt: https://www.scala-sbt.org/

3. Install Git: https://git-scm.com/downloads

4. Install Intelli-J https://www.jetbrains.com/idea/download/#section=mac (Be careful to select the right version of Intelli-J that works with the MMT plugin. (https://plugins.jetbrains.com/plugin/11450-mmt/ -> Under **What's new**)

5. Download the mmt.jar file here https://github.com/UniFormal/MMT/releases/

6. Now open Intelli-J (You could create a dummy project first) and go to **Preference -> Plugins -> Marketplace tab** and then search for `Scala` and then `mmt`. Install both plugins.

7. Once they are installed, restart the Intelli-J. (Maybe you might need to restart it after installing each plugin. It doesn't make any difference.)

8. Finally when you launch Intelli-J, create a new `MathHub` project. 
- Click on + Create New Project 
- Then select MMT MathHub
- Select the `mmt.jar` file you download during step 5
- Give a name to your project
- Click on Finish

9. In the section below (after IntelliJ has fully launched), you will see some tabs like `TODO`, `Version Control`, `MMT`, `Terminal`. 
- Click on `MMT`. 
- Next the following tabs `MMT: Errors X Shell X` will become visible.
- Click on the `Shell` tab.

10. Finally, in the Textbox below (with the `Run` Button on the far right) enter the following command:
`lmh install Tutorials/Mathematicians`to download dependency archives.

You are now good to go. Take a look at the official guide if you encounter any issues.

Hope this helps.


