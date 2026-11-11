# SHU Restaurant: suburb location page template

**Layout name:** SHU suburb location page (Squarespace 7.1 fluid engine)
**Source (approved, built by delivery):** https://www.shurestaurant.com/vegan-restaurant-kensington/ (primary) and https://www.shurestaurant.com/vegan-restaurant-southbank/ (identical section order)
**Yum cha facts source:** https://www.shurestaurant.com/sunday-yumcha
**Pages to write with this template:** Yum Cha Footscray, Yum Cha Preston
**Files:** page_css.css (classes `su-`, header `suh-`, footer `suf-`), page_header.html, page_footer.html, skeleton.html, sample.html (Yum Cha Footscray).

## Hard rules
- SHU is entirely plant based. Never mention meat, seafood, dairy, egg, "mock meat" comparisons to animal dishes, or anything that suggests non-vegan food.
- SHU has ONE venue: 147 Johnston Street, Collingwood. A suburb page must never imply a venue, branch, delivery or pop-up in that suburb. Use "near <Suburb>", "visiting from <Suburb>", "<Suburb> diners", and always say guests join us in Collingwood.
- Do not state travel times, distances, tram/train routes or parking unless the live site states them (it does not).
- No menu prices, no hats, awards, rankings or review scores. The live yum cha page shows prices, but they conflict ($68.80 vs $65), so never quote them.
- Only reuse facts listed under "Facts on the live site" below. If it is not there, leave it out.
- Australian English, "we" voice (the live pages are written as SHU: "We serve...", "We welcome..."), no em or en dashes, no Oxford comma.
- Exactly one `<h1>`. No inline `style` attributes. Do not rename or add classes.
- "Yum Cha" is capitalised as on the live site.

## Sections in order (what to write)
| # | Section (class) | Look | Fixed or slot | Words |
|---|---|---|---|---|
| 1 | Hero `pg-hero su-sec su-hero` | Full-width photo under a dark 70% overlay, centred white brush-script H1, coral square phone button "0390907878" | H1 + hero photo are slots; phone button fixed | H1 6 to 12 |
| 2 | Intro `su-intro` | White, photo left, text right (stacks on mobile), small coral "Call Me" button | H2 + 2 paragraphs + photo are slots; button fixed | H2 5 to 9; paras 45 to 65 and 45 to 70 |
| 3 | Our Dining Options `su-opts` | Pink band, giant script title, 3 white cards (4:3 photo, script title, text, coral button) | Card titles, photos, buttons, links fixed; each card blurb is a slot | 22 to 32 per card |
| 4 | Make a Reservation `su-res` | Pink to coral radial gradient, centred title, 6 policy bullets, OpenTable picker | Fully fixed, copy verbatim | 0 |
| 5 | Explore `su-explore` | White, text left, photo right | H2 + 2 paragraphs + photo are slots | H2 6 to 10; paras 50 to 70 and 40 to 60 |
| 6 | Give The Gift of SHU `su-gift` | Solid coral, centred white text, white button | Fully fixed | 0 |
| 7 | FAQ `su-faq` | Centred script title, centred accordion rows with plus icon and rule lines | 5 Q&As (4 to 6 allowed) are slots | Q 6 to 14; A 30 to 55 |
| 8 | Map `su-map` | Google Map of SHU, Collingwood | Fixed | 0 |

**Total written words (slots only):** 480 to 650. Whole page including fixed copy lands around 650 to 800, matching Kensington and Southbank.

### Section guidance
1. **H1.** Pattern from live pages: "Vegan Restaurant Near Kensington with a Modern Sichuan Twist", "Vegan Restaurant Near Southbank for Modern Chinese Dining". For yum cha pages: "Vegan Yum Cha Near <Suburb> with a Modern Sichuan Twist" or "Unlimited Vegan Yum Cha Near <Suburb>". Keyword + "Near <Suburb>" is mandatory, never "in <Suburb>".
2. **Intro.** H2 is a short benefit line (live: "Discover a Fresh Take on Vegan Chinese Cuisine"). Para 1 opens with the searcher's question ("Looking for / Searching for vegan Yum Cha near <Suburb>?"), says SHU is a fully plant-based Sichuan kitchen and welcomes them to Collingwood. Para 2 covers what to expect and who it suits, ends with a nudge to book. 1 to 2 internal links.
3. **Card blurbs.** Re-word every time (the live pages reword them per suburb), keep the "We ..." voice, keep to the facts: degustation = ten courses, seasonal plant-based Sichuan, optional wine pairing; 5 course = chef's choice inspired by Sichuan home cooking, street food and family recipes; Yum Cha = unlimited, Saturday and Sunday lunch, dumplings and Sichuan share plates, two-hour sitting, optional bottomless beverage package.
4. **Reservation.** Do not touch. Copy is verbatim from the live page, including its typos (see report).
5. **Explore.** About flavour and the experience: fragrant spices, chilli oil, Sichuan peppercorns, seasonal plant-based ingredients, texture. Mention "<Suburb> diners" once. End by placing the meal "in Collingwood".
6. **Gift.** Do not touch.
7. **FAQ.** Q1 always location ("Where is SHU located if we are visiting from <Suburb>?") with the Google Maps link. Last Q always how to book (reservation page + phone link). Middle questions for yum cha pages: when it runs, how the unlimited format works, dietary requests (not catered for Yum Cha), drinks, groups/celebrations. Questions use "we", answers start "Yes," / "We ...".
8. **Map.** Do not touch.

