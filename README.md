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

![image](https://github.com/Catty12384/creating-a-backdoor-with-SET/assets/120629225/c1343721-459a-4940-ab85-b36667141254)

It displays the following menu and select 2 for Website Attack Vectors:

![image](https://github.com/Catty12384/creating-a-backdoor-with-SET/assets/120629225/6ce201bc-1f4b-4417-b4b5-cda3bd7a5cc6)

The website Attack Vectors displays the following menu. In this menu3 for Credential Harvester Attack Method is selected:

![image](https://github.com/Catty12384/creating-a-backdoor-with-SET/assets/120629225/b04dc229-fec1-4036-8563-cff05d113f73)

The Credential Harvester Attack Method displays the following menu. In this menu1 for Web Templates is selected:

![image](https://github.com/Catty12384/creating-a-backdoor-with-SET/assets/120629225/afb11ff3-690f-4167-81c8-4c65de0bfb52)

It shows the following screen in which the ip address of the attacker need to be given which is the default value:

![image](https://github.com/Catty12384/creating-a-backdoor-with-SET/assets/120629225/55036490-0634-4844-9ffe-8017419f3f39)

It shows the following screen in which the option Google can be selected:

![image](https://github.com/Catty12384/creating-a-backdoor-with-SET/assets/120629225/340c08fb-0c74-4b38-917e-bad6e1a6355f)

SET starts my Kali Linux Webserver on port 80, with the fake Google account login page. The setup is done:

![image](https://github.com/Catty12384/creating-a-backdoor-with-SET/assets/120629225/bd4da206-7e8d-481d-bfac-2ac02ffc51dc)

In windows IE, on giving the url http://192.168.1.2, the fake Google page is displayed. The victim can enter the username and password

![image](https://github.com/Catty12384/creating-a-backdoor-with-SET/assets/120629225/5a6f29cd-ed7d-4185-961b-a784dc016904)

SET logs the information regarding the Google credentials:

![image](https://github.com/Catty12384/creating-a-backdoor-with-SET/assets/120629225/45b534bc-5248-4557-b87f-bcf43874e392)

SET logs the information in the xml file under /root/.set directory:

![image](https://github.com/Catty12384/creating-a-backdoor-with-SET/assets/120629225/2f7318ef-8ade-4970-921b-95f8fcdc06e8)

## RESULT:
The Social Engineering Toolkit (SET) is used to create backdoor is  examined successfully
