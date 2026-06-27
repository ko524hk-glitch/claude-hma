---
name: hk-film-app
description: Hong Kong movie location tourism app targeting mainland China visitors — gamified exploration with check-ins and community features
metadata: 
  node_type: memory
  type: project
  originSessionId: 5692d64f-148f-458d-ae32-b9ff780cce63
---

# HK Film Scene Tourism App (香港電影場景旅遊 App)

**Target users:** Mainland Chinese tourists (primary)
**Core concept:** Let tourists explore famous Hong Kong movie filming locations with gamified experiences
**Long-term goal:** Not just a travel tool — a permanent HK film culture community platform

## Two Core Games

### Game 1: Scene Guessing (場景猜猜猜) 🎬
- Show real HK location photos, guess which movie scene it's from
- Timer, scoring, hints system — playable without visiting
- **Strengths:** Low barrier, educational, social sharing potential (WeChat, 小紅書)
- **Risks:** Young mainland tourists may not know HK films; copyright issues with movie stills; content needs constant refresh
- **Role:** Low-barrier entry feature. Standalone retention: medium.

### Game 2: Daily Check-in Tasks (每日打卡任務) 📸
- Daily missions — visit filming locations, take photos, earn real rewards (coupons, tickets)
- GPS + AI image verification to prevent cheating
- **Strengths:** Matches mainland "打卡" culture perfectly; merchant partnership model; high daily retention
- **Risks:** Tourists only stay 3–5 days (limits daily task value); GPS+AI dev cost is high; virtual badges alone won't retain mainland users
- **Role:** Core feature. Commercial potential: very high.

### Synergy
猜猜猜 = low-barrier entry → 打卡任務 = core experience. Forms "learn → explore" loop.

## Long-term Retention Features (by priority)
- ⭐⭐⭐ Personal film memory photo album (auto-journal from check-ins — emotional lock-in)
- ⭐⭐⭐ Movie collection library + unlock progression system
- ⭐⭐⭐ Points ecosystem with 6-month expiry + membership tiers
- ⭐⭐ Daily film knowledge push notifications + daily quiz
- ⭐⭐ Mainland community + leaderboards
- ⭐⭐ "Next HK visit" wishlist (repeat visit incentive)
- ⭐⭐ Friend challenge mode (playable after leaving HK)
- ⭐ Monthly new scenes + limited-time events tied to HK film festival

## Mainland-Specific Requirements
- WeChat / Weibo one-tap sharing (no integration = no viral spread)
- Alipay / WeChat Pay rewards (real cash value only motivates mainland users)
- Simplified Chinese UI with mainland-familiar UX patterns
- Featured films mainland users know: 《無間道》《花樣年華》《英雄本色》《賭神》
- 小紅書 KOL partnerships for marketing
- "Film beginner mode" for users unfamiliar with HK cinema

## 3-Phase User Journey
- **Pre-trip (before arriving HK):** Route planning, scene preview, guessing game practice
- **During trip (in HK):** Daily check-in tasks, points, scene exploration ← main gameplay phase
- **Post-trip (back in mainland):** Memory album, social sharing, friend challenges, next-visit wishlist ← most travel apps abandon this phase entirely

## Core Challenges
1. **Users delete app after trip** — must solve with post-trip features
2. **Copyright for movie stills** — licensing costs, needs early resolution
3. **AI verification cost** — needed to prevent check-in cheating
4. **Business model** — free app + rewards has upfront cost; needs user base before merchants will partner

## Tech Requirements (for development)
- GPS location + AI image recognition (check-in verification)
- WeChat / Weibo Share API
- Alipay / WeChat Pay points redemption
- Cloud photo storage (memory album)
- Push notification system (daily tasks, knowledge push)
- Interactive film scene map

**How to apply:** Treat founder as non-technical. Recommend no-code/low-code first. Mainland China market integration (WeChat, Alipay, 小紅書) is a hard requirement, not optional.
