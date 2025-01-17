<img src="./asset/moonshines.png" width="150" align="right">

Moonshines
==========


![CC BY 4.0](https://img.shields.io/badge/license-CC--BY-lightgrey)

![characters badge](badges/characters.svg) ![regions badge](badges/regions.svg) ![lines badge](badges/lines.svg) ![files badge](badges/files.svg) 


## License

This dataset is published under the CC-BY 4.0 License.

To cite this dataset:

``` 
Chagué, A. (2023). moonshines (Version 2.0.0) [Data set]. https://github.com/alix-tz/moonshines
```

## Description

This dataset is composed of pages of text written in 2023 by a single person, copying texts taken from Guillaume Apollinaire's poems published in [*Alcools*](https://www.gutenberg.org/cache/epub/15462/pg15462.txt). 

The dataset is divided into two parts: 

- `data/` which is intended to train transcription models,
- `test/` which is intended for test.

## Transcription guidelines

The transcription strictly follows what is written on the images, including accentuation or capitalization errors.

The segmentation follows the SegmOnto ontology and mostly relies on `MainZone` and `DefaultLine`.

## Possible limitations

Since the text follows the structure of *Alcools*, there is almost no ponctuation in this ground truth. Besides, most of the lines start with a capital letter.
