# Solanki Co — Master Brand Website Project Reference

Use this file to onboard any new Claude chat session. Ask Claude to read this file first before starting work.

---

## Brand System — "Aman Aesthetic"

Solanki.co follows the same luxury hospitality aesthetic as nitinsolanki.com, inspired by Aman Resorts — calm, elevated, minimal, quiet luxury. See `Aman_Brand_Guide.docx` for the full reference.

### Colors
- Background: `#F3EEE7` (warm linen)
- Card/section backgrounds: `#E8DFD3` (light taupe)
- Accent/borders: `#D4C4B0` (muted gold taupe)
- Primary text: `#313131` (soft black)
- Medium text: `rgb(120, 110, 100)` (warm gray — used for secondary text)
- White: `#FFFFFF` (cards, overlays)

### Fonts
- **Cormorant Garamond** — serif, used for headings, display text, brand names (weight 300-400)
- **Inter** — sans-serif, used for body text, labels, navigation, eyebrows (weight 300-600)
- Loaded via Google Fonts

### Design Principles
- Generous whitespace, no clutter
- Subtle fade-in animations on scroll (IntersectionObserver)
- Thin accent lines as dividers (1px, taupe)
- Eyebrow labels: Inter, 0.68rem, weight 500, letter-spacing 2.5px, uppercase, warm gray
- Mobile-first responsive (768px tablet, 1100px desktop)
- No emojis, no bright colors, no gradients
- SVG icons: thin line style, stroke #D4C4B0, stroke-width 1.2

---

## Site Architecture

### Purpose
Solanki.co is the **master umbrella brand** for the Solanki ecosystem. It houses and connects six sub-brands under one unified identity. It is separate from nitinsolanki.com (personal brand) but shares the same aesthetic.

### Pages
| File | Purpose | Status |
|------|---------|--------|
| `index.html` | Homepage — hero, philosophy, ecosystem tiles, Mora Sol story, footer | Complete (v1) |
| Sub-brand pages | Individual pages for each pillar | Planned |

### Master Logo — D1 Lockup
The Solanki Co master logo uses the "D1" lockup across all pages:
- **Header:** Taupe circle (36px) with serif S + 1px accent divider + "SOLANKI" in Cormorant Garamond 300 with small "CO" in Inter 300 underneath
- **Hero (index + solanki-co):** Large taupe circle (80px) with serif S above "SOLANKI" display text + "CO" underneath
- **Footer:** Smaller version of header lockup (32px circle)
- CSS classes: `.logo-mark`, `.logo-divider`, `.logo-text`, `.logo-name`, `.logo-co` (header); `.hero-mark`, `.hero-co` (hero); `.footer-mark`, `.footer-divider`, `.footer-text`, `.footer-name`, `.footer-co` (footer)

### Navigation (all pages)
Desktop (1100px+): Foundation · Capital · Advisory · Digital · Studios · Travel + CONNECT button
Mobile/Tablet: Hamburger menu + "MENU" label (left) — D1 lockup (center) — CONNECT (right)

### Homepage Structure
1. **Hero** (100vh) — Eyebrow pillars · S circle mark · "SOLANKI" large display · "CO" · Subtitle · Scroll indicator
2. **Philosophy** — "Built to Last. Designed to Matter." centered text block
3. **Ecosystem** — "A Curated Ecosystem." + 6 venture tiles in 3x2 grid
4. **Mora Sol Story** — "A Name Rooted in Family" — brand etymology on taupe background
5. **Footer** — D1 lockup + © 2026 Solanki Co + Privacy/Terms/Connect links

---

## The Six Pillars (Sub-Brands)

### 1. IMPACT — The Solanki Foundation
- Purpose: Supporting South Asian women impacted by relationship trauma and family violence
- Mission: "The Solanki Foundation supports South Asian women impacted by relationship trauma and family violence by expanding access to culturally competent mental health resources, community support, and pathways to safety and stability."
- Role: The impact arm — partner-driven, not a direct service provider
- Description: "Supporting South Asian women impacted by relationship trauma through culturally competent mental health resources, community, and pathways to stability."
- Three program pillars:
  1. **Support** — Peer support circles + community partners (safe, culturally familiar spaces)
  2. **Access** — Subsidized therapy, counseling navigation, culturally competent professionals
  3. **Stability** — Emergency support pathways through partner orgs (safety resources, legal aid referrals, transitional support)
- Key positioning: Partners with experts and existing organizations; does not run clinical interventions directly

### 2. CAPITAL — Mora Sol Capital
- Purpose: Structured funding + real estate under one capital platform
- Product lines: Mora Sol Funding (lending, structured finance) + Mora Sol Real Estate (GP/JV, syndication)
- Who it serves: Investors, borrowers, operators, partners
- Description: "Structured funding and real estate. Downside-first capital deployed through disciplined partnerships."
- Revenue: Origination fees, interest spread, servicing fees, management fees, promote
- Passive potential: HIGH — source deals, partner with servicers/operators
- Note: Real Estate launches as a second product line when a deal is in motion

### 3. ADVISORY — Mora Sol Advisory
- Purpose: Selective strategy and operating counsel
- Who it serves: Founders, PE-backed operators, leadership teams at inflection points
- Description: "Selective strategy and operating counsel for founders and leadership teams navigating inflection points."
- Engagement types: Advisory (retainers, board-style) + Consulting (projects, sprints, execution)
- Revenue: Retainers, project fees, equity/advisory shares where appropriate
- Passive potential: LOW (most active arm) — keep selective and premium
- Note: Authentic to founder's consulting background; positioned as selective, not available-for-hire

