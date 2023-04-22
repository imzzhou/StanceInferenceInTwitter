# Stance Inference in Twitter through Graph Convolutional Collaborative Filtering Networks with Minimal Supervision

This repository contains the tweet IDs used in our study. The paper can be found at the following link: [arxiv](https://arxiv.org/pdf/2303.15532.pdf)

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

If you use the dataset provided in this repository, please cite our work:

@article{zhou2023stance,
  title={Stance Inference in Twitter through Graph Convolutional Collaborative Filtering Networks with Minimal Supervision},
  author={Zhou, Zhiwei and Elejalde, Erick},
  journal={arXiv preprint arXiv:2303.15532},
  year={2023}
}
