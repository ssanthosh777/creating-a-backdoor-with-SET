# creating-a-backdoor-with-SET
creating a backdoor with SET - Ethical Hacking Techniques course
```
NAME: SANTHOSH S
REG.NO: 212224100052
```

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
## OUTPUT
<img width="1920" height="1103" alt="Screenshot From 2026-02-14 14-00-56" src="https://github.com/user-attachments/assets/9694b813-b5ed-472b-8507-6f1544771fdc" />




The command sudo setoolkit in the prompt gives menu with set prompt. Select menu1 for Social Engineering Attacks:
## OUTPUT
<img width="1034" height="646" alt="Screenshot From 2026-02-14 14-03-08" src="https://github.com/user-attachments/assets/572f000a-79c5-4495-89fc-59eebd4e5ef0" />



It displays the following menu and select 2 for Website Attack Vectors:
## OUTPUT
<img width="1043" height="837" alt="Screenshot From 2026-02-14 14-03-42" src="https://github.com/user-attachments/assets/4dafbdaf-aef4-4294-b3f4-d5ec53e95ce4" />



The Credential Harvester Attack Method displays the following menu. In this menu1 for Web Templates is selected:
## OUTPUT
<img width="763" height="402" alt="Screenshot From 2026-02-14 14-04-40" src="https://github.com/user-attachments/assets/b6f9cd2a-dcdf-4440-a62b-c52034616b9a" />




It shows the following screen in which the ip address of the attacker need to be given which is the default value:
## OUTPUT
<img width="1553" height="836" alt="Screenshot From 2026-02-14 14-05-34" src="https://github.com/user-attachments/assets/eaf6a656-5fc3-49b2-97a3-84705f81cbe9" />




It shows the following screen in which the option Google can be selected:
## OUTPUT
<img width="1426" height="901" alt="Screenshot From 2026-02-14 14-07-00" src="https://github.com/user-attachments/assets/8eb43203-d64b-4460-90a4-acb38a852366" />






SET starts my Kali Linux Webserver on port 80, with the fake Google account login page. The setup is done




In windows IE, on giving the url http://172.20.10.12 (use appropriate IP address), the fake Google page is displayed. The victim can enter the username and password
## OUTPUT
<img width="1920" height="1200" alt="Screenshot (34)" src="https://github.com/user-attachments/assets/bb29052f-1558-4148-93bc-62fe9c5e0a9b" />


SET logs the information regarding the Google credentials:
## OUTPUT
<img width="1215" height="675" alt="Screenshot From 2026-02-14 14-09-52" src="https://github.com/user-attachments/assets/59e41e15-b32d-4b7a-8e84-ef972b0cecd4" />



SET logs the information in the xml file under /root/.set directory








## RESULT:
The Social Engineering Toolkit (SET) is used to create backdoor is  examined successfully
