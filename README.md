# Readme

This repository contains the scripts to produce the analyses in:

Goodwin, E., Levin, B., & Morgan, E. (2025). Syntactic Choice Is Shaped by Fine-Grained, Item-Specific Knowledge. Proceedings of the Annual Meeting of the Cognitive Science Society, 47.

To run these scripts, please first download the corpus data files from our [dataset repository](https://github.com/emilygoodwin/LCOD), and put them in the `data` directory.

Then run `corpusAnalyses.Rmd`.

To reproduce the results with the human preference data collected by Hawkins et al., you must also download their data (`generated_pairs_with_results.csv`) from their [repository](https://github.com/taka-yamakoshi/neural_constructions/tree/master/DAIS/data) and add it to the `data/humanPreferenceData` directory. Then run `humanDataComparison.Rmd`.

Reference: \
Robert Hawkins, Takateru Yamakoshi, Thomas Griffiths, and Adele Goldberg. 2020. [Investigating representations of verb bias in neural language models](https://aclanthology.org/2020.emnlp-main.376/). In *Proceedings of the 2020 Conference on Empirical Methods in Natural Language Processing (EMNLP)*, pages 4653–4663, Online. Association for Computational Linguistics.
