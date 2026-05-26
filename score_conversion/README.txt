This directory contains the data and code for converting the raw annotations using pairwise comparison (PC) and best-worst scaling (BWS) to real-valued scores for analysis.

Content:
json_output_to_hollis_input.ipynb: notebook for turning PC/BWS annotations from LLMs (raw output in JSON format) into dataframes ready for converting into real-value scores (with the scripts from Hollis(2018), provided by my supervisor, as they were also used in conducting the original study.)
bws_itemid_tweetids.csv, pc_itemid_tweetids.csv: the mapping of PC/BWS records to corresponding tweet ids, copied from the directory "annotation".
raw_output_from_models: the directory containing LLM-generated annotations in the form of JSON files, copied from the directory "annotation".
conversion: the directory in which score conversion was performed by running .py scripts from Hollis(2018) in the terminal:
 - bws_hollis_input, pc_hollis_input: .csv files generated from json_output_to_hollis_input.ipynb
 - original scripts from Hollis(2018) were also placed and used in this directory, but are not shared publicly here.
GPT_scores, mini_scores, nano_scores: real-valued scores generated from PC/BWS annotations.

References:
Hollis, Geoff. 2018. Scoring best-worst data in unbalanced many-item designs, with applications to crowdsourcing semantic judgments. Behavior Research Methods, 50(2):711–729.