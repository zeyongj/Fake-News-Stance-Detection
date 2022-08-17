# Prompt-based Text Matching Methods for Fake News Stance Detection

## Introudction
- SFU CMPT 413/713: Computational Linguistics/Natural Language Processing Course Project.
- Project duration is from October 2021 to December 2021.
- Text stance detection means that the machine learning system accepts two pieces of input text, and then output the stance relationship between the two pieces of text, such as agreement, opposition, or neutrality.
- This project is dedicated to using the BERT pre-training model to implement the classifier of stance detection related to fake news recognition.
- Fake News Challenge (FNC-1) is selected as the experimental environment, and the BERT model is used to process FNC task data, and an accuracy rate of 90.37% is obtained.
- For more details, please check the `report.pdf`.
- To view our presentation, please check the [project website](https://www.zeyongjin.net/post/project-003-nlp-prompt-based-text-matching-methods-for-fake-news-stance-detection), the slides `presentation.pdf` are also available in this repo.
- The professor is Dr. Angel Chang.
- The group members are Zeyong Jin (zeyongj@sfu.ca), Yuqing Wu (ywa292@sfu.ca) and Zhi Feng (zhif@sfu.ca).

## Contents

    source
    
    output
    
    README.md
    
    report.pdf
    
    presentation.pdf

## Requirements

- matplotlib==3.2.2
- numpy==1.19.5
- pandas==1.1.5
- sklearn==1.0.1
- torch==1.9.0+cu111
- torch_xla==1.9
- transformers==4.12.5

## Execution

- Via Google Colab, first running the `project.ipynb` in the source folder for model training. Be prepared for sevral hours or days of execution.
- After the previous step, running the `scorer.py` in the output folder to evaluate the trained model.

## References

- David M Blei, Andrew Y Ng, and Michael I Jordan. 2003. Latent dirichlet allocation. the Journal of machine Learning research, 3:993–1022.
- Jacob Devlin, Ming-Wei Chang, Kenton Lee, and Kristina Toutanova. 2018. Bert: Pre-training of deep bidirectional transformers for language understanding. arXiv preprint arXiv:1810.04805.
- Baotian Hu, Zhengdong Lu, Hang Li, and Qingcai Chen. 2014. Convolutional neural network architectures for matching natural language sentences. In Advances in neural information processing systems, pages 2042–2050.
- Po-Sen Huang, Xiaodong He, Jianfeng Gao, Li Deng, Alex Acero, and Larry Heck. 2013. Learning deep structured semantic models for web search using clickthrough data. In Proceedings of the 22nd ACM international conference on Information & Knowledge Management, pages 2333–2338.
- Ling Liu and M Tamer O¨ zsu. 2009. Encyclopedia of database systems, volume 6. Springer New York, NY, USA:.
- Yinhan Liu, Myle Ott, Naman Goyal, Jingfei Du, Mandar Joshi, Danqi Chen, Omer Levy, Mike Lewis, Luke Zettlemoyer, and Veselin Stoyanov. 2019. Roberta: A robustly optimized bert pretraining approach. arXiv preprint arXiv:1907.11692.
- Wenpeng Lu, Xu Zhang, Huimin Lu, and Fangfang Li. 2020. Deep hierarchical encoding model for sentence semantic matching. Journal of Visual Communication and Image Representation, 71:102794.
- Michal Lukasik, PK Srijith, Duy Vu, Kalina Bontcheva, Arkaitz Zubiaga, and Trevor Cohn. 2016. Hawkes processes for continuous time sequence classification: an application to rumour stance classification in twitter. In Proceedings of the 54th Annual Meeting of the Association for Computational Linguistics (Volume 2: Short Papers), pages 393–398.
- Matthew E Peters, Mark Neumann, Mohit Iyyer, Matt Gardner, Christopher Clark, Kenton Lee, and Luke Zettlemoyer. 2018. Deep contextualized word representations. arXiv preprint arXiv:1802.05365.
- Alec Radford, Karthik Narasimhan, Tim Salimans, and Ilya Sutskever. 2018. Improving language understanding by generative pre-training.
- Nils Reimers and Iryna Gurevych. 2019. Sentence-bert: Sentence embeddings using siamese bert-networks. arXiv preprint arXiv:1908.10084.
- Dhanya Sridhar, James Foulds, Bert Huang, Lise Getoor, and Marilyn Walker. 2015. Joint models of disagreement and stance in online debate. In Proceedings of the 53rd Annual Meeting of the Association for Computational Linguistics and the 7th International Joint Conference on Natural Language Processing (Volume 1: Long Papers), pages 116–125.
- Christian Stab and Iryna Gurevych. 2017. Parsing argumentation structures in persuasive essays. Computational Linguistics, 43(3):619–659.
- Kai Sheng Tai, Richard Socher, and Christopher D Manning. 2015. Improved semantic representations from tree-structured long short-term memory networks. arXiv preprint arXiv:1503.00075.
- Ming Tan, Cicero Dos Santos, Bing Xiang, and Bowen Zhou. 2016. Improved representation learning for question answer matching. In Proceedings of the 54th Annual Meeting of the Association for Computational Linguistics (Volume 1: Long Papers), pages 464–473.
- Jeffrey Ullman. 2011. Mining of massive datasets. Cambridge University Press.
- Ashish Vaswani, Noam Shazeer, Niki Parmar, Jakob Uszkoreit, Llion Jones, Aidan N Gomez, Łukasz Kaiser, and Illia Polosukhin. 2017. Attention is all you need. In Advances in neural information processing systems, pages 5998–6008.
- Marilyn Walker, Pranav Anand, Rob Abbott, and Ricky Grant. 2012. Stance classification using dialogic properties of persuasion. In Proceedings of the 2012 conference of the North American chapter of the association for computational linguistics: Human language technologies, pages 592–596.

## License

This work is licensed under [Apache License, Version 2.0](https://www.apache.org/licenses/LICENSE-2.0) (or any later version). 

`SPDX-License-Identifier: Apache-2.0-or-later`

## Disclaimer

This repository is ONLY for backup. Students should NEVER use this repository to finish their works, IN ANY WAY.

It is expected that within this course, the highest standards of academic integrity will be maintained, in
keeping with SFU’s Policy S10.01, `Code of Academic Integrity and Good Conduct`.

In this class, collaboration is encouraged for in-class exercises and the team components of the assignments, as well
as task preparation for group discussions. However, individual work should be completed by the person
who submits it. Any work that is independent work of the submitter should be clearly cited to make its
source clear. All referenced work in reports and presentations must be appropriately cited, to include
websites, as well as figures and graphs in presentations. If there are any questions whatsoever, feel free
to contact the course instructor about any possible grey areas.

Some examples of unacceptable behaviour:
- Handing in assignments/exercises that are not 100% your own work (in design, implementation,
wording, etc.), without a clear/visible citation of the source.
- Using another student's work as a template or reference for completing your own work.
- Using any unpermitted resources during an exam.
- Looking at, or attempting to look at, another student's answer during an exam.
- Submitting work that has been submitted before, for any course at any institution.

All instances of academic dishonesty will be dealt with severely and according to SFU policy. This means
that Student Services will be notified, and they will record the dishonesty in the student's file. Students
are strongly encouraged to review SFU’s Code of Academic Integrity and Good Conduct (S10.01) available
online at: http://www.sfu.ca/policies/gazette/student/s10-01.html.

## Acknowledgements

During the project, we had several meetings with Prof. Angel Chang of the School of Computing Science, Simon Fraser University. We would like to thank Prof. Chang for giving us beneficial suggestions on determining the topic, the preparation of the presentation and the arrangements of the source file, etc. We also thank the teaching team for providing feedback on our abstract, milestone paper and presentation.

## Author

Zeyong Jin

December 8th, 2021