### 4. DIGITAL — Mora Sol Digital
- Purpose: Productized systems, automation, and revenue infrastructure
- Includes: AI agents, CRM/RevOps, analytics, automation
- Description: "AI automation, CRM, and revenue infrastructure. Productized systems that scale without your time."
- Revenue: Productized deployments, monthly retainers, licensing, partner referral fees
- Passive potential: MEDIUM-HIGH if productized; LOW if custom consulting
- Partnership: Implementation partners deploy; you build the playbooks
- Note: Marketing lives under Studios or as a future separate arm — Digital is pure systems

### 5. STUDIOS — Mora Sol Studios
- Purpose: Editorial storytelling, branded content, and community
- Includes: Podcast/interview series, short-form series, event content, brand films, founder stories
- Description: "Editorial storytelling, branded content, and community. The creative engine and voice of the platform."
- Revenue: Sponsorships, content partnerships, audience monetization, branded content for clients
- Passive potential: MEDIUM — partner with producers/editors; founder as creative director, not daily talent
- Partnership: Editors, producers, videographers handle execution
- Note: Also serves as brand-building engine that feeds deal flow to other pillars

### 6. TRAVEL — Solanki Private Travel
- Purpose: Tailor-made travel and experiences, founder-led curation
- Who it serves: HNW network, discerning travelers
- Description: "Tailor-made travel and experiences. Founder-led curation built on taste, discretion, and trusted partnerships."
- Branded under Solanki (not Mora Sol) — travel is personal, taste-led, and founder-driven
- Revenue: Commissions from hotel/experience partners, booking fees, potential membership fees
- Passive potential: HIGH — once partner relationships are established, fulfillment is partner-handled
- Partnership: Hotel partners, experience providers, DMCs handle execution
- Inspiration: volartravels.com / Virtuoso model but elevated
- Note: Public positioning is client-first; partner perks strategy is internal only

---

## Future Additions (Planned/Maybe)

- **Mora Sol Partners** — JV structure for real estate deals, business rollups, special situations. Possibly part of Capital.
- **Solanki Community / Membership** — Invite-only dinners, founder/operator salons, investor meetups. Future consideration.

---

## Relationship to Other Properties

| Property | Relationship |
|----------|-------------|
| nitinsolanki.com | Separate personal brand site. Same aesthetic, not linked from Solanki.co tiles. |
| Aman Brand Guide | Source design document for the entire visual system |
| Mora Sol family | All "Mora Sol" sub-brands are business entities under the Solanki umbrella |
| The Solanki Foundation | The philanthropic entity — not Mora Sol branded |

---

## Key Decisions Made

1. **"Solanki Private Travel" over "Mora Sol Concierge"** — Travel is founder-led and taste-driven; Solanki name sells trust better than a sub-brand
2. **nitinsolanki.com not on tiles** — Kept separate; Solanki.co only features the ecosystem entities
3. **Digital = systems only** — "Mora Sol Digital" is AI, CRM, RevOps; marketing lives under Studios or as a future separate arm
4. **Single brand for Advisory** — "Mora Sol Advisory" covers both retainer advisory and project consulting
5. **Brand aesthetic is non-negotiable** — Every element follows the Aman/quiet luxury standard
6. **"MORA SOL" presentation** — Two words, no interpuncts or hyphens. Premium feel comes from restraint and typography.
7. **"Solanki Co" as the umbrella name** — Domain is solanki.co, "Co" differentiates the platform from the personal brand (nitinsolanki.com). Instagram: @solanki.co, X: @solanki
8. **D1 Lockup as master logo** — Taupe circle containing serif S + thin accent divider + SOLANKI wordmark with small CO underneath. Used in header, hero, and footer across all pages.

---

## Deployment Notes

- Website is static HTML/CSS/JS — no build step needed
- Single-file architecture (all CSS and JS inline in index.html)
- Google Fonts loaded externally (Cormorant Garamond + Inter)
- All pages should be uploaded to hosting whenever HTML changes are made

---

## Brand Name Etymology

**Mora Sol** — Derived from **Morarbhai Solanki**, Nitin's grandfather. The name honors a man whose quiet strength, conviction, and generosity shaped the family's values. In Spanish, "mora sol" translates to "dwelling sun" — warmth, resilience, and light. This dual meaning (family tribute + Spanish translation) is intentional and central to the brand story. The family origin is the primary story; the Spanish meaning is a beautiful secondary layer.

**Solanki Co** — The master brand platform. "Co" distinguishes the entity from the personal brand (nitinsolanki.com). The domain solanki.co IS the name. Architecture: Nitin Solanki (person) vs Solanki Co (platform).

**Presentation:** "MORA SOL" — two words, generous letter-spacing, Cormorant Garamond Light. No interpuncts, no hyphens. The premium feel comes from restraint and typography, not decoration.

**D1 Lockup:** The master logo features a taupe (#E8DFD3) circle containing a serif S (Cormorant Garamond 300) + thin accent divider line (#D4C4B0) + "SOLANKI" in Cormorant Garamond 300 with "CO" in Inter 300 positioned underneath. The S mark, divider, and wordmark are arranged horizontally in header/footer. In hero context, the S circle is centered above the display wordmark.
