# MoneyGuard app releases

This is where we keep track of changes to the **MoneyGuard app**: what was asked for, why, what we decided, and how far each change has got.

It is written for the product and management teams. Each change has its own page, written in plain language.

> MoneyGuard is still in testing. No version is live for the general public. New app versions are shared through Google Play's testing tracks.

## Changes

Newest first.

| ID | What changed | Where it stands | App version | Last updated |
| --- | --- | --- | --- | --- |
| [CR-001](changes/CR-001-onboarding-buttons-small-phones.md) | Sign-up buttons were hidden on smaller phones | Ready to release (not yet on Google Play) | 1.0.10 | 21 Oct 2026 |

## What "where it stands" means

| Status | Meaning |
| --- | --- |
| Requested | Someone has asked for this. No decision yet. |
| Approved | We have agreed to do it. |
| In progress | The team is building and testing it. |
| Ready to release | The final app version is built and checked, but not yet on Google Play. |
| With testers | Published on a Google Play testing track. |
| Confirmed | Someone has checked it works on a real phone. The page says who checked and what. |
| Declined | We decided not to do it. The page says why. |
| Replaced | Covered by another change. The page links to it. |

A change only counts as **Confirmed** after someone has tried it on a real phone. Automated tests alone don't count.

## Writing a page

- **One page per change.** Update it as the change moves along, rather than starting a new one. If something about it changes later (a follow-up fix, say), add a dated note at the bottom of the same page.
- **Plain language.** Write for someone who doesn't work on the code. Describe what customers see and what we did about it. Leave out code, file names and build details. The engineering team keeps those in their own records.
- **No personal details.** Never include customer names, emails, phone numbers, BVNs, account numbers or anything else that could identify someone. Say "two customers" or "a customer on a Samsung Galaxy A32".
- **Only what we know.** Record what was seen, decided or checked, with the date. Write "Not yet" for anything outstanding, and say plainly what hasn't been checked.
- **Numbering.** Pages are numbered in order (CR-001, CR-002, …), and numbers are never reused, even for declined requests. Name the file `CR-NNN-short-title.md` and put it in `changes/`.

Copy [the template](TEMPLATE.md) to start a new page, then add a row to the table above.
