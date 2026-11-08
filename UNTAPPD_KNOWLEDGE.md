# Untappd Knowledge File: Basic City Beer Co.

The working reference for running Basic City's Untappd for Business (UTFB) account and keeping the taproom tap list and to-go list accurate.

- **Owner:** Bart Lanman
- **Last full audit:** November 8, 2026, taken from the live account and the official UTFB Help Center and API docs.
- **Keeping it current:** Update the "Live Snapshot" section whenever the menus change in a big way.

---

## 1. Our account at a glance

### Venue
| Field | Value |
|---|---|
| Venue (UTFB name) | Basic City Beer Co. Eastside Waynesboro |
| Address | 1010 E Main St, Waynesboro, VA |
| UTFB location ID (used in admin URLs) | **4819** |
| Untappd Venue ID (used for the Toast/Square connection) | **5494151** |
| Admin URL | https://business.untappd.com/app/venues/4819/menus |
| Primary user | Bart Lanman (account owner since Feb 2017) |
| Plan | **Essentials**. The dashboard shows "Upgrade to Premium". |
| POS integration | **None connected.** Toast and Square both show "Connect". |

### Our menus
| Menu | Menu ID | Status | Sections |
|---|---|---|---|
| **Beer on Tap!** | 97291 | Published | Draft (528496), On Deck |
| **Packaged Beer** | 94252 | Published | 6 Pack Cans 12oz (511476), 4 Pack Cans 16oz (511477) |

### Direct links
- **Tap list:** `https://business.untappd.com/app/venues/4819/menus/97291`
- **Packaged:** `https://business.untappd.com/app/venues/4819/menus/94252`

### Left navigation in UTFB
- **Menus:** Menu Management, Print Menus, Digital Menus, Embed Menus, Contactless Tools (QR codes), Menu History, Website
- **Analytics:** Venue Stats, Nearby Stats, Promo Stats, Local Badge Stats
- **Venue Activity:** Events, Announcements, Check-Ins
- **Revenue:** Sponsored Ads (new program: Untappd places short ads between digital-board loops and shares the revenue)
- **Settings & Integrations:** Location Settings, Integrations, API Access

> **Security:** Never put API tokens, passwords or auth tokens in this repo. The tokens live under **API Access** in UTFB. Reset them there (or via `DELETE /sessions`) if one is ever exposed.

---

## 2. Live snapshot: November 8, 2026

### Beer on Tap! → Draft (14 lines)
Prices are 16oz / 8oz / 4oz.

| # | Beer | Brewery | Style | ABV | Untappd rating (count) | Prices |
|---|---|---|---|---|---|---|
| 1 | Kathedral Kolsch | Basic City | Kölsch | 4.8 | 3.68 (185) | $7.00 / 3.50 / 2.25 |
| 2 | Our Daily Pils | Basic City | Pilsner – German | 4.7 | 3.60 (3,587) | $6.00 / 3.50 / 2.25 |
| 3 | Mayor of Munich Oktoberfest | Basic City | Festbier | 5.4 | 3.77 (435) | $7.00 / 3.50 / 2.25 |
| 4 | The Hornig Amber Lager | Basic City | Lager – Amber/Red | 5.4 | 3.70 (845) | $6.50 / 3.50 / 2.25 |
| 5 | Crispy Bask Lager | Basic City | IPL | 4.5 | 3.66 (216) | $6.50 / 3.50 / 2.25 |
| 6 | Brujula Mexican Lager | Basic City | Lager – Mexican | 4.7 | 3.67 (556) | $7.00 / 3.50 / 2.25 |
| 7 | The 6th Lord IPA | Basic City | IPA – American | 5.3 | 3.73 (11,323) | $7.00 / 3.50 / 2.25 |
| 8 | Cactus Garden IPA | Basic City | IPA – American | 6.7 | 3.71 (253) | $7.00 / 3.50 / 2.25 |
| 9 | Baby Bask Session IPA | Basic City | IPA – NE/Hazy | 5.0 | 3.78 (2,321) | $7.00 / 3.50 / 2.25 |
| 10 | Golden Child IPA | Basic City | IPA – NE/Hazy | 6.5 | 3.81 (488) | $7.00 / 3.50 / 2.25 |
| 11 | Bask DIPA | Basic City | DIPA – NE/Hazy | 7.6 | 3.96 (9,525) | $8.00 / 4.50 / 2.25 |
| 12 | Guest Tap! – Tavern Brown Ale | Alewerks | Brown Ale – American | 5.7 | 3.63 (19,807) | $7.00 / 3.50 / 2.25 |
| 13 | Guest TAp! – Watermelon Gose | Three Notch'd | Sour – Fruited Gose | 5.1 | 3.70 (9,249) | $7.00 / 3.50 / 2.25 |
| 14 | Guest Tap! – Falcon Smash | Triple Crossing | IPA – American | 7.0 | 3.97 (38,889) | $8.00 / 5.00 / 2.75 |

