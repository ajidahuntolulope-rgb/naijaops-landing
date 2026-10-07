# NaijaOps — Buyer List (Ikeja, private, reachable) — corrected 7 October 2026

Filtered from the 86-business screen. The screen answered "what does the market look like";
this answers "who can actually be messaged". **The filter is code** (`buyer-filter-log.json`,
`buyers-v2.json`), so the report cannot drift from the data by hand.

## Corrections to the previous version

- **Energy plumbing professional services** was left in Tier 2 with address "Idimu, Alimosho".
  Out of area. Dropped.
- **Local Bukka (Yaba)** was left in the place-ID table. Yaba is out of area. Dropped.
- **Nett Pharmacy** phone is "12955051" — not a usable Nigerian number. Marked invalid, not queued.
- **Tier 1 of 4 included the HOLD row.** Sendable Tier 1 is **3**.
- **"20 Tier 1 or Tier 2" included HOLD and unreachable rows.** Sendable is **15**.

## Filter applied

| Dropped | Count | Why |
|---|---|---|
| Sponsored cards | 3 | Scrape artifacts, not distinct businesses |
| Government facilities | 5 | LASUTH, Mother and Child, Ayinke House, Oregun PHC, Ikeja PHC |
| Large institutions | 3 | Ikeja Medical Centre, Iwosan Lagoon, Duchess International |
| Markets | 1 | Ladipo Auto Market is a market, not a buyer |
| Out of area | 13 | Lekki, VI, Ikoyi, Ajah, Surulere, Yaba, Ogba, Alimosho, Idimu, Dopemu, Egbeda, Maryland |

**86 unique → 61 Ikeja private businesses.**

## Counts, stated plainly

- Tier 1 (unclaimed): **4** — of which **3 sendable** (one on HOLD)
- Tier 2 (claimed, missing phone or website): **15**
- Tier 3 (already built, do not message): **42**
- **Sendable queue (Tier 1 or 2, valid phone, not HOLD): 15**

Cafecito is unclaimed and has **no phone on its listing**, so it is not a WhatsApp send. It
stays in the list as a phone-or-visit target only and is excluded from the 15.

## Tier 1 — unclaimed (4)

| Business | Address | Rating | Phone on listing | Website | Maps place URL |
|---|---|---|---|---|---|
| Cafecito | 11 Joel Ogunnaike St, Ikeja GRA, Lagos 101233, Lagos | 4.0 | none | none | https://www.google.com/maps/place/Cafecito/@6.5865141,3.3556279,17z/data=!3m1!4b1!4m6!3m5!1s0x103b93001f1e48c1:0x7eafa7dd0adf7274!8m2!3d6.5865141!4d3.3556279!16s%2Fg%2F11xrf186yv?entry=ttu |
| Fiora' Garden | 9 Sasegbon St, Ikeja GRA, Lagos 101233, Lagos | 4.4 | 0903 000 4080 | Instagram only | https://www.google.com/maps/place/Fiora'+Garden/@6.5777841,3.3555387,17z/data=!3m1!4b1!4m6!3m5!1s0x103b93007e98cd4b:0xa8f691d97ead4850!8m2!3d6.5777841!4d3.3555387!16s%2Fg%2F11wmqr3dn5?entry=ttu |
| Ican Lectures | 110 Obafemi Awolowo Wy, Allen, Ikeja 101233, Lagos | 4.3 | 0708 681 0335 | none | https://www.google.com/maps/place/Ican+Lectures/@6.6022129,3.3447339,17z/data=!3m1!4b1!4m6!3m5!1s0x103b922ed729f155:0xaa8caa95f5b8713c!8m2!3d6.6022129!4d3.3447339!16s%2Fg%2F1q629jpkx?entry=ttu |
| Ikeja lagos state **(HOLD — trading name unconfirmed)** | 3 Samuel Awoniyi St, Opebi, Ikeja 101233, Lagos | — | 0808 721 2252 | yes | https://www.google.com/maps/place/Ikeja+lagos+state/@6.5798836,3.3479714,13z/data=!4m10!1m2!2m1!1shardware+shop+Ikeja+Lagos!3m6!1s0x103b93003905e769:0xcd7515626dd4c7dc!8m2!3d6.5923946!4d3.3613056!15sChloYXJkd2FyZSBzaG9wIElrZWphIExhZ29zkgEOaGFyZHdhcmVfc3RvcmXgAQA!16s%2Fg%2F11ynzcnn_q |

