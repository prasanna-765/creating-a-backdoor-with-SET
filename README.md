# creating-a-backdoor-with-SET
creating a backdoor with SET - Ethical Hacking Techniques course

# AIM:
To Create a backdoor with Social Engineering Toolkit (SET)

## DESIGN STEPS:

### Step 1:

Install kali linux either in partition or virtual box or in live mode


### Step 2:

Investigate on the various categories of tools as follows:

### Step 3:

Open terminal and try execute some kali linux commands

## EXECUTION STEPS AND ITS OUTPUT:
Social Engineering attacks are the various cons used by the hackers to trick people into providing sensitive data to the attackers. 
The command sudo setoolkit in the prompt gives menu with set prompt:


![image](https://github.com/user-attachments/assets/05ae2f8f-add3-4ec1-8e11-c45f2f01d6ad)




The command sudo setoolkit in the prompt gives menu with set prompt. Select menu1 for Social Engineering Attacks:

![image](https://github.com/user-attachments/assets/a345a377-07ea-4700-818d-b6c0125958b0)


It displays the following menu and select 2 for Website Attack Vectors:

![image](https://github.com/user-attachments/assets/660b47e8-83e3-4d1f-ac0e-67ca1bcc7472)


The website Attack Vectors displays the following menu. In this menu3 for Credential Harvester Attack Method is selected:

![image](https://github.com/user-attachments/assets/f93c0060-9199-44a0-a176-538453d50e15)

The Credential Harvester Attack Method displays the following menu. In this menu1 for Web Templates is selected:

![image](https://github.com/user-attachments/assets/b0f4aa96-612d-4a10-89f8-23b8e3f1b08b)


It shows the following screen in which the ip address of the attacker need to be given which is the default value:

![image](https://github.com/user-attachments/assets/dc583ae8-f8a5-4c47-92c4-0672de397fa0)



In windows IE, on giving the url http://192.168.1.2, the fake Google page is displayed. The victim can enter the username and password

![image](https://github.com/user-attachments/assets/6b78e4f2-45ef-429f-9786-ed5fae47e9fe)


![image](https://github.com/user-attachments/assets/c6f49486-7e62-4639-a3f3-255eb84d0620)



SET logs the information regarding the Google credentials:

![image](https://github.com/user-attachments/assets/6f3a103d-07a7-4e5a-8746-6e8fce301632)


SET logs the information in the xml file under /root/.set directory:



![image](https://github.com/user-attachments/assets/53a1f69a-b834-49c7-a701-b17a7ce7ea54)


## RESULT:
The Social Engineering Toolkit (SET) is used to create backdoor is  examined successfully
