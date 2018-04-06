---
title: "Spam Email Classifier"
excerpt: "Classifying emails as spam or not-spam using decision trees."
header:
  teaser: /assets/images/projects/spam-th.jpg
sidebar:
  - title: "<i class=\"fab fa-github\" aria-hidden=\"true\"></i> <a href=\"https://github.com/yashketkar/B551-Elements-Of-Artificial-Intelligence/tree/master/pssapre-sdarekar-yketkar-a4\">GitHub Repo</a>"
    image: /assets/images/projects/spam-sb.jpg
    image_alt: "thumbnail"
  - title: "Responsibilities"
    text: "Creating an email classifier using decision trees."
---
Classified spam and non-spam emails using Naive Bayes and Decision Trees with 98% accuracy. Implemented decision tree learning algorithm in Python without using any external libraries.

Here I had the problem of learning a decision tree from a training dataset of emails. The words found in the document were considered as the features for the decision tree. For each word the "Average Disorder" or the "Entropy" was calculated, this could be done using two ways either by checking the presence of the word (binary) or the count of the word (continuous). Once the feature or the word which splits the dataset giving the least entropy was found. The dataset was split on the basis of presence of the word. A recursive call on the split up datasets to further split them based on the word with the next least entropy was done. I used the ID3 algorithm for the binary feature type and used binning for the continuous type where I calculated the frequency/total ratio of the counts of the words in a document.

The resulting decision tree looked somewhat as follows, once this was found a simple traversal(or walk) on the tree could very quickly classify any given email as spam or non spam. The walk or traversal in this case would mean checking if the word was present in the given test email.

The top 4 levels of Decision Tree learnt using binary feature were as follows:

                  x-spam-status:

          False                           in-reply-to:

                          False                   zzzz@localhost.netnoteinc.com

                                          False                           reserved.

In this representation the root node is "x-spam-status:"

"x-spam-status:" has left node as "False" and right node as "in-reply-to:"

"in-reply-to:" has left node as "False" and right node as "zzzz@localhost.netnoteinc.com"

"zzzz@localhost.netnoteinc.com" has left node as "False" and right node as "reserved."

More nodes further down the tree are not shown here.

Percentage Accuracy: 98.6296006265 %

| Confusion Matrix | Predicted Spam| Predicted Not-Spam  |
| ---------------- |:-------------:| -------------------:|
| Actual Spam      | 1173          |   12                |
| Actual Non Spam  | 23            | 1346                |
