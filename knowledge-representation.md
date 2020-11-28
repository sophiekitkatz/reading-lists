# Readings

All documents in `./documents/...` were freely and publicly found on *scholar.google.com*. Any relative paths are relative to the current `reading.md` file. The following regex can be used to match all documents and publications listed here.

```
`((\./)|(https?:))[^`]*`
```

## General background on knowledge representation

`./documents/Danh_gia_qua_trinh_Bai_tp_v_nha_bai_t.pdf`

*Knowledge Representation and Reasoning - Ronald J. Brachman, Hector J. Levesque (2003)*

Although not one of the first works by a long shot, still a seminal summary of the field. It leans heavily on the concept of frames, developed by Minsky in 1975.

* **Introduction**
    * A proposition is a simple, declarative sentence. (i.e. Mary is going to the party).
    * Propositional attitudes are relations between agents and propositions (i.e. John knows that Mary is going to the party).
        * A belief is a type of propositional attitude.
    * Knowledge representation is the study of formalization of knowledge.
    * Reasoning is manipulation of represented knowledge.
    * There's an example of a bird named Tweety. Is this where *Tweety: A Comprehensive Collection of Java Libraries for Logical Aspects of Artificial Intelligence and Knowledge Representation - Matthias Thimm (2014)* came from? That'd be pretty funny.
* **Chapter 2: The Language of First-Order Logic**
    * An interpretation mapping is the set of objects or N-tuples of objects in the domain that match a predicate given as a parameter.
    * Note that the domain of FOL seems to contain sets of other objects in the domain.
* **Chapter 3: Expressing Knowledge**
    * ... there's not too much of interest here.
* **Chapter 4: Resolution**
    * ... there's not too much of interest here.
* **Chapter 5: Reasoning with Horn Clauses**
    * Introduction to Prolog.
* **Chapter 6: Procedural Control of Reasoning**
    * ... there's not too much of interest here.
* **Chapter 7: Rules in Production Systems**
    * ... there's not too much of interest here.
* **Chapter 8: Object-Oriented Representation**
    * A frame is a class-like data structure for representing objects (Minsky, 1975).
        * Properties are slots.
        * Values to be given to properties are fillers.
* **Chapter 9: Structured Descriptions**
    * ... there's not too much of interest here.
* **Chapter 10: Inheritance**
    * Ways of disambiguation for inferences.
* **Chapter 11: Defaults**
    * ... there's not too much of interest here.
* **Chapter 12: Vagueness, Uncertainty, and Degrees of Belief**
    * Good mathematical framework for fuzzy knowledge representation.
* **Chapter 13: Abductive Reasoning**
    * Logical abduction is the process of, given a logical statement `P & Q => R`, and assuming the truth of `P`, finding what `Q` must be true for `R` to be true.
    * `Q` is an "explanation" and must be conjunctive, which is nice.
    * I probably need to read this section more closely.
* **Chapter 14: Actions**
    * Introduction to situation calculus.
* **Chapter 15: Planning**
    * ... there's not too much of interest here.
* **Chapter 16: The Tradeoff Between Expressiveness and Tractability**
    * ... there's not too much of interest here.

`./documents/The_Handbook_of_Knowledge_Representation.pdf`

*Handbook of Knowledge Representation - Edited by Frank van Harmelen, Vladimir Lifschitz, Bruce Porter (2008)*

An excellent anthology of readings in the field. I would say it's best used as a reference (like the title suggests), so I'm not going to read it through at the moment.

## Background on testing knowledge representation approaches

`./documents/393484.ESWA_3237_final.pdf`

*Dynamic test generation over ontology-based knowledge representation in authoring shell - Branko Zitko, Slavomir Stankov, Marko Rosic, Ani Grubišic (2009)*

This is a kind of bullshit paper; it goes over how OWL can be used to teach students, but the expert data is authored by a human user, the data is hierarchically organized by a human user, and the students' sample was not specified at all. I assume it was a handful of students.

`./documents/Thimm_2014.pdf`

*Tweety: A Comprehensive Collection of Java Libraries for Logical Aspects of Artificial Intelligence and Knowledge Representation - Matthias Thimm (2014)*

This looks like a tool paper describing *Tweety*, which is a framework for testing knowledge representation systems. It's very similar to the topic at hand!

* Contains a citation for *Knowledge Representation and Reasoning (KR) (Brachman and Levesque 2004)*. 
* It's kind of the author jerking themselves off for 10 pages, but no actual results.
* Holy shit this project is still actively developed. It looks like by the same person.

 `./documents/tweety_kr2018.pdf`

 *Implementing KR Approaches with Tweety - Matthias Thimm (2018)*

 Basically, an example set for Tweety (see above). This is actually a really large and well-developed project. Not a lot of info about testing.

* "Evaluation is usually analytically, but experimental evaluation helps for trial-and-error purposes".

`./documents/Applying-Ontology-Knowledge-Representation-Technology-and-Semantic-Searching-Methods-to-Support-the-Production-of-High-Quality-Longan-Fruit.pdf`

*Applying Ontology Knowledge Representation Technology and Semantic Searching Methods to Support the Production of High Quality Longan Fruit - Winai Bangkhomned and Janjira Payakpate (2020)*

One of the few practical examples of KR being used for a real-world problem, but it's a very narrow use of KR. This papers overwhelmingly positive results are mostly driven by the fact that the KR is so transparent. Expert knowledge was obtained from human experts, and then experts (it's not clear if it was a different set of experts) rated the data. The sample size was only 3 experts for testing.

`./documents/s10799-019-00299-9.pdf`

*Knowledge representation for computational thinking using knowledge discovery computing - Youngseok Lee, Jungwon Cho (2019)*

* "In the era of the current Fourth Industrial Revolution, software is expected to become the center of value creation and innovation." Someone's been reading Marx....
* Again, separation between expert, teacher, and student "modules". This is similar to *Dynamic test generation over ontology-based knowledge representation in authoring shell - Branko Zitko, Slavomir Stankov, Marko Rosic, Ani Grubišic (2009)* (see above).
* This isn't really a knowledge representation paper as a CS concept, but more a study on an alternative way of testing academic performance in CS.

`https://www.frontiersin.org/articles/10.3389/fnbot.2020.00004/full`

*Semantic Knowledge Representation for Strategic Interactions in Dynamic Situations - Carlos Calvo Tapia, José Antonio Villacorta-Atienza, Sergio Díez-Hermano, Maxim Khoruzhko, Sergey Lobov, Ivan Potapov, Abel Sánchez-Jiménez and Valeri A. Makarov (2020)*

An interesting way of representing the problem of fencing as a learnable search-space. Very little to do with KR.

`./documents/Kalouli_2-46rla0c8u80e9.pdf`

*GKR: the Graphical Knowledge Representation for semantic parsing - Aikaterini-Lida Kalouli, Richard Crouch (2018)*

Discusses semantic analysis of English sentences via NLP methods. It contrasts AKR with GKR (a novel? method).

`./documents/1705.03202.pdf`

*Does William Shakespeare REALLY Write Hamlet? Knowledge Representation Learning with Confidence - Ruobing Xie, Zhiyuan Liu, Fen Lin, Leyu Lin (2018)*

Describes a novel method for noise reduction in large KR datasets.

`./documents/9834218.pdf`

*Some Criteria of the Knowledge Representation Method for an Intelligent Problem Solver in STEM Education - Hien D. Nguyen, Nhon V. Do, Nha P. Tran, Xuan Hau Pham, and Vuong T. Pham (2020)*

Seems very similar to *Dynamic test generation over ontology-based knowledge representation in authoring shell - Branko Zitko, Slavomir Stankov, Marko Rosic, Ani Grubišic (2009)*.

A little bit less bullshit, though. It describes the *Rela-Ops* KR model and provides two algorithms on it. It's pretty sparse on detailing how *Rela-Ops* could be actually used, though. This is one of the few KR models I have seen which uses inference rules within it (although I haven't seen too many, yet).

