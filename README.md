# Sentiment of Podcast Reviews vs Ratings, with VADER and BERT

In two Colab Notebooks we:
- Compare VADER and distilBERT as sentiment classifiers on [1 million podcast reviews](https://www.kaggle.com/datasets/thoughtvector/podcastreviews) from Apple Podcasts.
- Fine-tune distilBERT to predict the ratings from the content of the reviews.
- Investigate the connection between the sentiment of reviews and the rating given by the user.

One motivation for this is that while the sentiment of the reviews is closely associated with the ratings, there is still some information in the reviews about user preference that is not contained in the ratings. Some 1 star reviews make it clear that they overall like the podcast but want to make a constructive criticism, for example.

The notebooks can be found as blog posts [here](https://david-recio.com/2022/10/21/vader-bert-podcast-reviews.html) and [here](https://david-recio.com/2022/10/21/bert-fine-tune-podcast-reviews.html), with some code cells removed and output cleaned up for readability.
