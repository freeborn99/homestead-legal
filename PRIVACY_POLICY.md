# Privacy Policy — Homestead: 3D Farm Tycoon

**Effective date:** 16 September 2026
**Last updated:** 16 September 2026 (app version 1.4.0)
**App:** Homestead: 3D Farm Tycoon (`com.homestead.farm`)
**Developer:** Casayoung Development
**Contact:** casayoung.dev@gmail.com

This Privacy Policy explains what information the game **Homestead: 3D Farm Tycoon**
("the Game", "we", "us") handles when you install and play it on an Android device. It
applies to the Game itself and not to any other service.

---

## 1. Summary

- Your farm progress is saved **on your own device** by default. You do not need an account
  and the Game works fully offline.
- You may **optionally** sign in with Google to back your farm up to the cloud and compare
  stats with other players. If you never sign in, we receive nothing at all — see section 4.
- We do **not** collect your phone number, contacts, photos, files or precise location, and
  we do not ask you to create a username or password.
- The Game shows **optional rewarded video ads** through Google AdMob. To do that, Google
  may collect device and advertising information as described in section 3.
- You can erase everything the Game stores by clearing the app's storage or uninstalling it,
  and you can delete your cloud backup and profile at any time (section 9).

## 2. Information stored on your device

Homestead is built to work offline. The following is written to your device's local app
storage (Android `localStorage`) and stays there:

- Game progress: buildings and layout, resources (Labor, Coins, Gems, Ribbons), upgrades,
  achievements, reputation, prestige state, seasons, crafting and cargo contracts.
- Settings and preferences: your farm name, audio and UI toggles, tutorial progress.
- A timestamp of your last session, used to calculate offline progress.

This information is **not transmitted to us or to anyone else**. It leaves your device only
if you choose to copy it yourself (for example a device backup you configure).

## 3. Information collected by third parties (advertising)

The Game integrates Google AdMob (Google LLC) to show **optional rewarded advertisements**
(for example 2× production boosts, shopping discounts, express crafting, or gems). Watching
an ad is always your choice; the Game is fully playable without them.

When an ad is requested or shown, Google and its ad partners may collect and process:

- your device's **advertising ID** (Android Advertising ID) and other device identifiers,
- device and app information (model, operating system, app version, language, IP address),
- **approximate** location derived from your IP address,
- how you interacted with the ad (impressions, clicks, completion).

The Game declares the `com.google.android.gms.permission.AD_ID` permission, which Android
requires in order to read the advertising ID. We do not receive your advertising ID
ourselves, and we cannot see your individual ad data — it is processed by Google as an
independent controller. See:

- Google Privacy Policy: <https://policies.google.com/privacy>
- How Google uses information from sites or apps that use our services:
  <https://policies.google.com/technologies/partner-sites>

Google Play Services is also used for app distribution, update delivery and Android
platform integrity, under Google's own privacy policy.

### Your advertising consent (EEA, UK, Switzerland and US state privacy laws)

Where the law requires it, the Game asks for your consent before it requests any ad, using
Google's **User Messaging Platform (UMP)**. On first launch in a region that requires
consent you are shown a consent form, and **no ad is requested and no advertising SDK is
initialised until you have made your choice**. If you decline personalised advertising, ads
are either not shown or served in a non-personalised form, and the Game remains fully
playable.

You can change or withdraw your choice at any time: open the **⚡ Farm Boost Center** in the
Game and tap **"Ad privacy settings"**. This reopens the same privacy options form (Google
requires that withdrawing consent be as easy as giving it).

## 4. Optional Google account and cloud save

The Game is fully playable **without** an account. If you choose to sign in with Google, we
use **Google Firebase Authentication** and **Cloud Firestore** (Google LLC) to offer cloud
backup of your farm. Signing in is optional and can be undone at any time.

If you sign in, the following is stored for you:

- your Firebase **user ID** (a long random identifier, not your name or email),
- the **display name** and **email address** attached to the Google account you sign in with,
  which we receive from Google,
- a **copy of your farm save** (the same progress data described in section 2), so it can be
  restored on another device,
- a small **public profile** used for the optional friends ranking: your farm name, era,
  lifetime Labor, Blue Ribbons, building count and play time. Farm names are limited to 24
  characters, and there is no chat, comment or free-text feature.

What we do **not** do with it:

- we do not sell it, we do not use it for advertising, and we do not share it with anyone
  other than Google as our hosting provider;
