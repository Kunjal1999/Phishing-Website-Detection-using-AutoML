# Phishing-Website-Detection-using-AutoML

This is a small project that detects phishing websites using machine learning and automated machine learning. 

# Steps:
1. We have initially downloaded a list of phishing websites from PhishTank.com and benign(safe) websites from OpenDMZ
2. Using python REGEX, whois library and some open source scripts we have extracted features for each URL and stored everything in a CSV file.
3. We perform data preprocessing (one hot encoding and normalization)
4. We build seven traditional machine learning models and later employ the famous TPOT library for AutoML
5. Using AutoML we have achieved around 98% accuracy.