## Tier 2 — claimed, missing phone or website (15)

| Business | Address | Rating | Phone on listing | Website | Maps place URL |
|---|---|---|---|---|---|
| Ace Wash N Dry | Kudirat Abiola Way, Oregun, Ikeja 101233, Lagos | 4.8 | 0905 718 4682 | none | https://www.google.com/maps/place/Ace+Wash+N+Dry/@6.6031369,3.362752,17z/data=!3m1!4b1!4m6!3m5!1s0x103b93214beb204f:0xbaf75ad1a5ba0b2b!8m2!3d6.6031369!4d3.362752!16s%2Fg%2F11h6dhd8q2?entry=ttu |
| Avid Dental Clinic Lagos | Ile Zik Bus Stop, 601 Agege Motor Rd, Ile Zik, Ikeja 101233, Lagos | 5.0 | 0901 645 9100 | none | https://www.google.com/maps/place/Avid+Dental+Clinic+Lagos/@6.6023837,3.3314089,17z/data=!3m1!4b1!4m6!3m5!1s0x103b91e1db9e2ee5:0xcd83f1cef4aa229a!8m2!3d6.6023837!4d3.3314089!16s%2Fg%2F11vbwr8srf?entry=ttu |
| Bodet Medicare Maternity center | 6 Odewale St, Alausa, Ikeja 101233, Lagos | 4.0 | 0802 313 8907 | none | https://www.google.com/maps/place/Bodet+Medicare+Maternity+center/@6.6094652,3.3558174,17z/data=!3m1!4b1!4m6!3m5!1s0x103b9234cc29d223:0x438ffbd35ffad546!8m2!3d6.6094652!4d3.3558174!16s%2Fg%2F11bbrc7qhn?entry=ttu |
| Braids by Enny in Allen Avenue Ikeja Lagos | 60 Allen Ave, Allen, Ikeja 100001, Lagos | 5.0 | none | wa.me only | https://www.google.com/maps/place/Braids+by+Enny+in+Allen+Avenue+Ikeja+Lagos/@6.601907,3.3520669,17z/data=!3m1!4b1!4m6!3m5!1s0x103b9388440ffe33:0xbcf0976b2470cf98!8m2!3d6.601907!4d3.3520669!16s%2Fg%2F11zds26nyw?entry=ttu |
| Commint Buka | 15/17 Majekodunmi St, Allen, Ikeja 101233, Lagos | 4.2 | 0909 000 5472 | none | https://www.google.com/maps/place/Commint+Buka/@6.5977219,3.3518684,17z/data=!3m1!4b1!4m6!3m5!1s0x103b923a593bb5bb:0x140df44c0f5801a1!8m2!3d6.5977219!4d3.3518684!16s%2Fg%2F11c0tb0rqh |
| Ezzy Place Cyber Cafe & DI Printing Centre | 4 Oriyomi St, off Kodesoh Street, Opebi, Ikeja 100001, Lagos | 4.2 | 0815 771 5971 | none | https://www.google.com/maps/place/Ezzy+Place+Cyber+Cafe+%26+DI+Printing+Centre/@6.5957094,3.3417479,17z/data=!3m1!4b1!4m6!3m5!1s0x103b9226e56e19c3:0x647ddce3b4ed85bb!8m2!3d6.5957094!4d3.3417479!16s%2Fg%2F1pp2wzj9f?entry=ttu |
| Food Headquarters Ikeja | 7 Olowu St, Allen, Ikeja 100212, Lagos | 4.6 | 0811 887 7147 | none | https://www.google.com/maps/place/Food+Headquarters+Ikeja/@6.5989707,3.3435678,17z/data=!3m1!4b1!4m6!3m5!1s0x103b93bd44b6a5cf:0xc633353df4cef20a!8m2!3d6.5989707!4d3.3435678!16s%2Fg%2F11h1kp_cbj |
| IKOKO | 23b Isaac John St, Ikeja GRA, Ikeja 000000, Lagos | 4.5 | 0915 436 6666 | none | https://www.google.com/maps/place/IKOKO/@6.5807117,3.3584375,17z/data=!3m1!4b1!4m6!3m5!1s0x103b935dfc959a3f:0x6b3d0db68250080!8m2!3d6.5807117!4d3.3584375!16s%2Fg%2F11xkpf8n_6?entry=ttu |
| Japhet Laundry and Dry-cleaning Services | p"block powa plaza behind new aviation ikeja, Lagos | 4.7 | 0706 616 9284 | none | https://www.google.com/maps/place/Japhet+Laundry+and+Dry-cleaning+Services+%7C+Ikeja,+Lagos/@6.5838439,3.3584378,17z/data=!3m1!4b1!4m6!3m5!1s0x103b935fb5920c5f:0x1a46bb373584bb5c!8m2!3d6.5838439!4d3.3584378!16s%2Fg%2F11h4rx1cj9?entry=ttu |
| Nailsbyfey | local government, No8 Amore street, Off Toyin Street, Ikeja Lagos Ikeja Ikeja, Lagos 100271, Lagos | 4.8 | 0706 915 8434 | none | https://www.google.com/maps/place/Nailsbyfey+%7C+Nails+techinician+in+Ikeja+%7C+Nails+in+Lagos/@6.596806,3.3498941,17z/data=!3m1!4b1!4m6!3m5!1s0x103b93734fd628af:0x905f66b82097a640!8m2!3d6.596806!4d3.3498941!16s%2Fg%2F11r1xdx7tw?entry=ttu |
| Nett Pharmacy **(phone invalid — do not message)** | 33 Opebi Rd, Allen, Ikeja 101233, Lagos | 3.7 | 12955051 | none | https://www.google.com/maps/place/Nett+Pharmacy/@6.5968929,3.3554963,16z/data=!4m10!1m2!2m1!1sNett+Pharmacy+Opebi+Ikeja!3m6!1s0x103b923f67678ebd:0x2f2eef99a591f661!8m2!3d6.5925473!4d3.3589452!15sChlOZXR0IFBoYXJtYWN5IE9wZWJpIElrZWphWhsiGW5ldHQgcGhhcm1hY3kgb3BlYmkgaWtlamGSARZwaGFybWFjZXV0aWNhbF9jb21wYW55mgEkQ2hkRFNVaE5NRzluUzBWSlEwRm5UVU5KZWtvMk9XZFJSUkFC4AEA-gEECFwQLQ!16s%2Fg%2F119w0rtjs?entry=ttu |
| Original Parts Nigeria | 45B Opebi Rd, Opebi, Ikeja 100001, Lagos | 4.7 | 0816 222 5612 | none | https://www.google.com/maps/place/Original+Parts+Nigeria/@6.590928,3.3602859,17z/data=!3m1!4b1!4m6!3m5!1s0x103b924060ea1cad:0xbd0f37e167712f50!8m2!3d6.590928!4d3.3602859!16s%2Fg%2F11fz3d9jxc?entry=ttu |
| Petite Wellness Spa (PWS) | Obafemi Awolowo house,4 Alhaji kofoworola street off Obafemi Awolowo way Ikeja Ikeja, Ikeja, Lagos | 5.0 | 0805 802 9610 | none | https://www.google.com/maps/place/Petite+Wellness+Spa+(PWS)/@6.5971629,3.3403871,17z/data=!3m1!4b1!4m6!3m5!1s0x103b93535a8dfac1:0x128693e280d3becb!8m2!3d6.5971629!4d3.3403871!16s%2Fg%2F11z67c747t?entry=ttu |
| Pipes and Co Plumbing | 1 Kodesoh St, Ikeja, Lagos 101233, Lagos | 4.0 | 0708 992 8150 | none | https://www.google.com/maps/place/Pipes+and+Co+Plumbing/@6.5966319,3.341045,17z/data=!3m1!4b1!4m6!3m5!1s0x103b9226dfe4d8bd:0xadb1c431066f0555!8m2!3d6.5966319!4d3.341045!16s%2Fg%2F11dxs979fy?entry=ttu |
| TEJ Salon and Spa | 19 Adeleke St, Allen, Ikeja 101233, Lagos | 4.6 | 0906 371 8357 | none | https://www.google.com/maps/place/TEJ+Salon+and+Spa/@6.6022239,3.350691,17z/data=!3m1!4b1!4m6!3m5!1s0x103b93cfa8f07707:0x363406da18f16244!8m2!3d6.6022239!4d3.350691!16s%2Fg%2F11gy9yv9cw?entry=ttu |

