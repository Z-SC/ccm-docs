# Registration and login steps

## Eligibility
Employees and students with `ucdenver.edu` or `cuanschutz.edu` login credentials. In addition, external collaborators may 
also be given access if they are sponsored by a faculty member. Temporary accounts can be set up for training workshops, reach out to [Jan Mandel](mailto:Jan.Mandel@ucdenver.edu)
for more information. 


## Registering your account
You must have a faculty member reqeust access on your behalf. They will fill out [this form](https://forms.office.com/r/GQ9ef7ei4i) using their UCDenver credentials.
This form will require the following:

* Email address of all users
 
* Brief description of project
 
* Funding source(s)

* Project name (optional)
 
* Affirmation of [Terms and Conditions](./index.md/) 

## Logging in 
### Register for and install Duo Security MFA
All university accounts must have MFA set up!

you will need Duo Security in order to log into the VPN .For more information on Duo MFA, see the [guide](https://www.ucdenver.edu/offices/office-of-information-technology/software/how-do-i-use/getting-started-with-multi-factor-authentication)

### Log into GlobalProtect (VPN)
You must be connected to the VPN in order to access the cluster! 

For more information, see the [guide](https://www.ucdenver.edu/offices/office-of-information-technology/software/how-do-i-use/vpn-and-remote-access)

*Note: When using GlobalProtect for Linux, you will need to respond to the push notifications two times.
### Identify your username
Your username should be known to you, it is the first 7 characters of your last name, and the first letter of your first name. If you do not know your username, visit [this site](https://myaccount.ucdenver.edu), enter the required information, and click Submit.
From there, you will be directed to a new page. Your username will be in the top right, just above your email address. If you need further assistance, contact your academic advisor, or OIT helpdesk at [ucd-oit-helpdesk@cuanschutz.edu](mailto:ucd-oit-helpdesk@cuanschutz.edu).

### SSH into a head node
To log into the clas-compute head node, type `ssh username@clas-compute.ucdenver.pvt`

To log into the Alddran head node, type `ssh username@math-alderaan.ucdenver.pvt` or `ssh username@10.133.30.100`

From there, you will enter your university password, and 
#### Using Windows
Windows Terminal (recommended):
The latest builds of Windows 10 & 11 have a built-in SSH client that you can use in Windows Terminal. For more information, see the [user guide](https://learn.microsoft.com/en-us/windows/terminal/tutorials/ssh)
#### Using iOS
Terminal (recommended):
This application is automatically installed on your system. For more information see the [user guide](https://support.apple.com/lt-lt/guide/terminal/apd5265185d-f365-44cb-8b09-71a064a42125/mac)
#### Using Ubuntu/Linux
Terminal (recommended):
This application is automatically installed on your system. For more information, see the [user guide](https://ubuntu.com/tutorials/command-line-for-beginners#3-opening-a-terminal)a