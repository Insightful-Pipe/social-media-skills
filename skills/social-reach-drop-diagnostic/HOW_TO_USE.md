# How to Use This Skill

Hey Claude, I just added the "social-reach-drop-diagnostic" skill. Our Instagram reach dropped off a cliff this month. Find out why and tell me how to get it back.

## What you need

- **Nothing connected, at the least.** Paste or upload a post export covering the last 120 days (date, format, video length, views or impressions, and the caption) and the skill runs on that.
- **Better: the InsightfulPipe MCP connected to Claude** with the accounts that fell: Instagram, Facebook Pages, TikTok, LinkedIn Pages, X or YouTube. The skill reads posts, daily totals and follower numbers itself. Add the InsightfulPipe Social Media Scheduler and it also checks for posts that failed to publish.
- **A control network,** if you have one: any other connected account that didn't fall. It tells a platform problem apart from a seasonal or audience one.
- **A few numbers from the app,** if you can: the follower and non-follower split of views on Instagram or Facebook, and the For You share on TikTok, for the last 30 days and the 90 days before. Their APIs mostly don't share them.

## Example requests

**Instagram shadowban check**
Hey Claude, I just added the "social-reach-drop-diagnostic" skill. I think our Instagram is shadowbanned. Check the evidence and tell me what's really going on.

**Why are my TikTok views low**
Hey Claude, I just added the "social-reach-drop-diagnostic" skill. Our TikTok views have been low for a month. Is it the videos, the algorithm or something else?

**Several networks at once**
Hey Claude, I just added the "social-reach-drop-diagnostic" skill. Reach fell on Instagram and LinkedIn in the last few weeks. Check both, and use YouTube as the control.

**Followers falling**
Hey Claude, I just added the "social-reach-drop-diagnostic" skill. Our Facebook Page is losing followers. Find the days it happened and what we posted.

**From an export**
Hey Claude, I just added the "social-reach-drop-diagnostic" skill. Here's our LinkedIn post export for the last four months. Why are impressions down?

## What you get

1. **A drop check per network:** the last 30 days against your own 90-day baseline, by median views per post (daily views on YouTube), with how many recent posts fell below the old normal. It says plainly whether the drop is real, narrow (a few weak posts) or not there at all.
2. **Eight causes, each with a verdict** (supported, possible, ruled out or not checked) and the numbers behind it:
   - fewer posts
   - a format shift, with how much of the drop the change in mix alone explains
   - a viral post that made the old normal look higher
   - a change in where views come from (followers and non-followers, recommendation feeds, search)
   - links and hashtags
   - failed scheduled posts
   - restriction signs
   - seasonality or a platform-wide dip
3. **A straight answer on shadowbans:** no platform's API exposes one, so the skill shows whether the patterns a restriction leaves are there, and lists the status screens to check in each app.
4. **A recovery plan,** in order: one action per cause, each with a 14-day test and the number that shows it worked.
5. **What couldn't be checked,** and why.

## What it can change for you

With your yes on the exact change, it can put a failed scheduled post back in the queue in the Social Media Scheduler. That needs a Read & Write connection, and an owner, admin or operator can switch it off. It never posts, edits, deletes or boosts anything on your accounts.

## Tips

- **Say when you first noticed.** If the drop started more than 30 days ago, ask for a longer recent window so the baseline doesn't already include it.
- **Give it a week.** Posts younger than 7 days are left out of the medians because their counts are still growing.
- **Change one thing at a time.** The recovery plan runs one 14-day test per cause, so you can see which fix worked.
- **Ignore "shadowban reset" advice.** Deleting posts or going quiet for a week doesn't restore reach; the plan works on the causes the numbers show.
