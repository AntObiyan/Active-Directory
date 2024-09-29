# Active-Directory
![FIM](https://raw.githubusercontent.com/AntObiyan/Active-Directory/main/what-is-active-directory%20(1).webp)



## Introduction
Active Directory (AD) is a directory service developed by Microsoft for Windows domain networks. It manages and organizes network resources like users, computers, and devices, making it easier to control access and security within a network. AD stores data as objects, such as user accounts or computers, and helps administrators control permissions, authenticate users, and enforce security policies. It also enables centralized management of resources, making it a core tool for organizations to streamline IT tasks, automate processes, and ensure secure, efficient operations across large networks. To do this project I installed a Windows server in a virtual machine, the VM used was VMWare Workstation. I also created an AD domain  (AObiyan.local & AntO.local)

## Creation of Organizational Units
The first step in this Active Directory setup was creating three Organizational Units (OUs): USA, Asia, and Europe. An Organizational Unit is essentially a container that holds various types of objects, such as users, groups, and computers, helping to organize and manage resources within the directory.


![Architecture Diagram](https://github.com/AntObiyan/Active-Directory/blob/main/OU%20Creation%20.png?raw=true)

## Creation of Groups
Next, I created groups within each Organizational Unit (OU), organizing them into categories for computers, users (personnel), and servers.


![Architecture Diagram](https://github.com/AntObiyan/Active-Directory/blob/main/OU%20Creation%202.png?raw=true)


## Creation of Departments
Next, I created various departments within the groups, including IT, Accounting, HR, Sales, and Management.


![Architecture Diagram](https://github.com/AntObiyan/Active-Directory/blob/main/Depts.png?raw=true)


## Group - IT
I created an IT group, choosing the global group type so it can be used within the AObiyan.local domain and accessed by resources in that domain. I selected the security group type to manage permissions for shared resources and grant user rights solely to the IT department.


![Architecture Diagram](https://github.com/AntObiyan/Active-Directory/blob/main/IT%20group%20creation%20.png?raw=true)


## Distribution Groups
A distribution group is used to create an email list that allows messages to be sent to a group of users. For instance, members of the finance department would receive all emails relevant to their team. For the DL-ITAdmin group, the distribution group type was chosen, so IT professionals will receive emails specific to their role.


![Architecture Diagram](https://github.com/AntObiyan/Active-Directory/blob/main/Groups%20creation%20.png?raw=true)


## Creation of User
Lastly, I created a newly onboarded user, specifying the full name, logon name, and a default password. I also selected the option to require a password reset upon the first login. 


![Architecture Diagram](https://github.com/AntObiyan/Active-Directory/blob/main/User%20creation%20.png?raw=true) 
![Architecture Diagram](https://github.com/AntObiyan/Active-Directory/blob/main/Default%20password.png?raw=true)
