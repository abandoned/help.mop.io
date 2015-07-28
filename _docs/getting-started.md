---
layout: page
title: Getting Started
excerpt: >
  By design, Mopio is effective and easy-to-use. We want you to get the best out of the app from the moment you sign up.
---

You have activated your account and may be wondering what will happen next.

In the background, Mopio will start syncing your existing inventory and tracking changes on Amazon in real time. As changes come in, we'll review your listings and make small adjustments to maintain or improve your competitive position.

Mopio has sensible defaults. We expect that most sellers can start using Mopio without any further setup or change. We tuck away the complexity of dynamic pricing behind intuitive business goals.

You can tweak how Mopio behaves in two ways:

1. You can define an app-wide strategy [on the Settings page][settings].
2. You can define specific strategies for individual listings.

The latter take precedence over the app-wide strategy.

## App-wide strategy

Click on **Settings** in the top navigation bar to go to the **Strategy** page:

![foo](/images/getting-started-1.png)

Here you will start by setting a **business goal**. The default goal is to *win the Buy Box*. You can change this to *match* or *beat the lowest price*. These seem to work better if you are selling mostly in the Media categories.

If you choose to compete for the lowest price and sell used items, you can tweak your strategy to ignore listings in worse condition.

You may also adjust the conservative default values we have set for **Maximum Allowed Discount (MAD)** and **Maximum Allowed Markup (MAM)**. These percentages help us calculate a floor and ceiling for your listings based on their original prices. A MAD of 10% means that something originally listed for $50 will always remain above $45.

Finally, you have an option to set an **absolute floor**. This comes in handy if you have a very aggressive MAD but want to ensure you never sell below a certain price. An absolute floor of $2 means that your listings will always be priced above $2, even if MAD would have pulled it further below.

## Listings

To finetune how a listing is repriced beyond the app-wide settings, go to **Listings**, find and click on the listing, and go to **Edit**:

![foo](/images/getting-started-2.png)

Here you can define a **business goal** for that listing. This will override the app-wide goal.

Similarly, you can set a **floor** and **ceiling** to define the boundaries within which our algorithm should operate. These will override what we would have calculated using your MAD, MAM, and absolute floor settings.

If you set a floor of $25 and ceiling of $30 for a listing, we'll work within those limits only, choosing what we think is the optimal price point. If competing offers fall below your floor, we'll stop there. Conversely, we'll never exceed your ceiling even if there is no competition.

If you would rather tweak your listings individually, you can turn off your app-wide strategy by setting both MAD and MAM to 0%.

Finally, if you want to update a large number of listings, you will want to import a flat file or use our API instead of editing them individually by hand.


[settings]: https://www.mop.io/settings/strategy
