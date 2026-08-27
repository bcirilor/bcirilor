## Bruno Cirilo Rocha

Civil engineer (CREA-PR 208770/D) who tests and documents what gets built, on site
and in software. Eight years between construction sites and technical documentation,
now writing the automation that used to be manual work.

Based in Cascavel, Parana, Brazil. Open to remote work.

### Testing and BIM

**[qa-automation](https://github.com/bcirilor/qa-automation)**
Playwright suite against the Sauce Labs demo app. 33 tests on Chromium, Firefox and
Mobile Safari, 99 runs per pipeline, GitHub Actions on every push. Six of the ten
login tests are failures rather than successes, because a form that logs you in is
the easy part. Includes a decision log and the bug I found: the cart reaches the
order confirmation with zero items.
`Playwright · TypeScript · GitHub Actions`

**[ifcqt](https://github.com/bcirilor/ifcqt)**
Quantity takeoff and model consistency checks straight from an IFC file, with no
Revit licence. Eight checks written as the code version of what clash coordination
does before anyone opens a viewer: the element with no quantity that silently leaves
the total, the opening that lost its host wall, the beam outside every storey.
`Python · IfcOpenShell · pytest`

### Applications

**[google-ads-autopilot](https://github.com/bcirilor/google-ads-autopilot)**
Audit and optimization for Google Ads accounts, with human approval between the
recommendation and the change. An action allowlist, a ceiling of plus or minus 30%
per budget change, a 7 day cooldown per target, and an append-only log that makes
undo mean restoring the previous value rather than guessing it.
`Python · GAQL · Service Account`

**[doxa-worship-platform](https://github.com/bcirilor/doxa-worship-platform)**
Multitrack audio in the browser: 8 stems in sync, per track mixer, arrangement
editor, synced chord charts. Decoded on demand in 3 second blocks through WebCodecs,
because 8 stems of 5 minutes take 400MB of RAM and that kills the tab on a phone.
`Next.js · TypeScript · Supabase RLS · WebCodecs · OPFS`

**[tazza-site](https://github.com/bcirilor/tazza-site)**
Company website in production. Lead capture with rate limit, honeypot, allowlist
validation, and an insert that retries without the phone column when the migration is
late, because a late migration should not cost a lead.
`Next.js · TypeScript · Supabase`

The three application repositories are excerpts. The full products are private.

### Where I come from

Reading executive drawings, checking formwork and rebar before the pour, supervising
SPT boreholes under NBR 6484, building cost estimates on SINAPI. The habit that
carried over: find the defect before it becomes expensive, then write it down so the
next person does not repeat it.

Revit and BIM coordination, hydraulic and structural clash detection, safety
regulations, ISO 9001.

### Reach me

[LinkedIn](https://www.linkedin.com/in/brunocirilorocha) · 1bcirilor@gmail.com
