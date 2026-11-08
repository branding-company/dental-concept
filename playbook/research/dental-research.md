# Dental clinic concept: research report (2026-11-08)

Status: Step 1 draft for Ilona's approval. Nothing is designed yet.

## How reliable this is
Web search only returned snippets; I did not open the live sites of Kois Center,
Dentalclinic Zürich or the Yerevan clinics, so I make no claims about their
visuals. Items marked (judgment) are my own reading, not sourced. Search could
not confirm Kois Center, "London Smile Clinic" (no site by that name found),
or any Awwwards dental Site of the Day winner. Those need a manual look.

## What the best do (sourced)
- **Invisalign:** self-guided smile simulator from a selfie, plus a chairside
  tool (Outcome Simulator Pro) that merges a photo with an iTero 3D scan. Sources
  describe it as a preview, not a guarantee. This confirms our signature feature
  is a known, proven pattern; our difference is that it runs fully in the browser,
  covers whitening, veneers and alignment, and ends in a booking.
- **London veneer clinics (Marylebone Smile Clinic, Smile Cliniq, Dental Implants
  London, Whites Dental):** dedicated treatment pages with before/after galleries;
  one states its photos are unedited, one ties a 7-year guarantee to review visits.
  Captions are often generic. Proof is shown as static photos, not interactive.
- **Straumann:** a patient brochure on the steps to a new smile and a Dentist
  Finder, and it states a listing does not vouch for quality. Brand-led, not
  clinic-led.
- **Awwwards dental candidates to review by hand:** Alley Dental (calm transitions),
  South Cliff Dental Group (3D immersive), Halo Dental (SOTD, but a dental-tech
  product, not a clinic), L'Avenir (Montreal), Gadoury (Quebec).
- **Calm-UX advice (agency blogs, low evidence):** explain the first visit,
  show the team before the visit, muted palette and real photography, one clear
  next step, speak about anxiety openly.

## How patients choose
- Türkiye dental-tourism study (one private hospital, so not general): about 94%
  cited price, 82% trust in the dentist; agencies, word of mouth and social media
  shaped the decision.
- Serbian survey of 220 patients: online reviews and website quality had the
  strongest effect on trust; price transparency also mattered.
- Clinic guides: itemised quotes, credentials, detailed plans, aftercare, and
  before/after photos are the checks people are told to make.
- (judgment) For a nervous or remote patient the order is: trust in the doctor,
  proof it works, a price they can predict, then convenience.

## Armenian market
- Directories (WhatClinic, Bookimed, Placidway) are where clinics are compared.
  Examples listed: Neva Clinics, SHAMS, Implantum, Avanta, GDC, Yerevan State
  University clinic. Prices listed are self-reported and dated 2024 to 2026.
- Sample listed prices (AMD): single implant from about 110,000 to 267,000;
  veneers about 91,000 to 655,000 per unit depending on clinic; All-on-4 from
  about 680,000. Ranges are wide and unverified, so our planner uses clearly
  marked sample numbers.
- Dental tourism: a Laing Buisson item says Armenia is trying to widen demand
  beyond diaspora workers to other Europeans, and that no reliable dental-tourism
  figures exist. No data found by origin country (Russia, Iran, Lebanon, US).
  I will not quote a share for any country.
- Savings claims (for example "one fifth of US prices") are anecdotal.

## What is missing in Armenia (judgment, from what listings show)
1. Directory-style presence: little brand, no sense of calm or design.
2. Prices as wide ranges with no way to estimate your own case.
3. No interactive way to see a possible result before booking.
4. Dental-tourism help is a line of text, not a planner (visits, days, hotel).
5. Fear is not addressed: no step-by-step first visit, no sedation explanation.
6. Doctors appear as names, not people with stories and languages.

## How this clinic stands out
Boutique-hotel calm instead of hospital white. One signature: Smile Preview in
the browser, nothing uploaded. Honest planning: cost planner in AMD plus USD,
EUR, RUB, and a trip planner. Proof as sliders, doctors as people, fear
addressed on purpose. Everything labelled sample or simulation.

## Direction notes
- Stay away from: Forum, Manrope, IBM Plex, Archivo; dark basalt; teal-grey
  technical. The bonbons final look is not in style-log.md yet; I will check it
  before locking palette and type. Ilona to confirm it.
- Face landmarks: MediaPipe Face Landmarker (`@mediapipe/tasks-vision`, 478
  points, lips set available, runs on-device). Runs on the main thread, so use a
  worker or throttle on phones.

## Open items for Ilona
- Bonbons final look (colours, fonts) so I can keep clear of it.
- Canva images: available for me to generate here, or will you supply?
- Whether Dentalclinic Zürich, Kois Center and Awwwards winners should be
  reviewed by hand and screenshotted (I can't open them reliably from here).
