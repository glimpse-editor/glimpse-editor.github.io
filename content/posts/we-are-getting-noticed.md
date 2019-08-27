---
title: "We Are Getting Noticed"
date: 2019-08-27T19:14:00+01:00
draft: false
---
If you are new to our project, welcome! Here is a quick reminder of where you can find us on social media and our project tools:

- Twitter: https://twitter.com/glimpse_editor
- Fediverse: https://bobadon.co.uk/@glimpse
- Patreon: https://www.patreon.com/glimpse
- Matrix: https://matrix.to/#/#glimpse:matrix.org
- Github: https://github.com/glimpse-editor/Glimpse
- Wiki: https://wiki.getglimpse.app

We also encourage those who can to donate to the GNU Image Manipulation Program, as that funds the components Glimpse depends on: https://www.gimp.org/donating/

## Glimpse discussed on YouTube
The biggest update this week was been the project gaining the attention of two prominent YouTubers in the Linux community.

**Bryan Lunduke** (65,000 subscribers) published a video called *"The GIMP has been forked by folks who find the name offensive"*: https://youtu.be/CV1HZU4KFHc

After seeing Bryan's video we have taken his feedback on board and temporarily made `dev-g210` the default branch so people can more easily find our in-development changes. We disagree that "Glimpse" is a bad name, but have opened a Github Issue for people who would like to suggest alternatives we can put to the community here: https://github.com/glimpse-editor/Glimpse/issues/92

**Gardiner "The Linux Gamer"** (47,000 subscribers) published a video called *"Why are people FREAKING OUT about Glimpse?"*: https://youtu.be/CbxvaC9fo4g

Everyone on Matrix chat appreciated the sentiments Gardiner expressed in that video, and the Glimpse project also encourages everyone in our own community to support each other and be kind to people who may have opinions that differ from our own.

We would like to thank Bryan and Gardiner for their even-handed reviews of the issues and for encouraging their viewers to remain civil. The Glimpse project and individuals involved with it have periodically been on the receiving end of targetted harassment since its inception, but we are relieved to report no increase since those videos were released. We were also pleased to see that regardless of their opinions about our fork the vast majority of people on social media have been constructive and respectful to each other.

If you like their work, you can find donation links here:

- Bryan Lunduke: http://lunduke.com/
- Gardiner "The Linux Gamer": https://www.patreon.com/thelinuxgamer

## Glimpse mentioned on "OMG! Ubuntu!"
You can find the article here: https://www.omgubuntu.co.uk/2019/08/glimpse-gimp-image-editor-fork

It is very cool to see our project start to attract the attention of major Linux news outlets at such an early stage in its development. We would also like to thank them for linking to our [Github project](https://github.com/glimpse-editor/Glimpse) and [Patreon donation page](https://www.patreon.com/glimpse).

## Glimpse also mention on "It's FOSS"
You can find the article here: https://itsfoss.com/gimp-fork-glimpse/

This was a well-researched and thoughtful article we enjoyed reading!

## More logo ideas
"will", "measly twerp" and "jwhkvthdi" posted some interesting logo ideas and concept artwork in the Matrix chat. We appreciate their contributions and warmly welcome them to our community.

Bobby Moss particularly enjoyed the pagan mascot idea from Chris Tallerås here: https://mastodon.art/@ChrisTalleras/102684102318412133

## Code changes
Bobby Moss reinstated the "Dark" and "Light" UI themes, as well as the "Symbolic" and "Symbolic-Inverted" icons. (The "Gray" UI theme and "Color" icons have been left out as we do not believe they add any value beyond what the existing "System" UI them and "Legacy" icons provide)

## Project decisions
We collectively agreed that because GTK2 applications look out-of-place on some operating systems we should choose the default UI theme and icon set that best fits with the operating system we publish binaries for. This is intended as a temporary measure until upstream finishes the port to GTK3.

Melody stepped down as a moderator on our Matrix channels. The project thanks her for the contributions she has made so far and is excited to see the design activities she is working on.

We also agreed that we should determine whether to squash commits in a pull request after consulting the original poster. In some cases contributors may have taken care to make atomic, buildable commits in their Git history and we should take this into account.

Chris and Clipsey also produced mockups for a potential new "Welcome screen" that could replace the default splash screen after the hard fork.

## Website updates
Bobby Moss updated the FAQs page and added two new answers for project-related questions.

Martijn Braam also added a subtitle to our homepage so newcomers can see a one-line summary clarifying the Glimpse project's purpose.
