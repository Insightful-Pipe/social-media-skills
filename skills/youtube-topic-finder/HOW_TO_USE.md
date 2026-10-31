# How to Use This Skill

Hey Claude, I just added the "youtube-topic-finder" skill. Find YouTube video ideas for my channel from what is working for these rival channels, and plan my next quarter.

## What you need

- **Nothing, to start.** Paste a list of videos (title, publish date, length, views) for your channel and 3 to 6 rival or nearby channels, plus any viewer comments or search volumes you have. The skill runs the same maths on what you paste and marks anything it couldn't check.
- **Better: the InsightfulPipe MCP connected to Claude, with your YouTube channel added.** The skill then pulls rival channels and their uploads, video stats and comments itself, and reads your own Shorts and long-form results from YouTube Analytics.
- **Optional: DataForSEO connected through InsightfulPipe,** for Google search volume, YouTube interest over 12 months and the age of the videos ranking today. A run uses at most 8 paid calls, or 10 when it also has to find nearby channels for you, and asks before going past 10. This path was not run when the skill was built, because the test account had no credit.
- **Channel IDs, not handles.** Rival channels are looked up by ID (it starts with `UC`). On a channel page, open the About panel, click "Share channel", then "Copy channel ID".

## Example requests

**Plan a quarter**
Hey Claude, I just added the "youtube-topic-finder" skill. Plan our next quarter of YouTube videos from these four channels. We can make one long video every two weeks and two Shorts a week.

**What to make next**
Hey Claude, I just added the "youtube-topic-finder" skill. Which video should I make next? Show me the rival videos and viewer questions behind each idea.

**A new channel**
Hey Claude, I just added the "youtube-topic-finder" skill. I'm starting a YouTube channel about bookkeeping for small cafes. Give me my first 10 videos.

**From a pasted list**
Hey Claude, I just added the "youtube-topic-finder" skill. Here are the last 80 videos from three channels in my niche, with views and dates. Find the outliers and turn them into video ideas for me.

## What you get

1. **Baselines:** each channel's median views for Shorts and long-form, and which videos beat it.
2. **Ranked ideas** with a score out of 100 from four parts (proof, demand, openness, fit), each part shown, and a tier: make next, test as a Short first, or park.
3. **The evidence behind each idea:** the outlier videos and their ratios, the viewer questions with a short quote, and search volume. The YouTube trend is checked for the 10 ideas with the strongest proof, and the age of the ranking videos for the top 5, to keep paid calls low; the rest are marked not checked, and the skill can check more if you approve the extra calls.
4. **Series** that group related ideas into a run of videos.
5. **A 13-week slate** of long-form videos and Shorts, with a rule for when a Short earns a long-form follow-up.
6. **A first 10-video plan** when the channel is new.
7. **Parked ideas** with the reason, and a list of what couldn't be checked.

## What it can change for you

Nothing. The skill is read only: it never uploads, edits videos, replies to comments or changes playlists.

## Tips

- Mix direct rivals with nearby channels that serve the same viewers. Nearby channels often hold the best outliers.
- Run it again each quarter, and after a Short takes off.
- Once you pick an idea, write its title, description and tags with youtube-seo-optimizer, if installed.
