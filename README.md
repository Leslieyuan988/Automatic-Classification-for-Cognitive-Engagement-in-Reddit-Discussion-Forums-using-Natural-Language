# Topic Modeling with Latent Dirichlet Allocation (LDA)

Designed a subreddit recommendation engine based on similar topics according to Reddit documents.

Dataset is collected from Open Source Reddit API: https://www.reddit.com/dev/api/.
- data_collection.ipynb describe a simple data pipeline that collect essential data and store them in PostgreSQL.
- data_preparation.ipynb assesses and validate assumptions using EDA, ensuring data are prepared for modeling.
- topic_modeling.ipynb extract latent features of reddit transcript using LDA and map them to the most similar subreddits.
