### <ins>Probabilistic verification</ins>

#### <span style="color:blue">Verification of stochastic games</span>

#### Verification of continuous-time Markov models

#### Perturbation analysis and robust verification
We identify discrepancies between a stochastic model used in probabilistic verification and the real-world system it represents when the model is built from statistical data. The issue, which is was overlooked for many years, is that a tiny but nontrivial change to model quantities may lead to misleading or even invalid verification results. We present rigours, mathematical formulation of the problem, with important steps towards a systematic solution. Empirical studies show that the novel notion of asymptotic perturbation bounds can accurately estimate maximum variations of verification results induced by model perturbations.

##### Selected papers

- Guoxin Su, Yuan Feng, Taolue Chen, and David S. Rosenblum. Perturbation Analysis of Stochastic Systems with Empirical Distribution Parameters: An Asymptotic Approach. IEEE Trans. Software Eng. 42(7): 623-639, 2016.
- Guoxin Su, Taolue Chen, Yuan Feng, and David S. Rosenblum.  ProEva: Runtime Proactive Performance Evaluation Based on Continuous-Time Markov Chains. ICSE'17, 2017, IEEE/ACM.
- Guoxin Su, Taolue Chen, Yuan Feng, David S. Rosenblum, and P. S. Thiagarajan. An Iterative Decision-Making Scheme for Markov Decision Processes and Its Application to Self-Adaptive Systems. FASE’16. LNCS 9633 pp. 269-286, 2016.
- Taolue Chen, Yuan Feng, David Rosenblum, Guoxin Su.  Perturbation Analysis in Verification of Discrete-Time Markov Chains. CONCUR’14, LNCS 8704, pp. 218-233, 2014. 
- Taolue Chen, Tingting Han, Marta Z. Kwiatkowska. On the complexity of model checking interval-valued discrete time Markov chains. Information Processing Letters 113(7): 210-216, 2013.

### <ins>Program analysis and constraint solving</ins>

#### String constraint solving
String constraint solving is important in a wide range of areas, e.g., program analysis and web security. Previous studies either provide rather fragmented theoretical results on its decidability/complexity, or practical algorithms without completeness guarantees. We identify novel semantical---as opposed to previously syntactic---conditions for string constraints which entail decidability, providing effective decision procedures with detailed complexity analysis, and importantly, efficient implementation as a new string solver Ostrich. The experiments demonstrate the efficacy of the new solver against other competitive solvers. In contrast to previous work, the solver achieves efficiency but without sacrificing theoretical guarantees. 

##### Selected papers:
- Taolue Chen, Matthew Hague, Anthony Lin, Philipp Ruemmer, Zhilin Wu. Decision Procedures for Path Feasibility of String-Manipulating Programs with Complex Operations. POPL'19. PACMPL 3(POPL): 49:1-49:30, 2019.
- Taolue Chen, Yan Chen, Matthew Hague, Anthony W. Lin, Zhilin Wu. What Is Decidable about String Constraints with the ReplaceAll Function. Proceedings of the ACM on Programming Languages, Vol. 2, No. POPL, Article 3. 2018.

