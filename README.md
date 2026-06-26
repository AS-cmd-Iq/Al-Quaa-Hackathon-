# مورد القاع — Mawred Al Quaa

### A community resource-sharing platform for Al Quaa residents

![Challenge](https://img.shields.io/badge/Challenge-5%20—%20Solve%20a%20real%20community%20problem-1B4F35?style=for-the-badge)
![Status](https://img.shields.io/badge/Status-Live%20%26%20Working-25D366?style=for-the-badge)
![Language](https://img.shields.io/badge/Language-Arabic%20%2B%20English-blue?style=for-the-badge)

---

## Live Demo

**Open `index.html` in any browser — no setup, no install, works immediately.**

Or view online: https://github.com/AS-cmd-lq/Al-Quaa-Hackathon-

---

## 1. The Challenge

**Challenge 5 — Free choice: solve a real problem in your community**

### The problem

Al Quaa is a dispersed rural community in Al Ain where residents, farmers, and small business owners regularly need shared resources: water tankers, generators, 4×4 vehicles, farm tools, event tents, temporary workers, and cold transport.

Today this exchange happens entirely through personal contacts and phone calls. **If you don't know the right person, you waste time, overpay, or go without.**

The problem is not that resources don't exist — they do. The problem is that they are **invisible**. A farmer 4 km away may have an idle generator. A household may have a water tanker available this afternoon. Nobody knows.

This is a **daily** friction affecting every farm owner, every household, every small entrepreneur in Al Quaa.

---

## 2. Who It's For

| Group | Their situation |
|-------|----------------|
| **Farm owners** | Need seasonal equipment but can't justify owning it year-round |
| **Households** | Need occasional generators, vehicles, or event supplies |
| **Small entrepreneurs** | Want to start a business but can't afford upfront equipment costs |
| **Residents with idle assets** | Own equipment sitting unused that could earn them income |

**Location:** Al Quaa, Al Ain, Abu Dhabi, UAE
**Estimated residents:** 500–2,000 households
**Language:** Arabic-first, fully bilingual Arabic/English

---

## 3. The Solution

**Mawred Al Quaa** (مورد القاع) makes hidden local resources visible and accessible.

Residents can:
- **Request** a resource — with timing, budget, and delivery preference
- **List** a resource they can offer — equipment, vehicles, skills
- **Browse** what is available nearby, filtered by category
- **Respond to urgent requests** — same-day needs
- **Connect instantly** via WhatsApp with a pre-written Arabic or English message

### What makes it unique

**Trust circles** — listings can be shared with:
- Family and neighbours only
- Verified Al Quaa residents
- Public

This mirrors how the community actually works. People in Al Quaa already lend and share — but only within circles of trust. The app extends that trust digitally.

**Micro-business suggestions** — when a resident lists what they own, the app suggests a small business they could start. A pickup truck and free evenings → evening local delivery service. This connects to Challenge 1 (entrepreneurship) as a bonus.

### Measurable impact claims

| Claim | Before | After |
|-------|--------|-------|
| Time to find a water tanker | 30–90 min (phone calls) | Under 10 min via app |
| Price transparency | None — you pay what you're told | Visible market rate before contact |
| Earning from idle assets | Near zero formalised | Any verified resident lists in 2 minutes |
| First contact with provider | Requires knowing someone personally | Zero prior relationship needed |

---

## 4. Feasibility

| Factor | Assessment |
|--------|------------|
| **Device access** | Smartphones are universal in Al Quaa. Runs in any mobile browser — no download needed |
| **Connectivity** | Mobile data covers Al Quaa. No heavy internet features required |
| **Contact method** | All contact goes through WhatsApp — no new habit needed |
| **Language** | Fully bilingual Arabic/English, Arabic-first, full RTL layout |
| **Onboarding** | Phone number only, SMS verified. No email or password |
| **Cost to run** | Single HTML file — free hosting on GitHub Pages, Netlify, or any server |

### Deployment path

**Month 1** — Deploy to a public URL. Share with 20–30 known Al Quaa residents via WhatsApp. Seed first listings manually.

**Month 2–3** — Add SMS verification (Unifonic UAE, ~0.05 AED/SMS). Add database (Supabase free tier). Run first real transactions.

**Month 6+** — Optional 2–3% fee on confirmed rentals. Partnership with Al Ain Municipality as a funded community service.

### What it does NOT require
- No app store approval
- No proprietary hardware
- No AI inference costs
- No complex infrastructure

---

## 5. Scalability

The entire platform is **one HTML file**. Replication to another community takes under one hour.

**Other UAE communities with identical needs:**
Mahadha, Hatta, Khatam Al Shaala, Remah, Sweihan, Sila, Al Mirfa

**The platform scales two ways:**
1. More users in Al Quaa — network effect; more listings = more value
2. More communities — the codebase is community-agnostic; a new community is a configuration change, not a rebuild

---

## 6. Evidence and Testable Claims

### How to verify right now

| Claim | Test |
|-------|------|
| App runs with zero setup | Open `index.html` in any browser. It works immediately. |
| Bilingual toggle works | Click the language button. Every label, placeholder, and layout switches Arabic ↔ English with RTL/LTR flipping. |
| WhatsApp integration works | Tap any WhatsApp button. Opens WhatsApp with a pre-written message in the correct language. |
| Request → match flow works | Go to "I need something" → fill form → tap "Find matches" → 3 matched providers appear with contact options. |
| Micro-business tip updates | Go to "I can offer" → change resource type → tip updates to match what you selected. |
| Trust circles work | Select different visibility options — Family only / Verified residents / Public. |
| Category filter works | Browse page → tap any category pill → listings filter instantly. |
| Live search works | Browse page → type in search box → results update in real time. |

### Community validation basis

- Informal resource sharing via phone calls is observable behaviour in Al Quaa and similar UAE rural communities
- WhatsApp community groups for local requests already exist — evidence of demand without a structured solution
- No existing platform serves this specific rural community need in the UAE

### Known limitations (honest)

- SMS verification is mocked in the demo (any 4 digits work)
- Data is sample data — a live version needs a backend database
- Ratings are displayed but not yet writable
- Distance is manually entered, not GPS-calculated

Each has a clear, low-cost solution path described in Section 4.

---

## 7. How to Run It

### Zero setup — open directly

1. Download `index.html`
2. Open it in Chrome, Edge, Safari, or Firefox
3. Full app runs immediately — no server, no install, no dependencies

### Deploy live in 2 minutes

1. Go to [netlify.com/drop](https://netlify.com/drop)
2. Drag `index.html` onto the page
3. Get a public URL instantly

### Tools used

| Tool | Purpose |
|------|---------|
| HTML5 / CSS3 / Vanilla JavaScript | Full application in one file |
| IBM Plex Sans Arabic | Bilingual Arabic/English typeface |
| Tabler Icons (CDN) | Icon library |
| WhatsApp deep link (`wa.me/`) | Contact routing |
| Google Fonts CDN | Font delivery |

**No build step. No npm. No framework. No dependencies to install.**

---

## 8. App Screens

The app includes these fully working screens:

1. **Splash** — Arabic/English with desert dune and star illustration
2. **Register** — name, phone, area, user type
3. **Verify OTP** — SMS code confirmation
4. **Home** — urgent banner, 4 action buttons, category filter, live listings
5. **Browse** — searchable, filterable resource listings
6. **Request** — resource type, timing, budget, trust circle selector
7. **Matches** — 3 ranked providers with WhatsApp and confirm buttons
8. **Confirmed** — booking summary with WhatsApp contact
9. **Offer** — list a resource with micro-business suggestion
10. **Urgent** — same-day requests needing help
11. **Profile** — stats, listings history, settings
12. **Notifications** — activity feed

---

## One-line pitch

> Mawred Al Quaa helps residents and farm owners share, rent, and request local resources — so the community can use what it already has before buying or searching outside.

---

**Hackathon:** Al Quaa Hackathon — Tatweer, June 2025
**Challenge:** Challenge 5 — Solve a real problem in your community
**Team:** AS-cmd-lq