## The sendable 15, ranked

| # | Business | Tier | Phone | Missing | Place URL |
|---|---|---|---|---|---|
| 1 | Ican Lectures | T1 | 0708 681 0335 | website | https://www.google.com/maps/place/Ican+Lectures/@6.6022129,3.3447339,17z/data=!3m1!4b1!4m6!3m5!1s0x103b922ed729f155:0xaa8caa95f5b8713c!8m2!3d6.6022129!4d3.3447339!16s%2Fg%2F1q629jpkx?entry=ttu |
| 2 | Ace Wash N Dry | T2 | 0905 718 4682 | website | https://www.google.com/maps/place/Ace+Wash+N+Dry/@6.6031369,3.362752,17z/data=!3m1!4b1!4m6!3m5!1s0x103b93214beb204f:0xbaf75ad1a5ba0b2b!8m2!3d6.6031369!4d3.362752!16s%2Fg%2F11h6dhd8q2?entry=ttu |
| 3 | Avid Dental Clinic Lagos | T2 | 0901 645 9100 | website | https://www.google.com/maps/place/Avid+Dental+Clinic+Lagos/@6.6023837,3.3314089,17z/data=!3m1!4b1!4m6!3m5!1s0x103b91e1db9e2ee5:0xcd83f1cef4aa229a!8m2!3d6.6023837!4d3.3314089!16s%2Fg%2F11vbwr8srf?entry=ttu |
| 4 | Bodet Medicare Maternity center | T2 | 0802 313 8907 | website | https://www.google.com/maps/place/Bodet+Medicare+Maternity+center/@6.6094652,3.3558174,17z/data=!3m1!4b1!4m6!3m5!1s0x103b9234cc29d223:0x438ffbd35ffad546!8m2!3d6.6094652!4d3.3558174!16s%2Fg%2F11bbrc7qhn?entry=ttu |
| 5 | Commint Buka | T2 | 0909 000 5472 | website | https://www.google.com/maps/place/Commint+Buka/@6.5977219,3.3518684,17z/data=!3m1!4b1!4m6!3m5!1s0x103b923a593bb5bb:0x140df44c0f5801a1!8m2!3d6.5977219!4d3.3518684!16s%2Fg%2F11c0tb0rqh |
| 6 | Ezzy Place Cyber Cafe & DI Printing Centre | T2 | 0815 771 5971 | website | https://www.google.com/maps/place/Ezzy+Place+Cyber+Cafe+%26+DI+Printing+Centre/@6.5957094,3.3417479,17z/data=!3m1!4b1!4m6!3m5!1s0x103b9226e56e19c3:0x647ddce3b4ed85bb!8m2!3d6.5957094!4d3.3417479!16s%2Fg%2F1pp2wzj9f?entry=ttu |
| 7 | Food Headquarters Ikeja | T2 | 0811 887 7147 | website | https://www.google.com/maps/place/Food+Headquarters+Ikeja/@6.5989707,3.3435678,17z/data=!3m1!4b1!4m6!3m5!1s0x103b93bd44b6a5cf:0xc633353df4cef20a!8m2!3d6.5989707!4d3.3435678!16s%2Fg%2F11h1kp_cbj |
| 8 | IKOKO | T2 | 0915 436 6666 | website | https://www.google.com/maps/place/IKOKO/@6.5807117,3.3584375,17z/data=!3m1!4b1!4m6!3m5!1s0x103b935dfc959a3f:0x6b3d0db68250080!8m2!3d6.5807117!4d3.3584375!16s%2Fg%2F11xkpf8n_6?entry=ttu |
| 9 | Japhet Laundry and Dry-cleaning Services | T2 | 0706 616 9284 | website | https://www.google.com/maps/place/Japhet+Laundry+and+Dry-cleaning+Services+%7C+Ikeja,+Lagos/@6.5838439,3.3584378,17z/data=!3m1!4b1!4m6!3m5!1s0x103b935fb5920c5f:0x1a46bb373584bb5c!8m2!3d6.5838439!4d3.3584378!16s%2Fg%2F11h4rx1cj9?entry=ttu |
| 10 | Nailsbyfey | T2 | 0706 915 8434 | website | https://www.google.com/maps/place/Nailsbyfey+%7C+Nails+techinician+in+Ikeja+%7C+Nails+in+Lagos/@6.596806,3.3498941,17z/data=!3m1!4b1!4m6!3m5!1s0x103b93734fd628af:0x905f66b82097a640!8m2!3d6.596806!4d3.3498941!16s%2Fg%2F11r1xdx7tw?entry=ttu |
| 11 | Original Parts Nigeria | T2 | 0816 222 5612 | website | https://www.google.com/maps/place/Original+Parts+Nigeria/@6.590928,3.3602859,17z/data=!3m1!4b1!4m6!3m5!1s0x103b924060ea1cad:0xbd0f37e167712f50!8m2!3d6.590928!4d3.3602859!16s%2Fg%2F11fz3d9jxc?entry=ttu |
| 12 | Petite Wellness Spa (PWS) | T2 | 0805 802 9610 | website | https://www.google.com/maps/place/Petite+Wellness+Spa+(PWS)/@6.5971629,3.3403871,17z/data=!3m1!4b1!4m6!3m5!1s0x103b93535a8dfac1:0x128693e280d3becb!8m2!3d6.5971629!4d3.3403871!16s%2Fg%2F11z67c747t?entry=ttu |
| 13 | Pipes and Co Plumbing | T2 | 0708 992 8150 | website | https://www.google.com/maps/place/Pipes+and+Co+Plumbing/@6.5966319,3.341045,17z/data=!3m1!4b1!4m6!3m5!1s0x103b9226dfe4d8bd:0xadb1c431066f0555!8m2!3d6.5966319!4d3.341045!16s%2Fg%2F11dxs979fy?entry=ttu |
| 14 | TEJ Salon and Spa | T2 | 0906 371 8357 | website | https://www.google.com/maps/place/TEJ+Salon+and+Spa/@6.6022239,3.350691,17z/data=!3m1!4b1!4m6!3m5!1s0x103b93cfa8f07707:0x363406da18f16244!8m2!3d6.6022239!4d3.350691!16s%2Fg%2F11gy9yv9cw?entry=ttu |
| 15 | Fiora' Garden | T1 | 0903 000 4080 | — | https://www.google.com/maps/place/Fiora'+Garden/@6.5777841,3.3555387,17z/data=!3m1!4b1!4m6!3m5!1s0x103b93007e98cd4b:0xa8f691d97ead4850!8m2!3d6.5777841!4d3.3555387!16s%2Fg%2F11wmqr3dn5?entry=ttu |

