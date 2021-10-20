# Spider-DK
Exploring Underexplored Limitations of Cross-Domain Text-to-SQL Generalization

Paper published in EMNLP 2021: [arXiv](https://arxiv.org/abs/2109.05157)

We slightly modified three databases to insert domain knowledge. To use the Spider-DK, you should merge the database folder of Spider and Spider-DK and then use the `tables.json` file here instead of the Spider one.

In `Spider-DK.json`, type 0 means there is no domain knowledge, while type 1 to 5 represent T1 to T5 in the paper. Besides, type 34 means this example contain both T3 and T4 knowledge type, and so on. 



### Cite

If you use the dataset in this repo, please cite the following paper:

```
@misc{gan2021exploring,
      title={Exploring Underexplored Limitations of Cross-Domain Text-to-SQL Generalization}, 
      author={Yujian Gan and Xinyun Chen and Matthew Purver},
      year={2021},
      eprint={2109.05157},
      archivePrefix={arXiv},
      primaryClass={cs.CL}
}

```