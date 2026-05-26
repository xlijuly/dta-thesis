This directory contains the data and code for prompting LLMs to generate annotations for the present study.

Content:
prompting.ipynb: the notebook with code for prompting (single item tests, pilot tests, and finally annotating all tweets).
rs_batch1.txt, pc_batch1.txt, bws_batch1.txt: the tweet ids of the tweets, pairs, or tuples for annotating with the 3 different methods. The tweet ids for annotating with rating scales (RS) are directly copied from the VAD scores data provided by my supervisor. For the pairs for pairwise comparison (PC) and tuples for best-worst scaling (BWS) are copied from the directory "tuple_generation".
GPT-5.4-mini_29Apr, GPT-5.4-nano_29Apr, GPT-5.4_29Apr, rs10_30Apr: directories containing LLM-generated annotations in the form of JSON files.
bws_itemid_tweetids.csv, pc_itemid_tweetids: the mapping of PC/BWS records to corresponding tweet ids, saved for future use.

Apart from these, another file id2text_batch1.csv which maps the tweet ids to tweet texts is also used in prompting, but is not shared in this public repository for privacy issues as it contains tweet texts.