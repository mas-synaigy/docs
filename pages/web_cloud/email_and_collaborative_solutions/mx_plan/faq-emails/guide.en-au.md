---
title: FAQ OVHcloud emails
updated: 2020-05-05
---

## OVHcloud email FAQ

### What do I do if I can't send or receive emails? 

Most of the time, a failure in sending/receiving emails is related to the configuration of your address in your email client. To verify, test it by connecting to [webmail](https://www.ovh.com.au/mail/), and try sending and receiving a test email with this account. 

- If this works fine, the failure is indeed due to your email client configuration. 
- If, however, you still cannot send or receive an email, there are other solutions you can try. 

After sending an email to your email account, do you receive an error message? If yes, check the error message, as it may specify the reason (mailbox full, mailbox does not exist, etc.). 

You can also check that your domain name is delivering emails to the right place. To do this, go to the [OVHcloud Control Panel](https://ca.ovh.com/auth/?action=gotomanager&from=https://www.ovh.com.au/&ovhSubsidiary=au){.external}, select the DNS zone for your domain name, then look at the MX records that have been set up. These records must be in the form "mx**X**.mail.ovh.ca." (replace **X** with a number between 0 and 3). If the MX records are different, this could mean you have an email solution from an operator other than OVHcloud. 

**Tips and tricks**: If you cannot log in via webmail, your password may be incorrect. Check your password, and if necessary, reset it via the [OVHcloud Control Panel](https://ca.ovh.com/auth/?action=gotomanager&from=https://www.ovh.com.au/&ovhSubsidiary=au){.external} — then try logging in again. To do this, you can use the following documentation: [Changing your password for an MX Plan email address](/pages/web_cloud/email_and_collaborative_solutions/mx_plan/email_change_password).

### How do I set up my email address and use it with webmail? 

You can configure your email account to use an email client like Outlook, Thunderbird, Mac Mail, etc. To do this, we have created guides to help you set up your email address. You can find them on [this page](/products/web-cloud-email-collaborative-solutions-mx-plan). 

With [webmail](https://www.ovh.com.au/mail/), you can access your inbox at any time from any connected device. Once you have created your email account, you can log in here to access it. 

**Tips and tricks**: If you configure your email account in an email software client, we advise configuring it with the IMAP protocol. This way, emails will stay stored on the server, and you can read them from any device via [webmail](https://www.ovh.com.au/mail/). To do this, you can use the following documentation: [Getting started with an MX Plan solution](/pages/web_cloud/email_and_collaborative_solutions/mx_plan/email_generalities).

### How do I manage my email services? 

All of your email addresses are managed via the [OVHcloud Control Panel](https://ca.ovh.com/auth/?action=gotomanager&from=https://www.ovh.com.au/&ovhSubsidiary=au){.external}. To do this, log in and access the product concerned. You can change the passwords for your email addresses, check how much space they have left, create new email addresses, or delete existing ones. 

**Tips and tricks**: With MX Plan email solutions, you can delegate the management of an email account to another OVHcloud account while keeping control over it yourself. To do this, simply set up a delegation from the [OVHcloud Control Panel](https://ca.ovh.com/auth/?action=gotomanager&from=https://www.ovh.com.au/&ovhSubsidiary=au){.external}: Log in to the OVHcloud Control Panel, navigate to the `Emails` section and select the domain concerned. Next, go to the `Emails` tab, then select an option:

- `Manage the elements shared by all email adresses`{.action} on the right-hand side if you would like to delegate management of all accounts for this domain
- `Delegation management`{.action} if you would like to delegate management of a specific account (click on `...`{.action} next to the account)  

Please note that an OVHcloud customer ID (NIC handle) is required for both options.

### How do I limit the amount of spam I receive? 

To limit the amount of spam emails you receive, you can set up inbox rules on your account (called "Filters" in the old MX Plan solution). Their purpose is to move emails to the spam folder ot delete them as soon as they are received. To do this, log in to the [OVHcloud Control Panel](https://ca.ovh.com/auth/?action=gotomanager&from=https://www.ovh.com.au/&ovhSubsidiary=au){.external}, then in the `Emails` section, select the domain concerned. Next, go to the `Emails`{.action} tab and click on the filter symbol in the "Filter" column. 

If you don't see this column, spam filters can only be created by setting up inbox rules on your email account via [webmail](https://www.ovh.com.au/mail/). Please refer to [this guide](/pages/web_cloud/email_and_collaborative_solutions/using_the_outlook_web_app_webmail/creating-inbox-rules-in-owa-mx-plan) for detailed instructions.

**Tips and tricks**: If you set up a spam filter, legitimate emails may be marked as spam. These are called "false positives". If this happens, please submit a support ticket via the [OVHcloud Control Panel](https://ca.ovh.com/auth/?action=gotomanager&from=https://www.ovh.com.au/&ovhSubsidiary=au){.external} and let us know. We can then take the necessary steps to ensure that they are no longer labelled as spam in the future.

### I want to change my email solution for my address, how can I do this while keeping its content?

You want to change [email solutions](https://www.ovhcloud.com/en-gb/emails/) to benefit from more space and features, but you want to keep the content of your existing account. To do this, please follow the corresponding migration guide:

- [Migrate an MX Plan email address to an Email Pro or Exchange account](/pages/web_cloud/email_and_collaborative_solutions/migrating/migration_control_panel)
- [Migrate your email addresses from one OVHcloud email platform to another](/pages/web_cloud/email_and_collaborative_solutions/migrating/migration_control_panel)
- [Migrate your email address manually](/pages/web_cloud/email_and_collaborative_solutions/migrating/manual_email_migration)
- [Migrate email accounts via OVH Mail Migrator](/pages/web_cloud/email_and_collaborative_solutions/migrating/migration_omm)
- [Migrate a Gmail account to an OVHcloud email account via the OVH Mail Migrator](/pages/web_cloud/email_and_collaborative_solutions/migrating/security_gmail)

### Does the Office 365 Pro Plus solution include a Skype licence?

The Office 365 Pro Plus solution does not come with a Skype licence. Only the Skype for Business software is included with it.

## Go further

Join our community of users on [https://community.ovh.com/en/](https://community.ovh.com/en/).