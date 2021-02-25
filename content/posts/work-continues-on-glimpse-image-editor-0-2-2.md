---
title: "Work Continues on Glimpse Image Editor 0.2.2"
date: 2021-02-21T12:00:00+00:00
draft: false
---
Check out our [Contribute](/contribute/) page for social media and news links to follow our progress.

## Glimpse Image Editor 0.2.2 Progress Update
Glimpse Image Editor 0.2.2 is currently delayed due to a combination of breakage introduced by external dependencies and contributors understably being distracted by everything that is happening in the outside world. We are doing our best to polish off what's left of the code and packaging problems as quickly as possible so that we can start beta testing. 

The [planned donation](https://opencollective.com/glimpse/expenses?tag=donation) for the GNU Image Manipulation Program developers that coincides with this release has already been completed, bringing our running total to $750 USD since Glimpse project started in July 2019.

Despite the departure of the fork's lead developer, Glimpse Image Editor 0.2.2 will still be released as planned, and it will continue to be maintained with hotfixes until Glimpse NX is ready in 2022. More information will be provided about that in future blog posts.

### Recent code changes

* We backported an upstream fix to resolve breakage introduced in GEGL 0.4.28. [#516](https://github.com/glimpse-editor/Glimpse/pull/516)
* The WiX manifests for the Windows installers have been updated with new dependencies and the new "large font" UI themes. [#519](https://github.com/glimpse-editor/Glimpse/pull/519)
* In-app URLs will be pointed back to glimpse-editor.org when 0.2.2 is released. [#518](https://github.com/glimpse-editor/Glimpse/pull/518)

### Outstanding bugs

* We are no longer able to sign Windows MSI installers with an EV code signing certificate. Due to Brexit, the organization that had donated this to us had to be wound down, and so no longer exists. A new solution or workaround is needed. [#523](https://github.com/glimpse-editor/Glimpse/issues/523)
* The Windows build is currently broken due to an external dependency fetched by MSYS2 that has changed. This issue needs further investigation. [Build output](https://github.com/glimpse-editor/Glimpse/actions/runs/586439561)
* The automated Snap build hosted by Canonical on Launchpad has not been running since November 2020. Current user impact is that `edge` channel is not up to date, but it also means that 0.2.2 cannot currently be deployed on `beta` and `stable` channels. There is no immediate cause for concern as 0.2.0 has no known critical security vulnerabilities or showstopping bugs on that platform, and snaps are sandboxed from the underlying system. We will need to reach out to Canonical to resolve this problem as soon as possible.

## Bobby Moss departs the project
Bobby Moss ([TrechNex](https://keybase.io/trechnex)) is one of the Glimpse project founders, and has been the lead developer on the fork up to this point. He has left the project at the request of his employer, and has provided this parting statement:

*"I would like to thank everyone that has supported and contributed to Glimpse Image Editor. Over the last 20 months, we have built the Glimpse project to be resilient to change and bigger than any one person. It is fair to say that what we have achieved has exceeded my expectations, and I encourage our community to help the remaining contributors continue to support users with patches and begin development on Glimpse NX."*

Bobby has also taken down the Facebook Page, SourceForge mirror and archive.org links that he set up. We are on the lookout for volunteers to help us support those platforms. 

There is now at least one vacant position in the Glimpse governance team. Over the next few months, Christopher Davis and Luna will seek to appoint willing Glimpse project contributors to both the governance and moderation teams. [More information](/about/#how-does-this-project-govern-itself)

## A new port for nixOS unstable channel
After months of amazing work, the [NixOS](https://nixos.org/) packaging project has now added Glimpse Image Editor 0.2.0 in its unstable channel. You can try out this community-supported download source [here](https://search.nixos.org/packages?channel=unstable&show=glimpse&from=0&size=50&sort=relevance&query=glimpse).

## We reviewed our Code of Conduct
Our [code of conduct](/code-of-conduct/) is currently based on the [Contributor Covenant 1.4](https://www.contributor-covenant.org/version/1/4/code-of-conduct.html), and in January 2021 we discussed the possibility of moving to the [Contributor Covenant 2.0](https://www.contributor-covenant.org/version/2/0/code_of_conduct/).

While those discussions have not been closed, they are currently stalled because of concerns our contributors have raised about the new enforcement guidelines introduced in version 2.0. You can find out more about how we currently enforce our code of conduct on [our FAQs page](/about/#how-does-the-glimpse-project-enforce-its-code-of-conduct).