- we do not read your save contents for any purpose other than storing them and returning
  them to you;
- your save is protected by security rules so that **only your own signed-in account can read
  or write it**. The friends-ranking profile is readable by other signed-in players; your save
  is not.

Google's handling of Firebase data is described in Google's Privacy Policy
(<https://policies.google.com/privacy>) and the Firebase privacy documentation
(<https://firebase.google.com/support/privacy>).

## 5. How information is used

- **Locally stored game data** is used only to run the Game and to restore your farm when
  you come back.
- **Advertising information** is used by Google to select and measure the rewarded ads
  shown in the Game, to prevent ad fraud, and to pay us for the ad impressions that keep
  the Game free.

## 6. Sharing and selling

We do not sell your personal information. We do not share information with third parties
other than the advertising and platform providers described in section 3, and we do not
transfer your save data to anyone.

## 7. Your choices and controls

- **Personalised advertising:** you can limit ad personalisation in
  Android **Settings → Privacy → Ads**, where you can also reset or delete your advertising
  ID. Google's ad settings are at <https://adssettings.google.com>.
- **Consent choices:** in the Game, open the **⚡ Farm Boost Center → "Ad privacy settings"**
  to change or withdraw your advertising consent at any time.
- **Ads in the Game:** every ad is opt-in. Declining or cancelling an ad never blocks
  gameplay and never charges you anything.
- **Notifications and permissions:** the Game does not request notification, camera,
  microphone, contacts or precise-location access.
- **Purchases:** this version contains no in-app purchases and no real-money transactions.

## 8. Data retention

Locally stored game data remains on your device until you delete it. If you have signed in,
your cloud backup and public profile remain in Firestore until you delete them (section 9) —
we keep them only so that a restore is possible. Advertising data is retained by Google
according to its own policies (see the links in section 3).

## 9. Deleting your data

You are in full control of the data the Game stores:

- **On your device:** Android **Settings → Apps → Homestead → Storage → Clear storage**
  deletes all local game data, or uninstalling the Game removes it entirely. This cannot be
  undone, and because we hold no copy of your local save, we cannot restore it for you.
- **Cloud backup, profile and name reservation (only if you signed in):** tap the **profile
  button in the top bar** (it shows your name once signed in), then **🗑️ Delete cloud data**.
  That erases your stored save, your public ranking profile and your farm-name reservation
  from Firestore immediately. You can also email us at **casayoung.dev@gmail.com** from the
  address on the Google account you used and we will delete them within 30 days. Signing out
  stops all further syncing but leaves the existing backup until you delete it. Full
  step-by-step instructions: <https://freeborn99.github.io/homestead-legal/delete-account.html>
- **Advertising data:** reset or delete your advertising ID in Android
  **Settings → Privacy → Ads**, and use Google's ad settings for ad personalisation.

If you would like help with a data question, email us at **casayoung.dev@gmail.com** and we
will respond as quickly as we can.

## 10. Children's privacy

Homestead is family-friendly and rated **Everyone (PEGI 3 / ESRB E)**. It is not directed to
children under 13 (or the equivalent minimum age in your country), and we do not knowingly
collect personal information from children. The Game has no accounts, no chat, no
user-generated content and no social features. If you believe a child has provided personal
information to us, contact us and we will delete it.

## 11. International users

The Game can be played anywhere. If you are in the European Economic Area, the United
Kingdom, Switzerland, California or another region with data-protection laws, you may have
rights to access, correct, delete or restrict processing of your personal information, and
to object to personalised advertising. Because we do not hold personal information about
you, requests about advertising data are handled by Google through the controls in section
6; we will still help where we can. Our legal basis for the limited processing we take part
in is your consent (for personalised ads, where required) and our legitimate interest in
funding a free game with advertising.

## 12. Security

Game data stays on your device and is protected by Android's app sandbox. Because we do not
collect it, there is no server-side store of player data to breach. Ad transmission
(including any data sent to Google) uses encrypted connections.

## 13. Changes to this policy

If this policy changes, the updated version will be published at this page with a new
"Last updated" date. Material changes will also be noted in the Game's release notes on
Google Play. Continuing to play after an update means you accept the revised policy.

## 14. Contact us

Casayoung Development
Email: **casayoung.dev@gmail.com**

Questions about this policy, your data, or the Game's advertising are welcome.
