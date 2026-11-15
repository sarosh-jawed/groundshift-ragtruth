# GroundShift

**Course:** IS 826A Application Programming, Emporia State University  
**Team:** Sarosh Jawed and Farhad Akter  
**Status:** Work in progress

## Research question

Can lightweight machine learning models detect annotated hallucinations in AI-generated responses, and how well do they perform when evaluated on a different task type?

## Dataset

This project uses the publicly available [RAGTruth dataset](https://github.com/ParticleMedia/RAGTruth), which contains human-annotated AI responses across question answering, summarization, and data-to-text tasks.

## Planned approach

We will prepare numerical features from the response text and its supporting evidence, then compare two classification models:

- K-Nearest Neighbors
- Decision Tree

Our main experiment will compare standard held-out performance with performance on a withheld task type.

## Tools

Python, Google Colab, pandas, scikit-learn, and matplotlib.

## Evaluation

We plan to report precision, recall, F1, accuracy, confusion matrices, and the size and class balance of each evaluation set.

## Project files

The Colab notebook, experiment results, and supporting documentation will be added as they are completed and verified.

## Research limitations

The models will predict labels defined from the RAGTruth annotations. Their predictions should not be treated as independent verification of factual correctness.

## Dataset credit

RAGTruth: https://github.com/ParticleMedia/RAGTruth

We will cite the original dataset paper in the final report.
