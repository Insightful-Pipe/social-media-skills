# How to Use This Skill

Hey Claude, I just added the "social-media-audit" skill. Audit all our social accounts for the last 90 days and give me a scored fix list.

## What you need

- **Either** the InsightfulPipe MCP connected to Claude with your social profiles added (Facebook Pages, Instagram, LinkedIn Pages, TikTok, X, Pinterest, YouTube) and, ideally, GA4. The skill finds the profiles and pulls the numbers itself.
- **Or** no connection at all:
  - the URL of every profile you run, including old ones
  - a 90-day post export from each network (date, reach or views or impressions, likes, comments, shares, saves)
  - follower counts at the start and end of the 90 days
  - the time of each public comment and of your first reply to it, if the network lets you export them
  - a GA4 export of sessions, engaged sessions and key events by session source, medium and default channel group

  Anything you leave out shows up as unknown in the report, with the reason.
- **Your targets,** if you have them (posts a week, reply time). Without them, the skill uses its dated house thresholds and says so.

## Example requests

**Full audit**
Hey Claude, I just added the "social-media-audit" skill. Run a social media audit on every profile we have and score each network.

**Taking over a brand**
Hey Claude, I just added the "social-media-audit" skill. I'm the new social media manager. Find every account we run, including old ones, and tell me what to fix first.

**Agency client**
Hey Claude, I just added the "social-media-audit" skill. Audit this client's social channels from the exports I've attached and fill in a social media audit template I can send them.

**Is social sending anyone?**
Hey Claude, I just added the "social-media-audit" skill. Audit our social profiles and tell me which networks actually send visits and sign-ups to the site.

## What you get

1. **An inventory** of every profile: name, handle, followers, posts in the window, last post, link, and whether it's active, stale or a duplicate.
2. **A score out of 100** and a grid of networks against six areas: profile setup, posting cadence and gaps, engagement, follower growth, public comment response, and traffic and key events from GA4.
3. **A fix list** ranked by impact and effort, each fix with the numbers and the threshold behind it.
4. **The area detail,** with every engagement rate labelled by its basis (reach, views or impressions).
5. **What couldn't be checked,** and why. Direct message response time is always here: no connector exposes the inbox.
6. **Today's follower counts,** saved so the next audit can measure growth on networks that only report the current count.

## What it changes

Nothing. The skill only reads. Every fix is yours to make in the network's own settings or tools.

## Tips

- Run it each quarter with the same 90-day window, so scores compare.
- Tell it about old or regional accounts, even if nobody posts on them. Stale and duplicate profiles are part of the audit.
- If you tag profile links with your own `utm_source` (for example `fbpage`), say so, so the skill counts those visits under the right network.
