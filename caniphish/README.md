# CanIPhish Phishing Simulation

[← Back to Project Overview](../README.md)

## Overview
[CanIPhish](https://caniphish.com/) is an AI-powered phishing simulation and adaptive security awareness training platform. It focuses on building an "AI-Ready Human Firewall" by combining realistic phishing simulations with targeted, gamified learning modules.

## Pricing & Licensing
During our research, the following pricing and tier information was identified:

- **Free Edition (Community Tier):** €0/month for up to **10 employees**. This is a fully functional tier designed for small teams or initial testing.
- **Paid Tiers:** Scaling plans starting at approximately **€0.42/user/month** for a 1000 user license.
- **Enterprise Add-ons:** Advanced features such as SSO, White-labelling, and Deepfake Voice Phishing are available as optional add-ons.

## Key Features
- **Phishing Simulations:** Support for standard Email phishing, Conversational (multi-turn) Email Phishing, and next-gen Deepfake Voice Phishing.
- **Adaptive Training:** Over 60 micro-learning modules that adapt based on employee performance and risk profiles.
- **Human Risk Management:** Gamified experience with badges, leaderboards, and detailed employee risk profiling.
- **Threat Analysis:** AI-powered email threat analysis and interactive sandboxing.
- **Directory Integration:** Seamlessly integrates with **Microsoft Entra ID (Azure AD)** and **Google Workspace** for automated onboarding (paid tiers).

## Free Plan Limitations
While the Community Tier is powerful, it has several limitations to consider for academic use:
1. **User Limit:** Strictly capped at **10 employees**.
2. **Content Access:** Limited library of phishing templates and training modules compared to paid tiers.
3. **Advanced AI:** No access to conversational/voice phishing or AI-powered content generation.
4. **Platform Features:** No SSO (SAML), Webhooks, or White-labelling.
5. **Exports:** SCORM export for training modules is not available.

## Setup & Deployment
CanIPhish is designed for rapid, self-service deployment:
- **Allowlisting:** Requires standard configuration of IPs, Headers, and URLs in the mail server (e.g., M365) to ensure simulation delivery.
- **Quick Reference:** A comprehensive Knowledge Base and video walkthroughs are available to guide administrators through the initial setup.
