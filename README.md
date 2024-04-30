# Ex-07 Creating-a-backdoor-with-SET
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

## OUTPUT:
![image](https://github.com/Lakshmipriya2005/creating-a-backdoor-with-SET/assets/115525361/1a8c3de4-fc7f-4033-8e42-94d0d130354b)



The command sudo setoolkit in the prompt gives menu with set prompt. Select menu1 for Social Engineering Attacks:

## OUTPUT:
![image](https://github.com/Lakshmipriya2005/creating-a-backdoor-with-SET/assets/115525361/6c846b27-4ac2-40df-b48f-80a3b9eafac0)

It displays the following menu and select 2 for Website Attack Vectors:

## OUTPUT:
![image](https://github.com/Lakshmipriya2005/creating-a-backdoor-with-SET/assets/115525361/1263bf77-8da2-4a97-b88b-0f0d0e768e0c)



The website Attack Vectors displays the following menu. In this menu3 for Credential Harvester Attack Method is selected:

## OUTPUT:
![image](https://github.com/Lakshmipriya2005/creating-a-backdoor-with-SET/assets/115525361/131510f9-fc3e-4480-bc6b-36c56551ad5b)

The Credential Harvester Attack Method displays the following menu. In this menu1 for Web Templates is selected:

## OUTPUT:
![image](https://github.com/Lakshmipriya2005/creating-a-backdoor-with-SET/assets/115525361/25a53d1f-f056-42a2-8899-2b315ab258f4)

It shows the following screen in which the ip address of the attacker need to be given which is the default value:

## OUTPUT:
![image](https://github.com/Lakshmipriya2005/creating-a-backdoor-with-SET/assets/115525361/7ffe4da3-78b5-4927-a34b-e25fcc8406e5)

It shows the following screen in which the option Google can be selected:

## OUTPUT:
![image](https://github.com/Lakshmipriya2005/creating-a-backdoor-with-SET/assets/115525361/5cff32e6-230c-48a9-891c-1a9d7c9e41ee)

SET starts my Kali Linux Webserver on port 80, with the fake Google account login page. The setup is done:

## OUTPUT:
![image](https://github.com/Lakshmipriya2005/creating-a-backdoor-with-SET/assets/115525361/29260581-702c-4dcb-83f0-e4dbb94deea1)

In windows IE, on giving the url http://192.168.1.2, the fake Google page is displayed. The victim can enter the username and password

## OUTPUT:
![image](https://github.com/Lakshmipriya2005/creating-a-backdoor-with-SET/assets/115525361/8db86ae6-4c70-4e45-a112-fd74b85c03cd)

SET logs the information regarding the Google credentials:

## OUTPUT:
![image](https://github.com/Lakshmipriya2005/creating-a-backdoor-with-SET/assets/115525361/de35890b-2c51-47bb-bece-a1b880043632)

SET logs the information in the xml file under /root/.set directory:

## OUTPUT:
![image](https://github.com/Lakshmipriya2005/creating-a-backdoor-with-SET/assets/115525361/d6937c16-0595-45e7-ba0e-08b63e0f533a)



## RESULT:
The Social Engineering Toolkit (SET) is used to create backdoor is  examined successfully
