# UPI Transfer UI — Interactive Demo

This is a mobile-first front-end prototype inspired by the supplied reference screenshots.

## Files
- `index.html`: interactive home page and demo flows
- `payment-sent-chime.wav`: original four-note notification sound
- `payment-sent-chime.mp3`: compressed sound copy (included if MP3 encoder was available)

## Home-page interactions
- Profile: profile/help/settings sheet
- Search: filters available demo features
- Notifications: notification and sound preview options
- Scan QR: demo scanner; sample QR opens a recipient and amount screen
- Pay Anyone: search/select sample recipients
- To Bank & Self A/c: sample bank form and amount entry
- Balance & History: simulated wallet balance and local demo transaction history
- Recharge & Bills / View All: mobile, credit card, electricity, EMI, DTH and broadband demo forms
- Jio card: opens mobile recharge form
- Gold/loan/rewards cards: informational demo pages
- Payment flow: amount, optional message, explicit demo confirmation, receipt, original chime, local simulated wallet/history updates

## Deploy
Upload the files to GitHub and create a Render **Static Site**. Publish directory: `.`. No build command is required.

## Important
This is a simulation only. It does not connect to a bank, UPI, mobile operator, biller, loan provider, or gold service. No real payment or recharge occurs. The success receipt and balance are simulated. Never enter a real UPI PIN.
