# Papers for Hardware Formal Verification

Credit to git repo [jdnklau/fm-ml](https://github.com/jdnklau/fm-ml) and [wcventure/FuzzingPaper](https://github.com/wcventure/FuzzingPaper#difuzzrtl-differential-fuzz-testing-to-find-cpu-bug-sp-2021). I use the markdown format from [wcventure/FuzzingPaper](https://github.com/wcventure/FuzzingPaper#difuzzrtl-differential-fuzz-testing-to-find-cpu-bug-sp-2021) and get some paper resources from [jdnklau/fm-ml](https://github.com/jdnklau/fm-ml).

The papers I selected on here are all from top publication venues. All the selected conferences and jornals have good reputation and well-known. To see the full name and access to the homepage of those confereces and jornal, please refer to the [appendix](#appendix).

## **Content**

1. Papers
   1. [Classification according to Publication](#papers-classified-by-publication)
   2. [Classification according to Subject](#papers-classified-by-subject)
2. [Researchers](#researchers-to-follow-up)
3. [Details of Papers](#details-of-papers)
4. [Appendix](#appendix)

## Papers Classified by Publication

- **Survey/Review**
  - Algorithms for verifying deep neural networks, arxiv 2020
  - A convex relaxation barrier to tight robustness verification of neural networks, NeurIPS 2019
  - A survey of side-channel attacks on caches and countermeasures, 2018
  - ML + FV = ? A Survey on the Application of Machine Learning to Formal Verification, 2018
- **FMCAD**
  - [IC3 with Internal Signals, 2021](#ic3-with-internalignals)
  - End-to-End Formal Verification of a RISC-V Processor Extended with Capability Pointers, 2021
  - [Robustness between Weak Memory Models, 2021](#robustness-between-weak-memory-models)
  - A Multithreaded Vampire with Shared Persistent Grounding, 2021
  - Data-driven Optimization of Inductive Generalization, 2021
  - [Distributed Bounded Model Checking, 2020](#distributed-bounded-model-checking)
  - [Efficient implementation of property directed reachability, 2011](#efficient-implementation-of-property-directed-reachability)
- **VMCAI**
  - Synthesizing Environment Invariants for Modular Hardware Verification, 2020
  - A Cooperative Parallelization Approach for Property-Directed k-Induction, 2020
  - [SAT-Based Model Checking without Unrolling, 2011](#sat-based-model-checking-without-unrolling)
- **CAV**
  - Pono: A Flexible and Extensible SMT-Based Model Checker, 2021
  - [Code2Inv: A Deep Learning Framework for Program Verification, 2020](#code2inv-a-deep-learning-framework-for-program-verification)
  - StringFuzz: A fuzzer for string solvers, 2018
  - [End-to-End Verification of ARM Processors with ISA-Formal, 2016](#end-to-end-verification-of-arm-processors-with-isa-formal)
  - [ICE: A Robust Framework for Learning Invariants, 2014](#ice-a-robust-framework-for-learning-invariants)
- **DAC**
  - [A Formal Approach for Detecting Vulnerabilities to Transient Execution Attacks in Out-of-Order Processors, 2020](#a-formal-approach-for-detecting-vulnerabilities-to-transient-execution-attacks-in-out-of-order-processors)
- **DATE**
  - When Capacitors Attack: Formal Method Driven Design and Detection of Charge-Domain Trojans, 2019 (best paper)
- **ICCAD**
  - DATC RDF-2019: Towards a Complete Academic Reference Design Flow, 2019
- **MICRO**
  - [Checkmate: Automated synthesis of hardware exploits and security litmus tests, 2018](#checkmate-automated-synthesis-of-hardware-exploits-and-security-litmus-tests)
- **TACAS**
  - [SAT Solving with GPU Accelerated Inprocessing, 2021](#sat-solving-with-gpu-accelerated-inprocessing)
  - [MachSMT: A Machine Learning-based Algorithm Selector for SMT Solvers, 2021](#machsmt-a-machine-learning-based-algorithm-selector-for-smt-solvers)
  - [AVR: Abstractly Verifying Reachability, 2020](#avr-abstractly-verifying-reachability)
  - Software Verification with PDR: An Implementation of the State of the Art, 2020
  - Multi-agent Safety Verification Using Symmetry Transformations, 2020
- **TODAES**
  - Instruction-Level Abstraction (ILA): A Uniform Specification for System-on-Chip (SoC) Verification, 2020 (best paper)
- **ECAI**
  - Verification of Recurrent Neural Networks for Cognitive Tasks via Reachability Analysis, 2020
- **PLDI**
  - Abstract Interpretation under Speculative Execution, 2019
  - [A Data-Driven CHC Solver, 2018](#a-data-driven-chc-solver)
- **CCS**
  -  A Formal Foundation for Secure Remote Execution of Enclaves, 2017 (best paper)
- **HVC** 
- **NFM**
- **POPL**
- **ASPLOS**
- **ASP-DAC**
- **Arxiv**
  - Fuzzing Hardware Like Software, 2021
  - System-on-Chip Security Assertions, 2020
- **Others**
  - Abstraction mechanisms for hardware verification, *VLSI Specification, Verification and Synthesis* 1988
  - [Heuristic Model Checking using a Monte-Carlo Tree Search Algorithm, GECCO 2015](#heuristic-model-checking-using-a-monte-carlo-tree-search-algorithm)

## Papers Classified by Subject

- **Survey/Review**
  - Algorithms for verifying deep neural networks, arxiv 2020
  - A convex relaxation barrier to tight robustness verification of neural networks, NeurIPS 2019
  - A survey of side-channel attacks on caches and countermeasures, 2018
  - ML + FV = ? A Survey on the Application of Machine Learning to Formal Verification, arxiv 2018
- **Model Checking**
  - SAT-Based Model Checking without Unrolling, VMCAI 2011
  - Efficient implementation of property directed reachability, FMCAD 2011
- **Formal Verification Acceleration**
  - SAT Solving with GPU Accelerated Inprocessing, TACAS 2021
  - Distributed Bounded Model Checking, FMCAD 2020
  - A Cooperative Parallelization Approach for Property-Directed k-Induction, VMCAI 2020
- **Neural Network Verification**
  - The Marabou Framework for Verification and Analysis of Deep Neural Networks,CAV 2019
  - Towards Scalable Complete Verification of ReLU Neural Networks via Dependency-based Branching, IJCAI 2021
  - (Look for VNN-COMP for the latest solvers and techniques)
- **Side-Channel Attack**
  - A Formal Approach for Detecting Vulnerabilities to Transient Execution Attacks in Out-of-Order Processors, 2020
  - Abstract Interpretation under Speculative Execution, PLDI 2019
  - When Capacitors Attack: Formal Method Driven Design and Detection of Charge-Domain Trojans, DATE 2019
  - Checkmate: Automated synthesis of hardware exploits and security litmus tests, MICRO 2018
- **Weak Memory Model**
  - Herding Cats: Modelling, Simulation, Testing, and Data Mining for Weak Memory, TOPLAS14
  - Robustness between Weak Memory Models, FMCAD 2021
- **AI+Formal**
  - MachSMT: A Machine Learning-based Algorithm Selector for SMT Solvers, TACAS 2021
  - Code2Inv: A Deep Learning Framework for Program Verification, CAV 2020
  - A Data-Driven CHC Solver, PLDI 2018
  - ICE: A Robust Framework for Learning Invariants, CAV 2014
- **Fuzzing**
  - StringFuzz: A fuzzer for string solvers, CAV 2018
- **Logic Design and Verification**
- **Firmware and Systems-on-Chip Security**

## Researchers to Follow-up

1. **U.S.**
   1. [Timothy Trippel](https://timothytrippel.com) (Hardware security, side-channel attack)
   2. [Caroline Trippel](https://cs.stanford.edu/people/trippel/) (Formal verification for hardware security)
   3. [Aman Goel](https://aman-goel.github.io) (The main developer of AVR, IC3po)
   4. [Xiaolong Guo](https://www.ece.k-state.edu/people/faculty/guo/) (Formal verification for side-channel attack prevention on hardware)
   5. [Xujie Si](https://www.cs.mcgill.ca/~xsi/#research) (AI + Formal researcher)
   6. [He Zhu](https://herowanzhu.github.io/#publication) (Author of data-driven CHC solver)
   7. [Kaidi Xu](https://kaidixu.com/) (Expert on neural network verification)
2. **Europe**
   1. [JKU-Institute for Formal Models and Verification Group](http://fmv.jku.at/index.html) (Organizer of HWMCC'20, has good publication record in formal verification)
   2. [TU Graz-IAIK](https://www.iaik.tugraz.at/research-area/formalmethods/) (Focus on formal method and computer security)
   3. [Clifford Wolf](http://www.clifford.at) (From [SymbioticEDA](http://www.symbioticeda.com), conducting research on [riscv-formal](https://github.com/SymbioticEDA/riscv-formal)) 
   4. [Cambridge-REMS](https://www.cl.cam.ac.uk/~pes20/rems/) (ISA-formal)
3. **Asia**
   1. [Yibo Lin](https://scholar.google.com/citations?user=155hQCcAAAAJ&hl=en) (Implement ML for routing and placement)
   2. [Aquinas Hobor](https://www.comp.nus.edu.sg/~hobor/) (Expert on formal verification and computer  security)
   3. [Kuldeep S. Meel](https://www.comp.nus.edu.sg/~meel/) (Expert on AI, security and formal verification)

## Details of Papers

### End-to-End Verification of ARM Processors with ISA-Formal

* <img src="image/pdf_24px.png">[Paper](https://alastairreid.github.io/papers/cav2016_isa_formal.pdf)
* <img src="image/ppt_24px.png">[Slide](https://alastairreid.github.io/papers/cav2016_isa_formal-slides.pdf)

**Abstract:** This paper describes how ARM has overcome these issues in our Instruc- tion Set Architecture Formal Verification framework “ISA-Formal.” This is an end-to-end framework to detect bugs in the datapath, pipeline con- trol and forwarding/stall logic of processors. A key part of making the approach scale is use of a mechanical translation of ARM’s Architecture Reference Manuals to Verilog allowing the use of commercial model checkers. ISA-Formal has proven especially effective at finding micro- architecture specific bugs involving complex sequences of instructions. An essential feature of our work is that it is able to scale all the way from simple 3-stage microcontrollers, through superscalar in-order processors up to out-of-order processors. We have applied this method to 8 different ARM processors spanning all stages of development up to release. In all processors, this has found bugs that would have been hard for conventional simulation-based verification to find and ISA-Formal is now a key part of ARM’s formal verification strategy. To the best of our knowledge, this is the most broadly applicable formal verification technique for verifying processor pipeline control in mainstream commercial use.

###  SAT-Based Model Checking without Unrolling

* <img src="image/pdf_24px.png">[Paper](http://alcom.ee.ntu.edu.tw/system/privatezone/meetingfile/201010222258251.pdf)

**Abstract:** A new form of SAT-based symbolic model checking is described. Instead of unrolling the transition relation, it incrementally gen- erates clauses that are inductive relative to (and augment) stepwise ap- proximate reachability information. In this way, the algorithm gradually refines the property, eventually producing either an inductive strengthen- ing of the property or a counterexample trace. Our experimental studies show that induction is a powerful tool for generalizing the unreachability of given error states: it can refine away many states at once, and it is effective at focusing the proof search on aspects of the transition system relevant to the property. Furthermore, the incremental structure of the algorithm lends itself to a parallel implementation.

### Efficient implementation of property directed reachability

* <img src="image/pdf_24px.png">[Paper](https://www.cs.utexas.edu/~ragerdl/fmcad11/papers/7.pdf)

**Abstract:** Last spring, in March 2010, Aaron Bradley published the first truly new bit-level symbolic model checking algorithm since Ken McMillan’s interpolation based model checking pro- cedure introduced in 2003. Our experience with the algorithm suggests that it is stronger than interpolation on industrial prob- lems, and that it is an important algorithm to study further. In this paper, we present a simplified and faster implementation of Bradley’s procedure, and discuss our successful and unsuccessful attempts to improve it.

### IC3 with Internal Signals

* <img src="image/pdf_24px.png">[Paper](https://www.rohitdureja.com/papers/DGIV21.pdf)

**Abstract:** IC3 is a highly-effective algorithm for formal hard- ware verification. It cleverly uses a SAT solver to compute an inductive invariant, an over-approximation of reachable states, of a hardware design. The invariant is computed in CNF as a conjunction of lemmas. This CNF representation over state variables, although efficient, leads to an obvious deficiency: IC3 is not effective for designs that do not have a concise CNF invariant over state variables. We show how to remedy this deficiency by extending traditional IC3 to learn invariants not only in terms of state variables, but also in terms of internal signals of the design. Our proposed method can learn significantly more compact invariants than IC3, while maintaining a highly-efficient CNF representation. We evaluate our technique on several industrial sequential equivalence checking (SEC) problems from IBM, SEC problems derived from designs in the Hardware Model Checking Competition (HWMCC) and SEC problems from academia. In addition, we evaluate it on HWMCC benchmarks. IC3 with internal signals is efficient for SEC and outperforms traditional IC3 on an important class of benchmarks.

### Robustness between Weak Memory Models

* <img src="image/pdf_24px.png">[Paper](https://www.st.ewi.tudelft.nl/sschakraborty/paper.pdf)

**Abstract:** Robustness of a concurrent program ensures that its behaviors on a weak concurrency model are indistinguishable from those on a stronger model. Enforcing robustness is particularly useful when porting or migrating applications between architectures. Existing tools mostly focus on ensuring sequential consistency (SC) robustness which is a stronger condition and may result in unnecessary fences. To address this gap, we analyze and enforce robustness between weak memory models, more specifically for two main- stream architectures: x86 and ARM (versions 7 and 8). We iden- tify robustness conditions and develop analysis techniques that facilitate porting an application between these architectures. To the best of our knowledge, this is the first approach that addresses robustness between the hardware weak memory models. We implement our robustness checking and enforcement procedure as a compiler pass in LLVM and experiment on a number of standard concurrent benchmarks. In almost all cases, our procedure terminates instantaneously and insert significantly less fences than the naive schemes that enforce SC-robustness.

### Distributed Bounded Model Checking

* <img src="image/pdf_24px.png">[Paper](https://arxiv.org/pdf/2005.08063.pdf)

**Abstract:** Program verification is a resource-hungry task. This paper looks at the problem of parallelizing SMT-based automated program verification, specifically bounded model-checking, so that it can be distributed and executed on a cluster of machines. We present an algorithm that dynamically unfolds the call graph of the program and frequently splits it to create sub-tasks that can be solved in parallel. The algorithm is adaptive, controlling the splitting rate according to available resources, and also leverages information from the SMT solver to split where most complexity lies in the search. We implemented our algorithm by modifying CORRAL, the verifier used by Microsoft’s Static Driver Verifier (SDV), and evaluate it on a series of hard SDV benchmarks. 

### Code2Inv: A Deep Learning Framework for Program Verification

* <img src="image/pdf_24px.png">[Paper](https://www.cis.upenn.edu/~mhnaik/papers/cav20.pdf)

**Abstract:** We propose a general end-to-end deep learning framework Code2Inv, which takes a verification task and a proof checker as input, and automatically learns a valid proof for the verification task by inter- acting with the given checker. Code2Inv is parameterized with an em- bedding module and a grammar: the former encodes the verification task into numeric vectors while the latter describes the format of solutions Code2Inv should produce. We demonstrate the flexibility of Code2Inv by means of two small-scale yet expressive instances: a loop invariant syn- thesizer for C programs, and a Constrained Horn Clause (CHC) solver.

### ICE: A Robust Framework for Learning Invariants

* <img src="image/pdf_24px.png">[Paper](http://madhu.cs.illinois.edu/CAV14ice.pdf)

**Abstract:** We introduceICE,a robust learning paradigm for synthesizing invari- ants, that learns using examples, counter-examples, and *implications*, and show that it admits honest teachers and strongly convergent mechanisms for invariant synthesis. We observe that existing algorithms for black-box abstract interpre- tation can be interpreted as ICE-learning algorithms. We develop new strongly convergent ICE-learning algorithms for two domains, one for learning Boolean combinations of numerical invariants for scalar variables and one for *quantified* invariants for arrays and dynamic lists. We implement these ICE-learning algo- rithms in a verification tool and show they are robust, practical, and efficient.

### A Formal Approach for Detecting Vulnerabilities to Transient Execution Attacks in Out-of-Order Processors

* <img src="image/pdf_24px.png">[Paper](https://dl.acm.org/doi/pdf/10.5555/3437539.3437752)

**Abstract:** Transient execution attacks, such as Spectre and Meltdown, create a new and serious attack surface in modern processors. In spite of all countermeasures taken during recent years, the cycles of alarm and patch are ongoing and call for a better formal understanding of the threat and possible preventions. This paper introduces a formal definition of security with respect to transient execution attacks, formulated as a HW property. We present a formal method for security verification by HW property checking based on extending *Unique Program Execution Checking (UPEC)* to out-of-order processors. UPEC can be used to systematically detect all vulnerabilities to transient execution attacks, including vulnerabilities unknown so far. The feasibility of our approach is demonstrated at the example of the BOOM processor, which is a design with more than 650,000 state bits. In BOOM our approach detects a new, so far unknown vulnerability, called Spectre-STC, indicating that also single-threaded processors can be vulnerable to contention-based Spectre attacks.

### A Data-Driven CHC Solver

* <img src="image/pdf_24px.png">[Paper](https://www.cs.purdue.edu/homes/suresh/papers/pldi18.pdf)

**Abstract:** We present a data-driven technique to solve Constrained Horn Clauses (CHCs) that encode verification conditions of programs containing unconstrained loops and recursions. Our CHC solver neither constrains the search space from which a predicate’s components are inferred (e.g., by con- straining the number of variables or the values of coefficients used to specify an invariant), nor fixes the shape of the pred- icate itself (e.g., by bounding the number and kind of logi- cal connectives). Instead, our approach is based on a novel machine learning-inspired tool chain that synthesizes CHC solutions in terms of arbitrary Boolean combinations of unre- stricted atomic predicates. A CEGAR-based verification loop inside the solver progressively samples representative posi- tive and negative data from recursive CHCs, which is fed to the machine learning tool chain. Our solver is implemented as an LLVM pass in the SeaHorn verification framework and has been used to successfully verify a large number of non- trivial and challenging C programs from the literature and well-known benchmark suites (e.g., SV-COMP).

### Heuristic Model Checking using a Monte-Carlo Tree Search Algorithm

* <img src="image/pdf_24px.png">[Paper](https://dl.acm.org/doi/pdf/10.1145/2739480.2754767)

**Abstract:** Monte-Carlo Tree Search algorithms have proven extremely effective at playing games that were once thought to be difficult for AI techniques owing to the very large number of possible game states. The key feature of these algorithms is that rather than exhaustively searching game states, the al- gorithm navigates the tree using information returned from a relatively small number of random game simulations. A practical limitation of software model checking is the very large number of states that a model can take. Motivated by an analogy between exploring game states and check- ing model states, we propose that Monte-Carlo Tree Search algorithms might also be applied in this domain to efficiently navigate the model state space with the objective of finding counterexamples which correspond to potential software faults. We describe such an approach based on Nested Monte-Carlo Search—a tree search algorithm ap- plicable to single player games—and compare its efficiency to traditional heuristic search algorithms when using Java PathFinder to locate deadlocks in 12 Java programs.

### MachSMT: A Machine Learning-based Algorithm Selector for SMT Solvers

* <img src="image/pdf_24px.png">[Paper](https://uwspace.uwaterloo.ca/bitstream/handle/10012/15755/machsmt_final.pdf?sequence=6&isAllowed=y)

**Abstract:** In this paper, we present MachSMT, an algorithm selection tool for state-of-the-art Satisfiability Modulo Theories (SMT) solvers. MachSMT supports the entirety of the logics within the SMT-LIB ini- tiative. MachSMT uses machine learning to learn empirical hardness models (a mapping from SMT-LIB instances to solvers) for state-of-the- art SMT solvers to compute a ranking of which solver is most likely to solve a particular instance the fastest. We analyzed the performance of MachSMT on 102 logics/tracks of SMT-COMP 2019 and observe that it improves on competition winners in 49 logics (with up to 240% in perfor- mance for certain logics). MachSMT is clearly not a replacement for any particular SMT solver, but rather a tool that enables users to leverage the collective strength of the diverse set of algorithms implemented as part of these sophisticated solvers. Our MachSMT artifact is available at https://github.com/j29scott/MachSMT.

### AVR: Abstractly Verifying Reachability

* <img src="image/pdf_24px.png">[Paper](https://aman-goel.github.io/publications/goel2020avr_submission_version.pdf)

**Abstract:** We present AVR, a push-button model checker for verifying state transition systems directly at the source-code level. AVR uses infor- mation embedded in the word-level syntax of the design representation to automatically perform scalable model checking by combining a novel syntax-guided abstraction-refinement technique with a word-level imple- mentation of the IC3 algorithm. AVR provides independently-verifiable certificates that offer provable assurance and are easy to relate to the word-level system. Moreover, proof certificates can be further used in innovative ways to extract key design information and are useful in a growing number of applications.

### SAT Solving with GPU Accelerated Inprocessing

* <img src="image/pdf_24px.png">[Paper](https://gears.win.tue.nl/papers/parafrost_gpu.pdf)

**Abstract:** Since2013,theleadingSATsolversintheSATcompetitionallusein- processing, which unlike preprocessing, interleaves search with simplifications. However, applying inprocessing frequently can still be a bottle neck, i.e., for hard or large formulas. In this work, we introduce the first attempt to parallelize in- processing on GPU architectures. As memory is a scarce resource in GPUs, we present new space-efficient data structures and devise a data-parallel garbage col- lector. It runs in parallel on the GPU to reduce memory consumption and im- proves memory access locality. Our new parallel variable elimination algorithm is twice as fast as previous work. In experiments our new solver PARAFROST solves many benchmarks faster on the GPU than its sequential counterparts.

### CheckMate: Automated Synthesis of Hardware Exploits and Security Litmus Tests

* <img src="image/pdf_24px.png">[Paper](https://www-cs.stanford.edu/~trippel/pubs/ctrippel_MICRO51.pdf)

**Abstract:** Recent research has uncovered a broad class of se- curity vulnerabilities in which confidential data is leaked through programmer-observable microarchitectural state. In this paper, we present CheckMate, a rigorous approach and automated tool for determining if a microarchitecture is susceptible to specified classes of security exploits, and for synthesizing proof-of-concept exploit code when it is. Our approach adopts “microarchitec- turally happens-before” (μhb) graphs which prior work designed to capture the subtle orderings and interleavings of hardware execution events when programs run on a microarchitecture. CheckMate extends μhb graphs to facilitate modeling of security exploit scenarios and hardware execution patterns indicative of classes of exploits. Furthermore, it leverages relational model finding techniques to enable automated exploit program synthesis from microarchitecture and exploit pattern specifications. As a case study, we use CheckMate to evaluate the suscepti- bility of a speculative out-of-order processor to FLUSH+RELOAD cache side-channel attacks. The automatically synthesized results are programs representative of Meltdown and Spectre attacks. We then evaluate the same processor on its susceptibility to a dif- ferent timing side-channel attack: PRIME+PROBE. Here, *Check- Mate synthesized new exploits* that are similar to Meltdown and Spectre in that they leverage speculative execution, but unique in that they exploit distinct microarchitectural behaviors— speculative cache line invalidations rather than speculative cache pollution—to form a side-channel. Most importantly, our results validate the CheckMate approach to formal hardware security verification and the ability of the CheckMate tool to detect real- world vulnerabilities.

## Appendix

The full name of selected conference and jornals: 

**Conference**

1. **FMCAD** (Formal Methods in Computer-Aided Design)
   1. Accepted Papers
      1. [2021 Accepted Papers](https://fmcad.org/FMCAD21/accepted/)
      2. [2020 Accepted Papers](https://fmcad.forsyte.at/FMCAD20/accepted/)
   2. Submission Deadline
      1. 14th May (2021)
2. **VMCAI** (International Conference on Verification, Model Checking, and Abstract Interpretation)
   1. Accepted Papers
      1. [2021 Accepted Papers](https://popl21.sigplan.org/home/VMCAI-2021#event-overview)
      2. [2020 Accepted Papers](https://popl20.sigplan.org/home/VMCAI-2020#event-overview)
   2. Submission Deadline
      1. 2nd Sep (2021)
3. **CAV** (Computer Aided Verification)
   1. Accepted Papers
      1. [2021 Accepted Papers](http://i-cav.org/2021/accepted-papers/)
      2. [2020 Accepted Papers](http://i-cav.org/2020/accepted-papers/)
   2. Submission Deadline
      1. 28th Jan (2021)
4. **DAC** (Design Automation Conference)
   1. [1964-2021 Accepted Papers](https://dl.acm.org/conference/dac/proceedings)
   2. Submission Deadline
      1. 3rd Nov (2020)
5. **DATE** (Design, Automation & Test in Europe)
   1. [1998-2021 Accepted Papers](https://dl.acm.org/conference/date/proceedings)
   2. Past Best Papers
      1. [2021 Best Papers](https://past.date-conference.com/proceedings-archive/2021/html/bestpaper.html)
      2. [2020 Best Papers](https://past.date-conference.com/proceedings-archive/2020/html/bestpaper.html)
6. **ICCAD** (International Conference on Computer-Aided Design)
   1. [1992-2021 Accepted Papers](https://dl.acm.org/conference/iccad/proceedings)
7. **ASP-DAC** (Asia and South Pacific Design Automation Conference)
   1. [2022 Accepted Papers](https://aspdac2022.github.io/index.html)
8. **MICRO** (IEEE/ACM International Symposium on Microarchitecture)
   1. [Accepted Papers](https://dblp.org/db/conf/micro/index.html)
9. **TACAS** (International Conference on Tools and Algorithms for the Construction and Analysis of Systems) 
   1. [1995-2021 Accpeted papers](https://link.springer.com/conference/tacas) (*Note: TACAS has a couple of volumns, don't miss out*)
10. **ECAI** (European Conference on Artificial Intelligence)
    1. [2020 Accepted Papers](https://digital.ecai2020.eu/accepted-papers-main-conference/)
11. **PLDI** (ACM SIGPLAN Conference on Programming Language Design & Implementation)
    1. [2021 Accepted Papers](https://pldi21.sigplan.org/track/pldi-2021-papers#event-overview)
    2. [2020 Accepted Papers](https://pldi20.sigplan.org/track/pldi-2020-papers#event-overview)
12. **POPL** (ACM SIGPLAN-SIGACT Symposium on Principles of Programming Languages)
    1. [2021 Accepted Papers](https://popl21.sigplan.org/track/POPL-2021-research-papers#event-overview)
    2. [2020 Accepted Papers](https://popl20.sigplan.org/track/POPL-2020-research-papers#event-overview)
13. **ASPLOS** (International Conference on Architectural Support for Programming Languages and Operating Systems)
    1. [2021 Accepted Papers](https://asplos-conference.org/2021/index.html%3Fp=2181.html)
    2. [ACM database](https://dl.acm.org/conference/asplos)
14. **CCS** (ACM Conference on Computer and Communications Security)
    1. [2021 Accepted Papers](https://www.sigsac.org/ccs/CCS2021/accepted-papers.html)
    2. [2020 Accepted Papers](https://www.sigsac.org/ccs/CCS2020/accepted-papers.html)
15. **HVC** (Haifa Verification Conference)
    1. [2005-2017 Accepted Papers](https://link.springer.com/conference/hvc)
16. **NFM** (NASA Formal Methods Symposium)
    1. [2020 Accepted Papers](https://ti.arc.nasa.gov/events/nfm-2020/papers/)

**Jornal**

1. TODAES (ACM Transactions on Design Automation of Electronic Systems)
   1. [Archive (1990s to 2021)](https://dl.acm.org/loi/todaes/group/d2020.y2021)

