<div align="center">

# مورد القاع
## Mawred Al Quaa

**A community resource-sharing platform for Al Quaa, Al Ain**

[![Challenge](https://img.shields.io/badge/Challenge_5-Solve_a_Real_Community_Problem-1B4F35?style=for-the-badge&logo=target)](https://github.com/AS-cmd-lq/Al-Quaa-Hackathon-)
[![Status](https://img.shields.io/badge/Status-Live_%26_Working-25D366?style=for-the-badge&logo=checkmarx)](https://github.com/AS-cmd-lq/Al-Quaa-Hackathon-)
[![Language](https://img.shields.io/badge/Language-Arabic_%2B_English-185FA5?style=for-the-badge&logo=googletranslate)](https://github.com/AS-cmd-lq/Al-Quaa-Hackathon-)
[![No Install](https://img.shields.io/badge/Setup-Zero_Install_Required-F59E0B?style=for-the-badge)](https://github.com/AS-cmd-lq/Al-Quaa-Hackathon-)

---

*شارك. اطلب. وفّر. — Share. Request. Save.*

**Open `index.html` in any browser. It works immediately. No install. No server. No dependencies.**

</div>

---

## The Problem

Al Quaa is a dispersed rural community in Al Ain where residents, farmers, and small business owners regularly need shared resources: water tankers, generators, 4×4 vehicles, farm tools, event tents, temporary workers, and cold transport.

Today this exchange happens entirely through personal contacts and phone calls.

> **If you don't know the right person, you waste time, overpay, or go without.**

The problem is not that resources don't exist — they do. The problem is that they are **invisible**. A farmer 4 km away may have an idle generator available tonight. A household may have a water tanker free this afternoon. Nobody knows.

This is a **daily** friction affecting every farm owner, every household, and every small entrepreneur in Al Quaa.

---

## Who It's For

| Group | Situation |
|-------|-----------|
| 🌾 **Farm owners** | Need seasonal equipment (harvest tools, water, workers) but can't justify owning it year-round |
| 🏠 **Households** | Need occasional generators, vehicles, or event supplies but rely only on personal networks |
| 💼 **Small entrepreneurs** | Want to start a business but can't afford upfront equipment costs |
| 📦 **Residents with idle assets** | Own equipment sitting unused that could earn income |

**Location:** Al Quaa, Al Ain, Abu Dhabi, UAE  
**Estimated addressable community:** 500–2,000 households  
**Languages:** Arabic (default, full RTL) + English

---

## The Solution

**Mawred Al Quaa** (مورد القاع) makes hidden local resources visible and accessible.

### Core features

| Feature | What it does |
|---------|-------------|
| 🔴 **Request** | Ask for a resource with timing, budget, delivery preference |
| 🟢 **Offer** | List equipment, vehicles, or skills you can share or rent |
| 🔵 **Browse** | Search and filter available resources nearby |
| 🟡 **Urgent today** | See and respond to same-day urgent needs |
| 💬 **WhatsApp connect** | One tap opens WhatsApp with a pre-written message in Arabic or English |

### Two features that make it unique

**1. Trust circles**

Every listing can be scoped to:
- 👪 Family and neighbours only
- ✅ Verified Al Quaa residents
- 🌐 Public

This mirrors how the community actually works. People in Al Quaa already lend and share — but only within circles of trust. The app extends that trust, not replaces it.

**2. Micro-business suggestions**

When a resident lists what they own, the app suggests a small business they could start from it:

> *You have a pickup truck + free evenings → Evening local delivery service*  
> *You have a generator → Rent it to events and farms when idle*

This connects Mawred directly to **Challenge 1 (entrepreneurship)** as a secondary benefit.

---

## Impact — Measurable Claims

> All claims below are testable. See the [Verification section](#verification--how-to-test-every-claim) for exact test methods.

| Metric | Before Mawred | After Mawred |
|--------|---------------|--------------|
| ⏱️ Time to find a water tanker | 30–90 min (phone calls, if you know someone) | Under 10 min via app |
| 💰 Price transparency | None — you pay whatever you're told | Visible listed price before contact |
| 📲 First contact with provider | Requires knowing them personally | Zero prior relationship needed |
| 🏪 Earning from idle assets | Near zero formalised | Any verified resident lists in under 2 minutes |
| 🌍 Community resource visibility | 0% — completely informal | 100% of listed resources discoverable |

---

## Feasibility

### Why this works in Al Quaa specifically

| Factor | Assessment |
|--------|------------|
| 📱 **Device access** | Smartphones are universal in Al Quaa. App runs in any mobile browser — no download needed |
| 📶 **Connectivity** | Mobile data covers Al Quaa. Core features need minimal data |
| 💬 **Contact method** | All contact routes through WhatsApp — no new communication habit required |
| 🌐 **Language** | Arabic-first, full RTL layout, instant toggle to English |
| 🔐 **Onboarding** | Phone number only, SMS verified. No email or password |
| 💵 **Cost to run** | Single HTML file — free hosting on GitHub Pages, Netlify, or any server |

### What it does NOT require
- ❌ App store approval
- ❌ Proprietary hardware  
- ❌ AI inference costs
- ❌ Complex backend at launch
- ❌ Any technical knowledge from residents

### Deployment path

```
Month 1   →  Deploy HTML to public URL
              Share with 20–30 Al Quaa residents via WhatsApp
              Seed first listings manually

Month 2–3 →  Add SMS verification (Unifonic UAE, ~0.05 AED/SMS)
              Add database (Supabase free tier — handles thousands of listings)
              First real transactions running

Month 6+  →  Optional 2–3% fee on confirmed rentals
              Partnership with Al Ain Municipality as funded community service
              Expand to similar UAE rural communities
```

---

## Scalability

The entire platform is **one HTML file**. Replication to any community takes under one hour.

### UAE communities with identical profiles
Mahadha · Hatta · Khatam Al Shaala · Remah · Sweihan · Sila · Al Mirfa · Ghayathi

### Two growth directions

```
Direction 1 — More users in Al Quaa
More listings = more value = more users (network effect)
The platform becomes more useful every time someone new joins

Direction 2 — New communities
Change community name + area list = new deployment
Same codebase, different configuration
```

---

## Verification — How to Test Every Claim

Open `index.html` in any browser and verify each claim yourself:

| Claim | How to verify |
|-------|--------------|
| ✅ Zero setup required | Open `index.html`. It works with no server, no install |
| ✅ Arabic/English toggle | Tap the language button. Every label, placeholder, and layout switches. RTL/LTR flips correctly |
| ✅ WhatsApp integration | Tap any WhatsApp button. Opens WhatsApp with correct pre-written message in the active language |
| ✅ Full request flow | Home → "I need something" → fill form → "Find matches" → 3 providers appear with contact options |
| ✅ Match confirmation | Tap "Confirm" on a match → booking summary screen appears |
| ✅ Offer + micro-business tip | Home → "I can offer" → change resource type → tip text updates to match |
| ✅ Trust circle selector | Request or Offer form → select different visibility options |
| ✅ Category filtering | Browse page → tap any category pill → listings filter instantly |
| ✅ Live search | Browse page → type in search box → results update in real time |
| ✅ Urgent requests | Tap urgent banner or "Urgent today" button → urgent listings page |

### Known limitations (honest assessment)

| Limitation | Status | Solution path |
|-----------|--------|---------------|
| SMS verification is mocked | Demo only | Unifonic UAE API, ~0.05 AED/SMS |
| Data is sample data | Demo only | Supabase free tier database |
| Ratings displayed but not writable | Demo only | Backend API endpoint |
| Distance is manually entered | Demo only | Browser Geolocation API |

---

## How to Run It

### Option A — Open directly (recommended for judges)
```
1. Download index.html
2. Open in Chrome, Edge, Safari, or Firefox
3. Full app runs immediately
```

### Option B — Deploy live in 90 seconds
```
1. Go to netlify.com/drop
2. Drag index.html onto the page
3. Get a public URL instantly
```

### Option C — GitHub Pages (already set up)
```
Settings → Pages → Source: main branch / root
URL: https://AS-cmd-lq.github.io/Al-Quaa-Hackathon-
```

---

## Technical Stack

| Layer | Technology | Why |
|-------|-----------|-----|
| Structure | HTML5 | Single-file deployment, universal browser support |
| Styling | CSS3 with custom properties | Full RTL/LTR, responsive, no framework needed |
| Logic | Vanilla JavaScript | Zero dependencies, instant load |
| Typography | IBM Plex Sans Arabic | Best-in-class Arabic + Latin bilingual typeface |
| Icons | Tabler Icons (CDN) | 6,000+ outline icons, open source |
| Contact | WhatsApp deep link (`wa.me/`) | Universal in UAE, zero friction |

**Build steps:** None  
**Dependencies to install:** None  
**Bundle size:** 61KB — loads in under 1 second on any connection

---

## App Screens

The app contains 12 fully working screens:

```
01  Splash          Desert night sky with dunes + stars, Arabic/English
02  Register        Name, phone, area, user type selection
03  Verify OTP      SMS code confirmation
04  Home            Urgent banner, 4 actions, category filter, live listings
05  Browse          Searchable + filterable resource listings
06  Request         Resource type, timing, budget, trust circle selector
07  Matches         3 ranked providers with ratings, WhatsApp + confirm
08  Confirmed       Booking summary with direct WhatsApp contact
09  Offer           List a resource + micro-business suggestion
10  Urgent          Same-day requests needing community response
11  Profile         Stats, listing history, language settings
12  Notifications   Activity and match feed
```

---

## Community Validation

The informal sharing economy in Al Quaa is observable and documented:

- Residents already call each other to borrow equipment, hire drivers, and share water tankers — the behaviour exists, the platform is missing
- WhatsApp community groups for local requests exist informally in UAE rural communities — evidence of demand without a structured solution
- No existing platform (OLX, Dubizzle, or otherwise) provides community-specific, trust-circle-based, rural-focused resource sharing in the UAE

---

## One-Line Pitch

> **Mawred Al Quaa helps residents and farm owners share, rent, and request local resources — so the community can use what it already has before buying or searching outside.**

---

<div align="center">

**Hackathon:** Al Quaa Hackathon — Tatweer · June 2025  
**Challenge:** Challenge 5 — Solve a real problem in your community  
**Built for:** The people of Al Quaa

*The goal is not to win a hackathon. The goal is to actually deploy this.*

</div>
