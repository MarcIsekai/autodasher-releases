# Auto-Dasher release notes

## v2.23 (version code 35)
- New: your own timing for the auto actions. Under the Auto-accept switch there is now an Auto-accept delay pair — a Minimum and a Maximum in seconds, anywhere from 2 to 30 — and the same pair under Auto-decline. The app picks a random moment inside your range, so no two offers are handled alike; set both points to the same number for a fixed delay. Dragging Minimum past Maximum pushes Maximum along, so the pair can't cross. Defaults are the old timing (accept 2–4s, decline 5–15s), so nothing changes until you move them. CLOSE offers still get their flat 30 seconds.
- Removed: the Check for Updates button on the System Check page is gone from the Play Store and Safe builds — Google Play (or your download page) handles updates there, and the button did nothing. It stays in this full build, which still updates itself from this page.

## v2.22 (version code 34)
- Correction to v2.21: the separate Shop & Deliver units slider is gone. Shopping and Shop & Deliver are the same thing, so there is one pair of load caps now, side by side: Max items and Max units.
- New: Max items slider, directly above Max units. An item is a product; units are how many of it the order carries ("Shop for 2 items (13 units)"). A card that states more items than your max is a SKIP, same as the other caps. It starts at 200, which is effectively no cap, so nothing changes until you set it.
- The Max total time slider from v2.21 stays exactly as it was.

## v2.21 (version code 33)
- Screenshot fixes (from a tester's night of dashing): offer screenshots now fire only for a confirmed offer card, so browsing DoorDash (earnings, ratings) no longer triggers stray shots — and a real offer's screenshot can no longer be eaten by an earlier one. Back-to-back offers each get their own capture, and a capture that fails once retries instead of giving up.
- New: Max total time slider. Cap an offer's stated total minutes; over the cap is a SKIP, same as the other caps. Off until you set it.
- New: Max units (Shop & Deliver) slider. A units cap of its own for Shop & Deliver offers, independent of the general shopping units cap. Off until you set it.
- The Max units (shopping) slider now runs 1–200 (it used to stop at 20).

## v2.19 (version code 30)
- New in the System Check menu: going-rate and floor-rate sliders. The $1.50 going rate and the $1.00 floor are yours to set now, and the menu warns you if the floor ever crosses the going rate (the CLOSE band disappears when it does). The main screen is unchanged.
- Spanish: pick English or Español in the System Check menu. The whole app, the banners (BUENA / CERCA / PASAR), the spoken verdicts, and the watcher switch together, and the watcher reads Spanish offer cards too, US and metric formats alike.
- Kilometres: a miles/kilometres switch in the same menu. Distances, caps, and rates convert together, so your verdicts come out exactly the same in km.

## v2.16 (version code 27)
- Updates now come from this GitHub repository instead of Google Drive. Same app, same rules, same verdicts; the download address is the only thing that changed. Drive links could stall or make you download twice; these are permanent links that just serve the file.
- If you are updating from v2.14 or earlier, this one update still arrives the old way (through Drive or the file you already use). Every update after this one comes from here.

## v2.14 (version code 25)
- GOOD now requires the going rate: at least $1.50 per mile. $1.00 to $1.50 per mile is CLOSE, under $1.00 is SKIP.
- CLOSE offers get a flat 30 seconds, then they decline themselves. Tap the banner to grab one instead.
- Stacked offers (2 or more stores AND 2 or more dropoffs) are always CLOSE, never auto-accepted. Two stores with one dropoff is one customer with two orders and is judged on the numbers.
- Auto-decline taps both of DoorDash's Decline buttons, the one on the card and the one on the confirm screen.
- One screenshot per offer, taken the moment the offer lands.
