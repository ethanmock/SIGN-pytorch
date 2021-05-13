This is our implementation for the paper:

Su, Y., Zhang, R., Erfani, S., & Xu, Z. (2021). *Detecting Beneficial Feature Interactions for Recommender Systems*. In Proceedings of the 34th AAAI Conference on Artificial Intelligence (AAAI). [Link](https://arxiv.org/abs/2008.00404)


### Requirement 

Python version >= 3.7

Install appropriate packages listed in requirements.txt:
```
pip install -r requirement.txt
```

### Run our code:
```
cd code
python SIGN_main.py --dataset=frappe --predict_edge=1 --lr=0.05
```

For more argument options, please refer to ```SIGN_main.py```

