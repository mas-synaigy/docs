---
title: "Transferring a GoDaddy domain name to OVHcloud"
excerpt: "Find out how to transfer a GoDaddy domain name to OVHcloud"
updated: 2024-04-10
---

## Objective

To transfer a GoDaddy domain name, you will need to follow a specific procedure.

**This guide explains how to transfer a GoDaddy domain name to OVHcloud.**

> [!warning]
>
> The domain name [registrar](/links/web/domains-what-is-registrar) is a service provider authorised to offer domain names for registration by an individual, association or organisation. You renew your domain name subscription with the same registrar (usually once a year).
>
> If OVHcloud is already the registrar of your domain name, the incoming domain transfer procedure does not apply. The incoming domain transfer procedure described in this guide is **only** appropriate for domain names registered with a registrar other than OVHcloud.
>
> To transfer the domain name management to another OVHcloud customer account, a **change of contacts** must be made instead. The procedure is described in [our contact management guide](/pages/account_and_service_management/account_information/managing_contacts).
>
> If you also need to change the **domain name holder**, you should do so **before** you change the domain name contacts. To do this, use our [change of ownership for domain names instructions](/pages/web_cloud/domains/trade_domain).
>

## Requirements

- A domain name registered with GoDaddy.
- The domain name is more than 60 days old.
- The domain name has not been transferred or changed owners within the last 60 days.
- The domain name status is "OK" or "Transferable".
- The domain name is not expired and has an expiry date that allows to finish the transfer process in time - recommended are more than 60 days.
- You can unlock the domain name and you have the transfer code or are able to retrieve it.
- You have the authority to request a transfer for the domain name.
- The domain name owner and/or its administrators must be informed of the transfer request.


> [!warning]
>
> OVHcloud provides services for which you are responsible with regard to their configuration and management. It is therefore your responsibility to ensure that they function correctly.
> 
> This guide is designed to help you with common tasks. Nevertheless, we recommend contacting a [specialist provider](/links/partner) or your current domain name registrar if you encounter any difficulties. OVHcloud cannot provide you with technical support in this regard. You can find more information in the [Go further](#go-further) section of this guide.
> 

## Instructions

> [!primary]
>
> The active DNS zone for a domain name contains the DNS configuration applied to your domain name. It links your domain name to your services, such as your email addresses and your website.
>
> If, in addition to your domain name, you also have an active DNS zone for it at your current registrar, check that the DNS zone applied to your domain name will not be deleted once the transfer is complete.
>
> Some registrars delete the DNS zone as soon as your domain name transfer is complete. If this is the case, recreate your DNS zone identically at OVHcloud before starting the domain name transfer.
>
> To do this, refer to the following guides:
>
> - [Create a DNS zone at OVHcloud](/pages/web_cloud/domains/dns_zone_create)
> - [Edit an OVHcloud DNS zone](/pages/web_cloud/domains/dns_zone_edit)
>
> Also check that your current domain name registrar will not close other services, such as the email addresses associated with your domain name.
>

### Step 1 - Unlock the domain name at GoDaddy

Locking a domain name protects it against unauthorized transfer attempts.
GoDaddy enables this protection by default. You will need to disable it in order to transfer your domain name to OVHcloud.

Follow the steps described in [GoDaddy dedicated documentation](https://www.godaddy.com/help/unlock-or-lock-my-domain-410){.external}.

### Step 2 - Get the authorization code 

OVHcloud will ask you to provide the authorization code, or Auth code, before you begin the domain name transfer procedure. You can get it by opening your `Domain names`{.action} portfolio page at GoDaddy.

Follow the steps described in [GoDaddy dedicated documentation](https://www.godaddy.com/help/transfer-my-domain-away-from-godaddy-3560){.external}.

### Step 3 - Initiate the domain transfer to OVHcloud

Once you have obtained the authorization code, you can proceed with the transfer of your domain name by following the steps in our guide “[Transferring a domain name to OVHcloud](/pages/web_cloud/domains/transfer_incoming_generic_domain)”.

## Go further <a name="go-further"></a>

[Transferring a domain name to OVHcloud](/pages/web_cloud/domains/transfer_incoming_generic_domain)

[Migrating your website and emails to OVHcloud](/pages/web_cloud/web_hosting/hosting_migrating_to_ovh)

For specialised services (SEO, development, etc.), contact [OVHcloud partners](/links/partner).

If you would like assistance using and configuring your OVHcloud solutions, please refer to our [support offers](/links/support).

Join our community of users on <https://community.ovh.com/en/>.
