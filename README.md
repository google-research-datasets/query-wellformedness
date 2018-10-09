# Query-wellformedness Dataset

25,100 queries from the Paralex corpus (Fader et al., 2013) annotated with human ratings of whether they are well-formed natural language questions.

http://goo.gl/language/query-wellformedness

## Description

Google's query wellformedness dataset was created by crowdsourcing well-formedness annotations for 25,100 queries from the Paralex corpus. Every query was annotated by five raters each with 1/0 rating of whether or not the query is well-formed. For further details please read our paper: **[Identifying Well-formed Natural Language Questions](https://arxiv.org/abs/1808.09419)**

For each query we provide the average of the 5 binary judgements as the wellformedness score for the query. Following are some examples of queries present in the dataset:

Query | Wellformedness rating
------|-----------------------
Which form of government is still in place in greece ? | 1.0
Population of owls just in north america ? | 0.0
Is johnny depp a celtic fan ? | 0.8
Where did Roald Dahl live in his teenaged years ? | 0.6

The dataset is divided into three files: train.tsv, dev.tsv and test.tsv each containing rated queries. The size of the files is as follows:

File        | No. of queries
------------| ---------------
train.tsv   | 17,500
dev.tsv     |  3,750
test.tsv    |  3,850

## Examples

The examples in each file are tab separated containing the following columns:

Column | Content
:-----:| ---------------
1      | The European Union includes how many ?
2      | 0.2

## Reference

If you use or discuss this dataset in your work, please cite our paper:

```
@InProceedings{FaruquiDas2018,
  title = {{Identifying Well-formed Natural Language Questions}},
  author = {Faruqui, Manaal and Das, Dipanjan},
  booktitle = {Proc. of EMNLP},
  year = {2018}
}
```

## License

Query-wellformedness dataset is licensed under [CC BY-SA 4.0](http://creativecommons.org/licenses/by-sa/4.0/). Any third party content or data is provided “As Is” without any warranty, express or implied.

## Contact

If you have a technical question regarding the dataset or publication, please
create an issue in this repository.
