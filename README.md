![](http://img.shields.io/badge/license-MIT-blue.svg?style=flat-square)

# C# Oauth Twitter Library (Tweet only)
You can use this library when you want to tweet other CsharpApplication.This is simple POST method code.
# How to use
Input your four API Tokenkey and please write this code

```C#
using System.Twitter;
```
Tweet method example
```C#
  var twitter = new TwitterAPI(ConsumerKey,ConsumerKeySecret,AccessToken,AccessTokenSecret);

  var tweetValue = "HELLO"; //or Textbox.text and so on
  twitter.Tweet(tweetValue);　//tweet value
```