`./documents/1804.08207.pdf`

*Collecting Diverse Natural Language Inference Problems for Sentence Representation Evaluation - Adam Poliak, Aparajita Haldar, Rachel Rudinger, J. Edward Hu, Ellie Pavlick, Aaron Steven White, Benjamin Van Durme (2018)*

A reading list on different NLP datasets and how well they can be used for semantic analysis with KR. Not much detail on the KR part of this, honestly.

`./documents/63883.pdf`

*A Survey on Domain Knowledge Representation with Frames - Vladislavs Nazaruks and Jānis Osis (2017)*

A reading list of different ontological methods of learning about frame systems. A little too specific for this topic.

`./documents/E102.D_2019EDL8069.pdf`

*A Knowledge Representation Based User-Driven Ontology Summarization Method - Yuehang DING, Member, Hongtao YU, Jianpeng ZHANG, Huanruo LI, and Yunjie GU, Nonmembers (2019)*

Using *K-means++* to determine important facts in an ontology and to measure distances between concept vectors in an ontology.

## Background on data-driven knowledge acquisition approaches

`./documents/KSC2018_Umer.pdf`

*Blockchain Driven Knowledge Acquisition Systems: A General Framework - Umer Majeed and Choong Seon Hong (2018)*

This paper's ideology implies that it's a known fact that knowledge bases are prone to malicious attack. What the fuck...? Nothing really here.

