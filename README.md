Zeni Vault - Final (Ready to deploy on Vercel)
--------------------------------------------

Quick steps to deploy:
1. Install dependencies: `npm install`
2. Set environment variables on Vercel (see .env.local.example)
3. Push to GitHub and import to Vercel, or upload folder directly.
4. Redeploy on Vercel.

Required env vars (Vercel):
  SMTP_USER - zenivault5@gmail.com
  SMTP_PASS - Gmail App Password
  ADMIN_EMAIL - zenivault5@gmail.com
  NEXT_PUBLIC_WHATSAPP_NUMBER - 27824238988
  NEXT_PUBLIC_SHEET_ID - your Google Sheet ID (1UZP5l-...)
  FIREBASE_API_KEY - Firebase client SDK key
  FIREBASE_AUTH_DOMAIN - Firebase auth domain
  FIREBASE_PROJECT_ID - Firebase project id
  FIREBASE_APP_ID - Firebase app id
  ADMIN_PASSWORD - admin password (for admin endpoint)
