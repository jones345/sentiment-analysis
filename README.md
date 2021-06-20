# sentiment-analysis
Sentiment analysis (or opinion mining) is a natural language processingtechnique used to determine whether data is positive, negative or neutral. Sentiment analysis is often performed on textual data to help businesses monitor brand and product sentiment in customer feedback, and understand customer needs.


topic covered

1.What Is Sentiment Analysis?
2.Types of Sentiment Analysis
3.Why Is Sentiment Analysis Important?
4.How Does Sentiment Analysis Work?
5.Sentiment Analysis Challenges
6.Sentiment Analysis Applications & Examples
7.Sentiment Analysis Tools & Tutorials
8.Sentiment Analysis Research & Courses


What Is Sentiment Analysis
Sentiment analysis is the process of detecting positive or negative sentiment in text. It’s often used by businesses to detect sentiment in social data, gauge brand reputation, and understand customers.

Since customers express their thoughts and feelings more openly than ever before, sentiment analysis is becoming an essential tool to monitor and understand that sentiment. Automatically analyzing customer feedback, such as opinions in survey responses and social media conversations, allows brands to learn what makes customers happy or frustrated, so that they can tailor products and services to meet their customers’ needs. 


Types of Sentiment Analysis
Sentiment analysis models focus on polarity (positive, negative, neutral) but also on feelings and emotions (angry, happy, sad, etc), urgency (urgent, not urgent) and even intentions (interested v. not interested). 
Fine-grained Sentiment Analysis
    Very positive
    Positive
    Neutral
    Negative
    Very negative
This is usually referred to as fine-grained sentiment analysis, and could be used to interpret 5-star ratings in a review, for example:

    Very Positive = 5 stars
    Very Negative = 1 star
    
 Emotion detection
 This type of sentiment analysis aims to detect emotions, like happiness, frustration, anger, sadness, and so on. Many emotion detection systems use lexicons (i.e. lists of words and the emotions they convey) or complex machine learning algorithms.
 One of the downsides of using lexicons is that people express emotions in different ways. Some words that typically express anger, like bad or kill (e.g. your product is so bad or your customer support is killing me) might also express happiness (e.g. this is bad ass or you are killing it).
 
 Aspect-based Sentiment Analysis
 Usually, when analyzing sentiments of texts, let’s say product reviews, you’ll want to know which particular aspects or features people are mentioning in a positive, neutral, or negative way.hat's where aspect-based sentiment analysis can help, for example in this text: "The battery life of this camera is too short", an aspect-based classifier would be able to determine that the sentence expresses a negative opinion about the feature battery life.
 
 Multilingual sentiment analysis
 Multilingual sentiment analysis can be difficult. It involves a lot of preprocessing and resources. Most of these resources are available online (e.g. sentiment lexicons), while others need to be created (e.g. translated corpora or noise detection algorithms), but you’ll need to know how to code to use them.
 
 Sentiment Analysis types
    Rule-based: these systems automatically perform sentiment analysis based on a set of manually crafted rules.
    Automatic: systems rely on machine learning techniques to learn from data.
    Hybrid systems combine both rule-based and automatic approaches.
 
 Rule-based Approaches
 Usually, a rule-based system uses a set of human-crafted rules to help identify subjectivity, polarity, or the subject of an opinion.
 These rules may include:
     Stemming, tokenization, part-of-speech tagging and parsing.
    Lexicons (i.e. lists of words and expressions).
    
 Here’s a basic example of how a rule-based system works:

    Defines two lists of polarized words (e.g. negative words such as bad, worst, ugly, etc and positive words such as good, best, beautiful, etc).
    Counts the number of positive and negative words that appear in a given text.
    If the number of positive word appearances is greater than the number of negative word appearances, the system returns a positive sentiment, and vice versa. If the numbers are even, the system will return a neutral sentiment.   
    
    