## Fixed copy (verbatim, already in skeleton.html)
- Hero button: `0390907878` linking `tel:0390907878`
- Intro button: `Call Me` linking `tel:+61390907878`
- List title: `Our Dining Options`; cards `10 Course Vegan Degustation` / `Tell Me More` (/10-course-vegan-degustation), `Chef's choice of 5 course` / `Read More` (/pick-n-shus-a-la-carte-menu), `Unlimited Yum Cha Sat/Sun` / `SEE MENU` (/sunday-yumcha)
- Reservation block: `MAKE A RESERVATIOn`, `Please read carefully before making a reservation` + 6 bullets (as in skeleton)
- Gift: `Give The Gift of SHU`, `Need a gift? Want to introduce someone to the world of plant based dining? Buy a gift card for one of Shu’s experimental or 10 course dining experiences.`, `Buy A Gift Card` (/gift-cards)
- FAQ title: `Frequently Asked Questions`

## Facts on the live site (only these may be used)
| Fact | Verbatim | Where |
|---|---|---|
| Address | "147 Johnston Street, Collingwood, VIC 3066" (FAQ). Footer shows "147 Johnson St, Collingwood,  VIC 066" | Kensington and Southbank FAQ; site footer |
| Map link | https://maps.app.goo.gl/6aXgCVskieWFVqKq8 | Kensington FAQ |
| Phone | "03 9090 7878" (tel:0390907878); buttons show "0390907878" | Kensington FAQ, hero button |
| Email | "shu@shurestaurant.com" | Footer |
| Opening hours | "MON-TUE: CLOSED / WED-FRI: 6pm-9:30pm / SAT: 12pm-3pm (YUMCHA) / SAT:  6pm-10pm(DINNER) / SUN: 12PM-3PM (YUMCHA)" | Footer, every page |
| Yum cha days | "We serve unlimited vegan Yum Cha at lunch on Saturdays and Sundays. Each sitting lasts two hours" | /vegan-restaurant-kensington FAQ |
| Yum cha format | "a two-hour unlimited feast featuring 9 signature dishes cooked to order, all 100% vegan" ; "plant-based dumplings, baos, noodles, and small plates" | /sunday-yumcha |
| Yum cha dietary | "We do not cater for any dietary requests for Yum Cha" ; "Sorry we do not cater for any allergies and dietary requests." | Reservation block; /sunday-yumcha |
| Yum cha drinks | "we offer an optional bottomless beverage package that can be added to your Yum Cha booking" | /sunday-yumcha FAQ |
| Yum cha style | "Instead of the usual Cantonese-style dim sum, we serve creative plant-based dishes inspired by Sichuan flavours such as chilli, fermented sauces, and aromatic spices" | /sunday-yumcha FAQ |
| Groups | "great option for birthday lunches, catch-ups with friends, or casual celebrations" | /sunday-yumcha FAQ |
| Whole menu vegan | "Yes, our entire menu is vegan." | Kensington FAQ |
| Degustation | ten courses, seasonal plant-based, "Optional wine pairing is available." | Kensington cards |
| 5 course | "five courses inspired by Sichuan home cooking, street food and family recipes" | Kensington cards |
| Private events | "we offer dining spaces for birthdays, group dinners and private functions" | Kensington FAQ |
| No BYO, weekend surcharge | "No BYO" ; "10% surcharge applies on Saturdays and Sundays." | Reservation block |
| Booking | online at https://www.shurestaurant.com/reservations or by phone | Kensington FAQ; header Book Now |
| Announcement bar | "Unlimited Yum Cha. Crafted to Share | Every Saturday & Sunday" | Site-wide |

## Internal links (use full https://www.shurestaurant.com URLs, 3 to 5 in the written slots)
- /sunday-yumcha (anchor: unlimited vegan Yum Cha, weekend Yum Cha), use on every yum cha page
- /vegan-restaurant-collingwood (Collingwood restaurant)
- /plant-based-restaurant-in-melbourne (plant-based food in Melbourne)
- /chinese-sichuan-cuisine-in-melbourne (Chinese cuisine, Sichuan cuisine)
- /vegan-restaurant-in-melbourne (vegan restaurant in Melbourne)
- /blog/vegan-food-collingwood (vegan food in Melbourne)
- /reservations (reservation page), /gift-cards, /10-course-vegan-degustation
- Existing related pages to be aware of (do not cannibalise, may link): /vegan-yum-cha-melbourne, /sichuan-restaurant-near-preston

## Images
Three slot photos per page: hero (landscape, shown at 30% under a dark overlay), intro and explore (cropped to fill). Use client library photo URLs only, never stock, and never the same photo twice on a page. Card photos are fixed. Alt text describes the photo plainly and may name the topic once.

## Avoid
- "in Footscray", "our Footscray restaurant", "local to you", "just around the corner", travel times.
- Prices, "best", "award-winning", "hatted", star ratings, review counts.
- Promising dietary changes or allergy handling for Yum Cha.
- Claiming Yum Cha runs any day but Saturday and Sunday, or at dinner.
- Mentioning Sunday dinner (the footer lists no Sunday dinner).
