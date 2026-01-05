---
title: Authentication
---

# Authentication

DataTyper uses Figma OAuth for authentication.  
This means you sign in using your Figma account, and DataTyper never handles your password.

## On this page

- [How authentication works](#how-authentication-works)
- [What DataTyper stores](#what-datatyper-stores)
- [Where the token is stored](#where-the-authorization-token-is-stored)
- [Logging out and revoking access](#logging-out-and-access-revocation)


---

## How authentication works

When you open DataTyper, you are redirected to Figma’s authorization flow.

During this process:

- You authenticate directly with Figma
- Figma issues an authorization token
- DataTyper uses this token to identify you and access the plugin API

DataTyper does **not** implement its own authentication system.

---

## What DataTyper does NOT store

DataTyper **never stores**:

- Figma passwords
- OAuth secrets
- API keys
- Any other sensitive authentication credentials

All authentication is delegated to Figma.

---

## Where the authorization token is stored

<div class="callout tip">
<strong>Tip</strong><br>
If you share a computer, sign out from Figma to revoke local access.
</div>



The authorization token issued by Figma is stored:

- **Locally**
- Inside **Figma clientStorage**
- On the **user’s own computer**

The token is not stored in plain text databases and is not shared with other users.

---

## What DataTyper stores

To function correctly, DataTyper stores a minimal set of user information on its servers:

- Figma user ID
- Email address
- Display name
- Avatar image

This information is used only to:
- identify the user
- associate datasets with their owner
- enable collaboration features

---

## Logging out and access revocation

You can revoke DataTyper’s access at any time:

- From Figma account settings
- Or by removing the plugin

Once access is revoked:
- The authorization token becomes invalid
- DataTyper can no longer access your account

---

## Security model summary

- Authentication is handled by Figma OAuth
- No passwords or secrets are stored by DataTyper
- Tokens are stored locally in Figma clientStorage
- Only minimal user profile data is stored server-side

For details about data handling and user responsibilities, see the **Privacy Policy**.

<!-- DATATYPER_DOCS_NAV -->
<div class="docs-page-nav">
  <a href="/">← Getting Started</a>
  <a href="/datasets/overview">Overview →</a>
</div>
