BUVEXA WEBSITE (static, for Vercel)

Before you deploy, find and replace these in ALL files (index, privacy, terms, refunds, robots.txt, sitemap.xml):
  REPLACE_EMAIL      your business email, for example hello@yourdomain
  REPLACE_PHONE      your business phone, for example +234 801 234 5678
  REPLACE_WHATSAPP   WhatsApp number, digits only with country code, for example 2348012345678
  REPLACE_ADDRESS    your business address
  REPLACE_DOMAIN     your live domain without https://, for example buvexa.shop

Deploy: push this folder to GitHub and import it at vercel.com/new (Framework preset: Other, no build command),
or run "npx vercel" inside this folder.
