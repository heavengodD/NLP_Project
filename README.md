# NLP_Project
Text classification and summarization of amazon reviews

Sentiment analysis is a classification process whereby machine learning techniques are applied on text-driven
datasets in order to analyze its sentiment, e.g. a message being positive or negative about a certain topic. We want
to investigate if these sentiment analysis techniques are also feasible for application on product reviews form
Amazon.com. In this study, different machine learning algorithms are compared, trained and tested on a dataset (N
= 60, 000) containing product reviews from Amazon.com which are randomly selected from dataset available from
Kaggle containing 4 million reviews. The performance of three different algorithms were compared: Multinomial
Naive Bayes (MNB), Linear Support Vector Machine (LSVM) and Long short-term memory network (LSTM). The
LSTM resulted in the highest performance (Accuracy = 0.90, AUC = 0.96). Thereafter, to evaluate the LSTM
model, it was applied on the remaining 3.94 million reviews from the Kaggle dataset, as well as on a new scraped
dataset from Amazon.com containing reviews on products from different categories. This resulted in a very
accurate classification, with the best results for reviews on furniture products (Accuracy = 0.92). In conclusion,
LSTM networks are very suitable for classification of the sentiment on product reviews and the results do not
change significantly for different categories. Further study is needed to investigate if the classification remains
accurate when including more than two classes (e.g. introducing a neutral class).



Setiment Analysis have loads of application right now as its directly connected to the human
interaction. It can be used as data analysis in business aplication, usage in virtual assistants,
for social media, and several other natural language processing applications. We have so many
major companies that are working towards setiment analysis and its related applications. The
insight you gain from analyzing consumer sentiment can be used to improve your business in
a variety of ways:
Drive decisions: Sentiment analysis provides insight on any change in public opinion related
to your brand that will either support or negate the direction your business is heading. High or
low sentiment scores help you identify ways to restructure teams or develop new creative
strategies.
Highlight competitive advantage: There are strategic benefits in knowing consumer sentiment
related to your competitors. Sentiment analysis can help predict customer trends, so keeping a
pulse on public opinion of other businesses in your industry provides a control group to
compare your scores against.
Predict product lifecycle: Data derived from sentiment analysis reveals how well your product
is faring in the market, how this performance can be improved, and if it‟s time to pull it off the
shelves.
Improve customer experience: Never underestimate the return on investment from a customer
who feels like his voice has been heard. Understanding consumer sentiment provides a direct
opportunity to fix the problems real users identify and put more resources behind the things
your business is doing well.