`https://link.springer.com/article/10.1631/FITEE.1601883`

*Challenges and opportunities: from big data to knowledge in AI 2.0 - Yue-ting Zhuang, Fei Wu, Chun Chen & Yun-he Pan (2017)*

Talks about crowdsourced knowledge bases, but nothing too relevant here.

`./documents/5d105d0afb6581d250fd39ef_iProcess Enabling IoT Platforms in Data Driven Knowledge Intensive Processes.pdf`

*iProcess: Enabling IoT Platforms in Data-Driven Knowledge-Intensive Processes - Amin Beheshti, Francesco Schiliro, Samira Ghodratnama, Farhad Amouzgar, Boualem Benatallah, Jian Yang, Quan Z. Sheng, Fabio Casati, and Hamid Reza Motahari-Nezhad (2018)*

Discusses connecting multiple databases together into a *data lake* by using WordNet or similar to combine terms and items. There's a reason their results section is basically two sentences long and doesn't cover actual evaluation of the process (although they do mention that this will be a topic to be researched further in the future).

`./documents/3055462.pdf`

*Developing a Data-driven Medication Indication Knowledge Base using a Large Scale Medical Claims Database - Ying Li Ph.D., Cao Xiao Ph.D. (2019)*

Seems like a more well-researched version of *iProcess: Enabling IoT Platforms in Data-Driven Knowledge-Intensive Processes - Amin Beheshti, Francesco Schiliro, Samira Ghodratnama, Farhad Amouzgar, Boualem Benatallah, Jian Yang, Quan Z. Sheng, Fabio Casati, and Hamid Reza Motahari-Nezhad (2018)*. However, this paper has the unfair advantage of being sourced from semi-structured source datasets with standardizable terms.

`./documents/08319403.pdf`

*A Data-Driven Knowledge Acquisition System: An End-to-End Knowledge Engineering Process for Generating Production Rules - MAQBOOL ALI, RAHMAN ALI, WAJAHAT ALI KHAN, SOYEON CAREN HAN, JAEHUN BANG, TAEHO HUR, DOHYEONG KIM, SUNGYOUNG LEE, (Member, IEEE), AND BYEONG HO KANG (2018)*

* "The CRoss-Industry Standard Process for Data Mining (CRISP-DM) is a widely used systematic methodology for DM and DS system development."
* Looks like a tool for extracting information from already structured datasets.

`./documents/11524-Article (PDF)-21550-1-10-20190617.pdf`

*REBA: A Refinement-Based Architecture for Knowledge Representation and Reasoning in Robotics - Mohan Sridharan, Michael Gelfond, Shiqi Zhang, Jeremy Wyatt (2019)*

