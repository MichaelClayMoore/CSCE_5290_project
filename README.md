# CSCE_5290_project

---

## Goal:

The Goal of this project was to generate fake reviews, and then create a model to distinguish between fake and real reviews. We did this project with the help of aitextgen and huggingface

---
# Sections:

1) Data Ingestion
2) Review Generate
3) Review Classification

--- 

## Data Ingestion:

this section is found in the explore.ipynb. In that notebook, we read in the dataset and output the model inputs for the next section.

## Review Generation:

This section (Generate_Reviews.ipynb) takes the input data generated in the last step and uses it to fine-tune a GPT-2 model. This model is then made to generate 1000 reviews and save them to a csv for the next section.

## Review Classification:

The final section of our project (TextClassification.ipynb) takes the fake reviews as well as the real reviews from the previous steps and uses BERT to classify them.