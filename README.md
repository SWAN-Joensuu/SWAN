# SWAN
Zip file for the tool and video tutorials
1. Your computer need to have 512 MB or more RAM.
2. In order to be able to use this tool, you must have Java (Java Runtime Environment version 1.6 or higher) installed to your computer. To know if you have, go to the www.java.com site and click on the link "Do I Have Java" under the red button. If you have older versions of Java, we recommend you unistall them by clicking "unistall" underthe red button too. After which, go to the following page (https://www.java.com/en/download/manual.jsp) and download the Java version for your computer. Java version and operating system (OS) should have the same wordlength. Most of the modern Windows computers (Windows 7 or newer) are 64-bit. If your OS is 64-bit, install 64-bit version of Java.
It is recommended that you update your Java installation regurarly for full compatibility with this and other Java applications and for security updates. You can download the latest Java Runtime Environment (JRE) from here.
Mac users with several Java versions installed should check that only the latest version is selected in Java Preference application.

Troubleshooting & FAQ

Q: Does SWAN send my text to an another server (eg. cloud) for an analysis?
A: No. All text analysing is done on the local computer, and nothing of the text is sent to any servers.
Q: (Windows) When I try to launch .bat file, a black window appears and disappears instantly
A: Make sure you have Java installed. Also make sure you have extracted the whole .zip package into the same directory before running any files
Q: I have installed 64-bit version of Java but SWAN still asks me to install 64-bit Java
A: In some cases the computer already had 32-bit Java installed and it still remains as the main Java installation after 64-bit installation. Uninstall 32-bit Java before installing 64-bit Java (or alternatively use Java Control Panel -> Java to select which installation to use)
Launching the tool

Launching the tool depends on your operation system. To launch the tool, you have to use one of the following script files. The reason for this is, that these script files will reserve more memory for the tool to use than will be reserved if you run the tool directly from .jar file. If you run the tool from .jar file directly, the tool might crash or behave unpredictable.

On Windows computers: double click Launch_SWAN_(Windows).bat file
On Linux computers: launch Launch_SWAN_(Linux).sh from command line
On Mac computers: double click Launch_SWAN_(Mac).command file *
*) Special note for Mac You may need to first grant permissions for the launch file.
You can do this e.g. the following way: start Terminal, browse to the folder the software is. Then use the following command:
sudo chmod 777 Launch_SWAN_(Mac).command

Terminal might ask your account's password, type it in. After this, you should be able to start the software by double clicking Launch_SWAN_(Mac).command file. You may also be able to grant these permissions via Mac's graphical user interface. More about granting permissions for files and folders on Mac (OS X 10.4): http://docs.info.apple.com/article.html?path=Mac/10.4/en/mh669.html

For additional help, look at the following page: http://cs.joensuu.fi/swan/help.html

