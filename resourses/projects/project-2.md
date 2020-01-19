# PROJECT 2: CRACKING WEB

## Description:
This project is about cracking WEP. The WEP vulnerabilities have been
long established and this project lets you have a little fun with it
yourselves using prominent tools that are freely available online for
download. Not all of them might work on your choice of Operating System
and/or wireless devices/laptops. It is for that reason, you are provided
here with a list of tools that have been popularly and quite
successfully used in cracking WEP encryption over 802.11b/g. First set
up a wireless computer to associate to an AP using WEP and choose a
relatively simple WEP key. Next you would need to have a laptop running
a software that captures enormous number of packets through packet dump,
a software that captures the IV’s appended to these captured packets and
then another that cracks these IV’s to reveal the WEP key. The commonly
used tools depending on your OS are (this list is by no means
comprehensive):
- WEPCrack – Most popular Perl-based WEP encryption cracking tool
- AirSnort – Passively captures packets and recovers WEP encryptions
- Aircrack-ng – ARP spoof/injection using aireplay-ng
- Kismet – Network Sniffer, can grab IVs as well
- Airodump – GrabbingIVs
- Aircrack – Cracking the IVs
- Commview – Capturing the Packets in Windows.

There are many tutorials
  available online and so as a part of the exercise, you are required to
  dig them out. You are required to download some of the tools listed
  above and follow the procedure(s) listed in some of these tutorials.
  Obviously revealing the key might take different times when different
  tools are used. Though the project seems small, your wireless device
  might not be able to inject packets into the WEP enabled network, thus
  preventing an Active attack. This means that you might have to capture
  packets to get a fair amount of IVs and then crack the WEP. So you
  might want to start early.

## Project Specifics:
You need to use the software mentioned above to
  crack two different WEP keys (both 40 bit keys). (Cracking one key is
  sufficient if time is an issue.) Use a character-based password and a
  numerical password if you are using a password/passphrase conversion
  (see, e.g., http://www.powerdog.com/wepkey.cgi).

**Deliverables**: There are two components to this project, a report and
a demonstration.
1. Report:
No more than a 5-8 page report with proper screenshots and appropriate schematic
diagrams/flowcharts that describe all the tools you have explored and also references to
the tutorials consulted. The report should also contain the basic analysis and methodology
of cracking WEP in detail.
You should also indicate which software you used and which laptops you used to crack
WEP. Do include the specifics about the hardware used like the Make, Model number,
OS, CPU speed, Memory capacity and Wireless Card make and model.
2. Demonstration: You only need to demonstrate the cracking of two
  different WEP keys (both 40 bit keys). The demonstration may be held
  in a lab or class room. A sign-up sheet will be set
  up a few days prior to the submission date. If you finish the project
  sooner than the deadline, demonstration can be held prior to the
  deadline as well.

**Special Notes**:
1. If you don’t have access to an AP that has WEP encryption enabled (e.g., the UB
APs don't have WEP encryption enabled), then you can do the following: Person
A configures his laptop to accept ad-hoc connections (hence function as an AP)
and turn WEP encryption on. Person B then connects his laptop to the (pseudo)
AP, which is laptop A. Person C tries to sniff the password.
2. Since the project depends on the maker of your wireless card, you might not be
able to actually crack a WEP (last time when this project was offered, only one
group was able to crack). However, the project is for you to understand and see
the weaknesses of WEP. If you are unable to achieve the cracking, report on what
you have accomplished.
3. Since each team will need three laptops if you decide to set up the system in an
ad-hoc connection fashion, two groups can collaborate and provide a joint report.
If you do collaborate, indicate it and include the names of both groups in your
report and the amount of work done by each group.