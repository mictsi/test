# FAQ – Multi-Factor Authentication (MFA) at KTH

**Ingress:**  
Multi-Factor Authentication (MFA) is a key part of how KTH protects identities, accounts, and digital services. This document explains why MFA is used, why Microsoft Authenticator is the chosen solution, how it supports KTH’s Zero Trust strategy, and what this means for security, accessibility, and future authentication methods.

---

## What is MFA and why does KTH use it?

**MFA (Multi-Factor Authentication)** requires more than a username and password. In addition to something you know (your password), you must also confirm your identity with something you have, such as a mobile phone.

KTH uses MFA to:
- Protect accounts from phishing and credential theft
- Reduce the risk of unauthorised access
- Protect sensitive information, systems, and services

---

## How does MFA relate to KTH’s Zero Trust strategy?

MFA and phishing-resistant authentication are **core tenets** of the **Zero Trust (ZT)** strategy being implemented at KTH.

### What is Zero Trust?

Zero Trust is based on the principle **“never trust, always verify”**:
- No user, device, or network is trusted by default
- Every access request must be explicitly verified
- Identity is the primary security boundary

Access decisions are based on strong authentication, context, and continuous risk evaluation rather than network location.

### Why is MFA critical in Zero Trust?

- Strong identity verification is mandatory
- Phishing-resistant MFA greatly reduces identity compromise
- Stolen passwords alone are insufficient for attackers

---

## When does MFA become mandatory?

MFA will be **mandatory for all employees and affiliated users from 24 February 2026** when accessing KTH’s central login service and connected systems.

---

## Which services require MFA?

MFA is required for KTH’s **central login service**, including:
- kth.se
- Canvas
- Zoom
- Microsoft 365
- Other centrally authenticated services

---

## How do I activate MFA?

1. Install **Microsoft Authenticator**
2. Go to https://aka.ms/mfasetup
3. Sign in with username@ug.kth.se
4. Add Microsoft Authenticator
5. Scan the QR code
6. Approve the test sign-in

---

## Why must Microsoft Authenticator be installed from official app stores?

Only install from **App Store** or **Google Play** to ensure:
- Protection from malicious apps
- Verified publisher
- Automatic security updates
- Full KTH support

---

## Supported mobile devices

- iPhone: iOS 16+
- Android: Android 8+

---

## TOTP and third-party MFA apps

KTH does **not** support TOTP or third-party MFA apps due to insufficient phishing resistance and lack of identity integration.

---

## Why phishing-resistant authentication?

These methods prevent reuse of stolen credentials and protect against real-time phishing and MFA fatigue attacks.

---

## Why Microsoft MFA?

Microsoft MFA is:
- Integrated with KTH’s identity platform
- Phishing-resistant and hardware-backed
- Cost-efficient through existing licenses
- Centrally managed and future-ready

---

## Passkeys, FIDO2, and passwordless authentication

KTH is evaluating these methods for future use.

---

## Can I use my own YubiKey or FIDO2 key when available?

No. FIDO2 devices must be **provisioned and managed by KTH**.  
Personal keys will not be supported to ensure secure lifecycle management, recovery, and compliance.

---

## Accessibility

Users with accessibility needs should contact **KTH IT Support** for individual assessment.
