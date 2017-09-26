
# Hacking Challenges

Challenges that I authored/co-authored over the years for education and training purposes.

- [Scream (2012)](#scream)
- [Relativity (2013)](#relativity)
- [Persistence (2014)](#persistence)
- [Pipe (2015)](#pipe)
- [Sleepy (2015)](#sleepy)
- [K2 (2017)](#k2)

## Scream
<img align="left" src="https://upload.wikimedia.org/wikipedia/commons/f/f4/The_Scream.jpg" width="200" height="260">

```
  _________                                    
 /   _____/ ___________   ____ _____    _____  
 \_____  \_/ ___\_  __ \_/ __ \\__  \  /     \ 
 /        \  \___|  | \/\  ___/ / __ \|  Y Y  \
/_______  /\___  >__|    \___  >____  /__|_|  / .VM.
        \/     \/            \/     \/      \/ 
----------------------------------------------------------------------------
|  cReaTeD....: sagi-                |  DaTe......: 12-11-10               |
|  oS.........: Windows XP Home/Pro  |  oBJecTiVe.: Get the local user's   |
|               SP2/3 x86            |              password               |
|  iNSTaLLeR..: g0tmi1k              |  GReeTZ....: #vulnhub               |
----------------------------------------------------------------------------
```
### Download

**NOTE:** 
 Creation of the VM requires [VulnInjector](https://github.com/sagishahar/VulnInjector).
* [Download Link](https://www.vulnhub.com/entry/devrandom-scream,47/#download)
* [Download Link](https://drive.google.com/open?id=0B6EDpYQYL72rQ1ZDX0tOLU1qZUU_)

### Solution

[Watch Solution](https://youtu.be/aJktFdwhixY)

## Relativity
<img align="left" src="https://upload.wikimedia.org/wikipedia/en/a/a3/Escher%27s_Relativity.jpg" width="200" height="240">

```
     __________       .__          __  .__      .__  __
     \______   \ ____ |  | _____ _/  |_|__|__  _|__|/  |_ ___.__.
      |       _// __ \|  | \__  \\   __\  \  \/ /  \   __<   |  |
      |    |   \  ___/|  |__/ __ \|  | |  |\   /|  ||  |  \___  |
      |____|_  /\___  >____(____  /__| |__| \_/ |__||__|  / ____| ·VM·
             \/     \/          \/                        \/  -v1.0.1-
 +-----------------------------------------------------------------------+
 |  cReaTeD....: sagi-               |  DaTe......: 2013-11-29           |
 |  oS.........: Linux               |  oBJecTiVe.: Read /root/flag.txt  |
 |                                   |  GReeTZ....: g0tmi1k & l0ca1hoSt  |
 +-----------------------------------------------------------------------+
 |  VM HiSToRY:                                                          |
 |  v1.0.1 - 2013-11-29 Fixed a few bugs when using VirtualBox (thanks   |
 |           to Bas van den Berg - @barrebas)                            |
 |  v1.0   - 2013-11-16 Public release                                   |
 |  v0.0   - 2013-11-01 Private release - Zacon                          |
 |  v0.0   - 2013-06-29 Private release - HackFu                         |
 +-----------------------------------------------------------------------+
```
### Download

* [Download Link](https://www.vulnhub.com/entry/devrandom-relativity-v101,55/#download)
* [Download Link](https://drive.google.com/open?id=0B6EDpYQYL72rdHV1U2h6a1hwdjg)

### Solution

[Watch Solution](https://youtu.be/okW0KAojfNc)

## Persistence

<img align="left" src="https://upload.wikimedia.org/wikipedia/en/d/dd/The_Persistence_of_Memory.jpg" width="180" height="230">

```
██████╗█████████████╗███████ ██ █████████████████████████╗   ██╗█████████████╗
██╔══████╔════██╔══████╔════    ██╔════╚══██╔══██╔════████╗  ████╔════██╔════╝
██████╔█████╗ ██████╔███████ ██ ███████╗  ██║  █████╗ ██╔██╗ ████║    █████╗  
██╔═══╝██╔══╝ ██╔══██╚════██ ██ ╚════██║  ██║  ██╔══╝ ██║╚██╗████║    ██╔══╝  
██║    █████████║  █████████ ██ ███████║  ██║  █████████║ ╚████╚█████████████╗
╚═╝    ╚══════╚═╝  ╚═╚══════ ╚═ ╚══════╝  ╚═╝  ╚══════╚═╝  ╚═══╝╚═════╚══════╝

   "the fact of continuing in an opinion or course of action in spite of 
    difficulty or opposition"

                                                by sagi- & superkojiman


DISCLAIMER
----------
By using this virtual machine, you agree that in no event will we be liable 
for any loss or damage including without limitation, indirect or 
consequential loss or damage, or any loss or damage whatsoever arising 
from loss of data or profits arising out of or in connection with the use
of this software.

TL;DR - You are about to load up a virtual machine with vulnerabilities 
created by hackers. If something bad happens, it's not our fault.


ABOUT
-----
Persistence aims to provide you with challenging obstacles that block your
path to victory. It is perhaps best described by quotes made by some famous
people: 

"A little more persistence, a little more effort, and what seemed 
hopeless failure may turn to glorious success." - Calvin Coolidge

"Energy and persistence conquer all things." - Benjamin Franklin

"Persistence and resilience only come from having been given the chance
to work though difficult problems." - Gever Tulley


GOAL
----
Get a root shell and read the contents of /root/flag.txt to complete 
the challenge!


SETUP
-----
The virtual machine will get an IP address via DHCP, and it has been 
tested on the following hypervisors:

VMware Fusion 6
VMware Player 6
VMware Workstation 10
VirtualBox 4.3


SHOUT OUTS
----------
Thanks @VulnHub for kindly hosting this challenge, and thanks to 
@recrudesce for testing it and providing valuable feedback

```
### Download

* [Download Link](https://www.vulnhub.com/entry/persistence-1,103/#download)
* [Download Link](https://drive.google.com/open?id=0B6EDpYQYL72rRGRkaElGeUtaTk0)

### Solution

[Watch Solution](https://youtu.be/p5VKnzFum9s)

## Pipe

<img align="left" src="https://upload.wikimedia.org/wikipedia/en/b/b9/MagrittePipe.jpg" width="200" height="150">

```
__________.__               
\______   \__|_____   ____  
 |     ___/  \____ \_/ __ \ 
 |    |   |  |  |_> >  ___/ 
 |____|   |__|   __/ \___  >
             |__|        \/  ·VM· (MiNi CHaLLeNGe BuiLT FoR ZaCoN Vi)

+-----------------------------------------------------------------------+
|  cReaTeD....: sagi- (@s4gi_)      |  DaTe......: 2015-10-02           |
|  oS.........: Linux               |  oBJecTiVe.: Get /root/flag.txt   |
|                                   |  GReeTZ....: @zac0n               |
|                                   |  TeSTeRs...: @leonjza             |
|                                   |              @barrebas            |
+-----------------------------------------------------------------------+
```
### Download

* [Download Link](https://www.vulnhub.com/entry/devrandom-pipe,124/#download)
* [Download Link](https://drive.google.com/open?id=0B6EDpYQYL72ra1pKYThDTTMtUGc)

### Solution

[Watch Solution](https://youtu.be/tx3JvuTEqIc)

## Sleepy

<img align="left" src="https://vignette.wikia.nocookie.net/disney/images/a/a4/Sleepy1.png" width="230" height="150">

```
  _________.__                              
 /   _____/|  |   ____   ____ ______ ___.__.
 \_____  \ |  | _/ __ \_/ __ \\____ <   |  |
 /        \|  |_\  ___/\  ___/|  |_> >___  |
/_______  /|____/\___  >\___  >   __// ____| ·VM·
        \/           \/     \/|__|   \/

+-----------------------------------------------------------------------+
|  cReaTeD....: sagi- (@s4gi_)      |  DaTe......: 2015-10-02           |
|  oS.........: Linux               |  oBJecTiVe.: Get /root/flag.txt   |
|                                   |  GReeTZ....: @nanomebia           |
|                                   |  TeSTeRs...: @barrebas            |
|                                   |              Christopher Panayi   |
+-----------------------------------------------------------------------+
|  VM HiSToRY:                                                          |
|  v1.0 - Public release @ ZaCon VI "Capture the Flag (and in between)" |
|  V0.1 - Private release @ SecTalks Perth                              |
+-----------------------------------------------------------------------+
```
### Download

* [Download Link](https://www.vulnhub.com/entry/devrandom-sleepy,123/#download)
* [Download Link](https://drive.google.com/open?id=0B6EDpYQYL72rS3pDdW5OTXV2dU0)

### Solution

[Watch Solution](https://youtu.be/CN3dHC0giU8)

## K2
<img align="left" src="https://upload.wikimedia.org/wikipedia/commons/thumb/1/12/K2_2006b.jpg/1200px-K2_2006b.jpg" width="200" height="150">

```
 ____  __.________
|    |/ _|\_____  \
|      <   /  ____/
|    |  \ /       \
|____|__ \\_______ \ ·VM·
        \/        \/

+----------------------------------------------------------------------------+
|  cReaTeD....: sagi- (@s4gi_)      |  DaTe......: 2017-07-26                |
|  oS.........: Linux               |  oBJecTiVe.: Get /root/flag.txt        |
|                                   |  TeSTeR....: @leonjza                  |
+----------------------------------------------------------------------------+
|  VM DesCriPtiOn:                                                           |
|  This challenge was built to promote the Windows / Linux Local Privilege   |
|  Escalation workshop. A free of charge 3-day workshop that was created as  |
|  a give back to the community initiative.                                  |
|                                                                            |
|  <3 sagi-                                                                  |
+----------------------------------------------------------------------------+
| SSH AccEsS DeTaiLs:                                                        |
| Username: user                                                             |
| Password: password                                                         |
+----------------------------------------------------------------------------+
```
### Download

* [Download Link](https://drive.google.com/open?id=0B6EDpYQYL72rUkh2WHNJczFiOVE)

### Solution

[Watch Solution](https://youtu.be/9B1C_xi_yic)
