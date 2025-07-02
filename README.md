# Obesity Categorization via Clustering and Dimensionality Reduction

Obesity is a growing public health issue that affects millions of Americans today. Despite its widespread impact, there remains substantial debate regarding its root causes. For instance, two reputable articles that helped inspire this analysis take opposing views:

- One article argues that weight gain is primarily driven by the **calories in vs. calories out** equation.
- The other contends that not all calories are equal, and that calorie count alone doesn't tell the full story.

This project explores whether various lifestyle traits and behavioral indicators can naturally group individuals into obesity categories using unsupervised learning techniques.

---

## Objective

Using a dataset containing behavioral and physiological features potentially related to obesity, we aim to answer:

- Do certain lifestyle or dietary patterns naturally cluster people into obesity categories?
- Can traits such as physical activity, eating habits, or health history predict distinctions between obesity levels (e.g., Obesity Type I vs. Type III)?
- Are there identifiable subgroups within the population that could inform targeted interventions?

---

## Methods

We use a variety of unsupervised machine learning techniques to analyze the data:

- **Principal Component Analysis (PCA)** – for dimensionality reduction and visualization
- **K-Means Clustering** – to identify natural groupings within the dataset
- **Hierarchical Clustering** – to explore multi-level relationships among individuals

These tools help us discover patterns in the data **without using obesity status as a label** during training.

---

## Key Questions

- Can people be grouped into obesity categories based on lifestyle and demographic traits alone?
- Are the resulting clusters meaningful, or do individuals fall into categories randomly?
- Is there a distinguishable difference between obesity subtypes, such as Obesity Type I vs. Obesity Type III?

