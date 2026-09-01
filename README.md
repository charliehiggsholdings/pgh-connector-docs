# PGH Pest Control — Claude Connector

Check prices, find a real appointment slot and book a pest control visit with
**PGH Pest Control** directly from your AI assistant. You pay securely on a Stripe
checkout page — your assistant never takes payment details.

**Connector URL:** `https://pgh-booking-mcp.charlie-4be.workers.dev/mcp`
**No sign-in required.** Works with Claude custom connectors (web, Desktop, Mobile, Claude Code).

## What it can do

| Tool | What it does |
|---|---|
| **List PGH services and prices** | The live service list — wasp and hornet nests, rodents, bed bugs, fleas, moths, cockroaches, squirrels, moles, bird and badger work, surveys and proofing — with visit counts, from-prices including VAT, and the questions each service needs answered. Read-only. |
| **Check PGH appointment availability** | Real diary availability for your postcode and dates. Some services are only bookable within travelling distance, and availability reflects which technicians can actually attend. Read-only. |
| **Reserve a PGH appointment** | Holds your chosen slot and returns a Stripe checkout link for **you** to pay. The exact price including VAT is confirmed before you pay. If you don't pay, the slot is released automatically at no cost — there is nothing to cancel. |

## How a booking goes

1. Tell your assistant what the problem is and where you are. It reads PGH's live
   service list and asks the same qualifying questions the website asks.
2. It checks genuine diary availability for your postcode and offers you real slots.
3. You're shown the exact price (including VAT) and PGH's
   [terms](https://book.pghpestcontrol.co.uk/booking/terms). If you're happy, the
   assistant reserves the slot and hands you a Stripe checkout link.
4. **You pay on Stripe's page** — the assistant never sees or handles card details.
   Your confirmation email arrives from PGH once payment completes, and the visit is
   in the technician's diary.

## Important notes

- Payment always happens on Stripe, completed by you. Nothing is charged through the
  assistant, and no card details are ever requested in the conversation.
- An unpaid reservation releases itself automatically — you are never charged for
  abandoning a booking part way.
- Some jobs can't be priced online (larger or unusual infestations, protected species,
  commercial contracts). The connector says so and points you to a survey or a phone
  call instead of guessing a price.
- Cancellations, refunds and rescheduling are handled by the PGH office, not by the
  assistant — call **01483 273478**.
- Data handling: your answers, postcode and contact details go to PGH's own booking
  systems — the same ones behind [book.pghpestcontrol.co.uk](https://book.pghpestcontrol.co.uk/).
  See the [privacy policy](https://pghpestcontrol.co.uk/privacy-policy/).

## Support

Call **01483 273478** or use the contact options at
[pghpestcontrol.co.uk](https://pghpestcontrol.co.uk/contact/).
