---
title: "About (FAQs)"
date: 2021-02-18T23:45:00+00:00
draft: false
menu: "main"
---
## Contents {#contents}
Glimpse Image Editor 0.2.0 is an open source image editing program based on the GNU Image Manipulation Program 2.10.18. You can read more about our development priorities and our target userbase here: https://github.com/glimpse-editor/Glimpse/wiki/Development-Priorities

Glimpse NX aims to create a lightweight new interface for pre-existing GNU Image Manipulation Program libraries and frameworks. We will provide more details about that project in coming months.

The goal of both projects is to experiment with new ideas and expand the use of open source software.

### Introduction
- [What is the correct name for your project?](#what-is-the-correct-name-for-your-project)
- [What is Glimpse Image Editor?](#what-is-glimpse-image-editor)
- [What is Glimpse NX?](#what-is-glimpse-nx)
- [What is wrong with the "GIMP" name?](#what-is-wrong-with-the-gimp-name)
- [Are there any disabled people involved with the project?](#are-there-any-disabled-people-involved-with-the-project)
- [Do you intend to replace the GNU Image Manipulation Program?](#do-you-intend-to-replace-the-gnu-image-manipulation-program)
- [Why do you call yourself "open source"?](#why-do-you-call-yourself-open-source)
- [Did you know that name is used elsewhere?](#did-you-know-that-name-is-used-elsewhere)
- [What if I find the word "Glimpse" offensive?](#what-if-i-find-the-word-glimpse-offensive)

### Technical Questions
- [How does your release numbering work?](#how-does-your-release-numbering-work)
- [Which operating systems do you support?](#which-operating-systems-do-you-support)
- [Who signs the Windows installer?](#who-signs-the-windows-installer)
- [Can I install Glimpse and GNU Image Manipulation Program on the same machine?](#can-i-install-glimpse-and-gnu-image-manipulation-program-on-the-same-machine)
- [Are you going to publish this for my favorite Linux distribution?](#are-you-going-to-publish-this-for-my-favorite-linux-distribution)
- [Will you support BSD, Haiku, Solaris or other UNIX platforms?](#will-you-support-bsd-haiku-solaris-or-other-unix-platforms)
- [Why are you using Github instead of Gitlab?](#why-are-you-using-github-instead-of-gitlab)
- [Could you just run "find and replace" to fix the name?](#could-you-just-run-find-and-replace-to-fix-the-name)
- [When are you going to implement the bug-fix or feature I asked for?](#when-are-you-going-to-implement-the-feature-i-asked-for)
- [Can you make Glimpse look like Adobe Photoshop?](#can-you-make-glimpse-look-like-adobe-photoshop)
- [How do I install third-party plugins?](#how-do-i-install-third-party-plugins)
- [How do I migrate my settings from Glimpse 0.1.x to 0.2.x?](#how-do-i-migrate-my-settings-from-glimpse-0-1-x-to-0-2-x)

### Money Matters
- [Why do you need monetary donations?](#why-do-you-need-monetary-donations)
- [Do you plan to sell Glimpse Image Editor?](#do-you-plan-to-sell-glimpse-image-editor)
- [How much do you earn from this project?](#how-much-do-you-earn-from-this-project)
- [Are you scamming me?](#are-you-scamming-me)
- [Will you adopt a cryptocurrency or blockchain reward system?](#will-you-adopt-a-cryptocurrency-or-blockchain-reward-system)

### Project Governance
- [Where is the Glimpse code of conduct?](#where-is-the-glimpse-code-of-conduct)
- [How does the Glimpse project enforce its code of conduct?](#how-does-the-glimpse-project-enforce-its-code-of-conduct)
- [How does your project govern itself?](#how-does-this-project-govern-itself)
- [Why are you deprecating your Matrix channels?](#why-are-you-deprecating-your-matrix-channels)
- [How do I stay up-to-date with this project?](#how-do-i-stay-up-to-date-with-this-project)
- [How do I contribute to this project?](#how-do-i-contribute-to-this-project)

---

## What is the correct name for your project? {#what-is-the-correct-name-for-your-project}
The open source software we produce is called "Glimpse Image Editor", but we sometimes shorten that to just "Glimpse". We refer to our governance structure, core contributors and participants on our Discord server as "the Glimpse project". We often call our social media followers, donors and end users "the Glimpse Community".

Glimpse NX is a separate project we plan to start soon where we will create a lightweight new interface for pre-existing GNU Image Manipulation Program libraries and frameworks. You may sometimes see it referred to as "the rewrite". We will provide more information about that project in coming weeks and months.

If you are a blogger or a member of the technology industry press, we do not yet have branding guidelines in place. However we have provided screenshots, our branding assets and instructions for their basic usage here: https://github.com/glimpse-editor/branding. You may also contact us directly [by email](mailto:glimpse.editor@icloud.com) for further information about the project.

[Return to top](#contents)

## What is Glimpse Image Editor? {#what-is-glimpse-image-editor}
Glimpse Image Editor is a "fork" or "respin" of the [GNU Image Manipulation Program](https://www.gimp.org/), and it is also an open source image editing application.

This project was originally started due to long-standing disagreements between the GNU Image Manipulation Program developers and some of the software's users about who the target audience is, the priority of usability/accessibility changes, and whether it is still appropriate to call a 25 year old software program "the Gimp" as a joke.

Forking (or "remixing") an existing software program is a long-established way to resolve such disputes. In fact, the [GNU manifesto](https://www.gnu.org/gnu/manifesto.en.html) encourages users to modify the applications they use to better suit their needs so long as they are also respectful to the community and make those changes available to others.

While there was some controversy surrounding our project in the months after we first started it in July 2019, we believe that a long and independently-verifiable record of positive actions towards the GNU Image Manipulation Program developers and the wider open source community make our position and positive intentions clear.

[Return to top](#contents)

## What is Glimpse NX? {#what-is-glimpse-nx}
Glimpse NX will be an open source software application using [GNOME](https://www.gnome.org/) technologies that provides a more lightweight and accessible user interface for the same underlying components that the GNU Image Manipulation Program uses. It will also be ported to Windows and MacOS.

We are still deciding which programming language to use, but [Rust](https://www.rust-lang.org/) is the most likely candidate. As we will be using components that are licensed under the [GNU LGPLv3](https://www.gnu.org/licenses/lgpl-3.0.html), we expect the project itself will be provided under the GNU General Public License v3 or a similar compatible license.

Further information for this exciting new spin-off project will be provided in coming months.

As stated in previous blog posts, we did originally consider the possibility of creating a new bespoke cross-platform user interface toolkit and then writing an entirely new BSD-licensed program based on it with the more estoteric [D](https://dlang.org/) programming language. A group of contributors investigated that solution, but after six months of incubation we collectively agreed that such an ambitious project cannot be delivered in a two year timeframe with the resources we have available.

[Return to top](#contents)

## What is wrong with the "GIMP" name? {#what-is-wrong-with-the-gimp-name}
It was originally chosen by Spencer Kimball and Peter Mattis as a joke reference to a questionable scene in an 18 certificate movie called "Pulp Fiction". The word "gimp" also has [other meanings](https://www.merriam-webster.com/dictionary/gimp) that may be considered ableist.

While we cannot provide a solution that resolves the wider societal discussion about what is considered appropriate and "politically correct" in every situation, we can provide an alternative option that helps people who are offended or made uncomfortable by the name, and assist open source advocates that encounter barriers when they recommend the GNU Image Manipulation Program to friends, family, coworkers and employers.

Our project also offers a more constructive path forward to people that have become frustrated by the GNU Image Manipulation Program developers' [long-standing decision](https://www.gimp.org/docs/userfaq.html#i-dont-like-the-name-gimp-will-you-change-it) to not change the name of their software. That means fewer people yelling at each other on social media, and more people working on the code.

[Return to top](#contents)

## Are there any disabled people involved with the project? {#are-there-any-disabled-people-involved-with-the-project}
Yes. However, our contributors are not under any obligation to disclose their status as a disabled person or the nature of their impairment(s) to you, as that is private medical information.

We encourage open source software developers **of all political stripes** to better prioritize fixing accessibility and usability problems, because seemingly small changes can make a big difference and it is not reasonable to constantly expect disabled people to fight you for them first.

While there are many improvements we all need to make on the legacy systems we maintain, even limited efforts made in good faith can send a positive message that disabled people are welcome in our community and their needs matter to us.

[Return to top](#contents)

## Do you intend to replace the GNU Image Manipulation Program? {#do-you-intend-to-replace-the-gnu-image-manipulation-program}
No, this project does not intend to replace or supplant the GNU Image Manipulation Program. We aim to expand the userbase for that software, and creating a respin that makes it more appealing to a new audience is already helping us to achieve that objective.

The Glimpse project is run entirely by passionate enthusiasts. Development on the GNU Image Manipulation Program has continued as normal with the same core group of developers that were working on it before, and their progress has not been hindered by this project at all.

We also frequently link to the GNU Image Manipulation Program developers' [donations page](https://www.gimp.org/donating/) throughout our documentation, and you can review the donations we periodically make ourselves here: https://opencollective.com/glimpse/expenses?tag=donation

Whenever we make improvements or spot a bug in the upstream code, we usually make the GNU Image Manipulation Program developers aware of it on [their IRC channel](https://www.gimp.org/irc.html).

You can read more about what we intend to add in our own "fork" or "respin" on the [development priorities](https://github.com/glimpse-editor/Glimpse/wiki/Development-Priorities) page of the project wiki.

[Return to top](#contents)

## Why do you call yourself "open source"? {#why-do-you-call-yourself-open-source}
Glimpse Image Editor is licensed under the [GNU General Public License version 3](https://www.gnu.org/licenses/gpl-3.0.en.html), and that is an [Open Source Initiative](https://opensource.org/) approved "open source" license.

You can read the full definition for what "open source" means and how that impacts your rights as a user here: https://opensource.org/docs/osd

You can also review the GNU definition of "free software" here: https://www.gnu.org/philosophy/free-sw.html

We standardize on the term "open source" to make it clear to end users who may not be familiar with the GNU-sanctioned definition of "free software" that we do not follow the same "freeware", "shareware" or "adware" models that they usually encounter in commercial app stores for Windows, macOS and mobile platforms.

[Return to top](#contents)

## Did you know that name is used elsewhere? {#did-you-know-that-name-is-used-elsewhere}
We are aware of a number of other unrelated projects called "Glimpse". We have made changes based on feedback from our critics such as changing our website's domain name and defining "Glimpse" as a shortened version of "Glimpse Image Editor".

The project's current stance is that while we are theoretically open to changing our name, there is very limited support in favor of actually doing so. We granted our critics time to find an alternative name that addresses the concerns they raised, fulfils our project's requirements and enjoys popular support. Even with three months and our assistance they were not able to do so, so we consider the matter closed for the time being.

See ["How does your project govern itself?"](#how-does-this-project-govern-itself) for more details about why we now limit discussion about this topic on our Discord server.

[Return to top](#contents)

## What if I find the word "Glimpse" offensive? {#what-if-i-find-the-word-glimpse-offensive}
That seems unlikely given we checked its meaning in every known language, but if you have a legitimate concern then let us know.

If you are offended by the fact we forked a project, we suggest you continue using the [GNU Image Manipulation Program](https://www.gimp.org) instead of annoying our contributors and making more work for our moderators.

[Return to top](#contents)

## How does your release numbering work? {#how-does-your-release-numbering-work}
Glimpse Image Editor 0.1.0 and 0.1.2 were based on the GNU Image Manipulation Program 2.10.12. These initial releases made minor cosmetic changes and helped us learn how to build and package the application.

Glimpse Image Editor 0.2.0 and 0.2.2 is based on the GNU Image Manipulation Program 2.10.18, and it introduces additional plugins and functional changes. All 0.2.x releases will add our changes, back port useful functionality and update key dependencies on the same 2.10.18 base.

"Beta test" and "Stable" release versions always end in an even number. Odd numbered versions are "Unstable" builds created from our development branch.

Glimpse NX (the interface rewrite) will have its own version scheme.

[Return to top](#contents)

## Which operating systems do you support? {#which-operating-systems-do-you-support}
We support systems running Windows 7 or newer, and most modern variants of Linux.

Unfortunately [despite our best efforts](https://github.com/glimpse-editor/Glimpse/issues/402), Glimpse Image Editor is not supported natively on MacOS. We recommend either running Glimpse Image Editor in a virtualized environment or sticking with [the GNU Image Manipulation Program](https://www.gimp.org/downloads/).

You may also be interested in trying [Seashore](https://apps.apple.com/us/app/seashore/id1448648921?mt=12), an older fork of the GNU Image Manipulation Program designed specifically for MacOS. While it does have fewer features, it may still be suitable for your intended use case.

[Return to top](#contents)

## Who signs the Windows installer? {#who-signs-the-windows-installer}
[Cynthia Revström](https://cynthia.re/), a renowned security researcher. She signs our Windows installers with an Extended Validation (EV) code signing certificate belonging to a registered company called [Qs.nu](https://qs.nu/).

If we do not sign our MSI installer then potential users can run into a number of problems. Certain web browsers block the download of "untrusted" files, Windows SmartScreen creates error screens that non-technical people find difficult to override, and anti-virus programs incorrectly flagging Glimpse Image Editor as "malware" can interfere with the installation process and normal operation of the program.

We initially tried a self-signed certificate, but that did not resolve the problem. The Glimpse project is not a registered company and cannot afford to reimburse individuals for certificate authority notarization requirements, so we cannot provide our own code signing certificate. As a result we rely on a trusted individual to voluntarily sign each MSI installer we release on our behalf.

[Return to top](#contents)

## Can I install Glimpse and GNU Image Manipulation Program on the same machine? {#can-i-install-glimpse-and-gnu-image-manipulation-program-on-the-same-machine}
On Windows, you can safely install and run both applications at the same time.

On Linux, the Flatpak and Snapcraft builds that we support and maintain are fully self-contained and should not interfere with any installed versions of the GNU Image Manipulation Program. If you discover that is not the case on your system, please [report it as a bug](https://github.com/glimpse-editor/Glimpse/issues).

If you are using a Linux build from a third party source that we do not directly support (such as AUR or your distribution's package repositories) then it is unlikely because there may be package and file name conflicts. You should ask the people responsible for maintaining those packages for confirmation and any help you might need.

We plan to assist Linux and BSD distribution maintainers by fixing problems that would require them to mark other packages as conflicts in order to distribute Glimpse Image Editor. You can track progress in this issue: [#320](https://github.com/glimpse-editor/Glimpse/issues/320)

[Return to top](#contents)

## Are you going to publish this for my favorite Linux distribution? {#are-you-going-to-publish-this-for-my-favorite-linux-distribution}
You can see all the Linux installation methods we are aware of for Glimpse Image Editor on [our downloads page](/downloads/).

We already publish our own stable builds on [Flathub](https://flathub.org/apps/details/org.glimpse_editor.Glimpse) and [the Snap Store](https://snapcraft.io/glimpse-editor).

You can also install our latest development snapshot as an [AppImage](https://appimage.github.io/Glimpse-Image-Editor/).

All other installation mechanisms for Linux are considered "community supported". That means we do not have any say about how they are built, packaged or maintained. We link to them, but if you raise bug tickets with us we may direct you back to those sources instead.

We recommend Linux/BSD distribution package maintainers mark `gimp` and `glimpse` packages as conflicts for the time being.

[Return to top](#contents)

## Will you support BSD, Haiku, Solaris or other UNIX platforms? {#will-you-support-bsd-haiku-solaris-or-other-unix-platforms}
Other UNIX systems are treated the same way as any individual Linux distribution. We do not directly support the individual packaging formats and publishing platforms for each variant of UNIX because we don't have the knowledge or resources to support and maintain them all.

However, we will accept code fixes that enhance UNIX compatibility and will assist any third party package maintainers that want to port Glimpse Image Editor to operating systems like BSD, Haiku, Solaris and other UNIX variants.

[Return to top](#contents)

## When are you going to implement the bug-fix or feature I asked for? {#when-are-you-going-to-implement-the-feature-i-asked-for}
The first place to check is our [Github Issues list](https://github.com/glimpse-editor/Glimpse/issues).

We aim to tag each bug and feature request to a [release milestone](https://github.com/glimpse-editor/Glimpse/milestones) so that you have a rough idea of when we think we can feasibly deliver the functionality. Those estimates are subject to change based on our shifting project priorities and any technical hurdles we come across. We also do our best to add regular comments to every issue so that you can see the most up-to-date information about them.

If the functionality you want is not listed, the next place to check is [the roadmap page](https://wiki.gimp.org/wiki/Roadmap) for the GNU Image Manipulation Program. Because that project has more contributors and resources than we do as a downstream fork, we are normally a release or two behind them. If they are implementing a fix or change though, then we will eventually inherit it.

Finally, if the change you want isn't requested in either place then feel free to raise it as a bug or a feature request! Alternatively you can contact us by using the links on our [Contribute](/contribute/) page.

[Return to top](#contents)

## Can you make Glimpse look like Adobe Photoshop? {#can-you-make-glimpse-look-like-adobe-photoshop}
If you want the closest possible experience, we recommend you install the [PhotoGIMP](https://github.com/glimpse-editor/Glimpse/wiki/How-to-Install-the-PhotoGIMP-Plugin) plugin.

We understand why it is important for Glimpse Image Editor to feel familiar to users of existing image editing applications, and that is why we are incorporating a number of PhotoGIMP's features into our "fork" of the GNU Image Manipulation Program. However, we think it is also important for us to do our own thing because that will create more new and interesting ideas, and it should also avoid any potential legal problems.

The developers of the GNU Image Manipulation Program have a similar stance on this, and you can read more about it on [their FAQ page](https://www.gimp.org/docs/userfaq.html#i-dont-like-gimps-user-interface-why-cant-you-just-copy-adobe-photoshop).

[Return to top](#contents)

## Why are you using Github instead of Gitlab? {#why-are-you-using-github-instead-of-gitlab}
That was a choice made early on for practical reasons such as project discoverability, ease-of-use, user familiarity and cost. We also support [Github Sponsors](https://github.com/sponsors/glimpse-editor), rely on [Github Actions](https://github.com/glimpse-editor/Glimpse/actions) for automated builds, and use their servers as a [release mirror](https://github.com/glimpse-editor/Glimpse/releases).

As a project we are aware that some people have ethical concerns about using Github, and that other projects appear above us in [the search results](https://github.com/search?utf8=%E2%9C%93&q=glimpse&type=). For those reasons we periodically discuss how our contributors feel about using it, as well as the merits and drawbacks of potential alternatives.

We have tried self-hosted solutions in the past, and you can see evidence of that in our blog and Open Collective profile. The main problem is that the build process for Glimpse Image Editor requires a lot of compute power, and we do not receive enough donations to replicate the same functionality we can achieve with Github Actions. In addition deploying, hardening and maintaining multiple servers is not a straightforward task, and time our volunteer contributors spend being server administrators is time that they cannot spend developing Glimpse Image Editor or Glimpse NX.

There are currently no plans to move the Glimpse Image Editor source code from Github.

We are still exploring potential host platforms for Glimpse NX. The project will initially be developed on Github, but once we have a minimum viable product we will have a better understanding of our technical requirements and can then start exploring other alternatives.

[Return to top](#contents)

## Could you just run "find and replace" to fix the name? {#could-you-just-run-find-and-replace-to-fix-the-name}
No. That would break API compatibility with submodule dependencies and plugins, and the build system would also require a lot of refactoring. In addition, you would also break all the translation files and the mechanisms that keep them up-to-date. All of those problems would be very time-consuming to fix.

To preserve compatibility we had to maintain existing file names, variable names, constants, class names, methods and APIs. This meant we had to provide our own files, variables and constants, then identify where we wanted to use them, swap in those values wherever that did not break compatibility, and find a suitable replacement wherever we referred to upstream code that we had not modified (we settled on "GNU I.M.P"). That cannot be achieved using find-and-replace tools or regular expressions alone.

It is not straightforward to rebrand the GNU Image Manipulation Program. You can read more about our other aims and objectives on the [Development Priorities](https://github.com/glimpse-editor/Glimpse/wiki/Development-Priorities) wiki page.

[Return to top](#contents)

## How do I install third-party plugins? {#how-do-i-install-third-party-plugins}
We provide a full listing for how to install various third-party plugins on this wiki page: https://github.com/glimpse-editor/Glimpse/wiki#third-party-plugin-installation-guides

If there is a third party plugin you would like us to support better, feel free to raise an issue on our Github project: https://github.com/glimpse-editor/Glimpse/issues

[Return to top](#contents)

## How do I migrate my settings from Glimpse 0.1.x to 0.2.x? {#how-do-i-migrate-my-settings-from-glimpse-0-1-x-to-0-2-x}
Follow the instructions on our wiki for instructions on how to do that on [Windows](https://github.com/glimpse-editor/Glimpse/wiki/How-to-migrate-configuration-settings-from-Glimpse-Image-Editor-0.1.x-to-0.2.x-%28Windows%29) and [Linux](https://github.com/glimpse-editor/Glimpse/wiki/How-to-migrate-configuration-settings-from-Glimpse-Image-Editor-0.1.x-to-0.2.x-%28Linux%29).

[Return to top](#contents)

## Why do you need monetary donations? {#why-do-you-need-monetary-donations}
We have used the donations we have received so far to fund server hosting, web domains and new artwork. You can review all of our spending in [the expenses section](https://opencollective.com/glimpse/expenses) of our Open Collective profile.

If you would like to donate money to the Glimpse project, you can do so on [Open Collective](https://opencollective.com/glimpse). We also support [Github Sponsors](https://github.com/sponsors/glimpse-editor), and that platform automatically passes those funds to Open Collective once a month.

Open Collective is a trusted 501(c) charity. None of our contributors can receive donated funds without a valid receipt or invoice, and any spending requires the formal approval of both Open Collective and the Glimpse governance team. All donations and spending is displayed publicly and in real time so that you can make an informed choice before donating, and you can hold us accountable afterwards if you do not feel that we have spent your money wisely.

When we first started the Glimpse project we made a commitment to pass along a portion of our donations to the GNU Image Manipulation Program developers, and we will continue to do for as long as we "fork" or "respin" their project. You can judge how well we are keeping our promise yourself by [reviewing how much we have sent so far](https://opencollective.com/glimpse/expenses?tag=donation) and then comparing that amount to our estimated annual budget.

We also encourage everyone that would like to support the GNU Image Manipulation Program developers to use [their donation page](https://www.gimp.org/donating/) to do so.

[Return to top](#contents)

## Do you plan to sell Glimpse Image Editor? {#do-you-plan-to-sell-glimpse-image-editor}
No. Glimpse Image Editor is an open source application, and we have no plans to sell copies of the software. The same will also apply to Glimpse NX.

If that policy ever changes, it will go through the usual governance channels for this project, and our community will be consulted about it first. In practice, there is little or no support within the Glimpse project to start charging for copies of the software, so it is extremely unlikely to ever happen.

As for the project itself, we have not built a formal organization or legal entity around it. We are a group of volunteers that share the same online infrastructure and follow mutually agreed procedures.

[Return to top](#contents)

## How much do you earn from this project? {#how-much-do-you-earn-from-this-project}
Nothing. This is a strictly not-for-profit venture, and all donated funds are held by a trusted 501(c) charity called [Open Collective](https://opencollective.com/glimpse).

None of our contributors can receive donated funds without a valid receipt or invoice, and any spending requires the formal approval of both Open Collective and the Glimpse governance team. All donations and spending is displayed publicly and in real time so that you can make an informed choice before donating, and you can hold us accountable afterwards if you do not feel that we have spent your money wisely.

[Return to top](#contents)

## Are you scamming me? {#are-you-scamming-me}
No. Unfortunately there are people on the Internet who disagree with our project existing for political reasons, and in the absence of any reasonable arguments against what we are doing, some of them have tried to smear the Glimpse project and our contributors with false accusations.

To determine for yourself if we have delivered on the objectives we have set out, you can compare your current experience of the software against our [Development Priorities](https://github.com/glimpse-editor/Glimpse/wiki/Development-Priorities), the `NEWS` file provided with [the source code](https://github.com/glimpse-editor/Glimpse), and the release notes we produce on [our blog](/posts/).

You can also review how much we have received in donations and the ways we have spent that money on [our Open Collective profile](https://opencollective.com/glimpse).

Open Collective is a trusted 501(c) charity. None of our contributors can receive donated funds without a valid receipt or invoice, and any spending requires the formal approval of both Open Collective and the Glimpse governance team. All donations and spending is displayed publicly and in real time so that you can make an informed choice before donating, and you can hold us accountable afterwards if you do not feel that we have spent your money wisely.

Our [Github Sponsors](https://github.com/sponsors/glimpse-editor) page is directly linked to our Open Collective profile via [Stripe](https://stripe.com/), so all donations received from that channel are also collected and recorded by Open Collective without our intervention.

**The Glimpse project is strictly not-for-profit, and we periodically donate surplus funds to the GNU Image Manipulation Program developers**. You can review those donations here: https://opencollective.com/glimpse/expenses?tag=donation

It is also our policy to provide a link to the [GNU Image Manipulation Program donation page](https://www.gimp.org/donating/) whenever we provide links to our own donation page so that it is clear to prospective donors that there are two separate projects. 

We also state wherever possible that Glimpse Image Editor is based on the GNU Image Manipulation Program, and clarify which version Glimpse Image Editor is based on. You can review the source code and compliance with applicable licenses on [our Github repository](https://github.com/glimpse-editor/Glimpse). We also display the names of upstream contributors in the **Help** > **About** > **Credits...** section of the software with a "(GNU I.M.P)" tag next to each applicable entry.

Whenever we provide download figures, we always provide links to the tools and websites we used so that (wherever possible) you can independently verify that the numbers we have published and our interpretation of them are correct.

Finally, you can review all of our previous blog posts to understand how our project has evolved and changed since it first started. Our project's website is also [kept under version control](https://github.com/glimpse-editor/getglimpse-web), so you can also review any changes that we have made to specific pages and posts.

While we doubt we will convince everyone, we hope that our commitment to transparency will help reassure those with an open mind that there is no sinister conspiracy, nefarious agenda, or evil plan. We are just a group of well-meaning volunteers trying to solve a problem in our spare time.

[Return to top](#contents)

## Will you adopt a cryptocurrency or blockchain reward system? {#will-you-adopt-a-cryptocurrency-or-blockchain-reward-system}
No, and we have no interest in our project being used as the experimental basis for such an initiative.

Read ["How does your project govern itself?"](#how-does-this-project-govern-itself) for more information about why our moderators limit debate on some topics.

[Return to top](#contents)

## Where is the Glimpse code of conduct? {#where-is-the-glimpse-code-of-conduct}
You will find it on [this page](/code-of-conduct/). Our code of conduct is based on [the contributor covenant](https://www.contributor-covenant.org/) and will be developed and amended over time as the need arises. As this project spawned from [the fediverse](https://joinmastodon.org/) our experiences in that online space inform the project's future governance and direction.

We also want to make it clear that we value and encourage diverse representation in leadership positions within our community, and we believe that is the best way to enforce a code of conduct that protects all contributors and promotes wider participation. At this early stage our initial governance team is formed entirely of individuals from marginalized communities, and that makes our project [very atypical](https://opensource.com/article/17/9/diversity-and-inclusion-innovation). That emerged organically as a result of the project starting on [the fediverse](https://fediverse.party/).

We know how important it is to enact the right code of conduct and enforce the rules pro-actively. We want to promote a safe and inclusive environment, not a toxic one. If you have ideas to help us do that and want to get involved with this discussion then please join us in the project's communication channels.

Our project reviewed the Contributor Covenant version 2.0 in January 2021. For the time being we have chosen stick with version 1.4, as our existing battle-tested enforcement practices have served us well so far and our contributors raised concerns about changing them.

[Return to top](#contents)

## How does the Glimpse project enforce its code of conduct? {#how-does-the-glimpse-project-enforce-its-code-of-conduct}
The moderation team was originally formed by the Glimpse contributors to "pro-actively police" the [code of conduct](/code-of-conduct/). The legacy of this means that they do not necessarily wait for members of the Glimpse project to report violations, and moderators keep an eye on project communication channels so they can gently nudge people towards positive behaviours. They also perform some limited vetting on new users that join the Discord server, and coach new open source contributors that are acting in good faith. This approach helps us to foster a safe and welcoming environment for everyone.

If an individual chooses to ignore moderator guidance, then moderators may, at their discretion, and depending on the severity of the problems an individual is causing, issue up to three warnings to the same person on the same communication channel. Warnings for minor "first offences" are normally forgiven automatically after two weeks have passed, but they may still be considered in future moderation decisions. If an individual reacts badly or attempts to overturn previous warnings they have received, that behavior usually counts against them if moderators take further action. 

**Our code of conduct applies and always has applied to everyone in our project** regardless of their role, and regardless of any reputation they might have inside or outside the project created by their career, open source contributions, personal blogs, YouTube channels, social media profiles, etc. We care about protecting our contributors from online abuse and harassment regardless of any external consequences to the project, and no one individual is bigger than the whole project or "above the rules".

Normally moderators will seek a majority vote on the moderation team's private Discord channel before implementing a project-wide ban against an individual. If a moderator feels they need to act before a vote can be held, they may at their own discretion ban someone immediately and then confidentially explain their actions to the other moderators (and with supporting evidence if requested) within 72 hours. The "instant ban" mechanism is primarily intended for bot accounts, spam and obvious trolling.

If the other moderators do not agree with any ban, then a majority vote on the moderation team's private Discord channel can reverse that decision. The governance team also reserves the right to eject a moderator from the moderation team at any time if they collectively agree that moderator has abused their position or violated the [code of conduct](/code-of-conduct/).

We rarely implement temporary bans, so most bans are permanent. Individuals have to wait for a 72 hour cool-off period to elapse before they can appeal a ban, and they must do so via the Glimpse project contact email address. Appeals are reviewed by the governance team, and they will only consider reversing a ban if there has been a clear case of mistaken identity, moderator misconduct, or exceptional mitigating circumstances that adequately excuse the violation (as determined by the governance team and any victims of the miconduct in question).

[Return to top](#contents)

## How does your project govern itself? {#how-does-this-project-govern-itself}
The Glimpse Project is run by a self-appointed board called "the governance team" that contains three or more Glimpse contributors. The current governors are: [Christopher Davis](https://social.libre.fi/users/brainblasted), [Luna](https://twitter.com/Clipsey5) and one recently vacant seat. Decisions are made with a majority vote after consultation with project contributors and any other interested parties. The governance team also appoints and oversees "the moderation team", which is responsible for policing our [code of conduct](/code-of-conduct/) and fostering a welcoming online community.

We host a [Discord server](https://discord.gg/hZhRceq) for project decisions, Glimpse NX development and some technical support queries. The governance team also discusses project moderation decisions in a private channel on that server. You can read the rules for joining this server's public channels on the `#rules-and-info` channel.

[Github Issues](https://github.com/glimpse-editor/Glimpse/issues) are used to track bug reports, suggestions and questions from the wider community, and items we have agreed as a project need action. Action items are allocated to a milestone to give an indication of their priority and likely timeline, but these are always provisional until the work is done.

No decision is ever set in stone and can be revisited if new information comes to light or there is enough support within the project to do so. The governance team will generally only block the re-opening of an issue or delay a decision if the discussion is becoming too heated or obstructs the day-to-day running of the project. The governance team also reserves the right to end a discussion if, after giving an idea a fair hearing, there is clearly a lack of support within the Glimpse project in favor of it being worked on or developed any further.

Finally, the project may from time to time run polls on social media to canvas opinion for specific issues if there is support for doing so. They are always non-binding and only intended to facilitate the existing decision-making process.

[Return to top](#contents)

## Why are you deprecating your Matrix channels? {#why-are-you-deprecating-your-matrix-channels}
We deprecated them in January 2021, and have now fully moved across to [our Discord server](https://discord.gg/hZhRceq).

As you will have read elsewhere on this FAQs page, there are two parallel development streams in the Glimpse project:

- An open source fork of the GNU Image Manipulation Program 2.10.x called "Glimpse Image Editor"
- A new open source image editing program for the GNOME desktop called "Glimpse NX"

The eventual plan is to deprecate Glimpse Image Editor in favor of Glimpse NX, and we expect that to happen some time in 2022.

Matrix was the communication platform that was chosen by the fork's contributors in July 2019 as a replacement for a freenode IRC channel. Discord was originally chosen in May 2020 by the Glimpse NX contributors. It makes sense that as we shifted resources away from the fork and towards Glimpse NX that activity would drop on Matrix and increase on Discord, and it reached the point that we could no longer justify the time we spend moderating and maintaining our Matrix channels.

We spent three weeks through December 2020 experimenting with various ways we could create a communication bridge between Matrix and Discord. Unfortunately that did not prove to be a viable solution for us. Our project is too large for zero-cost off-the-shelf services, and we have learned repeatedly through experience that self-hosting can require a significant amount of time and resources to maintain.

To assist our users and supporters that would like to better understand how we make decisions about our project tools and communication platforms, these are the core values we follow:
- We should aim to lower the barrier to entry for newcomers that have never contributed to an open source project before
- We require comprehensive moderation tools that are not time-consuming to maintain, learn or use effectively
- While open source solutions are preferred, our contributors' time and welfare are always more important
- Our governance team does not make decisions without consulting the Glimpse project contributors, listening to their feedback, and exploring their suggestions

[Return to top](#contents)

## How do I stay up-to-date with this project? {#how-do-i-stay-up-to-date-with-this-project}
You can follow us on [the fediverse](https://mastodon.art/@glimpse) and [Twitter](https://twitter.com/glimpse_editor). This blog also has a full text [RSS feed](https://getglimpse.app/index.xml).

Our [Open Collective](https://opencollective.com/glimpse) backers also get regular updates about the project. 

Our Discord server is primarily intended for existing and prospective contributors. If you only want to keep up with project news, we encourage you to follow our social media accounts and RSS feed instead.

[Return to top](#contents)

## How do I contribute to this project? {#how-do-i-contribute-to-this-project}
All of our contribution links are available on our [Contribute](/contribute/) page.

Please ensure that you read our [code of conduct](/code-of-conduct/) before you join our community. Regardless of your past experience and the usefulness of your contributions you are expected to comply with it.

[Return to top](#contents)
