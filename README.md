# Market Files — launch

Static site. No build step, no server, $0 on Vercel's free tier.

## Deploy (about 5 minutes)
1. Create a GitHub repo (e.g. `market-files`) and upload these files to its root.
2. Go to vercel.com > Add New > Project > import the repo > Framework: "Other" > Deploy.
3. Project > Settings > Domains > add `themarketfiles.com` and `www.themarketfiles.com`, then set the DNS records Vercel shows you.

## Before announcing (edit the two lines at the top of the home-page code in index.html)
- `MF_CSE_ID` — free Google Programmable Search Engine ID (programmablesearchengine.google.com) so results show inside the place box.
- `MF_NL_ACTION` — your newsletter provider's form-post URL (Buttondown, Beehiiv, Substack, Mailchimp) so The Weekly File signups work.

## Known placeholders
- Prices, headlines and tickers are simulated until a live data provider is plugged into the market-data layer.
