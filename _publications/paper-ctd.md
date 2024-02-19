---
title: "Enabling Contextual Soft Moderation on Social Media through Contrastive Textual Deviation"
collection: publications
permalink: /publication/paper-ctd
excerpt: 'Improving contextual soft moderation using unsupervised stance detection'
venue: '33rd Usenix Security Symposium'
paperurl: ''
date: 2024-08-14
citation: 'P. Paudel, M.H. Saeed, R. Auger, C. Wells and G. Stringhini, “Enabling Contextual Soft Moderation
on Social Media through Contrastive Textual Deviation,” 33rd Usenix Security Symposium, Philadelphia,
PA, USA, 2024'
---
⏳⏳ Pre-print coming soon. Stay tuned! 👀

Automated soft moderation systems are unable to ascertain if a post supports or refutes a false claim, resulting in a large number of contextual false positives. This limits their effectiveness, for example undermining trust in health experts by adding warnings to their posts or resorting to vague warnings instead of granular fact-checks, which result in desensitizing users. In this paper, we propose to incorporate stance detection into existing automated soft-moderation pipelines, with the goal of ruling out contextual false positives and providing more precise recommendations for social media content that should receive warnings. We develop a textual deviation task called Contrastive Textual Deviation (CTD), and show that it outperforms existing stance detection approaches at the task of stance detection for soft moderation. We then integrate CTD into the state-of-the-art system for automated soft moderation Lambretta, showing that our approach can reduce contextual false positives from 20% to 2.1%, providing another important building block towards deploying reliable automated soft moderation tools on social media.