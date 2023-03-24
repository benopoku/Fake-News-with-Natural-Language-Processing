# Fake-News-with-Natural-Language-Processing
Detecting Fake and True News with Natural Language Processing
Download the dataset here: https://www.kaggle.com/clmentbisaillon/fake-and-real-news-dataset.

Also, the ink to the model on Hugging Face Hub: https://huggingface.co/bopoku/Fake-news-detection/commit/a3cb9601853d504f4a507a006a71fbc9d28f2d2e link text
Include are some explaination of what to improve the model's performance on these news articles in the future:
On all datasets, random forest outperformed the others in terms of accuracy. However, the accuracy score alone is not a good measure of a model's performance; thus, we also evaluate the performance of learning models using recall, precision, and the F1-score. I deployed Linear SVC, to improve this model, one has to chose a soft margin rather than a hard margin, which means intentionally let some data points enter the margin so that the classifier does not overfit on the training sample. And its performance also performed so well.
