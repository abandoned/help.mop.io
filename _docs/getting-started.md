---
layout: page
title: Getting Started
excerpt: >
  By design, Mopio is effective and easy-to-use. We tuck away the complexity of real-time pricing behind simple business goals you define.
---

You have activated your account and may be wondering what will happen next.

In the background, Mopio will start syncing your existing inventory and tracking changes on Amazon in real time. It will also tweak your initial prices if necessary.

As changes come in, we'll review your listings and make adjustments to maintain or improve your competitive position. All changes take place within limits you define.

When you first set up your account, we start with sensible defaults. We expect that most sellers can start using the app without any further setup or change. However, if you do, you can tweak how Mopio behaves on two levels:

1. You can define a general business goal for the entire app [on the Settings page][settings].
2. You can define specific goals for individual listings. These will then take precedence over the general goal you defined on the application level.

## Business goal

We start with a general business goal that applies to your entire inventory: for instance, *win me the Buy Box within 3% of my original prices*.

To view or update your goal, click on **Settings** in the top menu and go to the **Strategy** section:

![foo](/images/getting-started-1.png)

Here you'll define what you want to achieve and the relative limits within which Mopio should run.

The default goal is to *win the Buy Box*. You can change this to *match* or *beat the lowest price*. While most sellers will want to win the Buy Box, the latter seem to work better when selling mostly Media. If you choose to compete for the lowest price, you'll have a chance to ignore listings in worse condition.

The limits within which Mopio runs are determined by two parameters: **Maximum Allowed Discount (MAD)** and **Maximum Allowed Markup (MAM)**. These percentage values help us calculate a floor and ceiling for your listings based on their original prices: for instance, a MAD of 10% means something originally listed for $50 will always remain above $45.

Finally, you have an option to set an **absolute floor**. This comes in handy if you have a very aggressive MAD but want to ensure you never sell below a certain price. An absolute floor of $2 means that your listings will always be priced above $2, even if MAD would have pulled it further below.

## Listing goal

To finetune how a listing is repriced beyond the general business goal, you have to edit the listing. Click on **Listings** in the top menu, find the listing, and go to **Edit**:

![foo](/images/getting-started-2.png)

Here you can define a **goal** that is specific to that listing.

Similarly, you can set a **floor** and **ceiling** to define the boundaries within which Mopio should operate. These values will override what we would have calculated using your MAD and MAM.

If you set a floor of $25 and ceiling of $30 for a listing, we'll work within those limits only. If competing offers fall below your floor, we'll stop at your floor. Conversely, we'll never exceed your ceiling even if there is no competition.

## Questions

### How can I reprice only a subset of my inventory?

Turn off your application-wide strategy by setting both MAD and MAM to 0%. Then, add individual floor and ceiling prices to the listings you want to reprice.

### How can I edit listings in bulk?

You can import a flat file or use our API.

[settings]: https://www.mop.io/settings/strategy
