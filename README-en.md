# FAQ – Multi-Factor Authentication (MFA) at KTH

**Ingress (for CMS):**  
Multi-Factor Authentication (MFA) is a key part of how KTH protects identities, accounts, and digital services. This page explains why MFA is being introduced, why Microsoft Authenticator is used, how it supports KTH’s Zero Trust strategy, and what this means for security, accessibility, and future authentication methods.

---

## What is MFA and why does KTH use it?

**MFA (Multi-Factor Authentication)** is a security method that requires more than just a username and password when you sign in. In addition to something you know (your password), you must also confirm your identity with something you have (for example, a mobile phone).

KTH uses MFA to:
- Protect accounts from password theft and phishing
- Reduce the risk of unauthorized access
- Protect sensitive information, systems, and services

---

## How does MFA relate to KTH’s Zero Trust strategy?

MFA and phishing-resistant authentication are **core tenets** of the **Zero Trust (ZT) security strategy** that KTH is implementing.

### What is Zero Trust?

Zero Trust is a security model based on the principle **“never trust, always verify”**. This means that:
- No user, device, or network is trusted by default
- Every access request must be explicitly verified
- Identity is treated as the primary security boundary

Instead of relying on network location (for example being “on campus”), access decisions are based on:
- Strong authentication
- Device and user context
- Continuous risk evaluation

### Why is MFA critical in Zero Trust?

Within a Zero Trust model:
- **Strong identity verification is mandatory** before access is granted
- **Phishing-resistant MFA** significantly reduces the risk of identity compromise
- Compromised passwords alone are not sufficient for attackers

By using Microsoft MFA and prioritising phishing-resistant methods, KTH establishes a strong identity foundation that enables secure access to services regardless of location, network, or device.

This is a fundamental building block for KTH’s long-term security architecture.

---

## When does MFA become mandatory?

MFA will be **mandatory for all employees and affiliated users from 24 February 2026** when accessing KTH’s central login service and connected systems.

---

## Which services require MFA?

MFA is required when logging in via KTH’s **central login service**, which is used for many KTH systems, including (but not limited to):
- kth.se
- Canvas
- Zoom
- Microsoft 365 Services
- Other services connected to KTH’s central authentication

---

## How do I activate MFA?

1. Install **Microsoft Authenticator** on your mobile phone.
2. Open a browser (preferably in private/incognito mode) and go to **https://aka.ms/mfasetup**.
3. Sign in with your KTH account (username@ug.kth.se).
4. Choose to add **Microsoft Authenticator** as your authentication method.
5. Scan the QR code with the app.
6. Approve the test sign-in to complete setup.

---

## Why is it important to install Microsoft Authenticator from the App Store or Google Play?

Installing **Microsoft Authenticator** only from the **official App Store (iOS)** or **Google Play Store (Android)** is critical for security and reliability:
- **Protection against malicious apps** – Apps from unofficial sources may be modified to steal passwords, MFA approvals, or personal data.
- **Verified publisher** – Official app stores verify that the app is genuinely published by Microsoft and has not been tampered with.
- **Automatic security updates** – Updates from official stores include security fixes and compatibility updates required for KTH systems.
- **Supported by KTH** – KTH’s MFA solution is tested and supported only with the official Microsoft Authenticator app.
- **Reduced risk of account compromise** – Unofficial apps significantly increase the risk of phishing and malware.

Always ensure the app is published by **Microsoft Corporation**.

---

## What mobile phones are supported?

You may use either a **personal or work phone**.

Supported operating systems:
- **iPhone:** iOS 16 or later
- **Android:** Android 8 or later

You can check your phone’s OS version in the device settings.

---

## Can I register more than one phone for MFA?

Yes. You can register **multiple phones** for MFA.

To add a new phone, you must approve the addition using an already registered MFA device.

---

## I have a new phone. What should I do?

- **If you still have access to your old phone:** Add MFA on the new phone before removing the old one.
- **If you no longer have the old phone:** Remove the old device using **Mobile BankID** via “Manage your KTH account”.
- **If you do not have Mobile BankID:** Contact **IT Support** for assistance.

