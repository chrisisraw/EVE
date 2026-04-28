# E.V.E. — Everything Vegan Ever
## Vercel Deployment

### Files:
```
index.html        ← The full app
vercel.json       ← Vercel config
api/claude.js     ← API proxy (keeps your Anthropic key secret)
```

### Deploy Steps:

1. Go to https://vercel.com → sign up free (GitHub login is easiest)

2. Click "Add New Project" → "Deploy without a Git repo" 
   (or drag this folder)

3. Add your API key:
   - Project Settings → Environment Variables
   - Name:  ANTHROPIC_API_KEY
   - Value: your key from https://console.anthropic.com

4. Deploy — you get a free yoursite.vercel.app URL instantly

### All AI features will work:
✓ Auto-Plan Week
✓ Wellness Report
✓ Personal Trainer
✓ Pantry Match
✓ Recipe Fetching
✓ Garden Advisor
