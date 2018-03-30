# Twitter Sentiment Analysis

This API integrates the Twitter API with the IBM Watson Tone Analyzer API to detect any strong emotions within
a given tweet.

A detectable tone is one of the following:
* Anger
* Fear
* Joy
* Sadness
* Analytical
* Confident
* Tentative

## Endpoints

```
/analyze?user={twitter_handle}&count={count}
```
Searches and analyzes the most recent tweets of a user.


```
/retrieve/tone/{tone_id}
```
Pulls tweets of a given tone from the database.


```
/retrieve/user/{twitter_handle}
```
Pulls tweets of a given user from the database.
