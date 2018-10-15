---
title: CodeIT-Suisse Singapore 2018
author: 1st Place Winner
layout: post
---

We developed and deployed a PaaS webapp to solve various algorithmic challenges in Python, Java, and Javascript.

CodeIT Suisse is an annual algorithmic competition held by Credit Suisse, in tandem with teams from Hong Kong. We participated in the same competition [last year](./2017-09-24-CodeIT-Suisse.md).

This year, the algorithmic challenges included 0-1 knapsack on a directed graph, goldbach conjecture, OCR deep learning, image forensics, dynamic programming and machine learning using heuristics. You may view the [original host website here](http://cis2018-coordinator-sg.herokuapp.com/).

We thought it would be funny to throwback to our competition last year by reusing our team name. Surprisingly, many of the staff from the previous years recognised us, and ended up rooting for us.

This year, our team was more ready for the battle, having prepared various config files of the various server and languages we needed to use. Despite having a slow start due to some bad config files, we worked through the night and managed to climb the [leaderboards](http://cis2018-coordinator-sg.herokuapp.com/leaderboard/index.html) until we caught up to the 1st place team. It boiled down to whether I would be able to solve the tetris challenge before they solved the digit recognition challenge.

Unfortunately the other team did not manage to solve the digit recognition challenge, which ultimately became the reason why we managed to clinch first place.

You may find the link to our solution code [here](https://github.com/rrtheonlyone/Credit-Suisse-CodeSprint). Some solutions were implemented in python, to which a Django server was deployed for them; some were implemented in Java, which a Java Spring server was deployed; and the tetris AI was written in Javascript, where a node server was deployed.
