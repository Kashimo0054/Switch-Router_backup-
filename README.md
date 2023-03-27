# Switch-Router_backup-
Network-device backup using python
This simple python script allows you to ssh into network devices enabled with ssh and retrieve configuration at the present state and store files on the system using 
date and time format 
The modules used in the script are very easy to grasp and will find tons of information online 
It is essential to grasp some foundational level of python before you can create your own python script trial and error lead you to become a better system/engineer or 
administrator 
The concept used in this script includes a dictionary to store my IP address and a description of the device an example would include a core router or a switch that you have placed in your network 
Next, it would include a for loop  to iterate over the dictionary and devices mentioned in it 
The modules used include paramiko which would allow you to ssh into the device date and time module which would allow you to store files promptly on time and OS module which would allow you to manipulate and create files upon successful execution of the script. 
This script  has been modified to work in Debian environment you can also use crontab to schedule the execution of the script at your convenience time 
I would also include a script that can be executed on windows enviroment  and you can use task scheduler to achieve this 
