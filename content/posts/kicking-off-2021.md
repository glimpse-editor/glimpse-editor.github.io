---
title: "Kicking Off 2021"
date: 2021-01-11T21:30:00+00:00
draft: false
---
Check out our [Contribute](/contribute/) page for social media and news links to follow our progress. You can also review our project's success so far and long term plans in our previous blog post, [A Year In Summary](/posts/a-year-in-summary/).

## Old versions of Glimpse Image Editor now available on Archive.org
Previously you could only find older releases [on Github](https://github.com/glimpse-editor/Glimpse/releases). To assist any users that are unable or unwilling to use that service, and to preserve Glimpse Image Editor for posterity, we have now started uploading our old release binaries and source code to [archive.org](https://archive.org/search.php?query=creator%3A%22Glimpse+Project%22).

## We fixed our Linux AppImage
Some of you may have spotted that our [Linux AppImage](https://appimage.github.io/Glimpse-Image-Editor/) was missing [important components](https://github.com/glimpse-editor/Glimpse/issues/510) for a number of weeks in December 2020 and January 2021. That was due to [a bug in the AppImage Creator](https://github.com/AppImageCrafters/appimage-builder/issues/78) software, and we are grateful to [Alexis López Zubieta](https://github.com/azubieta) for fixing the problem in that external project quickly.

## Changes to our internal project communications
On Friday 15th January 2021, we will finally be closing our two remaining Matrix channels (they are already invite-only). Both were originally started in July 2019 as a replacement for a freenode IRC channel, and they were particularly useful during the early development of Glimpse Image Editor.

It has been clear for some time that our project has outgrown those channels, and most activity is now happening on [our Discord server](https://discord.gg/hZhRceq), which we first launched in May 2020 to support the development of Glimpse NX. 

In December 2020, our contributors investigated the possibility of hosting a communication bridge between Matrix and Discord. Unfortunately this proved to be time-consuming and impractical to maintain over the longer term for a project of our size. After many in-depth discussions with our contributors, the Glimpse governance team has approved the decision to fully move our project communications across to Discord.

We know that some of you will have strong opinions about this decision. Before providing feedback to us on social media, we encourage you to read the FAQ answer that fully explains the story and reasoning behind the decision we made here: ["Why are you deprecating your Matrix channels?"](/about/#why-are-you-deprecating-your-matrix-channels)

## Updated plans for Glimpse Image Editor 0.2.2
We had previously intended to provide a fully-fleged Glimpse Image Editor 0.2.2 release this month on both Windows and Linux. However, we are not part of a larger organization and our open source project relies entirely on unpaid volunteer contributions, so we are not immune from the impact of everything that has been going on in the world over the last six months. We have had to adapt our approach so that we can take care of our contributors and still deliver a good experience for our users.

We are having problems improving our Windows port because of bugs in the tools we rely on as part of the build process. Also, we are not able to incorporate many of the assets provided in the PhotoGIMP plugin due to ambiguous licensing terms for their use and redistribution. We will need more time to find solutions and workarounds for both of those problems.

Our plan to start providing tarballs that have had `make dist` run against them again has also been postponed until we release Glimpse Image Editor 0.3.0. The specific version of the GNU Image Manipulation Program we used as a base for Glimpse Image Editor 0.2.x has known bugs that prevent us from doing this, and the multiple changes required to fix that problem are time-consuming to backport, so we have chosen to wait until we re-base on a newer version of the GNU I.M.P.

Given that the Windows build for Glimpse Image Editor 0.2.0 is already stable and recent changes do not significantly improve the user experience, we have concluded that it makes sense to skip a release for that platform. We will re-engineer our Windows build process ready for Glimpse Image Editor 0.3.0 (expected in July 2021) to avoid encountering the same build problems in future.

Linux users will still receive a smaller "micro-update" later this month (January 2021) that applies backported patches, updates dependency versions and introduces minor feature improvements, such as being able to increase the UI font size in **Edit** > **Preferences** > **Themes**. This micro-update will still be tagged as `v0.2.2` in our Github repository as normal, so automated packaging processes should be able to deploy our changes to existing installations without any problems. You can preview these changes on our [Linux AppImage](https://appimage.github.io/Glimpse-Image-Editor/).

We sincerely apologize to anyone that we have disappointed with this change of plans. We hope that you can understand that we are unpaid volunteers, and we are doing the best we can under difficult circumstances with the limited time and resources that we have available.
