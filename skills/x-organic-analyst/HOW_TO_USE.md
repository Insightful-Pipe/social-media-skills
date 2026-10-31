# How to Use This Skill

Hey Claude, I just added the "x-organic-analyst" skill. Analyse our X account for the last 30 days and tell me which posts, formats and posting times work, then draft our next posts from the winners.

## What you need

- **Your X numbers, one of three ways:**
  - the InsightfulPipe MCP connected to Claude with X Organic added (it uses your own X developer app, and X bills each call to that app, so the skill tells you the cost of each page before it pulls more)
  - or the content CSV export from X account analytics
  - or your posts pasted in, with their impressions and clicks
- **Google Analytics 4, optional.** Connected through the InsightfulPipe MCP, it shows the site visits each link post sent and the key events (conversions, such as sign-ups) those visits led to.
- **An earlier follower count with its date,** if you have one, for the follower trend.

## Example requests

**Monthly X analytics report**
Hey Claude, I just added the "x-organic-analyst" skill. Give me our X analytics report for the last 30 days, with the checks and the top 5 actions.

**What sends people to the site**
Hey Claude, I just added the "x-organic-analyst" skill. Which of our X posts sent profile clicks and site visits? GA4 is connected.

**Working from the export**
Hey Claude, I just added the "x-organic-analyst" skill. Here is our X analytics CSV for October. Tell me which formats and hours beat our usual, and keep replies separate.

**Grow on X with new drafts**
Hey Claude, I just added the "x-organic-analyst" skill. We want to grow on X. Find our best posts and threads and draft 3 posts and a thread in the same style. Don't post anything yet.

## What you get

1. **Five checks** measured against your own account: reach momentum, profile pull, reply balance, site handoff and the follower trend.
2. **The top 5 actions,** each with the posts and numbers behind it.
3. **Original posts and replies kept apart,** so a stream of small replies doesn't hide how your posts do.
4. **Formats, topics and posting hours** compared with your own rolling median, with a verdict only where there are 10 or more posts.
5. **The posts that sent profile clicks and site visits,** matched to GA4 sessions by UTM tag or by page and day.
6. **Drafts:** 3 posts and a thread, each modelled on a named winner, with character counts and the exact post payload.

## What it can do for you

With your yes on the exact text, it can publish a draft post or thread to your X account. Each post is billed to your X developer app, and a post with a link costs more. It never deletes, edits, reposts or replies to other accounts.

## Tips

- Run it every 30 days. The X API returns link and profile clicks only for posts from the last 30 days, so a monthly run never loses them.
- Give it the follower count from the last run so the trend has a starting point.
- Tag your link posts with `utm_content`, so each one's site visits are matched exactly instead of by page and day.
