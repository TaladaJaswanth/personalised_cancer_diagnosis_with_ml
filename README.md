# Personalized-Cancer-Diagnosis-Analysis
Objective: Sort cancer into classes using the Gene, the Variation, and the Text. The goal was to take a genetic variation/mutation and figure out which class it belongs to, using evidence from clinical research text.
Several ML models were tried, and their results were compared.
Business constraints:

Mistakes can be expensive
The model needs to be easy to understand
Speed isn't a concern

Data overview:
training_variants (ID, Gene, Variation, Class)
training_text (ID, Text)

Performance metrics used:
Multi-class log-loss
Confusion matrix

The results for each model can be seen in its matching file.

This project was done as part of the Scaler projects.