* Describes coarse and fine transition diagrams. Seems similar to situation calculus.
    * Fine transition stems from sensory input.
    * Coarse transition is for a higher-level domain.
    * These are "tightly coupled".
* Uses an answer set prolog (ASP)?
* The coupling is done via a semi-supervised algorithm.
* "The zoomed
fine-resolution system description, and a probabilistic representation of the uncertainty in sensing and actuation, are used to construct a partially observable Markov decision process (POMDP). The policy obtained by solving the POMDP is invoked repeatedly to implement the abstract transition as a sequence of concrete actions. The fine-resolution outcomes of executing these concrete actions are used to infer coarse-resolution outcomes that are added to the coarse-resolution history and used for subsequent coarse-resolution reasoning."
* The paper describes how KR and reasoning can be used to drive robotic actions to achieve results.
* This is the best paper in the field.

`./documents/1812.10901.pdf`

*Knowledge Representation Learning: A Quantitative Review - Yankai Lina, Xu Hana, Ruobing Xiea, Zhiyuan Liua, Maosong Sun (2018)*

This is a very data-science oriented anthology of existing research.

`./documents/master_Hovi_Juha_2019.pdf`

*Data-driven generation of rules for ontology-based decision making systems in autonomous vehicles - Juha Hovi (2019)*

* This is very closely related to the topic at hand.
* "A field within machine learning focused on learning of this nature is called rule-based machine learning (RBML)."
* "ROS is an open source framework widely used for development of robotics applications that offers multiple ready-made packages for common tasks in robotics."
* This solution uses RDF.
* "The Apriori algorithm was chosen for discovering frequent itemsets in the data."
* This solution is relatively supervised.

`./documents/10.1.1.465.490.pdf`

*A General Game Description Language for Incomplete Information Games - Michael Thielscher (2010)*

Describes a framework for formalizing games.

`https://link.springer.com/article/10.1007/s13218-018-0564-6#Abs1`

*A Brief Survey on Forgetting from a Knowledge Representation and Reasoning Perspective - Thomas Eiter & Gabriele Kern-Isberner (2019)*

Describes different methods of forgetting in KBs, but doesn't go much into comparing their effectiveness.

`./documents/227.pdf`

*Mimosa: using ontologies for modeling and simulation - Jean-Pierre Muller (????)*

A tool paper describing a simulation framework, but it's really vague.

`./documents/Hofmann2001_Article_UnsupervisedLearningByProbabil.pdf`

*Unsupervised Learning by Probabilistic Latent Semantic Analysis - THOMAS HOFMANN (2001)*

* "The key idea in LSA is to map high-dimensional count vectors, such as termfrequency (tf) vectors arising in the vector space representation of text documents (Salton & McGill, 1983), to a lower dimensional representation in a so-called latent semantic space."
* A very data-science driven approach.

`./documents/nihms-1050423.pdf`

*Learning Disentangled Semantic Representation for Domain Adaptation - Ruichu Cai, Zijian Li, Pengfei Wei, Jie Qiao, Kun Zhang, Zhifeng Hao (2019)*

This paper is incredibly hard to read, but luckily it seems to not have a huge amount of bearing on the topic at hand.

`./documents/WS96-05-002.pdf`

*Asking Queries about Frames - Alexander Borgida and Deborah L. McGuinness (1996)*

It seems to be some kind of pattern matching on framed knowledge? It's kind of hard to read.

`./documents/E100.D_2016EDP7337.pdf`

*Ontology-Based Driving Decision Making: A Feasibility Study at Uncontrolled Intersections - Lihua ZHAO, Nonmember, Ryutaro ICHISE, Member, Zheng LIU, Nonmember, Seiichi MITA, Member, and Yutaka SASAKI, Nonmember (2017)*

* "To represent the stream data from the sensors equipped on the autonomous vehicles, we use timestamp-based temporal RDF representation to construct RDF Stream data [6]. Furthermore, to access the ontology-based data, we use SPARQL Protocol and RDF Query Language (SPARQL), which is a powerful RDF query language for accessing to static RDF data [7]."
* It's clear that *Data-driven generation of rules for ontology-based decision making systems in autonomous vehicles - Juha Hovi (2019)* is highly derivative from this work. Reading this paper is almost equivalent to reading Hovi, 2019.

