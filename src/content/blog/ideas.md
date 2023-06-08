---
title: "Ideas"
description: "Various ideas for products and tools that I've had over the years"
pubDate: "Jun 6 2023"
tag: "tech"
---

_Before reading this, you might be interested in reading my post about [the kinds of software problems I like working on](/blog/problems-i-like)._

For years, I have kept a list of ideas for software products and tools. After I re-lauched my website, I figured why not clean up the list and make it public? Having ideas is the easy part, after all. Maybe one day I'll convince someone to work on one of these with me :).

# Better browser history and bookmarking

I've always been dissatisfied with browsers' native experiences for managing browser history and bookmarks.

Browser history is hard to search, as you often end up recalling content and not the title of the webpage nor exactly when you opened it (or your customized title, even if you took the time to do so).

My ideal browser history tool would allow me to:

- revisit sets of related links, where "related" means they are linked to one another, opened in the same window, and/or contain similar content
- see pieces of text that I have highlighted, shared with others, or copied to my journal
- search bookmark titles, descriptions, and content to find old links
- browse a graph of past browsing activities, so I can understand which links are related (e.g. which link led me to another link, which links do I move back and forth between)

[Rewind.ai](http://Rewind.ai) has come along, which is extremely impressive! It records zoom calls, videos, browser activity, and much more, and it provides an easy way to search your browser history as well as everything else you are doing on your computer.

Bookmarking leaves you with, at best, an organized list of folders with a mix of aspirational, stale, and heavily used links. I think it's reasonable to guess that most people do not organize their bookmarks at all. Of course there are solutions to some of these individual problems - tools like Pocket help you to organize interesting things that you have read or want to read. There are many browser extensions that give you a more powerful UI to organize and tag your bookmarks. The Arc browser seems to take a more opinionated approach to bookmarking - instead of allowing them to amass and languish, you can put them in a folder or pin them to the top of the browser sidebar, which caused me to be more hesitant to bookmark things, which is probably a good thing.

My ideal bookmarking tool would allow me to:

- Quickly tag interesting sites
- Add more context around a bookmark
- Embed bookmarks in a larger note. I would like to be able to put more meaningful structure around my bookmarks than simple tags. For example, when planning a backpacking trip, I'd love to have a single browser with just the relevant links open, and "bookmarking" is just the act of putting the link in the note for the trip.

I find myself wanting a more powerful tool for browsing the internet, bookmarking, taking notes, and browsing past activity. Recently I've wondered if it's possible to mash together a note-taking tool and a browser together in order to address all my desires for browser history and bookmarking all at once. Imagine if Arc and Notion were one tool? I'm pretty excited by the idea, but it needs a lot more thought.

# Better tools for planning backpacking routes

I go on backpacking trips several times each year, and recently I've been getting more into off-trail backpacking, which requires thorough planning. GaiaGPS and Caltopo seem to be the go-to apps for trail maps, route planning, and viewing layers of information on top of the map (e.g. slope angle shading, snowpack depth).

These tools are great, but they fall far short of the quality I have grown accustomed to after building and using well-crafted software. I used to work on [Remix](https://www.remix.com/), a product that cities can use to plan their transit infrastructure. Imagine Google Maps with route-drawing tools and more data overlays. The snappy route-drawing experience, clean design, and excellent usability of Remix starkly contrasts the slower, jankier experience of using GaiaGPS and Caltopo (particularly GaiaGPS, which has a very buggy and janky route-drawing experience).

While this is just a "build a better app" idea, it would be a ton of fun to work on since I like the outdoors so much. Though I may be downplaying the potential of this idea; whenever there are software categories where the best-in-class solutions are difficult to use and better UX is never prioritized, those best-in-class solutions seem to get replaced by software that understands the value of great UX.

I also have a sneaking suspicion that there are opportunities to build better software for outdoor professionals (e.g. wildland firefighters, search and rescue), though I haven't validated this yet.

# Design system tools

I've spent a lot of time in my career working with design systems, both as a designer and as an engineer. I've had a few different ideas in this space, and I actually [worked on one of these ideas](/blog/composer) for a few months.

# App data catalog developer tooling

Working in observability, the UI could change pretty drastically depending on the different permutations of data the user was viewing. Observability software has lots of rich user interfaces that allow you to filter, group, and augment charts and tables, often with data streaming in real-time. While working on these products, I noticed how easy it was for the UI to break in subtle ways without rigorous automated or manual testing. A common practice is to have local test data that can be used for changing existing code or working on new features, but it is easy for this to get out of date, and it is difficult to capture the variations, complexity, and nuance of real production data.

It would be cool to automatically record a data catalog based on different types of production data (somehow anonymized, of course) that could be used for local development (and probably in other ways I haven't thought about yet). It would also be cool to be able to generate screenshots of the UI with these different types of data, and possibly run visual regression tests over those screenshots. Perhaps it could also help catch unexpected variants in the data, like new response structures, new types of errors, etc. I think there is at least one really cool develop tool idea here!

# Software for construction?

I worked several summers doing drywall cleanup, stucco, and painting, and I ran an IT consultancy in college and had several construction companies as clients. The software they used to do their jobs is truly attrocious, and my understanding is that it hasn't improved much. I still know lots of people at these construction companies that would be happy to tell me all about the software they use and what they wish was different about it.
