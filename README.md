# Futures R-Multiple Calculator

Professional position sizing calculator for futures trading with support for popular contracts.

## Features
- Pre-configured presets for ES, NQ, CL, GC, and more
- Automatic position sizing based on account risk
- Calculate R-multiples for futures trades
- Track multiple trades with portfolio statistics
- Point value and tick size calculations

## Quick Deploy to Render (3 Minutes)

### Method 1: Static Site (EASIEST - No GitHub needed)

**Option A: Direct Upload**
1. Go to https://render.com and sign up/login
2. Click "New +" → **"Static Site"**
3. Choose "Deploy from Git" OR "Upload files"
4. If uploading files:
   - Upload `index.html`
   - Set Publish Directory: `.`
5. Click "Create Static Site"
6. Done! Your app will be live instantly

**Option B: Using GitHub**
1. Create a new repository on GitHub
2. Upload `index.html` to your repository
3. Go to https://render.com
4. Click "New +" → **"Static Site"**
5. Connect your GitHub repository
6. Settings:
   - **Build Command:** (leave empty)
   - **Publish Directory:** `.`
7. Click "Create Static Site"

### Method 2: Alternative Platforms

**Netlify (Even Simpler)**
1. Go to https://app.netlify.com/drop
2. Drag the `index.html` file into the browser
3. Done! Instant deployment

**Vercel**
1. Go to https://vercel.com
2. Click "Add New" → "Project"
3. Import your Git repository
4. Deploy with one click

**GitHub Pages (Free Forever)**
1. Create a GitHub repository
2. Upload `index.html`
3. Go to Settings → Pages
4. Select branch: main
5. Your site will be at: `https://yourusername.github.io/repo-name`

## Local Testing

Simply open `index.html` in any web browser. No server required!

## Contract Presets Included

- E-mini S&P 500 (ES)
- E-mini Nasdaq 100 (NQ)
- E-mini Dow (YM)
- E-mini Russell 2000 (RTY)
- Micro E-mini S&P 500 (MES)
- Micro E-mini Nasdaq 100 (MNQ)
- Crude Oil (CL)
- Gold (GC)
- Natural Gas (NG)
- 30-Year T-Bond (ZB)
- Euro FX (6E)

## Usage Example

1. Select a contract preset (e.g., ES - E-mini S&P 500)
2. Enter your account size
3. Set risk percentage (1-2% recommended)
4. Enter entry price and stop loss distance in ticks
5. System auto-calculates number of contracts
6. Enter exit price and click Calculate
7. View your R-multiple and P/L
8. Add trade to portfolio for tracking

## Support

For questions or issues, open an issue on GitHub.