`./documents/JSAI2018_1F102.pdf`

*Faster Ontology Reasoning with Typed Propositionalization - Maxime Clement, Ryutaro Ichise (2018)*

A good explanation and quantitative evaluation of typed propositions in optimizing KR reasoning. Great paper! Very short, easy to read, and has lots of good info and citations!

`./documents/hai18_vqaExplain.pdf`

*Non-monotonic Logical Reasoning and Deep Learning for Explainable Visual Question Answering - Heather Riley, Mohan Sridharan (2018)*

Discusses a generalized framework for using KR for augmenting deep learning frameworks for explainability. Uses feature extraction resulting in an ASP or decision tree.

`./documents/MohanSridharan_RainrTalk.pdf`

*Commonsense Reasoning and Knowledge Acquisition to Guide Deep Learning on Robots - Tiago Mota, Heather Riley, Mohan Sridharan (2019)*

* Discusses acquiring domain knowledge interactively!
* Basically a presentation on *REBA: A Refinement-Based Architecture for Knowledge Representation and Reasoning in Robotics - Mohan Sridharan, Michael Gelfond, Shiqi Zhang, Jeremy Wyatt (2019)*.

`./documents/Wagner_Answering_Visual_em_What-If_Questions_From_Actions_to_Predicted_Scene_ECCVW_2018_paper.pdf`

*Answering Visual What-If Questions: From Actions to Predicted Scene Descriptions - Misha Wagner, Hector Basevi, Rakshith Shetty, Wenbin Li, Mateusz Malinowski, Mario Fritz, and Ales Leonardis (2018)*

Application of KR learning techniques to physics simulations.

`./documents/2015_JNL_TRO_Zhang.pdf`

*Mixed Logical Inference and Probabilistic Planning for Robots in Unreliable Worlds - Shiqi Zhang, Mohan Sridharan, and Jeremy L. Wyatt (2015)*

Definitely a prior work to *REBA: A Refinement-Based Architecture for Knowledge Representation and Reasoning in Robotics - Mohan Sridharan, Michael Gelfond, Shiqi Zhang, Jeremy Wyatt (2019)*.

`./documents/POMDP_lecture.pdf`

*Partially Observable Markov Decision Processes (POMDPs) - Geoff Hollinger (2007)*

Decent introduction, but it's just a presentation. It needs more details to be fully understood.

`https://www.youtube.com/watch?v=-q61H11Lm0s`

*POMDP Partially Observable Markov Decision Process - José Vidal (2012)*

A video lecture on POMDPs. Very clear!

`./documents/1301.1386v1.pdf`

*SPARC – Sorted ASP with Consistency Restoring Rules - Evgenii Balai, Michael Gelfond, and Yuanlin Zhang (2013)*

The initial paper for SPARC.

`https://www.youtube.com/watch?v=um903nr4Ayo`

`https://www.youtube.com/watch?v=jWni8RyG0W8`

This person is GOD-TIER in terms of education.

`https://www.youtube.com/watch?v=d3arlJlGRTk`

Torsten Schaub made a video series on Potassco tools! Very informative.

`https://www.youtube.com/watch?v=fFacIqoDX6k`

The GOD-TIER person's take on the node coloring problem discussed by Schaub, but using Sparc instead.

`./documents/1907.13482.pdf`

*Bridging Commonsense Reasoning and Probabilistic Planning via a Probabilistic Action Language - Yi Wang, Shiqi Zhang, Joohyung Lee (2003)*

A much more prior work to *REBA: A Refinement-Based Architecture for Knowledge Representation and Reasoning in Robotics - Mohan Sridharan, Michael Gelfond, Shiqi Zhang, Jeremy Wyatt (2019)*.

`https://link.springer.com/article/10.1007/s10489-017-0988-y`

*Answer set programming for non-stationary Markov decision processes - Leonardo A. Ferreira, Reinaldo A. C. Bianchi, Paulo E. Santos & Ramon Lopez de Mantaras (2017)*

