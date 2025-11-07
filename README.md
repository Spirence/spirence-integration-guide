# Spirence Integration Guide

Welcome to the Spirence Integration Guide, your step-by-step resource for connecting your organization to the Spirence platform.

This guide covers everything you need to get your employees enrolled, your systems connected, and your experience running smoothly from day one.

&nbsp;

## Table of Contents

- [Onboarding Wizard](#onboarding-wizard)
- [Whitelist Information](#whitelist-information)
- [Auto-Enrolling Employees](#auto-enrolling-employees)
- [SSO (Single Sign-On)](#sso-single-sign-on)
- [Nectar: Content Licensing API](#nectar-content-licensing-api)
- [Additional Integration Options](#additional-integration-options)

&nbsp;


## Onboarding Wizard

Use our Onboarding Wizard to finalize your integration, create your employer account, and complete your contract details.

The wizard will guide you through:

- Contract and billing information
- Account and admin setup
- Employee enrollment preferences

[Access Onboarding Wizard](https://app.spirencewellness.com/onboarding-wizard)

&nbsp;
## Whitelist Information

To ensure all Spirence services function properly, please whitelist the following domains and IPs within your company’s firewall or email filters. If your company uses strict outbound content filters, confirm that Vimeo and Spirence domains are accessible to avoid playback or login issues.

#### Spirence Platform
```
*.spirencewellness.com 
*.wp.com 
```

#### Vimeo
```
*.vimeo.com 
*.vimeocdn.com 
*.magisto.com 
*.akamaized.net 
*.cloudfront.net  
```

#### Email Senders

```
*@spirencewellness.com
```

#### Mailchimp

Used for sending content-based notifications to users (new course, live event, etc). Reference the [Mailchimp Documentation](https://mailchimp.com/about/ips/)

```
205.201.128.0/20
198.2.128.0/18
148.105.0.0/16
```

#### Brevo

Used for sending notifications to users from our platform (magic links, password resets, etc.). Reference the [Brevo Documentation](https://help.brevo.com/hc/en-us/articles/208848409-Brevo-IP-ranges-improve-the-deliverability-of-B2B-emails)

```
1.179.112.0/20
77.32.148.0/24
77.32.149.0/24
185.41.28.0/24
212.146.244.0/24
mailinblue.com 
d.mailin.fr 
d.sender-sib.com 
sendib.com 
sendibm0.com 
sendibm1.com 
sendibm2.com 
sendibm3.com 
sendibm4.com 
sendibt1.com 
sendibt2.com 
sendibt3.com 
sendibt4.com 
sp1-brevo.net 
sp2-brevo.net 
sp3-brevo.net 
sp9-brevo.net 
tsp1-brevo.net 
```


&nbsp;
## Auto-Enrolling Employees

To make setup simple, Spirence supports bulk employee enrollment via CSV upload.

Download the enrollment template below and fill it in with your employee roster. Required fields are highlighted in the first row.

Once completed, you can securely upload your spreadsheet through your Employer Dashboard, or send it directly to your Spirence implementation manager.

After upload, your employees will receive:

- Immediate access to Spirence platform
- A welcome email with login instructions
- An introduction to Spirence and available services

[Download Auto-Enroll Template](https://futuresofpb-my.sharepoint.com/:x:/g/personal/cholder_spirencewellness_com/EQztdmsAYa5FqUcVKmLoBBwB9huexyjTAkPAijucpk0UMA?e=xMK08E)

&nbsp;
## SSO (Single Sign-On)

Spirence offers seamless authentication via SSO (SAML 2.0 or OAuth 2.0) to provide employees with direct, secure access from your internal systems.

Supported identity providers include:

- Okta
- Azure AD
- Google Workspace
- Ping Identity
- OneLogin
- And More...

If your organization prefers a custom setup, please contact your technical account manager for configuration details.

[Request SSO Information](mailto:connect@spirencewellness.com)

&nbsp;
## Nectar: Content Licensing API

Our Nectar API allows partners to integrate Spirence’s licensed mental health and leadership content directly into your internal LMS or employee platforms.

With Nectar, you can:

- Programmatically pull course metadata, categories, and presenters
- Manage access permissions and track engagement
- Embed or reference licensed video and article content

Documentation and API keys are available here:

[Nectar API Documentation](https://app.spirencewellness.com/api/nectar)

&nbsp;
## Additional Integration Options

Depending on your technical setup and goals, you can also:

- Embed Spirence content directly in your intranet or LMS using iFrame or SCORM packages.
- Schedule automated syncs for employee data to keep enrollments current.
- Access analytics on engagement and prevention scores via your dashboard or API.

If you’d like a guided walkthrough or custom integration, reach out to your Spirence Success Manager at [connect@spirencewellness.com](mailto:connect@spirencewellness.com).
