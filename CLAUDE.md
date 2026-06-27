# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Response Style

- Reply in Cantonese (廣東話)
- Keep responses short and direct — give the answer, skip lengthy explanation unless asked
- Use simple language, no jargon, explain in a way a non-technical person understands
- All times use UTC+8 (Hong Kong time)

---

## About the Founder

Non-technical solo founder based in Hong Kong. No coding background. Building two apps simultaneously. Prefers no-code/low-code solutions. Always recommend the simplest, most cost-effective approach first.

---

## Project 1: HK Salon Booking App (香港髮廊預約平台)

**Goal:** Salon discovery and booking platform for Hong Kong residents. Fills a gap Google Maps can't — hair-specific filters, stylist profiles (trackable across salons), before/after photos, verified reviews, transparent pricing, in-app booking.

**Revenue model:** Booking commission via Stripe Connect (10% per booking).

**Target users:** Hong Kong residents looking for hair salons.

**Languages:** Traditional Chinese, Simplified Chinese, English.

**Search:** By Hong Kong district (Causeway Bay, Mong Kok, Central, etc.)

**Rating system:** Overall star (1–5) + category scores (hygiene, skill, value, attitude). Only users who booked via platform can leave reviews — this is the core differentiator.

**Payments:** Credit card, FPS, Alipay HK via Stripe.

**Platform:** Web first → iOS later (after web version matures).

### Tech Stack
- **App/Frontend:** Bubble.io (~HK$155/mo)
- **Database & Auth:** Supabase (free tier — note: pauses after 7 days idle)
- **Payments:** Stripe Connect (3.4% + HK$2.35 per transaction)
- **Maps:** Google Maps API (~8,000 free calls/mo free)
- **Email:** Resend (3,000 free/mo)
- **Design:** Figma (free)
- **Marketing:** Instagram + 小紅書 (free)

### Monthly Costs
- MVP: ~HK$65/mo
- Growth: ~HK$650–1,600/mo
- Net per HK$500 booking at 10% commission: ~HK$30.65 after Stripe fees

### 4-Phase Roadmap
1. **Weeks 1–4:** Validate market — visit 10 salons, interview 15 users
2. **Weeks 5–8:** Design — Figma clickable prototype, user testing
3. **Months 3–6:** Build — Bubble.io web app, connect Stripe + Google Maps
4. **Months 6–7:** Launch — onboard 20 salons in 2 districts manually, social media, then iOS

### Top 3 Risks
1. **Chicken-and-egg:** Solve by manually onboarding 20 salons before launch
2. **Salons bypassing platform:** Retain them with analytics + review system value
3. **Review credibility:** Must strictly enforce booking-required rule

---

## Project 2: HK Film Location Tourism App (香港電影場景旅遊 App)

**Goal:** Let mainland Chinese tourists explore famous Hong Kong movie filming locations with gamified experiences. Long-term vision: a permanent HK film culture community platform.

**Target users:** Mainland Chinese tourists (primary).

### Two Core Features

**Game 1 — Scene Guessing (場景猜猜猜):** Show real HK location photos, guess which movie scene it's from. Timer, scoring, hints. Playable without visiting HK. Low-barrier entry feature.

**Game 2 — Daily Check-in Tasks (每日打卡任務):** Daily missions — visit filming locations, take photos, earn real rewards (coupons, tickets). GPS + AI image verification to prevent cheating. Core commercial feature.

Synergy: 猜猜猜 = low-barrier entry → 打卡任務 = core experience. "Learn → explore" loop.

### Long-term Retention (by priority)
- Personal film memory photo album (auto-journal from check-ins)
- Movie collection library + unlock progression
- Points ecosystem with 6-month expiry + membership tiers
- Daily film knowledge push + daily quiz
- Mainland community + leaderboards
- "Next HK visit" wishlist

### Mainland-Specific Hard Requirements
- WeChat / Weibo one-tap sharing (no integration = no viral spread)
- Alipay / WeChat Pay rewards (real cash value only motivates mainland users)
- Simplified Chinese UI with mainland-familiar UX patterns
- Featured films: 《無間道》《花樣年華》《英雄本色》《賭神》
- 小紅書 KOL partnerships for marketing
- "Film beginner mode" for users unfamiliar with HK cinema

### 3-Phase User Journey
- **Pre-trip:** Route planning, scene preview, guessing game practice
- **During trip (main phase):** Daily check-in tasks, points, scene exploration
- **Post-trip:** Memory album, social sharing, friend challenges, next-visit wishlist

### Core Challenges
1. Users delete app after trip — must solve with post-trip features
2. Copyright for movie stills — licensing cost, resolve early
3. AI verification cost for check-in anti-cheat
4. Business model — free app + rewards has upfront cost; needs user base before merchants partner

### Tech Requirements
- GPS location + AI image recognition (check-in verification)
- WeChat / Weibo Share API
- Alipay / WeChat Pay points redemption
- Cloud photo storage (memory album)
- Push notification system
- Interactive film scene map

---

## Project Structure

_To be filled in once scaffolded._

## Commands

_Add build, run, and test commands here once set up._

## Architecture

_Document high-level architecture here once it takes shape._

---

## Current Status (as of 2026-06-27)

### Situation
Founder has surgery from **5 July – 12 July 2026**. Goal is to have the Salon Booking App core flow stable before surgery, then resume on a **laptop** after recovery.

### Salon App — Pre-surgery Build Plan (27 Jun – 4 Jul)
| Date | Task |
|------|------|
| 27–28 Jun | Bubble.io: build homepage, search page, salon detail page |
| 29–30 Jun | Supabase: set up tables (salons, services, bookings, users, reviews) |
| 1 Jul | Connect Google Maps API, district-based search working |
| 2 Jul | Stripe Connect basic integration (payment flow runnable) |
| 3 Jul | End-to-end test: search → detail → booking → payment |
| 4 Jul | Backup everything, document what's unfinished |

**Not needed before surgery:** review system, iOS, multilingual toggle, marketing.

### During Surgery Recovery (5–12 Jul)
- Use **claude.ai on mobile** for light planning and decisions — no laptop needed
- Do NOT rush to code during recovery

### After Recovery — Resume on Laptop
- `git clone` or `git pull` this repo on the laptop
- Open folder in Claude Code — it will read this CLAUDE.md automatically
- No retraining needed, all context is here

### What's NOT started yet
- Bubble.io pages (not built)
- Supabase tables (not set up)
- Stripe Connect (not connected)
- Google Maps API (not connected)
- Film App (on hold, Salon App is priority)
