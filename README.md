# Inverse-Scaling-Prize

**Contributors:** Rauno Arike, David McSharry

Participating in the [Inverse Scaling Prize](https://github.com/inverse-scaling/prize) competition to find anomalies in the scaling of the capabilities of language models as they get bigger as our final project of the [ML Safety Scholars program](https://course.mlsafety.org/).

To replicate our results, simply download either the `logic_dataset.csv` file and evaluate it in the Inverse Scaling Prize's [Colab notebook for GPT-3](https://colab.research.google.com/drive/1SGmUh0NbqSrRkWRUcmjg8BS5eU5qvJ0Y#scrollTo=SpIfwfNjfMm8) models or [Colab notebook for OPT models](https://colab.research.google.com/drive/1NBDIdsY5d1NhgZIhelm9FbWARzySlc2H#scrollTo=SpIfwfNjfMm8) using the `absolute_logodds` metric, or download the `representation_divergence.csv` file and evaluate it using the `classification` or `classification_acc` metric. Our latest results can be viewed in the results folder.

The repository also includes our final report describing the results and the Jupyter Notebook `script_for_prompts.ipynb` that we used to convert the examples that we created for our task into a suitable format for the Inverse Scaling Prize's Colab notebooks. The datasets included in the datasets folder are already in the correct format.
