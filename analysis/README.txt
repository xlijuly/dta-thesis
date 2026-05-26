This directory contains the data and code for analyzing and visualizing the results.

Content:
- preprocessing:
 - human_data: 
  - valence.xlsx, arousal.xlsx, dominance.xlsx: human annotations for Batch 1 provided by my supervisor.
  - human_scores.ipynb: notebook for turning Human VAD scores into a long format table.
  - human_scores.csv: output of human_scores.ipynb.
 - LLMs:
  - gpt, mini, nano: directories containing PC/BWS scores from the directory "score_conversion".
  - llm_pc_bws.ipynb: notebook for turning PC/BWS annotations into a long format table.
  - llm_pc_bws_scores.csv: output of llm_pc_bws.ipynb.
  - rs: directory containing LLM annotations with RS, notebook for turning RS annotations (0-100 and 0-10) into a long format table, and the outputs.
  - llm_scores.ipynb: notebook for merging the RS and PC/BWS tables, resulting in a long format table with all LLM annotations.
  - llm_scores.csv: output of llm_scores.ipynb.
- rs10: 
 - rs10.ipynb: notebook for the supplementary experiment comparing 0-100 and 0-10 rating scales (section 4.5 of the thesis)
 - llm_rs_scores.csv, llm_rs10_scores.csv: long format tables for RS annotations from the directory "rs".
- human_scores.csv, llm_scores.csv (same files as mentioned above, copied): long format tables ready for analysis.
- results.ipynb: notebook for the results and analysis sections (4.1-4.4) of the thesis. Part of the code (functions) for section 4.4 is taken from Calderon et al.(2025)'s AltTest notebook, openly available on GitHub (https://github.com/nitaytech/AltTest), and adapted for the present data.

References:
Calderon, Nitay, Roi Reichart, and Rotem Dror. 2025. The alternative annotator test for LLM-as-a-judge: How to statistically justify replacing human annotators with LLMs. In Proceedings of the 63rd Annual Meeting of the Association for Computational Linguistics (Volume 1: Long Papers), pages 16051–16081, Association for Computational Linguistics, Vienna, Austria.