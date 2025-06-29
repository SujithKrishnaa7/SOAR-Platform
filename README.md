# SOAR-Platform
Created a Worflow to automate every SOC things.

Technologies used:
Wazuh -------SIEM / XDR 
TheHive	-----Security Incident Response Platform (SIRP)	
Shuffle.io --Security Automation and Orchestration (SOAR)

Let's Start !!!

Working ,in words:

The Wazuh agent sends an alert to the Wazuh manager when a rule is triggered. The Wazuh manager then forwards the alert to Shuffle. Shuffle sends the alert to TheHive and collects IOCs. After that, it sends the IOCs back to Shuffle, which then sends an email notification to the SOC analyst to take action. 

Let me make the Hosting process simple: 

DigitalOcean($200 credit): https://m.do.co/c/894547e5b0f6 

Once you sign through referral link, you'll get $200 to host machines (Wazuh and theHive). 

Each machine costs $48 per month, but you can host at no cost. 
(Note:I used this free stuff to setup things.)

Initial Setup :
VirtualBox for Windows : https://download.virtualbox.org/virtualbox/7.1.10/VirtualBox-7.1.10-169112-Win.exe 

Download Win10 ISO and run it as Virtual Machine.  
