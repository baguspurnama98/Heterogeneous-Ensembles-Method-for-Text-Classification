# Heterogeneous-Ensemble-Method-for-Text-Classification

**Background:** Question-answer (QA) is a popular method to seek health-related information and biomedical data. Such questions can refer to more than one medical entity (multi-label) so determining the correct tags is not easy. The question classification (QC) mechanism in a QA system can narrow down the answers we are seeking. Objective: This study develops a multi-label classification using the heterogeneous ensembles method to improve accuracy in biomedical data with long text dimensions.

**Methods:** We used the ensemble method with heterogeneous deep learning and machine learning for multi-label extended text classification. There are 15 various single models consisting of three deep learning (CNN, LSTM, and BERT) and four machine learning algorithms (SVM, kNN, Decision Tree, and Naïve Bayes) with various text representations (TF-IDF, Word2Vec, and FastText). We used the bagging approach with a hard voting mechanism for the decision-making. Results: The result shows that deep learning is more powerful than machine learning as a single multi-label biomedical data classification method. Moreover, we found that top-three was the best number of base learners by combining the ensembles method. Heterogeneous-based ensembles with three learners resulted in an F1-score of 82.3%, which is better than the best single model by CNN with an F1-score of 80%.

**Conclusion:** A multi-label classification of biomedical QA using ensemble models is better than single models. The result shows that heterogeneous ensembles are more potent than homogeneous ensembles on biomedical QA data with long text dimensions.


# Citation
If the code is useful in your research, please cite the following paper:

Abdillah, A. F., Putra, C. B. P., Apriantoni, A., Juanita, S., & Purwitasari, D. (2022). Ensemble-based Methods for Multi-label Classification on Biomedical Question-Answer Data. Journal of Information Systems Engineering and Business Intelligence, 8(1), 42-50.

[Ensemble-based Methods for Multi-label Classification on Biomedical Question-Answer Data](https://doi.org/10.21609/jiki.v14i1.959)

