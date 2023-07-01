# Sentiment Analysis on Historical Journals

This research project aims to perform sentiment analysis on historical journals to gain insights into the emotional and psychological experiences of authors, which are often overlooked in traditional historical accounts. The project compares the performance of three state-of-the-art models for sentiment analysis: BERT, DistilBERT, and RoBERTa. The hypothesis is that transformer-based models, such as these, will outperform traditional deep learning models for sentiment analysis due to their ability to capture complex relationships between words in a sentence.

The project aims to identify which model outperforms the others in terms of accuracy, precision, recall, and F1 score. It also investigates how the performance of these models is influenced by factors such as data pre-processing, hyperparameter tuning, and model architecture. The research findings will provide insights into the effectiveness of these models for sentiment analysis of historical journals and potentially help inform decisions about which model to use in similar applications.

## Introduction
Sentiment analysis is a crucial field of natural language processing (NLP) that involves analyzing text data to determine the subjective information, opinions, and emotions expressed within it. While sentiment analysis has been extensively applied to contemporary texts, such as social media posts and product reviews, its application to historical texts has been largely unexplored.

This research project focuses on sentiment analysis of historical documents, particularly journals from the 19th century. Analyzing historical texts can provide valuable insights into the cultural, social, and political attitudes of the time, as well as the evolution of language and the impact of historical events on people's emotions and opinions.

While deep learning models have shown promise for sentiment analysis, there is a lack of studies comparing their performance on historical documents. Most existing studies have focused on contemporary texts. Therefore, this project aims to fill this research gap and evaluate the performance of three state-of-the-art transfer learning models: BERT, DistilBERT, and RoBERTa.

## Dataset and Preprocessing
To perform sentiment analysis on historical documents, a dataset comprising historical documents from the 19th century was collected. The dataset was labeled into three classes (positive, negative, and neutral) using the VADER sentiment analysis tool, which utilizes a lexicon-based approach combined with grammatical rules and heuristics.

Data preprocessing was performed to clean and standardize the text data. This included converting the text to lowercase, removing URLs, non-alphabetic characters, English stopwords, excess spaces, underscores, digits, numerals, and punctuation. Duplicate instances and non-English material were also removed.

## Methodology
The research project employs three state-of-the-art models for sentiment analysis: BERT, DistilBERT, and RoBERTa.

- **BERT**: A pre-trained model that utilizes a masked language model and is fine-tuned using the dataset.
- **DistilBERT**: A smaller and faster version of BERT, created through knowledge distillation, which retains comparable performance.
- **RoBERTa**: An enhanced version of BERT, pre-trained using a larger corpus of text data with improved text representations.

The models were fine-tuned using the preprocessed dataset and evaluated based on accuracy, precision, recall, and F1-score. The performance of the models was analyzed, considering factors such as data pre-processing, hyperparameter tuning, and model architecture.

## Conclusion
The research project aims to compare the performance of BERT, DistilBERT, and RoBERTa models for sentiment analysis on historical journals. By analyzing the accuracy, precision, recall, and F1-score of these models, valuable insights can be gained regarding their effectiveness in sentiment analysis of historical texts. The research findings will contribute to improving sentiment analysis of old texts and historical documents and provide guidance on selecting appropriate models for similar applications.

## Additional

Sentiment Analysis on "Diary of a Young Girl" by Anne Frank

In addition to performing sentiment analysis on the historical documents from the 19th century, we also conducted sentiment analysis on "Diary of a Young Girl" by Anne Frank. This famous diary provides a firsthand account of Anne Frank's experiences during the Holocaust and offers a unique perspective on the emotional and psychological aspects of that time period.

To analyze the sentiment in Anne Frank's diary, we followed a similar approach as described earlier. The text data from the diary was preprocessed to ensure consistency and remove any extraneous material. We applied the same techniques of lowercase conversion, removal of URLs and non-alphabetic characters, elimination of English stopwords, and standardization of the data.


The sentiment analysis of "Diary of a Young Girl" provides valuable insights into Anne Frank's thoughts and feelings, highlighting the impact of historical events on individuals. By comparing the sentiments expressed in this diary with those in other historical documents, we can uncover commonalities and differences, ultimately enhancing our understanding of the past.

