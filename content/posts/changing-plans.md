---
title: "Changing Plans"
date: 2020-03-17T21:30:00+00:00
draft: false
---
Check out our [Contribute](/contribute/) page for social media and news links to follow our progress.

## Glimpse Image Editor updated on Snapcraft
We are pleased to announce that the Snapcraft version of Glimpse Image Editor was updated to 0.1.2 on 2019-03-12. The feedback we have received about this so far has been very positive.

Bobby Moss also worked with Heather Ellsworth to ensure that the “edge” and “beta” channels used by this community-supported download source builds from the correct Github branches, and that the app store text matches what we use for Flathub.

You can find out more here: https://snapcraft.io/glimpse-editor

## Adapting to the Coronavirus (COVID-19) pandemic
We would like to reassure our end users, followers and supporters that we take this public health crisis very seriously. The project is taking action to ensure that development continues for as long as possible, and that you are not left without feature improvements and security updates.

We have advised our contributors to avoid attending any free software or Linux conferences on our behalf, and our planned releases over the next six months have also been changed to account for more intermittent contributions from our existing project members. This blog post goes into more detail about that in the "Updated release schedule and priorities" section.

Finally, we would like to ask all our users to be patient with us over the coming months if there is a delayed response to bug tickets, feature requests, merge approvals, and questions on social media. Our contributors and their families are just as susceptible to COVID-19 as you are, but we will do our best to assist you.

* Find out how to help our project progress: https://glimpse-editor.org/contribute/
* Bolster our funding reserves on Open Collective: https://opencollective.com/glimpse
* Help the GNU Image Manipulation Program too: https://www.gimp.org/donating/

## Updated release schedule and priorities
We have decided to create a 0.1.4 release and continue working on the same GNU Image Manipulation 2.10.12 base for the time being instead of creating a new 0.2.0 release based on 2.10.18.

The reason for that decision is we want to spend more time fixing bugs and packaging our software for a wider audience. We also expect to have reduced capacity for changes over the next six months, so completely re-basing our hard fork will likely prevent us from working on more meaningful changes.

However, you will not miss out on upstream fixes and improvements. We intend to package Glimpse Image Editor 0.1.4 with new versions of GEGL, BABL and other libraries. Also useful features such as the new high contrast themes and update checker will be backported. We also still plan to pre-bundle useful plugins such as G'MIC.

We will focus on new release packaging first, and aim to release Linux AppImages for 0.1.2 before the end of March 2020, and an MSIX file for those using Windows 10 on their workplace machines in April 2020.

The other big changes coming for Glimpse Image Editor 0.1.4 are that we intend to fix the man pages (finally!) and refactor libgimp so that distribution maintainers can package our software without having to mark the GNU Image Manipulation Program as a conflict in their repositories.

Chaomodus will also be working on Jenkins build infrastructure. They will also be evaluating how we can better manage and improve our non-English translations.

We aim to release Glimpse Image Editor 0.1.4 in May 2020, but that is subject to change based on how well we progress. After 0.1.4 is released we will immediately start work on the macOS port, but if we have spare capacity we will begin work on it sooner.

You can see a provisional list of all the planned features and fixes here: https://github.com/glimpse-editor/Glimpse/milestone/12

## Download figures update
All figures were correct on the day this blog post was published and sources have been provided so that you can verify our claims. If the figures are accurate then we would consider this to be a good start for our project, and can confirm that the number of downloads has ramped up significantly since 2020-01-31. [Source](/posts/progress-on-our-first-errata-release/)

We know that Glimpse Image Editor has been downloaded at least 12544 (+5684) times across all platforms and download sources since it was first released on 2019-11-22. A detailed breakdown is provided below.

### Linux
Glimpse Image Editor has been downloaded 5274 (+1084) times from Flathub since it was first released. [Source](https://gitlab.com/ahayzen/flathub-api-stats-generator)

Heather Ellsworth reports that there are 1623 (-7) active users that have installed Glimpse Image Editor through Snapcraft. [Source](/glimpse-snap-2020-03-14.png)

The distribution tarballs we provided on Github for Glimpse Image Editor 0.1.2 have been downloaded 53 times, suggesting that there is some early interest from Linux distro maintainers about hosting our software natively in their repositories. [Source](https://somsubhra.github.io/github-release-stats/?username=glimpse-editor&repository=Glimpse)

We do not have the figures for other community-supported Linux download sources.

### Windows
The new Glimpse Image Editor 0.1.2 installer has been downloaded 552 times from Github since its release on 2020-03-02. [Source](https://somsubhra.github.io/github-release-stats/?username=glimpse-editor&repository=Glimpse)

To date there have been 4951 (+761) direct downloads of Glimpse Image Editor 0.1.0 for Windows from Github. [Source](https://somsubhra.github.io/github-release-stats/?username=glimpse-editor&repository=Glimpse)

There are two new unofficial third-party download sources for Windows users that provide download statistics:

* 62 downloads from [Softpedia](https://www.softpedia.com/dyn-search.php?search_term=glimpse)
* 29 downloads from SourceForge (Link no longer available - Feb 2021)
