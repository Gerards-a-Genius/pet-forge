# Pet Forge — Two-App Product Design

Two interlocking apps built around the cozy chibi pet / build-your-own-pet weekend.
One app makes people fall in love; the other sells, ships, and scales the experience.

---

## The shared artifact

The thing that ties both apps and both days together is **the Pet Config** — a small
JSON/script describing the pet's *species, accessories, and behaviors*. This is the
"source code of a life."

- **App 1 (Mochi):** you author the config and live with the pet.
- **App 2 (Forge):** the same config becomes a physical thing, and the transaction happens.

One artifact, two surfaces. This is the moat — nobody else has an app where the pet you
code on your phone is the same pet you bedazzle at a workshop.

---

## App 1 — **Mochi** (the pet app · consumer / everyday)

**One-liner:** Your chibi pet lives on your phone, reacts to your day, and you make it
*yours* by coding its accessories and behaviors.

**Audience:** creative people, couples, kids-adjacent, the "cozy tech / digital pets"
crowd — all the Starboy energy, but participatory instead of just buyable.

**Core loop:** Adopt a pre-programmed pet → **code its fun stuff** (accessories + behaviors)
→ watch it react & live ambiently → **share it** in the herd → **port it to hardware.**

### Features
1. **Pet studio** — the animated chibi as hero (the generated art set).
2. **Personality / block editor** — the Day-1 "code the fun stuff" loop (our v2 prototype,
   productionized): accessories, behaviors (`when X → do Y`), reactions.
3. **Ambient care** — the pet reacts to real signals: time of day, weather, light,
   movement (via phone sensors). "Happy in the sun," "shivers in the cold." Straight from
   the Starboy sensor playbook.
4. **Herd** — a shared community gallery; pets **borrow accessories & behaviors** when they
   meet (offline device-to-device / Bluetooth contact-store).
5. **Accessory & behavior marketplace** — limited seasonal drops + a creator channel. This
   is the recurring-revenue engine and the flywheel.
6. **Port-to-hardware** — export the config as a QR / flash that loads onto the physical
   device. The bridge to Forge.
7. **Persistent memory** — the pet remembers your interactions, your name, your habits; it
   *grows*. Agent-native: the pet is an ambient actor with a few rules you set; progressive
   autonomy (tap a rule on/off, the pet runs it in the background).

### Monetization
Free pet + paid accessory drops / seasonal packs / premium skins. Marketplace takes a cut
on creator sales.

---

## App 2 — **Forge** (the workshop conductor · event + business)

**One-liner:** The software that runs a build-night — a guided two-day build for
participants, and a revenue console for the host.

**Audience:** (participants) workshop attendees; (host) Gerard today, other hosts/creators
later.

**Core loop — participant:** Register/kit → **Day 1** personality coding → **Day 2**
assembly + bedazzle → **flash your pet** → leave with a working pet + your config.

**Core loop — host:** Create cohort → set pricing → ship/order kits → prep checklist →
run the two days → collect revenue & photos.

### Features
1. **Participant build guide** — animated step-by-step (Day 1 code / Day 2 assemble →
   decorate), the parts checklist (BOM), bench tips, and a **coach agent** that checks you
   off. Agent-native supervision, verification-first.
2. **Day-2 assembly view** — the "sandwich" internals (board / screen / battery / SD),
   shell snap-in, and the **decoration planner** (bedazzle, paint, decals).
3. **Cohort gallery** — see everyone's pets in the room, vote, share. (The herd shop
   becomes a real social moment.)
4. **Host console** — cohort creation, ticketing & pricing (the two-tier model), kit BOM +
   Amazon ordering links, prep checklist (pre-flash SDs, bench-test), facilitator timeline,
   revenue dashboard.
5. **Kit manifest + "port my pet"** — flash the config from Mochi onto the device at the end.
6. **Creator publishing** — publish your own pet design or accessory pack to the marketplace.
   The flywheel: workshop → creator → marketplace → more builders.

### Monetization
The cohort ticket. The host console as SaaS for other hosts. Marketplace commissions.

---

## Why two (not one)

- **Mochi** makes kids & couples fall in love, is the recurring revenue, and is the
  emotional moat (a pet you coded *and* decorated that remembers you).
- **Forge** is the machine that sells, ships, and de-risks the hardware — it turns a
  one-off weekend into a repeatable business and lets it scale to other hosts.

One without the other = just a toy, or just an event. Together = a brand.

---

## Visual identity

- **The pets:** the chibi set — cozy, warm cream / blush / mint / honey, huge glossy eyes
  (the generated designs).
- **Mochi:** soft, cozy, tactile. Warm off-white canvas, pillowy rounded frames, the chibi
  as hero, gentle ambient micro-animations.
- **Forge:** the builder/experience brand. Editorial/experimental (Mobbin direction:
  oversized type, off-white, asymmetric splits, pixel/generative details, floating media
  tiles) for marketing + landing; the in-app coach stays warm & clear.

---

## Build order (iterate, don't boil the ocean)

1. **Mochi prototype v1** — we're ~80% there with the editor; add ambient reactions +
   accessory drops on top. Make it feel alive.
2. **Forge participant mode** — Day 1/Day 2 guided build + kit manifest.
3. **Wire the pet-config transfer** between both apps (the shared artifact).
4. **Forge host console** — pricing, BOM, revenue dashboard — *after* the pilot validates.

---

## Open questions for you (pick, I'll run with the answers)
- **Name:** does "Mochi" (pet app) + "Forge" (workshop) hit, or do you want different names?
- **Mochi primary platform:** phone (iOS/Android) or since we're already web — a PWA you
  open on your phone (fastest to ship, no app store) until you want native?
- **What's the event called** — "Build Night," "Pet Forge Workshop," "Cozy Build," ...?
