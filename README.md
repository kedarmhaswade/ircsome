ircsome
=======

An experiment in sentiment analysis.

The What
========

Is it really possible to do sentiment analysis if you are given load of data?
We decided to give this a try, while discussing things over dinner table. I decided to create a simple project, get the data from (English) IRC logs, anonymize the data and then try to do some kind of sentiment analysis. This is perhaps a huge task, but we expect it to be fun.

What should we be able to predict/say from this data? I guess in order to be useful, it needs to be able to do the following:

1. Given a date range, it should be able to find clusters of people with similar mindset. This is the classic clustering I suppose. Thus the clusters could be adjectives like _generous_, _kind_, _helpful_, _strict_, _professional_, _calm_, _playful_, _serious_ etc.
2. Given a day, it should be possible to say what __mood__ a particular person was in.
3. Given a handle, predict how likely s/he is going to be say _angry_.
4. 
