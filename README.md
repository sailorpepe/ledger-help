# Ledger — support and privacy

**The public support page and privacy policy for [Ledger](https://sailorpepe.github.io/ledger-help/),
a free work log for union construction laborers.**

| | |
|---|---|
| **Support** | https://sailorpepe.github.io/ledger-help/ |
| **Privacy policy** | https://sailorpepe.github.io/ledger-help/privacy.html |
| **Contact** | ledger@the-undesirables.com |

This repository holds two static pages and one stylesheet. **The app's source
code is not here** — it is private. Apple requires every app on the App Store to
publish a reachable support URL and privacy policy, and this is where those two
pages live and nothing else.

---

## What Ledger is

A laborer logs a day in twenty seconds — punch in and out, or just type the
hours — and the overtime splits itself using the real rules in the collective
agreement rather than jobsite folklore. Every entry is sealed with a hash
chained to the one written before it, so an entry changed afterwards no longer
matches its seal. Seal times come from the phone's clock, and the seal is not
proof against someone who rebuilds a whole log. A day that ran short asks why,
and says what may be owed under Article 39, which sets a floor for showing up
and getting rained out that most members have never read. Most of it is written
for Will and Grundy counties, so the app labels it that way and points the
member to his steward.

It also reads the filings a union and its benefit funds are required by federal
law to publish — LM-2 reports to the U.S. Department of Labor, Form 5500 reports
under ERISA, and federal court dockets — and puts them in plain English and
plain Spanish.

It is free, it has no account, and the app never sends anything a member logs
off their phone. There is no server to send it to. If the phone backs itself up
to iCloud or a computer, that backup may include Ledger's data, the same as any
app's. That copy is the member's, in their own iCloud account or on their own
computer, and we never receive it.

Built by a union laborer.

## Why the privacy policy is short

Because the honest answer is one word. No account, no sign-up, no server, no
analytics, no advertising, no third-party SDK. Everything a member enters is
written to storage on their own phone, and the app sends none of it anywhere.
We could not produce anyone's log if we were asked for it, because we have
never had it.

## Independence

Ledger is published by **The Undesirables LLC**. It is **not** affiliated with,
endorsed by, sponsored by or connected to LIUNA, any local union, district
council, benefit fund, or employer. Union names appear only as they appear in
the public records the app cites.

The app is not legal or financial advice. Lawsuits it surfaces are filed claims
taken from public dockets — allegations until a court says otherwise — and every
one links to the record. The list is dated as of its last refresh, and a match
against a member's log is a match on the name, to check against the docket.

## Building

There is nothing to build. Four files, served as-is by GitHub Pages:

```
index.html      support page
privacy.html    privacy policy
style.css       one stylesheet, no scripts, no web fonts
icon-256.png    the app icon
```

No dependencies, no build step, no JavaScript. It has to open on a job
trailer's signal, on a phone somebody bought in 2019.

## Licence

Copyright © 2026 The Undesirables LLC. The page content and the Ledger name and
icon are all rights reserved. Published here so the URLs stay reachable, not as
an invitation to reuse.
