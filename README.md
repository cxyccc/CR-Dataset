# CR-Dataset
A Cantonese rumor dataset for the paper 《Identifying Cantonese Rumors with Discriminative Feature Integration in online Social Networks》

We develop a web crawler to collect Cantonese tweets from Twitter and finish the data annotation to construct this dataset. This dataset contains 27,328 tweets, including 13,883 rumors and 13,445 non-rumors.

## Collection

CR-Dataset-example.csv: This file provides the source tweets and labels in a format like: 'text, label'.

Example:

| Text | Label |
| :----: | :----: |
| 今日警察已經光明正大喬裝示威者到處破壞而唔需要隱藏！光明正大拿槍對準市民 #929globalantitotalitarianism #hkpolicebrutality https://t.co/OURXJZyfag | 1 |

The time of data collection: 
- February 2020 - April 2020 
- November 2021 - December 2021

## Annotation

The reports from three sources are recognized as the bases of facts:
- [Hong Kong Government News](https://sc.news.gov.hk)
- [Hong Kong Police Force](https://www.police.gov.hk)
- [*Top 10 Rumors of Mobs in Hong Kong in 2019*](https://m.mp.oeeee.com/a/BAAFRD000020200112249042.html) from *Southern Metropolis Daily*

Data annotation is strictly in accordance with reports from the above three sources, and does not involve personal political positions. This dataset is used for academic research only.

## Citation

If you find this dataset useful, please cite our paper.



