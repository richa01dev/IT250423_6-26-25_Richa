# IT250423_6-26-25_Richa
5 individual learning points in this file
1.Firstly we have to create command line in a desktop
2.Created a folder "Work"
3.Formed a text file in the folder 
4.Collected information in that text file
5.Used commands in command line.

Microsoft Windows [Version 10.0.26100.4351]
(c) Microsoft Corporation. All rights reserved.

C:\Work>dir
 Volume in drive C is Windows
 Volume Serial Number is A004-512C

 Directory of C:\Work

06/26/2025  10:44 AM    <DIR>          .
06/26/2025  10:47 AM                67 A221-PC001.txt
               1 File(s)             67 bytes
               1 Dir(s)  847,600,726,016 bytes free

C:\Work>notepad A221-PC001.txt

C:\Work>type  pc A221-PC001.txt
The system cannot find the file specified.
Error occurred while processing: pc.

A221-PC001.txt


This will contain information about this computer.

Second line

C:\Work>systeminfo

Host Name:                     A221-PC001
OS Name:                       Microsoft Windows 11 Pro
OS Version:                    10.0.26100 N/A Build 26100
OS Manufacturer:               Microsoft Corporation
OS Configuration:              Member Workstation
OS Build Type:                 Multiprocessor Free
Registered Owner:              Windows user
Registered Organization:       PEC
Product ID:                    00331-10000-00001-AA929
Original Install Date:         3/21/2025, 5:08:54 PM
System Boot Time:              6/13/2025, 9:02:23 AM
System Manufacturer:           Dell Inc.
System Model:                  OptiPlex SFF Plus 7010
System Type:                   x64-based PC
Processor(s):                  1 Processor(s) Installed.
                               [01]: Intel64 Family 6 Model 183 Stepping 1 GenuineIntel ~2100 Mhz
BIOS Version:                  Dell Inc. 1.23.0, 2/6/2025
Windows Directory:             C:\Windows
System Directory:              C:\Windows\system32
Boot Device:                   \Device\HarddiskVolume1
System Locale:                 en-us;English (United States)
Input Locale:                  en-us;English (United States)
Time Zone:                     (UTC-05:00) Eastern Time (US & Canada)
Total Physical Memory:         32,457 MB
Available Physical Memory:     13,434 MB
Virtual Memory: Max Size:      34,505 MB
Virtual Memory: Available:     8,702 MB
Virtual Memory: In Use:        25,803 MB
Page File Location(s):         C:\pagefile.sys
Domain:                        networksupport.local
Logon Server:                  \\SRV01
Hotfix(s):                     5 Hotfix(s) Installed.
                               [01]: KB5056579
                               [02]: KB5048779
                               [03]: KB5050575
                               [04]: KB5063060
                               [05]: KB5059502
Network Card(s):               2 NIC(s) Installed.
                               [01]: VirtualBox Host-Only Ethernet Adapter
                                     Connection Name: Ethernet 2
                                     DHCP Enabled:    No
                                     IP address(es)
                                     [01]: 192.168.56.1
                                     [02]: fe80::ce8f:db13:b41f:942a
                               [02]: Intel(R) Ethernet Connection (17) I219-LM
                                     Connection Name: Ethernet
                                     DHCP Enabled:    Yes
                                     DHCP Server:     192.168.221.1
                                     IP address(es)
                                     [01]: 192.168.221.152
                                     [02]: fe80::7f68:fe96:a69b:7fd
Virtualization-based security: Status: Running
                               Required Security Properties:
                                     Base Virtualization Support
                               Available Security Properties:
                                     Base Virtualization Support
                                     Secure Boot
                                     DMA Protection
                                     UEFI Code Readonly
                                     SMM Security Mitigations 1.0
                                     Mode Based Execution Control
                                     APIC Virtualization
                               Services Configured:
                                     Hypervisor enforced Code Integrity
                               Services Running:
                                     Hypervisor enforced Code Integrity
                                     Hypervisor-Enforced Paging Translation
                               App Control for Business policy: Enforced
                               App Control for Business user mode policy: Off
                               Security Features Enabled:
