---
title: "Research"
author_profile: true
permalink: /research/
redirect_from: 
  - /research.html
---

**Overview**: I'm passionate about Machine Learning, Natural and Artificial Intelligence, Robotics, Computational Biology and Medicine. 
For a complete list of my publications and patents, visit my [Google Scholar profile](https://scholar.google.com/citations?user=S6wyhngAAAAJ&hl=en). 


***

## Reverse-chronological summary:

### Post-doc at Harvard Medical / Kempner Institute (2024-Current)
Working with [Kanaka Rajan](https://twitter.com/KanakaRajanPhD) at the intersection of DeepRL-Agents and Neuroscience.  My current research focuses on:

- **Agent Models in Neuroscience**: Developing RNN-based reinforcement learning agents to study complex naturalistic animal behavior. 

As an example, in a collaboration with [Nate Sawtell (Columbia)](https://sawtell-lab.neuroscience.columbia.edu), I have been investigating active electrosensing and emergent social behaviors in MARL-trained agents, inspired by Weakly Electric Fish.
  - Singh, S. H., Johnson-Yu, S., et al. (2025). "Active Electrosensing and Emergent Communication in Artificial Fish Collectives" *(In Preparation).*
  - Johnson-Yu, S., Singh, S. H., et al. (2024). "Understanding biological active sensing behaviors by interpreting learned artificial agent policies." *Workshop on Interpretable Policies in Reinforcement Learning@ RLC-2024* [[Paper](https://openreview.net/forum?id=FX7YtfEYj8)] [[TalkRL Podcast](https://www.talkrl.com/episodes/rlc-2024-posters-and-hallways-2)]  

<div align="center">
  <img src="/files/MAFish_20250109_183556_58206857_5sec.gif" alt="Weakly Electric Fish" />
</div>

Another example, in collaboration with [Florian Engert (Harvard)](https://www.engertlab.org/research), I have been studying naturalistic hunting behavior of Zebrafish larvae in both solitary and collective settings. 
 - Malik R, Singh SH, Johnson-Yu S, et al (2025), "Dissecting Larval Zebrafish Hunting using Deep Reinforcement Learning Trained RNN Agents" (Full length paper Submitted; extended abstract accepted to NeurIPS 2025 AI4Science workshop)

<div align="center">
  <img src="/files/Bots_20250922.gif" alt="Zebrafish" />
</div>

- **Methods and Theory for understanding RNN Agents**: To *interpret, compare, and constrain neural networks trained via RL*, I develop theoretical tools and methods using tools from dynamical systems theory, neuroscience, and AI interpretability.
  - Huang, A. H., Singh, S. H., et al. (2024). "Learning Dynamics and the Geometry of Neural Dynamics in Recurrent Neural Controllers." *Workshop on Interpretable Policies in Reinforcement Learning@ RLC-2024* [[Paper](https://openreview.net/forum?id=SbbpTtB6B4)] [[TalkRL Podcast](https://www.talkrl.com/episodes/rlc-2024-posters-and-hallways-1)]    
  - Huang, A. H., Singh, S. H., Rajan, K. (2025). "Measuring and Controlling Solution Degeneracy in Task-Trained RNNs." [[NeurIPS 2025, Spotlight Talk](https://arxiv.org/abs/2410.03972)]
  - Huang, A. H., Ostrow, M., Singh, S. H., et al, "InputDSA: Demixing then comparing recurrent and externally driven dynamics" *(Submitted).*



### Post-doc at Baylor College of Medicine/Rice University (2023)
1. **Gene Regulatory Network (GRN) Evolution**: Simulated GRN evolution to study transcription factor promiscuity and adaptation.
   - *"Binding affinity distributions drive adaptation in GRN evolution"* (ALIFE 2023) [[Paper](https://direct.mit.edu/isal/proceedings/isal/35/89/116839)]

2. **AI for Mental Health**: Developed RACER, an auditable, expert-steerable LLM-based methodology for analyzing semi-structured healthcare interviews.
   - *RACER: An LLM-powered Methodology for Scalable Analysis of Semi-structured Mental Health Interviews* (EMNLP 2024 Workshop on NLP4Science) [[Paper](https://aclanthology.org/2024.nlp4science-1.8/)]

3. **AI in Cardiology**: Implemented uncertainty-aware arrhythmia detection models for pediatric ICUs.
   - *"A multimodal deep learning tool for detection of junctional ectopic tachycardia in children with congenital heart disease"* (Heart Rhythm O2, 2024) [[Paper](https://pubmed.ncbi.nlm.nih.gov/39119021/)]

4. **Multi-Omic Cancer Progression Analysis**: Characterized molecular markers of [Myelodysplastic Syndrome (MDS)](https://www.mds-foundation.org/what-is-mds/) using multi-omic liquid biopsies. (Ongoing) [[Abstract: Experimental Hematology](https://www.sciencedirect.com/science/article/pii/S0301472X24002261)] 



***

### Post-PhD Industry (2022)
Research Scientist in Machine Learning in the [Probability team](https://research.facebook.com/teams/probability/) team at Meta. Worked on team proojects involving: 
* Uncertainty Quantification using Neural Networks (Deep Ensembles, MCMCDropout, ...)
* Bayesian Modeling for Online Experiments (primarily using sampling-based inference from the in-house [Bean Machine](https://research.facebook.com/blog/2021/12/introducing-bean-machine-a-probabilistic-programming-platform-built-on-pytorch/) PPL) 

<!-- At the end of a [very volatile year](https://www.nytimes.com/2022/11/09/technology/meta-layoffs-facebook.html), my entire org was [disbanded](https://venturebeat.com/ai/meta-layoffs-hit-entire-ml-research-team-focused-on-infrastructure/) in Nov 2022. While I had the option to stick around and find another team after the layoffs, I decided to pursue my research passions. -->

***

### PhD (9/2017 - 12/2021)
* PhD at the [University of Washington (Seattle)](https://www.washington.edu), at the intersection of ML/RL and Computational Neuroscience. Advised by [Bingni W Brunton (UW Neurobiology)](https://www.biology.washington.edu/people/profile/bing-w-brunton) and [Rajesh PN Rao (UW Computer Science)](https://www.cs.washington.edu/people/faculty/rao).

#### Project 1: Using deep recurrent reinforcement-learning agents to understand insect plume tracking 

[Singh et al, Nature Machine Intelligence, Jan 2023, Cover Feature](https://www.nature.com/articles/s42256-022-00599-w).  

<div align="center">
  <img src="/files/nmi_cover.png" alt="Artwork by Bingni Brunton and Floris van Breugel" />
</div>

[#tweeprint](https://twitter.com/tweetsatpreet/status/1442974225032093698): 
<blockquote class="twitter-tweet"><p lang="en" dir="ltr">1/n Excited to share our new preprint where we study turbulent plume tracking using deep reinforcement learning (DRL) trained RNN *agents* and find many intriguing similarities with flying insects. w/ <a href="https://twitter.com/FlorisBreugel?ref_src=twsrc%5Etfw">@FlorisBreugel</a> <a href="https://twitter.com/RajeshPNRao?ref_src=twsrc%5Etfw">@RajeshPNRao</a> <a href="https://twitter.com/bingbrunton?ref_src=twsrc%5Etfw">@bingbrunton</a>; <br> <a href="https://twitter.com/hashtag/tweeprint?src=hash&amp;ref_src=twsrc%5Etfw">#tweeprint</a> <a href="https://twitter.com/Flypapers?ref_src=twsrc%5Etfw">@flypapers</a> <a href="https://twitter.com/hashtag/Drosophila?src=hash&amp;ref_src=twsrc%5Etfw">#Drosophila</a> <a href="https://t.co/PdVKxbP0hs">pic.twitter.com/PdVKxbP0hs</a></p>&mdash; Satpreet Singh (@tweetsatpreet) <a href="https://twitter.com/tweetsatpreet/status/1442974225032093698?ref_src=twsrc%5Etfw">September 28, 2021</a></blockquote> <script async src="https://platform.twitter.com/widgets.js" charset="utf-8"></script>

<!-- ![Constant Wind Plume Tracking](/oldparams-cropped.gif) -->
<!-- ![Noisy Wind Plume Tracking](/noisy3x5b5_HOME_ep159.mp4) -->
<!-- ![Constant Wind Plume Tracking](/constantx5b5_HOME_ep088.mp4) -->

<!-- [Montreal AI-Neuroscience Conference 2021 (Nov 2021) Invited Talk:](https://twitter.com/tweetsatpreet/status/1462948984545169408) on this work:
<blockquote class="twitter-tweet"><p lang="en" dir="ltr">Check out <a href="https://twitter.com/bingbrunton?ref_src=twsrc%5Etfw">@bingbrunton</a>&#39;s upcoming talk at MAIN 2021 on our recently released preprint:<a href="https://t.co/7fkIuXiRkt">https://t.co/7fkIuXiRkt</a> <a href="https://t.co/eOkylFSltP">https://t.co/eOkylFSltP</a></p>&mdash; Satpreet Singh (@tweetsatpreet) <a href="https://twitter.com/tweetsatpreet/status/1462948984545169408?ref_src=twsrc%5Etfw">November 23, 2021</a></blockquote> <script async src="https://platform.twitter.com/widgets.js" charset="utf-8"></script>
 -->


Presented at:
<!-- * [RLDM 2022](https://rldm.org) -->
* [CoSyNe 2022](https://www.cosyne.org/poster-session-3)
* [Montreal AI-Neuroscience Conference 2021](https://www.main2021.org/schedule) 
* [NAISys 2020](https://meetings.cshl.edu/abstracts.aspx?meet=naisys&year=20) 
* [IROS 2020 Robot Inspired Biology Workshop](http://gravishlab.ucsd.edu/iros2020/)
* [ALIFE Conference 2020](https://direct.mit.edu/isal/proceedings/isal2020/32/750/98465) 


([More behavior+neural animations](https://github.com/BruntonUWBio/plumetracknets)) ([Preprint](https://arxiv.org/abs/2109.12434))


#### Project 2: Naturalistic motor neuroscience using long-term human video and neural recordings

[Singh et al (Journal of Neuroscience Methods, Apr 2021)](https://www.sciencedirect.com/science/article/pii/S0165027021001345)
([Preprint](https://arxiv.org/abs/2001.08349)) ([Code, data & more videos](https://github.com/BruntonUWBio/mining2021)) 

![Right Wrist](https://raw.githubusercontent.com/BruntonUWBio/mining2021/master/right_only_1x4_boomerang.gif)


[#tweeprint](https://twitter.com/tweetsatpreet/status/1276201158575452160) on this paper:  
<blockquote class="twitter-tweet"><p lang="en" dir="ltr">Our new preprint titled “Investigating naturalistic hand movements by behavior mining in long-term video and neural recordings” is now online: <a href="https://t.co/46FsBMFnV1">https://t.co/46FsBMFnV1</a><br>Joint work with <a href="https://twitter.com/stevenmpeterson?ref_src=twsrc%5Etfw">@stevenmpeterson</a>, <a href="https://twitter.com/RajeshPNRao?ref_src=twsrc%5Etfw">@RajeshPNRao</a> &amp; <a href="https://twitter.com/bingbrunton?ref_src=twsrc%5Etfw">@bingbrunton</a> <br>1/4 <a href="https://t.co/6360Dw8TMs">pic.twitter.com/6360Dw8TMs</a></p>&mdash; Satpreet Singh (@tweetsatpreet) <a href="https://twitter.com/tweetsatpreet/status/1276201158575452160?ref_src=twsrc%5Etfw">June 25, 2020</a></blockquote> <script async src="https://platform.twitter.com/widgets.js" charset="utf-8"></script>

This paper's data generating pipeline and dataset were the foundation for additional papers:
* [Peterson, SP and Singh, SH, et al (eNeuro, May 2021)](https://www.eneuro.org/content/early/2021/05/21/ENEURO.0007-21.2021.abstract) (Joint 1st author)
* [SM Peterson, SH Singh, B Dichter, M Scheid, RPN Rao, BW Brunton (Nature Scientific data, April 2022)](https://www.nature.com/articles/s41597-022-01280-y) 
* [Peterson et al (Journal of Neural Engineering, March 2021)](https://iopscience.iop.org/article/10.1088/1741-2552/abda0b/meta) (Only contributed data)


***

### Before PhD and side-projects 
* [Non-Negative Matrix Factorization Game](https://arxiv.org/abs/2104.05069): A novel game-theoretic formulation of the Non-Negative Matrix Factorization (NNMF) algorithm, with favorable scaling and parallelization properties, and reconstruction and convergence performance comparable to original algorithm.

* [Cerenkov: Computational elucidation of the regulatory noncoding variome, ](https://par.nsf.gov/biblio/10049769) at the 8th ACM International Conference on Bioinformatics, Computational Biology,and Health Informatics (2017)

* [Visualization and Analysis of Sensor Data for Detecting Microclimate Cold Air Pools](https://ir.library.oregonstate.edu/concern/graduate_thesis_or_dissertations/k0698d22b) Oregon State University MS Thesis (2017): Developed a piecewise-linear probabilistic model of sensor-network data.  
![Nonlinear dashboard](https://github.com/satpreetsingh/osu-cap/raw/master/animations/gpInflectionLapseAnimation_2011-12-12.fullday.gif)

* [Hydro-NEXRAD-2: real-time access to customized radar-rainfall for hydrologic applications](https://iwaponline.com/jh/article/15/2/580/3447/Hydro-NEXRAD-2-real-time-access-to-customized) Journal of Hydroinformatics (2013)

* [Industry patents](https://scholar.google.com/citations?hl=en&user=S6wyhngAAAAJ&view_op=list_works&sortby=pubdate): As part of the visionary data-science team at LinkedIn, I had the exciting opportunity to contribute to groundbreaking patents that reshaped the way professionals connect, find jobs, and grow their careers. 


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

 <!-- Default Statcounter code for Personal
http://satpreetsingh.github.io -->
<script type="text/javascript">
var sc_project=13020034; 
var sc_invisible=1; 
var sc_security="69b15dcb"; 
</script>
<script type="text/javascript"
src="https://www.statcounter.com/counter/counter.js"
async></script>
<noscript><div class="statcounter"><a title="Web Analytics"
href="https://statcounter.com/" target="_blank"><img
class="statcounter"
src="https://c.statcounter.com/13020034/0/69b15dcb/1/"
alt="Web Analytics"
referrerPolicy="no-referrer-when-downgrade"></a></div></noscript>