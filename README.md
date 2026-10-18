# Mateusz Jendza

Identity & cloud architect. I spend most of my time around **Microsoft Entra ID**, **verifiable credentials / EUDI wallets**, and **infrastructure as code** on Azure.

I enjoy mountain biking (MTB) and spending time in the sauna, but since this is GitHub, let's focus on tech! ;)

> `Prediction is very difficult, especially about the future.`
> — Niels Bohr

![Azure](https://img.shields.io/badge/Azure-0078D4?style=for-the-badge&logo=microsoftazure&logoColor=white)
![Entra ID](https://img.shields.io/badge/Microsoft%20Entra%20ID-0067B8?style=for-the-badge&logo=microsoft&logoColor=white)
![Terraform](https://img.shields.io/badge/Terraform-844FBA?style=for-the-badge&logo=terraform&logoColor=white)
![.NET](https://img.shields.io/badge/.NET-512BD4?style=for-the-badge&logo=dotnet&logoColor=white)
![C#](https://img.shields.io/badge/C%23-239120?style=for-the-badge&logo=csharp&logoColor=white)
![PowerShell](https://img.shields.io/badge/PowerShell-5391FE?style=for-the-badge&logo=powershell&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)
![OpenID Connect](https://img.shields.io/badge/OpenID%20Connect-F78C40?style=for-the-badge&logo=openid&logoColor=white)

[![Followers](https://img.shields.io/github/followers/mjendza?style=for-the-badge&logo=github&label=Followers&color=181717)](https://github.com/mjendza?tab=followers)
[![Total stars](https://img.shields.io/github/stars/mjendza?affiliations=OWNER&style=for-the-badge&logo=github&label=Total%20stars&color=181717)](https://github.com/mjendza?tab=repositories)

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://github-profile-summary-cards.vercel.app/api/cards/profile-details?username=mjendza&amp;theme=github_dark">
  <img alt="GitHub profile summary" src="https://github-profile-summary-cards.vercel.app/api/cards/profile-details?username=mjendza&amp;theme=github">
</picture>

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://github-profile-summary-cards.vercel.app/api/cards/repos-per-language?username=mjendza&amp;theme=github_dark">
  <img alt="Top languages by repository" src="https://github-profile-summary-cards.vercel.app/api/cards/repos-per-language?username=mjendza&amp;theme=github">
</picture>
<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://github-profile-summary-cards.vercel.app/api/cards/most-commit-language?username=mjendza&amp;theme=github_dark">
  <img alt="Top languages by commit" src="https://github-profile-summary-cards.vercel.app/api/cards/most-commit-language?username=mjendza&amp;theme=github">
</picture>

**Find me:** [mjendza.net](https://mjendza.net) · [github.com/mjendza](https://github.com/mjendza)

<!-- TODO: add social handles here, e.g. LinkedIn / X / Mastodon — or delete this comment. -->

---

## Contents

- [What I Build](#what-i-build)
- [Digital Identity](#digital-identity) — verifiable credentials, EUDI, OAuth/OIDC, CIAM
- [Microsoft Entra ID](#microsoft-entra-id) — the big one
- [Azure and Cloud Architecture](#azure-and-cloud-architecture)
- [Software Architecture](#software-architecture)
- [AI](#ai)
- [Tools and Workstation](#tools-and-workstation)
- [Home Lab and Smart Home](#home-lab-and-smart-home)
- [People, Blogs and Feeds](#people-blogs-and-feeds)
- [OS and Hardware](#os-and-hardware)
- [Fun and Off-topic](#fun-and-off-topic)

Everything below is a personal, opinionated collection of links and resources that changed how I work.

---

## What I Build

- [**workshop-entra-as-code-interactive**](https://github.com/mjendza/workshop-entra-as-code-interactive) — hands-on workshop: managing Microsoft Entra ID declaratively, as code.
  [![Stars](https://img.shields.io/github/stars/mjendza/workshop-entra-as-code-interactive?style=flat&logo=github&label=stars)](https://github.com/mjendza/workshop-entra-as-code-interactive/stargazers)
  [![Last commit](https://img.shields.io/github/last-commit/mjendza/workshop-entra-as-code-interactive?style=flat&logo=github)](https://github.com/mjendza/workshop-entra-as-code-interactive/commits)
- [**terraform-provider-verifiedid**](https://github.com/mjendza/terraform-provider-verifiedid) — Terraform provider for Microsoft Entra Verified ID.
  [![Stars](https://img.shields.io/github/stars/mjendza/terraform-provider-verifiedid?style=flat&logo=github&label=stars)](https://github.com/mjendza/terraform-provider-verifiedid/stargazers)
  [![Last commit](https://img.shields.io/github/last-commit/mjendza/terraform-provider-verifiedid?style=flat&logo=github)](https://github.com/mjendza/terraform-provider-verifiedid/commits)
- [**agents for Entra ID**](https://github.com/mjendza/terraform-provider-verifiedid) — Series of Entra ID Agents
  [![Stars](https://img.shields.io/github/stars/mjendza/entra-id-agents?style=flat&logo=github&label=stars)](https://github.com/mjendza/entra-id-agents/stargazers)
  [![Last commit](https://img.shields.io/github/last-commit/mjendza/entra-id-agents?style=flat&logo=github)](https://github.com/mjendza/entra-id-agents/commits)
---

## Digital Identity

### Verifiable Credentials & EUDI

#### Products & Libraries

| Name                                        | Details & Supported Format                                        | Link                                                                                          |
|---------------------------------------------|-------------------------------------------------------------------|-----------------------------------------------------------------------------------------------|
| FIDES Community                             | Discover organizations shaping the global ecosystem of digital wallets and verifiable credentials |https://fides.community/organizations/                         | 
| Paradym                                     | Dedicated Wallet (format: sd+vc-json)*                            | https://paradym.id/ & https://play.google.com/store/apps/details?id=id.paradym.wallet         |
| Entra Verified ID                           | Authenticator App + Wallet SDK from MS                            | https://www.microsoft.com/en-us/security/business/identity-access/microsoft-entra-verified-id |
| Demo: vcplayground                          | jwt-vc-json                                                       | https://vcplayground.org/                                                                     |
| Demo: funke.animo.id                        | EUDI/cred-ts                                                      | https://funke.animo.id/ - (test credo-ts solution)                                            |
| Playground: hovie.id                        | EUDI + VerifiedID                                                 | https://playground.hovi.id/                                                                   |
| Test & Playground EUDI Dev Wallet           | EUDI                                                              | https://eudi-test.dev                                                                         |
| Unofficial EUDI Wallet Dev Toolkit          | EUDI                                                              | https://github.com/dominikschlosser/eudi-dev                                                  |
| WalletSDK                                   | works with vcplayground (format:jwt-vc-json)*                     | https://github.com/trustbloc/wallet-sdk                                                       |
| credo-ts                                    | Full VC Backend (format:sd+vc-json) hosted with docker compose 💪 | https://github.com/openwallet-foundation/credo-ts https://credo.js.org/                       |
| walt.id                                     | Backend with wallet                                               | https://docs.walt.id/community-stack/home                                                     |
| bifold                                      | React native wallet                                               | https://github.com/openwallet-foundation/bifold-wallet                                        |
| MS Authenticator App                        | VC Wallet Product                                                 |                                                                                               |
| .Net Wallet                                 | Not Updated for long time                                         | https://github.com/openwallet-foundation-labs/wallet-framework-dotnet                         |
| didwebvh /didwebvh-ts                       | play with did:webvh                                               | https://github.com/decentralized-identity/didwebvh-ts                                         |
| Apostille - Verifiable Credentials Platform |                                                                   | https://github.com/openwallet-foundation-labs/apostille                                       |

*Not confirmed via official pages and documentation

#### Specifications — Final

- https://openid.net/specs/openid-4-verifiable-credential-issuance-1_0.html
- https://openid.net/specs/openid-4-verifiable-presentations-1_0.html
- https://openid.net/specs/openid4vc-high-assurance-interoperability-profile-1_0-final.html

#### Specifications — Drafts & Concepts

- https://github.com/pic-protocol/pic-spec/blob/main/draft/0.1/pic-spec.md
- Wallet to Wallet https://docs.eudi.dev/latest/reference-implementation/feature-map/#wallet-to-wallet
- [Specification of Strong Customer Authentication (SCA) Implementation with the Wallet](https://github.com/eu-digital-identity-wallet/eudi-doc-standards-and-technical-specifications/blob/main/docs/technical-specifications/ts12-electronic-payments-SCA-implementation-with-wallet.md)

#### Platform Support

Android:

- https://android-developers.googleblog.com/2025/04/announcing-android-support-of-digital-credentials.html
- https://developer.android.com/identity/digital-credentials/credential-verifier
- https://developer.android.com/identity/digital-credentials/phone-number-verification

iOS:

- https://developer.apple.com/documentation/BundleResources/Entitlements/com.apple.developer.identity-document-services.document-provider.mobile-document-types

#### Ecosystem, Demos & Reading

- [VC for Europeans](https://github.com/goeIDAS/testbed)
- [eIDAS test site](https://test.eid.as/)
- [Decentralized Identifiers (DIDs) as an Identifier Metasystem](https://blog.identity.foundation/decentralized-identifiers-dids-as-an-identifier-metasystem/)
- [Awesome Self-Sovereign Identity](https://github.com/animo/awesome-self-sovereign-identity)
- https://github.com/decentralized-identity/didcomm-messaging
- https://demo.didcomm.org/ :arrow_up_small:
- CH https://github.com/e-id-admin/eidch-android-wallet
- EU https://github.com/orgs/eu-digital-identity-wallet/repositories
- KeyCloack https://keycloak-day.dev/assets/files/Norimatsu_KeycloakDevDay2025_Darmstadt.pdf
- https://www.verifiedorchestration.com/
- [EU: Digital Product Passport DDP](https://single-market-economy.ec.europa.eu/single-market/digital-product-passport_en)
- to check: https://www.ethentic.eu/
- [Takahiko Kawasaki/VC Deep Dive/Issuing verifiable credentials in the SD-JWT VC and mdoc/mDL formats, mandated in eIDAS 2.0](https://darutk.medium.com/oid4vci-demo-87a232cfcc2a)
- [How VC Issuance works](https://www.authlete.com/developers/oid4vci/)

#### DID & VC Tools

- DID Resolver: https://dev.uniresolver.io/

### OAuth 2.0, OIDC & Tokens

#### Learning the Protocols

- [OCTA: OAuth 2.0 and OpenID Connect (in plain English)](https://www.youtube.com/watch?v=996OiexHze0)
- [OAuth – the good Parts - Dominick Baier - NDC Oslo 2021](https://www.youtube.com/watch?v=y2Psj8ACZyw)
- [An Illustrated Guide to OAuth and OpenID Connect](https://developer.okta.com/blog/2019/10/21/illustrated-guide-to-oauth-and-oidc)
- https://www.nango.dev/blog/why-is-oauth-still-hard
- [awesome-iam](https://github.com/kdeldycke/awesome-iam)
- [Openid Connect Diagram - get token via confidential client](https://learn.microsoft.com/en-us/entra/identity-platform/v2-protocols-oidc#protocol-diagram-access-token-acquisition)
- [Authentication with multiple identity providers](https://damienbod.com/2023/11/13/authentication-with-multiple-identity-providers-in-asp-net-core/)

#### Tokens, Cookies & Sender Constraining

- :lock: [Demystifying cookies and tokens](https://tommihovi.com/2024/05/demystifying-cookies-and-tokens/)
- DPoP https://auth0.com/docs/secure/sender-constraining/demonstrating-proof-of-possession-dpop & https://auth0.com/blog/protect-your-access-tokens-with-dpop/
- https://brave.com/blog/zklogin/

#### Authorization & Policy

- https://auth0.com/docs/authorization
- :lock: FGA solution https://docs.permit.io/modeling/mesa-verde/ & DEMO https://github.com/permitio/mesa-verde-banking-demo
- Cedar [video](https://www.youtube.com/watch?v=Oh0EaisUtYI&t=1829s) & into token [Cedar policy with an access token](https://www.linkedin.com/feed/update/urn:li:activity:7348099179870568448/)
- https://blog.christianposta.com/api-keys-are-a-bad-idea-for-enterprise-llm-agent-and-mcp-access/
- https://www.linkedin.com/pulse/implementing-mcp-dynamic-client-registration-spiffe-keycloak-posta-ccryf

#### Standards & Guidance

- Annotated Version of NIST Special Publication (SP) 800-63-4, Digital Identity Guidelines: https://www.tcannex.com/p/annotated-nist-sp-800-63-4
- CIAM MS Overview: https://www.microsoft.com/en-us/security/business/security-101/what-is-ciam

### CIAM & IAM Platforms

#### Hosted

- https://auth0.com/
- https://stytch.com/
- https://www.descope.com/
- https://clerk.com
- :lock: AWS Cognito Sample https://medium.com/@samudurand/protecting-lambda-urls-with-cognito-iam-lambda-edge-and-cdk-4ac79f9e779c

#### Self-Hosted

- https://goauthentik.io/
- https://www.keycloak.org/

#### Vendor Demos

- [Microsoft Woodgrove Groceries -> Azure AD B2C MS Demo](https://woodgrovegroceries.net/)
- [Microsoft Woodgrove Groceries -> Entra External ID for Customers MS Demo](https://woodgrovedemo.com/)

### Open Source IAM Projects

- https://github.com/discord/access
- https://github.com/jhaals/yopass
- https://github.com/JanssenProject/jans
- https://github.com/jelhub/scimgateway

### Identity Testing & Debugging Tools

- Debug OIDC flows: https://oidcdebugger.com/debug
- Review & analyze tokens: https://jwt.ms & https://jwt.io
- Generate tokens: https://token.dev/
- Test FIDO2/Passkeys: https://www.token2.swiss/tools/fido2-demo
- [SAML DevTools extension](https://chrome.google.com/webstore/detail/saml-devtools-extension/jndllhgbinhiiddokbeoeepbppdnhhio)
- Online SMS service to test OTP: https://anonymsms.com/
- Temporary Email Service (allows custom email addresses): https://www.minuteinbox.com/
- Virtual Phone Numbers: https://www.twilio.com/en-us/phone-numbers
- A verification tool to replace CAPTCHA: https://www.cloudflare.com/products/turnstile/
- https://www.iredmail.org/

---

## Microsoft Entra ID

### Fundamentals & Deep Dives

- https://github.com/merill/awesome-entra
- Big picture diagram: https://github.com/msandbu/azuread
- [Journey to Azure AD PRT- Primary Refresh Token](https://aadinternals.com/post/prt/)
- [Entra Primary Refresh Token](https://learn.microsoft.com/en-us/entra/identity/devices/concept-primary-refresh-token?tabs=windows-prt-issued%2Cwindows-prt-used%2Cwindows-prt-renewal%2Cwindows-prt-protection%2Cwindows-apptokens%2Cwindows-browsercookies%2Cwindows-mfa)
- [Understanding Entra ID App Registrations, Enterprise Applications and Service Principals (part 2)](https://heusser.pro/p/understanding-entra-id-app-registrations-enterprise-applications-and-service-principals-part-2-os8rb48knqez/)
- Agent ID: https://learn.microsoft.com/en-us/entra/agent-id/identity-platform/
- https://derkvanderwoude.medium.com/agent-identity-security-demystified-2ecb164239bf
- :lock: https://learn.microsoft.com/en-us/entra/global-secure-access/how-to-configure-kerberos-sso
- [**Workload Identity Protection**](https://youtu.be/TASsrY_ilWc)
- [**Governance**](https://youtu.be/yqiZhVdo6WE)
- [**Managed ID**](https://youtu.be/rC1TV0_sIrM)
- [**App Registrations, Enterprise Apps and Service Principals**](https://youtu.be/WVNvoiA_ktw)
- [**PIM**](https://youtu.be/gccgIkR8_a0)
- [Deep Dive into Entra: Exclusive Outage Stories & Architectural Innovations](https://www.youtube.com/watch?v=PtEQYnRu6eo)
- Actor tokens security issue: https://dirkjanm.io/obtaining-global-admin-in-every-entra-id-tenant-with-actor-tokens/
- ACS: https://learn.microsoft.com/en-us/previous-versions/azure/active-directory/azuread-dev/active-directory-acs-migration

### News & Roadmap

- https://learn.microsoft.com/en-us/entra/fundamentals/whats-new-ignite-2025#microsoft-entra-external-id
- https://learn.microsoft.com/en-us/entra/identity/hybrid/user-source-of-authority-overview
- https://learn.microsoft.com/en-us/entra/identity/authentication/synced-passkey-faq
- Feature plan & list (not official): https://deltapulse.app/dashboard
- https://tech.nicolonsky.ch/AiTM-Phishing-with-Azure-Functions/

### Licensing & Features

- https://www.microsoft.com/en-us/security/business/microsoft-entra-pricing
- https://learn.microsoft.com/en-us/entra/id-governance/licensing-fundamentals#features-by-license

### Governance

- [An introduction to Azure AD Identity Governance](https://identity-man.eu/2020/11/23/an-introduction-to-azure-ad-identity-governance/)
- https://www.christianfrohn.dk/2025/01/15/monitoring-access-package-delivery-status-in-entra-id-governance/
- https://janbakker.tech/dynamic-approval-in-entra-id-access-packages-using-custom-extensions/
- Review permissions: https://m365scripts.com/microsoft365/manage-entra-id-delegated-permissions-for-specific-users-using-microsoft-graph/

### Conditional Access

- https://learn.microsoft.com/en-us/entra/identity/conditional-access/service-dependencies
- https://learn.microsoft.com/en-us/entra/identity/conditional-access/concept-conditional-access-cloud-apps?tabs=powershell#office-365
- https://learn.microsoft.com/en-us/entra/identity/conditional-access/concept-token-protection
- https://cloudbrothers.info/en/conditional-access-bypasses/

### Workload Identity

- https://device-insight.com/en/developers-blog/use-azure-ad-workload-identity-for-pod-assigned-managed-identity-in-aks/
- https://johnlokerse.dev/2024/05/05/setup-azure-devops-workload-identity-federation-using-azure-bicep/
- https://ourcloudnetwork.com/direct-managed-identity-or-federated-managed-identity/

### Account Recovery

- https://learn.microsoft.com/en-us/entra/identity-platform/tutorial-custom-authentication-extension-account-recovery?tabs=azure-portal
- https://github.com/Azure-Samples/active-directory-verifiable-credentials-dotnet/tree/main/7-AccountRecovery-ClaimsMatching

### Security & Monitoring

- https://github.com/Cloud-Architekt/AzureAD-Attack-Defense
- https://github.com/reprise99/Sentinel-Queries
- https://learn.microsoft.com/en-us/security/operations/incident-response-playbooks
- https://learn.microsoft.com/en-us/entra/architecture/security-operations-introduction
- https://github.com/guardzcom/security-research-labs/tree/main/AI-Cloud-Tools/M365-Tools/EntraReaper
- Workbooks: https://github.com/davidalonsod/Dalonso-Security-Repo/tree/main/Workbooks

#### KQL

- https://www.systanddeploy.com/2025/10/dashboard-of-windows-authentication.html
- https://learnsentinel.blog/2022/06/21/kql-lessons-learnt-from-365daysofkql/
- https://github.com/davidalonsod/Dalonso-Security-Repo
- https://github.com/benscha/KQLAdvancedHunting

### Entra as Code

- 📌 [My workshop: Entra as Code](https://github.com/mjendza/workshop-entra-as-code-interactive)
- https://registry.terraform.io/providers/hashicorp/azuread/latest
- https://www.terraprovider.com/
- https://blog.kewalaka.nz/post/2025/11/avm-pim-group-module/
- https://mattias.engineer/blog/2026/terraform-github-1/

### Tools & Repositories

- https://github.com/microsoft/EntraExporter
- https://github.com/microsoft/Microsoft365DSC
- https://github.com/kayasax/SCIMTool
- https://github.com/ThomasKur/M365Documentation
- https://github.com/Cloud-Architekt/EntraOps
- https://github.com/LETHAL-FORENSICS/Microsoft-Analyzer-Suite
- https://github.com/Noble-Effeciency13/M365IdentityPosture
- https://github.com/Semperis/EntraGoat
- https://github.com/IdentityMan/MasterclassELDK26
- https://github.com/maester365/maester
- https://github.com/jflieben/DriftMaester

#### Online Tools

- https://permissions.factorlabs.pl/
- https://entrascopes.com/
- https://github.com/merill/microsoft-info
- https://entratracker.aboutcloud.io/
- https://docstracker.marshsecurity.org/

### Development & Samples

- Summary of MS samples & platforms: https://learn.microsoft.com/en-us/entra/identity-platform/sample-v2-code
- ASP.NET Web App - Confidential Client: https://github.com/Azure-Samples/active-directory-aspnetcore-webapp-openidconnect-v2
- https://github.com/Azure-Samples/active-directory-dotnetcore-daemon-v2
- JavaScript Public Client: https://github.com/Azure-Samples/ms-identity-docs-code-javascript
- For External ID sample: https://github.com/Azure-Samples/ms-identity-ciam-javascript-tutorial
- Graph Explorer (with tenant-id param): https://developer.microsoft.com/en-us/graph/graph-explorer?tenant={{tenant-id-here}}
- [OAuth - Native Flow Authorization Code Flow Diagram + Postman Collection](https://learn.microsoft.com/en-us/azure/active-directory/develop/v2-oauth2-auth-code-flow#protocol-details)
- [Postman Oauth Entra ID Collection](https://www.postman.com/platform-collections/workspace/d/collection/18113418-00c88086-f071-4ad6-901a-49ac46b33a63)
- [Default Azure Credentials](https://nestenius.se/2024/04/18/default-azure-credentials-under-the-hood/)
- MCP + Azure OAuth2 OBO: https://jaydoubleu.dev/guides/mcp-azure-oauth2-obo

#### Azure AD B2C

- https://gist.github.com/rbrayb/847be01d7f2c532d66cf07ad84d6466d
- OpenID Connect details: https://learn.microsoft.com/en-us/azure/active-directory-b2c/openid-connect
- Debugging setup: VS Code + B2C extension + App Insights debugger

#### External ID

- https://learn.microsoft.com/en-us/entra/external-id/external-identities-overview#comparing-external-id-feature-sets
- https://learn.microsoft.com/en-us/entra/external-id/customers/concept-supported-features-customers
- https://learn.microsoft.com/en-us/entra/identity/users/convert-external-users-internal
- :lock: https://learn.microsoft.com/en-us/entra/architecture/external-identity-deployment-architectures

#### MSAL

- Refresh Token: https://github.com/AzureAD/microsoft-authentication-library-for-js/issues/5137
- https://learn.microsoft.com/en-us/entra/msal/dotnet/acquiring-tokens/desktop-mobile/linux-dotnet-sdk-wsl
- [MSAL - Retry policies](https://learn.microsoft.com/en-us/entra/msal/dotnet/advanced/exceptions/retry-policy)
- [MSAL Logger](https://learn.microsoft.com/en-us/entra/msal/dotnet/advanced/exceptions/msal-logging#iidentitylogger-implementation)

### PowerShell

- https://www.powershellgallery.com/packages/PSPreworkout

### Windows & Intune

- https://swjm.blog/the-complete-guide-to-rdp-with-yubikeys-fido2-cba-1bfc50f39b43
- https://mjshellenberger.com/2024/10/31/configure-microsoft-cloud-pki-a-step-by-step-guide/

---

## Azure and Cloud Architecture

### Cloud Adoption Framework & Landing Zones

- https://github.com/Azure/Enterprise-Scale
- https://learn.microsoft.com/en-us/azure/cloud-adoption-framework/ready/landing-zone/ with a nice [Visio drawing](https://github.com/microsoft/CloudAdoptionFramework/raw/main/ready/enterprise-scale-architecture.vsdx)
- https://github.com/Azure/ALZ-Bicep/wiki/Accelerator
- [GitHub - ACA-Landing-Zone-Accelerator](https://github.com/Azure/ACA-Landing-Zone-Accelerator)
- https://github.com/Azure/terraform-azurerm-lz-vending
- [Prepare your Azure Cloud Environment with the Cloud Adoption Framework](https://www.thomasmaurer.ch/2023/07/prepare-your-azure-cloud-environment-with-the-cloud-adoption-framework/)
- [Terraform CAF Enterprise Scale walkthrough](https://www.youtube.com/watch?v=IyQM_wG_X_Q) & https://github.com/Azure/terraform-azurerm-caf-enterprise-scale

### Azure Services & Cost

- https://github.com/mivano/azure-cost-cli
- https://azurealan.ie/2025/11/08/using-traffic-manager-to-failover-or-bypass-azure-front-door/
- https://azurecharts.com/

### Azure Policy

- https://blog.tyang.org/2021/12/06/monitoring-azure-policy-compliance-states-2021-edition and connected repo: https://github.com/andrewmatveychuk/azure.policy

### Azure Security

- https://medium.com/@omaxel/allow-access-to-azure-app-service-only-from-azure-front-door-bdfa16bc675d
- https://cloudtips.nl/securing-azure-web-apps-and-function-apps-with-azure-front-door-e4a5e4071290

### Computing
#### Container Apps 
- https://cloudtips.nl/automate-microsoft-azure-tasks-with-azure-container-app-jobs-%EF%B8%8F-c8f8ec037495
- https://learn.cloudpartner.fi/posts/azure-container-apps-express-built-on-sandboxes

### DevOps & IaC

- https://azure.github.io/Azure-Verified-Modules/
- https://github.com/Azure/bicep-registry-modules
- https://medium.com/into-alm/configuration-as-code-moving-away-from-library-groups-in-azure-devops-e9ff683d150d
- https://github.com/arindam0310018/10-Oct-2023-DevOps__Workload-Identity-Federation-with-Service-Principal-Using-Terraform
- https://spacelift.io/ (Terraform & OpenTofu)
- https://registry.terraform.io/modules/Azure-Terraformer/atat/github/latest

### Microsoft 365

- [Microsoft 365 Licensing Map](https://m365maps.com/)

---

## Software Architecture

### Styles & Patterns

- Architecture Styles Worksheet: https://www.developertoarchitect.com/downloads/architecture-styles-worksheet.pdf
- https://jacquiread.com/posts/software-design/
- Distributed systems real-life example: https://www.enterpriseintegrationpatterns.com/ramblings/18_starbucks.html
- [Advanced API and Integration Problems & Patterns - Udi Dahan - NDC Oslo 2022](https://www.youtube.com/watch?v=vNouCMGP1eE)
- :boom: [Learn Advanced Distributed Systems Design](https://particular.net/adsd)
- [Microfrontends that don't hurt (ASP.NET Core)](https://developersvoice.com/blog/frontend/microfrontends-that-dont-hurt-aspnet-core/)

### Evolutionary Architecture

- By example: [GitHub](https://github.com/evolutionary-architecture/evolutionary-architecture-by-example) and [Video](https://github.com/evolutionary-architecture/evolutionary-architecture-by-example?tab=readme-ov-file#videos-)

### Books, Talks & Essays

- 📖 [The Software Architect Elevator](https://www.amazon.com/Software-Architect-Elevator-Redefining-Architects/dp/1492077542)
- 📖 [Designing Data-Intensive Applications](https://www.amazon.com/Designing-Data-Intensive-Applications-Reliable-Maintainable/dp/1449373321)
- 📖 [Database Internals](https://www.amazon.com/_/dp/1492040347)
- :hammer: [(Almost) Every infrastructure decision I endorse or regret after 4 years running infrastructure at a startup](https://cep.dev/posts/every-infrastructure-decision-i-endorse-or-regret-after-4-years-running-infrastructure-at-a-startup/)
- [Functional Programming on .NET - The Best of Both Worlds - Isaac Abraham - NDC Oslo 2024](https://www.youtube.com/watch?v=V9GYPOsPj4M)
- [Let's build the worst Event Sourcing system! - Oskar Dudycz - NDC London 2024](https://www.youtube.com/watch?v=20zvAJAhqS0)
- :hammer: [PL Async Internals in .NET](https://www.youtube.com/watch?v=OfLK1a1jUjU&t=2862s)
- [Serverless Chats: Streaming Data at Scale Using Serverless with Anahit Pogosova Part 1](https://open.spotify.com/episode/117MX2HHDcOGWFcw8XBoA5)
- [Serverless Chats: Streaming Data at Scale Using Serverless with Anahit Pogosova Part 2](https://open.spotify.com/episode/0s1zyqP21k6LwECLZAxSje)

### .NET

- https://github.com/Finbuckle/Finbuckle.MultiTenant

### Documentation & Diagramming

- https://backstage.io & https://github.com/backstage/backstage
- https://www.websequencediagrams.com/
- 👑 https://plantuml.com/ & https://github.com/plantuml-stdlib/C4-PlantUML

---

## AI

📌 **[Dedicated page: what I use daily, Claude Code, MCP servers →](ai/README.md)**

### LLM Solutions & RAG

- https://techcommunity.microsoft.com/blog/azure-ai-services-blog/graphrag-end-to-end-poc/4361080
- https://learn.microsoft.com/azure/cosmos-db/gen-ai/quickstart-rag-chatbot

### MCP

- Microsoft Learn MCP Server https://github.com/MicrosoftDocs/mcp
- Lokka - MS Entra Graph API MCP: https://lokka.dev/docs/install
- Atlas MCP server that provides access to Microsoft Graph API using Entra ID authentication with On-Behalf-Of (OBO) flow: https://github.com/JasSuri/atlas
- https://github.com/rinadelph/Agent-MCP
- https://techcommunity.microsoft.com/blog/azure-ai-foundry-blog/deployment-guide-copilot-studio-agent-with-mcp-server-exposed-by-api-management-/4462432

---

## Tools and Workstation

### Development & Testing

- Mock Service (useful for checking request payloads 😉): https://beeceptor.com/
- Temp mail (trashmail) as a service: https://github.com/HaschekSolutions/opentrashmail
- Find a free replacement: https://openalternative.co
- https://pagespeed.web.dev/
- HTTP benchmarking: https://github.com/codesenberg/bombardier

### Network & Web

- :hammer: :lock: Secure your website with the right security headers — [Mozilla Observatory](https://observatory.mozilla.org/) and [SecurityHeaders](https://securityheaders.com/)
- My own score: https://observatory.mozilla.org/analyze/mjendza.net
- https://blog.icewolf.ch/archive/2023/05/28/http-security-headers/
- Speed test with details: https://speed.cloudflare.com/
- https://report-uri.com/
- https://redbot.org/
- https://netbird.io/ (tailscale alternative)

### Workflow Automation

- https://n8n.io
- https://kestra.io/
- https://airflow.apache.org/

### Tunnels & Proxies

- [www.cloudflare.com Tunnel](https://www.cloudflare.com/products/tunnel/)
- :heart_eyes_cat: https://tailscale.com
- ngrok.com - need to pay 10$ for features
- Visual Studio IDE built-in proxy

Tailscale — enable proxy for a service:

```
tailscale serve --service=svc:my-name-of-service --https=3000 http://localhost:3000
```

### Everyday Utilities

- https://ntfy.sh/ (push notifications)
- Kleopatra - manage Yubikey certificates, etc https://apps.kde.org/kleopatra/
- Faking data and getting notification someone is accessing it (credit card, AWS credentials): https://canarytokens.org/generate
- https://www.base64decode.org/
- https://www.urlencoder.org/
- https://parseurlonline.com/
- https://asecuritysite.com/
- https://www.bestrandoms.com/random-address-in-us
- https://iancoleman.io/bip39/#english
- https://comparisontabl.es/cloud-storage/

### OSINT & SOC

- https://osint.aadinternals.com/
- https://soctoolkit.com/

---

## Home Lab and Smart Home

- :heart_eyes_cat: HomeAssistant: https://www.home-assistant.io/
- esphome https://esphome.io/ (ESP8266 | ESP32 | other => easy yaml config and push to HomeAssistant)
- Portainer https://www.portainer.io/ (Container Management for Docker)
- Home DNS server? Try PiHole https://pi-hole.net/
- OpenWrt as router OS https://openwrt.org/
- Smart switches and other devices https://www.shelly.com/
- HVAC: Salus Controls & Panasonic AC (with https://github.com/sockless-coding/panasonic_cc integration)
- https://mqtt-explorer.com/

---

## People, Blogs and Feeds

### Blogs

- https://damienbod.com/
- https://identity-man.eu/
- https://www.troyhunt.com/
- https://scotthelme.co.uk/
- https://event-driven.io/ and the tag Architecture: https://event-driven.io/en/category/architecture/
- https://blog.codingmilitia.com/
- https://architectelevator.com/
- https://ericonidentity.com/
- https://discovery.cevolution.co.uk/ciam/

### Entra ID Blogs

- https://ourcloudnetwork.com/
- https://www.cloud-architekt.net/
- https://cloudbrothers.info/

### Newsletters & Feeds

- https://entra.news
- https://newsletter.identosphere.net/

---

## OS and Hardware

- https://omarchy.org/
- [Pop!_OS](https://system76.com/pop/)

---

## Fun and Off-topic

- [Boris Cherny (Creator of Claude Code) On What Grew His Career And Building at Anthropic](https://www.youtube.com/watch?v=AmdLVWMdjOk)
- [Hacking Formula 1: Accessing Max Verstappen's passport and PII through FIA bugs](https://ian.sh/fia)
- [Wat](https://www.destroyallsoftware.com/talks/wat)
- [Email vs Capitalism, or, Why We Can't Have Nice Things - Dylan Beattie - NDC Oslo 2023](https://www.youtube.com/watch?v=mrGfahzt-4Q)
- [Foxes](https://sprocketfox.io/xssfox/2021/01/18/pipeline/)
- [Mountain Biking](https://www.youtube.com/watch?v=WPVRU7jSYkQ)
- [Żywot programisty](https://youtu.be/_q-l6Cn6WxY) - Sorry, only for Polish programmers :construction_worker:
- Morse code translator: https://github.com/ozdemirburak/morse-code-translator
