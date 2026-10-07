# NaijaOps — Buyer List (Ikeja, private, reachable) — corrected 7 October 2026

Filtered from the 86-business screen. **The filter is code** (`buyers-v2.json`,
`buyer-filter-log.json`), so this page cannot drift from the data by hand.

## Corrections to earlier versions

- **Energy plumbing professional services** (Idimu, Alimosho) — out of area. Dropped.
- **Local Bukka (Yaba)** — out of area. Dropped from the target list and the place-URL table.
- **Nett Pharmacy** phone "12955051" is not a usable Nigerian number. Flagged invalid, not queued.
- **Tier 1 of 4 included the HOLD row.** Sendable Tier 1 is **3**.
- **"20 Tier 1 or Tier 2" included HOLD and unreachable rows.** Sendable is **15**.
- **Search URLs.** Four links once carried a Google search-query payload. Every URL is now a
  canonical place-ID URL (`/maps/place/?q=place_id:...`), which has no query payload at all.
- **Two table rows were split by a pipe character in the listing name** (Japhet, Nailsbyfey).
  Pipe characters are now escaped before rendering, so no cell can split. Japhet's address
  field was also carrying scraped junk from the page markup. It now reads "Powa Plaza, behind
  New Aviation, Ikeja, Lagos".

## Filter applied

| Dropped | Count | Why |
|---|---|---|
| Sponsored cards | 3 | Scrape artifacts, not distinct businesses |
| Government facilities | 5 | LASUTH, Mother and Child, Ayinke House, Oregun PHC, Ikeja PHC |
| Large institutions | 3 | Ikeja Medical Centre, Iwosan Lagoon, Duchess International |
| Markets | 1 | Ladipo Auto Market is a market, not a buyer |
| Out of area | 13 | Lekki, VI, Ikoyi, Ajah, Surulere, Yaba, Ogba, Alimosho, Idimu, Dopemu, Egbeda, Maryland |

**86 unique → 61 Ikeja private businesses.**

## Counts

- Tier 1 (unclaimed): **4** — of which **3 sendable** (one on HOLD)
- Tier 2 (claimed, missing phone or website): **15**
- Tier 3 (already built, do not message): **42**
- **Sendable queue (Tier 1 or 2, valid phone, not HOLD): 15**

Cafecito is unclaimed with **no phone on its listing** — not a WhatsApp send. It stays as a
phone-or-visit target only and is excluded from the 15.

## Tier 1 — unclaimed (4)

| Business | Address | Rating | Phone on listing | Website | Maps place URL |
|---|---|---|---|---|---|
| Cafecito | 11 Joel Ogunnaike St, Ikeja GRA, Lagos 101233, Lagos | 4.0 | none | none | https://www.google.com/maps/place/?q=place_id:0x103b93001f1e48c1:0x7eafa7dd0adf7274 |
| Fiora' Garden | 9 Sasegbon St, Ikeja GRA, Lagos 101233, Lagos | 4.4 | 0903 000 4080 | Instagram only | https://www.google.com/maps/place/?q=place_id:0x103b93007e98cd4b:0xa8f691d97ead4850 |
| Ican Lectures | 110 Obafemi Awolowo Wy, Allen, Ikeja 101233, Lagos | 4.3 | 0708 681 0335 | none | https://www.google.com/maps/place/?q=place_id:0x103b922ed729f155:0xaa8caa95f5b8713c |
| Ikeja lagos state **(HOLD — trading name unconfirmed)** | 3 Samuel Awoniyi St, Opebi, Ikeja 101233, Lagos | — | 0808 721 2252 | yes | https://www.google.com/maps/place/?q=place_id:0x103b93003905e769:0xcd7515626dd4c7dc |

## Tier 2 — claimed, missing phone or website (15)

