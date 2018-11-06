---
title: Computer Science Notes
layout: post
author: soham.deshpande
permalink: /computer-science-notes/
source-id: 19XM7rrtULEpPILO03KSx8Qpw2rBu3_NhAkTqYoRZSe0
published: true
---
<table>
  <tr>
    <td>Notes</td>
  </tr>
</table>


<table>
  <tr>
    <td>Overflow- a computer can only handle 8 bit. If there is a 9th or more  bit, it is called an overflow</td>
  </tr>
</table>


<table>
  <tr>
    <td>Addition</td>
  </tr>
</table>


<table>
  <tr>
    <td>512</td>
    <td>256</td>
    <td>128</td>
    <td>64</td>
    <td>32</td>
    <td>8</td>
    <td>4</td>
    <td>2</td>
    <td>1</td>
    <td></td>
  </tr>
  <tr>
    <td></td>
    <td></td>
    <td>0</td>
    <td>1</td>
    <td>1</td>
    <td>0</td>
    <td>0</td>
    <td>1</td>
    <td>1</td>
    <td>no.1</td>
  </tr>
  <tr>
    <td></td>
    <td></td>
    <td>1</td>
    <td>1</td>
    <td>0</td>
    <td>1</td>
    <td>1</td>
    <td>1</td>
    <td>1</td>
    <td>no.2</td>
  </tr>
  <tr>
    <td></td>
    <td>1</td>
    <td>0</td>
    <td>1</td>
    <td>0</td>
    <td>0</td>
    <td>0</td>
    <td>1</td>
    <td>0</td>
    <td>total</td>
  </tr>
  <tr>
    <td></td>
    <td></td>
    <td>1</td>
    <td>1</td>
    <td>1</td>
    <td>1</td>
    <td>1</td>
    <td>1</td>
    <td></td>
    <td>carry</td>
  </tr>
</table>


<table>
  <tr>
    <td>
To multiply a binary digit by 2, you do a binary shift. This is when you add a 0 at the end.


1010101010 x 2=
10101010100

1.23456 x 10⁷
That is called standard form in maths. In binary it is called a floating point.

In binary, the maximum number of "things" is 256 in 8 bit. You can only count upto 255 as you skip zero.

 



In ascii there are only 128 possibilities.

  
8 bits = 1 Byte
1024 Bytes = 1 kB
1024 kB = 1mB
1024 mB = 1GB
1024 GB = 1TB
1024 TB = 1 PetaBYte
        = 1 ExaByte
        = 1 ZetaBYte
        = 1 YottaByte




A FLOP is a floating point operation. Computers run on teraflops.



08 bit = 256   = 2⁸
16 bit = 25536 = 2¹⁶
32 bit =       = 2 32
64 bit =       = 2 64




2 1
2 0
2 -1
2 -2
2
1
1/2
1/4


 
</td>
  </tr>
</table>


<table>
  <tr>
    <td>  4A = 74
+ DC = 220
 ---------
 126

 49
 56
----
 9F

tinyurl.com/ydy9t35n
Computing resources
https://sites.google.com/challoners.org/computing-resources/python_coding_resources
</td>
  </tr>
</table>


<table>
  <tr>
    <td>There are 4 main types. Boolean 

Why is ascii 7 bit and unicode 8 bit?- Exam question
Unicode can encode 256 characters. Standard unicode works in 8 bit however has unicode is universal, it has to work for different languages. This adds more characters to Unicode. That is why unicode now works in 32 bit which has around 4 billion possibilities.



THE FETCH/EXECUTE/DECODE CYCLE#

http://www.hartismere.com/CPU-Fetch-Decode-Execute-Animation-20398


How a computer works

It consists of memory and CPU. The key parts in the CPU are 

AC - Accumulator.Holds pieces of processed data
Arithmetic Logic unit-  adds, divides,multiply, greater than …
Control Unit- Decides what is going to happen

Registers:

MAR- Memory address register
CIR- Control instruction register
PC - Program counter
MDR- Memory data register
 

Assembly language is basic instruction set

The main component on any computer is the CPU, which stands for Central Processing Unit. The CPU gets instructions and then performs calculations. If a processor can only process one set of instructions at a single, that means it has only a single core.

the PCI Special Interest Group (PCI-SIG) said that the new version "doubles the interconnect bit rate from 2.5 GT/s to 5 GT/s." Most of us are used to seeing bus speeds specified in Gbps, or gigabits per second, but GT/s stands for gigatransfers per second.




VON NEUMANN ARCHITECTURE

