---
title: About timelinejs-template
nav: About
nav_order: 2
---

# History of this timeline technology

'timelinejs-template' is a template timeline technology that uses Git & GitHub, that this 'timelinez/jfk' repo is based on.

This 'http://timelinez.github.io/jfk' usage has a small amount of modifications versus the template it is based on [timelinejs-template](https://github.com/thecdil/timelinejs-template) by Center for Digital Inquiry and Learning (CDIL) a "digital scholarship" organization within the University of Idaho. 

CDIL's template (substantially by Evan Williamson) is further work based on [Kinight Lab](https://knightlab.northwestern.edu/) (Northwestern University) multi-year buildout of [Timeline JS3](https://github.com/NUKnightLab/TimelineJS3). Some twenty-five contributors have made TimelineJS3 polished control (most frequent are Joe Germuska , Zach Wise, Heather Billings, Jennifer Y Wilson, Scott Bradley).

CDIL's work shifts emphasis from GoogleDocs for the raw curation of timelines, to JSON (or CSV) co-located with the repo in question (under source control).

CDIL also maintain an "about" page here: [thecdil.github.io/timelinejs-template/about.html](https://thecdil.github.io/timelinejs-template/about.html)

## Changes in 'timelinez/jfk' over 'thecdil/timelinejs-template'. 

* Git commit ID is in each generated page (at the bottom, with reduced font size)
* The JavaScript techologies are sourced from a CDN now
* Hours/Minute added to some timeline entries (that was supported in thecdil/timelinejs-template but now shown)

## Changes vs [timelinez/jfk-OLD](https://github.com/timelinez/jfk-OLD)

No part of the JS technology from that repos is retained. Only the timeline was taken forward (fixed up & enhanced).

# Why Git & GitHub

Git is a history maintaining merkle tree. You can to batch operations on it (clone/checkout, change files en masse, commit back in one commit). You can keep note of the hashes of the published items and enjoy that it is tamper evident as a system. You can solicit and review changes from people outside your organization if you want. Others can verify that times presented online purported to be from a Git repo on GitHub can actually be verified as such. Indeed, screenshots purported to be from a repo can be verified if you're willing to type in a commit ID as part of your verification.

![image](https://user-images.githubusercontent.com/82182/100537959-a26a0280-3224-11eb-83a9-046c52b8bf62.png)
 
 GitHub also allow forks. One org could take another org's timeline and publish their own modifications to it. In the case of JFK's death, conspiracy theory people could publish their own timeline including all the additional events they think happened. Same rules for them though, Git makes their changes trackable and verifiable.  Orgs would add a license to make usage of the trademarks and copyright conditional for forked repositories.