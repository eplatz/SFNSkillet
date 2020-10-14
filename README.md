# SFNSkillet
SFNSkillet eliminates the manual firewall configuration needed to use SafeNetworking.

##SFNSkillet and panhandler
SFNSKillet is designed to work with the panhandler application.

[Quick Start Guide to panhandler](https://live.paloaltonetworks.com/t5/skillet-tools/install-and-get-started-with-panhandler/ta-p/307916)

[panhandler full documentation](https://panhandler.readthedocs.io/en/master/)

##SafeNetworking
SafeNetworking is a software application that recevies both THREAT and TRAFFIC syslogs events from Palo Alto Networks NGFWs. Using the Palo Alto Networks Threat Intelligence Cloud, SafeNetworking is able to correlate some of the threat logs (DNS queires mainly) with malware known to be associated with the event in question. SafeNetworking utilizes ElasticStack's open-source version to gather, store and visualize these enriched events.

Before using SafeNetworking, please read and understand our Support Policy
For a more detailed introduction to SafeNetworking, see What is SafeNetworking?
For the latest information and release specific notes view the release notes

If you want to use SafeNetworking (not develop against it) it is suggested to get the pre-installed VM that can be obtained from your Palo Alto Networks account team and can be used for a proof-of-concept of SafeNetworking and comes pre-installed and ready to go.

If you are looking to install a dev copy and develop against the code or do not have an account team, please take a look at instructions in the wiki on how to install and run.

If wanting to submit a pull-request, please see the contributing guidelines.

https://github.com/PaloAltoNetworks/SafeNetworking

### Support Policy
The code and templates in the repo are released under an as-is, best effort, support policy. These scripts should be seen as community supported and Palo Alto Networks will contribute our expertise as and when possible. We do not provide technical support or help in using or troubleshooting the components of the project through our normal support options such as Palo Alto Networks support teams, or ASC (Authorized Support Centers) partners and backline support options. The underlying product used (the VM-Series firewall) by the scripts or templates are still supported, but the support is only for the product functionality and not for help in deploying or using the template or script itself. Unless explicitly tagged, all projects or work posted in our GitHub repository (at https://github.com/PaloAltoNetworks) or sites other than our official Downloads page on https://support.paloaltonetworks.com are provided under the best effort policy.