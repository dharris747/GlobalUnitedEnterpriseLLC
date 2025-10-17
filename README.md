# Global United Enterprise LLC — Website

Static, no-fee business site. Host free on GitHub Pages / Cloudflare Pages / Netlify.

## Update your details
Edit the placeholders inside HTML files:
- `Global United Enterprise LLC`, `Atlanta, GA`, `derrickharris@globalunitedent.com`, `(888) 508-6798`
- `Government contract procurement & administration—done right.`, `We help agencies and prime contractors simplify acquisition, compliance, and contract administration from pre-award through closeout.`, `Procurement support, proposal coordination, compliance, and end-to-end contract administration for federal, state, and local projects.`, `government contract procurement and administration`
- Capabilities placeholders: `541611; 541618; 541990 (edit to match)`, `XXXX`, `XXXXXXXXXXXX`, `GSA MAS / State IDIQ / BPA (edit)`, `Small Business (edit)`
- Google Forms: `https://docs.google.com/forms/d/e/FORM_ID/viewform?embedded=true`, `https://docs.google.com/forms/d/e/FORM_ID/viewform`

## Step-by-step: Publish on GitHub Pages (no fees)
1. Create a free GitHub account and sign in.
2. Click **New repository** → Name it (e.g., `globalunited-site`), set **Public** → **Create repository**.
3. Click **Add file → Upload files** → Drag all files from this folder (after unzipping) → **Commit changes**.
4. Go to **Settings → Pages**.
   - Under **Build and deployment**, set **Source = Deploy from a branch**.
   - Set **Branch = main**, **Folder = / (root)** → **Save**.
5. Wait up to a minute, then your site appears at `https://<your-username>.github.io/<repo-name>/`.
6. (Optional) Make it your main site by creating a repo named `<your-username>.github.io` and repeating steps 3–4.

## Switch the contact form to Google Forms
1. Create a Google Form with fields you want (Name, Email, Phone, Message).
2. Click **Send** → the **<> Embed** tab → copy the **embed URL** (starts with `https://docs.google.com/forms/.../viewform?embedded=true`).
3. Paste it into `contact.html` replacing `https://docs.google.com/forms/d/e/FORM_ID/viewform?embedded=true`.
4. Also click the **Link** tab and copy the shareable form link; paste it into `https://docs.google.com/forms/d/e/FORM_ID/viewform` as a fallback.
5. Save and push changes to GitHub; your live site updates automatically.

## Print a one-page PDF capabilities statement
- Open `capabilities.html` in your browser → **Print** → Destination: **Save as PDF** → Margins **Narrow**.
- (Optional) Add your logo and branding before export.

## Free forever tips
- Use the free `github.io` subdomain to avoid domain costs.
- Payments: use Stripe Payment Links or PayPal buttons (no monthly fee; per-transaction only).
