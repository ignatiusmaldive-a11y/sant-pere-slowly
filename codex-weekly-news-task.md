# Codex weekly news task

Schedule: every Monday at 08:00, Europe/Madrid. Use the Sant Pere, Slowly project in a dedicated worktree where available.

## Saved task prompt

Every Monday, research and refresh the “The neighborhood, this week” digest on the Sant Pere, Slowly Hugo website.

1. Search for reporting published in the last seven days about Sant Pere, Santa Caterina, La Ribera/Born, and immediately adjacent Ciutat Vella. Prioritize Betevé neighborhood coverage, Ajuntament de Barcelona notices and cultural calendars, and direct updates from Santa Caterina Market, Antic Teatre, RAI, La Bonne/Biblioteca Francesca Bonnemaison, Cercle Artístic de Sant Lluc, and neighborhood associations. Include wider Ciutat Vella items only when useful to someone visiting these nearby streets.
2. Select up to four timely, worthwhile stories. Prefer neighborhood reporting and civic or cultural changes over generic city-wide tourism pieces. If the week is quiet, publish fewer items rather than padding the list.
3. Verify every headline, publication date, location, and direct article URL. Link to original reporting. Clearly distinguish an article’s publication date from any future event date. Never invent news or present an old article as new. Add a brief neutral note explaining why the story matters to a visitor or helps them understand local life.
4. Create a new dated Hugo content file at content/news/YYYY-MM-DD.md using the established front matter shape: title, date, summary, and an items list with title, source/date, url, and note. Write a short introduction as the body. Keep the tone curious and respectful of residents; avoid framing local people or ordinary cultural activity as tourist spectacle.
5. Keep the site’s displayed week-of date driven by the latest news page. The homepage should display only the newest digest; leave older dated digests in place as an archive. Update README or templates only if needed to preserve this behavior.
6. Run hugo --minify to verify the site builds. Review the generated homepage to confirm it shows the new digest, links, and correct date without older issues mixed in.
7. Report what changed and list the linked stories. Do not publish, push to main, or open a pull request automatically; leave the worktree changes ready for review.

If reliable reporting cannot be found for the last seven days, keep the existing digest and report that there were no strong new items.