Basically what it says it is. A method of using ASP to optimize trajectories in MDPs. Needs more detail about how the reinforced learning model is used to mutate the ASP, though.

`./documents/IROS17-Lu.pdf`

*Leveraging Commonsense Reasoning and Multimodal Perception for
Robot Spoken Dialog Systems - Dongcai Lu, Shiqi Zhang, Peter Stone, and Xiaoping Chen (2017)*

P-log, the ASP variety of the authors' choice, claims to be more quantitative. However, it's literally ASP with the addition of fuzzy logic. This is applied to a POMDP.

`./documents/1804.07779.pdf`

*PEORL: Integrating Symbolic Planning and Hierarchical Reinforcement Learning for Robust Decision-Making - Fangkai Yang, Daoming Lyu, Bo Liu, Steven Gustafson (2018)*

Very similar to *Answer set programming for non-stationary Markov decision processes - Leonardo A. Ferreira, Reinaldo A. C. Bianchi, Paulo E. Santos & Ramon Lopez de Mantaras (2017)*, yet it doesn't cite it. Hmmm.....

`https://link.springer.com/article/10.1007/s13218-019-00616-y`

*Towards a Theory of Explanations for Human–Robot Collaboration - Mohan Sridharan & Ben Meadows (2019)*

Verrry vague. Used a similated "game" to test KR.

## Background on logical abduction

`./documents/KBSE01.pdf`

*On the Use of Logical Abduction in Software Engineering - ALESSANDRA RUSSO and BASHAR NUSEIBEH (2000)*

Too hard to read.

`./documents/https://arxiv.org/pdf/1906.00107.pdf`

*Out of Sight But Not Out of Mind: An Answer Set Programming Based Online Abduction Framework for Visual Sensemaking in Autonomous Driving - Jakob Suchan, Mehul Bhatt, and Srikrishna Varadarajan (2019)*

Interesting concept, not enough detail for reproduction on its own.

`./documents/8548-bridging-machine-learning-and-logical-reasoning-by-abductive-learning.pdf`

*Bridging Machine Learning and Logical Reasoning by Abductive Learning - Wang-Zhou Dai, Qiuling Xu, Yang Yu, Zhi-Hua Zhou (2019)*

Very optimistic, but not too much new provided.

`./documents/Abduction.pdf`

*A Case for Abductive Reasoning over Ontologies - Corinna Elsenbroich, Oliver Kutz, and Ulrike Sattler (????)*

Based on description logic, not predicate logic. Definitely interesting, though.



## Background on agent simulations

`./documents/1121-Article Text-1118-1-10-20080129.pdf`

*Intelligent Agents for Interactive Simulation Environments - Milind Tambe, W. Lewis Johnson, Randolph M. Jones, Frank Koss, John E. Laird, Paul S. Rosenbloom, and Karl Schwamb (1995)*

Very military, much coroporate. Mentions a unified theory of computer cognition. Did I mention this was written in 1995?

`./documents/2007.04954.pdf`

*ThreeDWorld: A Platform for Interactive Multi-Modal Physical Simulation - Chuang Gan, Jeremy Schwartz, Seth Alter, Martin Schrimpf, James Traer, Julian De Freitas , Jonas Kubilius, Abhishek Bhandwaldar, Nick Haber, Megumi Sano, Kuno Kim, Elias Wang, Damian Mrowca, Michael Lingelbach, Aidan Curtis, Kevin Feigelis, Daniel M. Bear, Dan Gutfreund, David Cox, James J. DiCarlo, Josh McDermott, Joshua B. Tenenbaum, Daniel L.K. Yamins (2020)*

A really good simulation.

`./documents/0060.pdf`

*Networks dynamics and information sharing: an agent-based simulation approach for the sharing economy - Stefano Za, M. Gisela Bardossy, Eusebio Scornavacca (2019)*

Using AI to model how memes are shared.

`./documents/2004.05363.pdf`

