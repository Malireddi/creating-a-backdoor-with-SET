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
![1](https://github.com/user-attachments/assets/8e3bb125-d21f-441c-937d-35c0527cfd8b)

### It displays the following menu and select 2 for Website Attack Vectors:

![WhatsApp Image 2025-05-05 at 10 47 01_27b5799e](https://github.com/user-attachments/assets/9ab4ab78-f198-4aaf-a14a-c72da6e3e07c)

### The website Attack Vectors displays the following menu. In this menu3 for Credential Harvester Attack Method is selected:
![WhatsApp Image 2025-05-05 at 10 48 23_10c56e12](https://github.com/user-attachments/assets/fb3d9cb4-2fae-4507-817d-a3acf3ce4e22)

### The Credential Harvester Attack Method displays the following menu. In this menu1 for Web Templates is selected:

![4](https://github.com/user-attachments/assets/27e63d5b-13d5-4f20-948e-eb9358598607)

### It shows the following screen in which the ip address of the attacker need to be given which is the default value:

![WhatsApp Image 2025-05-05 at 10 49 11_25f36169](https://github.com/user-attachments/assets/1c82381e-40b0-4b1d-b86f-220ac287cb74)

### It shows the following screen in which the option Google can be selected

![WhatsApp Image 2025-05-05 at 10 50 22_4f03ab8f](https://github.com/user-attachments/assets/e5fbb7cb-f713-4b74-84f8-4ab9df05e31f)

### SET starts my Kali Linux Webserver on port 80, with the fake Google account login page. The setup is done:

![WhatsApp Image 2025-05-05 at 10 55 00_200e4490](https://github.com/user-attachments/assets/ca1dc124-4f39-4e10-8273-45e3e65ec18d)

### In windows IE, on giving the url http://192.168.25.***, the fake Google page is displayed. The victim can enter the username and password
![WhatsApp Image 2025-05-05 at 10 56 34_96b9d118](https://github.com/user-attachments/assets/c197c226-0ef9-4724-bb46-72f79fe1839d)




## RESULT:
The Social Engineering Toolkit (SET) is used to create backdoor is  examined successfully
