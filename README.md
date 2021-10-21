# Discourse-Phenomena-in-Document-level-Neural-Machine-Translation
Dataset for the paper "A Test Suite for Evaluating Discourse Phenomena in Document-level Neural Machine Translation". (In Proceedings of the Second International Workshop of Discourse Processing. 2020.)

## Abstract:
The need to evaluate the ability of context aware neural machine translation (NMT) models in dealing with specific discourse phenomena arises in document-level NMT. Here, we propose a test suite to evaluate three common discourse phenomena in English-Chinese translation: pronoun, discourse connective and ellipsis where discourse divergences lie across the two languages. The test suite contains 1,200 instances, 400 for each type of discourse phenomena.  
- Pronoun phenomena:
"you-你们", "you-你", "they/them/their-它们", "they/them/their-她们", "they/them/their-他们".  
Each pronoun contains 80 instances.
- Discourse connective phenomena:
"while-而", "while-当", "as-因为", "as-当", "since-因为", "since-既然", "though-虽然", "though-但是", "or-否则", "or-或者".  
Each contains 40 instances. 

We perform both automatic and human evaluation with three state-of-the-art context-aware NMT models on the proposed test suite. Results suggest that our test suite can be used as a challenging benchmark test bed for evaluating document-level NMT.

We release the dataset under the following license:
Attribution 4.0 International (CC BY 4.0) license. (License URL: https://creativecommons.org/licenses/by/4.0/)

## Reference:
If you use the dataset included here in your work, please cite the following paper:  
```bibtex
@inproceedings{cai2020test,  
  title={A Test Suite for Evaluating Discourse Phenomena in Document-level Neural Machine Translation},  
  author={Cai, Xinyi and Xiong, Deyi},  
  booktitle={Proceedings of the Second International Workshop of Discourse Processing},  
  pages={13--17},  
  year={2020}  
}
```
