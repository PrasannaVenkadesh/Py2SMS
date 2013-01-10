Py2sms is an CUI based Terminal App using which you can send SMS from your Terminal using your www.way2sms.com account.
So You need to create an account in www.way2sms.com before using this app.

Download tar or zip file and Extract it. Rename the Extracted folder to Py2sms.

Note:- This app is not from Way2sms Team.


Installing:
===========

* Open your Terminal

* Fedora / Redhat / CentOS users :- 

		sudo yum install python-mechanize

* Ubuntu / LinuxMint / Debian :-

		sudo apt-get install python-mechanize

* Common steps :-

		cd ~/Downloads/Py2sms
		sudo sh w2sms-install

Usage:
======

* Open your Terminal 

		$ w2sms-login
The above command is a one-time command, you do not need to execute this everytime, once you enter Login Credentials it will be saved.

* Enter the Login Details

		$ w2sms


Removing:
=========

* Open your Terminal

		$w2sms-remove


Updating:
=========

* Open your Terminal

		$git clone git@github.com:PrasannaVenkadesh/Py2SMS.git
		$cd Py2SMS
		$w2sms-remove
		$./w2sms-install

Obviously this is not the better way to update, I will write a shell script or python script for that.
