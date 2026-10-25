---
layout: default
title: "Privacy Policy"
---

# Privacy Policy — Bodycount

**Version**: 1.0  
**Last updated**: 25 October 2026  
**Data controller**: Benjamin Merlet, sole trader (auto-entrepreneur), France  
**Contact**: contact@shadowappstudio.com

*Version française : [Politique de confidentialité](politique-confidentialite.html)*

---

## 1. In short

- **Your intimate data stays on your phone.** Partners, dates, ratings, comments, photos, cities and preferences are saved only on your device. The Publisher has no access to them, and the App sends them neither to its servers nor to Google.
- **An account is only created for Premium** (email address, password, month and year of birth).
- **The free version shows an advertising banner** (Google AdMob). Ads are not personalised. In the European Economic Area, the United Kingdom and Switzerland, a form first asks for your consent.
- **Premium shows no ads at all**: the advertising module is not even started.
- **The App is for adults only** (18 and over).

---

## 2. Who is responsible for your data?

Bodycount (the "App") is published by **Benjamin Merlet**, a sole trader based in France (the "Publisher"). The Publisher is the data controller for the data described below, except for what Google and Stripe process for their own purposes (see §3.3 and §3.4).

For any question, or to exercise your rights: **contact@shadowappstudio.com**.

---

## 3. Data processed, purposes and legal bases

### 3.1 Data you enter in the App

This data concerns your intimate life and is therefore particularly sensitive: partners' names or nicknames, ratings, comments, size, sex, ethnicity, practices ("kinks"), city, dates and durations of encounters, photos.

- It is stored **only on your device**, in the App's private storage.
- The Publisher **does not collect it, cannot read it and does not pass it to anyone**. The App sends none of this data to Google, Stripe or any other third party.
- Access to the App is protected by a **4-digit PIN**; only its hash (SHA-256) is kept on the device.
- The **camera** and the **gallery** are used only when you add a photo; the photo is copied into the App's private storage.
- It is excluded from Android's automatic backups (see §9).

### 3.2 Premium account (server)

| Data | Why | Legal basis |
|---|---|---|
| Email address (lower-cased) | Create and identify your account, log you in, link your subscription | Performance of a contract (Art. 6(1)(b) GDPR) |
| Password, kept only as a hash (bcrypt) | Authentication | Performance of a contract |
| Month and year of birth | Check that you are 18 or over | Legitimate interest in keeping the App for adults (Art. 6(1)(f)) |
| Chosen language | Show the App in your language | Performance of a contract |
| Stripe customer identifier, subscription status and dates | Manage the subscription and its renewals | Performance of a contract |
| Account creation date | Account management | Performance of a contract |

A login token (valid for 30 days) is stored on your device. The server is hosted by Railway (United States).

### 3.3 Payment (Stripe)

Premium is paid on a **page hosted by Stripe**. Your card details are entered with Stripe and are **never accessible to the Publisher**. The Publisher sends Stripe your email address to create your customer record. Stripe then processes your payment data as a payment service provider, under its own privacy policy: <https://stripe.com/privacy>.

### 3.4 Advertising (Google AdMob) — free version only

The free version shows a banner served by **Google AdMob** (Google Ireland Limited for the European Economic Area, Google LLC elsewhere). To serve it, Google's advertising module automatically collects from your device:

- your IP address;
- the Android advertising ID (or an app-specific identifier if you have disabled it);
- information about the device and the App: model, Android version, language, screen size, App version;
- ad events: display, click, loading error.

What this means:

- **Ads are not personalised**: they are not targeted using your interests, and the App restricts ad content (no ads aimed at an adult audience).
- **We pass no data entered in the App to Google** (partners, dates, photos, ratings, cities, etc.).
- However, the mere fact that Google receives technical information from this App lets it know the App is installed on your device. If that bothers you, switch to Premium: no data is then sent to Google for advertising.
- Google acts as a **separate data controller** for its advertising and security purposes. See <https://policies.google.com/technologies/partner-sites> and <https://policies.google.com/privacy>.
- **Legal basis:** your **consent** (Art. 6(1)(a) GDPR and the ePrivacy Directive), collected through a Google form in the European Economic Area, the United Kingdom and Switzerland. In other regions, the legitimate interest in funding the free App, in compliance with local law.