| Business | Address | Rating | Phone on listing | Website | Maps place URL |
|---|---|---|---|---|---|
| Ace Wash N Dry | Kudirat Abiola Way, Oregun, Ikeja 101233, Lagos | 4.8 | 0905 718 4682 | none | https://www.google.com/maps/place/?q=place_id:0x103b93214beb204f:0xbaf75ad1a5ba0b2b |
| Avid Dental Clinic Lagos | Ile Zik Bus Stop, 601 Agege Motor Rd, Ile Zik, Ikeja 101233, Lagos | 5.0 | 0901 645 9100 | none | https://www.google.com/maps/place/?q=place_id:0x103b91e1db9e2ee5:0xcd83f1cef4aa229a |
| Bodet Medicare Maternity center | 6 Odewale St, Alausa, Ikeja 101233, Lagos | 4.0 | 0802 313 8907 | none | https://www.google.com/maps/place/?q=place_id:0x103b9234cc29d223:0x438ffbd35ffad546 |
| Braids by Enny in Allen Avenue Ikeja Lagos | 60 Allen Ave, Allen, Ikeja 100001, Lagos | 5.0 | none | wa.me only | https://www.google.com/maps/place/?q=place_id:0x103b9388440ffe33:0xbcf0976b2470cf98 |
| Commint Buka | 15/17 Majekodunmi St, Allen, Ikeja 101233, Lagos | 4.2 | 0909 000 5472 | none |  |
| Ezzy Place Cyber Cafe & DI Printing Centre | 4 Oriyomi St, off Kodesoh Street, Opebi, Ikeja 100001, Lagos | 4.2 | 0815 771 5971 | none | https://www.google.com/maps/place/?q=place_id:0x103b9226e56e19c3:0x647ddce3b4ed85bb |
| Food Headquarters Ikeja | 7 Olowu St, Allen, Ikeja 100212, Lagos | 4.6 | 0811 887 7147 | none |  |
| IKOKO | 23b Isaac John St, Ikeja GRA, Ikeja 000000, Lagos | 4.5 | 0915 436 6666 | none | https://www.google.com/maps/place/?q=place_id:0x103b935dfc959a3f:0x6b3d0db68250080 |
| Japhet Laundry and Dry-cleaning Services | Powa Plaza, behind New Aviation, Ikeja, Lagos | 4.7 | 0706 616 9284 | none | https://www.google.com/maps/place/?q=place_id:0x103b935fb5920c5f:0x1a46bb373584bb5c |
| Nailsbyfey | local government, No8 Amore street, Off Toyin Street, Ikeja Lagos Ikeja Ikeja, Lagos 100271, Lagos | 4.8 | 0706 915 8434 | none | https://www.google.com/maps/place/?q=place_id:0x103b93734fd628af:0x905f66b82097a640 |
| Nett Pharmacy **(phone invalid — do not message)** | 33 Opebi Rd, Allen, Ikeja 101233, Lagos | 3.7 | 12955051 | none | https://www.google.com/maps/place/?q=place_id:0x103b923f67678ebd:0x2f2eef99a591f661 |
| Original Parts Nigeria | 45B Opebi Rd, Opebi, Ikeja 100001, Lagos | 4.7 | 0816 222 5612 | none | https://www.google.com/maps/place/?q=place_id:0x103b924060ea1cad:0xbd0f37e167712f50 |
| Petite Wellness Spa (PWS) | Obafemi Awolowo house,4 Alhaji kofoworola street off Obafemi Awolowo way Ikeja Ikeja, Ikeja, Lagos | 5.0 | 0805 802 9610 | none | https://www.google.com/maps/place/?q=place_id:0x103b93535a8dfac1:0x128693e280d3becb |
| Pipes and Co Plumbing | 1 Kodesoh St, Ikeja, Lagos 101233, Lagos | 4.0 | 0708 992 8150 | none | https://www.google.com/maps/place/?q=place_id:0x103b9226dfe4d8bd:0xadb1c431066f0555 |
| TEJ Salon and Spa | 19 Adeleke St, Allen, Ikeja 101233, Lagos | 4.6 | 0906 371 8357 | none | https://www.google.com/maps/place/?q=place_id:0x103b93cfa8f07707:0x363406da18f16244 |

## The sendable 15, ranked