Hyper-V Requirements:          A hypervisor has been detected. Features required for Hyper-V will not be displayed.

C:\Work>ipconfig/all

Windows IP Configuration

   Host Name . . . . . . . . . . . . : A221-PC001
   Primary Dns Suffix  . . . . . . . : networksupport.local
   Node Type . . . . . . . . . . . . : Hybrid
   IP Routing Enabled. . . . . . . . : No
   WINS Proxy Enabled. . . . . . . . : No
   DNS Suffix Search List. . . . . . : networksupport.local

Ethernet adapter vEthernet (Default Switch):

   Connection-specific DNS Suffix  . :
   Description . . . . . . . . . . . : Hyper-V Virtual Ethernet Adapter
   Physical Address. . . . . . . . . : 00-15-5D-B6-AB-0B
   DHCP Enabled. . . . . . . . . . . : No
   Autoconfiguration Enabled . . . . : Yes
   Link-local IPv6 Address . . . . . : fe80::e630:f075:4db8:4a19%19(Preferred)
   IPv4 Address. . . . . . . . . . . : 172.25.128.1(Preferred)
   Subnet Mask . . . . . . . . . . . : 255.255.240.0
   Default Gateway . . . . . . . . . :
   DHCPv6 IAID . . . . . . . . . . . : 318772573
   DHCPv6 Client DUID. . . . . . . . : 00-01-00-01-2F-6F-B7-54-CC-96-E5-36-D1-AD
   NetBIOS over Tcpip. . . . . . . . : Enabled

Ethernet adapter Ethernet:

   Connection-specific DNS Suffix  . : networksupport.local
   Description . . . . . . . . . . . : Intel(R) Ethernet Connection (17) I219-LM
   Physical Address. . . . . . . . . : CC-96-E5-36-D1-AD
   DHCP Enabled. . . . . . . . . . . : Yes
   Autoconfiguration Enabled . . . . : Yes
   Link-local IPv6 Address . . . . . : fe80::7f68:fe96:a69b:7fd%17(Preferred)
   IPv4 Address. . . . . . . . . . . : 192.168.221.152(Preferred)
   Subnet Mask . . . . . . . . . . . : 255.255.255.0
   Lease Obtained. . . . . . . . . . : Friday, June 13, 2025 9:03:34 AM
   Lease Expires . . . . . . . . . . : Friday, June 27, 2025 9:07:32 AM
   Default Gateway . . . . . . . . . : 192.168.221.1
   DHCP Server . . . . . . . . . . . : 192.168.221.1
   DHCPv6 IAID . . . . . . . . . . . : 399283941
   DHCPv6 Client DUID. . . . . . . . : 00-01-00-01-2F-6F-B7-54-CC-96-E5-36-D1-AD
   DNS Servers . . . . . . . . . . . : 192.168.2.203
                                       192.168.2.205
                                       192.168.2.155
   Primary WINS Server . . . . . . . : 192.168.2.205
   Secondary WINS Server . . . . . . : 192.168.2.203
   NetBIOS over Tcpip. . . . . . . . : Enabled

Ethernet adapter Ethernet 2:

   Connection-specific DNS Suffix  . :
   Description . . . . . . . . . . . : VirtualBox Host-Only Ethernet Adapter
   Physical Address. . . . . . . . . : 0A-00-27-00-00-05
   DHCP Enabled. . . . . . . . . . . : No
   Autoconfiguration Enabled . . . . : Yes
   Link-local IPv6 Address . . . . . : fe80::ce8f:db13:b41f:942a%5(Preferred)
   IPv4 Address. . . . . . . . . . . : 192.168.56.1(Preferred)
   Subnet Mask . . . . . . . . . . . : 255.255.255.0
   Default Gateway . . . . . . . . . :
   DHCPv6 IAID . . . . . . . . . . . : 168427559
   DHCPv6 Client DUID. . . . . . . . : 00-01-00-01-2F-6F-B7-54-CC-96-E5-36-D1-AD
   NetBIOS over Tcpip. . . . . . . . : Enabled

website that explains how to find the name of your PC

https://www.youtube.com/watch?v=5gBSS5mHLF8