---

## How often will I be asked to use MFA?

MFA is required **per browser and per device**.

You will be prompted again if:
- You switch browser or device
- You clear browser data
- You have been inactive for a longer period

---

## Can I manage my MFA settings myself?

Yes, if you have **Mobile BankID**.

Using the **Manage your KTH account** service, you can:
- Add a phone to MFA
- Remove a phone from MFA
- View registered MFA devices

If you do not have Mobile BankID, contact **IT Support**.

---

## How do I remove a phone from MFA?

1. Log in to **Manage your KTH account** using Mobile BankID.
2. Go to **My MFA devices**.
3. Select the device you want to remove.
4. Confirm the removal with Mobile BankID.

---

## What should I do if I cannot log in because of MFA?

- If you have **Mobile BankID**, use it to manage or reset your MFA devices.
- If you **do not have Mobile BankID**, contact **KTH IT Support** for help.

---

## Does KTH support software or hardware TOTP (one-time password) tokens?

No. KTH does **not** support software-based or hardware-based TOTP solutions (for example, six-digit rotating codes).

KTH prioritises **phishing-resistant authentication methods**, and traditional TOTP does not provide sufficient protection against modern phishing attacks.

---

## Why does KTH prioritise phishing-resistant authentication methods?

Phishing-resistant methods are designed so that authentication cannot be reused by an attacker, even if a user is tricked into approving a login.

KTH prioritises these methods because they:
- Prevent attackers from capturing and reusing credentials or MFA codes
- Protect against real-time phishing and “MFA fatigue” attacks
- Bind authentication to the correct service and identity
- Significantly reduce the risk of account takeover

This approach aligns with current best practices and recommendations from major security authorities.

---

## Why does KTH use Microsoft MFA as its solution?

KTH uses **Microsoft MFA (Microsoft Authenticator)** as the standard MFA solution for several strategic and security reasons:
- **Integrated with KTH’s identity environment** – Seamlessly integrated with KTH’s central identity and access management platform
- **Strong identity protection** – Enables conditional access, risk-based authentication, and account protection at scale
- **Phishing-resistant authentication** – Supports modern, phishing-resistant methods such as number matching and device-bound approvals
- **Hardware-backed security** – Uses secure hardware features on modern phones to protect cryptographic keys
- **Future-ready** – Enables adoption of stronger authentication methods in the future without changing platform
- **Cost efficiency** – Included in KTH’s existing licensing, avoiding additional token and infrastructure costs
- **Ease of management** – Centralised administration, monitoring, and recovery through existing KTH and Microsoft tooling

This combination allows KTH to improve security while keeping the solution manageable, scalable, and user-friendly.

---

## Why do we use a Microsoft solution specifically?

Microsoft MFA is part of the same platform that already manages identities, access, and security for large parts of KTH’s IT environment.

Using a single, integrated platform allows KTH to:
- Protect the **identity itself**, not just individual logins
- Apply consistent security policies across all services
- Correlate identity signals, risk, and authentication events
- Reduce architectural complexity and operational risk

This integration is a key requirement for implementing Zero Trust at scale.

---

## What about passkeys, FIDO2 security keys, and passwordless authentication?

KTH is actively **evaluating passkeys, FIDO2 security keys, and passwordless authentication methods** for future use.

These technologies are of interest because they:
- Are **phishing-resistant by design**
- Eliminate or reduce reliance on passwords
- Bind authentication cryptographically to the user, device, and service
- Can provide a simpler and more secure user experience

Microsoft MFA and KTH’s current identity platform enable the use of these methods in the future once they are mature, well-tested, and suitable for KTH’s environment.

At present, these methods are **not generally available at KTH**, but they are part of KTH’s long-term authentication strategy.

---

## Can I use my own YubiKey when FIDO2 keys will be available?

No. A FIDO2 device needs to be **provisioned by KTH**.

---

## Why are third-party MFA apps not allowed?

