# Twitter Users and Tweets Ranking

This social network analysis project aims to rank Twitter users based on the importance of their tweets using various ranking algorithms. It utilizes bipartite graph modeling for tweets and employs the HITS (Hyperlink-Induced Topic Search) algorithm to determine tweet authority values. These authority values are then reflected onto users as initial user importance. Furthermore, the PageRank algorithm is employed to rank users based on their importance within the Twitter network.

## Table of Contents

- [Introduction](#introduction)
- [Instructions](#instructions)
- [Files Description](#files-description)


## Introduction

The objective of this project is to rank Twitter users based on the importance of their tweets. This is achieved by modeling the data as a network and applying ranking algorithms learned in class. The project involves preprocessing text data, building a bipartite graph for tweets, utilizing the HITS algorithm to calculate tweet authority values, reflecting these values onto users, and finally, employing the PageRank algorithm to rank users.

## Instructions

1. **Preprocessing Text Data**: Remove stopwords, punctuation, and perform other necessary cleaning steps on the text data.
2. **Bipartite Graph Construction**: Build a bipartite graph for tweets.
3. **HITS Algorithm**: Utilize the HITS algorithm to calculate tweet authority values.
4. **Reflecting Authority Values onto Users**: Reflect tweet authority values onto users as initial user importance.
5. **PageRank Algorithm**: Use the PageRank algorithm to rank users based on their importance within the Twitter network.

## Files Description

- **Twitter_dataset**: Contains tweets data and the user authoring each tweet.
- **User_following**: Contains the user and who follows whom.

