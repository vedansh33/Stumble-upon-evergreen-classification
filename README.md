# Stumble-upon-evergreen-classification
StumbleUpon is a user-curated web content discovery engine that recommends relevant, high quality pages and media to its users, based on their interests. In other words, pages can either be classified as “ephemeral” or “evergreen”.
While some pages we recommend, such as news articles or seasonal recipes, are only relevant for a short period of time, others maintain a timeless quality and can be recommended to users long after they are discovered. In other words, pages can either be classified as “ephemeral” or “evergreen”. The ratings we get from our community give us strong signals that a page may no longer be relevant — but what if we could make this distinction ahead of time? A high quality prediction of “ephemeral” or “evergreen” would greatly improve a recommendation system like ours.
###Dataset>dr<
This is the link for the [dataset](https://www.kaggle.com/c/stumbleupon/data)
###Approach
-For this problem statement i used pretrained DistilBert transformer which had a Sequence to Sequence classifier.
-DistilBert had a pretrained tokenizer which helped me to tokenize the sentences .
- I used trainer for training purposes .
###Result
-The training error after taraining was .47 and the evaluation error was .57.
-The accuracy that i got on kaggle leaderboard was 81%
