# CPA-LGC
CPA-LGC Recbole (https://recbole.io/index.html) implementation for the paper   
Jin-Duk Park, Siqing Li, Won-Yong Shin, and Xin Cao,
"Criteria Tell You More than Ratings: Criteria Preference-Aware Light Graph Convolution for Effective Multi-Criteria Recommendation",   
Proceedings of the 29th ACM SIGKDD International Conference on Knowledge Discovery & Data Mining, **KDD '23**



# Dependancy
- numpy
- pands
- torch
- recbole (install via: conda install -c aibox recbole)
- networkx


# Dataset Descriptions
Original interaction datasets and MC expansion graph datasets    
(Dataset.tr.inter: training dataset (MCEG),  Dataset.ts (val).inter: test (validation) dataset, Dataset.inter: original dataset)   
-TA5: TripAdvisor, YM5: Yahoo!Moive, RB5: RateBeer, YP5: Yelp   

# Custom dataset
For custom dataset of any manipulation of dataset, 
please refer to the preprocessing codes in Processing_example_YM.ipynb for Recbole implementation of CPA-LGC

# Contact
For more information, contact via: jindeok6@yonsei.ac.kr
