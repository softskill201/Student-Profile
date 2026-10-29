# Namami Digital Skills Academy — Fees Manager (Starter)

A local-first browser app starter for student admissions, payment/installment entry, receipts, reports, course setup, and separate Admin/User accounts.

## Live page
https://softskill201.github.io/Student-Profile/

## First-time use
1. Open the page and create the Admin account with a strong, unique password.
2. Log in as Admin.
3. Open **User Accounts** to create separate usernames and passwords for User 1 and User 2.
4. Admin controls course fees, agreed student fees, discounts, and accounts. Data-entry users can add student profiles and payments but cannot change fees/discounts or edit/delete records.
5. Download backups regularly and keep them private. Never commit backups or student photos to this public repository.

## Local data and offline use — important
- Student records, payments, and photos are stored in the current browser profile's local storage. This app does not upload them to GitHub.
- For offline use, download `index.html` and open it in the same browser. The live GitHub Pages link needs internet to load initially.
- Browser storage can be lost if browser data is cleared, the profile changes, or the device fails. Back up regularly and test restoring backups.
- This is a starter, not a hardened secure accounting system. Browser-only passwords are not encrypted authentication, and a technically skilled person with access to the device can inspect or alter local data. Do not treat it as strong access control on an untrusted/shared computer. For stronger protection, use a desktop app with an encrypted database and OS account permissions or a properly authenticated server.
- Avoid entering Aadhaar or other sensitive data until the local device is secured and the backup process is tested.

## Included starter features
- First-run Admin setup and separate Admin / data-entry accounts
- Student profiles and course-wise generated IDs
- Course fee and per-student agreed fee / discount (Admin only)
- Payment and installment history, payment method/reference, received-by username
- Fee receipt and A4-style student fee report printing
- Local JSON backup and restore
- Course setup and basic dashboard/search

## Current limitations
- This is an initial version; test with dummy records first.
- BCC installment guidance is shown as 10% / 20% / 20% / 50%; this starter does not automatically create a full installment schedule.
- Local browser passwords are not cryptographically protected. Client-side role checks are not a substitute for hardened security.
- Use fake data while testing, then make a verified backup before entering actual student records.
