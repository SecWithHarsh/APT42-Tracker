# APT42: Phishing Campaigns — Mandiant 2022 Analysis

This document provides an in-depth look at APT42's phishing campaigns based on Mandiant's 2022 publication: *“APT42: Crooked Charms, Cons, and Compromises”*. The group, linked to Iran’s IRGC-IO, has demonstrated advanced phishing capabilities, primarily for credential harvesting, surveillance, and initial access operations.

### Lures & Social Engineering Themes

APT42 commonly poses as:
- Journalists offering interviews
- Researchers requesting collaboration, feedbacks
- Medical officials or aid organizations

These personas are used to establish trust and extract credentials or further engage targets.

### Targets of APT42
- Civil society and non-profits
- Education
- Governments
- Healthcare
- Legal and professional services
- Manufacturing
- Media and entertainment
- Pharmaceuticals

### Credential Harvesting Flow

1. **Initial Contact** – The victim is approached via email, either by a fake persona or through a compromised account belonging to a think tank, journalist, or academic institution. 
2. **Engagement** – A phishing link or malicious document is delivered to the target.
3. **Redirection** – The victim is redirected to a credential-harvesting page designed to mimic legitimate login portals (e.g., Gmail login).
4. **Capture & MFA Abuse** – Victim credentials are harvested, and in some cases, MFA codes are also intercepted. APT42 may register their own MFA method (e.g., Microsoft Authenticator) to maintain long-term access and persistence.
