# learning-openings

**Implementation of the analyses described in Kuperwajs, van Opheusden, Russek, and Griffiths (2024).**

## Approach

This repository provides analysis code for studying learning in chess openings using Jupyter notebooks. The filtered data necessary to run the code is also provided. The raw data is available from the Lichess open database at https://database.lichess.org, the source code for preprocessing the raw data is available from Scoutfish at https://github.com/mcostalba/scoutfish, and the model fitting code is available at https://github.com/ndawlab/em.

## File description

- `preprocessing_learning.ipynb`: generates the filtered data for the learning analysis
- `modeling_preprocessing_learning.ipynb`: generates the filtered data for the model fitting
- `learning.ipynb`: analysis of learning across multiple openings
- `modeling_learning.ipynb`: model fitting across multiple openings
- `intermediate_learning.ipynb`: control analysis (intermediate positions) across multiple openings
- `length_learning.ipynb`: control analysis (game length) across multiple openings
- `replication_learning.ipynb`: replication of the main learning analysis
- `Data`: filtered data split by opening in subfolders for the learning analysis
- `Modeling`: filtered data split by opening in subfolders for the model fitting
