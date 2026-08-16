BCF — Booster Club Financials
Version 1.3 Sponsor Build

Hesperia Football Booster Club

WHAT'S NEW
- Dedicated Sponsors module
- Sponsor/business name, contact, phone, email, sponsorship level, pledged amount, status, event/program, and notes
- Sponsor fulfillment/benefit checklist
- Sponsor totals: pledged, received, and outstanding
- Record Sponsor Payment workflow
- Sponsor payments NEVER post directly to the ledger
- Every sponsor payment goes through BCF's final Verify Before Ledger Change screen
- Sponsor payment status updates from Partial to Paid after verified ledger posting
- Sponsor data is included in BCF backup/restore files
- Startup warning reminds you to confirm that the device has the current books
- Existing PDF/CSV import and verification-first ledger controls remain in place

TESTING
1. Extract this ZIP.
2. Open index.html on your Mac.
3. Open Sponsors from the left menu.
4. Add a test sponsor.
5. Add promised benefits/fulfillment items.
6. Click Record Payment.
7. Confirm that BCF shows the final verification screen BEFORE the ledger changes.
8. Approve the payment and confirm it appears in the ledger and sponsor totals.
9. Create a BCF backup and restore it to confirm sponsor records travel with the books.

PDF IMPORT
This test build uses an online PDF.js reader library. Internet access is required when opening BCF for PDF statement testing.
The generic PDF transaction parser may need to be tuned after testing an actual statement from the Booster Club's bank.

IMPORTANT BCF RULE
Nothing may ever post directly to the official ledger. CSV imports, PDF imports, manual transactions, receipt entries, transaction edits, and sponsor payments must all be verified and explicitly approved first.
