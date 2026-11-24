# Auto-Dasher release notes

## v2.27 (version code 39)
- Daily History now uses YOUR mileage rate. A slider on the history page sets your cost per mile anywhere from $0.10 to $0.76, and every day on the page refigures the moment you move it: expense, actual earned, and cost saved.
- The default is still the federal rate of $0.76 a mile, and the page says which rate it used, federal or yours. Nothing is stored any differently; the rate is applied when the page figures your days, so your existing history picks it up instantly.
- No new permissions in any build. The Play build still has no internet permission at all.

## v2.26 (version code 38)
- Daily History now figures the cost of the miles, at the federal mileage rate of $0.76 a mile. Each day adds an expense line — the taken miles at that rate, and your actual earned: what the taken offers paid minus that expense. A hard day can show a negative actual earned, and it will, honestly.
- The passed side gains a total savings: the driving cost of the miles you did NOT drive by passing those offers, at the same rate. The rate used is printed right on the history page.
- Nothing else changes: the same witnessed-outcome counting, the same 20 days, the same phone-only records. No new permissions in any build — the Play build still has no internet permission at all.

## v2.25 (version code 37)
- New: Daily History. A DAILY HISTORY button on the main screen opens the last 20 days of offers Auto-Dasher handled: how many you took, what they paid and how far they ran, against how many you passed, what they would have paid ("given up") and the miles you saved by passing them. Pay is the offer's stated pay, the figure on the card when you decided.
- Only offers whose outcome the app actually saw are counted: one it accepted or declined itself, one you grabbed off the CLOSE banner, or one where it watched you accept or decline by hand. An offer that disappeared before its outcome isn't counted either way — the page says exactly that, because the numbers are only worth anything if they're honest.
- Private, like everything else in this app: the records live on your phone only. No account, no network, no export — the Play build still has no internet permission at all.

## v2.24 (version code 36)
- The free trial is now impossible to miss (Play Store build): the first time you open the app, a welcome message tells you the 14-day free trial has started and that keeping the app afterwards costs $4.99 once. Under the app name there is now a big TRIAL button counting down the days left, with "Click to purchase for life" printed under it — tap the button any time to buy. It turns red for the last 3 days.
- When the trial ends, a banner at the top of the screen says so and offers the purchase right there. Close it with the X and it simply comes back the next time you open the app, until you purchase. Once you purchase, the button and the banner disappear for good. Your settings are never touched either way.
- The same banner also appears over the DoorDash app itself when an offer comes in after the trial has ended, right where the verdict banner would normally be — so you can stop and either purchase or stop using the app. Its X closes it for that offer only; it returns on the next offer, and purchasing makes it disappear for good. While the trial is over the watcher stays paused: no verdicts, no auto-accept or auto-decline, no screenshots — the purchase banner is the only thing that shows.

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
