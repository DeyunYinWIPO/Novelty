# Scientific Novelty

This repository is prepared for computing the novelty indicator of scientific publications. 


For further details, please refer to the following paper:  

- **Title**: [Measuring novelty in science with word embedding](https://journals.plos.org/plosone/article?id=10.1371/journal.pone.0254034)
- **Authors**: Sotaro Shibayama,Deyun Yin, Kuniko Matsumoto
- **Abstracts**: Novelty is a core value in science, and a reliable measurement of novelty is crucial. This study proposes a new approach of measuring the novelty of scientific articles based on both citation data and text data. The proposed approach considers an article to be novel if it cites a combination of semantically distant references. To this end, we first assign a word embedding–a vector representation of each vocabulary–to each cited reference on the basis of text information included in the reference. With these vectors, a distance between every pair of references is computed. Finally, the novelty of a focal document is evaluated by summarizing the distances between all references. The approach draws on limited text information (the titles of references) and publicly shared library for word embeddings, which minimizes the requirement of data access and computational cost. We share the code, with which one can compute the novelty score of a document of interest only by having the focal document’s reference list. We validate the proposed measure through three exercises. First, we confirm that word embeddings can be used to quantify semantic distances between documents by comparing with an established bibliometric distance measure. Second, we confirm the criterion-related validity of the proposed novelty measure with self-reported novelty scores collected from a questionnaire survey. Finally, as novelty is known to be correlated with future citation impact, we confirm that the proposed measure can predict future citation.


**Citation**: Shibayama, S., Yin, D., & Matsumoto, K. (2021). Measuring novelty in science with word embedding. PloS One, 16(7), e0254034. https://doi.org/10.1371/journal.pone.0254034



