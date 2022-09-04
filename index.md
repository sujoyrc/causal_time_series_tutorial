<!-- ---
layout: page 
# Identification of Causal Dependencies in Multivariate Time Series
--- -->

<!-- [![GitHub Repo stars](https://img.shields.io/github/stars/nicolas-van/bootstrap-4-github-pages?style=social)](https://github.com/nicolas-van/bootstrap-4-github-pages) -->

## Tutorial for "Identification of Causal Dependencies in Multivariate Time Series"

* This tutorial will be presented at "Second International Conference on AI-ML Systems" 
* Visit here for Conference details - https://www.aimlsystems.org/2022/
* Watch this space for registration link - "Coming Soon"

![correlation](https://user-images.githubusercontent.com/8533584/183008597-249bbcba-e422-45e6-af26-899841adc1ae.png)


## Abstract

Telecommunications networks operate on enormous amount of time-series data, and often exhibit anomalous trends in their behaviour.
This is caused due to increased latency and reduced throughput in the network which inevitably leads to poor customer experience [19].
One of the common problems in machine learning in the telecom domain is to predict anomalous behaviour ahead of time. Whilst this
is a well-researched problem, though still open, there is far less work done in identifying causal structures from the temporal patterns of
various Key Performance Indicators (KPI) in the telecom network. The ability to identify causal structures from anomalous behaviours
would allow more effective intervention and generalisation of different environments and networks. The tutorial is focused on
discussing existing frameworks for establishing causal discovery for time-series data sets. In this hands-on tutorial, we will be covering
at least 3 state-of-the-art (SOTA) methods on causal time series analysis including Granger causality[9],convergent cross-mapping [16,
3, 11], Peter-Clark Momentary Conditional Independence (PC-MCI) [7, 15] and Temporal Causal discovery framework (TCDF)[12]. The
need for a causation analysis[8], beyond correlation will also be explained using publicly available datasets, such as, double pendulum
dataset [18]. The state-of-art methods are chosen to cover various aspects of the causal time series analysis, such as modelling the
non-linearity (non-linear Granger Causality), attempting the problem from chaos and dynamic systems (CCM), information-theoretic
approaches (PC-MCI, or having a data-driven approach (TCDF). State-of-the-art survey papers [13, 1] show that none of the methods
can be said to be ideal for all the possible time series and there are relative advantages and shortcomings for each of these methods

## Speakers

**Sujoy Roychowdhury**, _Principal Data Scientist Ericsson R&D_  has over 15 years of experience in Machine
learning and Artificial Intelligence. His main interests are in deep learning, causal reasoning and computer vision.
Sujoy previously was in IBM where he built multimodal recommendation systems deployed now in production
and was awarded some of the highest individual honours including the IBM Outstanding Technical Achievement
award and the Best of IBM Award. He has 6 filed patents, 8 peer reviewed international conferences including
two best paper awards and co-authored 2 Harvard Business School case studies

**Serene Banerjee**, _Master Researcher, Ericsson Research_, Bangalore, has 18+ years of industrial experience post
completion of her Ph.D. from The Univ. of Texas at Austin, under Prof. Brian L. Evans in 2004. She has a B. Tech.
(H) in Electronics and Electrical Communications Engineering from IIT Kharagpur in 1999. At Ericsson she is
focusing on developing AI/ML algorithms for Radio Access Networks. Prior to Ericsson she was with Texas
Instruments, HP, and Johnson Controls. She has 9 granted patents, 23 peer reviewed publications and several
pending.

**Ranjani**, _Principal Data Scientist Ericsson R&D_ has a total of 19 years experience combined in academia
and industry. She is currently with Ericsson, Bangalore with focus on machine learning problems in LTE and 5G
RAN. She completed her Ph.D. and M.Sc (Engg) from IISc, Bangalore. Her research interests include machine
learning, signal processing, speech audio and music signal analysis, RAN. She has 4 filed patents, and more than
10 peer reviewed publications.

**Chaitanya Kapoor** is a _Research Intern at Ericsson Research_, Bangalore, working on Causal AI. He is an
undergraduate student at Amrita Vishwa Vidyapeetham. He has co-authored 6 publications

## Tutorial Outline

Contrary to predictive models, causal AI can step in to understand the fundamental causes of an event or underlying
behavior that led to it. Causal inference focuses on understanding the real impact of specific phenomena that occurs
inside a system. Existing machine learning frameworks however focus on conclusions based on data, which might not
be as insightful as causal inference. Causal AI has also been used for addressing several industrial problems, such as,
churn prediction [10], scene reconstruction [2] etc.

In this hands-on tutorial, we will be covering at least 3 state-of-the-art methods on causal time series analysis,
including:

* **Introduction and motivation** Causal understanding helps unravel causes which explain effects. This is different
from the majority of machine learning and deep learning models which are based on correlational studies.

*  **State of the art methods**
    *  **Granger causality** [9] Granger causality tries to identify the causal direction in a system based on how the
                  predictive power of a system changes with the inclusion or exclusion of a feature in the dataset.
    *   **Non-linear Granger Causality** [17, 14] Neural Granger Causality are a class of nonlinear methods that
apply multilayer perceptrons (MLPs) or recurrent neural networks (RNNs) combined with sparsity-inducing penalties on the weights. By encouraging specific sets of weights to be zero—in particular, through the use of convex group-lasso penalties—it is possible to extract the Granger causal structure.
    *  **Convergent Cross Mapping** (CCM) [16, 3, 11] Convergent cross mapping uses a system dynamics view of
the problem by trying to find correlations between shadow manifolds of different state variables of the system.
Although various methods [5, 6] exist for estimation of causality in presence of noise, outliers and missing
data this tutorial would focus on Latent convergent cross mapping. This method, based on Neural Ordinary
differential equations (ODEs) [4], is used for identifying causal direction and link for sporadic time series and
noisy data.
    *  **Peter-Clark Momentary Conditional Independence** (PC-MCI) [10, 11] PCMCI method takes a 2 step
approach, where it uses (a) a PC approach, named after the inventors to detect parents that can be flexibly
implemented with different kinds of conditional independence tests and which can handle nonlinear dependencies
and variables that are discrete or continuous, and univariate or multivariate. Then, it uses (b) Momentary
Conditional Independence tests reducing false positives for the highly-interdependent time series.
    *  **Temporal Causal Discovery Framework** (TCDF) [12] TCDF has four stages: Correlation Discovery, Causal
Discovery, Delay Discovery and Graph Construction. It uses independent attention based convolutional neural
networks, all having the same architecture but a different target time series.
* Code walk through/hands-on for GC, CCM, PCMCI, TCDF
* Q&A

The need for a causation analysis [15], beyond correlation will also be explained using publicly available datasets,
such as, double pendulum dataset.

The state-of-art methods are chosen to cover various aspects of the causal time series analysis, such as modelling
the non-linearity (non-linear Granger Causality), attempting the problem from chaos and dynamic systems (CCM),
information-theoretic approaches (PC-MCI, or having a data-driven approach (TCDF). State-of-the-art survey papers
[13, 14] show that none of the methods can be said to be ideal for all the possible time series and there are relative
advantages and shortcomings for each of these methods

## Tutorial Details

### Slides

[Slides](https://github.com/sujoyrc/causal_time_series_tutorial/blob/238611c534f3ec5c2dded1be4db41af4112b9fb4/TutorialContent/Slides/Causal%20Modelling%20on%20Multivariate%20Time%20Series.pdf)

### Demo Code

[Demo Code](https://github.com/sujoyrc/causal_time_series_tutorial/tree/master/TutorialContent/DemoCode)

### Dataset

[Dataset](https://github.com/sujoyrc/causal_time_series_tutorial/tree/master/TutorialContent/DemoCode/Dataset)

##  References

[1] Charles K Assaad, Emilie Devijver, and Eric Gaussier. 2022. Survey and evaluation of causal discovery methods for time series. Journal of Artificial
Intelligence Research, 73, 767–819.

[2] Yoshua Bengio, Tristan Deleu, Edward J Hu, Salem Lahlou, Mo Tiwari, and Emmanuel Bengio. 2021. Gflownet foundations. arXiv preprint
arXiv:2111.09266.

[3] Edward De Brouwer, Adam Arany, Jaak Simm, and Yves Moreau. 2020. Latent convergent cross mapping. In International Conference on Learning
Representations.

[4] Edward De Brouwer, Jaak Simm, Adam Arany, and Yves Moreau. 2019. Gru-ode-bayes: continuous modeling of sporadically-observed time series.
Advances in neural information processing systems, 32.

[5] Guanchao Feng, J Gerald Quirk, and Petar M Djurić. 2019. Detecting causality using deep gaussian processes. In 2019 53rd Asilomar Conference on
Signals, Systems, and Computers. IEEE, 472–476.

[6] Guanchao Feng, Kezi Yu, Yunlong Wang, Yilian Yuan, and Petar M Djurić. 2020. Improving convergent cross mapping for causal discovery with
gaussian processes. In ICASSP 2020-2020 IEEE International Conference on Acoustics, Speech and Signal Processing (ICASSP). IEEE, 3692–3696.

[7] Andreas Gerhardus and Jakob Runge. 2020. High-recall causal discovery for autocorrelated time series with latent confounders. Advances in
Neural Information Processing Systems, 33, 12615–12625.

[8] Madelyn Glymour, Judea Pearl, and Nicholas P Jewell. 2016. Causal inference in statistics: A primer. John Wiley & Sons.

[9] CWJ Granger. 1969. Investigating causal relationships by econometric models and cross-spectral methods’, economˆ trica. July.

[10] Scott Lundberg. 2021. Be careful when interpreting predictive models in search of causal insights. (May 2021). https://towardsdatascience.com/becareful-
when-interpreting-predictive-models-in-search-of-causal-insights-e68626e664b6.

[11] Dan Mønster, Riccardo Fusaroli, Kristian Tylén, Andreas Roepstorff, and Jacob F Sherson. 2016. Inferring causality from noisy time series data.
arXiv preprint arXiv:1603.01155.

[12] Meike Nauta, Doina Bucur, and Christin Seifert. 2019. Causal discovery with attention-based convolutional neural networks. Machine Learning
and Knowledge Extraction, 1, 1, 19.

[13] Ana Rita Nogueira, Andrea Pugnana, Salvatore Ruggieri, Dino Pedreschi, and João Gama. 2022. Methods and tools for causal discovery and causal
inference. Wiley Interdisciplinary Reviews: Data Mining and Knowledge Discovery, 12, 2, e1449.

[14] Maciej Rosoł, Marcel Młyńczak, and Gerard Cybulski. 2022. Granger causality test with nonlinear neural-network-based methods: python package
and simulation study. Computer Methods and Programs in Biomedicine, 216, 106669.

[15] Jakob Runge. 2020. Discovering contemporaneous and lagged causal relations in autocorrelated nonlinear time series datasets. In Conference on
Uncertainty in Artificial Intelligence. PMLR, 1388–1397.

[16] George Sugihara, Robert May, Hao Ye, Chih-hao Hsieh, Ethan Deyle, Michael Fogarty, and Stephan Munch. 2012. Detecting causality in complex
ecosystems. science, 338, 6106, 496–500.

[17] Alex Tank, Ian Covert, Nicholas Foti, Ali Shojaie, and Emily Fox. 2018. Neural granger causality for nonlinear time series. stat, 1050, 16.

[18] [n. d.] The double pendulum — scipython.com. https://scipython.com/blog/the-double-pendulum/. [Accessed 10-Jul-2022]. ().

[19] Keli Zhang, Marcus Kalander, Min Zhou, Xi Zhang, and Junjian Ye. 2020. An influence-based approach for root cause alarm discovery in telecom
networks. In International Conference on Service-Oriented Computing. Springer, 124–136.
              
     
