Windows:
The main sources of additional information on CAC Authentication can be found at:
https://public.cyber.mil/pki-pke/end-users/getting-started/#toggle-id-1
https://public.cyber.mil/pki-pke/end-users/web-browsers/#toggle-id-1

Get a smart card and reader.
To get access, work with home component. Review  CAC smart card reader requirements.

Install middleware if needed. 
Middleware enables the DoD PKI certificates stored on your Common Access Card (CAC) to interface with the many Public Key Enabled (PKE) applications on your system and across the Internet. Two of the most common middleware applications used across DoD are ActivClient and Spyrus. 

Install DoD Root Certificates with InstallRoot
In order for your machine to recognize your CAC certificates and DoD websites as trusted, run the InstallRoot utility (32-bit, 64-bit or Non Administrator) to install the DoD CA certificates on Microsoft operating systems. 

Once InstallRoot has started, click install certificates

Check if Installed Certificates are enabled within browser. 
For Chrome:
On the left, click Privacy and security.
Click Security.
Scroll to Advanced.
Click Manage certificates.
In the list, find the newly-added CAs.
For Non-Chrome browsers consult: https://public.cyber.mil/pki-pke/end-users/web-browsers/#toggle-id-2


Install VPN:
While having installed the necessary certificates installed, go to https://azure.cdl.af.mil
Download installer and give administrator permissions
To connect or disconnect from VPN, go to VPN settings.


If InstallRoot 4.1 is installed you will need to migrate configuration settings.
Uninstalling InstallRoot 4.1 will remove configuration information from registry.
Consult page 10 of the InstallRoot 5.2 User Guide to properly update. 
