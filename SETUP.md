# Setup (about 5 minutes)

1. **Repo name.** Your profile repo must be public and named exactly `kamalinirajan7-dotcom`. Upload everything from this folder into it, including the hidden `.github` folder.
2. **Permissions.** Repo → Settings → Actions → General → Workflow permissions → choose **Read and write permissions** → Save.
3. **Edit `config.json`:**
   - `linkedin_url`: your full LinkedIn profile link (the button only appears when this is filled in).
   - `featured_repos`: exact repo names to pin, e.g. `["loan-approval-predictor", "customer-persona-segmenter"]`. Leave `[]` to auto-pick by stars.
   - `blog_feed_url`: an RSS feed such as `https://dev.to/feed/yourname` or `https://medium.com/feed/@yourname`.
4. **First run.** Actions tab → run **Generate Snake**, then **Update README** (button: *Run workflow*). After that both run on their own.

## Good to know
- Updates run hourly. For an instant refresh, use *Run workflow* on **Update README**.
- LinkedIn has no public feed, so its posts can't be pulled automatically. Cross-posting to dev.to or Medium and using that feed is the workaround.
- Stats, trophies and streak cards come from free public services that occasionally rate-limit. If one shows an error, it usually fixes itself later.
- If GitHub ever pauses the scheduled workflows (it can after long inactivity), re-enable them in the Actions tab.
