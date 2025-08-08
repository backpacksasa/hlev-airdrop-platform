# Deploy HLEV Airdrop to Vercel for Analytics

## Steps to Deploy and See Analytics:

### Option 1: Connect GitHub Repository to Vercel
1. Go to https://vercel.com/dashboard
2. Click "New Project"
3. Connect your GitHub account
4. Select repository: `backpacksasa/hlev-airdrop-platform`
5. Click "Deploy"
6. Vercel will automatically detect it's a static site

### Option 2: Use Vercel CLI
```bash
npm i -g vercel
vercel login
vercel --prod
```

### Option 3: Import Project URL
1. Go to https://vercel.com/new
2. Paste your GitHub repo URL: https://github.com/backpacksasa/hlev-airdrop-platform
3. Click "Import"
4. Deploy

## After Deployment:
- Your site will be available at: `https://your-project-name.vercel.app`
- Analytics will be visible at: `https://vercel.com/dashboard/analytics`
- Real-time user data will populate within minutes

## Why GitHub Pages doesn't show Vercel Analytics:
- Vercel Analytics only works on Vercel-hosted sites
- GitHub Pages can't communicate with Vercel's analytics API
- The code is working (you see console logs), but data needs Vercel hosting

Your current analytics are working correctly - they just need Vercel hosting to display in the dashboard.