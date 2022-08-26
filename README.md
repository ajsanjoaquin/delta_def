# How fast can a model change?
## Measuring the Change in a Model’s Understanding of Words Under Few-shot Learning

Final Project for Machine Learning Safety Scholars Program (MLSS) 2022 by the Center for AI Safety. This project is made by Ayrton San Joaquin and Ardy Haroen, with advice from Hannah Brown.

Modern language models are susceptible to being trained on biased or incorrect information because of the nature of building training datasets for them. 
This leads to models that can generate biased or incorrect information. While finetuning on correct information may alleviate this, we ask how effective this approach is as we vary model size.
<b> How fast can the model learn the new and correct information\emph{while} forgetting the old, harmful information? </b>

Above we provide two notebooks:
- `Model_adapt_def.ipynb`: This is the main notebook where we experiment with the model's capability to forget meanings
- `gpt-embeddings.ipynb`: This is our sandbox notebook which contains our experiments to get GPT-2 embeddings

The Jupyter notebook is self-explanatory and outlines each section of the project. We recommend you run it on Google Colab, but if you would like to run it on your own computer, use the provided `requirements.txt`.
