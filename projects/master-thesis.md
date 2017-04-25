---
layout: portfolio
title: "Master's Thesis: \n News Filtering Based on Intrinsic User Feedback and a Modified ESA Model"
tags: [Study, Research]
category: portfolio
summary: "In this thesis I implemented a recommendation engine that filters top news of the day."
---
{% include base.html %}
## Abstract
Today’s news travels within seconds across earth. While in the past it took messengers days, or a ticker minutes, today it takes just a Tweet to get a news break across the globe. The fast travel of news also allows for the gathering of a lot of news. News websites are cluttered with articles on many topics even if they focus for example on only technology related news. It becomes more confusing to stay informed on the topics of interest. There is just too much noise of information.

In this thesis I will present a news filtering system in form of a website that filters out the noisy uninteresting news and will help the consumer to focus on the news she is interested in.

The filtering is reduced to a classification problem of text documents. In this thesis I compare different classification algorithms with the text features models TF-IDF, LDA, and a modified ESA which is introduced in this thesis.

Tests on the Reuters-21578 data set show that all algorithms yield good results and that the modified ESA model performs best. Tests on user data gathered during a five months period show that simple classification cannot solve the filtering problem alone. It seems that individual user data needs to be enriched with collaborative user data.

## Details
I implemented the system mostly in Python using [gensim](http://radimrehurek.com/gensim/), [Scikit-learn](http://scikit-learn.org), [Scipy](http://www.scipy.org/), [Numpy](http://www.numpy.org/). The front end uses [Flask](http://flask.pocoo.org/) and Twitter Bootstrap. Most parts of the system communicate via [STOMP](http://stomp.github.com) and its server implementation [CoilMQ](https://github.com/hozn/coilmq/).

The crawler is written in Ruby.

I added an implementation of a modified ESA model to gensim.

Some calculations were done on an EC2 instance.

You can download or fork the complete source code [here](https://github.com/blacklab/nyan) and find the thesis [here]({{ base }}/downloads/Masters_Thesis_Karsten_Jeschkies.pdf).

## Front End Screenshots
![Login]({{ base }}/public/img/login.png "Login")
![Password]({{ base }}/public/img/change_password.png "Change Password")
![All News]({{ base }}/public/img/all_news_hidden_read.png "All News")
![Manage Subscriptions]({{ base }}/public/img/manage_subscriptions.png "Manage Subscriptions")
![Top News]({{ base }}/public/img/top_news.png "Top News")
![Reading View]({{ base }}/public/img/reading_view.png "Reading View")
