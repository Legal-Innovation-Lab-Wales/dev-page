---
layout: blog
author: Ieuan
full-name: Ieuan Skinner
category: Our Approach
short-title: getting-real
full-title: Getting Real - The Useful Bits
file-type: md
publish-date: January 28
publish-year: 2022
card-color: yellow
---

# Getting Real - The Useful Bits

## Introduction

A lot of the modern software development we do at LILW requires us to build secure, feature-filled web applications as fast and economically as we can. Oftentimes we’ve found ourselves creating software that is so feature-full that it would typically necessitate the founding of a new start-up to be fully realised. The timelines we work to on these projects match the fast-paced style those start-ups would need in order to survive.

As a result of this, we choose to build our web apps in Ruby on Rails (Rails) although, to be frank, all of the reasons we have for using Rails are likely equally applicable to any other modern web-app framework (such as Django) and were we to upskill ourselves to be as knowledgeable on those frameworks as we are on Rails then the ultimate time-saving we’d achieve as a team would likely be negligible because as it turns out a lot of the modern tools used to build some of the most large-scale, complex software on the planet are all really *really* good.

So if the tools aren’t the biggest source of efficiency *wins* when it comes to building our software then what is? ... It’s our approach and processes of course! If you’re familiar with software development then this will come as no surprise, the “Agile Approach” to software development has been a long-established doctrine, and whilst there’s plenty to gain from this approach (and we follow it at the lab where applicable) it both benefits and suffers from abstraction.

Rails is a very opinionated framework. It isn't afraid to say "do it this way, this way works, we think this is the best approach". Getting Real takes the same blunt approach to the overall product life cycle, from finding funding to interface design.

## The Useful Bits

When I started reading "Getting Real" I decided that I would fold the page whenever I found a piece of advice and/or rule that I felt we at the lab either could benefit from or were benefiting from as a part of our current approach. That way by the end of the book I could simply write up these rules as a neat concise listicle. However, by the end of my reading, I wound up with a copy that looked like this:

![book.png](../../../assets/images/ieuan/book.png)

The chunk at the bottom of that image is predominantly introductory filler and the chunk about 3/4 of the way through is in regards to pricing, as you can see a lot of the advice excluding these sections I found to be quite useful, and as such I've had to limit my selections further for the sake of brevity and so will only present what are, in my opinion, the most important bits of advice.

