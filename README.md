# hacker-news-posts
Exploration of Hacker News posts

## Context
[Hacker News](https://news.ycombinator.com/) is a site started by the startup incubator Y Combinator, where user-submitted stories (known as 'posts') are voted and commented upon. Hacker News is extremely popular in technology and startup circles, and posts that make it to the top of Hacker News' listings can get hundreds of thousands of visitors as a result.

In this project, we'll work with a [dataset](https://www.kaggle.com/hacker-news/hacker-news-posts) of submissions to Hacker News (HN).

We're specifically interested in posts whose titles begin with either Ask HN or Show HN.

- Users submit Ask HN posts to ask the Hacker News community a specific question.
  - `Ask HN: How to improve my personal website?`
  - `Ask HN: Am I the only one outraged by Twitter shutting down share counts?`
  
- Likewise, users submit Show HN posts to show the Hacker News community a project, product, or just generally something interesting.
  - `Show HN: Wio Link  ESP8266 Based Web of Things Hardware Development Platform`
  - `Show HN: Something pointless I made`

## Aim
The aim of this project is to compare these two types of posts (Ask HN and Show HN) to determine the following:

1. Do Ask HN or Show HN receive more comments on average?
2. Do posts created at a certain time receive more comments on average?

## Skills / Libraries / Tools
We continue to use the standard Python Library only to do our practical data analysis, touching upon:

- Working with strings
- Dates and times
- Jupyter Notebook
