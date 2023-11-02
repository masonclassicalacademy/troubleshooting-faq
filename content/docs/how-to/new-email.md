---
title: Email Creation
type: docs
prev: docs/how-to/
---

## Email created in Google Admin Console
When adding teachers or staff, be sure to also add to teacher or staff groups. Groups are nested, so only add to lowest group, i.e. not to elementary, upperschool, highschool, faculty, allstaff, etc.

## Setting up Outlook (if needed)
Incoming Mail (IMAP) Server - Requires SSL
* imap.gmail.com
* Port: 993
* Requires SSL:Yes

Outgoing Mail (SMTP) Server - Requires TLS
* smtp.gmail.com
* Port: 465
* Requires SSL: Yes
* Requires authentication: Yes
* Use same settings as incoming mail server

* Full Name or Display Name: [your name]
* Account Name or User Name: your full Gmail address (username@gmail.com). Google Apps users, please enter username@your_domain.com
* Email address: your full Gmail address (username@gmail.com) Google Apps users, please enter username@your_domain.com
* Password: your Gmail password

## Additional Required Setup
Also, before it’ll work, you have to log into Gmail in the web browser and go to Manage your Google Account > Security, the scroll down to “Less secure app access” and set it to on.

Then back in Gmail, click on the gear at top right, then See all settings > Forwarding and POP/IMAP and enable IMAP.


## Forwarding CCPS Email
In order to forward CCPS email to your `.masonacademy.com` account, you need to setup email forwarding:
* Login to the [CCPS outlook web access app](https://webmail.collierschools.com/owa/#path=/mail/inbox): 
* Click on the gear > Options at the top right to go to settings.
* In the left-hand column, under Mail, select “Inbox and sweep rules”
* Click the + sign to add a rule.
* Give it a name like “Forward email to MCA”
* Add the condition “Apply to all messages”
* Do the following: “Redirect the message to...” and add your MCA email address.
* Check the checkbox “Stop processing more rules”
* Click OK at the top.
