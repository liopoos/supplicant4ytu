Description

This is a fully platform-certified script for the Python-based Supplicant developed by lyq1996.

Source Address: https://github.com/lyq1996/supplicant

At present, part of the source code is revised for Purcell network certification of Yantai University, and other schools may fail the certification.

Details: https://blog.mayuko.cn/archives/1897

  

Environment

- Mac OS 10.12. *, Windows, Linux, Android, (Openwrt for testing, python running environment, overlay requires more than 8m free space)
- Python 2.7.x



Bugs

If the authentication is successful, turn off the terminal and then re-certification will appear time out.

Repair method:

- Turn off the terminal, wait for the Purcell network is offline, then connect again.
- connect again.



Configuration

Please configure Python2.7.x before use, for some Linux distributions that come with Python3.5, please configure 2.7 yourself or you will get an error.

Open the program before you open the .py file for user name, password fill.

Mac users recommend using coderunner to open downloaded py files

Please download Qpython before using it.

username = '' # Fill in your username here

password = '' # Fill in your password here

  

Operation

Online 

Mac users: open the terminal, drag the py file to the terminal, press Enter.

Linux users: download python operating environment, followed by steps with Mac.

Offline

Enter ctrl + C

  

Notice

Please be optimistic about the use of your network adapter mac address and procedure is consistent, and ip is the current card.

Please use the ifconfig command to select the network card, otherwise it will report the user bind Mac address error!

If the terminal shows insufficient permissions, then right-click the property that will allow it to be checked as an executable file.