*WES: Agent-based User Interaction Simulation on Real Infrastructure - John Ahlgren, Maria Eugenia Berezin, Kinga Bojarczuk, Elena Dulskyte, Inna Dvortsova, Johann George, Natalija Gucevska, Mark Harman, Ralf Lämmel, Erik Meijer, Silvia Sapora, Justin Spahr-Summers (2020)*

Facebook is creating simulated models of its users. Figures.


`./documents/AIToMicrobeArchitectureSimulationIntelligenceConciousness.pdf`

*AI-to-Microbe Architecture: Simulation, Intelligence, Consciousness - Dennis Dollens (2019)*

Is AI really alive? No. The answer is no, but nice try.

`./documents/08865095.pdf`

*Improved Multi-Agent Deep Deterministic Policy Gradient for Path Planning-Based Crowd Simulation - SHANGFEI ZHENG AND HONG LIU (2019)*

Mentions deep reinforcement learning.

`./documents/8760-on-the-utility-of-learning-about-humans-for-human-ai-coordination.pdf`

*On the Utility of Learning about Humans for Human-AI Coordination - Micah Carroll, Rohin Shah, Mark K. Ho, Thomas L. Griffiths, Sanjit A. Seshia, Pieter Abbeel, Anca Dragan (2019)*

* Mentions that agents that learn based on human behavior are less optimimal than agents that self-learn, but are better performing with other human players.
* Uses a simulated model based on a popular video game.

`./documents/2002.11174.pdf`

*TANKSWORLD: A MULTI-AGENT ENVIRONMENT FOR AI SAFETY RESEARCH - Corban G. Rivera, Olivia Lyons, Arielle Summitt, Ayman Fatima, Ji Pak, William Shao, Robert Chalmers, Aryeh Englander, Edward W. Staley, I-Jeng Wang, Ashley J. Llorens (2020)*

Very brief.

`./documents/KadlecCAVE2012.pdf`

*Generating Corpora of Activities of Daily Living and Towards Measuring the Corpora’s Complexity - Rudolf Kadlec, Michal Cerm´ak, Zdenˇek Behan, and Cyril Brom (????)*

Discussing day-planning from an AI planning point of view. Describes a number of decent measurements of agent "believability".

`./documents/30276882.pdf`

*An automatic dialog simulation technique to develop and evaluate interactive conversational agents - David Griol, Javier Carbó, and José M. Molina (2013)*

Way too constrained to be useful to this topic.

`./documents/P14-1047.pdf`

*Single-Agent vs. Multi-Agent Techniques for Concurrent Reinforcement Learning of Negotiation Dialogue Policies - Kallirroi Georgila, Claire Nelson, David Traum (2014)*

Way too constrained to be useful to this topic.


## Background on symbolically-augmented machine learning

`https://towardsdatascience.com/open-ai-gym-classic-control-problems-rl-dqn-reward-functions-16a1bc2b007`

*Reward Engineering for Classic Control Problems on OpenAI Gym - Sachin (2019)*

A simple explanation of custom reward functions.

`./documents/11175-Article Text-20703-1-10-20180420.pdf`

*From Skills to Symbols: Learning Symbolic Representations for Abstract High-Level Planning - George Konidaris, Leslie Pack Kaelbling, Tomas Lozano-Perez (2018)*

Appears to be about going from machine learned policies to symbolic policies. Mentions hierarchical reinforcement learning. It appears to be starting with a set of high-level skills and then learning low-level skills autonomously from them. Cool idea! Used an option policy for abstraction, but didn't seem to justify using that over a more traditional deep learning method.

`./documents/68917.pdf`

*Building Symbolic Representations of Intuitive Real-time Skills from Performance Data - D. Michie and R. Camacho (????)*

Using C4.5 (a decision tree learning algorithm) to replicate an agent's behavior using a symbolic "program".

`./documents/xu18h.pdf`

*A Semantic Loss Function for Deep Learning with Symbolic Knowledge - Jingyi Xu, Zilu Zhang, Tal Friedman, Yitao Liang, Guy Van den Broeck (2018)*

Mentions representation learning. Discussion of using logical features as outputs to a neural network and provides a framework for differentiating this for loss calculation.
