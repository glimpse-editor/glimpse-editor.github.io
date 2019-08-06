---
title: "Completing Our First Month"
date: 2019-08-05T17:07:16+01:00
draft: true
---
As we approach the end of this project's first month we would like to thank everyone that has gotten involved, contributed to and supported this project so far. The wider community's enthusiasm for Glimpse has been amazing to see, and we hope we can keep that energy going through August and produce our first stable release very soon.

Let us proceed with the latest updates from week 4!

## Code changes
We changed the name of our current development branch based on the GNU Image Manipulation Project 2.10.12 codebase from "gimp2-10" to "dev-g210" so its purpose is clearer to new project members.

Bobby Moss cleared away more redundant UI themes, updated the web links in the Help menu and fixed the application name displayed when you create a new image or see error messages. He also updated his "helper scripts" after feedback from joshg.

Mathieu Bridon has started sharing the Flatpak build fixes he previously submitted upstream with us, and igalic reviewed the existing code build steps and started troubleshooting problems such as a blank `README` file being required and the final built executable still being called `gimp2-10`.

## Community Decisions
There was a lot of discussion about a potential rewrite of the codebase, and you can read more about the results of that in the "Future Plans After Glimpse 2.0" section of this blog post. We also decided to postpone any decision on the choice of language for any potential future rewrite until criteria have been determined for that decision.

We also considered whether Github was still an appropriate place to host our code and feature/bug tracking issues. There seems to be no great desire to switch to another platform, but we have had offers to share infrastructure with other projects if we ever change our mind (eg. GNOME project have offered us space in the "world" namespace, and Florence project have offered us access to their Gitea server)

The issues and milestones we have on Github were also rearranged to confirm our current understanding about the project's future direction: https://github.com/glimpse-editor/Glimpse/issues

Melody found an excellent wiki site produced by upstream about their plans for improvements to the GNU Image Manipulation Program's UI: https://gui.gimp.org/index.php?title=GIMP_GUI_Redesign. She is currently assessing how much of this could still be useful for us as much of the information has not been updated for quite some time. She also suggested we provide a wiki or image dump mechanism so examples and user studies could be stored in a useful location.

Potential future monetization options were also discussed. That open discussion will be picked up again later because the feedback we received is that we need to make sure any choices we make on this sensitive topic are practical, effective and not user-hostile.

There was also discussion about a potential new save file format. We learned that OpenRaster is intended as more of an archive format than one likely to be used on a day-to-day basis, and that XCF is exensible. That opens up the possibility of storing undo steps and other file-specific functionality in future releases.

There was also general support for "non-destructive changes" and discussion of how that might be achieved. We understand this is being actively developed as part of the GEGL library, so could wait for those changes instead of implementing them ourselves.

Bobby Moss agreed with sponsor contributors' submitted issues after "dogfooding" the pre-release version of Glimpse that we should update patterns, brushes and templates if we can for 1.0 as these are long-standing problems whose fixes could have a big user impact. It may get pushed out if this turns out to be hard to achieve.

A new issue was raised by the community about producing multiple output formats from the same save file instead of relying on users not saving destructive changes. It can be tracked here: https://github.com/glimpse-editor/Glimpse/issues/61

## Website Updates
Bobby Moss plans to move this Hugo site to the project's build server once it has been provisioned to keep costs low. He expects this to happen within the next two weeks.

Chaomodus also provisioned a new MediaWiki instance for our project to use. It is available via https://wiki.getglimpse.app and over time we will populate this with helpful project information, user guides and design work.

## Future Plans After Glimpse 1.0
There was a lot of discussion this week about the practical questions we may need to answer as part of a full code rewrite. In theory it is possible because most of the core functionality is now contained within the GEGL and BABL libraries. GNU Image Manipulation Program 2.10 primarily forms the graphical user interface, plug-in framework, help pages and other supplementary functionality so the learning curve is much shallower than we expected.

A rewrite would be beneficial because we can spend time designing a new GUI with feedback from end users, eliminate decades of unneeded code and would have full freedom over the tools and technologies we want to use. However, such an undertaking would require a considerable amount of time, people and resources to produce. The most practical route seems to be to develop our own new codebase and improve the existing one at the same time in two "streams".

1.x will be the "stream" that iterates new features and improvements on top of the existing GNU Image Manipulation Program 2.10.12 codebase. Helpful upstream changes would be incorporated periodically, and this would be the supported codebase for the time being.

2.x will be the "stream" that is written entirely by our project. This would be slowly developed over a number of years, may produce cool changes that are subsequently backported to 1.x, and would be what we eventually switch to once it is fully ready.

Of course this could all be "pie in the sky" thinking as this project has only existed for a month so far! However, we think some long term planning about the future direction of the Glimpse project will help us focus our discussions and better assess the long term ramifications of our current decision-making.
