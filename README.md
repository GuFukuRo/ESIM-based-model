# A data augmentation method based on [RoBERTa](https://arxiv.org/abs/1907.11692) and adjusted for NLI datasets
_The project is still under development._  
NLI (Natural Language Inference) datasets have different artifacts and biases that help models get right answers based on wrong criteria. Here is an attempt to make a data augmentation method using some of these specifics and at the same time trying to reduce existing defects.  
### Repo includes:
* data augmentation code, 
* pytorch implementation of ESIM-based model from [When data permutations are pathological: the case of neural natural language inference](https://www.aclweb.org/anthology/D18-1534/),
* cross-dataset testing for ESIM-based model,
* fine-tuning [BERT](https://arxiv.org/abs/1810.04805) and [DistilBERT](https://arxiv.org/abs/1910.01108) with pretrained models from [PyTorch-Transformers](https://github.com/huggingface/transformers).