| # | Business | Tier | Phone | Missing | Place URL |
|---|---|---|---|---|---|
| 1 | Ican Lectures | T1 | 0708 681 0335 | website | https://www.google.com/maps/place/?q=place_id:0x103b922ed729f155:0xaa8caa95f5b8713c |
| 2 | Ace Wash N Dry | T2 | 0905 718 4682 | website | https://www.google.com/maps/place/?q=place_id:0x103b93214beb204f:0xbaf75ad1a5ba0b2b |
| 3 | Avid Dental Clinic Lagos | T2 | 0901 645 9100 | website | https://www.google.com/maps/place/?q=place_id:0x103b91e1db9e2ee5:0xcd83f1cef4aa229a |
| 4 | Bodet Medicare Maternity center | T2 | 0802 313 8907 | website | https://www.google.com/maps/place/?q=place_id:0x103b9234cc29d223:0x438ffbd35ffad546 |
| 5 | Commint Buka | T2 | 0909 000 5472 | website |  |
| 6 | Ezzy Place Cyber Cafe & DI Printing Centre | T2 | 0815 771 5971 | website | https://www.google.com/maps/place/?q=place_id:0x103b9226e56e19c3:0x647ddce3b4ed85bb |
| 7 | Food Headquarters Ikeja | T2 | 0811 887 7147 | website |  |
| 8 | IKOKO | T2 | 0915 436 6666 | website | https://www.google.com/maps/place/?q=place_id:0x103b935dfc959a3f:0x6b3d0db68250080 |
| 9 | Japhet Laundry and Dry-cleaning Services | T2 | 0706 616 9284 | website | https://www.google.com/maps/place/?q=place_id:0x103b935fb5920c5f:0x1a46bb373584bb5c |
| 10 | Nailsbyfey | T2 | 0706 915 8434 | website | https://www.google.com/maps/place/?q=place_id:0x103b93734fd628af:0x905f66b82097a640 |
| 11 | Original Parts Nigeria | T2 | 0816 222 5612 | website | https://www.google.com/maps/place/?q=place_id:0x103b924060ea1cad:0xbd0f37e167712f50 |
| 12 | Petite Wellness Spa (PWS) | T2 | 0805 802 9610 | website | https://www.google.com/maps/place/?q=place_id:0x103b93535a8dfac1:0x128693e280d3becb |
| 13 | Pipes and Co Plumbing | T2 | 0708 992 8150 | website | https://www.google.com/maps/place/?q=place_id:0x103b9226dfe4d8bd:0xadb1c431066f0555 |
| 14 | TEJ Salon and Spa | T2 | 0906 371 8357 | website | https://www.google.com/maps/place/?q=place_id:0x103b93cfa8f07707:0x363406da18f16244 |
| 15 | Fiora' Garden | T1 | 0903 000 4080 | — | https://www.google.com/maps/place/?q=place_id:0x103b93007e98cd4b:0xa8f691d97ead4850 |

## Place IDs verified (17)

These are the place IDs captured when each listing was opened. **Verified** means the ID was
read off the live listing — it does not mean the business is in the send queue. Nett Pharmacy
(invalid phone) and Cafecito (no phone) are in this table and are not sendable.

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
| Ikeja lagos state | 0x103b93003905e769:0xcd7515626dd4c7dc |
| Japhet Laundry and Dry-cleaning Services / Ikeja, Lagos | 0x103b935fb5920c5f:0x1a46bb373584bb5c |
| Nailsbyfey / Nails techinician in Ikeja / Nails in Lagos | 0x103b93734fd628af:0x905f66b82097a640 |
| Nett Pharmacy | 0x103b923f67678ebd:0x2f2eef99a591f661 |
| Original Parts Nigeria | 0x103b924060ea1cad:0xbd0f37e167712f50 |
| Petite Wellness Spa (PWS) | 0x103b93535a8dfac1:0x128693e280d3becb |
| Pipes and Co Plumbing | 0x103b9226dfe4d8bd:0xadb1c431066f0555 |
| TEJ Salon and Spa | 0x103b93cfa8f07707:0x363406da18f16244 |

## Caveats

- Photo counts are not exposed by the public Maps view. Do not quote a photo number.
- "—" means no rating was displayed in the view captured; it does not mean zero.
- Listings change. Re-open the place URL the morning of any send.
