# Summary 
The present dataset is a collection of Iron Ossetic texts from the [Corpus of Oral Texts](https://www.ossetic-studies.org/en/texts/iron) with manual annotation for parts-of-speech and morphological features in UD v2.
# Introduction
The Corpus of Oral Texts is manually annotated for parts-of-speech and morphological features in custom schema. The annotation is manually revised and manually converted into the CoNLL-U Format using UD v2 Annotation Guidelines with the addition of language-specific guidelines. Ossetic is an Iranic language from the Indo-European family spoken by up to 641.450 speakers mostly in North Causasus region.

The present dataset contains 5454 sentences total. Training set contains 80% (4364) of the sentences. Validation and test sets contain 10% (545) of the sentences each.
# Statistics
## Subgenre distribution
| Tag | Train | Development | Test |
| :--- | :---: | :---: | :---: |
| Radio | 253 (6.15\%) | 37 (6.79\%) | 29 (5.32\%) |
| Expedition | 4111 (93.85\%) | 508 (93.21\%) | 516 (94.68\%) |

## Top 20 morphological tags distribution
| Tag | Train | Development | Test |
| :--- | :---: | :---: | :---: |
| PUNCT | 14913 (25.58\%) | 1865 (24.92\%) | 1824 (25.16\%) |
NOUN,Case=Nom\|Number=Sing | 3269 (5.61\%) | 450 (6.01\%) | 444 (6.12\%) |
PART | 3236 (5.55\%) | 419 (5.60\%) | 394 (5.43\%) |
CCONJ | 2794 (4.79\%) | 351 (4.69\%) | 355 (4.90\%) |
PROPN,Case=Nom | 1888 (3.24\%) | 253 (3.38\%) | 277 (3.82\%) |
ADV | 1027 (1.76\%) | 109 (1.46\%) | 127 (1.75\%) |
ADV,PronType=Int | 1009 (1.73\%) | 112 (1.50\%) | 116 (1.60\%) |
NOUN,Case=Nom\|Number=Plur | 1003 (1.72\%) | 126 (1.68\%) | 140 (1.93\%) |
ADV,PronType=Dem | 999 (1.71\%) | 123 (1.64\%) | 139 (1.92\%) |
PART,Polarity=Neg | 988 (1.69\%) | 111 (1.48\%) | 124 (1.71\%) |
ADJ | 882 (1.51\%) | 120 (1.60\%) | 104 (1.43\%) |
ADV,Deixis=Remt\|PronType=Dem | 851 (1.46\%) | 132 (1.76\%) | 111 (1.53\%) |
VERB,Mood=Ind\|Number=Sing\|Person=3\|<br>Tense=Pres\|VerbForm=Fin | 830 (1.42\%) | 100 (1.34\%) | 85 (1.17\%) |
VERB,Mood=Ind\|Number=Sing\|Person=3\|<br>Preverb=Yes\|Tense=Past\|VerbForm=Fin | 749 (1.28\%) | 95 (1.27\%) | 87 (1.20\%) |
INTJ | 714 (1.22\%) | 113 (1.51\%) | 132 (1.82\%) |
ADV,Deixis=Prox\|PronType=Dem | 701 (1.20\%) | 77 (1.03\%) | 92 (1.27\%) |
VERB,Mood=Ind\|Number=Sing\|Person=3\|<br>Tense=Past\|VerbForm=Fin | 673 (1.15\%) | 96 (1.28\%) | 98 (1.35\%) |
PRON,Case=Gen\|Number=Sing\|Person=3\|<br>PronType=Prs | 643 (1.10\%) | 82 (1.10\%) | 88 (1.21\%) |
NUM,Case=Nom\|NumType=Card | 610 (1.05\%) | 63 (0.84\%) | 81 (1.12\%) |
NOUN,Case=Gen\|Number=Sing | 590 (1.01\%) | 95 (1.27\%) | 66 (0.91\%) |

# References
```
@inproceedings{shatskikh2026ossetic,
  title={Ossetic-COT: Designing a morphologically annotated corpus and morphological analyzer for Ossetic},
  author={Shatskikh, Anna and Sorokin, Alexey},
  booktitle={Computational Linguistics and Intellectual Technologies. Proceedings of the International Conference “Dialogue 2026”},
  volume={2026},
  year={2026}
}
```
# Contact
The dataset was prepared by Anna Shatskikh (anapriselec@gmail.com) and Alexey Sorokin. All questions and comments are welcome.
# Changelog
