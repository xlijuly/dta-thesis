This directory contains the data and code for generating tuples required for LLM annotation using pairwise comparison and best-worst scaling. 

Content:
ID_1.txt: the IDs of the tweets to be annotated.
pc_batch1.txt and bws_batch1.txt: the tuples generated.
generate-PC-tuples.pl and generate-BWS-tuples.pl: PERL code from Kiritchenko and Mohammad (2016) for generating tuples when annotating with comparative methods (pairwise comparison and best-worst scaling). The parameters are set according to the experiment performed in this thesis. The scripts are provided by my supervisor, as they were also used in conducting the original study.

References:
Kiritchenko, Svetlana and Saif M. Mohammad. 2016. Capturing Reliable Fine-Grained Sentiment
Associations by Crowdsourcing and Best–Worst Scaling. In Proceedings of the 2016 Conference of
the North American Chapter of the Association for Computational Linguistics: Human Language
Technologies, pages 811–817, Association for Computational Linguistics, San Diego, California.
Kiritchenko, Svetlana and Saif Mohammad. 2017. Best-worst scaling more reliable than rating
scales: A case study on sentiment intensity annotation. In Proceedings of the 55th Annual
Meeting of the Association for Computational Linguistics (Volume 2: Short Papers), pages 465–470,
Association for Computational Linguistics, Vancouver, Canada.