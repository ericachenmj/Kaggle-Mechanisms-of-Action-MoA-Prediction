# Kaggle-Mechanisms-of-Action-MoA-Prediction

Mechanisms of Action (MoA) refers to the specific biochemical interaction between the drug
and its targets. Drug targets can be the molecules in either the human body or pathogens. In
the past, drugs were discovered via serendipitous approaches and were adopted into clinical
use for years before their mechanisms were truly understood. Today, the process of drug
discovery can be greatly benefited from a more targeted model-based approach, which is the
MoA prediction algorithm.

This project was chosen from the Kaggle mechanisms of action prediction competition.
A dataset that combines gene expression and cell viability data was provided. Samples are
drugs profiled at different time periods and doses. The goal is to predict the probabilities of
multiple targets of the MoA responses for each sample by building machine learning models
using PySpark. The features of data include gene expression (g-), cell viability (c-), cp_type,
cp_time, and cp_dose, and there are 206 labels to predict. Since a drug can have multiple
MoA annotations, this is a multi-label classification problem.
