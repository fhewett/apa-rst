# APA-RST
Corpus of 75 parallel texts, simplified on two levels, annotated with RST. The RST annotations can be found in the `rst/` folder, separated according to the complexity level. The aligned files can be found in the `alignments/` folder and the original texts in the `original_texts` folder.

## Notes on the aligned files

The `alignments/` folder contains three subfolders:
- in `or-b1` the sentences from the original texts are on the line that corresponds to the line in the B1 text
- `or-a2` same but for the A2 texts
- `b1-a2` the sentences from the B1 texts are on the line that corresponds to the line in the A2 text

If there are multiple sentences on one line, that means that multiple sentences were aligned to one sentence. If the line is empty, this means that no alignment was found.

## Additional alignment files with transformation labels

As of 2024, we have alignments with transformation labels (i.e. 'Simple split'). The files are formatted as `csv` files. More information on the annotation can be found in the SIGDIAL paper listed below.

The `alignments_with_transformations/` folder contains two subfolders:
- in `a2-b1` the A2 sentences are in the left-hand column, the B1 sentences in the right-hand column, and the transformation from B1 to A2 is in the middle
- `b1-or` same as above but with B1 on the left, OR on the right, the transformation from OR to B1 in the middle

## More information and citation

More information on the files can be found in our paper. If you use any of the data please cite this paper:

Freya Hewett. [APA-RST: A Text Simplification Corpus with RST Annotations](https://aclanthology.org/2023.codi-1.23/). In *Proceedings of the 4th Workshop on Computational Approaches to Discourse*. Toronto, Canada and Online, July 2023. Association for Computational Linguistics. 

If you use the alignment files with transformation labels please cite this paper:

Freya Hewett, Hadi Asghari, and Manfred Stede. 2024. [Elaborative Simplification for German-Language Texts](https://aclanthology.org/2024.sigdial-1.3). In Proceedings of the 25th Annual Meeting of the Special Interest Group on Discourse and Dialogue, pages 29–39, Kyoto, Japan. Association for Computational Linguistics.
