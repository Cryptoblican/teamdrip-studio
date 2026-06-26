# TeamDrip Studio — Locked Prompt Template
_Locked June 26, 2026 — Final approved version_

## Approved Reference Images
- OSU: `2026-06-26-osu-oneshottexttest---d569970d-7e25-443b-8b0c-f6db0f45da70.jpg`
- Utah: `2026-06-26-utah-sweep-fixed---ef879164-5d16-477b-b54c-07832ad3c989.jpg`
- BYU: `2026-06-26-byu-sweep-fixed---aeb3381e-6187-46b2-8ac2-3e27576a1ba7.jpg`

## Design Rules (Locked)
- Female LEFT, back to camera, head turned over left shoulder (face in 3/4 profile)
- Male RIGHT, relaxed angled stance facing camera
- Both athletic builds, relaxed natural posture
- NO drawstrings on either hoodie
- Sweep arch: SLEEVE TIP TO SLEEVE TIP — first letter on left sleeve, last letter on right sleeve cuff
- Sweep style: outline/hollow collegiate letters in school color
- Secondary text: Helvetica-style sans-serif regular weight, SOLID FILLED (not outline), tight below arch, one-third the height of arch letters
- Front crest: hockey puck size, centered on chest, outline/hollow style
- Background: neutral warm gray seamless paper studio backdrop

## Base Prompt (swap {{VARIABLES}})

```
Professional athletic apparel studio photograph. Two young athletic adult models with toned, athletic builds standing together against a neutral warm gray seamless paper studio backdrop, soft professional studio lighting. Relaxed, natural, confident posture.

Female model on left, body turned completely away from camera showing hoodie back, head turned left over her shoulder so her face is visible in 3/4 profile, relaxed expression, loose messy blonde bun. Wearing solid {{HOODIE_COLOR}} pullover hoodie — hood flat and smooth against her back, no visible seams or panel lines on the back or hood, clean smooth fabric throughout. NO drawstrings. Back has TWO distinct text elements:
1. '{{TEAM_NAME}}' — massive bold collegiate arch that EXTENDS ALL THE WAY across BOTH SLEEVES — the first letter begins on the left sleeve, the arch crosses the entire back, and the last letter ends on the right sleeve cuff. The arch is enormous and wide, sleeve tip to sleeve tip, not confined to the back panel only. {{LETTER_COLOR}} outline/hollow letters.
2. '{{SCHOOL_NAME}}' — small comfortable gap directly below the arch, centered on the back panel only, clean Helvetica Neue Regular — thin, clean, modern sans-serif, uniform letter weight, no serifs, no bold, no decorative styling. Solid {{LETTER_COLOR}} filled letters, NOT outline. Small understated size (one-third height of arch letters).
Black athletic jogger pants.

Male model on right, relaxed slightly angled stance facing camera. Matching solid {{HOODIE_COLOR}} pullover hoodie — NO drawstrings. Small '{{LOGO_TEXT}}' crest DEAD CENTER on the chest — perfectly centered left-to-right on the front of the hoodie, NOT on the left side, NOT off to one side — directly in the middle of the chest below the neckline. {{LETTER_COLOR}} outline/hollow. Hockey puck size only, small. Black athletic jogger pants.

Soft warm studio lighting. Waist-up shot. Commercial athletic apparel photography. Sharp focus.
```

## School Variables

| School | HOODIE_COLOR | TEAM_NAME | SCHOOL_NAME | LOGO_TEXT | LETTER_COLOR |
|---|---|---|---|---|---|
| Oklahoma State | black | COWBOYS | OKLAHOMA STATE | OSU | orange |
| Utah | red | UTAH UTES | University of Utah | U | white |
| BYU | navy blue | COUGARS | BYU | BYU | white |
| Utah State | navy blue | AGGIES | UTAH STATE | USU | white |
| UVU | forest green | WOLVERINES | UVU | UVU | white |
| Arizona State | maroon | SUN DEVILS | ARIZONA STATE | ASU | gold |
| Colorado | black | BUFFALOES | COLORADO | CU | gold |
| Iowa State | cardinal red | CYCLONES | IOWA STATE | ISU | gold |

## Key Prompt Rules
- "massive" and "EXTENDS ALL THE WAY across BOTH SLEEVES" — required to get sleeve-to-sleeve arch
- "not confined to the back panel only" — required, prevents AI from shrinking the arch
- "solid {{LETTER_COLOR}} filled letters, NOT outline" — required for secondary text style
- "one-third height of arch letters" — keeps secondary text understated
- "hockey puck size" — keeps front crest small and premium feeling
