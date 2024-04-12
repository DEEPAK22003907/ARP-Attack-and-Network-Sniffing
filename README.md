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
![Screenshot 2024-04-12 201828](https://github.com/DEEPAK22003907/ARP-Attack-and-Network-Sniffing/assets/119404520/f2a86a1d-26c3-4c67-86a6-da543b10173d)


From kali linux issue the command :
sudo arpspoof -i eth0 -t <target system> <gateway>
## OUTPUT:
![Screenshot 2024-04-12 201858](https://github.com/DEEPAK22003907/ARP-Attack-and-Network-Sniffing/assets/119404520/2b48b821-7c91-4be5-b2fa-54599ec1d1f2)


 dsniff:
 
In Metasploit open the ftp console as below. Also you can try other ftp websites ftp.vim.org

## OUTPUT:
![Screenshot 2024-04-12 201931](https://github.com/DEEPAK22003907/ARP-Attack-and-Network-Sniffing/assets/119404520/6ff048b1-7b65-444c-a769-92b97ce93ffa)



In Kali issue the following commands:

sudo dsnifff

## OUTPUT:

![Screenshot 2024-04-12 202006](https://github.com/DEEPAK22003907/ARP-Attack-and-Network-Sniffing/assets/119404520/a6f0c3cc-619b-47ab-85f1-b7ca78707777)


Invoke the wireshark and examine the various menus  and controls of the tool:
![Screenshot 2024-04-12 202050](https://github.com/DEEPAK22003907/ARP-Attack-and-Network-Sniffing/assets/119404520/1828cb0d-bd6b-43c2-8acd-44af96e5fd7d)



## RESULT:
The kali linux tools for ARP Attack and Network Sniffing were identified successfully
