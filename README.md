# Personalized-Cancer-Detection-Case-study

**All the relevant CODE & Final conclusions are in ipynb notebook.**<br>

**Problem Statement:-**<br>
Classify the given genetic variations/mutations into one of the nine classes based on evidence from text-based clinical literature.<br>

**Constraints:-**<br>
* Interpretability is important.
* Errors can be very costly.
* No low-latency requirement.
* Probability of a data-point belonging to each class is needed

**Data:-**<br>
* Source https://www.kaggle.com/c/msk-redefining-cancer-treatment/ <br>
* There are two data files: First contains the information about the genetic mutations and the other contains the clinical evidence (text) that human experts/pathologists use to classify the genetic mutations.<br>
* training_variants (ID , Gene, Variations, Class)<br>
* training_text (ID, Text)<br>

**Metric:-** Multi class log loss

