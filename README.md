#
This repository contains the corpus for the paper entitled [ANONYMIZED]. 

This dataset is available in JSON, CSV and TXT format. In addition to these, we provide  individual TXT files for each raw/unaligned entry to allow for users' own alignment methods. Our preprocessing and alignment code is also available.


```
.
├── data                          # Corpus data
│   ├── aligned                   # All (pre-processed) data aligned in various formats
│   │   ├── csv                   # .csv format - one file per <source>
│   │   │   ├── <source>.csv
│   │   ├── json                  # .json format - one file per <source>
│   │   │   ├── <source>.json
│   │   ├── txt                   # .txt format - two files per <source>
│   │   │   ├── <source>.tj       # Tajik sentences
│   │   │   ├── <source>.fa       # Farsi sentences
│   ├── unaligned                 # All raw data as individual .txt files in each <source> folder
│   │   ├── <source>.zip          # tajik/source/source_1.tj <=> farsi/source_1.fa
│   │   │   ├── <source>_1.tj    
│   │   │   ├── <source>_1.fa
│   │   │   ├── ...
├── alignment                     # Alignment and preprocessing code                  
│   ├── gale-church.py            # Original GaChalign code with ability to specify output
│   ├── gale.py                   # Calls gale-church.py on specified files
│   ├── gacha_input.py            # Converts corpus to GaChalign format
│   ├── minimath.py               # Dependency for GaChalign                
├── LICENSE
└── README.md
```

If you use or reference [ANONYMIZED], please cite our paper:

```
@inproceedings{anonymous-2024,
    title = "{[Title Redacted]}",
    author = "[Anonymous] and [Anonymous]",
    editor = "[Anonymous] and [Anonymous] and [Anonymous] and [Anonymous]",
    booktitle = "[Journal Redacted for Anonymity]",
    month = may,
    year = "2024",
    publisher = "[Publisher Redacted for Anonymity]]",
    url = "[Redacted]",
    pages = "1--7",
    abstract = "[Abstract Redacted for Anonymity]"
}
```
