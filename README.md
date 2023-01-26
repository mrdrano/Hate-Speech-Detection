# Hate-Speech-Detection
Using nltk, nlp technique to detect whether the tweets are actually hate speech related posts
Data: tweet text data
• Tweets have 3 classes
 0: Hateful
 1: Offensive
 2: Clean
• Classification Settings
 Training Data: 60%, ~16000 tweets
 Public Test Data: 20%, ~5000 tweets
 Private Test Data: 20%, ~5000 tweets
• Evaluation Metrics
 HateF: F1 Score of “Hateful” class
 AlllF: F1 Score of “all three classes”
 Final = 0.6*HateF + 0.4*AllF
