 # A Survey of Surveys (NLP & ML)

*Maintainers*

*Natural Language Processing Lab., School of Computer Science and Engineering, Northeastern University*

In this document, we survey hundreds of survey papers on Natural Language  Processing (NLP) and Machine Learning (ML). We categorize these papers into popular topics and do simple counting for some interesting problems. In addition, we show the list of the papers with urls.  

## Categorization

We follow the ACL and ICML submission guideline of recent years, covering a broad range of areas in NLP and ML. The categorization is (Table 1-2):
+ NLP
    + <a href="#machine-learning-for-nlp">Machine Learning for NLP</a>
    + <a href="#machine-translation">Machine Translation</a>
    + <a href="#sentiment-analysis-stylistic-analysis-and-argument-mining">Sentiment Analysis Stylistic Analysis and Argument Mining</a>
    + <a href="#nlp-applications">NLP Applications</a>
    + <a href="#information-extraction">Information Extraction</a>
    + <a href="#dialogue-and-interactive-systems">Dialogue and Interactive Systems</a>
    + <a href="#generation">Generation</a>
    + <a href="#recommender-systems">Recommender Systems</a>
    + <a href="#resources-and-evaluation">Resources and Evaluation</a>
    + <a href="#speech-and-multimodality">Speech and Multimodality</a>
    + <a href="#summarization">Summarization</a>
    + <a href="#question-answering">Question Answering</a>
    + <a href="#knowledge-graph">Knowledge Graph</a>
    + <a href="#interpretability-and-analysis-of-models-for-nLP">Interpretability and Analysis of Models for NLP</a>
    + <a href="#ner">NER</a>
    + <a href="#reading-comprehension">Reading Comprehension</a>
    + <a href="#natural-language-processing">Natural Language Processing</a>
    + <a href="#text-classification">Text Classification</a>
    + <a href="#information-retrieval-and-text-mining">Information Retrieval and Text Mining</a>
    + <a href="#tagging-chunking-syntax-and-parsing">Tagging Chunking Syntax and Parsing</a>
    + <a href="#semantics">Semantics</a>
    + <a href="#linguistic-theories,-cognitive-modeling-and-psycholinguistics">Linguistic Theories, Cognitive Modeling and Psycholinguistics</a>
    + <a href="#language-grounding-to-vision,-robotics-and-beyond">Language Grounding to Vision, Robotics and Beyond</a>
    + <a href="#computational-social-science-and-social-media">Computational Social Science and Social Media</a>
+ Machine Learning
    + <a href="#general-machine-learning">General Machine Learning</a>
    + <a href="#deep-learning">Deep Learning</a>
    + <a href="#graph-neural-networks">Graph Neural Networks</a>
    + <a href="#interpretability-and-analysis">Interpretability and Analysis</a>
    + <a href="#architectures">Architectures</a>
    + <a href="#ml-applications">ML Applications</a>
    + <a href="#deep-reinforcement-learning">Deep Reinforcement Learning</a>
    + <a href="#transfer-learning">Transfer Learning</a>
    + <a href="#generative-adversarial-networks">Generative Adversarial Networks</a>
    + <a href="#optimization">Optimization</a>
    + <a href="#multi-task-and-multi-view-learning">Multi-Task and Multi-View Learning</a>
    + <a href="#automl">AutoML</a>
    + <a href="#classification,clustering,regression">Classification,Clustering,Regression</a>
    + <a href="#model-compression-and-acceleration">Model Compression and Acceleration</a>
    + <a href="#data-augmentation">Data Augmentation</a>
    + <a href="#few-shot-and-zero-shot-learning">Few-Shot and Zero-Shot Learning</a>
    + <a href="#semi-supervised-and-unsupervised-learning">Semi-Supervised and Unsupervised Learning</a>
    + <a href="#bayesian-methods">Bayesian Methods</a></td>
    + <a href="#federated-learning">Federated Learning</a>
    + <a href="#online-learning">Online Learning</a>
    + <a href="#meta-learning">Meta Learning</a>
    + <a href="#curriculum-learning">Curriculum Learning</a>
    + <a href="#trustworthy-machine-learning">Trustworthy Machine Learning</a>
    + <a href="#metric-learning">Metric Learning</a>

<table>
<tr>
    <td>NLP</td>
    <td>Machine Learning</td>
</tr>
<tr>
    <td><a href="#machine-learning-for-nlp">Machine Learning for NLP</a></td>
    <td><a href="#general-machine-learning">General Machine Learning</a></td>
</tr>
<tr>
    <td><a href="#machine-translation">Machine Translation</a></td>
    <td><a href="#deep-learning">Deep Learning</a></td>
</tr>
<tr>
    <td><a href="#sentiment-analysis,-stylistic-analysis,-and-argument-mining">Sentiment Analysis, Stylistic Analysis, and Argument Mining</a></td>
    <td><a href="#graph-neural-networks">Graph Neural Networks</a></td>
</tr>
<tr>
    <td><a href="#nlp-applications">NLP Applications</a></td>
    <td><a href="#interpretability-and-analysis">Interpretability and Analysis</a></td>
</tr>
<tr>
    <td><a href="#information-extraction">Information Extraction</a></td>
    <td><a href="#architectures">Architectures</a></td>
</tr>
<tr>
    <td><a href="#dialogue-and-interactive-systems">Dialogue and Interactive Systems</a></td>
    <td><a href="#ml-applications">ML Applications</a></td>
</tr>
<tr>
    <td><a href="#generation">Generation</a></td>
    <td><a href="#deep-reinforcement-learning">Deep Reinforcement Learning</a></td>
</tr>
<tr>
    <td><a href="#recommender-systems">Recommender Systems</a></td>
    <td><a href="#transfer-learning">Transfer Learning</a></td>
</tr>
<tr>
    <td><a href="#resources-and-evaluation">Resources and Evaluation</a></td>
    <td><a href="#generative-adversarial-networks">Generative Adversarial Networks</a></td>
</tr>
<tr>
    <td><a href="#speech-and-multimodality">Speech and Multimodality</a></td>
    <td><a href="#automl">AutoML</a></td>
<tr>
    <td><a href="#summarization">Summarization</a></td>
    <td><a href="#classification,clustering,regression">Classification,Clustering,Regression</a></td>
</tr>
<tr>
    <td><a href="#question-answering">Question Answering</a></td>
    <td><a href="#model-compression-and-acceleration">Model Compression and Acceleration</a></td>
</tr>
<tr>
    <td><a href="#knowledge-graph">Knowledge Graph</a></td>
    <td><a href="#data-augmentation">Data Augmentation</a></td>
</tr>
<tr>
    <td><a href="#interpretability-and-analysis-of-models-for-nLP">Interpretability and Analysis of Models for NLP</a></td>
    <td><a href="#few-shot-and-zero-shot-learning">Few-Shot and Zero-Shot Learning</a></td>
</tr>
<tr>
    <td><a href="#ner">NER</a></td>
    <td><a href="#semi-supervised-and-unsupervised-learning">Semi-Supervised and Unsupervised Learning</a></td>
<tr>
    <td><a href="#reading-comprehension">Reading Comprehension</a></td>
    <td><a href="#bayesian-methods">Bayesian Methods</a></td>
</tr>
<tr>
    <td><a href="#natural-language-processing">Natural Language Processing</a></td>
    <td><a href="#federated-learning">Federated Learning</a></td>
</tr>
<tr>
    <td><a href="#text-classification">Text Classification</a></td>
    <td><a href="#online-learning">Online Learning</a></td>
</tr>
<tr>
    <td><a href="#information-retrieval-and-text-mining">Information Retrieval and Text Mining</a></td>
    <td><a href="#meta-learning">Meta Learning</a></td>
</tr>
<tr>
    <td><a href="#tagging-chunking-syntax-and-parsing">Tagging Chunking Syntax and Parsing</a></td>
    <td><a href="#curriculum-learning">Curriculum Learning</a></td>
</tr>
<tr>
    <td><a href="#semantics">Semantics</a></td>
    <td><a href="#trustworthy-machine-learning">Trustworthy Machine Learning</a></td>
</tr>
<tr>
    <td><a href="#linguistic-theories,-cognitive-modeling-and-psycholinguistics">Linguistic Theories, Cognitive Modeling and Psycholinguistics</a></td>
    <td><a href="#metric-learning">Metric Learning</a></td>
</tr>
<tr>
    <td><a href="#language-grounding-to-vision,-robotics-and-beyond">Language Grounding to Vision, Robotics and Beyond</a></td>
    <td><a href="#graph-neural-networks">Graph Neural Networks</a></td>
</tr>
<tr>
    <td><a href="#computational-social-science-and-social-media">Computational Social Science and Social Media</a></td>
    <td><a href="#graph-neural-networks">Graph Neural Networks</a></td>
</tr>
</table>

<table>
<tr><td colspan="4">NLP</td></tr> 
<tr>
    <td>&emsp;<a href="#machine-learning-for-nlp">Machine Learning for NLP</a></td>
    <td>&ensp;<a href="#machine-translation">Machine Translation</a></td>
    <td colspan="2">&ensp;<a href="#sentiment-analysis,-stylistic-analysis,-and-argument-mining">Sentiment Analysis, Stylistic Analysis, and Argument Mining</a></td>
</tr>
<tr>
    <td>&emsp;<a href="#nlp-applications">NLP Applications</a></td>
    <td>&ensp;<a href="#information-extraction">Information Extraction</a></td>
    <td>&emsp;<a href="#dialogue-and-interactive-systems">Dialogue and Interactive Systems</a></td>
    <td>&ensp;<a href="#generation">Generation</a></td>
</tr>
<tr>
    <td>&emsp;<a href="#recommender-systems">Recommender Systems</a></td>
    <td>&ensp;<a href="#resources-and-evaluation">Resources and Evaluation</a></td>
    <td>&emsp;<a href="#speech-and-multimodality">Speech and Multimodality</a></td>
    <td>&ensp;<a href="#summarization">Summarization</a></td>
</tr>
<tr>
    <td>&emsp;<a href="#question-answering">Question Answering</a></td>
    <td>&ensp;<a href="#knowledge-graph">Knowledge Graph</a></td>
    <td colspan="2">&emsp;<a href="#interpretability-and-analysis-of-models-for-nLP">Interpretability and Analysis of Models for NLP</a></td>
</tr>
<tr>
    <td>&emsp;<a href="#ner">NER</a></td>
    <td>&ensp;<a href="#reading-comprehension">Reading Comprehension</a></td>
    <td>&emsp;<a href="#natural-language-processing">Natural Language Processing</a></td>
    <td>&ensp;<a href="#text-classification">Text Classification</a></td>
</tr>
<tr>
    <td colspan="2">&emsp;<a href="#information-retrieval-and-text-mining">Information Retrieval and Text Mining</a></td>
    <td colspan="2">&emsp;<a href="#syntax:-tagging,-chunking,-syntax-and-parsing">Syntax: Tagging, Chunking, Syntax and Parsing</a></td>
</tr>
<tr>
    <td>&emsp;<a href="#semantics">Semantics</a></td>
    <td colspan="3">&ensp;<a href="#linguistic-theories,-cognitive-modeling-and-psycholinguistics">Linguistic Theories, Cognitive Modeling and Psycholinguistics</a></td>
</tr>
<tr>
    <td colspan="2">&emsp;<a href="#language-grounding-to-vision,-robotics-and-beyond">Language Grounding to Vision, Robotics and Beyond</a></td>
    <td colspan="2">&emsp;<a href="#computational-social-science-and-social-media">Computational Social Science and Social Media</a></td>
</tr>
</table>

<center>Table 1</center>

<table>
<tr><td colspan="3">Machine Learning</td></tr> 
<tr>
    <td>&emsp;<a href="#general-machine-learning">General Machine Learning</a></td>
    <td>&ensp;<a href="#deep-learning">Deep Learning</a></td>
    <td>&ensp;<a href="#graph-neural-networks">Graph Neural Networks</a></td>
</tr>
<tr>
    <td>&ensp;<a href="#interpretability-and-analysis">Interpretability and Analysis</a></td>
    <td>&emsp;<a href="#architectures">Architectures</a></td>
    <td>&ensp;<a href="#ml-applications">ML Applications</a></td>
</tr>
<tr>
    <td>&emsp;<a href="#deep-reinforcement-learning">Deep Reinforcement Learning</a></td>
    <td>&ensp;<a href="#transfer-learning">Transfer Learning</a></td>
    <td>&emsp;<a href="#generative-adversarial-networks">Generative Adversarial Networks</a></td>
</tr>
<tr>
    <td>&ensp;<a href="#optimization">Optimization</a></td>
    <td>&emsp;<a href="#multi-task-and-multi-view-learning">Multi-Task and Multi-View Learning</a></td>
    <td>&ensp;<a href="#automl">AutoML</a></td>
</tr>
<tr>
    <td>&emsp;<a href="#classification,clustering,regression">Classification,Clustering,Regression</a></td>
    <td>&ensp;<a href="#model-compression-and-acceleration">Model Compression and Acceleration</a></td>
    <td>&emsp;<a href="#data-augmentation">Data Augmentation</a></td>
</tr>
<tr>
    <td>&ensp;<a href="#few-shot-and-zero-shot-learning">Few-Shot and Zero-Shot Learning</a></td>
    <td>&ensp;<a href="#semi-supervised-and-unsupervised-learning">Semi-Supervised and Unsupervised Learning</a></td>
    <td>&emsp;<a href="#bayesian-methods">Bayesian Methods</a></td>
</tr>
<tr>
    <td>&ensp;<a href="#federated-learning">Federated Learning</a></td>
    <td>&ensp;<a href="#online-learning">Online Learning</a></td>
    <td>&emsp;<a href="#meta-learning">Meta Learning</a></td>
</tr>
<tr>
    <td>&ensp;<a href="#curriculum-learning">Curriculum Learning</a></td>
    <td>&ensp;<a href="#trustworthy-machine-learning">Trustworthy Machine Learning</a></td>
    <td>&ensp;<a href="#metric-learning">Metric Learning</a></td>
</tr>
</table>

<center>Table 2</center>

To reduce class imbalance, we separate some of the hot sub-topics from the original categorization of ACL and ICML submissions. E.g., NER is a first-level area in our categorization because it is the focus of several surveys.

