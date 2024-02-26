# Bank-Customer-Complaint-Analysis-for-Efficient-Dispute-Resolution

## Overview:

The Bank Customer Complaint Analysis project aims to revolutionize the dispute resolution process by leveraging Natural Language Processing (NLP) techniques to automatically categorize and route customer complaints to the appropriate teams. This project was undertaken as part of an internship, with the goal of improving efficiency and accuracy in handling complaints within the financial institution.

## Key Features:

# Data Collection and Preprocessing:

Gathered historical complaint data from the Consumer Financial Protection Bureau (CFPB) website.
Preprocessed textual narratives by removing noise, such as special characters and stopwords, and tokenized the text for further analysis.

# Classification Model Development:

Developed an NLP classification model using Bag of Words (BOW) with n-grams.
Explored and fine-tuned hyperparameters using Randomized Search, achieving an accuracy improvement from 79% to 86%.

# Model Training and Evaluation:

Trained the classification model on a labeled dataset and evaluated its performance using metrics such as accuracy, precision, recall, and F1-score.


# Routing and Resolution:

Implemented a routing mechanism to automatically route classified complaints to the appropriate teams within the financial institution for resolution.


# Feedback Mechanism:

Established a feedback mechanism to collect input from teams handling customer complaints for iterative model and process improvement.

# Results:

Trained NLP model achieving an accuracy of 86% after hyperparameter tuning.
Implemented an automated routing mechanism for efficient resolution of customer complaints.
Conducted error analysis, reducing misclassified samples from 1034 to 712 after hyperparameter tuning.

# Recommendations:

The project recommends using Bag of Words (BOW) with n-grams as the optimal vectorization technique.
The trained model, along with the implemented routing mechanism, significantly improves dispute resolution efficiency and customer satisfaction.

# Conclusion:

The Bank Customer Complaint Analysis project showcases the power of NLP in automating and enhancing the dispute resolution process. By leveraging advanced techniques and technologies, we've created a solution that not only streamlines operations but also contributes to overall customer satisfaction.
