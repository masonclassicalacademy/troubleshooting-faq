## Background
Our group policies are located on our Domain Controller

## Reports
To build a report of the group policies:
* Enter the following on a  command line to check for GP application: `GPResult /h Report.htm /f`<br />
This generates a report in the cmd directory you’re in that can be opened in a browser.

## Using Templates
Control through Group Policy Management on Domain Controller.  To use a template: 
* Download the Google Chrome ADM/ADMX templates from here: [http://dl.google.com/dl/edgedl/chrome/policy/policy_templates.zip](http://dl.google.com/dl/edgedl/chrome/policy/policy_templates.zip)
* Select the ADMX folder
* Copy `chrome.adml`  to `c:\windows\PolicyDefinitions\en-US`
* Copy `chrome.admx` to `c:\windows\PolicyDefinitions`
* Open up Group Policy Management (Start->Administrative Tools->Group Policy Management)
* Right click the Group Policy Object you want, and select Edit…
* Under Computer Configuration->Policies->Administrative Templates, you should now see a Google object.  Expand that to find the policies you can deploy.

## IP Addresses
* `198.74.252.144 /28`
* Useable: `198.74.252.145 - 157`
* Gateway: `198.74.252.158`
* Subnet Mask: `255.255.255.240`
