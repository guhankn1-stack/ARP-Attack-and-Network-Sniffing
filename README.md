# ARP-Attack-and-Network-Sniffing
# Explore Network Sniffing and ARP Attacks

# AIM:

To explore network sniffing and ARP Attacks

## STEPS:

### Step 1:

Install kali linux either in partition or virtual box or in live mode

### Step 2:

Investigate on the various categories of tools as follows:


### Step 3:
Open terminal and try execute some kali linux commands

## ARP Attacks:  
ARP spoofing: A hacker sends fake ARP packets that link an attacker's MAC address with an IP of a computer already on the LAN. 
Boot kali and Windows7 virtual machines.
In windows 7 give the command arp -a
## OUTPUT:
<img width="1382" height="518" alt="image" src="https://github.com/user-attachments/assets/40d19b6d-a36b-4225-a287-4325a2e91380" />




From kali linux issue the command :
sudo arpspoof -i eth0 -t <target system> <gateway>
## OUTPUT:
<img width="1147" height="518" alt="image" src="https://github.com/user-attachments/assets/4c5b8198-46a8-44ce-919f-190277e4cd46" />




dsniff:
In Metasploit open the ftp console as below. Also you can try other ftp websites ftp.vim.org
## OUTPUT:
<img width="1290" height="507" alt="image" src="https://github.com/user-attachments/assets/e13b9a72-2fa4-45be-84c4-43da099dcb65" />






In Kali issue the following commands:sudo dsnifff
## OUTPUT:
<img width="821" height="517" alt="image" src="https://github.com/user-attachments/assets/e836bccb-910b-4a76-8223-1904928415c3" />




Invoke the wireshark and examine the various menus  and controls of the tool:

![image](https://github.com/NAVEENKUMAR4325/ARP-Attack-and-Network-Sniffing/assets/119479566/6959c32b-aee6-41c2-8084-75b5eea80fdc)


## RESULT:
The kali linux tools for ARP Attack and Network Sniffing were identified successfully
