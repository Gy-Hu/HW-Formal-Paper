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
  - A survey of side-channel attacks on caches and countermeasures, 2018
  - A Survey on the Application of Machine Learning to Formal Verification, 2018
- **FMCAD**
  - IC3 with Internal Signals, 2021
  - End-to-End Formal Verification of a RISC-V Processor Extended with Capability Pointers, 2021
  - Robustness between Weak Memory Models, 2021
  - A Multithreaded Vampire with Shared Persistent Grounding, 2021
  - Data-driven Optimization of Inductive Generalization, 2021
  - Distributed Bounded Model Checking, 2020
  - [Efficient implementation of property directed reachability, 2011](#efficient-implementation-of-property-directed-reachability)
- **VMCAI**
  - Synthesizing Environment Invariants for Modular Hardware Verification, 2020
  - A Cooperative Parallelization Approach for Property-Directed k-Induction, 2020
  - [SAT-Based Model Checking without Unrolling, 2011](#sat-based-model-checking-without-unrolling)
- **CAV**
  - Pono: A Flexible and Extensible SMT-Based Model Checker, 2021
  - Code2Inv: A Deep Learning Framework for Program Verification, 2020
  - StringFuzz: A fuzzer for string solvers, 2018
  - [End-to-End Verification of ARM Processors with ISA-Formal, 2016](#end-to-end-verification-of-arm-processors-with-isa-formal)
  - ICE: A Robust Framework for Learning Invariants, 2014
- **DAC**
  - A Formal Approach for Detecting Vulnerabilities to Transient Execution Attacks in Out-of-Order Processors, 2020
- **DATE**
  - When Capacitors Attack: Formal Method Driven Design and Detection of Charge-Domain Trojans, 2019 (best paper)
- **ICCAD**
  - DATC RDF-2019: Towards a Complete Academic Reference Design Flow, 2019
- **MICRO**
  - Checkmate: Automated synthesis of hardware exploits and security litmus tests, 2018
- **TACAS**
  - SAT Solving with GPU Accelerated Inprocessing, 2021
  - MachSMT: A Machine Learning-based Algorithm Selector for SMT Solvers, 2021
  - AVR: Abstractly Verifying Reachability, 2020
  - Software Verification with PDR: An Implementation of the State of the Art, 2020
  - Multi-agent Safety Verification Using Symmetry Transformations, 2020
- **TODAES**
  - Instruction-Level Abstraction (ILA): A Uniform Specification for System-on-Chip (SoC) Verification, 2020 (best paper)
- **ECAI**
  - Verification of Recurrent Neural Networks for Cognitive Tasks via Reachability Analysis, 2020
- **PLDI**
  - Abstract Interpretation under Speculative Execution, 2019
  - A Data-Driven CHC Solver, 2018
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
  - Heuristic Model Checking using a Monte-Carlo Tree Search Algorithm, GECCO 2015

## Papers Classified by Subject

- **Survey/Review**
  - A Survey on the Application of Machine Learning to Formal Verification, arxiv 2018
- **Model Checking**
  - SAT-Based Model Checking without Unrolling, VMCAI 2011
  - Efficient implementation of property directed reachability, FMCAD 2011
- **Formal Verification Acceleration**
  - SAT Solving with GPU Accelerated Inprocessing, TACAS 2021
  - Distributed Bounded Model Checking, FMCAD 2020
  - A Cooperative Parallelization Approach for Property-Directed k-Induction, VMCAI 2020
- **Neural Network Verification**
  - Verification of Recurrent Neural Networks for Cognitive Tasks via Reachability Analysis, ECAI 2020
- **Side-Channel Attack**
  - A Formal Approach for Detecting Vulnerabilities to Transient Execution Attacks in Out-of-Order Processors, 2020
  - Abstract Interpretation under Speculative Execution, PLDI 2019
  - When Capacitors Attack: Formal Method Driven Design and Detection of Charge-Domain Trojans, DATE 2019
  - Checkmate: Automated synthesis of hardware exploits and security litmus tests, MICRO 2018
- **Weak Memory Model**
  - Robustness between Weak Memory Models, FMCAD 2021
- **AI+Formal**
  - MachSMT: A Machine Learning-based Algorithm Selector for SMT Solvers, 2021
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

**Summary:** Currenrly most broadly applicable formal verification technique for verifying processor pipeline control.

###  SAT-Based Model Checking without Unrolling

* <img src="image/pdf_24px.png">[Paper](http://alcom.ee.ntu.edu.tw/system/privatezone/meetingfile/201010222258251.pdf)

**Summary:** This paper introduce IC3 algorithm. 

### Efficient implementation of property directed reachability

* <img src="image/pdf_24px.png">[Paper](https://www.cs.utexas.edu/~ragerdl/fmcad11/papers/7.pdf)

**Summary:** Easier version to understand IC3/PDR.


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
6. **ICCAD** (International Conference on Computer-Aided Design)
   1. [1992-2021 Accepted Papers](https://dl.acm.org/conference/iccad/proceedings)
7. **ASP-DAC** (Asia and South Pacific Design Automation Conference)
   1. [2022 Accepted Papers](https://aspdac2022.github.io/index.html)
8. **MICRO** (IEEE/ACM International Symposium on Microarchitecture)
   1. [Accepted Papers](https://dblp.org/db/conf/micro/index.html)
9. **TACAS** (International Conference on Tools and Algorithms for the Construction and Analysis of Systems)
   1. [1995-2021 Accpeted papers](https://link.springer.com/conference/tacas)
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