## Place URLs verified (16)

Every URL below belongs to a business that survived the filter. Each was re-opened and captured as a **place** URL with its place ID. No search URLs remain. (Local Bukka's place URL was removed with it — Yaba is out of area.)

| Business | Place ID |
|---|---|
| Ace Wash N Dry | 0x103b93214beb204f:0xbaf75ad1a5ba0b2b |
| Avid Dental Clinic Lagos | 0x103b91e1db9e2ee5:0xcd83f1cef4aa229a |
| Bodet Medicare Maternity center | 0x103b9234cc29d223:0x438ffbd35ffad546 |
| Braids by Enny in Allen Avenue Ikeja Lagos | 0x103b9388440ffe33:0xbcf0976b2470cf98 |
| Cafecito | 0x103b93001f1e48c1:0x7eafa7dd0adf7274 |
| Ezzy Place Cyber Cafe & DI Printing Centre | 0x103b9226e56e19c3:0x647ddce3b4ed85bb |
| Fiora' Garden | 0x103b93007e98cd4b:0xa8f691d97ead4850 |
| IKOKO | 0x103b935dfc959a3f:0x6b3d0db68250080 |
| Ican Lectures | 0x103b922ed729f155:0xaa8caa95f5b8713c |
| Japhet Laundry and Dry-cleaning Services | Ikeja, Lagos | 0x103b935fb5920c5f:0x1a46bb373584bb5c |
| Nailsbyfey | Nails techinician in Ikeja | Nails in Lagos | 0x103b93734fd628af:0x905f66b82097a640 |
| Nett Pharmacy | 0x103b923f67678ebd:0x2f2eef99a591f661 |
| Original Parts Nigeria | 0x103b924060ea1cad:0xbd0f37e167712f50 |
| Petite Wellness Spa (PWS) | 0x103b93535a8dfac1:0x128693e280d3becb |
| Pipes and Co Plumbing | 0x103b9226dfe4d8bd:0xadb1c431066f0555 |
| TEJ Salon and Spa | 0x103b93cfa8f07707:0x363406da18f16244 |

## Caveats

- Photo counts are not exposed by the public Maps view. Do not quote a photo number.
- "—" means no rating was displayed in the view captured; it does not mean zero.
- Listings change. Re-open the place URL the morning of any send.
