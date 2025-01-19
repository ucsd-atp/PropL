# PropL

Tutorial:

Put the code in `propositional_logic/random_gen/*.py`, and run using `python3 -m propositional_logic.random_gen.gen_dataset`.

Questions? File an Issue. 

Cite as:
```
@inproceedings{an-etal-2024-learn,
    title = "Learn from Failure: Fine-tuning {LLM}s with Trial-and-Error Data for Intuitionistic Propositional Logic Proving",
    author = "An, Chenyang  and
      Chen, Zhibo  and
      Ye, Qihao  and
      First, Emily  and
      Peng, Letian  and
      Zhang, Jiayun  and
      Wang, Zihan  and
      Lerner, Sorin  and
      Shang, Jingbo",
    editor = "Ku, Lun-Wei  and
      Martins, Andre  and
      Srikumar, Vivek",
    booktitle = "Proceedings of the 62nd Annual Meeting of the Association for Computational Linguistics (Volume 1: Long Papers)",
    month = aug,
    year = "2024",
    address = "Bangkok, Thailand",
    publisher = "Association for Computational Linguistics",
    url = "https://aclanthology.org/2024.acl-long.45/",
    doi = "10.18653/v1/2024.acl-long.45",
    pages = "776--790",
    abstract = "Recent advances in Automated Theorem Proving have shown the effectiveness of leveraging a (large) language model that generates tactics (i.e. proof steps) to search through proof states. The current model, while trained solely on successful proof paths, faces a discrepancy at the inference stage, as it must sample and try various tactics at each proof state until finding success, unlike its training which does not incorporate learning from failed attempts. Intuitively, a tactic that leads to a failed search path would indicate that similar tactics should receive less attention during the following trials. In this paper, we demonstrate the benefit of training models that additionally learn from failed search paths. Facing the lack of such trial-and-error data in existing open-source theorem-proving datasets, we curate a dataset on intuitionistic propositional logic theorems and formalize it in Lean, such that we can reliably check the correctness of proofs. We compare our model trained on relatively short trial-and-error information (TrialMaster) with models trained only on the correct paths and discover that the former solves more unseen theorems with lower trial searches."
}
```

Manuscript: [
[ACL Version](https://doi.org/10.18653/v1/2024.acl-long.45),
[ArXiv Version](https://arxiv.org/abs/2404.07382)
]

MIT License
