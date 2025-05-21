---
title: Measuring Compliance of Consent Revocation on the Web
---

# Measuring Compliance of Consent Revocation on the Web

_Accepted at [PETS 2025](https://petsymposium.org/2025/), Washington DC, July 14–19, 2025_  
[Read the full paper](https://arxiv.org/abs/2411.15414)

---

## Motivation

The GDPR and ePrivacy Directive require that users must be able to revoke consent easily. Yet, research on how websites handle this right has been limited.

Our study analyzed 200 websites and found widespread **non-compliance** with revocation mechanisms.

---

## Key Findings

### 🧩 I. Non-compliant Revocation Interfaces

- ❌ 5.6% websites had **no revocation option**.
- ⚠️ 20% used a **different, harder interface** for revoking consent.
- ⚠️ 22% required **2–3 extra steps** to revoke using the same interface.

### 🔒 II. Poor Consent Revocation Storage & Communication

- ⚠️ 24.6% failed to register revocation consistently.
- 🚫 74.2% of TCF websites didn’t notify third parties.

### 🍪 III. Cookies Persist Despite Revocation

- ❌ 57.5% continued to store **advertising and analytics cookies** after revocation.

---

## Recommendations

- Enforce equal ease for revoking and granting consent.
- Standardize consent string storage and communication (via APIs & HTTP).
- Audit and enforce data deletion after consent is withdrawn.

---

## About the Authors

*Gayatri Priyadarsini*, *[Your Co-authors]*  
Part of an ongoing effort to hold digital platforms accountable to privacy laws.

---

> 💡 Want to know more? Visit [the full paper](https://arxiv.org/abs/2411.15414) or attend our talk at PETS 2025!