**Tools**: [Ostrich](https://github.com/pruemmer/ostrich)

#### Separation logic
- Chong Gao, Taolue Chen, Zhilin Wu. Separation Logic with Linearly Compositional Inductive Predicates and Set Data Constraints. 45th International Conference on Current Trends in Theory and Practice of Computer Science (SOFSEM), LNCS 11,376, 206-220, Springer, 2019.  
- Taolue Chen, Fu Song, and Zhilin Wu. Tractability of Separation Logic with Inductive Definitions: Beyond Lists. 28th International Conference on Concurrency Theory (CONCUR'17),  LIPIcs 85, 37:1-37:17, 2017.
- Zhaowei Xu, Taolue Chen, Zhilin Wu. Satisfiability of Compositional Separation Logic with Tree Predicates and Data Constraints. The 26th International Conference on Automated Deduction (CADE-26). LNCS 10395, pp. 509-527, 2017.
- Xincai Gu, Taolue Chen, and Zhilin Wu. A complete decision procedure for linearly compositional separation logic with data constraints. IJCAR’16, LNCS 9706, pp. 532-549, 2016.

#### Side-channel attacks
- Pengfei Gao, Hongyi Xie, Jun Zhang, Fu Song, Taolue Chen. Quantitative Verification of Masked Arithmetic Programs against Side-Channel Attacks. TACAS'19. LNCS 11,427. Springer. 2019.
 
#### Android Multitasking Mechanism
We propose Android Stack Machine (ASM), a formal model to capture key mechanisms of Android multi-tasking such as activities, back stacks, launch modes, as well as task affinities. The model is based on pushdown systems with multiple stacks, and focuses on the evolution of the back stack of the Android system when interacting with activities carrying specific launch modes and task affinities. For formal analysis, we study the reachability problem of ASM. While the general problem is shown to be undecidable, we identify expressive fragments for which various verification techniques for pushdown systems or their extensions are harnessed to show decidability of the problem.

- Jinlong He, Taolue Chen, Ping Wang, Zhilin Wu, Jun Yan. Android Multitasking Mechanism: Formal Semantics and Static Analysis of Apps. APLAS’19, 2019. 
Taolue Chen, Jinlong He, Fu Song, Guozhen Wang, Zhilin Wu, and Jun Yan. Android Stack Machine. 30th International Conference on Computer Aided Verification (CAV'18). LNCS 10,982, 487-504, 2018.

### <ins>Software engineering</ins>

#### Automatic Detection and Repair Recommendation of Directive Defects in Java API Documentation 
APIs represent key tools for software developers. Unfortunately, API providers tend to release incomplete or inconsistent API documentation, which deviates from the actual API implementation. This paper is significant because it is the first time that the issue of inconsistency between API code and its documentation was formally investigated, with a novel method---with tool implementation---to automatically detect and repair defects from API documents. The empirical evaluation shows that the approach and the associated tool are able to find confirmed defects of documents for JDK 1.8 APIs and Android 7.0.

##### Selected papers:

- Yu Zhou, Changzhi Wang, Xin Yan, Taolue Chen, Sebastiano Panichella, Harald Gall. Automatic Detection and Repair Recommendation of Directive Defects in Java API Documentation. IEEE Trans. Software Eng.  (Conference version was presented in ICSE'17.)  
- Yu Zhou, Xin Yan, Taolue Chen, Sebastiano Panichella, Harald Gall. DRONE: A Tool to Detect and Repair Directive Defects in Java APIs Documentation. ICSE’19, 
**Tool**: [DRONE](https://spanichella.github.io/tools.html#drone-tool), and a [demo video](https://youtu.be/NDPXiapxoMk)

#### Code recommendation

- Yu Zhou, Yanqi Su, Taolue Chen, Zhiqiu Huang, Harald Gall, Sebastiano Panichella. [User Review-Based Change File Localization for Mobile Applications](pub-papers/tse20.pdf). IEEE Trans. on Software Eng.

#### Comments generation
Code comments are crucial to program comprehension. We propose a novel approach ContextCC to automatically generate concise comments for Java methods based on neural networks, leveraging techniques of program analysis and natural language processing.  

#### User review analysis

### <ins>Verification meets AI</ins>

- #### Verification of multi-agent systems
- Yedi Zhang, Fu Song, Taolue Chen. Making Agents’ Abilities Explicit. IEEE Access 7(1), 101,804-101,819, 2019.
- Fu Song, Yedi Zhang, Taolue Chen, Yu Tang, Zhiwu Xu. Probabilistic Alternating-Time mu-Calculus. AAAI’19, pp. 6179-6186. 2019.
- Taolue Chen, Fu Song, and Zhilin Wu. Model Checking Pushdown Epistemic Game Structures. 19th International Conference on Formal Engineering Methods (ICFEM'17). LNCS 10610, pp. 36-53, 2017
- Taolue Chen, Fu Song, and Zhilin Wu. Verifying Pushdown Multi-Agent Systems against Strategy Logics. IJCAI’16, pp. 180-186, AAAI Press, 2016.
- Taolue Chen, Fu Song, and Zhilin Wu. Global Model Checking on Pushdown Multi-Agent Systems. AAAI’16, pp. 2459-2465, AAAI Press, 2016.
- Hengjun Zhao, Xia Zeng, Taolue Chen, Zhimin Liu. Synthesizing Barrier Certificates Using Neural Networks. HSCC'20. To appear. 

### <ins> Axiomatisation of process algebra</ins>
#### Semantics in the linear time–branching time spectrum

Van Glabbeek presented the linear time–branching time spectrum of behavioural semantics. He studied these semantics in the setting of the basic process algebra BCCSP, and gave finite, sound and ground-complete, axiomatisations for most of these semantics. Groote proved for some of van Glabbeek’s axiomatisations that they are ω-complete, meaning that an equation can be derived if (and only if) all of its closed instantiations can be derived. We settle the remaining open questions for all the semantics in the linear time–branching time spectrum, either positively by giving a finite sound and ground-complete axiomatisation that is ω-complete, or negatively by proving that such a finite basis for the equational theory does not exist. 

##### Selected papers:

- Taolue Chen and Wan Fokkink. The Saga of Finite Equational Bases over BCCSP. NVTI (Dutch Association for Theoretical Computer Science) Newsletter, 2010 (Invited contribution).
- Taolue Chen, Wan Fokkink, Rob J. van Glabbeek. On the Axiomatizability of Impossible Futures. Logical Methods in Computer Science, 11(3:17): 1-30, 2015.
- Taolue Chen, Wan Fokkink and Rob van Glabbeek. On Finite Bases for Weak Semantics: Failures versus Impossible Futures. 35th International Conference on Current Trends in Theory and Practice of Computer Science (SOFSEM'09). Lecture Notes in Computer Science 5404, pp. 167-180, Springer, 2009.
- Taolue Chen, Wan Fokkink and Rob van Glabbeek. Ready to Preorder: The Case of Weak Process Semantics. Information Processing Letters 109(2): 104-111, Elsevier, 2008.
- Taolue Chen and Wan Fokking. On the Axiomatizability of Impossible Futures: Preorder versus Equivalence. The Twenty-Third Annual IEEE Symposium on Logic in Computer Science (LICS'08), pp. 156-165.
- Taolue Chen, Wan Fokkink, Bas Luttik and Sumit Nain. On Finite Alphabets and Infinite Bases. Information and Computation 206(5): 492-519, Elsevier, 2008.
- Taolue Chen and Wan Fokkink. On Finite Alphabets and Infinite Bases III: Simulation. 17th Conference on Concurrency Theory (CONCUR'06), Lecture Notes in Computer Science, Springer, 2006.
- Taolue Chen, Wan Fokkink and Sumit Nain. On Finite Alphabets and Infinite Bases II: Completed and Ready Simulation. 9th Conference on Foundations of Software Science and Computation Structures (FoSSaCS'06), Lecture Notes in Computer Science 3921, Springer, 2006.

#### Priority operator

- Luca Aceto, Taolue Chen, Anna Ingolfsdottir, Bas Luttik and Jaco van de Pol. On the Axiomatizability of Priority II. TCS. 412(28): 3035-3044, 2011.
- Luca Aceto, Taolue Chen, Wan Fokkink and Anna Ingolfsdottir. On the Axiomatizability of Priority. Mathematical Structure in Computer Science 18(1): 5-28, Cambridge University Press, 2008. (Conference version appeared in ICALP'06).

- #### Prefix iteration

- Taolue Chen and Jian Lu. Complete Axiomatization for Divergent-sensitive Bisimulations in Basic Process Algebra with Prefix Iteration. The First International Conference on Foundations of Informatics, Computing and Software (FICS'08). Electronic Notes in Theoretical Computer Science 212: 55-70. Elsevier. 
- Taolue Chen, Tingting Han and Jian Lu. On the Complete Axiomatization for Prefix Iteration modulo Observation Congruence. Acta Cybernetica: 17(3), 2006.
