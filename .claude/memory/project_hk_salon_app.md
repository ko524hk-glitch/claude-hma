---
name: hk-salon-app
description: "Hong Kong salon discovery app project — goals, tech stack, revenue model, risks, and roadmap"
metadata: 
  node_type: memory
  type: project
  originSessionId: 5692d64f-148f-458d-ae32-b9ff780cce63
---

# Hong Kong Salon Discovery App (香港髮廊探索應用程式)

Founder is a non-technical solo entrepreneur building a salon discovery and booking platform for Hong Kong residents.

**Why:** Fills a gap that Google Maps can't — hair-specific filters, stylist profiles (trackable across salons), before/after photo gallery, verified reviews (booking required to leave review), transparent pricing, in-app booking.

**Revenue model:** Booking commission via Stripe Connect.

**Languages supported:** Traditional Chinese, Simplified Chinese, English.

**Search:** By Hong Kong district (Causeway Bay, Mong Kok, Central, etc.)

**Rating system:** Overall star (1–5) + category scores (hygiene, skill, value, attitude). Only users who booked via platform can leave reviews.

**Payments:** Credit card, FPS, Alipay HK via Stripe.

**Platform:** Web first → iOS later (after web version matures).

## Tech Stack (No-code MVP)
- **App:** Bubble.io (~HK$155/mo)
- **Database & Auth:** Supabase (free tier — risk: pauses after 7 days idle)
- **Payments:** Stripe Connect (3.4% + HK$2.35 per transaction)
- **Maps:** Google Maps API (~8,000 free calls/mo)
- **Email:** Resend (3,000 free/mo)
- **Design:** Figma (free)
- **Marketing:** Instagram + 小紅書 (free)

## Monthly Costs
- MVP: ~HK$65/mo
- Growth: ~HK$650–1,600/mo
- Net per HK$500 booking at 10% commission: ~HK$30.65 after Stripe fees

## 4-Phase Roadmap
1. **Weeks 1–4:** Validate market — visit 10 salons, interview 15 users
2. **Weeks 5–8:** Design — Figma clickable prototype, user testing
3. **Months 3–6:** Build — Bubble.io web app, connect Stripe + Google Maps
4. **Months 6–7:** Launch — onboard 20 salons in 2 districts manually, social media, then iOS

## Top 3 Risks
1. **Chicken-and-egg:** Solve by manually onboarding 20 salons before launch
2. **Salons bypassing platform:** Retain them with analytics + review system value
3. **Review credibility:** Must strictly enforce booking-required rule — this is the core differentiator

**How to apply:** When helping with this project, treat founder as non-technical. Recommend no-code/low-code solutions first. Keep suggestions practical and cost-conscious for a solo HK startup.