KTH does **not allow third-party MFA applications** for protecting KTH accounts.

This decision is based on security, manageability, and compliance considerations:
- **Lack of phishing resistance** – Many third-party apps rely on TOTP or basic push mechanisms that do not meet KTH’s requirements for phishing-resistant authentication.
- **No integration with KTH’s identity environment** – Third-party apps cannot be fully integrated with KTH’s identity, risk evaluation, and conditional access controls.
- **Inconsistent security guarantees** – KTH cannot verify how third-party apps store secrets, protect cryptographic keys, or use hardware-backed security.
- **Limited incident response and recovery** – Account recovery, device loss handling, and security monitoring become significantly harder with external solutions.
- **Increased operational complexity** – Supporting multiple MFA solutions increases administrative overhead, user confusion, and support costs.
- **Compliance and data protection risks** – KTH must ensure that authentication solutions meet regulatory, contractual, and institutional security requirements.

By standardising on Microsoft MFA, KTH can enforce consistent security controls, reduce risk, and ensure a predictable and supportable authentication experience.

---

## Why does KTH not use open-source MFA solutions?

Open-source MFA solutions are not used at KTH because they do not meet the combined requirements for **security, scalability, integration, and operational support** in KTH’s environment.

Key reasons include:
- **Lack of deep identity integration** – Open-source solutions typically cannot integrate tightly with KTH’s identity platform, conditional access, and risk-based controls.
- **Operational responsibility** – KTH would be fully responsible for hosting, securing, patching, monitoring, and incident response.
- **Limited phishing-resistant capabilities** – Many open-source solutions focus on TOTP rather than modern phishing-resistant authentication.
- **Scalability and availability** – Meeting KTH’s availability, performance, and global access requirements would require significant additional infrastructure.
- **Cost and risk over time** – While software may be free, long-term operational cost and security risk are significantly higher.

For identity and authentication, KTH prioritises **proven platforms with strong security guarantees, vendor accountability, and long-term support**.

---

## How does KTH view open source solutions versus commercial solutions?

KTH has a strong and well-established stance of **prioritising open source solutions** where they are suitable and meet KTH’s requirements. Open source is often preferred because it promotes transparency, flexibility, vendor independence, and collaboration.

However, the choice between open source and commercial solutions is always **context-dependent** and based on the type of service being delivered.

For each service, KTH evaluates factors such as:
- **Security requirements** – Including resistance to modern attack techniques and the ability to protect identities and sensitive data
- **Integration needs** – How well the solution integrates with KTH’s existing platforms and services
- **Operational maturity** – Availability of monitoring, incident response, recovery, and lifecycle management
- **Scalability and availability** – Ability to support the entire organisation with high availability
- **Total cost of ownership** – Including long-term operational cost, not just licensing
- **Risk and accountability** – Clear responsibility for vulnerabilities, updates, and support

For **identity and authentication**, the requirements are particularly high. These services form a critical security foundation for all other systems. In this area, KTH has determined that a **commercial, tightly integrated platform** currently provides stronger security guarantees, better phishing resistance, and lower overall risk than available open source alternatives.

This does not mean that open source is excluded at KTH. It means that **KTH chooses the solution type that best fits the risk profile and criticality of each service**, while continuing to evaluate open source options as technologies and ecosystems evolve.

---

## What about users with disabilities or accessibility needs?

KTH recognises that **not all users are able to use MFA in the same way**, and accessibility is an important consideration.

Microsoft Authenticator supports several accessibility features provided by the underlying operating system, such as:
- Screen readers
- Voice control
- High-contrast and accessibility display settings

However, KTH is aware that MFA can still present challenges for some users due to physical, cognitive, or other disabilities.

If you have accessibility needs that make it difficult or impossible to use Microsoft Authenticator:
- **Contact KTH IT Support** to discuss your situation
- Individual assessments can be made to identify **reasonable and secure alternatives or adjustments**

Any alternative solution must still meet KTH’s security requirements and align with phishing-resistant and Zero Trust principles.
