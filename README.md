# Tasensola_Aier_48474908
In this project, we explore the process of reproducing the results of the fastText text classifi-
cation model. After confirming the initial claims of the model’s performance from tutorials, we
extend the replication to a text dataset, demonstrating that the results are consistent
across various use cases and proving the model’s effectiveness in real-world applications.

PubMed 200k RCT is new dataset based on PubMed for sequential sentence classification. The
dataset consists of approximately 200,000 abstracts of randomized controlled trials, totaling 2.3
million sentences. Each sentence of each abstract is labeled with their role in the abstract using one
of the following classes: background, objective, method, result, or conclusion.In this project i have
used only 15,000 abstracts of this dataset. This structure aligns well with fastText’s capabilities in
text classification, enabling the model to learn and distinguish specific linguistic patterns associated
with each section.Also using this dataset supports reproducibility and open science goals by testing
fastText’s efficiency, accuracy, and applicability to domain-specific, multi-class classification tasks
in a real-world biomedical context.
