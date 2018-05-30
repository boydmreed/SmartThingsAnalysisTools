# SmartThingsAnalysisTools
Static Analysis tool for overprivilege, python script to auto-create device handlers, and completed capability docs at time of analysis.
We do not provide an app dataset for analysis.
Built and tested with Eclipse Oxygen, and Groovy Compiler 2.4.

Prerequisites:
1. Java JDK 1.7 http://www.oracle.com/technetwork/java/javase/downloads/java-archive-downloads-javase7-521261.html
2. Groovy compiler (on Mac use [Homebrew](https://brew.sh/) to install it via "brew install groovysdk")
3. Eclipse Oxygen (https://www.eclipse.org/downloads/download.php?file=/oomph/epp/oxygen/R2/eclipse-inst-mac64.tar.gz)
4. Install Groovy-eclipse plugin. Follow the directions [here] (https://www.function1.com/2016/06/installing-eclipse-groovy-plugin). In Step 2, use the plugin URL http://dist.springsource.org/release/GRECLIPSE/e4.7 
5. Add the Java 1.7 JRE to the build path in Eclipse. Follow the steps [here] (http://heather.sh/2014/04/installing-jre-78-jdk-1-71-8-on-mac-for-eclipse/)

How To:
1. Open the project in Eclipse.
2. Update AnalysisDriver.groovy and add the correct path to your project_root (for example, /Users/boydm/work/SmartThingsAnalysisTools).
3. AnalysisDriver.groovy can then be run as a Groovy Script.