## Statistics

We order the areas by paper number (see Figure 1).

![area.png](https://i.loli.net/2020/07/13/EjQp3Jn86xgZald.png)

<center>Figure 1</center>

Also, we plot paper number as a function of publication year (see Figures 2).

![number.png](https://i.loli.net/2020/07/15/rwesyLRDPqcG51K.png)

<center>Figure 2</center>

In addition, we generate the word cloud to show the hot topics in these surveys (see Figures 3).

![ciyun.jpeg](https://i.loli.net/2020/07/13/wgOWXGNvamMtqbk.jpg)

<center>Figure 3</center>

## The Paper List

#### [Architectures](#content)

1. **Recent Advances in Convolutional Neural Networks.** Pattern Recognition 2018 [paper](https://arxiv.org/abs/1512.07108v3)

    *Jiuxiang Gu, Zhenhua Wang, Jason Kuen, Lianyang Ma, Amir Shahroudy, Bing Shuai, Ting Liu, Xingxing Wang, Gang Wang, Jianfei Cai, Tsuhan Chen*

1. **Deep Echo State Network (DeepESN): A Brief Survey.** arxiv 2017 [paper](https://arxiv.org/abs/1712.04323)

    *Claudio Gallicchio, Alessio Micheli*

1. **Non-local Neural Networks.** CVPR 2018 [paper](https://openaccess.thecvf.com/content_cvpr_2018/html/Wang_Non-Local_Neural_Networks_CVPR_2018_paper.html)

    *Xiaolong Wang, Ross B. Girshick, Abhinav Gupta, Kaiming He*

1. **Binary Neural Networks: A Survey.** Pattern Recognit. 2020 [paper](https://arxiv.org/abs/2004.03333)

    *Haotong Qin, Ruihao Gong, Xianglong Liu, Xiao Bai, Jingkuan Song, Nicu Sebe*

1. **Sum-product networks: A survey.** arxiv 2020 [paper](https://arxiv.org/abs/2004.01167)

    *Iago París, Raquel Sánchez-Cauce, Francisco Javier Díez*

1. **An Attentive Survey of Attention Models.** arxiv 2019 [paper](https://arxiv.org/abs/1904.02874)

    *Sneha Chaudhari, Gungor Polatkan, Rohan Ramanath, Varun Mithal*

1. **A Survey on Latent Tree Models and Applications.** Journal of Artificial Intelligence Research 2013 [paper](https://arxiv.org/abs/1402.0577)

    *Raphaël Mourad, Christine Sinoquet, Nevin L. Zhang, Tengfei Liu, Philippe Leray*

1. **Neural Module Networks.** CVPR 2016 [paper](https://ieeexplore.ieee.org/document/7780381)

    *Jacob Andreas, Marcus Rohrbach, Trevor Darrell, D Klein*

1. **A Survey of End-to-End Driving: Architectures and Training Methods.** arXiv 2020 [paper](https://arxiv.org/abs/2003.06404)

    *Ardi Tampuu, Maksym Semikin, Naveed Muhammad, Dmytro Fishman, Tambet Matiisen*

1. **A Survey of Convolutional Neural Networks: Analysis, Applications, and Prospects.** arxiv 2020 [paper](https://arxiv.org/abs/2004.02806)

    *Zewen Li, Wenjie Yang, Shouheng Peng, Fan Liu*

1. **Survey on the attention based RNN model and its applications in computer vision.** arxiv 2016 [paper](https://arxiv.org/abs/1601.06823)

    *Feng Wang, David M. J. Tax*

1. **Understanding LSTM -- a tutorial into Long Short-Term Memory Recurrent Neural Networks.** arxiv 2019 [paper](https://arxiv.org/abs/1909.09586)

    *Ralf C. Staudemeyer, Eric Rothstein Morris*

#### [AutoML](#content)

1. **A Comprehensive Survey of Neural Architecture Search: Challenges and Solutions.** arxiv 2020 [paper](https://arxiv.org/abs/2006.02903)

    *Pengzhen Ren, Yun Xiao, Xiaojun Chang, Po-Yao Huang, Zhihui Li, Xiaojiang Chen, Xin Wang*

1. **A Survey on Neural Architecture Search.** arxiv 2019 [paper](https://arxiv.org/abs/1905.01392)

    *Martin Wistuba, Ambrish Rawat, Tejaswini Pedapati*

1. **Benchmark and Survey of Automated Machine Learning Frameworks.** arxiv 2020 [paper](https://arxiv.org/abs/1904.12054)

    *Marc-André Zöller, Marco F. Huber*

1. **Neural Architecture Search: A Survey.** Journal of Machine Learning Research 2019 [paper](https://arxiv.org/abs/1808.05377)

    *Thomas Elsken, Jan Hendrik Metzen, Frank Hutter*

1. **AutoML: A Survey of the State-of-the-Art.** arxiv 2019 [paper](https://arxiv.org/abs/1908.00709)

    *Xin He, Kaiyong Zhao, Xiaowen Chu*

1. **Neural Architecture Search at CVPR 2019.** CVPR 2019  [paper](https://drsleep.github.io/review/NAS-at-CVPR-2019/)

    *Vladimir Nekrasov*

1. **Benchmark and Survey of Automated Machine Learning Frameworks.** arXiv 2019 [paper](https://arxiv.org/abs/1904.12054)

    *Marc-André Zöller, Marco F. Huber*

#### [Bayesian Methods](#content)

1. **Towards Bayesian Deep Learning: A Survey.** arxiv 2016 [paper](https://arxiv.org/abs/1604.01662)

    *Hao Wang, Dityan Yeung*

1. **A survey of non-exchangeable priors for Bayesian nonparametric models.** IEEE 2015 [paper](https://arxiv.org/abs/1211.4798)

    *Nicholas J. Foti, Sinead Williamson*

1. **Bayesian Nonparametric Space Partitions: A Survey.** arXiv 2020 [paper](https://arxiv.org/abs/2002.11394)

    *Xuhui Fan, Bin Li, Ling Luo, Scott A. Sisson*

#### [Classification,Clustering,Regression](#content)

1. **A Survey of Classification Techniques in the Area of Big Data.** CoRR 2015 [paper](https://arxiv.org/abs/1503.07477)

    *Praful Koturwar, Sheetal Girase, Debajyoti Mukhopadhyay*

1. **Deep learning for time series classification: a review.** arXiv 2019 [paper](https://arxiv.org/abs/1809.04356)

    *Hassan Ismail Fawaz, Germain Forestier, Jonathan Weber, Lhassane Idoumghar, Pierre-Alain Muller*

1. **How Complex is your classification problem? A survey on measuring classification complexity.** ACM Comput. Surv. 52(5) 2019 [paper](https://arxiv.org/abs/1808.03591)

    *Ana Carolina Lorena, Luis P F Garcia, Jens Lehmann, Marcilio C P Souto, Tin K Ho*

1. **A Survey on Multi-View Clustering.** CoRR 2017 [paper](https://arxiv.org/abs/1712.06246)

    *Guoqing Chao, Shiliang Sun, Jinbo Bi*

1. **A Survey of Constrained Gaussian Process Regression: Approaches and Implementation Challenges.** arxiv 2020 [paper](https://arxiv.org/abs/2006.09319)

    *Laura P. Swiler, Mamikon Gulian, Ari Frankel, Cosmin Safta, John D. Jakeman*

#### [Computational Social Science and Social Media](#content)

1. **Computational Sociolinguistics: A Survey.** Computational Linguistics 2016 [paper](https://arxiv.org/abs/1508.07544)

    *Dong Nguyen, A Seza Dogruoz, Carolyn Penstein Rose, Franciska De Jong*

#### [Curriculum Learning](#content)

1. **Automatic Curriculum Learning For Deep RL: A Short Survey.** arXiv 2020 [paper](https://arxiv.org/abs/2003.04664)

    *Rémy Portelas, Cédric Colas, Lilian Weng, Katja Hofmann, Pierre-Yves Oudeyer*

1. **Curriculum Learning for Reinforcement Learning Domains: A Framework and Survey.** arXIv 2020 [paper](https://arxiv.org/abs/2003.04960)

    *Sanmit Narvekar, Bei Peng, Matteo Leonetti, Jivko Sinapov, Matthew E. Taylor, Peter Stone*

#### [Data Augmentation](#content)

1. **A survey on Image Data Augmentation for Deep Learning.** Journal of Big Data 2019 [paper](https://link.springer.com/article/10.1186/s40537-019-0197-0)

    *Connor Shorten*

1. **A Visual Survey of Data Augmentation in NLP.** not found  [paper]()

    *Amit Chaudhary*

1. **Time Series Data Augmentation for Deep Learning: A Survey.** arXiv 2020 [paper](https://arxiv.org/abs/2002.12478)

    *Qingsong Wen, Liang Sun, Xiaomin Song, Jingkun Gao, Xue Wang, Huan Xu*

1. **EDA: Easy Data Augmentation Techniques for Boosting Performance on Text Classification Tasks.** arxiv 2019 [paper](https://arxiv.org/abs/1901.11196)

    *Jason Wei, Kai Zou*

#### [Deep Learning](#content)

1. **Survey of Dropout Methods for Deep Neural Networks.** arxiv 2019 [paper](https://arxiv.org/abs/1904.13310)

    *Alex Labach, Hojjat Salehinejad, Shahrokh Valaee*

1. **Deep Learning on Graphs: A Survey.** arxiv 2018 [paper](https://arxiv.org/abs/1812.04202)

    *Ziwei Zhang, Peng Cui, Wenwu Zhu*

1. **The History Began from AlexNet: A Comprehensive Survey on Deep Learning Approaches.** arxiv 2018 [paper](https://arxiv.org/abs/1803.01164)

    *Zahangir Alom, Tarek M Taha, Christopher Yakopcic, Stefan Westberg, Paheding Sidike, Mst Shamima Nasrin, Brian C Van Esesn, Abdul A S Awwal, Vijayan K Asari*

1. **Geometric Deep Learning: Going beyond Euclidean data.** IEEE/CoRR 2016 [paper](https://arxiv.org/abs/1611.08097)

    *Michael M. Bronstein, Joan Bruna, Yann LeCun, Arthur Szlam, Pierre Vandergheynst*

1. **Neural Message Passing for Quantum Chemistry.** ICML/CoRR 2017 [paper](https://arxiv.org/abs/1704.01212)

    *Justin Gilmer, Samuel S. Schoenholz, Patrick F. Riley, Oriol Vinyals, George E. Dahl*

1. **A survey on modern trainable activation functions.** arxiv 2020 [paper](https://arxiv.org/abs/2005.00817)

    *Andrea Apicella, Francesco Donnarumma, Francesco Isgrò, Roberto Prevete*

1. **Foundations of Sequence-to-Sequence Modeling for Time Series.** AISTATS 2018 [paper](https://arxiv.org/abs/1805.03714)

    *Vitaly Kuznetsov, Zelda Mariet*

1. **A Survey of Neuromorphic Computing and Neural Networks in Hardware.** CoRR 2017 [paper](https://arxiv.org/abs/1705.06963)

    *Catherine D. Schuman, Thomas E. Potok, Robert M. Patton, J. Douglas Birdwell, Mark E. Dean, Garrett S. Rose, James S. Plank*

1. **Survey of reasoning using Neural networks.** CoRR 2017 [paper](https://arxiv.org/abs/1702.06186)

    *Amit Sahu*

1. **Convergence of Edge Computing and Deep Learning: A Comprehensive Survey.** arXiv 2019 [paper](https://arxiv.org/abs/1907.08349?context=cs.NI)

    *Xiaofei Wang, Yiwen Han, Victor C.M. Leung, Dusit Niyato, Xueqiang Yan, Xu Chen*

1. **A Survey on Deep Hashing Methods.** arXiv 2020 [paper](https://arxiv.org/abs/2003.03369)

    *Xiao Luo, Chong Chen, Huasong Zhong, Hao Zhang, Minghua Deng, Jianqiang Huang, Xiansheng Hua*

1. **The Deep Learning Compiler: A Comprehensive Survey.** arXiv 2020 [paper](https://arxiv.org/abs/2002.03794)

    *Mingzhen Li, Yi Liu, Xiaoyan Liu, Qingxiao Sun, Xin You, Hailong Yang, Zhongzhi Luan, Depei Qian*

1. **Improving Deep Learning Models via Constraint-Based Domain Knowledge: a Brief Survey.** arXiv 2020 [paper](https://arxiv.org/abs/2005.10691)

    *Andrea Borghesi, Federico Baldo, Michela Milano*

1. **Deep Learning Theory Review: An Optimal Control and Dynamical Systems Perspective.** arXiv 2019 [paper](https://arxiv.org/abs/1908.10920)

    *Guan-Horng Liu, Evangelos A. Theodorou*

1. **Review: Ordinary Differential Equations For Deep Learning.** arXiv 2019 [paper](https://arxiv.org/abs/1911.00502)

    *Xinshi Chen*

1. **Time Series Forecasting With Deep Learning: A Survey.** arXiv 2020 [paper](https://arxiv.org/abs/2004.13408)

    *Bryan Lim, Stefan Zohren*

1. **Survey of Expressivity in Deep Neural Networks.** arxiv 2016 [paper](https://arxiv.org/abs/1611.08083)

    *Maithra Raghu, Ben Poole, Jon Kleinberg, Surya Ganguli, Jascha Sohldickstein*

1. **Deep learning.** nature 2015 [paper](https://www.nature.com/articles/nature14539)

    *Yann LeCun*

#### [Deep Reinforcement Learning](#content)

1. **Feature-Based Aggregation and Deep Reinforcement Learning: A Survey and Some New Implementations.** IEEE 2019 [paper](https://arxiv.org/abs/1804.04577)

    *Dimitri P. Bertsekas*

1. **A Brief Survey of Deep Reinforcement Learning.** arxiv 2017 [paper](https://arxiv.org/abs/1708.05866)

    *Kai Arulkumaran, Marc Peter Deisenroth, Miles Brundage, Anil A Bharath*

1. **Deep Reinforcement Learning: An Overview.** arxiv 2017 [paper](https://arxiv.org/abs/1701.07274)

    *Yuxi Li*

1. **A Short Survey on Probabilistic Reinforcement Learning.** arxiv 2019 [paper](https://arxiv.org/abs/1901.07010)

    *Reazul Hasan Russel*

1. **A Survey of Inverse Reinforcement Learning: Challenges, Methods and Progress.** CoRR 2018 [paper](https://arxiv.org/abs/1806.06877)

    *Saurabh Arora, Prashant Doshi*

1. **A Survey of Reinforcement Learning Informed by Natural Language.** IJCAI 2019 [paper](https://arxiv.org/abs/1906.03926)

    *Jelena Luketina, Nantas Nardelli, Gregory Farquhar, Jakob N. Foerster, Jacob Andreas, Edward Grefenstette, Shimon Whiteson, Tim Rocktäschel*

1. **A Survey of Reinforcement Learning Algorithms for Dynamically Varying Environments.** arXiv 2020 [paper](https://arxiv.org/abs/2005.10619)

    *Sindhu Padakandla*

1. **A Short Survey On Memory Based Reinforcement Learning.** arXiv 2019 [paper](https://arxiv.org/abs/1904.06736v1)

    *Dhruv Ramani*

1. **A Survey of Reinforcement Learning Techniques: Strategies, Recent Development, and Future Directions.** arXiv 2020 [paper](https://arxiv.org/abs/2001.06921)

    *Amit Kumar Mondal*

1. **A survey on intrinsic motivation in reinforcement learning.** arXiv 2019 [paper](https://arxiv.org/abs/1908.06976)

    *Aubret, Arthur，Matignon, Laetitia，Hassas, Salima*

1. **A Survey on Reproducibility by Evaluating Deep Reinforcement Learning Algorithms on Real-World Robots.** arXiv 2019 [paper](https://arxiv.org/abs/1909.03772)

    *Nicolai A. Lynnerup, Laura Nolling, Rasmus Hasle, John Hallam*

#### [Dialogue and Interactive Systems](#content)

1. **Recent Advances and Challenges in Task-oriented Dialog System.** arxiv 2020 [paper](https://arxiv.org/pdf/2003.07490)

    *Zheng Zhang, Ryuichi Takanobu, Minlie Huang, Xiaoyan Zhu*

1. **Neural Approaches to Conversational AI.** ACL 2018 [paper](https://arxiv.org/pdf/1809.08267)

    *Jianfeng Gao, Michel Galley, Lihong Li*

1. **Challenges in Building Intelligent Open-domain Dialog Systems.** arxiv 2019 [paper](https://arxiv.org/abs/1905.05709)

    *Minlie Huang, Xiaoyan Zhu, Jianfeng Gao*

1. **A Survey on Dialog Management: Recent Advances and Challenges.** arxiv 2020 [paper](https://arxiv.org/abs/2005.02233)

    *Yinpei Dai, Huihua Yu, Yixuan Jiang, Chengguang Tang, Yongbin Li, Jian Sun*

1. **A Survey of Document Grounded Dialogue Systems.** arxiv 2020 [paper](https://arxiv.org/abs/2004.13818)

    *Longxuan Ma, Wei-Nan Zhang, Mingda Li, Ting Liu*

1. **A Comparative Survey of Recent Natural Language Interfaces for Databases.** {VLDB} J. 2019 [paper](https://arxiv.org/abs/1906.08990)

    *Katrin Affolter, Kurt Stockinger, Abraham Bernstein*

1. **A Survey of Natural Language Generation Techniques with a Focus on Dialogue Systems - Past, Present and Future Directions.** arxiv 2019 [paper](https://arxiv.org/abs/1906.00500)

    *Sashank Santhanam, Samira Shaikh*

1. **A Survey on Dialogue Systems: Recent Advances and New Frontiers.** Sigkdd Explorations 2017 [paper](https://arxiv.org/abs/1711.01731)

    *Hongshen Chen, Xiaorui Liu, Dawei Yin, Jiliang Tang*

1. **A Survey of Available Corpora for Building Data-Driven Dialogue Systems.** arxiv 2015 [paper](https://arxiv.org/abs/1512.05742)

    *Iulian Vlad Serban, Ryan Lowe, Peter Henderson, Laurent Charlin, Joelle Pineau*

1. **A Survey of Arabic Dialogues Understanding for Spontaneous Dialogues and Instant Message.** arxiv 2015 [paper](https://arxiv.org/abs/1505.03084)

    *AbdelRahim A. Elmadany, Sherif M. Abdou, Mervat Gheith*

1. **A Survey on Dialogue Systems:Recent Advances and New Frontiers.** doi 2017 [paper](https://doi.org/10.1145/3166054.3166058)

    *Hongshen Chen, Xiaorui Liu, Dawei Yin, Jiliang Tang*

1. **A Survey of Document Grounded Dialogue Systems (DGDS).** arXiv 2020 [paper](https://arxiv.org/abs/2004.13818)

    *Longxuan Ma, Wei-Nan Zhang, Mingda Li, Ting Liu*

#### [Federated Learning](#content)

1. **Towards Utilizing Unlabeled Data in Federated Learning: A Survey and Prospective.** arXiv 2020 [paper](https://arxiv.org/abs/2002.11545v2)

    *Yilun Jin, Xiguang Wei, Yang Liu, Qiang Yang*

1. **Threats to Federated Learning: A Survey.** CoRL 2019 2020 [paper](https://arxiv.org/abs/2003.02133)

    *Lingjuan Lyu, Han Yu, Qiang Yang*

1. **A Survey towards Federated Semi-supervised Learning.** FRUCT 2020 [paper](https://arxiv.org/abs/2002.11545v1)

    *Yilun Jin, Xiguang Wei, Yang Liu, Qiang Yang*

#### [Few-Shot and Zero-Shot Learning](#content)

1. **Generalizing from a Few Examples: A Survey on Few-Shot Learning.** arxiv 2019 [paper](https://arxiv.org/abs/1904.05046)

    *Yaqing Wang, Quanming Yao, James Kwok, Lionel M. Ni*

1. **Few-shot Learning: A Survey.** arXiv 2020 [paper](https://arxiv.org/abs/1904.05046v1)

    *Yaqing Wang, Quanming Yao*

1. **A survey on Zero-shot learning.** Journal of science  [paper]()

    *Fengyi Song*

1. **A Survey of Zero-Shot Learning: Settings, Methods, and Applications.** ACM Journals 2019 [paper](https://dl.acm.org/doi/10.1145/3293318)

    *Wei Wang,Vincent W. Zheng,Han Yu,Chunyan Miao*

#### [General Machine Learning](#content)

1. **Ensembling Neural Networks: Many Could Be Better than All.** Artificial Intelligence 2002 [paper](https://doi.org/10.1016/S0004-3702(02)00190-X)

    *Zhihua Zhou, Jianxin Wu, Wei Tang*

1. **Advances and Open Problems in Federated Learning.** arXiv 2019 [paper](https://arxiv.org/abs/1912.04977)

    *Peter Kairouz, H Brendan Mcmahan, Brendan Avent, Aurelien Bellet, Mehdi Bennis, Arjun Nitin Bhagoji, Keith Bonawitz, Zachary Charles, Graham Cormode, Rachel Cummings, Rafael G L Doliveira, Salim El Rouayheb, David Evans, Josh Gardner, Zachary A Garrett, Adria Gascon, Badih Ghazi, Phillip B Gibbons, Marco Gruteser, Zaid Harchaoui, Chaoyang He, Lie He, Zhouyuan Huo, Ben Hutchinson, Justin Hsu, Martin Jaggi, Tara Javidi, Gauri Joshi, Mikhail Khodak, Jakub Konecný, Aleksandra Korolova, Farinaz Koushanfar, Sanmi Koyejo, Tancrede Lepoint, Yang Liu, Prateek Mittal, Mehryar Mohri, Richard Nock, Ayfer Ozgur, Rasmus Pagh, Mariana Raykova, Hang Qi, Daniel Ramage, Ramesh Raskar, Dawn Song, Weikang Song, Sebastian U Stich, Ziteng Sun, Ananda Theertha Suresh, Florian Tramer, Praneeth Vepakomma, Jianyu Wang, Li Xiong, Zheng Xu, Qiang Yang, Felix X Yu, Han Yu, Sen Zhao*

1. **Relational inductive biases, deep learning, and graph networks.** CoRR 2018 [paper](http://arxiv.org/abs/1806.01261)

    *Peter W. Battaglia, Jessica B. Hamrick, Victor Bapst, Alvaro Sanchez-Gonzalez, Vinícius Flores Zambaldi, Mateusz Malinowski, Andrea Tacchetti, David Raposo, Adam Santoro, Ryan Faulkner, Çaglar Gülçehre, H. Francis Song, Andrew J. Ballard, Justin Gilmer, George E. Dahl, Ashish Vaswani, Kelsey R. Allen, Charles Nash, Victoria Langston, Chris Dyer, Nicolas Heess, Daan Wierstra, Pushmeet Kohli, Matthew Botvinick, Oriol Vinyals, Yujia Li, Razvan Pascanu*

1. **A Survey on Graph Kernels.** Applied Network Science 2020 [paper](https://arxiv.org/abs/1903.11835)

    *Nils M. Kriege, Fredrik D. Johansson, Christopher Morris*

1. **Algorithms Inspired by Nature: A Survey.** arxiv 2019 [paper](https://arxiv.org/abs/1903.01893)

    *Pranshu Gupta*

1. **Deep Tree Transductions - A Short Survey.** INNSBDDL 2019 [paper](https://arxiv.org/abs/1902.01737)

    *Davide Bacciu, Antonio Bruno*

1. **A Survey on Multi-output Learning.** CoRR 2019 [paper](https://arxiv.org/abs/1901.00248)

    *Donna Xu, Yaxin Shi, Ivor W. Tsang, Yew-Soon Ong, Chen Gong, Xiaobo Shen*

1. **A Survey on Data Collection for Machine Learning: a Big Data -- AI Integration Perspective.** CoRR 2018 [paper](https://arxiv.org/abs/1811.03402)

    *Yuji Roh, Geon Heo, Steven Euijong Whang*

1. **Verification for Machine Learning, Autonomy, and Neural Networks Survey.** CoRR 2018 [paper](https://arxiv.org/abs/1810.01989)

    *Weiming Xiang, Patrick Musau, Ayana A. Wild, Diego Manzanas Lopez, Nathaniel Hamilton, Xiaodong Yang, Joel Rosenfeld, Taylor T. Johnson*

1. **A Survey on Surrogate Approaches to Non-negative Matrix Factorization.** CoRR 2018 [paper](https://arxiv.org/abs/1808.01975)

    *Pascal Fernsel, Peter Maass*

1. **The Benefits of Population Diversity in Evolutionary Algorithms: A Survey of Rigorous Runtime Analyses.** CoRR 2018 [paper](https://arxiv.org/abs/1801.10087)

    *Dirk Sudholt*

1. **A Survey on Resilient Machine Learning.** CoRR 2017 [paper](https://arxiv.org/abs/1707.03184)

    *Atul Kumar, Sameep Mehta*

1. **Machine Learning with World Knowledge: The Position and Survey.** CoRR 2017 [paper](https://arxiv.org/abs/1705.02908)

    *Yangqiu Song, Dan Roth*

1. **A survey on feature weighting based K-Means algorithms.** Journal of Classification 2016 [paper](https://arxiv.org/abs/1601.03483)

    *Renato Cordeiro de Amorim*

1. **Survey on Feature Selection.** CoRR 2015 [paper](https://arxiv.org/abs/1510.02892)

    *Tarek Amr Abdallah, Beatriz de La Iglesia*

1. **A Survey of Predictive Modelling under Imbalanced Distributions.** CoRR 2015 [paper](https://arxiv.org/abs/1505.01658)

    *Paula Branco, Luis Torgo, Rita Ribeiro*

1. **Hierarchical Mixtures-of-Experts for Exponential Family Regression Models with Generalized Linear Mean Functions: A Survey of Approximation and Consistency Results.** CoRR 2013 [paper](https://arxiv.org/abs/1301.7390)

    *Wenxin Jiang, Martin A. Tanner*

1. **Survey on Five Tribes of Machine Learning and the Main Algorithms.** Software Guide 2019 [paper](http://en.cnki.com.cn/Article_en/CJFDTotal-RJDK201907003.htm)

    *LI Xu-ran，DING Xiao-hong*

1. **Machine Learning in Network Centrality Measures: Tutorial and Outlook.** Association for Computing Machinery 2018 [paper](https://arxiv.org/abs/1810.11760)

    *Felipe Grando, Lisandro Zambenedetti Granville, Luís C. Lamb*

1. **Learning Representations of Graph Data -- A Survey.** arxiv 2019 [paper](https://arxiv.org/abs/1906.02989)

    *Mital Kinderkhedia*

1. **Hyperbox based machine learning algorithms: A comprehensive survey.** arxiv 2019 [paper](https://arxiv.org/abs/1901.11303)

    *Thanh Tung Khuat, Dymitr Ruta, Bogdan Gabrys*

1. **Machine Learning for Spatiotemporal Sequence Forecasting: A Survey.** arxiv 2018 [paper](https://arxiv.org/abs/1808.06865)

    *Xingjian Shi, Dit-Yan Yeung*

1. **Network Representation Learning: A Survey.** IEEE Trans. Big Data 2020 [paper](https://arxiv.org/abs/1801.05852)

    *Daokun Zhang, Jie Yin, Xingquan Zhu, Chengqi Zhang*

1. **Mean-Field Learning: a Survey.** arxiv 2012 [paper](https://arxiv.org/abs/1210.4657)

    *Hamidou Tembine, Raúl Tempone, Pedro Vilanova*

1. **Narrative Science Systems: A Review.** International Journal of Research 2015 [paper](https://arxiv.org/abs/1510.04420)

    *Paramjot Kaur Sarao, Puneet Mittal, Rupinder Kaur*

1. **A Tutorial on Network Embeddings.** arxiv 2018 [paper](https://arxiv.org/abs/1808.02590)

    *Haochen Chen, Bryan Perozzi, Rami Al-Rfou, Steven Skiena*

1. **Structure Learning of Probabilistic Graphical Models: A Comprehensive Survey.** arxiv 2011 [paper](https://arxiv.org/abs/1111.6925)

    *Yang Zhou*

1. **Statistical Queries and Statistical Algorithms: Foundations and Applications.** arxiv 2020 [paper](https://arxiv.org/abs/2004.00557)

    *Lev Reyzin*

1. **A survey of dimensionality reduction techniques.** arxiv 2014 [paper](https://arxiv.org/abs/1403.2877)

    *C.O.S. Sorzano, J. Vargas, A. Pascual Montano*

1. **Relational Representation Learning for Dynamic (Knowledge) Graphs: A Survey.** arXiv 2019 [paper](https://arxiv.org/abs/1905.11485)

    *Seyed Mehran Kazemi, Rishab Goel, Kshitij Jain, Ivan Kobyzev, Akshay Sethi, Peter Forsyth, Pascal Poupart*

1. **Graph Representation Learning: A Survey.** arXiv 2019 [paper](https://arxiv.org/abs/1909.00958)

    *Fenxiao Chen, Yuncheng Wang, Bin Wang, C.-C. Jay Kuo*

1. **Multi-Objective Multi-Agent Decision Making: A Utility-based Analysis and Survey.** Autonomous Agents and Multi-Agent Systems 2020 [paper](https://link.springer.com/content/pdf/10.1007/s10458-019-09433-x.pdf)

    *Roxana Rădulescu, Patrick Mannion, Diederik M. Roijers, Ann Nowé *

1. **Survey: Machine Learning in Production Rendering.** arXiv 2020 [paper](https://arxiv.org/abs/2005.12518v1)

    *Shilin Zhu*

1. **Machine Learning Testing: Survey, Landscapes and Horizons.** arXiv 2019 [paper](https://arxiv.org/abs/1906.10742v1)

    *Jie M. Zhang (1), Mark Harman (1 and 2), Lei Ma (3), Yang Liu (4) ((1) University College London, (2) Facebook London, (3) Kyushu University, (4) Nanyang Technological University)*

1. **Heuristic design of fuzzy inference systems: A review of three decades of research.** arXiv 2019 [paper](https://arxiv.org/abs/1908.10122)

    *Varun Ojha, Ajith Abraham, Vaclav Snasel*

1. **Imbalance Problems in Object Detection: A Review.** arXiv 2019 [paper](https://arxiv.org/abs/1909.00169)

    *Kemal Oksuz, Baris Can Cam, Sinan Kalkan, Emre Akbas*

1. **Machine Learning at the Network Edge: A Survey.** arXiv 2020 [paper](https://arxiv.org/abs/1908.00080)

    *M.G. Sarwar Murshed, Christopher Murphy, Daqing Hou, Nazar Khan, Ganesh Ananthanarayanan, Faraz Hussain*

1. **Adversarial Examples in Modern Machine Learning: A Review.** arXiv 2019 [paper](https://arxiv.org/abs/1911.05268)

    *Rey Reza Wiyatno, Anqi Xu, Ousmane Dia, Archy de Berker*

1. **A Survey on Activation Functions and their relation with Xavier and He Normal Initialization.** arXiv 2020 [paper](https://arxiv.org/abs/2004.06632)

    *Leonid Datta*

1. **Unsupervised Cross-Lingual Representation Learning.** ACL 2019 [paper](https://www.aclweb.org/anthology/P19-4007.pdf)

    *Sebastian Ruder, Anders Søgaard, Ivan Vulic*

#### [Generation](#content)

1. **A Survey on Neural Network Language Models.** arxiv 2019 [paper](https://arxiv.org/abs/1906.03591)

    *Kun Jing, Jungang Xu*

1. **Survey of the State of the Art in Natural Language Generation: Core tasks, applications and evaluation.** Journal of Artificial Intelligence Research 2018 [paper](https://arxiv.org/abs/1703.09902)

    *Albert Gatt, Emiel Krahmer*

1. **A Survey of Paraphrasing and Textual Entailment Methods.** Journal of Artificial Intelligence Research 2010 [paper](https://arxiv.org/abs/0912.3747)

    *Ion Androutsopoulos, Prodromos Malakasiotis*

1. **Recent Advances in SQL Query Generation: A Survey.** CoRR 2020 [paper](https://arxiv.org/abs/2005.07667)

    *Jovan Kalajdjieski, Martina Toshevska, Frosina Stojanovska*

1. **A bit of progress in language modeling.** arxiv 2001 [paper](https://arxiv.org/pdf/cs/0108005)

    *Joshua T. Goodman*

1. **Pre-trained Models for Natural Language Processing: A Survey.** arxiv 2020 [paper](https://arxiv.org/abs/2003.08271)

    *Xipeng Qiu, Tianxiang Sun, Yige Xu, Yunfan Shao, Ning Dai, Xuanjing Huang*

1. **Survey of the State of the Art in Natural Language Generation: Core tasks.** Journal of Artificial Intelligence Research 2018 [paper](https://arxiv.org/abs/1703.09902)

    *Albert Gatt, Emiel Krahmer*

1. **Survey of the State of the Art in Natural Language Generation: Core tasks, applications and evaluation.** arxiv 2017 [paper](https://arxiv.org/abs/1703.09902)

    *Albert Gatt,Emiel Krahmer*

1. **Pre-trained Models for Natural Language Processing : A Survey.** arxiv 2020 [paper](https://arxiv.org/abs/2003.08271)

    *Xipeng Qiu, Tianxiang Sun, Yige Xu, Yunfan Shao, Ning Dai, Xuanjing Huang*

1. **Recent Advances in Neural Question Generation.** arxiv 2019 [paper](https://arxiv.org/abs/1905.08949)

    *Liangming Pan, Wenqiang Lei, Tat-Seng Chua, Min-Yen Kan*

1. **Neural Text Generation: Past, Present and Beyond.** CoRR 2018 [paper](https://arxiv.org/pdf/1803.07133.pdf)

    *Sidi Lu, Yaoming Zhu, Weinan Zhang, Jun Wang, Yong Yu*

#### [Generative Adversarial Networks](#content)

1. **Generative Adversarial Networks: A Survey and Taxonomy.** arxiv 2019 [paper](https://arxiv.org/abs/1906.01529)

    *Zhengwei Wang, Qi She, Tomas E Ward*

1. **生成式对抗网络GAN的研究进展与展望.** 自动化学报 2017 [paper](https://kns.cnki.net/KCMS/detail/detail.aspx?dbcode=CJFQ&dbname=CJFDLAST2017&filename=MOTO201703001&v=MTE2NDViRzRIOWJNckk5RlpZUjhlWDFMdXhZUzdEaDFUM3FUcldNMUZyQ1VSN3FmWU9acUZDamhWcnpKS0NMZlk=)

    *Kunfeng Wang, Gou Chao, Duan Yan-Jie, Lin Yilun*

1. **A Review on Generative Adversarial Networks: Algorithms, Theory, and Applications.** arXiv 2020 [paper](https://arxiv.org/abs/2001.06937)

    *Jie Gui, Zhenan Sun, Yonggang Wen, Dacheng Tao, Jieping Ye*

1. **Generative Adversarial Networks: An Overview.** IEEE Signal Processing Magazine 2018 [paper](https://arxiv.org/abs/1710.07035)

    *Antonia Creswell, Tom White, Vincent Dumoulin, Kai Arulkumaran, Biswa Sengupta, Anil A Bharath*

1. **How Generative Adversarial Nets and its variants Work: An Overview of GAN.** arxiv 2017 [paper](https://arxiv.org/abs/1711.05914v6)

    *Yongjun Hong, Uiwon Hwang, Jaeyoon Yoo, Sungroh Yoon*

1. **Stabilizing Generative Adversarial Networks: A Survey.** arxiv 2019 [paper](https://arxiv.org/abs/1910.00927)

    *Maciej Wiatrak, Stefano V. Albrecht, Andrew Nystrom*

1. **A Survey on Generative Adversarial Networks: Variants, Applications, and Training.** arxiv 2020 [paper](https://arxiv.org/abs/2006.05132)

    *Abdul Jabbar, Xi Li, Bourahla Omar*

1. **Stabilizing Generative Adversarial Network Training: A Survey.** arXiv 2020 [paper](https://arxiv.org/abs/1910.00927)

    *Maciej Wiatrak, Stefano V. Albrecht, Andrew Nystrom*

#### [Graph Neural Networks](#content)

1. **Bridging the Gap between Spatial and Spectral Domains: A Survey on Graph Neural Networks.** arXiv 2020 [paper](https://arxiv.org/abs/2002.11867)

    *Zhiqian Chen, Fanglan Chen, Lei Zhang, Taoran Ji, Kaiqun Fu, Liang Zhao, Feng Chen, Chang-Tien Lu*

1. **Graph Neural Networks Meet Neural-Symbolic Computing: A Survey and Perspective.** arXiv 2020 [paper](https://arxiv.org/abs/2003.00330)

    *Luis C. Lamb, Artur Garcez, Marco Gori, Marcelo Prates, Pedro Avelar, Moshe Vardi*

1. **Tackling Graphical NLP problems with Graph Recurrent Networks.** CoRR 2019 [paper](https://arxiv.org/abs/1907.06142)

    *Linfeng Song*

1. **Graph Neural Networks: A Review of Methods and Applications.** CoRR 2018 [paper](https://arxiv.org/abs/1812.08434)

    *Maosong Sun，Zhengyan Zhang，
Ganqu Cui ，Cheng Yang ，Jie Zhou ，
Zhiyuan Liu*

1. **Introduction to Graph Neural Networks.** IEEE 2020 [paper](https://ieeexplore.ieee.org/document/9048171)

    *Zhiyuan Liu, Jie Zhou*

1. **Adversarial Attack and Defense on Graph Data: A Survey.** CoRR 2018 [paper](https://arxiv.org/abs/1812.10528)

    *Lichao Sun, Ji Wang, Philip S. Yu, Bo Li*

1. **Computational Capabilities of Graph Neural Networks.** IEEE 2009 [paper](https://ieeexplore.ieee.org/document/4703190)

    *Franco Scarselli, Marco Gori, Ah Chung Tsoi, Markus Hagenbuchner, Gabriele Monfardini*

1. **The Graph Neural Network Model.** IEEE 2009 [paper](https://ieeexplore.ieee.org/document/4700287)

    *Franco Scarselli ; Marco Gori ; Ah Chung Tsoi ; Markus Hagenbuchner ; Gabriele Monfardini
*

1. **Benchmarking Graph Neural Networks.** CoRR 2020 [paper](https://arxiv.org/abs/2003.00982)

    *Vijay Prakash Dwivedi, Chaitanya K. Joshi, Thomas Laurent, Yoshua Bengio, Xavier Bresson*

1. **A Survey on The Expressive Power of Graph Neural Networks.** CoRR 2020 [paper](https://arxiv.org/abs/2003.04078)

    *Ryoma Sato*

1. **A Comprehensive Survey on Graph Neural Networks.** arxiv 2019 [paper](https://arxiv.org/abs/1901.00596)

    *Zonghan Wu, Shirui Pan, Fengwen Chen, Guodong Long, Chengqi Zhang, Philip S. Yu*

1. **Foundations and modelling of dynamic networks using Dynamic Graph Neural Networks: A survey.** arxiv 2020 [paper](https://arxiv.org/abs/2005.07496)

    *Joakim Skarding, Bogdan Gabrys, Katarzyna Musial*

1. **Graph embedding techniques, applications, and performance: A survey.** Knowledge Based Systems 2017 [paper](https://arxiv.org/abs/1705.02801)

    *Palash Goyal, Emilio Ferrara*

#### [Information Extraction](#content)

1. **Short Text Topic Modeling Techniques, Applications, and Performance: A Survey.** arxiv 2019 [paper](https://arxiv.org/abs/1904.07695)

    *Jipeng Qiang, Zhenyu Qian, Yun Li, Yunhao Yuan, Xindong Wu*

1. **Extracting Keywords from Open-Ended Business Survey Questions.** Journal of Data Mining and Digital Humanities 2018 [paper](https://arxiv.org/abs/1808.10685)

    *Barbara Mcgillivray、Gard B Jenset 、Dominik Heil*

1. **A Survey of Event Extraction From Text.** IEEE 2019 [paper](http://dblp.uni-trier.de/db/journals/access/access7.html#XiangW19)

    *Wei Xiang, Bang Wang*

1. **Content Selection in Data-to-Text Systems: A Survey.** arxiv 2016 [paper](https://arxiv.org/abs/1610.08375)

    *Dimitra Gkatzia*

1. **A Survey on Temporal Reasoning for Temporal Information Extraction from Text (Extended Abstract).** CoRR 2020 [paper](https://arxiv.org/abs/2005.06527)

    *Artuur Leeuwenberg, Marie-Francine Moens*

1. **A Survey on Open Information Extraction.** COLING/CoRR 2018 [paper](https://arxiv.org/abs/1806.05599)

    *Christina Niklaus, Matthias Cetto, André Freitas, Siegfried Handschuh*

1. **Relation Extraction : A Survey.** CoRR 2017 [paper](https://arxiv.org/abs/1712.05191)

    *Sachin Pawar, Girish K. Palshikar, Pushpak Bhattacharyya*

1. **A Survey of Deep Learning Methods for Relation Extraction.** CoRR 2017 [paper](https://arxiv.org/abs/1705.03645)

    *Shantanu Kumar*

1. **A Survey of Neural Network Techniques for Feature Extraction from Text.** CoRR 2017 [paper](https://arxiv.org/abs/1704.08531)

    *Vineet John*

1. **Automatic Extraction of Causal Relations from Natural Language Texts: A Comprehensive Survey.** CoRR 2016 [paper](https://arxiv.org/abs/1605.07895)

    *Nabiha Asghar*

1. **Neural Information Extraction From Natural Language Text.** Books and Theses 2019 [paper](https://edoc.ub.uni-muenchen.de/24953/)

    *Pankaj Gupta*

1. **More Data, More Relations, More Context and More Openness: A Review and Outlook for Relation Extraction.** arXiv 2020 [paper](https://arxiv.org/abs/2004.03186)

    *Xu Han, Tianyu Gao, Yankai Lin, Hao Peng, Yaoliang Yang, Chaojun Xiao, Zhiyuan Liu, Peng Li, Maosong Sun, Jie Zhou:*

1. **Keyphrase Generation: A Multi-Aspect Survey.** FRUCT 2019 [paper](https://arxiv.org/abs/1910.05059)

    *Erion Çano, Ondřej Bojar*

#### [Information Retrieval and Text Mining](#content)

1. **A survey of methods to ease the development of highly multilingual text mining applications.** language resources and evaluation 2012 [paper](https://arxiv.org/abs/1401.2937)

    *Ralf Steinberger*

1. **深度文本匹配综述.** 计算机学报 2017 [paper](http://cjc.ict.ac.cn/online/onlinepaper/pl-201745181647.pdf)

    *庞亮,兰艳艳,徐君,郭嘉丰,万圣贤,程学旗*

1. **A Brief Survey of Text Mining: Classification, Clustering and Extraction Techniques.** CoRR 2017 [paper](https://arxiv.org/abs/1707.02919)

    *Mehdi Allahyari, Seyed Amin Pouriyeh, Mehdi Assefi, Saied Safaei, Elizabeth D. Trippe, Juan B. Gutierrez, Krys Kochut*

1. **Opinion Mining and Analysis: A survey.** CoRR 2013 [paper](https://arxiv.org/abs/1307.3336)

    *Arti Buche, M. B. Chandak, Akshay Zadgaonkar*

#### [Interpretability and Analysis](#content)

1. **Visual interpretability for deep learning: a survey.** Journal of Zhejiang University Science C 2018 [paper](https://arxiv.org/abs/1802.00614)

    *Quanshi Zhang, Songchun Zhu*

1. **Explainable Artificial Intelligence (XAI): Concepts, Taxonomies, Opportunities and Challenges toward Responsible AI.** Information Fusion 2020 [paper](https://www.arxiv-vanity.com/papers/1910.10045/)

    *Alejandro Barredo Arrieta, Natalia Diazrodriguez, Javier Del Ser, Adrien Bennetot, Siham Tabik, Alberto Barbado, Salvador Garcia, Sergio Gillopez, Daniel Molina, Richard Benjamins, Raja Chatila, Francisco Herrera*

1. **How Generative Adversarial Networks and Their Variants Work: An Overview.** ACM 2017 [paper](https://arxiv.org/abs/1711.05914)

    *Yongjun Hong, Uiwon Hwang, Jaeyoon Yoo, Sungroh Yoon*

1. **Foundations of Explainable Knowledge-Enabled Systems.** Knowledge Graphs for eXplainable Artificial Intelligence: Foundations, Applications and Challenges/CoRR 2020 [paper](https://arxiv.org/abs/2003.07520)

    *Shruthi Chari*

1. **Explainable Reinforcement Learning: A Survey.** CoRR 2020 [paper](https://arxiv.org/abs/2005.06247)

    *Erika Puiutta, Eric M. S. P. Veith*

1. **Build, Compute, Critique, Repeat: Data Analysis with Latent Variable Models.** Annual reviews 2014 [paper](http://pdfs.semanticscholar.org/d74b/5dae099fd87e17fc4167bf4d88d5a9261824.pdf)

    *David M. Blei*

1. **Visualisation of Pareto Front Approximation: A Short Survey and Empirical Comparisons.** CEC 2019 [paper](https://arxiv.org/abs/1903.01768)

    *Huiru Gao, Haifeng Nie, Ke Li*

1. **Survey & Experiment: Towards the Learning Accuracy.** CoRR 2010 [paper](https://arxiv.org/abs/1012.4051)

    *Zeyuan Allen Zhu*

1. **Causal Interpretability for Machine Learning -- Problems, Methods and Evaluation.** Sigkdd Explorations 2020 [paper](https://arxiv.org/abs/2003.03934)

    *Raha Moraffah, Mansooreh Karami, Ruocheng Guo, Adrienne Raglin, Huan Liu*

1. **A Survey Of Methods For Explaining Black Box Models.** ACM 2018 [paper](https://dl.acm.org/doi/10.1145/3236009)

    *Riccardo Guidotti, Anna Monreale, Salvatore Ruggieri, Franco Turini, Fosca Giannotti, Dino Pedreschi*

1. **Language (Technology) is Power: A Critical Survey of "Bias" in NLP.** Association for Computational Linguistics 2020 [paper](https://arxiv.org/abs/2005.14050)

    *Su Lin Blodgett, Solon Barocas, Hal Daumé III, Hanna Wallach*

1. **A Survey of Safety and Trustworthiness of Deep Neural Networks: Verification, Testing, Adversarial Attack and Defence, and Interpretability.** arxiv 2020 [paper](https://arxiv.org/abs/1812.08342)

    *Xiaowei Huang*

1. **Understanding Neural Networks via Feature Visualization: A survey.** arXiv 2019 [paper](https://arxiv.org/abs/1904.08939)

    *Anh Nguyen, Jason Yosinski, Jeff Clune*

#### [Interpretability and Analysis of Models for NLP](#content)

1. **Analyzing and Interpreting Neural Networks for NLP:A Report on the First BlackboxNLP Workshop.** EMNLP 2019 [paper](http://arxiv.org/pdf/1904.04063.pdf)

    *Afra Alishahi, Grzegorz Chrupala, Tal Linzen*

1. **A Primer in BERTology: What we know about how BERT works.** arXiv 2020 [paper](https://arxiv.org/abs/2002.12327)

    *Anna Rogers, Olga Kovaleva, Anna Rumshisky*

1. **Beyond Leaderboards: A survey of methods for revealing weaknesses in Natural Language Inference data and models.** arxiv 2020 [paper](https://arxiv.org/abs/2005.14709)

    *Viktor Schlegel, Goran Nenadic, Riza Batista-Navarro*

1. **Analysis Methods in Neural Language Processing: A Survey.** NACCL/CoRR 2018 [paper](https://arxiv.org/abs/1812.08951)

    *Yonatan Belinkov, James R. Glass*

1. **Visualizing Natural Language Descriptions: A Survey.** ACM Computing Surveys 2016 [paper](https://arxiv.org/abs/1607.00623)

    *Kaveh Hassani, Won-Sook Lee*

1. **When do Word Embeddings Accurately Reflect Surveys on our Beliefs About People?.** ACL 2020 [paper](https://arxiv.org/abs/2004.12043)

    *Kenneth Joseph, Jonathan H. Morgan*

#### [Knowledge Graph](#content)

1. **Knowledge Graph Embedding for Link Prediction and Triplet Classification.** CCKS 2016 [paper](https://link.springer.com/chapter/10.1007%2F978-981-10-3168-7_23)

    *E. Shijia, Shengbin Jia, Yang Xiang, Zilian Ji*

1. **Knowledge Graph Embedding: A Survey of Approaches and Applications.** IEEE 2017 [paper](https://ieeexplore.ieee.org/document/8047276)

    *Quan Wang, Zhendong Mao, Bin Wang, Li Guo*

1. **A Survey on Knowledge Graphs: Representation, Acquisition and Applications.** CoRR 2020 [paper](https://arxiv.org/abs/2002.00388)

    *Shaoxiong Ji, Shirui Pan, Erik Cambria, Pekka Marttinen, Philip S. Yu:*

1. **Knowledge Graphs.** CoRR 2020 [paper](https://arxiv.org/abs/2003.02320)

    *Aidan Hogan, Eva Blomqvist, Michael Cochez, Claudia d'Amato, Gerard de Melo, Claudio Gutierrez, José Emilio Labra Gayo, Sabrina Kirrane, Sebastian Neumaier, Axel Polleres, Roberto Navigli, Axel-Cyrille Ngonga Ngomo, Sabbir M. Rashid, Anisa Rula, Lukas Schmelzeisen, Juan F. Sequeda, Steffen Staab, Antoine Zimmermann*

1. **Simple Embedding for Link Prediction in Knowledge Graphs.** NIPS 2020 [paper](https://arxiv.org/abs/1802.04868)

    *Seyed Mehran Kazemi, David Poole*

1. **Knowledge Graph Embedding for Link Prediction: A Comparative Analysis.** arXiv 2020 [paper](https://arxiv.org/abs/2002.00819)

    *Andrea Rossi, Donatella Firmani, Antonio Matinata, Paolo Merialdo, Denilson Barbosa*

1. **A survey of techniques for constructing chinese knowledge graphs and their applications.** mdpi 2018 [paper](https://www.mdpi.com/2071-1050/10/9/3245/htm)

    *Tianxing Wu, Guilin Qi, Cheng Li, Meng Wang*

#### [Language Grounding to Vision, Robotics and Beyond](#content)

1. **Emotionally-Aware Chatbots: A Survey.** arxiv 2019 [paper](https://arxiv.org/abs/1906.09774)

    *Endang Wahyu Pamungkas*

1. **Trends in Integration of Vision and Language Research: A Survey of Tasks, Datasets, and Methods.** arxiv 2019 [paper](https://arxiv.org/abs/1907.09358)

    *Aditya Mogadala, Marimuthu Kalimuthu, Dietrich Klakow*

#### [Linguistic Theories, Cognitive Modeling and Psycholinguistics](#content)

1. **Modeling Language Variation and Universals: A Survey on Typological Linguistics for Natural Language Processing.** Comput. Linguistics 45(3) 2019 [paper](https://arxiv.org/abs/1807.00914)

    *Edoardo Maria Ponti, Helen O'Horan, Yevgeni Berzak, Ivan Vulic, Roi Reichart, Thierry Poibeau, Ekaterina Shutova, Anna Korhonen*

1. **Survey on the Use of Typological Information in Natural Language Processing.** COLING 2016 [paper](https://arxiv.org/abs/1610.03349)

    *Helen O'Horan, Yevgeni Berzak, Ivan Vulic, Roi Reichart, Anna Korhonen*

#### [Machine Learning for NLP](#content)

1. **Attention in Natural Language Processing.** arxiv 2020 [paper](https://arxiv.org/abs/1902.02181v2)

    *Andrea Galassi, Marco Lippi, Paolo Torroni*

1. **Towards a Robust Deep Neural Network in Texts: A Survey.** arxiv 2020 [paper](https://arxiv.org/abs/1902.07285)

    *Wenqi Wang, Lina Wang, Run Wang, Zhibo Wang, Aoshuang Ye*

1. **Adversarial Attacks on Deep Learning Models in Natural Language Processing: A Survey.** arxiv 2019 [paper](https://arxiv.org/abs/1901.06796)

    *Wei Emma Zhang, Quan Z Sheng, Ahoud Alhazmi, Chenliang Li*

1. **Symbolic, Distributed and Distributional Representations for Natural Language Processing in the Era of Deep Learning: a Survey.** arxiv 2017 [paper](https://arxiv.org/abs/1702.00764)

    *Lorenzo Ferrone, Fabio Massimo Zanzotto*

1. **Neural Graph Embedding Methods for Natural Language Processing.** CoRR 2019 [paper](https://arxiv.org/abs/1911.03042)

    *Shikhar Vashishth*

1. **Adversarial Attacks and Defense on Texts: A Survey.** arxiv 2020 [paper](https://arxiv.org/abs/2005.14108)

    *Aminul Huq, Mst. Tasnim Pervin*

1. **A Survey on Contextual Embeddings.** arxiv 2020 [paper](https://arxiv.org/abs/2003.07278)

    *Qi Liu, Matt J. Kusner, Phil Blunsom*

1. **Natural Language Processing Advancements By Deep Learning: A Survey.** arxiv 2020 [paper](https://arxiv.org/abs/2003.01200)

    *Amirsina Torfi, Rouzbeh A. Shirvani, Yaser Keneshloo, Nader Tavvaf, Edward A. Fox*

1. **Word Embeddings: A Survey.** arxiv 2019 [paper](https://arxiv.org/abs/1901.09069)

    *Felipe Almeida, Geraldo Xexéo*

1. **An Introductory Survey on Attention Mechanisms in NLP Problems.** IntelliSys 2019 [paper](https://arxiv.org/abs/1811.05544)

    *Dichao Hu*

1. **A Survey of the Usages of Deep Learning in Natural Language Processing.** arxiv 2018 [paper](https://arxiv.org/abs/1807.10854)

    *Daniel W. Otter, Julian R. Medina, Jugal K. Kalita*

1. **From Word to Sense Embeddings: A Survey on Vector Representations of Meaning.** Journal of Artificial Intelligence Research 2018 [paper](https://arxiv.org/abs/1805.04032)

    *Jose Camachocollados, Mohammad Taher Pilehvar*

1. **A Survey Of Cross-lingual Word Embedding Models.** Journal of Artificial Intelligence Research 2019 [paper](https://arxiv.org/abs/1706.04902)

    *Sebastian Ruder, Ivan Vulic, Anders Sogaard*

1. **A Primer on Neural Network Models for Natural Language Processing.** arxiv 2015 [paper](https://arxiv.org/abs/1510.00726)

    *Yoav Goldberg*

1. **Recent Trends in Deep Learning Based Natural Language Processing.** arxiv 2017 [paper](https://arxiv.org/abs/1708.02709)

    *Tom Young, Devamanyu Hazarika, Soujanya Poria, Erik Cambria*

1. **Neural Network Models for Paraphrase Identification, Semantic Textual Similarity, Natural Language Inference, and Question Answering.** COLING/CoRR 2018 [paper](https://arxiv.org/pdf/1806.04330.pdf)

    *Wuwei Lan,Wei Xu*

1. **A comprehensive survey of mostly textual document segmentation algorithms since 2008.** Pattern Recognition 2017 [paper](https://www.sciencedirect.com/science/article/abs/pii/S0031320316303399)

    *Sébastien Eskenazi, Petra Gomez-Krämer, Jean-Marc Ogier*

1. **A Survey of Neural Networks and Formal Languages.** CoRR 2020 [paper](https://arxiv.org/abs/2006.01338)

    *Joshua Ackerman, George Cybenko*

1. **Tutorial on Variational Autoencoders.** CoRR 2016 [paper](https://arxiv.org/pdf/1606.05908.pdf)

    *Carl Doersch*

1. **From static to dynamic word representations: a survey.** IJMLC 2020 [paper](https://link.springer.com/article/10.1007/s13042-020-01069-8)

    *Yuxuan Wang, Yutai Hou, Wanxiang Che, Ting Liu*

#### [Machine Translation](#content)

1. **A Survey of Deep Learning Techniques for Neural Machine Translation.** arxiv 2020 [paper](https://arxiv.org/abs/2002.07526)

    *Shuoheng Yang, Yuxin Wang, Xiaowen Chu*

1. **A Survey on Document-level Machine Translation: Methods and Evaluation.** arxiv 2019 [paper](https://arxiv.org/abs/1912.08494)

    *Sameen Maruf, Fahimeh Saleh, Gholamreza Haffari*

1. **The Query Translation Landscape: a Survey.** arxiv 2019 [paper](https://arxiv.org/abs/1910.03118)

    *Mohamed Nadjib Mami, Damien Graux, Harsh Thakkar, Simon Scerri, Soren Auer, Jens Lehmann*

1. **A Survey of Methods to Leverage Monolingual Data in Low-resource Neural Machine Translation.** arxiv 2019 [paper](https://arxiv.org/abs/1910.00373)

    *Ilshat Gibadullin, Aidar Valeev, Albina Khusainova, Adil Mehmood Khan*

1. **Machine Translation using Semantic Web Technologies: A Survey.** Journal of Web Semantics 2018 [paper](https://arxiv.org/abs/1711.09476)

    *Diego Moussallem, Matthias Wauer, Axelcyrille Ngonga Ngomo*

1. **Machine-Translation History and Evolution: Survey for Arabic-English Translations.** arxiv 2017 [paper](https://arxiv.org/abs/1709.04685)

    *Nabeel T. Alsohybe, Neama Abdulaziz Dahan, Fadl Mutaher Baalwi*

1. **Machine Translation Approaches and Survey for Indian Languages.** arxiv 2017 [paper](https://arxiv.org/abs/1701.04290)

    *Nadeem Jadoon Khan, Waqas Anwar, Nadir Durrani*

1. **Machine Translation Evaluation Resources and Methods: A Survey.** arxiv 2018 [paper](https://arxiv.org/abs/1605.04515)

    *Lifeng Han*

1. **A Survey of Word Reordering in Statistical Machine Translation: Computational Models and Language Phenomena.** Comput. Linguistics 2016 [paper](https://arxiv.org/abs/1502.04938)

    *Arianna Bisazza, Marcello Federico*

1. **A Comprehensive Survey of Multilingual Neural Machine Translation.** arxiv 2020 [paper](https://arxiv.org/abs/2001.01115)

    *Raj Dabre, Chenhui Chu, Anoop Kunchukuttan*

1. **A Brief Survey of Multilingual Neural Machine Translation.** arxiv 2019 [paper](https://arxiv.org/abs/1905.05395)

    *Raj Dabre, Chenhui Chu, Anoop Kunchukuttan*

1. **Neural Machine Translation and Sequence-to-Sequence Models: A Tutorial.** arxiv 2017 [paper](https://arxiv.org/abs/1703.01619)

    *Graham Neubig*

1. **Neural Machine Translation: Challenges, Progress and Future.** arxiv 2020 [paper](https://arxiv.org/abs/2004.05809)

    *Jiajun Zhang, Chengqing Zong*

1. **Neural Machine Translation: A Review.** arxiv 2019 [paper](https://arxiv.org/abs/1912.02047)

    *Felix Stahlberg*

1. **A Survey of Multilingual Neural Machine Translation.** arXiv 2020 [paper](https://arxiv.org/abs/1905.05395)

    *Raj Dabre, Chenhui Chu, Anoop Kunchukuttan*

1. **A Survey of Domain Adaptation for Neural Machine Translation.** COLING 2018 [paper](https://arxiv.org/abs/1806.00258)

    *Chenhui Chu, Rui Wang*

#### [Meta Learning](#content)

1. **A Comprehensive Overview and Survey of Recent Advances in Meta-Learning.** arxiv 2020 [paper](https://arxiv.org/abs/2004.11149)

    *Huimin Peng*

1. **Meta-Learning in Neural Networks: A Survey.** arxiv 2020 [paper](https://arxiv.org/abs/2004.05439)

    *Timothy M. Hospedales, Antreas Antoniou, Paul Micaelli, Amos J. Storkey*

1. **Meta-Learning: A Survey.** CoRR 2018 [paper](https://arxiv.org/abs/1810.03548)

    *Joaquin Vanschoren*

#### [Metric Learning](#content)

1. **A Tutorial on Distance Metric Learning: Mathematical Foundations, Algorithms and Experiments.** arxiv 2018 [paper](https://arxiv.org/abs/1812.05944)

    *Juan Luis Suárez, Salvador García, Francisco Herrera*

1. **A Survey on Metric Learning for Feature Vectors and Structured Data.** arxiv 2013 [paper](https://arxiv.org/abs/1306.6709)

    *Aurélien Bellet, Amaury Habrard, Marc Sebban*

#### [ML Applications](#content)

1. **A Survey on Deep Learning based Brain-Computer Interface: Recent Advances and New Frontiers.** arXiv 2019 [paper](https://arxiv.org/abs/1905.04149v1)

    *Xiang Zhang, Lina Yao, Xianzhi Wang, Jessica J M Monaghan, David Mcalpine, Yu Zhang*

1. **Machine Learning Aided Static Malware Analysis: A Survey and Tutorial.** arxiv 2018 [paper](https://arxiv.org/abs/1808.01201)

    *Andrii Shalaginov, Sergii Banin, Ali Dehghantanha, Katrin Franke*

1. **Artificial Neural Networks-Based Machine Learning for Wireless Networks: A Tutorial.** IEEE Communications Surveys & Tutorials 2019 [paper](https://ieeexplore.ieee.org/document/8755300)

    *Mingzhe Chen, Ursula Challita, Walid Saad, Changchuan Yin, Mérouane Debbah*

1. **The Creation and Detection of Deepfakes:A Survey.** arXiv 2020 [paper](https://arxiv.org/abs/2004.11138v1)

    *Yisroel Mirsky, Wenke Lee*

1. **Machine Learning for Survival Analysis: A Survey.** CoRR 2017 [paper](https://arxiv.org/abs/1708.04649)

    *Ping Wang, Yan Li, Chandan K. Reddy*

1. **A Survey of Machine Learning Methods and Challenges for Windows Malware Classification.** arxiv 2020 [paper](https://arxiv.org/abs/2006.09271)

    *Edward Raff, Charles Nicholas*

1. **A survey on deep hashing for image retrieval.** arxiv 2020 [paper](https://arxiv.org/abs/2006.05627)

    *Xiaopeng Zhang*

1. **A Survey of Adaptive Resonance Theory Neural Network Models for Engineering Applications.** Neural Networks 2019 [paper](https://arxiv.org/abs/1905.11437)

    *Leonardo Enzo Brito da Silva, Islam Elnabarawy, Donald C. Wunsch II*

1. **How Developers Iterate on Machine Learning Workflows -- A Survey of the Applied Machine Learning Literature.** arxiv 2018 [paper](https://arxiv.org/abs/1803.10311)

    *Doris Xin, Litian Ma, Shuchen Song, Aditya G. Parameswaran*

1. **Malaria Likelihood Prediction By Effectively Surveying Households Using Deep Reinforcement Learning.** arxiv 2017 [paper](https://arxiv.org/abs/1711.09223)

    *Pranav Rajpurkar, Vinaya Polamreddi, Anusha Balakrishnan*

1. **A Survey on Deep Learning in Medical Image Analysis.** Medical Image Analysis 2017 [paper](https://arxiv.org/abs/1702.05747)

    *Geert J S Litjens, Thijs Kooi, Babak Ehteshami Bejnordi, Arnaud A A Setio, Francesco Ciompi, Mohsen Ghafoorian, Jeroen A W M Van Der Laak, Bram Van Ginneken, Clara I Sanchez*

1. **AI and Holistic Review: Informing Human Reading in College Admissions.** arXiv 2019 [paper](https://arxiv.org/abs/1912.09318)

    *AJ Alvero, Noah Arthurs, anthony lising antonio, Benjamin W. Domingue, Ben Gebre-Medhin, Sonia Giebel, Mitchell L. Stevens*

#### [Model Compression and Acceleration](#content)

1. **Pruning Algorithms to Accelerate Convolutional Neural Networks for Edge Applications: A Survey.** arxiv 2020 [paper](https://arxiv.org/abs/2005.04275)

    *Jiayi Liu, Samarth Tripathi, Unmesh Kurup, Mohak Shah*

1. **A Survey on Methods and Theories of Quantized Neural Networks.** CoRR 2018 [paper](https://arxiv.org/abs/1808.04752)

    *Yunhui Guo*

1. **Knowledge Distillation: A Survey.** arxiv 2020 [paper](https://arxiv.org/abs/2006.05525)

    *Jianping Gou, Baosheng Yu, Stephen John Maybank, Dacheng Tao*

1. **An Overview of Neural Network Compression.** arxiv 2020 [paper](https://arxiv.org/abs/2006.03669)

    *J O Neill*

1. **A Survey of Model Compression and Acceleration for Deep Neural Networks.** arxiv 2017 [paper](https://arxiv.org/abs/1710.09282)

    *Yu Cheng, Duo Wang, Pan Zhou, Tao Zhang*

#### [Multi-Task and Multi-View Learning](#content)

1. **A Survey on Multi-Task Learning.** CoRR 2017 [paper](https://arxiv.org/abs/1707.08114)

    *Yu Zhang, Qiang Yang*

1. **An Overview of Multi-Task Learning in Deep Neural Networks.** arXiv 2017 [paper](https://arxiv.org/abs/1706.05098)

    *Sebastian Ruder*

1. **An overview of multi-task learning.** National Science Review 2018 [paper](https://academic.oup.com/nsr/article/5/1/30/4101432)

    *Yu Zhang, Qiang Yang*

1. **A Brief Review on Multi-Task Learning.** Multimedia Tools and Applications 2018 [paper](https://www.researchgate.net/publication/326903979_A_brief_review_on_multi-task_learning)

    *Kimhan Thung, Chong Yaw Wee*

1. **Revisiting Multi-Task Learning in the Deep Learning Era.** arxiv 2020 [paper](https://arxiv.org/abs/2004.13379)

    *Simon Vandenhende, Stamatios Georgoulis, Marc Proesmans, Dengxin Dai, Luc Van Gool*

1. **Revisiting Multi-Task Learning in the Deep Learning Era.** arxiv 2020 [paper](https://arxiv.org/abs/2004.13379)

    *Simon Vandenhende, Stamatios Georgoulis, Marc Proesmans, Dengxin Dai, Luc Van Gool*

1. **A Survey on Multi-view Learning.** CoRR 2013 [paper](https://arxiv.org/abs/1304.5634)

    *Chang Xu, Dacheng Tao, Chao Xu*

#### [Natural Language Processing](#content)

1. **Natural Language Processing - A Survey.** arxiv 2012 [paper](https://arxiv.org/abs/1209.6238)

    *Kevin Mote*

1. **中文信息处理发展报告.** 中国中文信息学会 2016 [paper](http://cips-upload.bj.bcebos.com/cips2016.pdf)

    *中国中文信息学会*

1. **Jumping NLP curves: A review of natural language processing research.** IEEE 2014 [paper](http://krchowdhary.com/ai/ai14/lects/nlp-research-com-intlg-ieee.pdf)

    *Erik Cambria ; Bebo White*

1. **Natural Language Processing: State of The Art, Current Trends and Challenges.** arxiv 2017 [paper](https://arxiv.org/abs/1708.05148)

    *Diksha Khurana, Aditya Koli, Kiran Khatter, Sukhdev Singh*

1. **A Survey and Classification of Controlled Natural Languages.** Comput. Linguistics 2014 [paper](https://arxiv.org/abs/1507.01701)

    *Tobias Kuhn*

#### [NER](#content)

1. **A survey of named entity recognition and classification.** Lingvisticæ Investigationes 2007 [paper](https://nlp.cs.nyu.edu/sekine/papers/li07.pdf)

    *David Nadeau, Satoshi Sekine*

1. **Design Challenges and Misconceptions in Neural Sequence Labeling.** COLING 2018 [paper](https://arxiv.org/abs/1806.04470)

    *Jie Yang, Shuailong Liang, Yue Zhang*

1. **Neural Entity Linking: A Survey of Models based on Deep Learning.** CoRR 2020 [paper](https://arxiv.org/abs/2006.00575)

    *Özge Sevgili, Artem Shelmanov, Mikhail Arkhipov, Alexander Panchenko, Chris Biemann*

1. **A Survey on Recent Advances in Named Entity Recognition from Deep Learning models.** COLING/CoRR 2019 [paper](https://arxiv.org/abs/1910.11470)

    *Vikas Yadav，Steven Bethard*

1. **A Survey on Deep Learning for Named Entity Recognition.** CoRR 2018 [paper](https://arxiv.org/abs/1812.09449)

    *Jing Li, Aixin Sun, Jianglei Han, Chenliang Li*

1. **A Survey of Named Entity Recognition in Assamese and other Indian Languages.** CoRR 2014 [paper](https://arxiv.org/abs/1407.2918)

    *Gitimoni Talukdar, Pranjal Protim Borah, Arup Baruah*

#### [NLP Applications](#content)

1. **A Comprehensive Survey of Grammar Error Correction.** arxiv 2020 [paper](https://arxiv.org/abs/2005.06600)

    *Yu Wang, Yuelin Wang, Jie Liu, Zhuo Liu*

1. **Spam Review Detection with Graph Convolutional Networks.** CIKM 2019 [paper](https://arxiv.org/abs/1908.10679)

    *Ao Li, Zhou Qin, Runshi Liu, Yiqun Yang, Dong Li*

1. **Image Captioning based on Deep Learning Methods: A Survey.** CoRR 2019 [paper](https://arxiv.org/abs/1905.08110)

    *Yiyu Wang, Jungang Xu, Yingfei Sun, Ben He*

1. **Text Recognition in the Wild: A Survey.** arxiv 2020 [paper](https://arxiv.org/abs/2005.03492)

    *Xiaoxue Chen, Lianwen Jin, Yuanzhi Zhu, Canjie Luo, Tianwei Wang*

1. **Extraction and Analysis of Fictional Character Networks: A Survey.** {ACM} Comput. Surv. 2019 [paper](https://arxiv.org/abs/1907.02704)

    *Xavier Bost (LIA), Vincent Labatut (LIA)*

1. **Fake News Detection using Stance Classification: A Survey.** arxiv 2019 [paper](https://arxiv.org/abs/1907.00181)

    *Anders Edelbo Lillie, Emil Refsgaard Middelboe*

1. **Survey of Text-based Epidemic Intelligence: A Computational Linguistic Perspective.** {ACM} Comput. Surv. 2019 [paper](https://arxiv.org/abs/1903.05801)

    *Aditya Joshi, Sarvnaz Karimi, Ross Sparks, Cecile Paris, C Raina MacIntyre*

1. **SECNLP: A Survey of Embeddings in Clinical Natural Language Processing.** J. Biomed. Informatics 2019 [paper](https://arxiv.org/abs/1903.01039)

    *Kalyan KS, S Sangeetha*

1. **Fake News: A Survey of Research, Detection Methods, and Opportunities.** arxiv 2018 [paper](https://arxiv.org/abs/1812.00315)

    *Xinyi Zhou, Reza Zafarani*

1. **A Survey on Natural Language Processing for Fake News Detection.** LREC 2020 [paper](https://arxiv.org/abs/1811.00770)

    *Ray Oshikawa, Jing Qian, William Yang Wang*

1. **A Short Survey of Biomedical Relation Extraction Techniques.** arxiv 2017 [paper](https://arxiv.org/abs/1707.05850)

    *Elham Shahab*

1. **Automatic Language Identification in Texts: A Survey.** J. Artif. Intell. Res. 65 2019 [paper](https://arxiv.org/abs/1804.08186)

    *Tommi Jauhiainen*

1. **Text Detection and Recognition in the Wild: A Review.** arXiv 2020 [paper](https://arxiv.org/abs/2006.04305)

    *Zobeir Raisi, Mohamed A. Naiel, Paul Fieguth, Steven Wardell, John Zelek*

1. **Disinformation Detection: A review of linguistic feature selection and classification models in news veracity assessments.** arXiv 2019 [paper](https://arxiv.org/abs/1910.12073)

    *Jillian Tompkins*

#### [Online Learning](#content)

1. **Preference-based Online Learning with Dueling Bandits: A Survey.** CoRR 2018 [paper](https://arxiv.org/abs/1807.11398)

    *Robert Busa-Fekete, Eyke Hüllermeier, Adil El Mesaoudi-Paul*

1. **Online Learning: A Comprehensive Survey.** CoRR 2018 [paper](https://arxiv.org/abs/1802.02871)

    *Steven C.H. Hoi, Doyen Sahoo, Jing Lu, Peilin Zhao*

1. **A Survey of Algorithms and Analysis for Adaptive Online Learning.** Journal of Machine Learning Research 2017 [paper](https://arxiv.org/abs/1403.3465)

    *H. Brendan McMahan*

#### [Optimization](#content)

1. **Convex Optimization Overview.** IEEE Signal Processing Magazine 2008 [paper](http://citeseerx.ist.psu.edu/viewdoc/summary?doi=10.1.1.142.6470)

    *Nikos Komodakis*

1. **Optimization for deep learning: theory and algorithms.** arxiv 2019 [paper](https://arxiv.org/abs/1912.08957)

    *Ruoyu Sun*

1. **A Systematic and Meta-analysis Survey of Whale Optimization Algorithm.** Comput. Intell. Neurosci. 2019 [paper](https://arxiv.org/abs/1903.08763)

    *Hardi M. Mohammed, Shahla U. Umar, Tarik A. Rashid*

1. **A Survey of Optimization Methods from a Machine Learning Perspective.** arxiv 2019 [paper](https://arxiv.org/abs/1906.06821)

    *Shiliang Sun, Zehui Cao, Han Zhu, Jing Zhao*

1. **Optimization Models for Machine Learning: A Survey.** arxiv 2019 [paper](https://arxiv.org/abs/1901.05331)

    *Claudio Gambella, Bissan Ghaddar, Joe Naoum-Sawaya*

1. **Particle Swarm Optimization: A survey of historical and recent developments with hybridization perspectives.** Machine Learning and Knowledge Extraction 2019 [paper](https://arxiv.org/abs/1804.05319)

    *Saptarshi Sengupta, Sanchita Basak, Richard Alan Peters II*

1. **Gradient Boosting Machine: A Survey.** arXiv 2019 [paper](https://arxiv.org/abs/1908.06951)

    *Zhiyuan He, Danchen Lin, Thomas Lau, Mike Wu*

1. **An overview of gradient descent optimization algorithms.** arXiv 2017 [paper](https://arxiv.org/abs/1609.04747)

    *Sebastian Ruder*

#### [Question Answering](#content)

1. **Core techniques of question answering systems over knowledge bases: a survey.** SpringerLink 2017 [paper](https://link.springer.com/article/10.1007/s10115-017-1100-y)

    *Dennis Diefenbach, Vanessa Lopez, Kamal Singh & Pierre Maret *

1. **Introduction to Neural Network based Approaches for Question Answering over Knowledge Graphs.** arxiv 2019 [paper](https://arxiv.org/abs/1907.09361)

    *Nilesh Chakraborty,Denis Lukovnikov,Gaurav Maheshwari,Priyansh Trivedi,Jens Lehmann,Asja Fischer:*

1. **Tutorial on Answering Questions about Images with Deep Learning.** arxiv 2016 [paper](https://arxiv.org/abs/1610.01076)

    *Mateusz Malinowski, Mario Fritz:*

1. **Text-based Question Answering from Information Retrieval and Deep Neural Network Perspectives: A Survey.** arxiv 2020 [paper](https://arxiv.org/abs/2002.06612)

    *Zahra Abbasiyantaeb, Saeedeh Momtazi:*

1. **A Survey on Why-Type Question Answering Systems.** arxiv 2019 [paper](https://arxiv.org/abs/1911.04879)

    *Manvi Breja, Sanjay Kumar Jain:*

1. **Visual Question Answering using Deep Learning: A Survey and Performance Analysis.** arxiv 2019 [paper](https://arxiv.org/abs/1909.01860)

    *Yash Srivastava, Vaishnav Murali, Shiv Ram Dubey, Snehasis Mukherjee:*

1. **Survey of Visual Question Answering: Datasets and Techniques.** arxiv 2017 [paper](https://arxiv.org/abs/1705.03865)

    *Akshay Kumar Gupta*

1. **A survey on question answering technology from an information retrieval perspective.** Information Sciences 2011 [paper](https://www.sciencedirect.com/science/article/pii/S0020025511003860)

    *Oleksandr Kolomiyets, Marie-Francine Moens:*

#### [Reading Comprehension](#content)

1. **A Survey on Machine Reading Comprehension Systems.** arxiv 2020 [paper](https://arxiv.org/abs/2001.01582)

    *Razieh Baradaran, Razieh Ghiasi, Hossein Amirkhani:*

1. **A Survey on Neural Machine Reading Comprehension.** arxiv 2019 [paper](https://arxiv.org/abs/1906.03824)

    *Boyu Qiu, Xu Chen, Jungang Xu, Yingfei Sun:*

1. **Neural Reading Comprehension And Beyond.**  2018 [paper](https://stacks.stanford.edu/file/druid:gd576xb1833/thesis-augmented.pdf)

    *Danqi Chen*

1. **Neural Machine Reading Comprehension: Methods and Trends.** arxiv 2019 [paper](https://arxiv.org/abs/1907.01118)

    *Shanshan Liu, Xin Zhang, Sheng Zhang, Hui Wang, Weiming Zhang:*

1. **Machine Reading Comprehension: The Role of Contextualized Language Models and Beyond.** arxiv 2020 [paper](https://arxiv.org/abs/2005.06249)

    *Zhuosheng Zhang，Hai Zhao，Rui Wang*

1. **Machine Reading Comprehension: a Literature Review.** arxiv 2019 [paper](https://arxiv.org/abs/1907.01686)

    *Xin Zhang, An Yang, Sujian Li, Yizhong Wang*

#### [Recommender Systems](#content)

1. **Deep Learning based Recommender System: A Survey and New Perspectives.** ACM 2019 [paper](https://arxiv.org/abs/1707.07435)

    *Shuai Zhang, Lina Yao, Aixin Sun, Yi Tay:*

1. **Use of Deep Learning in Modern Recommendation System: A Summary of Recent Works.** arxiv 2017 [paper](https://arxiv.org/abs/1712.07525)

    *Ayush Singhal, Pradeep Sinha, Rakesh Pant:*

1. **Deep learning based recommender system:a survey and new perspectives.** ACM 2019 [paper](https://arxiv.org/abs/1707.07435)

    *Shuai Zhang, Lina Yao, Aixin Sun, Yi Tay*

1. **Sequence-Aware Recommender Systems.** ACM 2018 [paper](https://arxiv.org/abs/1802.08452)

    *Massimo Quadrana,Paolo Cremonesi,Dietmar Jannach*

1. **Cross Domain Recommender Systems: A Systematic Literature Review.** ACM 2017 [paper](https://dl.acm.org/doi/10.1145/3073565)

    *Muhammad Murad Khan,Roliana Ibrahim,Imran Ghani*

1. **Explainable Recommendation: A Survey and New Perspectives.** arXiv 2020 [paper](https://arxiv.org/abs/1804.11192)

    *Yongfeng Zhang, Xu Chen:*

1. **A review on deep learning for recommender systems: challenges and remedies.** springerlink期刊 2019 [paper](https://link.springer.com/article/10.1007/s10462-018-9654-y)

    *Zeynep Batmaz, Ali Yurekli, Alper Bilge, Cihan Kaleli:*

1. **Adversarial Machine Learning in Recommender Systems:State of the art and Challenges.** arXiv 2020 [paper](https://arxiv.org/abs/2005.10322)

    *Yashar Deldjoo, Tommaso Di Noia, Felice Antonio Merra*

1. **A Survey on Knowledge Graph-Based Recommender Systems.** arxiv 2020 [paper](https://arxiv.org/abs/2003.00911)

    *Qingyu Guo, Fuzhen Zhuang, Chuan Qin, Hengshu Zhu, Xing Xie, Hui Xiong, Qing He*

1. **Deep Learning on Knowledge Graph for Recommender System: A Survey.** arXiv 2020 [paper](https://arxiv.org/abs/2004.00387)

    *Yang Gao, Yi-Fan Li, Yu Lin, Hang Gao, Latifur Khan*

#### [Resources and Evaluation](#content)

1. **A Survey of Word Embeddings Evaluation Methods.** arxiv 2018 [paper](https://arxiv.org/abs/1801.09536)

    *Amir Bakarov*

1. **Measuring Sentences Similarity: A Survey.** arxiv 2019 [paper](https://arxiv.org/abs/1910.03940)

    *Mamdouh Farouk:*

1. **Survey on Evaluation Methods for Dialogue Systems.** arxiv 2019 [paper](https://arxiv.org/abs/1905.04071)

    *Jan Deriu, Álvaro Rodrigo, Arantxa Otegi, Guillermo Echegoyen, Sophie Rosset, Eneko Agirre, Mark Cieliebak:*

1. **TutorialBank: A Manually-Collected Corpus for Prerequisite Chains, Survey Extraction and Resource Recommendation.** ACL 2018 [paper](https://arxiv.org/abs/1805.04617)

    *Alexander R. Fabbri, Irene Li, Prawat Trairatvorakul, Yijiao He, Wei Tai Ting, Robert Tung, Caitlin Westerfield, Dragomir R. Radev:*

1. **A Short Survey on Sense-Annotated Corpora.** LREC 2020 [paper](https://arxiv.org/abs/1802.04744)

    *Tommaso Pasini, José Camacho-Collados:*

1. **Critical Survey of the Freely Available Arabic Corpora.** arxiv 2017 [paper](https://arxiv.org/abs/1702.07835)

    *Wajdi Zaghouani:*

1. **A Survey of Current Datasets for Vision and Language Research.** EMNLP 2015 [paper](https://arxiv.org/abs/1506.06833)

    *Francis Ferraro, Nasrin Mostafazadeh, Ting-Hao (Kenneth) Huang, Lucy Vanderwende, Jacob Devlin, Michel Galley, Margaret Mitchell:*

1. **Distributional Measures of Semantic Distance: A Survey.** arxiv 2012 [paper](https://arxiv.org/abs/1203.1858)

    *Saif Mohammad, Graeme Hirst:*

1. **Survey on Publicly Available Sinhala Natural Language Processing Tools and Research.** arxiv 2019 [paper](https://arxiv.org/abs/1906.02358)

    *Nisansa de Silva*

1. **Recent Advances in Natural Language Inference: A Survey of Benchmarks, Resources, and Approaches.** arxiv 2020 [paper](https://arxiv.org/abs/1904.01172)

    *Shane Storks, Qiaozi Gao, Joyce Y. Chai*

#### [Semantics](#content)

1. **Survey of Computational Approaches to Lexical Semantic Change.** arxiv 2019 [paper](https://arxiv.org/abs/1811.06278)

    *Nina Tahmasebi, Lars Borin, Adam Jatowt*

1. **Diachronic word embeddings and semantic shifts: a survey.** COLING 2018 [paper](https://arxiv.org/abs/1806.03537)

    *Andrey Kutuzov, Lilja Øvrelid, Terrence Szymanski, Erik Velldal*

1. **Word sense disambiguation: a survey.** arxiv 2015 [paper](https://arxiv.org/abs/1508.01346)

    *Alok Ranjan Pal, Diganta Saha*

1. **Semantics, Modelling, and the Problem of Representation of Meaning -- a Brief Survey of Recent Literature.** arxiv 2014 [paper](https://arxiv.org/abs/1402.7265)

    *Yarin Gal*

#### [Semi-Supervised and Unsupervised Learning](#content)

1. **Improvability Through Semi-Supervised Learning: A Survey of Theoretical Results.** arxiv 2019 [paper](https://arxiv.org/abs/1908.09574)

    *Alexander Mey, Marco Loog*

1. **A Survey on Semi-Supervised Learning Techniques.** CoRR 2014 [paper](https://arxiv.org/abs/1402.4645)

    *V. Jothi Prakash, Dr. L.M. Nithya*

1. **A brief introduction to weakly supervised learning.** arxiv 2018 [paper](https://cs.nju.edu.cn/_upload/tpl/01/0b/267/template267/zhouzh.files/publication/nsr18.pdf)

    *Zhihua Zhou*

1. **Learning from positive and unlabeled data: a survey.** Machine Learning 2020 [paper](https://arxiv.org/abs/1811.04820)

    *Jessa Bekker, Jesse Davis*

#### [Sentiment Analysis, Stylistic Analysis, and Argument Mining](#content)

1. **Semantic search on text and knowledge bases.** Foundations and trends in information retrieval 2016 [paper](https://www.researchgate.net/profile/Hannah_Bast/publication/304364705_Semantic_Search_on_Text_and_Knowledge_Bases/links/594a4734aca2723195de48df/Semantic-Search-on-Text-and-Knowledge-Bases.pdf)

    *Bast, Hannah，Buchhold, Bjoern，Haussmann, Elmar*

1. **Evolution of Semantic Similarity -- A Survey.** arxiv 2020 [paper](https://arxiv.org/abs/2004.13820)

    *Dhivya Chandrasekaran, Vijay Mago*

1. **A Comprehensive Survey on Aspect Based Sentiment Analysis.** arxiv 2020 [paper](https://arxiv.org/abs/2006.04611)

    *Kaustubh Yadav*

1. **Word Embeddings for Sentiment Analysis: A Comprehensive Empirical Survey.** arxiv 2019 [paper](https://arxiv.org/abs/1902.00753)

    *Erion Çano, Maurizio Morisio*

1. **Sentiment Analysis of Czech Texts: An Algorithmic Survey.** ICAART 2019 [paper](https://arxiv.org/abs/1901.02780)

    *Erion Çano, Ondřej Bojar*

1. **Sentiment analysis for Arabic language: A brief survey of approaches and techniques.** arxiv 2018 [paper](https://arxiv.org/abs/1809.02782)

    *Mo'ath Alrefai, Hossam Faris, Ibrahim Aljarah*

1. **A Survey on Sentiment and Emotion Analysis for Computational Literary Studies.** arxiv 2018 [paper](https://arxiv.org/abs/1808.03137)

    *Evgeny Kim, Roman Klinger*

1. **Deep Learning for Sentiment Analysis : A Survey.** Wiley Interdisciplinary Reviews-Data Mining and Knowledge Discovery 2018 [paper](https://arxiv.org/abs/1801.07883)

    *Lei Zhang, Shuai Wang, Bing Liu*

1. **Sentiment Analysis of Twitter Data: A Survey of Techniques.** arxiv 2016 [paper](https://arxiv.org/abs/1601.06971)

    *Vishal.A.Kharde, Prof. Sheetal.Sonawane*

1. **Sentiment/Subjectivity Analysis Survey for Languages other than English.** Social Netw. Analys. Mining 2016 [paper](https://arxiv.org/abs/1601.00087)

    *Mohammed Korayem, Khalifeh Aljadda, David Crandall*

1. **Deep Learning for Aspect-Level Sentiment Classification: Survey, Vision, and Challenges.** IEEE 2019 [paper](https://ieeexplore.ieee.org/document/8726353)

    *Jie Zhou, Jimmy Xiangji Huang, Qin Chen, Qinmin Vivian Hu, Tingting Wang, Liang He*

1. **Sentiment Analysis on YouTube: A Brief Survey.** arxiv 2015 [paper](https://arxiv.org/abs/1511.09142)

    *Muhammad Zubair Asghar, Shakeel Ahmad, Afsana Marwat, Fazal Masud Kundi*

1. **Deep learning for sentiment analysis: A survey.** arxiv 2018 [paper](https://arxiv.org/abs/1801.07883)

    *Lei Zhang, Shuai Wang, Bing Liu*

1. **Beneath the Tip of the Iceberg: Current Challenges and New Directions in Sentiment Analysis Research.** arXiv 2020 [paper](https://arxiv.org/abs/2005.00357v1)

    *Soujanya Poria, Devamanyu Hazarika, Navonil Majumder, Rada Mihalcea*

#### [Speech and Multimodality](#content)

1. **A Survey of Recent DNN Architectures on the TIMIT Phone Recognition Task.** TSD 2018 [paper](https://arxiv.org/abs/1806.07974)

    *Josef Michálek, Jan Vanek*

1. **Automatic Description Generation from Images: A Survey of Models, Datasets, and Evaluation Measures.** IJCAI 2017 [paper](https://arxiv.org/abs/1601.03896)

    *Raffaella Bernardi, Ruket Çakici, Desmond Elliott, Aykut Erdem, Erkut Erdem, Nazli Ikizler-Cinbis, Frank Keller, Adrian Muscat, Barbara Plank*

1. **A Survey and Taxonomy of Adversarial Neural Networks for Text-to-Image Synthesis.** CoRR 2019 [paper](https://arxiv.org/abs/1910.09399)

    *Jorge Agnese, Jonathan Herrera, Haicheng Tao, Xingquan Zhu*

1. **A Survey of Voice Translation Methodologies - Acoustic Dialect Decoder.** arxiv 2016 [paper](https://arxiv.org/abs/1610.03934)

    *Hans Krupakar, Keerthika Rajvel, Bharathi B, Angel Deborah S, Vallidevi Krishnamurthy*

1. **A Survey of Code-switched Speech and Language Processing.** arxiv 2019 [paper](https://arxiv.org/abs/1904.00784)

    *Sunayana Sitaram, Khyathi Raghavi Chandu, Sai Krishna Rallabandi, Alan W. Black*

1. **Speech and Language Processing.** Stanford University 2019 [paper](http://web.stanford.edu/~jurafsky/slp3/)

    *Dan Jurafsky and James H. Martin*

1. **Informed Machine Learning -- A Taxonomy and Survey of Integrating Knowledge into Learning Systems.** arxiv 2019 [paper](https://arxiv.org/abs/1903.12394)

    *Laura von Rueden, Sebastian Mayer, Katharina Beckh, Bogdan Georgiev, Sven Giesselbach, Raoul Heese, Birgit Kirsch, Julius Pfrommer, Annika Pick, Rajkumar Ramamurthy, Michal Walczak, Jochen Garcke, Christian Bauckhage, Jannis Schuecker*

1. **Multimodal Machine Learning: A Survey and Taxonomy.** IEEE 2019 [paper](https://arxiv.org/abs/1705.09406)

    *Tadas Baltrušaitis, Chaitanya Ahuja, Louis-Philippe Morency*

1. **A Comprehensive Survey on Cross-modal Retrieval.** arxiv 2016 [paper](https://arxiv.org/abs/1607.06215)

    *Kaiye Wang*

#### [Summarization](#content)

1. **Abstractive Summarization: A Survey of the State of the Art.** AAAI 2019 [paper](https://aaai.org/ojs/index.php/AAAI/article/view/5056)

    *Hui Lin, Vincent Ng*

1. **Neural Abstractive Text Summarization with Sequence-to-Sequence Models.** arxiv 2018 [paper](https://arxiv.org/abs/1812.02303)

    *Tian Shi, Yaser Keneshloo, Naren Ramakrishnan, Chandan K. Reddy*

1. **Neural Abstractive Text Summarization with Sequence-to-Sequence Models: A Survey.** arxiv 2018 [paper](https://arxiv.org/abs/1812.02303)

    *Tian Shi, Yaser Keneshloo, Naren Ramakrishnan, Chandan K. Reddy*

1. **A Survey on Neural Network-Based Summarization Methods.** arxiv 2018 [paper](https://arxiv.org/abs/1804.04589)

    *Yue Dong*

1. **Text Summarization Techniques: A Brief Survey.** arxiv 2017 [paper](https://arxiv.org/abs/1707.02268)

    *Mehdi Allahyari, Seyedamin Pouriyeh, Mehdi Assefi, Saeid Safaei, Elizabeth D. Trippe, Juan B. Gutierrez, Krys Kochut*

1. **Automated text summarisation and evidence-based medicine: A survey of two domains.** CoRR 2017 [paper](https://arxiv.org/abs/1706.08162)

    *Abeed Sarker, Diego Mollá Aliod, Cécile Paris*

1. **Automatic Keyword Extraction for Text Summarization: A Survey.** CoRR 2017 [paper](https://arxiv.org/abs/1704.03242)

    *Santosh Kumar Bharti, Korra Sathya Babu*

1. **Recent automatic text summarization techniques: a survey.** Artificial Intelligence Review 2016 [paper](https://link.springer.com/article/10.1007%2Fs10462-016-9475-9)

    *Mahak Gambhir, Vishal Gupta*

1. **From Standard Summarization to New Tasks and Beyond: Summarization with Manifold Information.** arXiv 2020 [paper](https://arxiv.org/abs/2005.04684)

    *Shen Gao, Xiuying Chen, Zhaochun Ren, Dongyan Zhao, Rui Yan*

#### [Syntax: Tagging, Chunking, Syntax and Parsing](#content)

1. **A Neural Entity Coreference Resolution Review.** arXiv 2019 [paper](https://arxiv.org/abs/1910.09329)

    *Nikolaos Stylianou, Ioannis Vlahavas*

1. **A survey of cross-lingual features for zero-shot cross-lingual semantic parsing.** CoRR 2019 [paper](https://arxiv.org/abs/1908.10461)

    *Jingfeng Yang, Federico Fancellu, Bonnie L. Webber*

1. **A Survey on Semantic Parsing.** AKBC 2019 [paper](https://arxiv.org/abs/1812.00978)

    *Aishwarya Kamath, Rajarshi Das*

1. **The Gap of Semantic Parsing: A Survey on Automatic Math Word Problem Solvers.** CoRR 2018 [paper](https://arxiv.org/abs/1808.07290)

    *Dongxiang Zhang, Lei Wang, Nuo Xu, Bing Tian Dai, Heng Tao Shen*

#### [Text Classification](#content)

1. **Text Classification Algorithms: A Survey.** CoRR 2019 [paper](https://arxiv.org/abs/1904.08067)

    *Kamran Kowsari, Kiana Jafari Meimandi, Mojtaba Heidarysafa, Sanjana Mendu, Laura E. Barnes, Donald E. Brown*

1. **A survey on phrase structure learning methods for text classification.** CoRR 2014 [paper](https://arxiv.org/abs/1406.5598)

    *Reshma Prasad, Mary Priya Sebastian*

1. **A Survey of Naïve Bayes Machine Learning approach in Text Document Classification.** CoRR 2010 [paper](https://arxiv.org/abs/1003.1795)

    *K. A. Vidhya, G. Aghila*

1. **Deep Learning Based Text Classification: A Comprehensive ReviewDeep Learning Based Text Classification.** arxiv 2020 [paper](https://arxiv.org/pdf/2004.03705.pdf)

    *Shervin Minaee，Nal Kalchbrenner，Erik Cambria*

1. **Deep Learning Based Text Classification: A Comprehensive Review.** arXiv 2020 [paper](https://arxiv.org/abs/2004.03705)

    *Shervin Minaee, Nal Kalchbrenner, Erik Cambria, Narjes Nikzad, Meysam Chenaghlu, Jianfeng Gao*

#### [Transfer Learning](#content)

1. **A Survey on Deep Transfer Learning.** ICANN (3) 2018 [paper](https://arxiv.org/abs/1808.01974)

    *Chuanqi Tan, Fuchun Sun, Tao Kong, Wenchang Zhang, Chao Yang, Chunfang Liu*

1. **A Comprehensive Survey on Transfer Learning.** arxiv 2019 [paper](https://arxiv.org/abs/1911.02685)

    *Fuzhen Zhuang, Zhiyuan Qi, Keyu Duan, Dongbo Xi, Yongchun Zhu, Hengshu Zhu, Hui Xiong, Qing He*

1. **A Survey of Unsupervised Deep Domain Adaptation.** arxiv 2020 [paper](https://arxiv.org/abs/1812.02849)

    *Garrett Wilson, Diane J. Cook*

1. **Neural Unsupervised Domain Adaptation in NLP---A Survey.** arxiv 2020 [paper](https://arxiv.org/abs/2006.00632)

    *Alan Ramponi, Barbara Plank*

1. **A survey on domain adaptation theory: learning bounds and theoretical guarantees.** arxiv 2020 [paper](https://arxiv.org/abs/2004.11829)

    *Ievgen Redko, Emilie Morvant, Amaury Habrard, Marc Sebban, Younès Bennani*

1. **Evolution of transfer learning in natural language processing.** arXiv 2019 [paper](https://arxiv.org/abs/1910.07370)

    *Aditya Malte, Pratik Ratadiya*

1. **Transfer Adaptation Learning: A Decade Survey.** CoRR 2019 [paper](https://arxiv.org/pdf/1903.04687.pdf)

    *Lei Zhang*

1. **Neural Transfer Learning for Natural Language Processing.** PhD Thesis  [paper]()

    *SEBASTIAN RUDER*

1. **Exploring the Limits of Transfer Learning with a Unified Text-to-Text Transformer.** CoRR 2019 [paper](https://arxiv.org/pdf/1910.10683.pdf)

    *Colin Raffel, Noam Shazeer, Adam Roberts, Katherine Lee, Sharan Narang, Michael Matena, Yanqi Zhou, Wei Li, Peter J. Liu*

1. **A survey on domain adaptation theory.** arXiv 2020 [paper](https://arxiv.org/abs/2004.11829)

    *Ievgen Redko, Emilie Morvant, Amaury Habrard, Marc Sebban, Younès Bennani*

#### [Trustworthy Machine Learning](#content)

1. **A Survey on Bias and Fairness in Machine Learning.** arxiv 2019 [paper](https://arxiv.org/abs/1908.09635)

    *Ninareh Mehrabi, Fred Morstatter, Nripsuta Saxena, Kristina Lerman, Aram Galstyan*

1. **Differential Privacy and Machine Learning: a Survey and Review.** CoRR 2014 [paper](https://arxiv.org/abs/1412.7584)

    *Zhanglong Ji, Zachary C. Lipton, Charles Elkan*

1. **Tutorial: Safe and Reliable Machine Learning.** CoRR 2019 [paper](https://arxiv.org/abs/1904.07204)

    *Suchi Saria, Adarsh Subbaswamy*




## Acknowledge

Please feel free to contact us (email???) if you have any questions.

We would like to thank the people who contributed to this project. They are

XXXXX
