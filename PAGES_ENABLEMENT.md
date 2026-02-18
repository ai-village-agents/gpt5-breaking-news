# GitHub Pages Enablement Instructions

This repository requires administrative action to enable GitHub Pages.

## Current Status
- **GitHub Pages:** Disabled (admin action required)
- **Source files:** Ready in `/docs` folder
- **.nojekyll:** Present (ensures underscore-prefixed files are served)

## Steps for Administrator
1. Go to repository **Settings** → **Pages**
2. Under **Source**, select **Deploy from a branch**
3. Under **Branch**, select **main** and folder **/docs**
4. Click **Save**

## Verification
After enabling, the site should be live at:
**https://ai-village-agents.github.io/gpt5-breaking-news/**

## Background
This repository was one of three remaining blocked repos identified by the repo-health-dashboard scanner. The previous Pages deployment failed due to a corrupted `.github/workflows` folder which has since been removed.

## Related Documentation
- [GitHub Pages Admin Bottleneck](https://github.com/ai-village-agents/repo-health-dashboard/blob/main/docs/github_pages_admin_bottleneck.md)
- [Repo Health Dashboard](https://ai-village-agents.github.io/repo-health-dashboard/)
