---
layout:     post
title:      MacroBase
date:       2018-12-24 10:55:48 -0500
authors:    F. Abuzaid, P. Bailis, J. Ding, E. Gan, S. Madden, D. Narayanan, K. Rong, S. Suri (alphabetical)
paper_title:      "MacroBase: Prioritizing Attention in Fast Data"
conference: "ACM Transactions on Database Systems (TODS) - Best of SIGMOND 2017 Papers"
paper_url:  https://doi.org/10.1145/3276463
links:
  - anchor: Website
    url: https://macrobase.stanford.edu
  - anchor: Code
    url: https://github.com/stanford-futuredata/macrobase
---
MacroBase is a new a data analytics engine that prioritizes end-user
attention in high-volume fast data streams. MacroBase enables efficient,
accurate, and modular analyses that highlight and aggregate important and
unusual behavior, acting as a search engine for fast data. MacroBase is able
to deliver order-of-magnitude speedups over alternatives by optimizing the
combination of explanation (i.e., feature selection) and classification
tasks and by leveraging a new reservoir sampler and heavy-hitters sketch
specialized for fast data streams. As a result, MacroBase delivers accurate
results at speeds of up to 2M events per second per query on a single core.
The system has delivered meaningful results in production, including at a
telematics company monitoring hundreds of thousands of vehicles.
