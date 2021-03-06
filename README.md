
# Active Directory Security Basics

You will need to have your free Azure account created and active before this training begins! 

[Free Azure Trial](https://azure.microsoft.com/free/)

For those that do not wish to build/use use their own systems to virtualize a set of domain controllers, the following can be used to deploy a pair, DC1 and DC2 in Azure using your previously activated trial subscription.

[Deploy Azure VMs using a Template](https://docs.microsoft.com/en-us/azure/virtual-machines/windows/ps-template)

I have uploaded copies of a reference template and parameters json files to the repository that can be used as references.

**It takes about 60 minutes to deploy this solution. VMs are deployed with autoshutdown scheduled for 11PM EST.**

**Perform this activity once you arrive and have established Internet connectivity.**

**It is YOUR responsibility to DESTROY these systems when no longer in use**

[Additional Azure Quickstart templates](https://github.com/Azure/azure-quickstart-templates)



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
