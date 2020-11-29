---
title: About this site & repo
nav: About
nav_order: 2
---

A simple timeline representation of events that pertain to a single topic. Made stronger by being backed by Git on GitHub.

# History of this timeline technology

Up for discussion:

1. This repo/site: [timelinez.github.io/jfk](https://timelinez.github.io/jfk/), Source [github.com/timelinez/jfk](https://github.com/timelinez/jfk/)
2. Template it is based on: Site: [thecdil.github.io/timelinejs-template/](https://thecdil.github.io/timelinejs-template/), Source [github.com/thecdil/timelinejs-template/](https://github.com/thecdil/timelinejs-template/) 

'timelinejs-template' [#2] is a template timeline technology that uses Git & GitHub, that this 'timelinez/jfk' [#1] repo is based on.

This 'timelinez/jfk' [#1] usage has a small amount of modifications versus the template [#2] it is based on. That template [#2] is by Center for Digital Inquiry and Learning ([CDIL](https://cdil.lib.uidaho.edu/)) a "digital scholarship" organization within the University of Idaho. From CDIL's website: *"The Center for Digital Inquiry and Learning (CDIL) is a collaboration between the College of Letters, Arts and Social Sciences (CLASS) and the University of Idaho Library. Its purpose is to advance digital scholarship opportunities at the University of Idaho."*

CDIL's template [#2] (substantially by Evan Williamson) is further work based on [Knight Lab](https://knightlab.northwestern.edu/)'s multi-year buildout of [Timeline JS3](https://github.com/NUKnightLab/TimelineJS3). Some twenty-five contributors have made TimelineJS3 polished UI control (most frequent are Joe Germuska, Zach Wise, Heather Billings, Jennifer Y Wilson, Scott Bradley). From their website, *"Northwestern University Knight Lab is a community of designers, developers, students, and educators working on experiments designed to push journalism into new spaces."*

CDIL's work shifts emphasis for the raw curation of timelines from GoogleDocs to JSON (or CSV) co-located with the repo in question (under source control).

CDIL also maintain an "about" page here for the template here: [thecdil.github.io/timelinejs-template/about.html](https://thecdil.github.io/timelinejs-template/about.html)

## Changes in 'timelinez/jfk' [#1] over 'thecdil/timelinejs-template' [#2]. 

* Git commit ID is in each generated page (at the bottom, with reduced font size)
* The JavaScript techologies are sourced from a CDN now
* Hours/Minute added to some timeline entries (that was supported in thecdil/timelinejs-template but now shown)

## Changes in [#1] vs [timelinez/jfk-OLD](https://github.com/timelinez/jfk-OLD)

No part of the JS technology from that repos is retained here. Only the timeline was taken forward (fixed up & enhanced). The `timelinez/jfk-OLD` was an earlier attempt to engineer the same experience, though with a vertical timeline rather than horizontal.

## Further Changes Needed

A single timeline in a long multi-event JSON document is going to be problematic for merging. Better would be one JSON file per event.

# Why Git & GitHub

Git is a history maintaining merkle tree. You can to batch operations on it (clone/checkout, change files en masse, commit back in one commit). You can keep note of the hashes of the published items and enjoy that it is tamper evident as a system. You can solicit and review changes from people outside your organization if you want. Others can verify that times presented online purported to be from a Git repo on GitHub can actually be verified as such. Indeed, screenshots purported to be from a repo can be verified if you're willing to type in a commit ID as part of your verification.

![image](https://user-images.githubusercontent.com/82182/100537959-a26a0280-3224-11eb-83a9-046c52b8bf62.png)
 
 GitHub also allow forks. One org could take another org's timeline and publish their own modifications to it. In the case of JFK's death, conspiracy theory people could publish their own timeline including all the additional events they think happened. Same rules for them though, Git makes their changes trackable and verifiable.  Orgs would add a license to make usage of the trademarks and copyright conditional for forked repositories.