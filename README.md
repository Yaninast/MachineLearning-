# NLP-projects

The objective of the analysis is to leverage the well-formed clusters given the corpus of 61 documents on Trump administration, retrieve the clusters labels using a set of representative words for each class and classify the documents according to the obtained labels. TF-IDF vectorization technique is used to represent the words in k-means clustering, Random Forest and Multinomial Logistic Regression analysis.

News articles clustering 

The following steps have been performed: (1) perform TF-IDF vectorization; (2) determine the characteristics that define the context or extract the most representative words of the documents; (3) apply k-means algorithm; (4) apply labels and identify issues for clustering; (5) use Word2Vec matrix to determine words which are similar; (5) build corpus ontology (6) create and test various term combinations as Equivalence Classes (ECs); (7) refine the reference term vector and repeat clustering ; (8) validation/confirmation of clusters. 

News articles classification 

The following steps have been performed: (1) perform TF-IDF vectorization; (2) determine the characteristics that define the context or extract the most representative words of the documents; (3) apply k-means algorithm and retrieve labels; (4) classify documents according to the obtained labels using Random Forest and Multinomial Logistic Regression; (5) use Word2Vec matrix to determine words which are similar; (5) build corpus ontology; (6) create and test various term combinations as Equivalence Classes (ECs); (7) refine the Reference Term Vector and repeat classification ; (8) validation of the classification results. 

BERT 

Uncased BERT base model (uncased 12-layer, 768-hidden, 12-heads , 110M parameters), that has been pre-trained on the large corpus of the data, has been fine- tuned on the given corpus of the documents to be used to build document embeddings which would capture documents contextual meaning and hopefully improve k – means performance by recognizing more sophisticated connections between documents. The performance of the model has been evaluated and predictions have been made on the new set of documents. The next step of the analysis is to increase the training data to remedy overfitting (or apply data augmentation techniques) and use the bidirectional embeddings to improve clustering results. 
