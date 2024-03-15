# Phishing URL Detection

## Introduction

Phishing attacks are a big problem online, causing financial losses and putting personal information at risk globally. With an average of $136 lost per phishing attack, this amounts to $44.2 million stolen by cyber criminals through phishing attacks in 2021.
One of the most expensive phishing attacks was through compromised emails with around 19,369 complaints having a loss of $1.8 billion.
 

Existing anti-phishing methods commonly rely on either human-verified URL blacklists or employ machine-learning algorithms based on specific features. While human-verified blacklists provide a low false positive rate, they struggle to adapt to new attacks, with studies showing limited effectiveness. Additionally, updating these blacklists demands significant human effort and may lag in responding to emerging phishing threats. Sheng et al. found that blacklists were updated at different speeds, and an estimated 47% - 83% of phish appeared on blacklists 12 hours after they were launched.
On the other hand, machine learning-based approaches face the challenge of feature quality, often relying solely on URL and HTML DOM, resulting in less discriminative features. This type of method tends to have a relatively higher FP. Concerns over liability for false positives have been a major barrier to deploying these technologies. 

# Target Problem

We are dealing with methods for detecting phishing websites by analyzing various features of benign and phishing URLs by machine learning techniques. A phishing URL is a web address designed to impersonate legitimate websites to fraudulently obtain sensitive information, characterized by: 
(1) Anomalies in domain properties and URL structure. 
(2) A login form requesting sensitive information such as bank details and password. 
(3) Content that closely imitates that of legitimate sites but with slight inconsistencies. 
