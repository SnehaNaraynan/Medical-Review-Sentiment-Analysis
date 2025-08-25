# Medical Review Classification Analysis

## Business Problem
Healthcare platforms need to automatically categorize patient reviews to identify specific medical conditions and understand sentiment patterns. Manual classification is time-intensive and inconsistent, making it difficult to extract actionable insights from large volumes of patient feedback.

## Approach
Built a multi-class text classification system to predict medical conditions from patient reviews. Implemented natural language processing techniques including text preprocessing, TF-IDF vectorization, and n-gram analysis. Compared multiple machine learning algorithms to optimize classification accuracy.

## Technical Implementation
- Data preprocessing: HTML removal, lemmatization, stopword filtering
- Feature engineering: TF-IDF vectorization with unigram, bigram, and trigram analysis
- Model comparison: Naive Bayes and Passive Aggressive classifiers
- Evaluation: Confusion matrices and accuracy metrics across model variations

## Key Findings
- Trigram features achieved highest classification accuracy across all medical conditions
- Passive Aggressive classifier outperformed Naive Bayes for this dataset
- Sentiment analysis revealed negative reviews exceeded positive by 3.31%
- Word cloud analysis identified condition-specific terminology patterns

## Business Impact
The classification system enables automated categorization of patient feedback, reducing manual review time and providing consistent condition identification. Sentiment insights can guide product teams in addressing patient concerns and improving healthcare delivery outcomes.
