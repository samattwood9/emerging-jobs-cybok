# README

*This repository contains the analyses reported in: **Exploring the UK Cyber Skills Gap through a mapping of active
job listings to the Cyber Security Body of Knowledge (CyBOK)**.* Available: https://dl.acm.org/doi/10.1145/3593434.3593459.

## Datasets

The two data-sets are available in the data folder:

- *reference.json*. A `json` version of the CyBOK Mapping Reference v1.3.
- *jobs_labelled.csv*. File containing job descriptions with author annotations. 

## Instructions for replication

The original analysis was achieved using Python 3.10.7. The required packages can be installed using:

```py
pip install -r requirements.txt
```

The results can then be replicated by running the `eda.ipynb` and `mapping.ipynb` notebooks.

## Citation

Please reference the following when using this work and/or the data-sets.

```
@inproceedings{10.1145/3593434.3593459,
author = {Attwood, Sam and Williams, Ashley},
title = {Exploring the UK Cyber Skills Gap through a Mapping of Active Job Listings to the Cyber Security Body of Knowledge (CyBOK)},
year = {2023},
isbn = {9798400700446},
publisher = {Association for Computing Machinery},
address = {New York, NY, USA},
url = {https://doi.org/10.1145/3593434.3593459},
doi = {10.1145/3593434.3593459},
abstract = {Background: The UK cyber skills gap/shortage amplifies the broader impact of cyber-attacks, which inflict harms such as privacy and economic loss on wider society. The demand is greatest (and growing fastest) in cyber-enabled disciplines, such as software engineering. Objectives: In this paper, we create a term frequency-inverse document frequency representation of the Cyber Security Body of Knowledge (CyBOK). We then evaluate the potential of this representation by using it to automatically map job descriptions to the different areas of the CyBOK. Method: We generate two representations of the CyBOK. The representations are mapped to a corpus of 454 job descriptions using TF-IDF. Comparing the similarity scores across these mappings allows us to identify relevant knowledge areas/groups. Results: The results are preliminary, but suggest that the approach warrants further investigation. Certain job descriptions are mapped to certain knowledge areas/groups in a way that makes intuitive sense to the authors. However, there is a degree homogeneity to the scores returned for certain knowledge areas/groups. There are several threats to validity, most notably the low number of job descriptions that have been studied. Conclusions: Our work shows that it is possible to automatically map job descriptions to the CyBOK in a meaningful way. Further research is required to address threats and to explore alternative mapping approaches. The authors intend to undertake this research culminating with a Grey Literature Informed Model of Practice in Secure Software Engineering.},
booktitle = {Proceedings of the 27th International Conference on Evaluation and Assessment in Software Engineering},
pages = {273–278},
numpages = {6},
keywords = {Cyber Security, Higher Education, CyBOK, Grey Literature, Secure Software Development},
location = {Oulu, Finland},
series = {EASE '23}
}
```


