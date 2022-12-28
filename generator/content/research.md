+++
title = "Research"
+++

# Research
* Publications & Patents available on [Google Scholar](https://scholar.google.com/citations?user=S6wyhngAAAAJ&hl=en)
* I maintain a broad interest in the fields of Machine Learning and AI, especially where they intersect with Psychology, Neuroscience, Biology and Physics


### PhD (Sept. 2017 - Dec. 2021)

* PhD at the University of Washington (Seattle), at the intersection of ML/RL and Computational Neuroscience. Advised by [Bingni W Brunton (UW Neurobiology)](https://www.biology.washington.edu/people/profile/bing-w-brunton) and [Rajesh PN Rao (UW Computer Science)](https://www.cs.washington.edu/people/faculty/rao).

#### Understanding biological plume tracking behavior using deep reinforcement-learning
Abstract: Tracking a turbulent plume to locate its source is a complex control problem because it requires multi-sensory integration and must be robust to intermittent odors, changing wind direction, and variable plume statistics.
This task is routinely performed by flying insects, often over long distances, in pursuit of food or mates.
Several aspects of this remarkable behavior have been studied in detail in many experimental studies. 
Here, we take a complementary in silico approach, using artificial agents trained with reinforcement learning to develop an integrated understanding of the behaviors and neural computations that support plume tracking.
Specifically, we use deep reinforcement learning (DRL) to train recurrent neural network (RNN) agents to locate the source of simulated turbulent plumes.
Interestingly, the agents' emergent behaviors resemble those of flying insects, and the RNNs learn to represent task-relevant variables, such as head direction and time since last odor encounter.
Our analyses suggest an intriguing experimentally testable hypothesis for tracking plumes in changing wind direction---that agents follow local plume shape rather than the current wind direction.
While reflexive short-memory behaviors are sufficient for tracking plumes in constant wind, longer timescales of memory are essential for tracking plumes that switch direction.
At the level of neural dynamics, the RNNs' population activity is low-dimensional and organized into distinct dynamical structures, with some correspondence to behavioral modules.
Our in silico approach provides key intuitions for turbulent plume tracking strategies and motivates future targeted experimental and theoretical developments. 

[#tweeprint](https://twitter.com/tweetsatpreet/status/1442974225032093698) on this paper:  
<blockquote class="twitter-tweet"><p lang="en" dir="ltr">1/n Excited to share our new preprint where we study turbulent plume tracking using deep reinforcement learning (DRL) trained RNN *agents* and find many intriguing similarities with flying insects. w/ <a href="https://twitter.com/FlorisBreugel?ref_src=twsrc%5Etfw">@FlorisBreugel</a> <a href="https://twitter.com/RajeshPNRao?ref_src=twsrc%5Etfw">@RajeshPNRao</a> <a href="https://twitter.com/bingbrunton?ref_src=twsrc%5Etfw">@bingbrunton</a>; <br> <a href="https://twitter.com/hashtag/tweeprint?src=hash&amp;ref_src=twsrc%5Etfw">#tweeprint</a> <a href="https://twitter.com/Flypapers?ref_src=twsrc%5Etfw">@flypapers</a> <a href="https://twitter.com/hashtag/Drosophila?src=hash&amp;ref_src=twsrc%5Etfw">#Drosophila</a> <a href="https://t.co/PdVKxbP0hs">pic.twitter.com/PdVKxbP0hs</a></p>&mdash; Satpreet Singh (@tweetsatpreet) <a href="https://twitter.com/tweetsatpreet/status/1442974225032093698?ref_src=twsrc%5Etfw">September 28, 2021</a></blockquote> <script async src="https://platform.twitter.com/widgets.js" charset="utf-8"></script>

<!-- ![Constant Wind Plume Tracking](/oldparams-cropped.gif) -->
![Noisy Wind Plume Tracking](/noisy3x5b5_HOME_ep159.mp4)
<!-- ![Constant Wind Plume Tracking](/constantx5b5_HOME_ep088.mp4) -->

More animations with tracking and "neural" activity can be seen [here](https://github.com/BruntonUWBio/plumetracknets)

<!-- [Montreal AI-Neuroscience Conference 2021 (Nov 2021) Invited Talk:](https://twitter.com/tweetsatpreet/status/1462948984545169408) on this work:
<blockquote class="twitter-tweet"><p lang="en" dir="ltr">Check out <a href="https://twitter.com/bingbrunton?ref_src=twsrc%5Etfw">@bingbrunton</a>&#39;s upcoming talk at MAIN 2021 on our recently released preprint:<a href="https://t.co/7fkIuXiRkt">https://t.co/7fkIuXiRkt</a> <a href="https://t.co/eOkylFSltP">https://t.co/eOkylFSltP</a></p>&mdash; Satpreet Singh (@tweetsatpreet) <a href="https://twitter.com/tweetsatpreet/status/1462948984545169408?ref_src=twsrc%5Etfw">November 23, 2021</a></blockquote> <script async src="https://platform.twitter.com/widgets.js" charset="utf-8"></script>
 -->

Associated publications
* [Preprint: "Emergent behavior and neural dynamics in artificial agents tracking turbulent plumes"](https://arxiv.org/abs/2109.12434)

Also presented at:
* [RLDM 2022](https://rldm.org)
* [CoSyNe 2022](https://www.cosyne.org/poster-session-3)
* [Montreal AI-Neuroscience Conference 2021](https://www.main2021.org/schedule) 
* [NAISys 2020](https://meetings.cshl.edu/abstracts.aspx?meet=naisys&year=20) 
* [IROS 2020 Robot Inspired Biology Workshop](http://gravishlab.ucsd.edu/iros2020/)
* [ALIFE Conference 2020](https://direct.mit.edu/isal/proceedings/isal2020/32/750/98465) 


#### Mining naturalistic human behaviors in long-term video and neural recordings

Abstract: Recent technological advances in brain recording and artificial intelligence are propelling a new paradigm in neuroscience beyond the traditional controlled experiment. Rather than focusing on cued, repeated trials, naturalistic neuroscience studies neural processes underlying spontaneous behaviors performed in unconstrained settings. However, analyzing such unstructured data lacking a priori experimental design remains a significant challenge, especially when the data is multi-modal and long-term. Here we describe an automated approach for analyzing simultaneously recorded long-term, naturalistic electrocorticography (ECoG) and naturalistic behavior video data. We take a behavior-first approach to analyzing the long-term recordings. Using a combination of computer vision, discrete latent-variable modeling, and string pattern-matching on the behavioral video data, we find and annotate spontaneous human upper-limb movement events. We show results from our approach applied to data collected for 12 human subjects over 7--9 days for each subject. Our pipeline discovers and annotates over 40,000 instances of naturalistic human upper-limb movement events in the behavioral videos. Analysis of the simultaneously recorded brain data reveals neural signatures of movement that corroborate prior findings from traditional controlled experiments. We also prototype a decoder for a movement initiation detection task to demonstrate the efficacy of our pipeline as a source of training data for brain-computer interfacing applications. Our work addresses the unique data analysis challenges in studying naturalistic human behaviors, and contributes methods that may generalize to other neural recording modalities beyond ECoG. We publicly release our curated dataset, providing a resource to study naturalistic neural and behavioral variability at a scale not previously available.

![Right Wrist](https://raw.githubusercontent.com/BruntonUWBio/mining2021/master/right_only_1x4_boomerang.gif)

[Singh et al (Journal of Neuroscience Methods, Apr 2021)](https://www.sciencedirect.com/science/article/pii/S0165027021001345)
([Preprint](https://arxiv.org/abs/2001.08349)) ([Code, data & more videos](https://github.com/BruntonUWBio/mining2021)) 

This paper's data generating pipeline and dataset were the foundation for additional papers:
* [Peterson, SP and Singh, SH, et al (eNeuro, May 2021)](https://www.eneuro.org/content/early/2021/05/21/ENEURO.0007-21.2021.abstract) (Joint 1st authorship)
* [SM Peterson, SH Singh, B Dichter, M Scheid, RPN Rao, BW Brunton (Nature Scientific data, April 2022)](https://www.nature.com/articles/s41597-022-01280-y) 
* [Peterson et al (Journal of Neural Engineering, March 2021)](https://iopscience.iop.org/article/10.1088/1741-2552/abda0b/meta) (Only contributed data, not an author)

[#tweeprint](https://twitter.com/tweetsatpreet/status/1276201158575452160) on this paper:  
<blockquote class="twitter-tweet"><p lang="en" dir="ltr">Our new preprint titled “Investigating naturalistic hand movements by behavior mining in long-term video and neural recordings” is now online: <a href="https://t.co/46FsBMFnV1">https://t.co/46FsBMFnV1</a><br>Joint work with <a href="https://twitter.com/stevenmpeterson?ref_src=twsrc%5Etfw">@stevenmpeterson</a>, <a href="https://twitter.com/RajeshPNRao?ref_src=twsrc%5Etfw">@RajeshPNRao</a> &amp; <a href="https://twitter.com/bingbrunton?ref_src=twsrc%5Etfw">@bingbrunton</a> <br>1/4 <a href="https://t.co/6360Dw8TMs">pic.twitter.com/6360Dw8TMs</a></p>&mdash; Satpreet Singh (@tweetsatpreet) <a href="https://twitter.com/tweetsatpreet/status/1276201158575452160?ref_src=twsrc%5Etfw">June 25, 2020</a></blockquote> <script async src="https://platform.twitter.com/widgets.js" charset="utf-8"></script>

#### Non-Negative Matrix Factorization Game

Abstract: We present a novel game-theoretic formulation of Non-Negative Matrix Factorization (NNMF), a popular data-analysis method with many scientific and engineering applications. The game-theoretic formulation is shown to have favorable scaling and parallelization properties, while retaining reconstruction and convergence performance comparable to the traditional Multiplicative Updates algorithm.

[Unrefereed Preprint/Extended Project Report](https://arxiv.org/abs/2104.05069)


### Before PhD 

* [Cerenkov: Computational elucidation of the regulatory noncoding variome, ](https://par.nsf.gov/biblio/10049769) at the 8th ACM International Conference on Bioinformatics, Computational Biology,and Health Informatics (2017)
* [Visualization and Analysis of Sensor Data for Detecting Microclimate Cold Air Pools](https://ir.library.oregonstate.edu/concern/graduate_thesis_or_dissertations/k0698d22b) Oregon State University MS Thesis (2017) 

Abstract: Cold air pools are spatiotemporal phenomena that occur when cold air from higher elevations roll down the slope to accumulate in lower elevations. Behaviors like this lead to microclimate anomalies such as the city of Corvallis (Oregon) experiencing persistent cold weather even on a sunny day. We analyze multivariate temperature time-series data and associated covariates from about 160 sensors from the HJ Andrews Research Forest (Oregon) through visualization and modeling to study this phenomenon. We develop detectors to localize cold air pools in both time and space, and carry out simulation studies to assess their performance under different microclimatic and sensor-performance conditions.
![Nonlinear dashboard](https://github.com/satpreetsingh/osu-cap/raw/master/animations/gpInflectionLapseAnimation_2011-12-12.fullday.gif)

* [Hydro-NEXRAD-2: real-time access to customized radar-rainfall for hydrologic applications](https://iwaponline.com/jh/article/15/2/580/3447/Hydro-NEXRAD-2-real-time-access-to-customized) Journal of Hydroinformatics (2013)

### Industry
* List of patents applied and granted can be found on [Google Scholar](https://scholar.google.com/citations?user=S6wyhngAAAAJ&hl=en). 


<!-- ## Research -->

<!-- Current interests include 
* Understanding agents and neural networks (recurrence, learning, representations/embeddings, tasks/curricula, actor-critic and specialized architectures), 
* Recurrent Neural Networks & Dynamical Systems
* Agents, Equilibria, Reinforcement learning and decision making
* Applications in Bio, Eco & Health; Cross-pollinating ML/AI with Neuroscience. 
* Inverse problems in Learning & Control
* Closed-loop (humans in the loop) Machine Learning systems
* Self-organization and brain/biology/nature inspired algorithms
 --><!-- 
Current interests: 
* Agents, Games & Reinforcement Learning
* Recurrent Neural Networks & Dynamical Systems
* Inverse problems in Learning & Control
* Self-organization and brain/biology/nature inspired algorithms
* Statistical Neuroscience 
 -->

<!-- Global site tag (gtag.js) - Google Analytics -->
<script async src="https://www.googletagmanager.com/gtag/js?id=G-FK1KPLK46E"></script>
<script>
  window.dataLayer = window.dataLayer || [];
  function gtag(){dataLayer.push(arguments);}
  gtag('js', new Date());

  gtag('config', 'G-FK1KPLK46E');
</script>