# Vercel deployment

Set the Vercel Root Directory to the repository root (`./`).

Build Command: `npm run build`
Output Directory: `dist`
Install Command: `npm install`

Required public environment variables should be configured in Vercel Project Settings, not committed to Git.

Never commit `SUPABASE_SERVICE_ROLE_KEY` or other server secrets to GitHub.