CPU-1-The central processing unit. This carries out all of the programs.

RAM-2- Random access memory. This stores data and machine code which can be called upon at any time. Volatility-  When the power is turned off, you lose everything


MOTHERBOARD- All-The main circuit board

PCI EXPANSION-3- It is a circuit board which can be slotted in to add functionality via the expansion bus
NORTH BRIDGE-Reads”Gigabyte” It is a core logic chipset which is used for tasks which require the highest performance. It holds together the ram and cpu. It has a faster bus.

SOUTH BRIDGE-4-It is a chipset which handles lower performance tasks
BIOS- Basic input output system. It is a firmware which is used during power on of the device.
STORAGE- Stores the data. 

SATA- Serial ATA . You can mirror 

ROM- Read only memory. E.g Cds e.t.c. The BIOS is stored  on ROM.

Peripherals-  Around the outside of the computer.External memory, keyboards, monitors, microphones e.t.c

Draw the image and label the motherboard with the labels and explain in our own words.


                                                     Bios







                                     Storage</td>
  </tr>
</table>


<table>
  <tr>
    <td>STANDARDS: Hardware based. Usb, HDMI. It is physical. 

PROTOCOLS: Software types, Bluetooth, Wi-Fi, HTTP. They allow devices to communicate with each other


HTTP- Hypertext transfer protocol
HTTPS- Hypertext transfer protocol secure


HTTPS- The company has to buy a certificate to confirm they are secure. The user sends information which gets encrypted and then the server on the other side decrypts it. The other side has to know the key to decrypt it.



Run length is a form of data compression
Run length encoding will not lose any of the original data. It is a form of lossless compression










Social Engineering techniques to hack devices  

1.The most common social engineering attacks come from phishing. 91% of data breaches comes from phishing

2.  Company refund ransomware. It is massive phishing attack that has a ransomware attachment. The attachment is an infected Word file, which holds  ransomware and encrypts the files 

3. Banking link scam. Hackers send you an email with a phony link to your bank, tricking you into entering in your bank ID and password.

4. Social media link scam. There has been instances where people have exploited the fact that lots of people made videos for a celebrity whom may have died. The hackers made phony videos which led to a survey where you had to input your details.

5.Pretexting is form of social engineering where attackers focus on creating a good pretext (a fake scenario) that they can use to try and steal their victims' personal information. These types of attacks commonly take the form of a scammer who pretends that they need certain bits of information from their target in order to confirm their identity.

6. Baiting. Baiters may offer users free music or movie downloads, if they surrender their login credentials to a certain site.


7.Another social engineering attack type is known as tailgating or "piggybacking." These types of attacks involve someone who lacks the proper authentication following an employee into a restricted area.




From Aqa Specification

Blagging is the act of creating and using an
invented scenario to engage a targeted victim in
a manner that increases the chance the victim
will divulge information or perform actions that
would be unlikely in ordinary circumstances.

Phishing is a technique of fraudulently obtaining
private information, often using email or SMS.

Pharming is a cyber attack intended to redirect
a website's traffic to another, fake site.
   
Shouldering is observing a person's private
information over their shoulder eg cashpoint
machine PIN numbers.





Sorting

Bubble sort

Check and swap.
https://repl.it/@SohamDeshpande/Check-and-Swap







Network security

If a standalone device is compromised, the data on that device is at risk. If a network is compromised, all the data on the network is at risk!
The Data Protection Act makes it a legal responsibility for businesses and other organisations to keep personal data secure.

What could happen if your network security failed?

Data could be stolen
Data could be changed
You might lose access to your data
“Malware” (malicious software) could be installed on your network

Goals of network security

Keep unauthorised people from accessing the network resources
Make sure authorised people CAN access the network resources

Methods of keeping a network secure

Authentication
User access levels
Encryption
Firewall
MAC address filtering
Backups

Authentication

Passwords enable the identification of genuine, authorised users. 
Passwords should be “strong”. The definition of a strong password changes as technology advances. We used to be told to make sure our passwords contained a mixture of numbers, letters (uppercase and lowercase) and punctuation, but current advice is that the length of your password is very important, the longer the better (but you must be able to remember it)!
Passwords should never be shared or written down.
Passwords should be changed regularly, but not too frequently. If you change your password very often then you are more likely to forget it, or start using a “system” for creating your password, so it could be easily worked out from an old password.
If you think someone knows your password, change it immediately!
Accounts can be “locked” after a certain number of incorrect passwords have been entered, this helps to prevent “brute force” attacks on an account (where a computer program repeatedly tries different passwords).
Biometric data (such as fingerprints or iris patterns) can be used to identify a person, so can be used for authentication.
Dongles (small hardware devices that can be connected to a computer) can be used like a key to authenticate a person, as can your mobile phone. You might have been asked for your mobile phone number so that a code could be sent to you to allow you access to an account.

