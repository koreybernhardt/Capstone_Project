# MS Data Science - Capstone Project
This project was an exploratory case study that took an in-depth look at using natural language processing (NLP) approaches to categorize unstructured data in the medical field, notably clinical notes. A look at the history of using NLP for clinical notes was completed, in addition to creating models to apply NLP to a dataset for further analysis. The primary question to be answered was whether high mortality conditions be extrapolated from clinical notes. Additional research questions included whether unsupervised learning models could be used and whether the approach could be scaled to other diseases. Detecting high-mortality diseases from clinical notes can significantly benefit primary care providers, medical specialists, and ultimately patients as people rely more and more on multiple care providers to support their medical needs. Four models were used to compare results, including three supervised models and one unsupervised model. Multiclass and binary classification approaches were analyzed. While a binary logistic regression performed the best, with 91% balanced accuracy and 92% weighted recall, an unsupervised neural networks model also achieved good results, with 89% balanced accuracy and 90% weighted recall. These results indicate that high-mortality conditions can be extrapolated from clinical notes with a high degree of accuracy using unsupervised learning. The results can be scaled to additional diseases with further research.      


## Files

* **A Case Study of Natural Language Processing_DS785_KBernhardt.docx**: The final research paper that includes a lit review, methodology, and results. 
* **DS785_Final_code.ipynb**: The jupyter notebook containing all code supporting the research paper. It contains results from running the notebook, which can be run using run all cells 
* **mtsamples.csv**: Contains clinical notes data and is the primary data source for the research paper. It was sourced from Kaggle and listed as a reference in the paper.
* **disease_aggregation.csv**: Mapping of specific diseases to one of five high mortality diseases. The compilation of this file is outlined in the paper in the Disease Labelling seciton.
* **disease_counts.csv**: All diseases assigned to transcriptions with count of transcriptions.


## Sample Visual Results 
![image](https://github.com/user-attachments/assets/2327804e-b57a-4225-9990-124c08d95355)

![image](https://github.com/user-attachments/assets/c0552e70-67c4-4cd1-a565-73cb10e22ade)

![image](https://github.com/user-attachments/assets/9baecc5c-9890-4e19-9e84-2b32256e3ff4)

![image](https://github.com/user-attachments/assets/6578822a-71a3-4ffa-8cbc-c75e11fbd950)
