# Sentiment Analysis of Amazon Reviews

## Overview
This project builds a sentiment analysis model on Amazon electronic product reviews. It covers data exploration, aspect-based analysis for warranty satisfaction, and a model to predict ratings from 1 to 5.

## Dataset
Key columns include `overall` (rating), `reviewText` (main input), and `vote` (helpfulness).

## Exploratory Analysis
- Plotted `overall` distribution and proposed balancing techniques.
- Generated word clouds for positive, neutral, and negative reviews.
- Identified top 10 reviewers by total votes.
- Analyzed `reviewText` length distribution.
- Found top products by 5-star reviews and top brands by average rating.

## Warranty Sentiment Analysis
Used embeddings to find synonyms for "warranty" and calculated average ratings from relevant reviews.

## Sentiment Model
Trained a text-based model to predict ratings (1–5). Applied preprocessing techniques and model fine-tuning.

## Submission Format
Output predictions in `q2_submission.csv` with a single `predicted` column. Evaluation is based on micro-averaged F1-score.

