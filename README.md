# Deutsch Padikkam: going live

Free German course for Malayalam speakers. Plain static website, no build step.

## 1. Fill in your details (required before going public)
Replace these placeholders:

| File | Replace |
|---|---|
| impressum.html | `Straße und Hausnummer`, `PLZ`, `DEINE-EMAIL@BEISPIEL.DE` (2x) |
| datenschutz.html | `Straße und Hausnummer`, `PLZ`, `DEINE-EMAIL@BEISPIEL.DE` (2x) |
| index.html | `DEINE-EMAIL@BEISPIEL.DE` (feedback link in footer) |

Tip: make a separate email address for the site.

## 2. Put it online (free)
1. Create accounts on github.com and netlify.com.
2. GitHub: New repository, name `deutsch-padikkam`, Create.
3. "Upload files": drag in all files and the `fonts` folder from this zip, then Commit.
4. Netlify: Add new site, Import an existing project, GitHub, choose the repository, Deploy.
   No build command. The site is live at `something.netlify.app` within a minute.
5. Optional: buy a domain and connect it in Netlify under Domain management. HTTPS is automatic.

## 3. After you have the final address
- In index.html, change `og-image.png` in the `<meta property="og:image" ...>` line to the full address,
  e.g. `https://deutschpadikkam.de/og-image.png`. WhatsApp needs the full URL for the preview image.
- Add the site in Google Search Console and request indexing.

## 4. Updating later
Change index.html (or get a new one from Claude). On GitHub open the file, upload the new version, Commit.
Netlify redeploys automatically. Learners keep their progress as long as the domain stays the same.

## Already done
- Fonts stored locally (no Google Fonts requests).
- No cookies, tracking or ads, so no cookie banner needed.
- Impressum (§ 5 DDG) and Datenschutzerklärung, linked in the footer.
- Share image, favicon, security headers (netlify.toml).
- Font licences (SIL Open Font License) in /fonts.

Not legal advice. Have Impressum and Datenschutz checked again if you add payments, logins or analytics.
