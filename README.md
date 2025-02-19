# README - CORETAX Sentiment Analysis

## **Background**

CORETAX, launched by Indonesia’s Directorate General of Taxes (DGT) in January, aims to modernize tax administration. However, since its launch, users have reported issues such as system errors, slow processing, and accessibility problems. Public sentiment, especially on X (formerly Twitter), provides valuable insights into its reception.

## **Problem Statement**

What is the public sentiment towards CORETAX? Is it positive or negative?

## **Stakeholder**

Directorate of Taxation Information and Technology (TIP), Indonesian Tax Ministry (DJP) – responsible for CORETAX implementation and public feedback.

## **Approach**

We conducted a sentiment analysis on tweets mentioning CORETAX, categorizing them as positive or negative using NLP techniques like tokenization and sentiment classification.

## **Dataset**

- Column: Name	Description
- id_str:	Unique identifier for each tweet
- username:	Twitter handle of the user
- created_at:	Tweet date and time
- full_text:	Content of the tweet
- retweet_count:	Number of shares
- favorite_count:	Number of likes

## **Findings**

Public sentiment is mostly negative due to technical issues.
Key negative words: “error,” “gagal” (fail), “tidak bisa” (cannot).
Positive sentiment is minimal, mainly praising smooth processes.
IndoBERT achieved 86% accuracy, but positive sentiment recall was low (0.50), showing bias toward negative sentiment.

## **Conclusion**

This analysis highlights user concerns and provides insights for improving CORETAX. Addressing system errors and enhancing user experience are crucial for better adoption.