### 3.5 Map and location (Premium)

The Map screen asks for access to your **approximate location**. It is used only to centre the map on you, **on your device**: it is not sent to the Publisher. Displaying the map uses **Google Maps**, which receives technical information (IP address, device, displayed area) under <https://policies.google.com/privacy>. You can refuse or withdraw the permission in Android settings; the map is then unavailable.

### 3.6 City search (Premium)

When you search for a city for a partner, **the text you type** (and your IP address) is sent to the **Photon** geocoding service, **operated by Komoot GmbH** (Germany), which returns suggestions. Only this text is sent: it is not linked to the partner's name or to your other data. Legal basis: performance of a contract (the feature you use).

### 3.7 Technical logs

The server host (Railway) may record technical logs (IP address, date, request) to keep the service secure and running. The Publisher uses no audience-analytics or crash-reporting tool, other than the advertising module described in §3.4.

---

## 4. Advertising: your choices

- **Consent (European Economic Area, United Kingdom, Switzerland).** A form appears before the first ad. You may refuse: the App stays usable.
- **Change your choice at any time**: *Settings* (gear icon) → **Ad privacy**. This row only appears if your region requires it.
- **Advertising ID**: you can reset or delete it in Android settings (*Privacy* or *Google* → *Ads*, depending on the version).
- **Remove ads**: the Premium subscription removes the banner.

---

## 5. Recipients

| Recipient | Role | Data | Country |
|---|---|---|---|
| Railway | Server hosting (processor) | Premium account data (§3.2), technical logs | United States |
| Stripe | Payment | Email, payment data (entered with Stripe) | United States, European Union |
| Google (AdMob) | Advertising (free version) | Technical data (§3.4) | United States, Ireland |
| Google (Maps) | Map display (Premium) | Technical data (§3.5) | United States, Ireland |
| Komoot (Photon) | City search (Premium) | Typed text, IP address (§3.6) | Germany |

The Publisher does not sell your data and does not share it with any other third party.

---

## 6. Transfers outside the European Union

Railway, Stripe and Google may process data in the United States. Depending on the provider, these transfers rely on the **EU–US Data Privacy Framework** or on the European Commission's **standard contractual clauses**.

---

## 7. Retention periods

| Data | Duration |
|---|---|
| Data entered in the App | On your device, until you delete it or uninstall the App |
| Premium account (§3.2) | As long as the account is active; deleted within 30 days of your request |
| Payment records | 10 years (accounting obligation) |
| Advertising data | As set by Google's policy |
| Advertising consent choice | On your device, until you change it or uninstall the App |

---

## 8. Security

- Exchanges with the server use an encrypted connection (HTTPS).
- Passwords are never stored in clear (bcrypt hash).
- Access to the App is protected by a PIN, and data is kept in the App's private storage, protected by your device's encryption when it is enabled.
- You remain responsible for the security of your phone (screen lock, updates).

---

## 9. Android backup

The App asks Android **not to include its data in automatic backups** (Google account) or in transfers to a new device. Your data therefore stays on this one device.

**As a result, if you change phone or uninstall the App, you lose your local data.** The Publisher cannot recover it.

---

## 10. Your rights

Under the GDPR you have the rights of **access**, **rectification**, **erasure**, **restriction**, **portability** (for your account data) and **objection**, and the right to **withdraw your consent** at any time, without affecting past processing.

- **How to exercise them**: write to **contact@shadowappstudio.com**. The Publisher replies within one month. Proof of identity may be requested if there is doubt.
- **Data in the App**: it is on your device. You view, edit and delete it directly in the App, or by uninstalling it.
- **Data held by Google and Stripe**: contact those companies directly.
- **Complaint**: you may lodge a complaint with the CNIL (the French data protection authority): <https://www.cnil.fr/en/complaints>, or with your local supervisory authority.

---

## 11. Minors

The App is **strictly for adults**. The Publisher does not knowingly collect data about minors. If the Publisher learns that an account belongs to a minor, it deletes it.

---

## 12. Changes

This policy may change, for example if a feature or a provider changes. The version in force is the one published at the address given in the App's store listing, with its update date. Any significant change is flagged in the App.

---

*Last updated: 25 October 2026*
