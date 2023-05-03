# Installation 

<< [Home](README.md)

You'll need JDK, Maven or Gradle and some IDE (optional)

## JDK

#### Windows:

1. Go to the official Oracle JDK download page: https://www.oracle.com/java/technologies/downloads/.
1. Accept the license agreement by clicking the checkbox next to "I agree to the Java SE Development Kit 11 License Agreement".
1. Choose the correct version of JDK for your Windows operating system.
1. Click the download link for the JDK installation file.
1. Once the download is complete, run the installation file and follow the instructions in the installer to complete the installation process.
1. After the installation is complete, open the command prompt and type "java -version" to verify that the JDK is installed correctly.


#### Mac:

1. Go to the official Oracle JDK download page: https://www.oracle.com/java/technologies/downloads/.
1. Accept the license agreement by clicking the checkbox next to "I agree to the Java SE Development Kit 11 License Agreement".
1. Choose the correct version of JDK for your Mac operating system.
1. Click the download link for the JDK installation file.
1. Once the download is complete, run the installation file and follow the instructions in the installer to complete the installation process.
1. After the installation is complete, open the Terminal app and type "java -version" to verify that the JDK is installed correctly.

#### Linux:

1. Open a terminal window and run the following command to update the package list: 
    ```bash
    sudo apt-get update
    ```
1. Run the following command to install the default JDK: 
    ```bash
    sudo apt-get install default-jdk
    ```
1. After the installation is complete, type "java -version" to verify that the JDK is installed correctly.
1. If the default JDK is not the version you need, you can install a specific version by running the following command: 
    ```bash
    sudo apt-get install openjdk-11-jdk
    ```
    (replace "11" with the version you need).

## Apache Maven

#### Windows:

1. Go to the official Apache Maven download page: https://maven.apache.org/download.cgi.
1. Download the latest binary zip archive for Windows.
1. Extract the contents of the zip archive to a folder of your choice.
1. Add the bin directory of the extracted folder to the PATH environment variable.
1. Open a new command prompt and type "mvn -version" to verify that Maven is installed correctly.

#### Mac:

1. Open a terminal window.
1. Install Homebrew package manager by running the following command: 
    ```bash
    /bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"
    ```
1. Install Maven by running the following command: brew install maven
1. After the installation is complete, type "mvn -version" to verify that Maven is installed correctly.

#### Linux:

1. Open a terminal window.
1. Install Maven by running the following command: 
    ```bash
    sudo apt-get install maven
    ```
1. After the installation is complete, type "mvn -version" to verify that Maven is installed correctly.


## Gradle

#### Windows:

1. Go to the official Gradle download page: https://gradle.org/releases/.
1. Download the latest binary distribution for Windows.
1. Extract the contents of the zip archive to a folder of your choice.
1. Add the bin directory of the extracted folder to the PATH environment variable.
1. Open a new command prompt and type "gradle -v" to verify that Gradle is installed correctly.

#### Mac:

1. Open a terminal window.
1. Install Homebrew package manager by running the following command: 
    ```bash
    /bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"
    ```
1. Install Gradle by running the following command: brew install gradle
1. After the installation is complete, type "gradle -v" to verify that Gradle is installed correctly.

#### Linux:

1. Open a terminal window.
1. Install Gradle by running the following command: 
    ```bash
    sudo apt-get install gradle
    ```
1. After the installation is complete, type "gradle -v" to verify that Gradle is installed correctly.


## IDE
If you are already familiar with one of the IDEs and feel comfortable using it, you can choose the one you prefer. Here are a few popular ones:
* [Visual Studio Code](https://code.visualstudio.com/download) - A universal tool from Microsoft that has a huge number of plugins for multiple languages. If you plan to use other languages in addition to Java, then this is the tool for you!
* [IntelliJ IDEA](https://www.jetbrains.com/idea/download/) - One of the best tools for Java developers. Unlike VSCode, it was originally developed for Java and only then grew with a multitude of additional features.
* [Eclipse](https://www.eclipse.org/downloads/) - This is a veteran among IDE tools. Starting from 2001, it has been a good free and open source alternative.


<< [Home](README.md)