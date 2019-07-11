---
title: "About"
date: 2019-07-08T20:25:21+01:00
draft: false
menu: "main"
---
## Contents {#contents}
- [What is wrong with the "GIMP" name?](#what-is-wrong-with-the-gimp-name)
- [Why are you forking?](#why-are-you-forking)
- [Is forking the project a duplication of effort?](#is-forking-the-project-a-duplication-of-effort)
- [Will you contribute changes back upstream?](#will-you-contribute-changes-back-upstream)
- [This project is big! Will it take a long time to rebrand?](#this-project-is-big-will-it-take-a-long-time-to-rebrand)
- [Why did you change the mascot?](#why-did-you-change-the-mascot)
- [Did you know that name is used elsewhere?](#did-you-know-that-name-is-used-elsewhere)
- [What if I find the word "Glimpse" offensive?](#what-if-i-find-the-word-glimpse-offensive)
- [Where is the Glimpse code of conduct?](#where-is-the-glimpse-code-of-conduct)
- [Why is there no lead developer on this project?](#why-is-there-no-lead-developer-on-this-project)
- [Why do you need monetary donations?](#why-do-you-need-monetary-donations)

## What is wrong with the "GIMP" name? {#what-is-wrong-with-the-gimp-name}
If English is not your first language, then you may not have realised that the word "gimp" is problematic. In some countries it is considered a slur against disabled people and a playground insult directed at unpopular children. It can also be linked to certain "after dark" activities performed by consenting adults.

You may think that this is "political correctness gone mad" and that those who have been complaining about it for more than a decade are "over-sensitive", but this choice does have real-life consequences. In addition to the pain it can cause to marginalized communities many of us have our own free software advocacy stories about the GNU Image Manipulation Program not being taken seriously as an option by bosses or colleagues in professional settings.

Educational institutions and public libraries may feel unable to provide or recommend the program to students due to possible legal or moral concerns. It can also be difficult for a teacher to keep a class of school-age children disciplined and focussed if they are distracted by the name of the computer program they have been asked to use.

We believe free software should be accessible to everyone, and in this case a re-brand is both a desirable and very straightforward fix that could attract a whole new generation of users and contributors.

[Return to top](#contents)

## Why are you forking? {#why-are-you-forking}
In recent versions of the upstream software you may have noticed that the window titles have switched to "GNU Image Manipulation Program" and the documentation [suggests expanding the acronym](https://www.gimp.org/docs/userfaq.html#i-dont-like-the-name-gimp-will-you-change-it) as a work-around for the bad name. However, we do not think that adequately addresses the issue because the website domain, documentation and wider community still refers to it as "the Gimp" just as they have done for the last two decades.

Feature requests have been raised about the problem multiple times on the project's communication channels over the last 13 years, but each time they are ignored, dismissed and/or the discussions get spammed by those with strong political views.

It is unfortunate that we have to fork the whole project to change the name, but we feel that discussions about the issue are at an impasse and that this is the most positive way forward.

[Return to top](#contents)

## Is forking the project a duplication of effort? {#is-forking-the-project-a-duplication-of-effort}
No, because we are not reimplementing a 20 year old codebase from scratch. Also once we "hard fork" we still intend to apply useful upstream changes rather than completely reimplementing them.

From our point of view we are simply exercising [our software freedoms](https://www.gnu.org/philosophy/free-sw.html) by forking the project and redistributing a modified version for others to benefit from. This is fully in accordance with the spirit and requirements of the [GNU General Public License](https://www.gnu.org/licenses/gpl-3.0.en.html) and [GNU Lesser General Public License](https://www.gnu.org/licenses/lgpl-3.0.en.html) as they both apply to this project.

[Return to top](#contents)

## Will you contribute changes back upstream? {#will-you-contribute-changes-back-upstream}
Absolutely! We intend to be good free software citizens, and as soon as we have made changes that the upstream project want to include in their codebase we will be willing to assist them however we can. We may also donate some of the money we receive from Patreon backers to the upstream project, and the community will determine how much and how often.

While both projects may not agree on some things, it is clear to us that an adversarial attitude will not help either of us. If we work together then the whole free software community can benefit from this fork that attracts new contributors, breathes new life into an ageing codebase and shares free software with a whole new audience.

[Return to top](#contents)

## This project is big! Will it take a long time to rebrand? {#this-project-is-big-will-it-take-a-long-time-to-rebrand}
The first release should appear within weeks because it will just have a cosmetic rebrand, and possibly some fixes or additions to the build system so it works with our choice of modern tools and technologies.

The major refactoring and de-cluttering work will happen in a future release that "hard forks" from version 2.10. At that stage we will be able to consider more radical ideas, new features and fixes that address long-standing complaints.

Also a lot of people have expressed an interest in contributing to this fork, which is definitely speeding up progress. The first few days were particularly frantic as we gathered ideas and feedback from the community and started rolling out their choice of project infrastructure.

[Return to top](#contents)

## Why did you change the mascot? {#why-did-you-change-the-mascot}
We wanted the project to forge its own identity. It is important we use this opportunity to foster new ideas and ways of working, and it may be harder to do that if we are still tied to old decisions made by a different project decades ago.

[Return to top](#contents)

## Did you know that name is used elsewhere? {#did-you-know-that-name-is-used-elsewhere}
Users have made us aware of a few software projects that share the same name as this fork. That is always a risk when you use an English language word, but we do not believe that it will cause problems for end users or hinder the adoption of this program.

[Glympse](https://www.glympse.com/) is a location-sharing application for mobile devices. We think the fact it runs on a different device category entirely, does something completely different, has a very different icon and has their name spelt differently means it is highly unlikely that end users will be confused.

[GLobal IMPlicit SEarch](https://packages.debian.org/sid/text/glimpse) is a file searching utility ported from UNIX that has been spotted buried in Debian's "unstable" repository (it is also mirrored in Ubuntu's "universe" repository). It was abandoned for over a decade, then in 2016 it was picked up again by a maintainer who has since [applied minor patches](https://metadata.ftp-master.debian.org/changelogs//main/g/glimpse/glimpse_4.18.7-4_changelog). A related tool called [WebGlimpse](http://webglimpse.net/) was last updated in 2014. We dispute the idea that this is a "very popular" command line utility, but out of common courtesy we will ensure our GNU/Linux package names do not clash with it.

[Glimpse-soft](https://sourceforge.net/projects/glimpse-soft/) is also an image manipulation program, but it uses completely different code written in Microsoft Visual C++ and has had no new releases since 2004. The sole developer last updated the project's SourceForge page in 2015 but we believe that project has been abandoned for quite some time and does not have an active userbase.

[Return to top](#contents)

## What if I find the word "Glimpse" offensive? {#what-if-i-find-the-word-glimpse-offensive}
This seems unlikely given we checked its meaning in every known language, but if you have a legitimate concern then let us know.

If you are offended by the fact we renamed the project, we suggest you continue using the [GNU Image Manipulation Program](https://www.gimp.org) instead of annoying our contributors and making more work for our moderators.

[Return to top](#contents)


## Where is the Glimpse code of conduct? {#where-is-the-glimpse-code-of-conduct}
There isn't one yet as it is still being discussed by the community, but it is likely to be based on [the contributor covenant](https://www.contributor-covenant.org/) or something similar. As this project spawned from [the fediverse](https://joinmastodon.org/) our experiences in that online space are going to inform the project's future governance and direction.

There is no [benevolent dictator for life](https://en.wikipedia.org/wiki/Benevolent_dictator_for_life) for this fork because we value collective decision-making. We believe a governing group is less fallible, makes better-considered choices and reflects the will of the wider community more accurately. That approach will help us form a robust and fair code of conduct, and we have elaborated more on our current governance structure here: ["Why is there is no lead developer on this project?"](#why-is-there-no-lead-developer-on-this-project)

We also want to make it clear that we value and encourage diverse representation in leadership positions within our community, and we believe that is the best way to form a code of conduct that protects all contributors, promotes wider participation and ensures the rules are fairly enforced. At this early stage our initial governance team is formed entirely of individuals from marginalized communities, and that makes our project [very atypical](https://opensource.com/article/17/9/diversity-and-inclusion-innovation).

We know how important it is to enact the right code of conduct and enforce the rules properly. We want to promote a safe and inclusive environment, not a toxic one. If you have ideas to help us do that and want to get involved with this discussion then please join us in the project's communication channels.

[Return to top](#contents)

## Why is there no lead developer on this project? {#why-is-there-no-lead-developer-on-this-project}
In most free software projects this is a single individual that decides if issues should be ignored, cancelled or implemented. Granting someone that kind of power would effectively make them our "benevolent dictator", and we do not want one of those!

At this early stage we prefer to discuss things with the community first, then make decisions based on consensus between the members of the governance team. It is likely that as Glimpse develops there will be a more formal separation of responsibilities, an agreed way to assess community opinion and a documented path for contributors to participate in the decision-making process.

Our vision for the future is that the community will always have a say in the direction of this project, no choices will ever be impossible to overturn and everyone responsible for decision-making will be held accountable by their fellow contributors. The value or quantity of someone's contributions will not confer any "special status" on them or grant any immunity if they violate our project's code of conduct.

[Return to top](#contents)

## Why do you need monetary donations? {#why-do-you-need-monetary-donations}
Just like many other free software projects we need to host the collaboration tools we use to develop and share the project. We have to purchase domain names, cloud servers and subscriptions from service providers to make this project a success. In addition we also intend to pay the artists we commission for the re-brand and reward our contributors for the value they add.

The accusation we sometimes receive is that we are "stealing money from the GNU Image Manipulation Program". That is completely untrue, and we encourage those that want to support the upstream project to use [this donation page](https://www.gimp.org/donating/). Our project is also already discussing if some of the money we receive should be shared with the upstream project once we have covered our own costs.

If you would like to donate some money to Glimpse project, you can do so by [becoming a patron](https://www.patreon.com/glimpse) on Patreon.

[Return to top](#contents)
