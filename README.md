# Azure-B2C-Authentication-Policies

#### 🛡️ Azure AD B2C Custom Policies

This repository contains custom policies (Identity Experience Framework - IEF) for Azure Active Directory B2C.
These policies extend the standard user flows to enable advanced authentication and user management scenarios.

#### 📘 Overview

Azure AD B2C custom policies (also known as Identity Experience Framework policies) allow full control over the authentication experience.
They define the complete sign-up, sign-in, and profile editing logic using XML-based configuration files.

This repo provides a working example of how to:

- Customize user journeys (sign-up, sign-in, password reset).
- Integrate with external identity providers (Google, Microsoft, etc.)
- Add custom claims transformations and validations.
- Manage localized UI and custom HTML templates.

#### 🚀 Getting Started

##### 1️⃣ Prerequisites
- An Azure AD B2C tenant.
- Azure portal access with permission to upload custom policies.
- App registrations for policy management.

##### 2️⃣ Setup
- Clone the repository:
  
```bash
  git clone https://github.com/vemurisrujan/Azure-B2C-Authentication-Policies.git
  cd Azure-B2C-Authentication-Policies
```
- Update XML files with your B2C tenant name and client IDs.
- Upload the policies in order (Base → Extensions → Relying Party) to your Azure B2C tenant.

#### 🧩 Key Features
- 🔐 Custom sign-in and sign-up with REST API integration.
- 🌐 Multi-language support (localized UI strings).
- 📞 External identity provider federation.
- 🧠 Claims enrichment and validation.
- 💅 Custom HTML/CSS for branded UI.

#### 🧠 Resources
- [Microsoft Docs: Azure AD B2C Custom Policies](https://learn.microsoft.com/en-us/azure/active-directory-b2c/custom-policy-overview).
- [IEF Starter Pack GitHub](https://github.com/Azure-Samples/active-directory-b2c-custom-policy-starterpack).
- [REST API Integration Guide](https://learn.microsoft.com/en-us/azure/active-directory-b2c/api-connectors-overview?pivots=b2c-custom-policy).
