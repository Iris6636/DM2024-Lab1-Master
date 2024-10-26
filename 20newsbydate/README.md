# 20 Newsgroups Dataset

## Introduction

The 20 Newsgroups dataset comprises roughly 20,000 documents from newsgroups, with an almost even distribution across 20 distinct newsgroups. Initially gathered by Ken Lang, this dataset has gained prominence in the machine learning community, particularly for text-related applications like classification and clustering.

## Dataset Structure

The dataset's organization is based on 20 different newsgroups, each representing a unique topic. While some of these newsgroups share similarities or are closely related, others are quite distinct from one another.

### List of Newsgroups:

- Computer Graphics
- Windows OS Miscellaneous
- IBM PC Hardware
- Mac Hardware
- Windows X
- Automobiles
- Motorcycles
- Baseball
- Hockey
- Cryptography
- Electronics
- Medicine
- Space
- Miscellaneous Sales
- Miscellaneous Politics
- Politics & Guns
- Middle East Politics
- Miscellaneous Religion
- Atheism
- Christianity

## Data Availability

The dataset is bundled in `.tar.gz` format. Within each bundle, individual subdirectories represent a newsgroup. Every file within these subdirectories corresponds to a document posted in that specific newsgroup.

There are three primary versions of the dataset:

1. The original version, which remains unaltered.
2. A version sorted by date, which segregates the data into training (60%) and test (40%) sets. This version has removed duplicates and some headers for clarity.
3. A version that only retains the "From" and "Subject" headers, with duplicates removed.

For those seeking a more consistent benchmark, the date-sorted version is recommended. It offers a realistic split based on time and has removed any newsgroup-specific identifiers.

## Matlab/Octave Version

For users of Matlab or Octave, a processed variant of the date-sorted dataset is available. This version is structured as a sparse matrix and includes files like `train.data`, `train.label`, `test.data`, and more. Additionally, a vocabulary file is provided to help users understand the indexed data.

## Additional Information

For more details and the original dataset, you can refer to the [official website](http://qwone.com/~jason/20Newsgroups/).