- **On Deck:** empty.
- **Last edited:** Oct 29, 2026.
- **Price pattern:**
  - House pints are $6.00–$8.00. The 8oz pour is $3.50, except DIPA at $4.50.
  - The 4oz taster is $2.25.
  - Premium guest beers run +$1 per pint.

### Packaged Beer (to-go)
| Section | Beer | Style | ABV | Prices |
|---|---|---|---|---|
| 6-pack 12oz | Mayor of Munich | Festbier | 5.4 | 6pk $10.99 · case $39.90 |
| 6-pack 12oz | Cactus Garden | IPA – American | 6.7 | 6pk $11.50 · case $43.70 |
| 6-pack 12oz | Brujula | Lager – Mexican | 4.7 | 6pk $10.99 · case $39.90 |
| 6-pack 12oz | Tart Up: Raspberry | Sour – Fruited | 4.7 | 6pk $10.99 · case $39.90 |
| 6-pack 12oz | The 6th Lord | IPA – American | 5.3 | 6pk $11.50 · case $43.70 |
| 6-pack 12oz | Our Daily Pils | Pilsner – German | 4.7 | 6pk $10.99 · case $39.90 |
| 4-pack 16oz | Gringo | Imperial Stout | 9.0 | **no containers or prices** |
| 4-pack 16oz | Bask DIPA | DIPA – NE/Hazy | 7.6 | 4pk $14.99 · case $85.44 |

- **Last edited:** Sep 28, 2026.

### Open issues found during the audit
Nothing has been changed yet; each of these needs Bart's OK.

1. **Gringo has no container or price.** It shows as for sale with nothing to buy. Add "16oz Can 4 Pack" plus a case price, or remove it if it's sold out.
2. **No tap numbers on any draft line.** Set 1–14 so the boards, print menus and app line up with the physical taps. Then sort by tap number.
3. **Typo:** "Guest TAp! – Watermelon Gose" should read "Guest Tap!".
4. **Guest names carry the "Guest Tap! –" prefix inside the beer name.**
   - The prefix works on the board, but it changes how the beer reads in UTFB.
   - Alternative: use a separate "Guest Taps" section and keep the original beer names.
5. **On Deck is empty.**
   - Park the next kegs and seasonals there; it's hidden and sends no notification.
   - Moving a beer from On Deck into Draft sends a "new beer" push to every subscriber. That's free marketing.
6. **Freshness.**
   - The tap list was last touched Oct 29. Untappd says guests treat a list older than about a week as stale.
   - Make an edit at least weekly, even if nothing changed.
7. **Mayor of Munich Oktoberfest is still on tap and in 6-packs in November.** Confirm it's actually still pouring and on the shelf.
8. **Container size names are inconsistent across packaged items.** "12oz 6pk", "6 Pack" and "12oz Can 6 Pack" all appear. Standardize them with **Favorite Containers**.

---

## 3. How UTFB is organized

**Location → Menus → Sections → Items → Containers.** A container is a size-and-price pair on an item.