Two Factor Authentication (2FA) is recommended these days. There are 3 types of authentication; something you know (like a password), something you are (biometric data) and something you have (like a dongle, or your mobile phone). Using TWO of these types of authentication together (instead of just one) is 2FA.

User access levels 

User access levels can be set for disks, folders or files so that users can only access the things they need to access. Various levels of access can be granted:
No Access - the file/folder/disk might not even be visible to the user in this case
Read Only Access - the user can read what is there but not make changes to it
Read-Write Access - the user can read what is there, write new data but not necessarily edit or delete what is already there
Edit Access - the user can edit the data

Encryption

This scrambles data to make it unreadable to anyone who DOES manage to access or intercept it.

Firewall

This stops unwanted Internet traffic from accessing the LAN. It can block IP addresses or ports (File Transfer Protocol uses port 21 for example).
Firewall software is often provided with operating systems but can also be bought or even obtained free of charge from organisations like banks. Always be certain that you trust an organisation that you are getting free software from.

MAC address filtering

This defines which physical devices can access your network, because each Network Interface Card has its own unique MAC address.

Backups

Backups are crucial in helping to secure access to your data. Even if someone does gain access to your network and changes, destroys or restricts your access to your data, at least you will be able to get it back.





Topologies

Advantages of networking:
You can share devices such as printers, scanners and external drives.
Easy to share folders and files of data.
Backup is taken care of centrally.
Disadvantages of networking:
Security is harder to control.
If a network shares one internet connection this can slow down the speed of downloading.
More costly to run as the LAN needs to be on all the time.
More complex to maintain a network
Local Area Networks (LANs):
Local Area Networks usually cover relatively small geographical areas.
Local Area Networks are often owned and controlled/managed by a single person or organisation.
Wide Area Networks (WANs):
The Internet is the biggest example of a Wide Area Network.
Wide Area Networks usually cover a wide geographic area.
Wide Area Networks are often under collective or distributed ownership.
Personal Area Networks (PANs): 
A Personal Area Network is a computer network used to connect devices centered on an individual person.
Bluetooth is an example of a Wireless Personal Area Network (WPAN). 
Bluetooth is a low-powered Personal Area Network carried over a short distance.
Personal Area Networks can be used for communication amongst the connected devices themselves, OR for connecting to a higher level network and the Internet (an “uplink”) where one master device takes up the role as “gateway”.  For example, if your phone did not have a connection to the Internet, you may have used a Bluetooth connection to a friend’s smartphone to allow you to access the Internet via their network.

Extra hardware needed to operate a LAN:
Network Interface Card (NIC) - a circuit board or card that is installed in a computer so that it can be connected to a network. Every NIC has a unique Media Access Control (MAC) address.
Switches - a component of a LAN which knows the MAC addresses of each connected device.
Routers - a networking device that forwards data packets between computer networks.
Hub - a common connection point for devices in a network. Commonly used to connect segments of a LAN. The hub contains multiple ports. When a packet arrives at one port, it is copied to the other ports so that all segments of the LAN can see all packets.





Connectivity


Some possible causes of buffering (symptoms of buffering = video pause or audio break up etc):
The receiving/client device may be old and therefore not have the necessary processing power. Closing applications might help.
The receiving/client device may not have enough memory. Installing extra RAM might help.
Wi-Fi provides lower transfer speed than using an Ethernet cable. Connecting your device straight to the router with a cable might help, or at least moving your device closer to the router.
Dual Network Mode: mobile devices can maintain a connection to a carrier network and Wi-Fi in parallel. Disabling carrier or Wi-Fi mode can help with network performance. Computers can connect to Wi-Fi and Ethernet in parallel. Disconnecting from the Wi-Fi network and using the Ethernet connection can help with network performance.
General network traffic: if another device on your network is performing a backup or transferring a large amount of data it could degrade overall network performance. Powering off other networked machines that are not currently being used can help reduce network traffic.
Faulty network hardware (such as the network card, router or network cable) can cause intermittent connectivity problems.
Internet Service Provider (ISP) bandwidth limitations or throttling can cause problems.
Small, local ISPs are often served by larger “upstream” providers. Issues with the upstream providers can cause network problems at the “downstream” ISP.









</td>
  </tr>
</table>


