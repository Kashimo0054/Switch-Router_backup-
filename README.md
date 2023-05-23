Network Device Backup Script using Python
This Python script simplifies the process of backing up network devices enabled with SSH. By establishing an SSH connection, the script retrieves the device's configuration in its current state and stores the backup files on the local system using a date and time format.

Key Features:

Simplified Network Device Backup: The script automates the SSH login process to network devices and retrieves their configurations, streamlining the backup procedure.
Easy-to-Grasp Modules: The script utilizes modules that are easy to understand and learn. Extensive online resources are available to support users in getting started quickly.
Foundational Knowledge Requirement: Prior foundational knowledge of Python is recommended to fully comprehend and customize the script. Learning through trial and error contributes to becoming a more proficient system engineer or administrator.
Device Dictionary for Configuration: The script employs a dictionary to store the IP addresses and descriptions of network devices. This allows for easy management and customization, supporting various device types such as core routers or switches within a network.
Efficient Iteration: The script employs a for loop to iterate over the device dictionary, enabling automated backup of multiple devices with minimal code modification.
Utilized Modules: The script utilizes Paramiko for SSH connectivity, the Date and Time module for accurate file naming, and the OS module for file manipulation and creation upon successful execution.
Debian Environment Compatibility: The script has been modified to function effectively within a Debian environment. However, it can be adapted for other environments as well.
Automation with Crontab: Users can schedule the script's execution conveniently using Crontab, allowing for regular and automated network device backups.
Windows Environment Support: The script includes an alternative version that can be executed on a Windows environment. Users can leverage the Task Scheduler to automate backups as per their requirements.
This script provides an efficient solution for network administrators and engineers to automate the backup process of SSH-enabled network devices. With its clear implementation and compatibility with different environments, it offers flexibility and ease of use.
