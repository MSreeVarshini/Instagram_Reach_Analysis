# Instagram Reach Analysis using Python

Instagram is one of the most popular social media applications today. People using Instagram professionally are promoting their business, building a portfolio, blogging and creating various kinds of content. As Instagram is a popular application used by millions of people with different niches, Instagram keeps updating itself for the betterment of content creators and users. But, as this keeps changing, it affects the reach of our posts that impacts us in a long run. So, if a content creator wants to do well on Instagram, they have to look at the data of their Instagram reach. That is where the use of Data Science in social media comes in to the picture. If you want to learn how to use our Instagram data for the task of Instagram reach analysis, I'll take you through Instagram Reach Analysis using Python, which will help content creators to understand how to adapt to the changes in Instagram in a long run.



## Instagram Reach Analysis:

I have been reseraching Instagram reach for a long time now. Everytime I post on my Instagram account, I collct data on how well the post reach after a week. That helps in understnding how Instagram's algorithm is working. If you want to analyze the reach of your Intagram account, you have to collect your data manually as there are some APIs, but they don't work well. So, It's better to collect your Instagram data manually.

If you are a Data Science student and want to learn Instagram reach analysis using python, you can use the data I have collected from my Instagram account. You can download the dataset I have used for the task of Instagram reach analysis from here. Now, in the further sections, I'll take you through the task of Instagram reach analysis and prediction with machine learning using python.


#### Instagram Reach Analysis using Python:

Let's start the task of analyzing the reach of my Instagram account by importing the necessary Python libraries and th dataset. Don't forget to install wordcloud (!pip3 install wordcloud). Make sure there are no null values and if null values exist, drop them all. Have a look at the insights of the columns to understand the data type of all.


#### Analyzing Instagram Reach:

Now, it's time to for analyzing the reach of my Instagram posts. I will first have a look at the distribution of impressions I have received from home. The impressions that I got from the home section on Instagram shows how much my posts reach my followers. Looking at the impressions from home, I can say that it's hard to reach all followers daily. 

Let's have an attention for the impressions that are received from hashtags. Hashtags are tools that are generally used to categorize our posts on Instagram so that we can reach more people based on the kind of content we are creating. The analysis on hashtag impressions shows that not all posts can be reached using hashtags, but many users can be reached from hashtags.

Let's have a look at the impressions that are received from the explore section of Instagram. The explore section of Instagram is the recommendation system of Instagram. It recommends posts to the users based on their preferences and interests. By looking at the impressions that I've received from the explore section, I can say that Instagram doesn't recommend our posts much to the users. Some posts have received a good reach from the explore section, but it's still very low compared to the reach that is received from hashtags.


#### Analyzing Content:

The dataset has two columns namely caption and hashtags, which will help us to understand the kind of content I post on Instagram. In order to analyze the content, I am using wordcloud to look at the most used words in the captions of the posts.


#### Analyzing Relationships:

It is really important to understand the relationships to find the most important factors of Instagram posts. It will also help us in understanding how the Instagram algorithm works. For analyzing relationships between 2 entities, I am using scatterplots. 

-> A linear relationship can be seen between number of likes and number of impressions on my posts.

-> Upon analyzing the relationship between number of comments and nuumber of impressions, I can say that the number of comments we get on a post doesn't affect it's reach.

-> The relationship between number of shares and number of impressions states that more number of shares will result in a higher reach, but shares doesn't affect the reach of a post as much as likes do.

-> There is a linear relationship between number of saves and number of impressions of my Instagram post.

Now, the correlation of all columns with impressions column can be found with the help of the code provided.
From the above insights, we can say that more likes and saves will help you get more reach on Instagram. The higher number of shares will also help in getting more reach, but low number of shares will not affect your reach either.


#### Analyzing Conversion Rate:

In Instagram, conversion rate means how many followers you are getting from the number of profile visits from a post. The formula that you can use to calculate conversion rate is [(follows / profile visits) * 100]. Now, it's time to have a look at the conversion rate of my Instagram account. The conversion rate of my account is 41% which sounds like a very good conversion rate. 



## Instagram Reach Prediction Model:

In this section, a machine learning model will be trained to predict the reach of an Instagram post for which the data is splitted into train and test sets. The model is trained using PassiveAggressiveRegressor. The model score of 90 has been achieved.



## Conclusion:

So, this is how you can analyze and predict the reach of Instagram posts with machine learning using python. If a content creator wants to do well on Instagram for a long run, they have to look at the data of their Instagram reach. That is where the use of Data Science in social media comes in.

I hope you liked this article on the task of Instagram Reach Analysis using Python :)
