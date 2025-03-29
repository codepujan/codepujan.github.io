---
title: "Unraveling the Web of Disinformation: Exploring the Larger Context of State-Sponsored Influence Campaigns on Twitter"
collection: publications
permalink: /publication/paper-influence-campaigns
excerpt: 'Improving textual soft moderation on Twitter using Learning To Rank'
venue: '27th International Symposium on Research in Attacks, Intrusions and Defenses'
paperurl: 'https://dl.acm.org/doi/abs/10.1145/3678890.3678911'
date: 2023-09-30
citation: 'Saeed, Mohammad Hammas, et al. "Unraveling the Web of Disinformation: Exploring the Larger Context of State-Sponsored Influence Campaigns on Twitter." Proceedings of the 27th International Symposium on Research in Attacks, Intrusions and Defenses. 2024.'
---

Social media platforms offer unprecedented opportunities for connectivity and exchange of ideas; however, they also serve as fertile grounds for the dissemination of disinformation. Over the years, there has been a rise in state-sponsored campaigns aiming to spread disinformation and sway public opinion on sensitive topics through designated accounts, known as troll accounts. Past works on detecting accounts belonging to state-backed operations focus on a single campaign. While campaign-specific detection techniques are easier to build, there is no work done on developing systems that are campaign-agnostic and offer generalized detection of troll accounts unaffected by the biases of the specific campaign they belong to.
In this paper, we identify several strategies adopted across different state actors and present a system that leverages them to detect accounts from previously unseen campaigns. We study 19 state-sponsored disinformation campaigns that took place on Twitter, originating from various countries. The strategies include sending automated messages through popular scheduling services, retweeting and sharing selective content and using fake versions of verified applications for pushing content. By translating these traits into a feature set, we build a machine-learning-based classifier that can correctly identify up to 94% of accounts from unseen campaigns. Additionally, we run our system in the wild and find more accounts that could potentially belong to state-backed operations. We also present case studies to highlight the similarity between the accounts found by our system and those identified by Twitter.
