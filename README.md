# Zoonosis Text Mining

This repository contains the code of my bachelor thesis. The link to the thesis will be added as soon as it is accepted.

Throghout my thesis I retrieved full texts of articles from the open access database PubMed Central and created a corpus for training purposes.
With this data a spaCy language model was updated, so it recognizes entities which are connected to the zoonotic virus rabies.

After the updating process was done, the new model was used on 10 articles to recognize these entities.

For each article an entry in the Open Research Knowledge Graph was created, which contains the recognized entities and metadata like the authors, DOI and the journal the article was published.

The trained model did not perform like it was supposed to do and in future work it will be updated to receive a high quality model.
