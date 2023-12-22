# fake-news-detection
Building NLP-based techniques and models to investigate fake news
*Team: Harsh Vardhan Pachisia, Jackie Glasheen, Ridhi Purohit, Shwetha Srinivasan (Machine Learning Final Project)*

### Background
“If we are not serious about facts and what’s true and what’s not, if we can’t discriminate between serious arguments and propaganda, then we have problems”. Former President Barack Obama stated this over 6 years ago, and with the percolation of AI and the trend of social media amplifying unreliable information, the issue of fake news affecting public discourse will only get worse. The motivation behind this project is to provide a tool that helps stem the flow of misinformation. Skewed facts can influence public opinion, trigger social unrest and sway political outcomes as we have seen worldwide over the past decade.

### Data and Analysis undertaken
For this task, we utilize a dataset of 20,166 news articles hosted on Kaggle from different authors and sources. We had access to the text, title, and author of each article with 16,608 forming a training set and had been labeled as reliable/unreliable with the rest forming a test set and remaining unlabelled. We first cleaned the dataset (text, author, title) and then conducted pre-processing on the data such as removing stop words, stemming, and lemmatizing words. Based on our exploratory data analysis, we tuned various supervised and unsupervised machine learning models to ascertain which ones provide us with the best overall performance given the equal importance of false positives and negatives in fake news prediction.

### Findings
We find that supervised models tended to outperform the unsupervised models providing greater accuracy as well as easier interpretability for users. While we got consistently high test accuracy (>90%) across most of our models, when we dug deeper into our features, we find concerns about inbuild biases in our training data, which give us pause as to whether fake news prediction can be a task simply done by machines due to inherent question of defining what the ‘truth’ is. What may seem reliable to one person may be unreliable to another due to their worldview.

### Conclusion
While we do get good results from our models, we do believe that the way our training data has been labeled will play a major role in how our models would work in the real world, potentially skewing their results. Ultimately, this leads us to conclude that the task of fake news prediction cannot be solely done via machine learning, and needs a more robust, holistic, human-centric approach to understanding what the ‘truth’ itself is to determine reliability.
