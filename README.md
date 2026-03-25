# IAM-Lab
Phase 1: User Creation (Joiner)
This phase focuses on the initial onboarding of users into the Okta Directory and observing the lifecycle transition from Staged to Active.

1. Manual Provisioning & Staged Status
I initiated the Joiner process by manually creating two users via Directory → People. This allowed me to test different activation flows:

User A: Self-activation via email.

User B: Admin-set password for immediate access.

Observation: Before the first user interacted with their email, the account held a Staged status. This is a critical security state where the identity exists but cannot yet authenticate.
