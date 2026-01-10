## Maithili-MT

This repository contains the Hindi-Maithili parallel corpus created as part of the work titled "MaithiliMT: Developing Multi-domain Parallel Corpus for Hindi-Maithili Machine Translation".


### Data
The folder 'Data' contains four sub-folders:
- Opus: The data collected from Opus of size 646,920 sentences.
- Post-Edited: The post-edited synthetic data of size 31,760 sentences.
- Synthetic: Synthetic data generated from existing Hindi data using Google Translate of size 508,339 sentences.
- Test: Manually created domain-specific test sets used in our experiments of size 753 sentences.

**Note:** Due to the file size limitations, Opus and Synthetic data are uploaded externally and can be accessed at: [GDrive Link](https://drive.google.com/drive/folders/1G2TlF4vfunZCZJAcctyNKaSFiSVMwAwz?usp=sharing). Post-edited and Test datasets are accessible from the respective folders.

### Citation
Please kindly cite the following paper if you have used our dataset:

```
@article{Appicharla2026MaithiliMT,
  author  = {Appicharla, Ramakrishna and
             Jha, Saroj Kumar and
             Ekbal, Asif and
             Bhattacharyya, Pushpak},
  title   = {MaithiliMT: Developing Multi-Domain Parallel Corpus for Hindi--Maithili Machine Translation},
  journal = {Language Resources and Evaluation},
  volume  = {60},
  number  = {1},
  pages   = {12},
  year    = {2026},
  publisher = {Springer},
  doi     = {10.1007/s10579-025-09890-9},
  url     = {https://doi.org/10.1007/s10579-025-09890-9},
  issn    = {1574-0218},
  abstract = {This work describes MaithiliMT, a multi-domain parallel corpus for the Hindi--Maithili language pair. Maithili is one of the 22 scheduled languages of India and is spoken by 14 million people. Maithili and Hindi belong to the Indo-Aryan language family and share lexical and syntactic similarities. We manually analyze the available Hindi--Maithili corpus and observe that the available corpus is of poor quality and that Hindi--Maithili machine translation (MT) can benefit from additional corpora. We create additional parallel corpora for administration, judicial, education, and general domains. The newly created corpus consists of a synthetic corpus created via back-translation and manual translation of monolingual Hindi data into Maithili. We also create post-edited data by manually correcting the generated synthetic data. We follow multilingual NMT, code-mixed augmentation, and automatic post-editing approaches to train baseline neural machine translation (NMT) models. The newly created dataset is of higher quality than the existing Hindi--Maithili corpus, and the NMT results show that multilingual models give better results than the other approaches. We release the created dataset for further research and development purposes.}
}

```
