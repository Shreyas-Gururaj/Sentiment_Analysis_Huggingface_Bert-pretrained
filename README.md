## Bert pretrained model provided by huggingface transformers library.

* Data was scraped from the google playstore website using <b> google-play-scraper </b> library
* The number of positive, negetive and neutral reviews was capped during scraping to have a balanced data set
* App reviews and app information was stored as .csv files for further operations
* Around 17k reviews was considered and the max_sequence length was chosen by looking at the distribution of the number of tokens in each review
* The model was trained with the hyperparameters and optimizer suggested by the authors of the paper
* Model finds it difficult to classify the neutral review into the correct class
