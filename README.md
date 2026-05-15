# Grant Engine — Web App

Multi-LLC grant discovery, vetting, and AI-drafted application generator.

**Live app:** https://luishunchgroup.github.io/grant-engine-app/

## What it does

- Live search of Grants.gov federal grant database (free API)
- Track grants across 4 LLCs (HVAC, Real Estate, Marketing, renameable)
- AI vetting: fit score, PURSUE/SKIP/PARK, advantages, gaps, LLC structure tips
- AI draft: 8-section grant application narratives per LLC
- Export to CSV (Google Sheets), JSON (backup), Markdown (Google Docs)

## How to use

1. Open the live app URL
2. Fill in your LLC profiles (Tab 03)
3. Add your Anthropic API key (Tab 03) to unlock AI features
4. Search grants, vet, draft, paste into real applications

All data lives in browser localStorage. Export JSON for backup.

## Joint Venture

Joint project between luishunchgroup and fortifiedkhan. Public repo so the live URL works without GitHub Pro. The HTML contains no secrets — each user adds their own Anthropic API key, stored only in their browser.

## Related projects

- Grant-Opportunities (private repo) — Next.js v2 with Clerk + Supabase + team CRM
- Chrome Extension (future) — logged-in scraping for Submittable, GrantHub
