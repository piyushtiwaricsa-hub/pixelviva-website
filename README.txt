PIXELVIVA CREATIVE STUDIO — UPDATED STATIC SITE

Files:
- index.html: updated responsive landing page, services, portfolio, pricing, email/Instagram links and WhatsApp enquiry buttons.
- login.html: separate sign-in page UI.
- signup.html: separate account onboarding page UI.

IMPORTANT LIMITATIONS:
1. Login/signup pages are visual front-end forms only. They do not create accounts or authenticate users, and they do not store/send passwords.
2. The supplied downloaded HTML did not contain a working authentication backend or email-confirmation configuration. Therefore email confirmation cannot safely be disabled by editing HTML alone.
3. For real login/signup, connect an authentication provider (for example Netlify Identity if enabled for your site, or another auth service) and change the email-confirmation setting in that provider's dashboard. Do not collect passwords without a secure backend.
4. WhatsApp links currently open WhatsApp with a pre-filled message but no business number. For a direct chat to your business, replace https://wa.me/?text=... links in index.html with https://wa.me/91YOURNUMBER?text=... using your actual WhatsApp number (digits only, country code included).
5. Deploying these files updates the live site only after a successful Netlify deploy.

NETLIFY MANUAL DEPLOY:
- Put index.html, login.html and signup.html together in one folder.
- Zip the three HTML files (not the containing folder, if the UI expects site files at ZIP root).
- In Netlify, open the PixelViva site and go to Deploys.
- If manual deploy is available, drag the ZIP or the folder containing these files into the manual deploy drop area.
- If Netlify blocks deploy due to usage/credit limits, wait for the usage reset or use another free static host. Do not delete the currently live deploy.
