# Inverse-Scaling-Prize

**Contributors:** Rauno Arike, David McSharry

Participating in the [Inverse Scaling Prize](https://github.com/inverse-scaling/prize) competition to find anomalies in the scaling of the capabilities of language models as they get bigger as our final project of the [ML Safety Scholars program](https://course.mlsafety.org/).

To replicate our results, download either the `logic_dataset_full.csv` file and evaluate it in the Inverse Scaling Prize's [Colab notebook for GPT-3 models](https://colab.research.google.com/drive/1SGmUh0NbqSrRkWRUcmjg8BS5eU5qvJ0Y#scrollTo=SpIfwfNjfMm8) or [Colab notebook for OPT models](https://colab.research.google.com/drive/1NBDIdsY5d1NhgZIhelm9FbWARzySlc2H#scrollTo=SpIfwfNjfMm8) using the `absolute_logodds` metric, or download the `representation_divergence_full.csv` file and evaluate it using the `classification` or `classification_acc` metric. Our results and final report of the project can be viewed in the Results folder.

The repository also includes two Jupyter Notebooks `script_for_logic_prompts.ipynb` and `script_for_repr_prompts.ipynb`. We used these notebooks to augment our datasets and then convert them into the format required by the Inverse Scaling Prize competition for submission. The datasets included in the datasets folder are already in the correct format.
