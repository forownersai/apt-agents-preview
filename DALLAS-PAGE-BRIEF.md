# Dallas Landing Page — design brief (Claude's design, 2026-08-02)

**Goal:** one job — get the visitor into the signup form. Not calls (agent coverage is thin until the AI receptionist exists), not browsing.
**Audience:** 25–35 working professionals, good credit/income, moving in DFW. 95% arrive on a phone from an Instagram deal post.
**Competitive frame:** Smart City wins on scale (300 agents, 9 cities, 10k+ reviews). We cannot out-scale them. We win on **money back + the move itself + curated judgment**. Never imitate their layout; beat them on a different axis.

## The strategic bet
Every locator says "free apartment finding." That's table stakes and nobody believes the differentiation. Our page should make three claims a competitor **cannot** copy cheaply:
1. **More cash than anyone** — up to $250 (industry tops out at $200)
2. **We handle the actual move** — mover quotes, genuinely negotiated discounts (not affiliate links that mark prices UP), booking help
3. **A curated shortlist, priced today** — 3 picks with reasons, not a 40-property data dump

Claim 3 is the sleeper. Everyone else hands over a list. Showing *what our recommendations look like* on the landing page proves the product before they sign up.

## Section order (mobile is the design; desktop adapts)
1. **Hero** — headline "Save more on your dream Dallas apartment." Sub: free service, up to $250 back, we handle the move. **Inline 3-field form** (first name, email, phone) + button "Get My Free Shortlist". Micro-trust line under the button. Award + 23 years + Google rating strip.
   _Why: the first screenful is the entire battle on mobile. Form is IN the hero — no scroll required to convert. 3 fields only; deeper qualification happens after submit (the old form asked 6–18 questions BEFORE contact info — that's the leak we're fixing)._
2. **"What you get" value stack** — the offer laid out as a stack with honest market values, totaling ~$900, priced at $0, with the catch explained ("properties pay us from their marketing budget"). _Brunson stack, executed honestly; the free reveal is the price-drop moment._
3. **The Move** — the differentiator section. Up to $250 · mover quotes from DFW's best · real negotiated discounts, not affiliate links · we help you book. _This is the wedge nobody else has._
4. **What our recommendations actually look like** — a live-feeling sample: 1 Star card (photo, reason-why, net-effective price, "checked today"), 1 under-budget card, 1 wildcard. Menu-engineered, 3 items max. _Show, don't tell. Proves curation._
5. **How it works** — 3 steps, tight. Tell us what you want → we send your shortlist (same day) → tour, lease, get paid.
6. **Proof** — Google reviews (real), Consumer's Choice 2026, 23 years, "200,000+ DFW renters helped" (helped, not "customers" — accuracy).
7. **Objections** — short: Is it really free? What's the catch? Do I have to tour with an agent? Can I still use it if I already started looking?
8. **Final CTA** — form repeat, same 3 fields.

## Hard rules
- **Mobile-first**: design and verify at 390px BEFORE desktop.
- **"Up to $250"** everywhere — never a bare $250.
- Never claim approval, never quote a hard reward amount, never promise a specific unit.
- No phone-number pressure (small link only, not a primary CTA).
- Brand system from how-it-works.html/rewards.html: navy #0F1338, lavender #9DAAF2, green #AECD81, DM Serif Display headings + DM Sans body, pill buttons #0d6efd.
- Anti-generic: layered color-tinted shadows (no flat shadow-md), no default Tailwind blue/indigo as brand color, no `transition-all`, animate transform/opacity only, hover + focus-visible + active on every interactive element, gradient overlay + mix-blend treatment on photos, consistent spacing scale.
- Sample recommendation cards use plausible placeholder data clearly marked as an example — never present invented listings as live inventory.
