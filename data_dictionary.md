### Data Dictionary

This data dictionary provides a quick overview of features/variables/columns, alongside data types and descriptions. 

|Feature|Type|Source|Description|
|---|---|---|---|
|**title_selftext**|*str*|cleaned_engineered.csv|engineered by adding title + selftext columns|
|**title_selftext_sentiment_pos**|*int*|cleaned_engineered.csv|sentiment intensity analyzed positive score|
|**title_selftext_sentiment_neg**|*int*|cleaned_engineered.csv|sentiment intensity analyzed negative score| 
|**text_sentiment_compound**|*int*|cleaned_engineered.csv|sentiment intensity analyzed compound score|
|**topics**|*int*|author_scrape.csv|orignal subreddit column, binarized| 
|**title_word_count**|*intt*|cleaned_engineered.csv|counted words in subreddit title| 
|**title_length**|*int*|cleaned_engineered.csv|counted characters in subreddit title| 
|**very_wrong_preds_df**|*float*|best_preds.csv|created to analyze residuals|
|**wrong_preds_df**|*float*|best_preds.csv|created to analyze residuals
|**preds_df**|*float*|best_preds.csv|created to analyze residuals|
|**drop_cvec**|*float*|cvec.csv|created to aid in visualizations|
|**espresso_cvec**|*int*|cvec.csv|created to aid in visualizations|
|**beer_cvec**|*int*|cvec.csv|created to aid in visualizations|