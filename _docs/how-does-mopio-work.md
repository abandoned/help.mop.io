---
layout: page
title: How does Mopio work?
permalink: /how-does-mopio-work/
---

Mopio reprices your listings in **real time**. This means it reprices as soon as a competing seller changes the price of their offer.

Let's say you are listing at *$20* and another seller reduces their price to *$19.80*. Within seconds, Mopio will reduce your price to *$19.79* and send a price update to Amazon. If the other seller then raises their price to *$20.10*, we'll raise yours to *$20.09*.

## Limits

Each listing has a floor and ceiling price, which are determined by the [relative margin][margin] and optional [absolute floor][floor] you define in the settings. Mopio will never price a listing below its floor or above its ceiling. In the above example, if your floor were *$19.85*, Mopio would stop there instead of lowering the price to *$19.79*.

## Rules

We tuck away the complexity of dynamic pricing behind a simple goal: to win the Buy Box and thereby to maximise your sales. Under the hood, we follow a few simple rules:

1. We only compete against listings who are eligible for the Buy Box. There's one exception: If your listing is not eligible, we'll price against all listings.
2. We price within the same condition category. If you're listing a new item, we only price against other new items.
3. We beat the competing offer by the smallest possible monetary value. There's one exception here: If we feel the other seller is pricing in real time as well, we cool off the race by **matching** instead of beating the competing price.


[margin]: /relative-margin/
[floor]: /absolute-floor/
