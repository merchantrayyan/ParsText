# ParsText: A Digraphic Corpus for Tajik-Farsi Transliteration
This repository contains the corpus for the paper entitled ["ParsText: A Digraphic Corpus for Tajik-Farsi Transliteration"](https://doi.org/10.31234/osf.io/xdf2w). 

This dataset is available in JSON, CSV and TXT format. We also provide each source of data separately, with individual TXT files for each raw/unaligned entry.


```
.
├── data                    # Corpus data
│   ├── aligned             # All (pre-processed) data aligned in various formats
│   │   ├── csv             # .csv format - one file per <source>
│   │   │   ├── <source>.csv
│   │   ├── json            # .json format - one file per <source>
│   │   │   ├── <source>.json
│   │   ├── txt             # .txt format - two files per <source>
│   │   │   ├── <source>.tj   # Tajik sentences
│   │   │   ├── <source>.fa   # Farsi sentences
│   ├── unaligned           # All raw data as individual .txt files in each <source> folder
│   │   ├── <source>        # tajik/source_1.tj <=> farsi/source_1.fa
│   │   │   ├── tajik       
│   │   │   │   ├── <source>_1.tj
│   │   │   ├── farsi       
│   │   │   │   ├── <source>_1.fa
├── alignment               # Alignment using GaChalign and pre-processing method used
│   ├──                     
│   ├──                   
├── LICENSE
└── README.md
```

If you use or reference ParsText, please cite our paper:

```
@InProceedings{MerchantTang_CAWL_Accepted_2024,
author = {Rayyan Merchant and Kevin Tang},
title = {{P}ars{T}ext: A Digraphic Corpus for {T}ajik-{F}arsi Transliteration},
booktitle = {{Proceedings of the Second Workshop on Computation and Written Language (CAWL 2024)}},
year = {2024},
editor = {Gorman, Kyle and Prud’hommeaux, Emily and Sproat, Richard and Roark, Brian},
note = {accepted (Preprint: \url{https://doi.org/10.31234/osf.io/xdf2w}},
publisher = {Association for Computational Linguistics},
month = {05},
pubstate = {forthcoming},
address = {Torino, Italia},
}
```
