---
title: Support
permalink: /support/
---

# DoNotBuy — Support

Need help with DoNotBuy? Email us:

**[radioideaxp@gmail.com](mailto:radioideaxp@gmail.com)**

We aim to reply within **2 business days**.

When reporting a bug, please include:

- Your iPhone model and iOS version
- The DoNotBuy version (Settings → About at the bottom of the screen)
- A short description of what you expected vs. what happened

---

## Frequently asked questions

### How do I cancel my Premium subscription?

Subscriptions are managed by Apple, not by us. Open the App Store, tap your profile picture in the top right, tap **Subscriptions**, then select **DoNotBuy** and tap **Cancel Subscription**. You can also go to **iOS Settings → [your name] → Subscriptions**.

You will keep Premium access until the end of the current billing period.

### How do I restore a previous purchase on a new device?

In the App Store, sign in with the same Apple ID you used for the original purchase. Open DoNotBuy, go to **Settings → Premium**, and tap **Upgrade to Premium** to open the paywall. Tap **Restore Purchases** at the bottom of the paywall.

### How do I get a refund?

Refunds are handled by Apple, not by us. Visit <https://reportaproblem.apple.com>, sign in with your Apple ID, find the DoNotBuy charge, and request a refund.

### Why am I not getting geofence alerts near stores I added?

Check the following:

1. **iOS Settings → DoNotBuy → Location** is set to **Always**. "While Using" is not enough for background geofencing.
2. **Notifications** are allowed for DoNotBuy.
3. **Low Power Mode** is off. iOS suppresses background activity in Low Power Mode.
4. **Precise Location** is enabled.
5. You are within ~100 meters of the store. iOS controls geofence accuracy and may need a few minutes to register your entry.

If alerts still don't fire after checking the above, email us with your iOS version and we'll help debug.

### Can I export my data?

Currently no. All your data lives on your iPhone in the iOS sandbox, and is backed up via iCloud if you have iCloud backup enabled. We are evaluating CSV export for a future release — if this is important to you, let us know.

### How do I delete all my data?

Open DoNotBuy, go to **Settings**, scroll to the bottom, tap **Reset All Data**. This deletes every store, item, check-in, goal, and notification setting from your device. You can also just delete the app — iOS will wipe everything in its sandbox.

### Where is my data stored?

On your iPhone, in the iOS sandbox. We do not have any backend that stores your data. The only data that leaves your phone is the pseudonymous identifier sent to RevenueCat to manage your subscription — see our [Privacy Policy]({{ '/privacy/' | relative_url }}) for full details.

### I have a question that's not answered here

Just email us: **[radioideaxp@gmail.com](mailto:radioideaxp@gmail.com)**. We read every message.

---

[Privacy Policy]({{ '/privacy/' | relative_url }}) · [Terms of Service]({{ '/terms/' | relative_url }})
