# How to Use This Skill

Hey Claude, I just added the "content-repurposer" skill. Take our top blog post and turn it into an X thread, hooks, tweets, hot takes, a LinkedIn post, an email and ad copy.

## What you need

- **The InsightfulPipe MCP connected to Claude, with Google Search Console for your site.** The skill finds your top post and the words people search to reach it.
- **No Search Console for the site?** DataForSEO can stand in. It estimates which posts get the most search visits and the words people search to reach one, and the report labels those figures as estimates.
- **Optional, for better drafts:** Google Analytics 4, your Facebook Page or LinkedIn Page (to learn which hooks your audience responds to), and the Social Media Scheduler (to check the post hasn't been shared already, and to save drafts).
- **A post URL,** if you want a specific post. Without one, the skill picks the post with the most search clicks in the last 90 days.
- **The audiences to adapt for,** if any, in plain words.
- **For a transcript to article:** the transcript pasted in, or an SRT or VTT caption file, plus the speakers' names and the recording link. No connection is needed; Search Console and DataForSEO aim the article at a real search, and WordPress lets it check for an existing draft and save the article as one.

## Example requests

**Top post, full pack**
Hey Claude, I just added the "content-repurposer" skill. Find our best blog post from the last 90 days and give me the full pack: thread, hooks, posts, hot takes, LinkedIn, email and ads.

**One post into an X thread**
Hey Claude, I just added the "content-repurposer" skill. Turn https://example.com/blog/my-post into an X thread and five alternative hooks.

**Tweet ideas and hot takes**
Hey Claude, I just added the "content-repurposer" skill. Give me five standalone tweets and three hot takes from our latest guide. Keep every claim to what the post says.

**Adapt for an audience**
Hey Claude, I just added the "content-repurposer" skill. Rewrite our top post for agency owners and for founders, and tell me what you changed for each.

**Transcript to blog post**
Hey Claude, I just added the "content-repurposer" skill. Here is the caption file from our latest podcast episode. Turn it into a blog post that targets a search people make, with timestamped quotes, and don't add anything the guest didn't say.

## What you get

1. **Why this post:** the top 5 candidates by search clicks (or estimated visits), and a note if GA4 isn't tracking the page.
2. **Your audience's words:** the searches that bring people to the post, and how much of the traffic they cover.
3. **What your history says:** whether question or statement hooks do better on your own page, or that the evidence doesn't favour either.
4. **Atoms:** the standalone points pulled from the post, each with an id.
5. **The pack:** an X thread, 5 hooks, 5 standalone posts, 3 hot takes, a LinkedIn post, Facebook and Threads versions, an email section, Google responsive search ad copy, a social ad, and one version per audience. Every draft lists the atoms it came from and its character count.
6. **Checks:** length, fact trace, offers, link placement and repeats, per draft.

**From a transcript,** you get instead: the cut log (filler, sponsor reads, housekeeping), the searches the recording answers with their volume and whether a page of your site already ranks for them, an outline with timestamps, the article itself (title, meta description, sections, word-for-word quotes, takeaways and internal links, every part tied to transcript lines), the lines it left out, and the checks. It can then run the article through the pack above.

## What it can do for you

With your yes on the exact drafts, it can save LinkedIn, Facebook Page and Threads drafts to the Social Media Scheduler, and a transcript article to WordPress, as **drafts**. It never posts, never schedules, never publishes, and never touches X, your email platform or your ad accounts. That needs a Read & Write connection, and an owner, admin or operator can switch them off.

## Tips

- Prices, discounts and trial terms never go into the drafts. If you want an offer in, give the current one.
- Run it once per post, then use the Content Calendar skill (if installed) to place the drafts at your best times.
- If the skill says GA4 has a tracking gap, check that your GA4 tag fires on blog pages.
