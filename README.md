
It is posted by Yong (예비개발자).

Blog URL: https://blog.naver.com/qbxlvnf11

LinkedIn: https://www.linkedin.com/in/taeyong-kong-016bb2154

- Upload proposed Mixture-of-Experts (ME) model optimized to learn ensemble rule code
- Upload code as a Jupiter Notebook file (.ipynb) for immediate understanding

.

- Proposed Mixture-of-Experts (ME) model
  - For news categorization
  - Design for learning ensemble rule of various feature spaces
  - Each of the single classifier learns each of the distinct latent feature space of character embedding space and word embedding space, and gate network combines these single classifiers
  - To be optimized to learning ensemble rule, gate network of proposed ME performs linear combination directly to concatenated layers of each single classifiers and is not trained by using input data
  - Be trained with transfer learning using pretrained two single classifiers learning latent features at each of feature spaces to maximize ensemble effect.

Datasets
=============

- News Aggregater

https://www.kaggle.com/uciml/news-aggregator-dataset


References
=============

Editing...


Code correction
=============

None
