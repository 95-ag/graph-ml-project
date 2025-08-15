# Network Representation Learning

This project reproduces and analyzes five popular Unsupervised Network Representation Learning (UNRL) methods for graphs, focusing on node classification and link prediction tasks.

## About

We implemented DeepWalk, Node2Vec, NetMF, LINE-1, and GraphSAGE to benchmark their performance on ten real-world network datasets. Our main focus was to reproduce results from Khosla et al. (2019) and to analyze outcomes when running these methods under resource constraints and on additional datasets.

## Experimental Setup

- Evaluated models on social, citation, and collaboration networks (including BlogCatalog, Flickr, YouTube, Twitter, Cora, PubMed, DBLP-Ci, and Facebook Page-Page).
- Downstream tasks included node classification (using logistic regression and F1 scores) and link prediction (using ROC-AUC).
- Key implementation modifications included tuning hyperparameters for limited compute resources and extending experiments to the Facebook Page-Page dataset.
- All code was written from scratch using NetworkX, Gensim, scikit-learn, TensorFlow, and StellarGraph.

## Resources

- Full project report: [Adv_ML_Project.pdf](./Adv_ML_Project.pdf)

## References

- Khosla, M., Setty, V., & Anand, A. (2019). "A comparative study for unsupervised network representation learning." IEEE Trans. on Knowledge and Data Engineering.
- Perozzi, B., Al-Rfou, R., & Skiena, S. (2014). "Deepwalk: Online learning of social representations." KDD.
- Řehůřek, R., & Sojka, P. (2010). "Software Framework for Topic Modelling with Large Corpora." LREC.
- Grover, A., & Leskovec, J. (2016). "node2vec: Scalable feature learning for networks." KDD.
- Qiu, J., et al. (2018). "Network embedding as matrix factorization." WSDM.
- Tang, J., et al. (2015). "LINE." WWW.
- Hamilton, W. L., Ying, R., & Leskovec, J. (2017). "Inductive representation learning on large graphs." NeurIPS.
- Rozemberczki, B., Allen, C., & Sarkar, R. (2019). "Multi-scale Attributed Node Embedding." arXiv:1909.13021.
- Hagberg, A., Swart, P., & S Chult, D. (2008). "Exploring network structure, dynamics, and function using NetworkX." Los Alamos National Lab.
- Data61 CSIRO. StellarGraph Library. [https://github.com/stellargraph/stellargraph](https://github.com/stellargraph/stellargraph)

## Acknowledgments

- Developed as part of **Advanced Machine Learning** at KTH Royal Institute of Technology.
- Contributors: Adhithyan Kalaivanan, Aishwarya Ganesan, Daniel Richards, Vishal Nedungadi
- Forked from original repo: https://github.com/dannyrichy/graph-ml-project.git
