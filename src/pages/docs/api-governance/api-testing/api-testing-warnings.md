---
title: "API testing warnings"
updated: 2022-07-20
contextual_links:
  - type: section
    name: "Next Steps"
  - type: link
    name: "Security warnings"
    url: "/docs/api-governance/api-testing/security-warnings/"
search_keyword: "api security, security warnings, security validation, api security audit, api security scan, security audit"
---

> **This feature is in beta.** During the beta period, it may not be available to all Postman users and is subject to potential change.

Postman recommends that you follow common security best practices at the API testing phase of API development. A security warning doesn't mean that your API is broken! Instead, it indicates that there are potential security risks that your API might be vulnerable to. Postman highlights these security warnings and helps you understand their implications and possible ways to patch the warnings.

## Viewing security warnings during API testing

When you [send a request](/docs/sending-requests/requests/), Postman scans it for potential security risks.

If it detects any, Postman notifies you using a dot on the security overview icon <img alt="Security overview icon" src="https://assets.postman.com/postman-docs/icon-lock.jpg#icon" width="11px"> in the right sidebar.

1. Select the icon to view the warnings.
1. For more details, select a warning to expand it.
1. Select **Possible fix** to learn about possible ways to fix the underlying problem.

<img alt="Viewing security warnings in the right sidebar" src="https://assets.postman.com/postman-docs/api-governance-testing-warnings-beta.jpg" width="400px"/>

## Next steps

For the list of all the security warnings that Postman might show at the API testing phase of development, see [Security warnings](/docs/api-governance/api-testing/security-warnings/).
