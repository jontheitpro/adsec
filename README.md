
# Active Directory Security Basics

You will need to have your free Azure account created and active before this training begins! 

**This activity should be completed before you arrive on Saturday, Feb 23rd**

[Free Azure Trial](https://azure.microsoft.com/free/)

For those that do not wish to build/use use their own systems to virtualize a set of domain controllers, the following can be used to deploy a pair, DC1 and DC2 in Azure using your previously activated trial subscription.

**Run the following template.**
https://portal.azure.com/microsoft.onmicrosoft.com/#create/Microsoft.Template/uri/https%3A%2F%2Fraw.githubusercontent.com%2Fdmitriilezine%2FExternal-AD-Lab-WS2016%2Fmaster%2FExternal%20AD%20Lab%20WS2016%2Fazuredeploy.json

1. Create new Resource Group, name it 'alias-ADLAB', where 'alias' is your alias

2. For location select "West US"

3. Admin password is created as "Subscription#YOURSUBSCRIPTIONID". You can replace it with your own strong password

4. Replace Source Client IP with Public IP of your device, or put "*" to allow any source

5. Accept defaults for DC1 and DC2

6. Virtual Machine Size Standard_DS12_v2 to have speedy lab experienses

7. Select to deploy first App Server - select Yes. No need to deploy other application servers for this lab.

8. Click "Purchase"

**It takes about 60 minutes to deploy this solution. VMs are deployed with autoshutdown scheduled for 11PM EST.**

**Perform this activity once you arrive and have established Internet connectivity.**

**It is YOUR responsibility to DESTROY these systems when no longer in use**


## Section 1 - Directory Service Basics
### What is a directory service

- [What is a Directory Service](https://www.dummies.com/programming/networking/defining-terms-what-is-a-directory-service/)
- [Wikipedia](https://en.wikipedia.org/wiki/Directory_service)

### Microsoft Active Directory
- [Active Directory](https://docs.microsoft.com/en-us/windows/desktop/ad/active-directory-domain-services)
- [Wikipedia](https://en.wikipedia.org/wiki/Active_Directory)
- [What's New in 2012/2012R2](https://docs.microsoft.com/en-us/previous-versions/windows/it-pro/windows-server-2012-R2-and-2012/hh831477(v=ws.11))
- [What's New in 2016](https://docs.microsoft.com/en-us/windows-server/identity/whats-new-active-directory-domain-services)

### Installation Process
- [Install Active Directory Level 100](https://docs.microsoft.com/en-us/windows-server/identity/ad-ds/deploy/install-active-directory-domain-services--level-100-)
- 2016 AD DS Installation video by "Instructor Paul"

<a href="http://www.youtube.com/watch?feature=player_embedded&v=Vo5WAoukDnE
" target="_blank"><img src="http://img.youtube.com/vi/Vo5WAoukDnE/0.jpg" 
alt="2016 AD DS Installation" width="320" height="240" border="10" /></a>

### Configuration Overview

### The "tools"
- [ADTimeline](https://github.com/ANSSI-FR/ADTimeline)
- [AD Topology Diagramer](https://www.microsoft.com/en-us/download/details.aspx?id=13380)
- [MS Security Compliance Toolkit](https://www.microsoft.com/en-us/download/details.aspx?id=55319)
- [ADExplorer](https://docs.microsoft.com/en-us/sysinternals/downloads/adexplorer)
- [AD Replication Status Tool](https://www.microsoft.com/en-us/download/details.aspx?id=30005)



****

## Section 2 - Recommended Practices
* Topology
* Sizing/Capacity Planning
* Virtualization
* Cloud/IaaS

****

## Section 3 - Directory Security Fundamentals
* AD Security Concerns
* Tier Model
* Securing Active Directory
* PAWs

****

## Section 4 - Hardening the Directory
* Baselines (MS/STIG/CIS)
* Security Hardening
* ESAE
