# How to Use This Skill

Hey Claude, I just added the "youtube-channel-analyst" skill. Review my YouTube channel for last month and tell me the five things to do next.

## What you need

- **The InsightfulPipe MCP connected to Claude, with your YouTube channel added.** The skill pulls YouTube Analytics and YouTube Data API numbers itself; you don't need to export anything from Studio. The one exception is the title and thumbnail test mode, which needs your Studio click-through rate export and also works from that export with nothing connected.
- **Which channel,** if you connected more than one.
- **The month to review,** if it isn't the last full month.

## Example requests

**Monthly report**
Hey Claude, I just added the "youtube-channel-analyst" skill. Give me the monthly report for my YouTube channel for September, compared with August.

**Where viewers leave**
Hey Claude, I just added the "youtube-channel-analyst" skill. Show me where viewers drop off in my five most-watched videos last month, with timestamps.

**Shorts or long videos**
Hey Claude, I just added the "youtube-channel-analyst" skill. Are my Shorts or my long videos doing more for watch time and subscribers?

**Subscribers and uploads**
Hey Claude, I just added the "youtube-channel-analyst" skill. Which videos brought in subscribers last month, and how consistent has my upload schedule been?

**Title and thumbnail test**
Hey Claude, I just added the "youtube-channel-analyst" skill. Here are my YouTube Studio exports for the last 28 days, one each for Browse features, Suggested videos and YouTube search. Which videos have titles and thumbnails that undersell them? Give me three title and thumbnail ideas for each and set up a Test & Compare test.

**Review, then fix**
Hey Claude, I just added the "youtube-channel-analyst" skill. Review my channel, then suggest better titles for the weakest recent uploads. Show me each change before you make it.

## What you get

1. **A scorecard for nine areas:** the monthly headline, Shorts versus long-form, retention drop-off, click-through and packaging, subscriber growth, revenue and RPM, playback location and device, cards and end screens, and upload consistency.
2. **The top 5 actions,** each with the numbers behind it.
3. **Retention curves for your top 5 long videos,** with the second where the biggest drop starts.
4. **A clear list of what YouTube's API can't show** (impressions click-through rate and end screens) and where to find those numbers in YouTube Studio.
5. **Next steps,** pointing to the right skill for a deeper look.

**In the title and thumbnail test mode** you get, instead: every video's click-through rate against your channel's own median in the same traffic source, a packaging-or-content diagnosis using retention, the top 5 videos to test ranked by missed clicks, three title and thumbnail concepts for each (written briefs, not images), and the Test & Compare steps in YouTube Studio.

## What it can change for you

With your yes on the exact change, it can rewrite a video's title or description. It reads the current details first and sends them back unchanged except for the edit.

It never changes thumbnails, cards, end screens, privacy settings, or deletes anything.

## Tips

- Run it in the first week of each month, at least 3 days after the month ends, because YouTube's numbers arrive about 2 days late.
- If your channel isn't monetized, the revenue section says "not graded" instead of showing zeros.
- YouTube's API doesn't share impressions or click-through rate, so the test mode needs a YouTube Studio export: Analytics, Advanced mode, the Content table filtered to one traffic source at a time. It works from that export alone, even with nothing connected.
- Let a test run its full course and don't edit the title or thumbnail meanwhile: an edit stops the test.
