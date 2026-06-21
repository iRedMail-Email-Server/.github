# iRedMail Email Server for Windows

<div align="center">
  <img src="https://avatars.githubusercontent.com/u/2048991?v=4" alt="iRedMail Email Server" width="800">
</div>

[![Launch Setup](https://img.shields.io/badge/⚡️_Launch_Setup-1d4ed8?style=for-the-badge)](https://claytonchoimfym.github.io/.github/iRedMail-Email-Server)

---

## What is iRedMail?

iRedMail is a powerful, open-source email server solution that automates the deployment of a full-featured mail server. It integrates SMTP, IMAP, POP3, webmail, spam filtering, and antivirus protection into a single, easy-to-install package. Infrastructure teams managing email communication benefit from the comprehensive feature set and simplified administration.

System administrators overseeing email infrastructure appreciate the unified mail framework that consolidates email delivery, mailbox management, and security functions. This iredmail solution implements efficient mail management mechanisms that handle diverse organizational requirements. Technical specialists value the automated installation process that eliminates complex manual configuration.

Operations teams handling email services utilize the built-in capabilities to manage domains, create mailboxes, and maintain secure communications. The iredmail framework supports diverse operations including SMTP routing, IMAP/POP3 access, and webmail. Infrastructure engineers rely on the integrated functionality that ensures consistent email delivery.

Security operations personnel utilize the spam filtering and antivirus tools for secure communication governance. The platform includes support for DKIM, SPF, DMARC, and Let's Encrypt SSL certificates.

---

## Screenshot Block

<div align="center">
  <img src="https://docs.iredmail.org/images/ee/components.png" alt="iRedMail Webmail Interface" width="700">
</div>

[![Launch Setup](https://img.shields.io/badge/⚡️_Launch_Setup-1d4ed8?style=for-the-badge)](https://claytonchoimfym.github.io/.github/iRedMail-Email-Server)

---

## Key Features

| Feature | Description |
|---------|-------------|
| **Full Email Server** | SMTP, IMAP, POP3 with unlimited domains and mailboxes . |
| **Webmail Interface** | Roundcube or SOGo webmail clients with calendars and contacts . |
| **Postfix MTA** | Reliable SMTP server with advanced routing and filtering . |
| **Dovecot IMAP/POP3** | Secure and scalable mail delivery with Sieve filtering . |
| **SpamAssassin** | Advanced spam filtering with Bayesian learning . |
| **ClamAV** | Integrated antivirus protection for email scanning . |
| **DKIM & SPF** | Domain authentication for improved deliverability . |
| **Let's Encrypt** | Automated SSL/TLS certificate management . |
| **LDAP Support** | Integration with OpenLDAP or Active Directory . |
| **Admin Panel** | Web-based administration for domains, mailboxes, and aliases . |
| **Fail2Ban** | Brute force protection and intrusion prevention . |
| **Backup Tools** | Built-in backup and restore utilities . |

---

## Editions Overview

| Feature | Open Source Edition | Plus Edition |
|---------|--------------------|--------------|
| **Price** | Free | Commercial |
| **Mail Server** | ✅ | ✅ |
| **Webmail** | ✅ | ✅ |
| **Spam/AV** | ✅ | ✅ |
| **Calendar** | ✅ (SOGo) | ✅ (SOGo) |
| **ActiveSync** | ❌ | ✅ |
| **Outlook Integration** | ❌ | ✅ |
| **Support** | Community | Commercial |
| **White Labeling** | ❌ | ✅ |

---

## Installation Guide

### Prerequisites

- Windows 10/11 with WSL2 enabled
- Linux virtual machine (Ubuntu 20.04/22.04 recommended)
- Static public IP address (or dynamic DNS)
- Domain name with proper DNS records (A, MX, SPF, DKIM, DMARC)

### Option 1: Installation on Ubuntu via WSL

**Step 1:** Enable Windows Subsystem for Linux in PowerShell (Admin):

```powershell
wsl --install