**[Fix Time and Budget, Flex Scope](https://basecamp.com/gettingreal/02.4-fix-time-and-budget-flex-scope)**
The heading essentially captures the essence of this advice; if you're able to be flexible with scope then you'll be more able to deliver on time and launching something great that's slightly smaller in scope is better than launching something mediocre and full of holes.

> How does a project get to be a year behind schedule? One day at a time. 😂
>

**[The Three Musketeers](https://basecamp.com/gettingreal/03.3-the-three-musketeers)**
The sub-head for this advice reads ***Use a team of three for version 1.0*** and that effectively encapsulates the advice. There's not much in the way of justification for this (yet) but anecdotally I'd have to agree this is a sweet spot number for starting any project.

**[Embrace Constraints](https://basecamp.com/gettingreal/03.4-embrace-constraints)**
Again this advice is neatly encompassed by its sub-heading: ***Let limitations guide you to creative solutions***. Relaying their own experience building Basecamp, 37signals outlines here how constraints can often become advantages if you can find ways to work with them rather than bleeding your time and energy into fighting them.

**[What's the Big Idea](https://basecamp.com/gettingreal/04.1-whats-the-big-idea)**
This is an idea that I don't believe we've fully embraced at the lab yet, however, I really like the simplicity of it and think it could be useful to us. The gist of it is to explicitly define the one-point vision for the apps you build and to examine the changes you make against that vision i.e. are these changes helping or hindering this vision? Are we straying in pursuit of something that is separate from the vision of this app?

37signals list the vision for each of their apps and provide some example extracts to justify this approach. They neatly end with ***Make the big decision about your vision upfront and all your future little decisions become much easier*** and I ultimately feel that this is where the big time-save comes from.

**[Ignore Details Early On](https://basecamp.com/gettingreal/04.2-ignore-details-early-on)**
This is a rather self-explanatory piece of advice but it is very easy to ignore. I appreciate the analogy to that of drawing wherein you don't begin by drawing the details right away, rather you begin by sketching the proportions for a scene and build up from there.

**[From Idea to Implementation](https://basecamp.com/gettingreal/06.3-from-idea-to-implementation)**
Here 37signals give a quick overview of their approach to the initial stages of web-app design which consists of **brainstorm → sketches → HTML → coding**, this isn't an approach I've taken as I've never been much of an artist so I find producing sketches daunting however a compelling case is made that even dirty "scrawl stuff" can be valuable at the outset.

**[Avoid Preferences](https://basecamp.com/gettingreal/06.4-avoid-preferences)**
A good piece of advice I've failed to follow is to avoid including preferences and just make a decision up front so the customer doesn't have to. The scenario is given about "messages per page" and including an option to choose "25, 50, or 100" is an **exact** position I've found myself in prior to reading this book, and at the time I decided to include the preference options as it seemed easier than having to make a decision myself and potentially getting it wrong. In the future, I'll be sure to ***make the call*** as the authors put it and avoid the costs that come with preferences.

**["Done!"](https://basecamp.com/gettingreal/06.5-done)**
Like many before the sub-heading neatly captures this advice as ***Decisions are temporary so make the call and move on***. Along with this advice is a snippet from Derek Sivers that neatly captures the relationship between good ideas and good execution, headlined *Be An Executioner* it can be found [here](https://basecamp.com/gettingreal/06.5-done#be-an-executioner).

**[Alone Time](https://basecamp.com/gettingreal/07.2-alone-time)**
To anybody who has worked as a software developer, this advice will probably be the most obvious and most precious, here 37signals outline the need to allow devs the time, space, and silence needed to enter the flow state from which maximal productivity and performance can be achieved.

Of course, this concept isn't just true for software developers, "the zone" is a concept that can transcend a lot of disciplines, and wherever it is applicable so too is the advice that ***People need uninterrupted time to get things done.***

**[Interface First](https://basecamp.com/gettingreal/09.1-interface-first)**
The whole ***Interface Design*** section of Getting Real that begins with this advice is honestly [worth a read](https://basecamp.com/gettingreal/09.1-interface-first) but I'll highlight 3 pieces I found very useful starting with this. Interface first might sound obvious but I've worked on projects where programming begins before design and more often than not this approach leads to headaches, design is relatively easy to change whereas assumptions about design that get baked into your code in the absence of a design are not so I'm in full-throated agreement with this: Interface 👏 First 👏

**[Three State Solution](https://basecamp.com/gettingreal/09.3-three-state-solution)**
This advice posits that there are 3 states you should effectively design all of your screens for, these are:

**Regular -** The screen people see when everything's working fine and your app is flush with data.
**Blank -** The screen people see when using the app for the first time before data is entered.
**Error -** The screen people see when something goes wrong.

This is (as all good advice tends to be) seemingly obvious however I know from experience that it's very easy when building new screens in a development environment that is flush with data to completely forgo the blank state or similarly to get so used to seeing your web-app working that you neglect to consider the error state entirely, therefore, I definitely think having this put so concisely makes it a useful bit of advice.

**[One Interface](https://basecamp.com/gettingreal/09.8-one-interface)**
The sub-heading here reads ***Incorporate admin functions into the public interface***. This advice I think is best taken with a grain of salt as it's certainly the case that some admin functions are so separate to anything that a typical user can either see or do that they will require their own screen however I think the points raised around the maintainability of 2 separate interfaces are completely fair and ultimately this is a useful bit of advice I'll try to follow.

**[Code Speaks](https://basecamp.com/gettingreal/10.3-code-speaks)**
This advice was quite jarring to me at first as it seemed to run contrary to the previous design-first approach and so I felt the authors had contradicted themselves and introduced confusion. However as I thought on it more I realised that what this advice is saying isn't that you should code-first and *then* design but that **as you are implementing your design in code** you should reflect on your design and if your code is beginning to shape a design element in a particular way (i.e. *this* way is far more practical than *that* way) then you should listen as often this pathfinding approach can be indicative of a positive direction.

Though I do think the Martin Fowler quote is very unhelpful.

**[There's Nothing Functional about a Functional Spec](https://basecamp.com/gettingreal/11.1-theres-nothing-functional-about-afunctional-spec)**
This advice felt a bit like a slap in the face as I had just begun working on what was in effect a functional specification for a web app we had built when I read it. Spanning 3 pages (possibly the longest piece of advice they've given) 37signals meticulously layout why functional specs can be, and often are, a waste of time.

**[Tell Me a Quick Story](https://basecamp.com/gettingreal/11.3-tell-me-a-quick-story)**
37signals sum this up best as *If you do find yourself requiring words to explain a new feature or concept, write a brief story about it. Don't get into the technical or design details, just tell a quick story. Do it in a human way, like you would in a normal conversation.*

Part of our success in the lab (I feel) has been our ability to do the above, we always try and treat software development and feature design as a collaborative effort that we can get into engineering quibbles about behind the scenes whereas when we talk things through with academics or other non-developers we try to keep the conversation as human as possible and thus far it has worked well.

**[Answer Quick](https://basecamp.com/gettingreal/14.3-answer-quick)**
***Quick turnaround time on support queries should be a top priority.*** Whether it's by virtue of being a small team or the ethos we've unspokenly agreed too I also feel that part of our success has also been in following this advice. The inverse of this advice also holds true in that if you don't maintain a quick turnaround for answering support queries then the people you need to work with you in order to get things done will be less and less likely to want to work with you going forward and as that relationship deteriorates so too can your team's reputation.

**[Tough Love](https://basecamp.com/gettingreal/14.4-tough-love)**
Another seemingly obvious piece of advice but being willing to say *no* when it comes to feature requests and scope is a big part of what makes a software project successful. At the lab, we're very good at being honest and upfront with stakeholders as we have enough autonomy that we don't need to be "yes-men" in order to survive.

**[Keep The Posts Coming](https://basecamp.com/gettingreal/15.2-keep-the-posts-coming)**
I've never *had* to maintain a developer blog on a web app before and it's unlikely we'd create a blog for the web apps we build at the lab but there's some other useful advice in here I'm sure we will use such as FAQs, How-Tos and Tips & Tricks.

**[All Bugs Are Not Created Equal](https://basecamp.com/gettingreal/15.4-all-bugs-are-not-created-equal)**
Prioritization is of course useful but the bolder advice given here is that "yes, you can ignore some bugs". I've seen a lot of software projects where inordinate resources go toward addressing some minor visual "bug" that only occurs in some niché context (sometimes so niché the only person who can seem to replicate it is the person who raised it in the first place 😂) and frankly they're never worth the effort in the long term.

As Voltaire once said (sort of) "Don't let perfect be the enemy of good".

**[Ride Out The Storm](https://basecamp.com/gettingreal/15.5-ride-out-the-storm)**
This is some advice I could have used much earlier in my career and I will be certain to carry it forward from now on. To be frank I can't paraphrase it any better so I'd suggest reading the whole piece linked above.

**[Beware The Bloat Monster](https://basecamp.com/gettingreal/15.7-beware-the-bloat-monster)**
This final piece of advice is aimed at mature software projects where most before it were considering projects in their early stages. Avoiding bloat might seem like an obvious piece of advice but the bolder, less obvious advice I feel is when 37signals say ***New doesn't always mean improved. Sometimes there's a point where you should just let a product be.***