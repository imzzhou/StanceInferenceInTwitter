# Stance Inference in Twitter through Graph Convolutional Collaborative Filtering Networks with Minimal Supervision

This repository contains the tweet IDs used in our study. The papers can be found at the following links: [Paper 1](https://dl.acm.org/doi/10.1145/3543873.3587640) and [Paper 2](https://epjdatascience.springeropen.com/articles/10.1140/epjds/s13688-024-00469-y)

## Overview

In our research, we conducted experiments on the two large datasets of tweets to gain insights and draw conclusions about a particular topic. Due to Twitter's terms of service, we cannot share the full text of the tweets. However, we are providing the tweet IDs used in our work so that researchers can reconstruct the dataset by hydrating the tweet IDs using tools such as [Tweepy](https://www.tweepy.org/) or [Twarc](https://github.com/DocNow/twarc).

## Tweet IDs

The dataset provided in this repository is a list of tweet IDs, which are unique identifiers for each tweet. These IDs can be used to download the original tweets' content and metadata.

To hydrate the tweet IDs and obtain the full dataset, you can follow these steps:

1. Make sure you have a Twitter Developer account and access to the Twitter API. If you don't have an account, you can [apply for one](https://developer.twitter.com/en/apply-for-access).
2. Choose a hydration tool, such as [Tweepy](https://www.tweepy.org/) or [Twarc](https://github.com/DocNow/twarc), and install it if necessary.
3. Follow the tool's documentation to download the tweet content and metadata using the tweet IDs provided in this repository.

Please note that some tweet IDs might not be available due to account suspensions, deletions, or other reasons. In such cases, the tool might return an error or skip the unavailable tweet.

## Citation

If you use the dataset provided in this repository, please cite our works:

1. Zhou, Z. and Elejalde, E., 2023, April. Stance inference in Twitter through graph convolutional collaborative filtering networks with minimal supervision. In Companion Proceedings of the ACM Web Conference 2023 (pp. 1030-1038).
```
@inproceedings{zhou2023stance,
  title={Stance inference in Twitter through graph convolutional collaborative filtering networks with minimal supervision},
  author={Zhou, Zhiwei and Elejalde, Erick},
  booktitle={Companion Proceedings of the ACM Web Conference 2023},
  pages={1030--1038},
  year={2023}
}
```

2. Zhou, Z., Elejalde, E. Unveiling the silent majority: stance detection and characterization of passive users on social media using collaborative filtering and graph convolutional networks. EPJ Data Sci. 13, 28 (2024).
```
@article{zhou2024unveiling,
  title={Unveiling the silent majority: stance detection and characterization of passive users on social media using collaborative filtering and graph convolutional networks},
  author={Zhou, Zhiwei and Elejalde, Erick},
  journal={EPJ Data Science},
  volume={13},
  number={1},
  pages={28},
  year={2024},
  publisher={Springer Berlin Heidelberg}
}
```
