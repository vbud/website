---
title: "Triads: from idealism to realism"
description: "What I've learned about how to structure EPD teams"
pubDate: "Mar 30 2023"
tag: "tech"
---

# Triads

Back in 2019, I had the opportunity to help redesign the EPD (engineering, product, and design) organization of the company I worked at. Among other changes, I rolled out the Triad model, and I wanted to write down what I learned from that experience.

tl;dr: Triads are useful, and they aim to address very real problems, but they also can introduce new problems. After being a strong proponent of them for many years, if I am ever in the position of designing EPD processes again, I would choose a more flexible “Leads” model that aims to achieve the same benefits without the same downsides.

# What are Triads and why do they exist?

Every software team I have been on has dealt with the same age-old questions:

- How are roles and responsibilities divided between engineering, product, and design?
- Who is in charge of defining what projects the team works on and the scope of those projects, and who gets to participate?

A common model that I have encountered in my career is the Triad. “Triad” is one of several terms (”tripod”, “leads”, "three-legged stool”) to describe the cross-functional leadership of a software team: tech lead (TL), product manager (PM), and designer. They set goals together and attend similar meetings. They try to stay a step ahead of the rest of the team, and they typically take responsibility for updating and aligning with leadership.

While there are many purported benefits to introducing Triads, the most important among them is to address the problem and consequences of not "starting together". For example, an engineer might just start building something and the designer didn’t have enough time to think through the workflow, or a PM commits to building something without running the problem by engineering and design first. Not “starting together” leaves people feeling justifiably frustrated and often results in lower quality outcomes.

# Great Triads

Much has been written about what makes great tech leads, product managers, and designers. Instead of addressing each role individually, I’ll summarize the attributes of the best Triads I’ve worked with:

- Great Triads maintain momentum and relentlessly seek clarity.
- Great Triads work ahead of the team to ensure product specs, tech specs, and designs all exist before the team needs them.
- Great Triads work well with management, ensuring alignment, advocating for the team when appropriate, and alerting management if a project is falling behind or if new information changes the scope of the project.
- Great Triads don’t view their roles too rigidly. They work with the strengths, weaknesses, and interests they have. For example, the designer may decide to let the PM run point on user research because they know the space better than the designer.
- Great Triads provide opportunities for others to lead and grow, and they are not gatekeepers of information from the rest of their teams.
- Great Triads share information at key points of clarity with the other ICs on their team, leadership, and other stakeholders.
- Great Triads take responsibility for the outcomes of their team, good or bad.
- Great Triads have mutual respect for each of the 3 disciplines (engineering, product, and design), and all 3 disciplines are considered to be a part of the team, instead of product and design feeling like external resources.
- Great Triads ensure there is ample time for product discovery to ensure that the team is building the right thing.
- Great Triads ensure the software they deliver meets or exceeds the quality bar set by the company.

# Problems that arise

While I have had many good experiences with the Triad model, I’ve also encountered recurring problems that make me skeptical that it is the best model to roll out uniformly across a Product organization.

## “Start together” can be taken too far

"Starting together” can be taken too far in two ways:

1. Leadership may feel the need to “start together” when taking on a new product initiative that will disrupt current teams’ roadmaps.
2. ICs on a product may feel left out from their team’s Triad and start pushing for the whole team to always “start together”.

Sometimes, information asymmetry is the best option, and “starting together” just isn’t possible.

Perhaps a CEO needs to pivot a team or an entire organization to solve a new problem. There is often no clean way to do this. Existing teams need to focus on finishing their current initiatives, and the CEO needs to spend time honing the new vision and goals. The CEO is, in fact, “starting together”, just with their heads of engineering, product, and design.

Or perhaps one or two ICs on a software team feels left out of the triad, and they propose involving the _whole team_ to product discovery activities. Now the meeting pressure has increased dramatically for every member of a team. This is very impractical for most teams, and usually it’s only one or two vocal people who really care about this. Instead of trying to formalize this into a process, find opportunities for these individuals, assuming they are ready! Sometimes there are vocal people who just aren’t ready for more responsibility, and that’s feedback they need to receive from their manager.

Ultimately, some research and decisions have to be made by key individuals with good judgment.

## The ambiguous role of the EM

Some organizations have EM / tech lead hybrids, and some do not. If the EM is not also the tech lead, that can result in introducing a fourth member to the triad. The EM’s role in modern tech companies, how many reports they have, and if they should also code is a broader topic that I don’t want to address in this post, but suffice to say that some types of EM roles can complicate applying the Triad model to all companies, or even to all software teams at a company.

## The Triad thinks they have to do everything together

Most Triads realize that it isn’t sustainable to do everything together and back off, even if they try this initially. But members of the triad can still have an uncomfortably high meeting load.

## Not all initiatives require a Triad

Some teams don’t have as much of a need for a designer or a PM. For example, perhaps the lead engineer is best suited to act as the PM (e.g. for a very technical feature, like an integration).

While mostly a nomenclature annoyance, it feels strange for management to have to think about Triads of various sizes.

## Who leads the Triad?

I’ve seen Triads where all members are nervous to be assertive or move the ball forward, so they try to run the triad by consensus, and as a result, decisions happen slowly.

This is probably the most common major issue I’ve seen with triads. “Three leaders” of a team is a lot of leaders. In consensus-oriented teams and cultures, they may frequently call in a head of product or engineering to deal with uncertainty or disagreement instead of resolving it themselves.

This is typically more of a failure of management to choose the right people for Triads, but it’s an outcome that happens frequently enough to warrant some thought. Triad members should be chosen for their leadership abilities. You need at least one (ideally more than one) triad member who can really move decisions forward, seek and find clarity, and take responsibility for good outcomes and functioning of the triad and the team.

Finally, because the Triad is perceived as a unit to the rest of the company, meetings tend to be large, and there is no one leader to have a candid 1:1 with for difficult discussions.

# If I had to do it again

If I needed to design an EPD organization again in the future, I would not require a Triad to have three members, and consequently I would stop using the term “Triad”. It’s too rigid. I’d probably try something like “Leads” to more naturally allow for various team/project leadership configurations. For example, some projects do not need (or may just need infrequent consultation with) a PM or a designer. This would also give management the flexibility to appoint a single Lead to a project, which is helpful for certain kinds of initiatives. I would give serious thought to taking it a step further and appointing a single DRI (directly responsible individual) to take a project to completion, and then ensure those DRIs know best practices like “starting together” with their peers. There is definitely a risk of making non-engineers feel like second class citizens in the DRI model, but I think this risk can be mostly mitigated.

I would invest more heavily in coaching anyone taking a leadership role on a team, especially if they are new to the role. A lot of the issues I encountered with Triads came down to unclear expectations for individuals' roles and for how to handle common situations that Triads run into. For example, a designer may not be used to being in a position to “start together” with their engineering and product management peers. They might take more of a back seat in the triad, or they may reach for agency-style techniques that do not fit well in a modern software development team (I’ve seen both of these happen, and both are coachable).

Something else I have noticed (not unique to Triads) is that someone on the team's leadership must have a strong vision for the initiative they are working on. Without this, “design by committee” starts to happen. This further reinforces a point I mentioned already about management needing to select the right people for a Triad. Regardless of any particular organizational design, management selection of a team’s composition, particularly the team's leader(s), seems to me to be the determining factor in a given initiative’s success (assuming the overall strategy is good, which is a separate topic).

# Closing thoughts

This is a pretty big topic that is closely tied to other tricky aspects of running an EPD organization, so there are some topics I intentionally brushed over in order to stay focused on the topic of Triads.

I honestly found it difficult to call this post "done". I kept thinking of scenarios that might not be handled by what I have written, or I will remember a different solution someone told me about years ago.

I think it's difficult for me to write about organizational design and process because I want to "solve" the problem once and for all. I'm approaching it like a programming problem, and it just isn't. Humans are messy, and groups of humans interacting with other groups of humans are even messier.

When designing an organization and its processes, my advice is as follows:

- Do something reasonable. Don't just create meetings to "align" or "collaborate" better. Get really clear on what you're trying to solve with a re-org or a process. You might find you don't even need a new process; you might just need to raise the quality bar, or you might need to make some personnel changes.
- Keep an open mind and stay flexible, while also not compromising on important company goals and cultural values.
- Learn about the roles you are less familiar with. If you're an engineering leader who now finds yourself in charge of an entire EPD organization, take some time to understand what great design and product management look like. Do not just delegate these roles entirely - it's your responsibility to ensure all three functions are working together effectively.
- Iterate on your processes and ask for feedback, but also don't change process too often, because that creates a ton of work for your ICs, and they will get disillusioned by frequent changes.
- Be ok with some degree of messiness! If you've designed a process that works well for 80% of your teams, that's a win in my opinion.

Thanks for reading!
