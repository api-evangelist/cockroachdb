---
title: "What write skew looks like"
url: "https://cockroachlabs.com/blog/what-write-skew-looks-like"
date: "2022-03-31"
author: "Justin Jaffray"
feed_url: "https://cockroachlabs.com/rss.xml"
---
Syndication from What Does Write Skew Look Like by Justin Jaffray This post is about gaining intuition for Write Skew, and, by extension, Snapshot Isolation. Snapshot Isolation is billed as a transaction isolation level that offers a good mix between performance and correctness, but the precise meaning of “correctness” here is often vague. In this post I want to break down and capture exactly when the thing called “write skew” can happen.
