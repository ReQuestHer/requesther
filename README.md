# ReQuestHer

A women's safety-focused service marketplace connecting clients with vetted, background-checked women service providers. Launching first in Chicago.

---

## What It Is

ReQuestHer is a platform similar to TaskRabbit or Thumbtack, built specifically around women's safety. Clients can find and book women service providers across categories like home repair, cleaning, beauty, wellness, and more. Every provider is background-checked, all communication stays in-app, and real-time location sharing is available during appointments.

---

## Current Status

Static HTML site — landing page, provider application, and supporting pages. Backend integration (Supabase, Stripe, Checkr, Twilio, Noonlight) is in progress.

---

## File Structure

| File | Purpose |
|------|---------|
| `index.html` | Main landing page — hero, waitlist form, how it works, safety pillars, provider application |
| `about.html` | About the platform and founding team |
| `contact.html` | Contact page |
| `services.html` | Service categories offered |
| `questhers.html` | Provider-facing information |
| `portal.html` | User portal (in progress) |
| `signup.html` | Signup flow (in progress) |

---

## Planned Integrations

| Service | Purpose |
|---------|---------|
| Supabase | Backend, authentication, database |
| Stripe Connect | Payments |
| Checkr | Provider background checks |
| Twilio | Phone masking / in-app communication |
| Noonlight | Emergency services integration |

---

## Branch Structure

| Branch | Purpose |
|--------|---------|
| `main` | Production — live site |
| `dev` | Active development |
| `test` | Testing before merging to main |

**Workflow:** make changes on `dev` → test on `test` → merge to `main` when ready.

---

## Contributing

Two contributors currently. All edits to content and copy go through `dev` branch. Backend integration handled separately.

---

## Contact

requesther.com · Launching Chicago 2026