### Menus
- **What they're for.** Each one is a separate list. The app shows them in the order set in Menu Management, which you change by dragging.
- **Publish / Unpublish.** Only published menus appear in the Untappd app.
- **"Show prices on Untappd."** This is set per menu and covers the whole menu. Print, digital and embed outputs each have their own price settings.

### Sections
- **What they're for.** Groupings inside a menu, such as Draft, 6-packs, 4-packs.
- **Order.** Drag the slider handle to reorder.
- **Hiding.** Section Settings has a "Hide this section from all published menus" option.

### On Deck
- **Built in.** Every menu has one.
- **Hidden.** Items there are invisible and trigger no notification.
- **Renaming.** It can be renamed, for example to "Coming Soon".
- **Going live.** Moving an item out of On Deck into a live section sends a push alert to subscribers.

### Items
- **Types:** Beer, Wine, Spirit, Ready to Drink, Food, Cocktail, Flight, N/A Bev, Merch, Misc.
- **Beers** link to the Untappd database by `untappd_id`, which brings in the label, style, ABV, rating and calories.
- **Per-item overrides** are possible (custom name, description, ABV and so on). They change **only our menus**, never the Untappd database.

### Containers
- **Beer** sizes come from a preloaded list of about 2,000. Picking a size unlocks the price field.
- **Order.** Drag containers into order in Item Details; the app shows them in that order.

### Favorite Containers
- **What they are.** Saved size and price shortcuts.
- **Defaults.** "Make Default" adds a favorite automatically to every new item of that type, on any menu.
- **Suggested setup:**
  - Draft: **16oz, 8oz, 4oz**.
  - Packaged: **12oz Can 6 Pack**, **12oz Can Case**, **16oz Can 4 Pack**, **16oz Can Case**.

### Bulk actions
- **Selecting.** Tick the box beside ITEMS to select everything in a section, or tick individual items.
- **The actions:**
  - **Move** to any menu or section.
  - **Delete.** Deleted items go to Menu History.
  - **Add containers and prices.**
- **Restriction.** Bulk container edits are blocked in sections that mix beer and non-beer items.

### Menu History
- **What it keeps.** Every deleted item, with its prices and custom descriptions.
- **Restoring.** Use **+** to put an item back on any menu or section.
- **Export.** The CSV includes Producer and Tap Number.
- **Coming back.** This is how a returning seasonal gets back on the menu with its old prices.

### Adding a beer that isn't on Untappd yet
1. Search "Beer Name – Basic City Beer Co".
2. If it's missing, click "Add it here". Required: name, brewery, style. Optional: ABV, IBU, description.
3. Since Feb 2026 you can attach the label at the same time. Brewery accounts get the label applied right away.
4. Better long-term: create new Basic City beers from the **brewery page** (section 9), so the database entry is correct for everyone.

---

## 4. Daily and weekly operations playbook

### When a keg is tapped
1. Make sure the beer is in **On Deck**, or add it there. Check its **16oz / 8oz / 4oz** containers and prices.
2. **Move** it into the **Draft** section and set its **tap number**.
   - Web: bulk Move.
   - Mobile: swipe left → Move.
3. The move sends a push notification to subscribers. Optionally add a **Menu Announcement → "Now"**, e.g. "Fresh: Golden Child just tapped".

### When a keg kicks
- **Mobile:** swipe left → **Replace**. This swaps in the next beer at the same position.
- **Or delete it.** It goes to Menu History with its prices, ready to restore later.
- **Same day:** never leave a kicked beer showing. Guests check Untappd before driving over.

### When a can release or packaged item lands
- Add it to **Packaged Beer** in the right section, with pack and case containers.
- When it sells out, delete it (it goes to History). Restore it on the next run.

### Weekly (Monday)
- [ ] Walk the taps and coolers, and compare them against both menus.
- [ ] Fix ABV and style overrides; confirm prices.
- [ ] Load upcoming kegs and cans into On Deck.
- [ ] Make at least one edit so "last updated" stays fresh.
- [ ] Toast and comment on recent check-ins (Check-Ins page or the mobile app).
- [ ] Post that week's events (section 7).

