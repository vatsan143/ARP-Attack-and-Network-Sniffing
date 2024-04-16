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
![320285258-f79b008f-1b89-40aa-b777-d99f2a10446e](https://github.com/gowriganeshns/ARP-Attack-and-Network-Sniffing/assets/147368204/e4c52bd7-5c30-42b0-9933-acda2de0ba42)


From kali linux issue the command :
sudo arpspoof -i eth0 -t <target system> <gateway>
## OUTPUT:
![320285289-ba1076ae-2855-43f6-a1bc-01db536f9c15](https://github.com/gowriganeshns/ARP-Attack-and-Network-Sniffing/assets/147368204/76d25e34-e776-4b59-b1eb-ab2c3eb1684c)


 dsniff:






In Metasploit open the ftp console as below. Also you can try other ftp websites ftp.vim.org
## OUTPUT:



![320285340-48c0b4bd-6b2d-4a8e-8f8b-ea6f1609896d](https://github.com/gowriganeshns/ARP-Attack-and-Network-Sniffing/assets/147368204/43988efa-5533-4138-9fed-c97f72742144)

In Kali issue the following commands:
sudo dsnifff
## OUTPUT:

![320285379-73b6ab84-8381-4dd1-b387-e6c9221f866c](https://github.com/gowriganeshns/ARP-Attack-and-Network-Sniffing/assets/147368204/f05d038a-8f46-49ac-bf85-2d77c7c7200b)


Invoke the wireshark and examine the various menus  and controls of the tool:
![320285404-50f6ef76-2e81-457e-84c1-00bce85fb69a](https://github.com/gowriganeshns/ARP-Attack-and-Network-Sniffing/assets/147368204/816bb3cc-4e94-4e80-a244-8d5911f2c6b4)


## RESULT:
The kali linux tools for ARP Attack and Network Sniffing were identified successfully
