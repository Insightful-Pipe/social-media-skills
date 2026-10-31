# How to Use This Skill

Hey Claude, I just added the "instagram-growth-analyst" skill. Give me our Instagram report for the last 4 weeks and tell me how to grow followers next month.

## What you need

- **The InsightfulPipe MCP connected to Claude, with your Instagram business or creator account added.** The skill reads your account totals and every post's insights itself. Threads and GA4 are optional extras.
- **Or, with nothing connected:** a Meta Business Suite content export (Insights, then Content, then Export) for the last 90 days.
- **Your follower count 4 weeks ago,** if you have it, so the report can show net growth.
- **The Business Suite export, even when connected,** if you post Stories: Instagram's API keeps Story insights only while a Story is live, and it doesn't return Reel follows or Reel lengths.
- **Your audience screen,** if you want the follower age, gender and city mix: copy the numbers from Insights in the Instagram app.

## Example requests

**Monthly report**
Hey Claude, I just added the "instagram-growth-analyst" skill. Run our Instagram analytics report for the last 28 days against the 28 before.

**Growing followers**
Hey Claude, I just added the "instagram-growth-analyst" skill. We're stuck at the same follower count. Show me which posts actually bring follows and what to change next month.

**Reels or carousels**
Hey Claude, I just added the "instagram-growth-analyst" skill. Are our Reels or our carousels doing better? Judge them against our own numbers, not industry averages.

**No connection**
Hey Claude, I just added the "instagram-growth-analyst" skill. Here's our Business Suite export. Tell me which topics and posting days work for us.

## What you get

1. **Account health:** views, reach, profile visits and link taps for the last 28 days against the 28 before, with what moved.
2. **Followers and audience:** net growth, new follows, which formats bring follows, how much of your reach is outside your followers, and who follows you.
3. **A format table:** Reels, carousels, single images and Stories on engagement per 1,000 accounts reached, saves, shares, follows and Reel watch time.
4. **What beats your median:** topics, hooks, Reel lengths and posting days, each with a post count. Groups under 5 posts are marked too few to call.
5. **Your top 5 and bottom 5 posts** side by side.
6. **Threads and your website:** Threads totals, and the visits Instagram sends to your site, when connected.
7. **Next month's moves:** up to five changes, each with the numbers behind it.

## What it changes

Nothing. It only reads. To plan and post next month's content from the report, use `social-content` if installed.

## Tips

- Run it at the same point each month, so every report compares the same kind of window.
- Accounts under 100 followers get no follower graph from Instagram's API; the report says so and counts follows from posts instead.
- A topic or format with 1 great post isn't a winner yet. Post it 5 times and run the report again.
