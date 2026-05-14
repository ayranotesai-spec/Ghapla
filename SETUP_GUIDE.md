# 🫠 Ghapla.in — Your Complete Setup Guide
### Zero technical knowledge required. Seriously.

---

## YOUR 4 FILES (keep all together in one folder)

```
ghapla-site/
├── index.html    ← The entire website
├── robots.txt    ← Tells Google to list you
├── sitemap.xml   ← Helps Google find you fast
└── vercel.json   ← Deployment settings (don't touch)
```

---

## STEP 1 — GET YOUR WEBSITE LIVE (FREE, ~10 minutes)

### A) Create a GitHub account
1. Go to **https://github.com**
2. Click **Sign Up** — use any email, create a username + password
3. Verify your email

### B) Upload your files to GitHub
1. After signing in, click the **+** icon (top right) → **New repository**
2. Name it: `ghapla` → leave everything else default → click **Create repository**
3. On the next page, click **"uploading an existing file"**
4. Drag and drop ALL 4 files into the upload box
5. Scroll down → click **Commit changes** (green button)

### C) Deploy to Vercel (makes it live on the internet)
1. Go to **https://vercel.com**
2. Click **Sign Up** → choose **Continue with GitHub** → authorize it
3. You'll see a dashboard. Click **"Add New Project"**
4. You'll see your `ghapla` repository — click **Import**
5. Don't change anything — click **Deploy**
6. Wait ~30 seconds → 🎉 Your site is LIVE!

Your site URL will be: `ghapla.vercel.app` (completely free forever)

---

## STEP 2 — GET A CUSTOM DOMAIN (Optional, ~₹700/year)

If you want `ghapla.in` instead of `ghapla.vercel.app`:

1. Buy the domain at **https://godaddy.com** or **https://namecheap.com**
   - Search for `ghapla.in` → buy for ~₹700/year
2. In your Vercel dashboard → click your project → **Settings** → **Domains**
3. Type your domain (e.g. `ghapla.in`) → click **Add**
4. Vercel will show you DNS settings to copy
5. Go back to GoDaddy/Namecheap → DNS settings → paste Vercel's records
6. Wait up to 24 hours → `ghapla.in` is now your site!

---

## STEP 3 — ADD GOOGLE ADSENSE (Start Earning Money)

### Get approved first:
1. Go to **https://adsense.google.com**
2. Sign in with your Google account
3. Click **Get Started** → enter `ghapla.in` (or your vercel URL)
4. Select India, accept terms → submit
5. Google reviews in 1–14 days and emails you

### Once you have your Publisher ID (looks like `ca-pub-1234567890123456`):

Open `index.html` in **Notepad** (right-click → Open with → Notepad)

**Do this in 3 places:**

**Place 1 — Near the top of the file** (search for `ADSENSE_PLACEHOLDER_START`):
- Delete the line: `<!--`
- Change `ca-pub-XXXXXXXXXXXXXXXX` to your actual Publisher ID
- Delete the line: `-->`

**Place 2, 3, 4, 5 — The ad slots** (search for each `👉 ADSENSE STEP`):
- For each one, remove the `<!--` and `-->` around the `<ins>` tag
- Replace `ca-pub-XXXXXXXXXXXXXXXX` with your Publisher ID
- Replace `YOUR_SLOT_ID` with the slot ID from your AdSense dashboard

Save the file → re-upload to GitHub (same way as before) → Vercel auto-updates in 30 seconds.

### Your 5 ad slots (already placed for maximum earnings):
| Slot | Position | Why it earns |
|------|----------|-------------|
| Leaderboard 728×90 | Top of page | First thing users see |
| Rectangle 300×250 | Middle of tools | Highest RPM format |
| Banner 468×60 | Between sections | Breaks up scroll |
| Large Rectangle 336×280 | Lower page | Good for mobile |
| Sticky Bottom Banner | Fixed at bottom | ALWAYS visible, highest RPM |

---

## STEP 4 — ADD GOOGLE ANALYTICS (See Your Traffic)

### Get your Measurement ID:
1. Go to **https://analytics.google.com**
2. Click **Start measuring**
3. Account name: `Ghapla` → Next
4. Property name: `Ghapla.in` → Country: India → Currency: INR → Next
5. Choose **Web** → enter your site URL
6. You'll get a Measurement ID like `G-ABC123XYZ`

### Add it to your site:
Open `index.html` in Notepad → search for `ANALYTICS_PLACEHOLDER_START`
- Remove the `<!--` and `-->` around the GA script block
- Replace both instances of `G-XXXXXXXXXX` with your actual Measurement ID
- Save → re-upload to GitHub

---

## STEP 5 — TELL GOOGLE YOU EXIST (Takes 2 minutes)

1. Go to **https://search.google.com/search-console**
2. Sign in → click **Add Property** → enter `https://ghapla.in`
3. Verify ownership (choose "HTML tag" method — copy the tag, paste into your `<head>`)
4. Once verified → go to **Sitemaps** → enter `sitemap.xml` → Submit

Google will start indexing you within a week.

---

## HOW TO ADD YOUR ADSENSE ID (The Simple Version)

When you message me your Publisher ID, I'll give you the exact updated file. You just:
1. Download the new file
2. Upload to GitHub
3. Done.

---

## VIRAL SHARING STRATEGY

### Day 1 (Launch):
- Share in your personal WhatsApp groups
- Message: *"Bhai ek ajeeb website mili hai, apna aura score check kar 🫠 ghapla.in"*
- Post on Twitter: screenshot of your tool result + "Found India's most pointless website"
- Best time: **7–10pm** (peak Indian internet time)

### Week 1:
- Post in these subreddits (free): `r/india`, `r/Btechtards`, `r/JEENEETards`, `r/IndianEnts`
- Share tool results as Instagram stories (they get screenshotted and reposted)
- DM 3–5 Indian meme pages on Instagram — offer them content

### Ongoing:
- Create a Twitter account `@GhaplaDotIn` — post 1 funny result screenshot daily
- Post in college/office WhatsApp groups during exam seasons
- Share the "Scam of the Day" section to parent groups (they love sharing it)

---

## EXPECTED EARNINGS (Realistic)

| Traffic Level | Monthly Income |
|--------------|---------------|
| 1,000 visitors/day | ₹1,500–4,000 |
| 5,000 visitors/day | ₹8,000–20,000 |
| 20,000 visitors/day | ₹35,000–80,000 |
| Viral moment | ₹2L+ that month |

RPM in India: ₹50–150 per 1000 page views normally, up to ₹300 during festive seasons.

---

## FAQ

**Q: Site shows an error after deploying?**
A: In Vercel dashboard → your project → click the deployment → check logs. Usually a file upload issue. Re-upload all 4 files.

**Q: AdSense says "insufficient content"?**
A: Your site already has tons of content. If rejected, wait 1–2 weeks and reapply. Make sure your Privacy Policy link works.

**Q: How do I add more tools or content?**
A: Just ask me! I'll update the file for you.

**Q: Can I change colors or fonts?**
A: Yes — ask me what you want changed and I'll give you the updated file.

**Q: Domain not working after 24 hours?**
A: DNS sometimes takes 48 hours. If still broken, share the Vercel DNS settings screenshot with me.

---

*Built with 🫠 energy. Ghapla guaranteed.*
