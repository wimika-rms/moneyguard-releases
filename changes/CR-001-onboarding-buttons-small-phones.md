# CR-001 — Sign-up buttons were hidden on smaller phones

**Where it stands:** Ready to release (not yet on Google Play) · **App version:** 1.0.10 · **Last updated:** 21 Oct 2026

## What was reported

On 21 October 2026, two customers said they couldn't continue signing up because they couldn't find the button to move on to the next step.

## What we found

On smaller phones, such as the Samsung Galaxy A32, the main button on some sign-up steps sat below the bottom of the screen. Customers had to scroll down to find it, and some didn't realise they could.

- **Always affected:** the *Choose plan* and *Protection summary* steps.
- **Also affected when the phone's text size is set larger:** the *Checkout* and *Sign up* steps.
- **Not affected:** the other sign-up steps.

One customer on a Galaxy A32 went back and forth between the same steps about ten times and never reached payment.

Our existing tests missed this because they used a larger screen and scrolled to each button automatically.

## What we decided

Decided on 21 October 2026:

- On the four affected steps, the main button now stays fixed at the bottom of the screen, so it is always visible.
- We added an automatic check that tests every sign-up step on small screens. It fails if a main button is out of view, so this problem can't quietly come back.

**Not changed:** we don't override the phone's own text size setting, and the other sign-up screens weren't redesigned, because they were already fine.

## Progress

| Step | Done? |
| --- | --- |
| Built and tested by the team | Yes, 21 Oct 2026 (all automated tests passed) |
| Final release version made | Yes, 21 Oct 2026 (version 1.0.10) |
| On Google Play for testers | Not yet |
| Checked on a real phone | Not yet |

## Not yet checked

- We have only tested it on simulated small screens, not yet on a real phone.
- We haven't tried a customer with a long list of bank accounts on the *Select accounts* step. That step looked fine in testing.

## History

- 21 Oct 2026 — Two customer reports received. We looked into it and confirmed the problem.
- 21 Oct 2026 — Fix approved and built.
- 21 Oct 2026 — Final release version 1.0.10 made and checked. Waiting to be published to Google Play testers.
