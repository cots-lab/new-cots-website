---
title: "Genetic Algorithm Based Deep Time Series Similarity Searching Approach for Acoustic Fingerprinting"
layout: post_1 # modified version of layout.post
date: 2023-05-10T15:14:39+10:00
image: assets/images/projects/Acoustic-Fingerprinting.jpg
weight: 5
---

###### Author [R.M.C.P.Rathnayake](/author/RMCPRathnayake.html)

###### Supervisor: [Dr. M.I.E.Wickramasinghe](/team/dr-manju/index.html)
###### Co-supervisor: [ Mr. M.A.P.P.Marasinghe](/team/pasindu-marasinghe/index.html)

#### Abstract
The thriving global music consumption has led to concerns regarding detecting
violations of music copyright and difficulty for users in finding and retrieving
specific music. As a result, exploring ways to effectively retrieve information
regarding a piece of music based on its audio features rather than relying on
metadata or textual information has become a significant research concern.
Acoustic fingerprinting is an approach of interest in performing such information
retrieval, which involves identifying an audio signal by examining its unique
acoustic characteristics.

Audio is expressed through the transmission of sound waves and is naturally
associated with the dimension of time. An audio signal is a time series, i.e.,
a collection of amplitude values recorded over time. Therefore, leveraging
recent literature to compute the similarity between two time series, a novel
Machine Learning (ML)-based audio fingerprinting system is proposed in this
study. However, tuning necessary ML hyperparameters that heavily influence the
system’s performance, is one of the major concerns in developing such a system. To
address this issue, a Genetic Algorithm (GA)-based approach for hyperparameter
tuning was employed, which resulted in a significant improvement in the system’s
performance. The proposed audio fingerprinting system was able to achieve a hit
rate of 64.44% while the powerful and widely adopted Shazam algorithm achieved
only a hit rate of 21.22% for the same dataset of degraded audio.
