# How fast can a model change?
## Measuring the Change in a Model’s Understanding of Words Under Few-shot Learning

Final Project for Machine Learning Safety Scholars Program (MLSS) 2022 by the Center for AI Safety. This project is made by Ayrton San Joaquin and Ardy Haroen, with advice from Hannah Brown.

Modern language models are susceptible to being trained on biased or incorrect information because of the nature of building training datasets for them. 
This leads to models that can generate biased or incorrect information. While finetuning or prompting with correct information may alleviate this, we ask how effective this approach is as we vary model size. We focus on prompting as the effectiveness of finetuning is dependent on much more hyperparameters than prompting.
We ask the question:
<b> How "fast" can the model discriminate the new and correct information from the old, harmful information? </b>

Above we provide a notebook:
- `dataset.ipynb`: This is the notebook to generate the datasets.

The Jupyter notebook is self-explanatory and outlines each section of the project. We recommend you run it on Google Colab.
