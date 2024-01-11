---
title: "Genetic Algorithm Based Deep Time Series Similarity Searching Approach for Acoustic Fingerprinting"
layout: post_1 # modified version of layout.post
date: 2023-05-10T15:14:39+10:00
image: /assets/images/author/john-doe.jpg
weight: 5
---

#### Under Guidence Of
* Supervisor: Dr. M.I.E. Wickramasinghe
* Co-supervisor: Mr. M.A.P.P. Marasinghe

#### Introduction 
The thriving global music consumption has led to concerns regarding detecting
violations of music copyright and difficulty for users in finding and retrieving
specific music. As a result, exploring ways to effectively retrieve information
regarding a piece of music based on its audio features rather than relying on
metadata or textual information has become a significant research concern.
Acoustic fingerprinting is an approach of interest in performing such information
retrieval, which involves identifying an audio signal by examining its unique
acoustic characteristics.

#### Research Aim & Objectives

- ###### Research Aim
  - This research aims to contribute to the body of science by exploring the potential
    of GA to formulate an effective and better-performing acoustic fingerprinting
    method.
  
- ###### Research Objectives
  - Studying and identifying the most appropriate Deep Time Series Similarity
    Searching (DTSSS) approaches for acoustic fingerprinting.

  - Studying and identifying an effective method of applying the GA to the
    acoustic fingerprinting model.

  - Investigating and identifying optimal algorithmic variations of GA that
    can contribute to the performance enhancement of the proposed acoustic
    fingerprinting model.

  - Designing the acoustic fingerprinting model.

  - Implementing the acoustic fingerprinting model.

  - Evaluating the acoustic fingerprinting model.

#### Research Questions?
- What will be the most suitable DTSSS approach to implement an acoustic
  fingerprint extraction method? (RQ1)

- Can the performance of the acoustic fingerprinting method be improved via
  the use of GA? (RQ2)

#### Discussion

##### Model Performance:

LSTM-based SNNs outperform CNN-based SNNs for audio fingerprinting tasks.
The LSTM-based SNN exhibits superior metrics (AUC, accuracy, precision, recall, F1 score), showcasing its effectiveness in processing temporal data.

##### Hyperparameter Optimization:

Genetic Algorithm (GA) optimization enhances the LSTM-based SNN's performance.
The optimized model surpasses the baseline in all performance metrics, indicating the positive impact of GA on hyperparameter tuning.

##### Comparison with Shazam Algorithm:

The proposed audio fingerprinting system outperforms the widely used Shazam algorithm.
The proposed model achieves significantly higher accuracy and demonstrates better precision, recall, and F1 score.

##### Robustness Analysis:

The proposed model shows greater robustness, particularly for tempo and pitch augmentation, compared to the Shazam algorithm.
Results confirm the efficacy of machine learning-based methods over traditional digital signal processing-based methods for audio fingerprinting.

> **_In conclusion:_** the study recommends LSTM-based SNNs, optimized with GA, as a more effective solution for audio fingerprinting, surpassing both CNN-based SNNs and the Shazam algorithm in accuracy and robustness.

#### Limitations and Drawbacks
To aid researchers with limited computational resources, the creators of the FMA
dataset have provided subsets of the data. Therefore, in this study, a subset of
the FMA dataset was utilized for training and testing tasks. Since the dataset
with the complete songs is about 1 TB in size, this study utilized a smaller subset
that only contained 30-second song clips.

Due to the limited computing resources, specifically the amount of RAM
available, only a smaller batch size can be accommodated in the RAM. When
the batch size gets decreased training time gets increased. Therefore, each
chromosome in a particular generation was trained and tested on a relatively
smaller amount of data to decrease the training time, which heavily contributes
to the fitness calculation time.

#### Conclusion
- ###### Research Question RQ1
  - Aim: Identify the most suitable DTSSS approach for creating an acoustic fingerprinting model.

  - Approach: An empirical investigation comparing RNN-based (specifically LSTM-based) and CNN-based      DTSSS models under the same conditions.

  - Finding: The LSTM-based DTSSS model outperformed the CNN-based DTSSS model, achieving a superior AUC performance of 0.91 compared to 0.77. This leads to the conclusion that the RNN-based approach is more suitable for audio fingerprinting.

- ###### Research Question RQ2
  - Aim: Explore the potential of Genetic Algorithm (GA) in improving the performance of the audio fingerprinting method through hyperparameter optimization.

  - Approach: Investigate whether GA can enhance the performance of the DTSSS model by optimizing hyperparameters.

  - Finding: The optimal set of hyperparameters suggested by GA significantly improved the DTSSS model's performance, raising the AUC value from 0.91 to 0.96. This confirms that GA-based hyperparameter optimization can enhance the audio fingerprinting method.

#### Concluding Remarks
> **_Conclution:_** In this study, an audio fingerprinting system was proposed. The proposed
system was constructed incorporating the superior DTSSS model out of the two
state-of-the-art models. The performance of this system was further enhanced by
utilizing GA and finally compared against the Shazam algorithm. In comparison
to the powerful Shazam algorithm, the proposed audio fingerprinting system
demonstrates a notable improvement in accuracy with a value of 64.44%, while
the Shazam algorithm only attained an accuracy of 21.22% for the same dataset.
Furthermore, the proposed model displays superior performance in handling pitch
and tempo augmentations compared to the Shazam algorithm.

###### Author [R.M.C.P.RathnayakeRathnayake](/author/Rathnayake.html)