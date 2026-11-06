SPINIX MANIA — PROJECT HANDOFF
================================

Included:
- index.html       Main responsive website, five box tiers, Paybill information, FAQ and winner placeholder.
- login.html       Supabase email/password sign-up, sign-in and password reset.
- account.html     Customer session page with sign-out. It does not invent balances or transactions.
- admin.html       Existing admin preview only; NOT a secure production admin console.
- CNAME            spinixmania.co.ke

IMPORTANT CONFIGURATION
-----------------------
The Supabase URL and publishable key are set in login.html and account.html:
URL: https://lkhkbsquoghfdlfcunwx.supabase.co
The same project URL must be used by any backend functions.

PAYBILL DETAILS PROVIDED BY THE OWNER
-------------------------------------
Business Paybill: 4043233
Account reference: customer's phone number

PAYMENT STATUS
--------------
The website displays Paybill instructions, but does NOT collect or automatically verify
Paybill payments. Do not accept payments for box entries using this front end. A production
integration needs a secure server-side Daraja C2B confirmation/validation endpoint or
approved STK Push endpoint, callback validation, transaction deduplication, database updates,
and end-to-end production tests. Never put Daraja consumer secrets, passkeys or Supabase
service-role keys in browser code or GitHub.

LEGAL / RESPONSIBLE LAUNCH
--------------------------
The box prices currently shown (Bronze 200, Silver 500, Gold 1,000, Platinum VIP 2,000,
Black Diamond 5,000 KSh) are carried forward from the project draft and need owner confirmation.
Because this concept charges for a chance-based prize, obtain Kenyan regulatory advice and any
required Gambling Regulatory Authority licence/approval, plus payment-provider approval, before
enabling paid entries, draws or prize payments. Publish official rules, eligibility, odds,
prize values, refund/complaint process and privacy terms.

DEPLOY
------
1. Keep a backup of the current GitHub repository.
2. Replace the repository files with the contents of this folder.
3. Keep CNAME in the repository root.
4. GitHub Pages should publish from the repository root / main branch.
5. Test on the custom domain: homepage, sign-up, email confirmation, sign-in, password reset,
   account page and sign-out.
6. Do not enable paid participation until secure backend, legal approvals and live payment
   reconciliation are complete.

This package is an improved front-end and authentication handoff, not a claim that live
payments, admin controls, paid draws or prize fulfilment are already operational.
