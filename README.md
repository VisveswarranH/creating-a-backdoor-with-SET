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

![image](https://github.com/user-attachments/assets/adf3577b-1b9e-4d8d-8034-2a764cc2cb86)

The command sudo setoolkit in the prompt gives menu with set prompt. Select menu1 for Social Engineering Attacks:

![image](https://github.com/user-attachments/assets/35fb5e97-0cc6-4515-b5fd-fed6935e0a63)

![image](https://github.com/user-attachments/assets/44d889c2-b21a-47f4-98a5-2dc567f95c24)





It displays the following menu and select 2 for Website Attack Vectors:

![image](https://github.com/user-attachments/assets/cedb45c9-01ab-43d1-bb0b-d609b83a60bc)



The website Attack Vectors displays the following menu. In this menu3 for Credential Harvester Attack Method is selected:
![image](https://github.com/user-attachments/assets/d230f0b7-985a-4e37-abfc-ca2822471269)


The Credential Harvester Attack Method displays the following menu. In git push origin mthis menu1 for Web Templates is selected:
![image](https://github.com/user-attachments/assets/b204e2fb-262c-4ecd-a3ad-a64947e41153)


It shows the following screen in which the ip address of the attacker need to be given which is the default value:

It shows the following screen in which the option Google can be selected:
![image](https://github.com/user-attachments/assets/daeb7dad-81f2-445b-bbbb-76b6eae5c83b)



SET starts my Kali Linux Webserver on port 80, with the fake Google account login page. The setup is done:

![image](https://github.com/user-attachments/assets/82d92cd5-a5b7-4c9a-8090-31dd0596157e)


In windows IE, on giving the url http://192.168.169.88, the fake Google page is displayed. The victim can enter the username and password
![image](https://github.com/user-attachments/assets/bbe2cd35-6170-49df-b6b8-5a929ab8f24e)



SET logs the information regarding the Google credentials:
![image](https://github.com/user-attachments/assets/cd4b4c80-ed17-4270-90cf-12daf6d9c441)

SET logs the information in the xml file under /root/.set directory:
![image](https://github.com/user-attachments/assets/2ddee83c-b8ad-4e56-bfa3-289a62a28074)

## RESULT:
The Social Engineering Toolkit (SET) is used to create backdoor is  examined successfully