### Monthly
- [ ] Review Venue Stats (check-ins, menu views, top beers) and Nearby Stats (what's popular around us). Consider one or two of the trending styles as guest taps.
- [ ] Refresh the digital board theme for the season.
- [ ] Check the Menu History export for beers worth bringing back.

### Why a menu isn't showing in the app (checklist)
1. The menu isn't **Published**.
2. The section is set to hidden.
3. The beers are sitting in **On Deck**.
4. The items were created as section headings. The menu then shows "(0 Items)".
5. Still missing? Go to **Location Settings → Details → Save** to force a refresh, then wait 15–20 minutes. After that, email business@untappd.com.

---

## 5. Menu outputs

### Digital boards (TVs)
- **Hardware.** **Fire TV Stick 4K or 4K MAX** with the "Digital Menus by Untappd" app, one stick per TV.
  - Smart-TV browsers, older or Lite sticks, and the Cube are **not** supported.
- **Setup.**
  1. Digital Menus → Add New → choose menus → Design.
  2. Find the board's 5-digit Menu ID.
  3. Enter that ID on the stick.
- **Multiple TVs.**
  - Set Display Style to **Single Page**.
  - Set items per screen to total taps divided by the number of TVs. Base it on capacity, e.g. 14 taps on 2 TVs means 7 each.
  - Every stick uses the same board ID; use the remote to advance to the right page.
- **Portrait.** Pick Portrait on the Structure tab, then rotate with the remote's Select button.
- **Themes.** Default, Chalkboard, Beer, Bricks, Wooden, Neon, Oktoberfest, Fall, Frozen, St. Paddy's, Football and more. There's also "Design with AI" for custom backgrounds.
- **Display options:**
  - Trailing-zeros toggle ($8 vs $8.00).
  - Rotation interval of 60, 90 or 120 seconds.
  - A "NEW" tag whose duration you set.
  - Live check-in feed.
- **Premium only:** CSS styling.
- **Optional revenue.** The Sponsored Ads program inserts short ads between loops for a revenue share. **Decide deliberately** whether it fits the taproom vibe.

### Print menus
- **Templates.** Aurora and Cascade can show the tap number as "Tap 1" or "1", and Aurora can put prices on the same line as the drink.
- **Printing on the go.** You can print from the mobile app, but editing print menus requires the web.

### QR codes (Contactless Tools)
- **Creating one.** Add New QR. It can point to the Untappd venue page (no login needed), a print-menu PDF, or an external link.
- **Using it.** Download as PNG and put it on table tents. Each code tracks scans over the last 30 days.

### Website embed (Embed Menus)
- **Code.** Two options: HTML or **iFrame** (the iFrame is better on mobile).
- **Look.** Four layouts. Background can be set to `TRANSPARENT`.
- **Saving.** You must click **Save and Exit**, or the changes are lost.
- **Our site.** Drop it into the Basic City website as a code or HTML block. **Wix** sites use an "Embed HTML" element.

### Menu Announcements
- **Timing options:** "Now", "Once" (scheduled) and "Weekly" (e.g. a recurring happy hour).
- **Where they show:** embed, print and digital board.

---

## 6. POS integration (not set up yet)

- **Which POS.** Built-in integrations are **Toast** (needs the Toast RMS plan) and **Square**.
- **Connecting.**
  - Toast: use our **Untappd Venue ID 5494151** in Toast's Integrations, then Toast Sync → Import.
  - Square: Connect → approve as a Square admin.
- **After connecting:**
  - **What updates in UTFB.** Stock, prices and item additions and removals sync continuously. Sold-out or 0-inventory items hide automatically.
  - **What becomes read-only.** Synced menus can't be restructured in UTFB; names, categories and order are managed in the POS.
  - **What stays editable in UTFB.** Beer details, nitro/cask/local designations and tap numbers.
- **Tap numbers from the POS.** The POS item name must start with the number and a period, e.g. `1. Our Daily Pils`.
- **Container mapping.** Use Size/Price pricing in the POS so "Pint", "Half" and "Taster" map to 16oz, 8oz and 4oz containers.
- **Essentials limit.** Up to **20 non-beer items** per synced menu.
- **Imports arrive Unpublished.** Review them and publish.
- **Worth deciding.** If the POS is the true source of what's pouring, connecting it removes the manual "kick and tap" step. That would mean the menu can't go stale.

---

## 7. Venue activity and engagement

### Events
- **Fields.** Name, start and end, free or cover price, link, and a 16:9 image (1920×1080, under 5MB).
- **Reach.** A push goes to subscribers, and the event appears in Upcoming Events for users within **75 miles**.
- **Our calendar.** Mirror the Foundry and Basic City events here; the Foundry event platform audit should include Untappd.

### Announcements
- Short notices on all menu outputs.

### Check-ins
- **On premise.** A check-in counts only if the guest tags our venue as LOCATION. Table tents and QR codes help.
- **Responding.** Toast or comment on check-ins; the guest gets a notification.
- **Off premise.** "Purchased At" check-ins track our cans being bought here.

### Subscribers
- **What they get.** Alerts for new beers and/or events, depending on their choice.
- **Growing the list.** Every On Deck → live move is a marketing touch.

### Local Badge
- **What it is.** A paid add-on, requested through business@untappd.com.
- **Levels.** The first check-in earns level 1, then one more level every 5 check-ins, up to 100. Rewards can be tied to levels.
- **Building it.**
  - Artwork at least 400×400. **No emojis** in the text.
  - The launch date must be at least 48 hours out.
  - Untappd approves it.

### Promotions
- **Verified-venue launch promo.** Runs within 20 miles, at no charge.
- **Paid promos.** Custom text promos and festival promos are available.

### Analytics (Venue Stats)
- **Check-ins:** total check-ins, unique users, and check-ins per user.
- **Menu views,** by app, web, embed or API.
- **Demographics.**
- **Subscribers.**
- **Popular and top-rated beers.**
- **Nearby Stats:** what's trending around Waynesboro.
- **Exports:** CSV.
- **Data timing:** Eastern Time, with a lag of up to one day.

---

## 8. Users and permissions

- **Adding users.** Click your name (top right) → **Manage Users** → invite by email.
- **Seat limit.** **Essentials allows up to 5 users.**
- **The owner.** Bart, as Primary User, controls billing and users.
- **Permission toggles,** set per user:
  - Manage Members
  - Menus
  - Events
  - Print, digital and embed menus
  - Website
  - Announcements
  - Analytics
  - Location details
  - Billing
- **Recommended for bar leads.** Menus and Announcements only.

---

## 9. Brewery page vs venue page (we have both)

### Two separate pages
- **Brewery page.**
  - Lives at untappd.com and covers Basic City Beer Co as a producer.
  - Holds every beer we make and every check-in of them anywhere.
  - Managed from untappd.com/login → "Is this for a brewery account?" → Yes.
- **Venue page.**
  - The Eastside taproom, managed in UTFB (business.untappd.com).
  - Holds menus, events, subscribers and on-site check-ins.
- **They can't be merged.**

### Fixing a beer's details
- **Always on the brewery page.** Fix ABV, description and labels there, so every bar carrying our beer is corrected.
- **Not in UTFB.** UTFB overrides only change our own menu.

### Brewery Beer Management
- **The tools:** Add, Edit and **Merge** duplicates (an admin reviews merges in 24–48 hours).
- **Don't use Delete.** It locks the beer until an admin releases it.

### Distribution dashboard
- **What it is.** The Beer Distribution / Brewery Stats dashboard shows where our beers are poured and checked in.
- **Plan.** It's a **Premium** feature.

---

## 10. UTFB mobile app (iOS and Android)

- **Menus:**
  - Swipe left on a menu to publish, unpublish, duplicate or delete it.
  - Add beers, set tap numbers, and add containers.
  - Swipe left on an item to **Move, Replace or Delete** it.
- **Digital boards.** Change menus and design remotely.
- **Events and insights.** Create events; view insights.
- **Check-ins.** Toast and comment.
- **Printing.** Print menus from the app.
- **Web only:** Menu History.

---

## 11. UTFB API reference (for automation)

- **Base URL:** `https://business.untappd.com/api/v1`
- **Authentication.** HTTP Basic with `email:token`.
  - A **read-only** token is enough for website and display use.
  - A **read & write** token is needed for changes.
  - Tokens are under **API Access**.
- **Plan.** The help center lists the official API as **Premium**. **[Verify]** We're on Essentials, but API Access appears in our nav.
- **Rate limits.** No published numbers; throttle calls.

### Key endpoints
| Purpose | Call |
|---|---|
| Our account | `GET /current_user` |
| Menus with full tree | `GET /menus/97291?full=true` |
| Sections (including On Deck) | `GET /menus/:id/sections?include_on_deck_section=true` |
| Items in a section | `GET /sections/528496/items` |
| Item containers and prices | `GET /items/:id/containers` |
| Search the Untappd database | `GET /items/search?q=` |
| Add a beer | `POST /sections/:id/items` with `type=beer` and `untappd_id` |
| Tap it (On Deck → live) | `PATCH /items/:id/move` with `section_id` |
| Set a tap number | `PATCH /items/:id` with `tap_number` |
| Sort by tap number | `PATCH /sections/:id/items/sort?sort_by=tap_number` |
| Add a container | `POST /items/:id/containers` with `container_size_id` and `price` |
| Publish | `POST /menus/:id/publish` |
| Announcement | `POST /locations/:id/menu_announcements` (period: now, once or weekly) |
| Events | `POST /locations/:id/events` |
| Check-ins | `GET /locations/:id/checkins` |
| Insights | `GET /locations/:id/insights/top_beers`, `/checkins_over_time`, and others |
| Restore from history | `POST /historical_items/:id/restore` with `section_id` |

> ⚠️ **`PUT /locations/:id/menus` (bulk upsert) DELETES anything you leave out of the payload.** Never use it for small edits.

### Useful IDs for us
| What | ID |
|---|---|
| Location (UTFB) | 4819 |
| Beer on Tap! menu | 97291 |
| Draft section | 528496 |
| Packaged Beer menu | 94252 |
| 6-pack 12oz section | 511476 |
| 4-pack 16oz section | 511477 |

---

## 12. Plans: Essentials (ours) vs Premium

| | Essentials | Premium |
|---|---|---|
| Users | 5 | Unlimited |
| Non-beer items | 20 | Unlimited |
| Wine, spirits and RTD database | – | ✓ |
| CSS on print and digital menus | – | ✓ |
| API | – | ✓ |
| Brewery distribution stats | – | ✓ |

- **Upgrading.** Use the "Upgrade to Premium" button on the dashboard.

---

## 13. Support and sources

- **Contacting support.** Email business@untappd.com, or use Help → Contact Support in UTFB. Include the account email, the location (4819) and a description of the issue.
- **Help Center.** https://help.untappd.com/hc/en-us/categories/360001962551
- **API docs.** https://docs.business.untappd.com/
- **Key articles:**
  - Menu not visible: https://help.untappd.com/hc/en-us/articles/33450730371092
  - Prices: https://help.untappd.com/hc/en-us/articles/360034120811
  - On Deck updates: https://help.untappd.com/hc/en-us/articles/47943107356564
  - Bulk actions: https://help.untappd.com/hc/en-us/articles/4408392848020
  - Favorite containers: https://help.untappd.com/hc/en-us/articles/21561445091604
  - Menu History: https://help.untappd.com/hc/en-us/articles/4801857733268
  - Mobile menus: https://help.untappd.com/hc/en-us/articles/29662583938836
  - Multiple TVs: https://help.untappd.com/hc/en-us/articles/19297669123476
  - Toast sync: https://help.untappd.com/hc/en-us/articles/43674169212692
  - Square FAQ: https://help.untappd.com/hc/en-us/articles/42491730039700
  - Premium vs Essentials: https://help.untappd.com/hc/en-us/articles/13225116244116
  - Brewery vs venue pages: https://help.untappd.com/hc/en-us/articles/49383456928276
