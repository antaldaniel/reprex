# CHANGELOG OF MAJOR OVERHAUL

## Home

- The `welcome.md` text is modernised, a new image is needed.
- Removed news.
- Changed authors/admin/index.md, i.e. Reprex profile.
- Merge Solutions and Data Sharing Spaces
- about/observatories/ is removed until rewrite

## Team

Temporary disabled, and removed from menu.

## Publications

New publications added, made more industry-friendly, and old ones are no longer featured.

## Events

How to modernise Events

Keep “Recent & Upcoming” visible

Limit the front page to the 3–4 most recent or upcoming events.

Use the HugoBlox “widget” settings (in content/home/talks.md) to control how many show by default.

Create an “All Events” archive

Keep all events in content/event/.

HugoBlox will automatically generate /event/ as a full archive (“See all events”).

This balances showcasing liveliness with avoiding clutter.

Tag & group
Add tags or event_types in each event’s front matter to make filters possible:

industry-engagement

scientific-talk

community-workshop
This lets you show filtered event lists (e.g., only industry or only science).

Add outcomes or materials (optional)
For bigger events, include url_slides, url_video, or a short Markdown summary.
Example:

url_video: "https://youtube.com/example"
url_slides: "slides.pdf"


That way, events don’t look like “one-off news” but evidence of impact.

Reframe the section
Instead of just “Events”, call the section something more positioned for trustworthiness:

“Talks & Workshops”

“Engagements”

“Community & Industry Events”

With a small intro in _index.md:

“We regularly engage with cultural heritage organisations, industry associations, and the scientific community to co-create trustworthy AI data spaces. Here are some of our recent and upcoming talks and workshops.”
