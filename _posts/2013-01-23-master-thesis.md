---
layout: portfolio_entry
title: "Master's Thesis: \n News Filtering Based on Intrinsic User Feedback and a Modified ESA Model"
tags: [Study, Research]
summary: "In this thesis I implemented a recommendation engine that filters top news of the day."
---
#### Abstract
Today’s news travels within seconds across earth. While in the past it took messengers days, or a ticker minutes, today it takes just a Tweet to get a news break across the globe. The fast travel of news also allows for the gathering of a lot of news. News websites are cluttered with articles on many topics even if they focus for example on only technology related news. It becomes more confusing to stay informed on the topics of interest. There is just too much noise of information.

In this thesis I will present a news filtering system in form of a website that filters out the noisy uninteresting news and will help the consumer to focus on the news she is interested in.

The filtering is reduced to a classification problem of text documents. In this thesis I compare different classification algorithms with the text features models TF-IDF, LDA, and a modified ESA which is introduced in this thesis.

Tests on the Reuters-21578 data set show that all algorithms yield good results and that the modified ESA model performs best. Tests on user data gathered during a five months period show that simple classification cannot solve the filtering problem alone. It seems that individual user data needs to be enriched with collaborative user data.

#### Details
I implemented the system mostly in Python using [gensim](http://radimrehurek.com/gensim/), [Scikit-learn](http://scikit-learn.org), [Scipy](http://www.scipy.org/), [Numpy](http://www.numpy.org/). The front end uses [Flask](http://flask.pocoo.org/) and Twitter Bootstrap. Most parts of the system communicate via [STOMP](http://stomp.github.com) and its server implementation [CoilMQ](https://github.com/hozn/coilmq/).

The crawler is written in Ruby.

I added an implementation of a modified ESA model to gensim.

Some calculations were done on an EC2 instance.

You can download or fork the complete source code [here](https://github.com/blacklab/nyan) and find the thesis [here]({{ site.url }}/downloads/Masters_Thesis_Karsten_Jeschkies.pdf).
. 

#### Front End Screenshots
<ul class="thumbnails">
  <li class="span4">
    <a href="{{ site.url }}/assets/img/login.png" class="thumbnail">
      <img data-src="holder.js/300x200" alt="Login" src="{{ site.url }}/assets/img/login.png">
    </a>
  </li>
  <li class="span4">
    <a href="{{ site.url }}/assets/img/change_password.png" class="thumbnail">
      <img data-src="holder.js/300x200" alt="Change Password" src="{{ site.url }}/assets/img/change_password.png">
    </a>
  </li>
  <li class="span4">
    <a href="{{ site.url }}/assets/img/all_news_hidden_read.png" class="thumbnail">
      <img data-src="holder.js/300x200" alt="All News" src="{{ site.url }}/assets/img/all_news_hidden_read.png">
    </a>
  </li>
</ul>

<ul class="thumbnails">
  <li class="span4">
    <a href="{{ site.url }}/assets/img/manage_subscriptions.png" class="thumbnail">
      <img data-src="holder.js/300x200" alt="Manage Subscriptions" src="{{ site.url }}/assets/img/manage_subscriptions.png">
    </a>
  </li>
  <li class="span4">
    <a href="{{ site.url }}/assets/img/top_news.png" class="thumbnail">
      <img data-src="holder.js/300x200" alt="Top News" src="{{ site.url }}/assets/img/top_news.png">
    </a>
  </li>
  <li class="span4">
    <a href="{{ site.url }}/assets/img/reading_view.png" class="thumbnail">
      <img data-src="holder.js/300x200" alt="Top News" src="{{ site.url }}/assets/img/reading_view.png">
    </a>
  </li>
</ul>
