## Privacy, Consent, and Zero-Trust Enforcement

Buzzomatic implements a **device-level Zero-Trust privacy model**.

### Consent Architecture
- ePrivacy consent is enforced before any non-essential storage or access
- GDPR applies to all identifiers derived from cookies or SDKs
- Consent is collected via a certified CMP (TCF v2.2)

### Technical Controls
- No analytics, advertising, or social SDK initializes pre-consent
- SDKs receive consent state explicitly; mediation does not imply consent
- Consent withdrawal triggers immediate SDK shutdown

### User Choice
- Rejecting non-essential processing does not block access
- Consent can be withdrawn at any time with equal ease

Buzzomatic observes machines, not people.
# Guangzhou
CMP Engineering Flow Diagram — Current-State (2025–2026)
