## Installing Java or Python on Your Laptop

Here are some instructions for downloading Java and Python development tools to your laptop computer. Before using them you might want to see if your operating system offers alternate, simpler ways to install these language systems. For example, if you use Ubuntu or Debian Linux you can get all the python tools needed just by running two commands like these:

sudo apt-get install python  
sudo apt-get install python-serial

If you don't have anything like that then use the following instructions for the language system you want to install.

### Installing Java

To install the Java System Design Kit (SDK) on your laptop you should be able to find the latest version for most commonly used operating systems on the [https://www.java.com/](https://www.java.com/) website. The download page is on:

[https://www.java.com/en/download/manual.jsp](https://www.java.com/en/download/manual.jsp)

You also need to install a class library that will allow you to use the USB serial ports on your computer to talk to things like RFID readers. The library commonly used in the lab is called RXTX. You can get RXTX from the following URL:

[http://rxtx.qbang.org/wiki/index.php/Download](http://rxtx.qbang.org/wiki/index.php/Download)

The instructions for using it with windows or Linux are reasonably clear, but not so clear for OSX. [A description of how to install RXTX on OSX can be found here](is2500_pdf/how_to_install_rxtx_for_osx.pdf).

### Installing Python

To install Python on your laptop you should be able to find both versions 2.7 and 3 for most commonly used operating systems on the [https://www.python.org/](https://www.python.org/) website. For projects in the lab, Python version 2.7 is used so you will want to download the latest version of that. The download page is on:

[https://www.python.org/downloads/](https://www.python.org/downloads/)

You also need to install a python module that will allow you to use the USB serial ports on your computer to talk to things like RFID readers. The module commonly used in the lab is called pyserial. You can get pyserial from the following URL:

[https://sourceforge.net/projects/pyserial/](https://sourceforge.net/projects/pyserial/)

Instructions for installing it are the same for all operating systems. The pyserial.sourceforge.net website give instructions for installing it. You need to install Python itself first before installing pyserial.
