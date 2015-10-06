# JavaPDG
## Program Dependence Analysis for Java Programs.

Dependence analysis is a fundamental technique for program understanding and is widely used in software testing and debugging. However, there are a limited number of analysis tools available despite a wide range of research work in this field. In this work, we present JavaPDG, the first static analyzer for Java bytecode, which is capable of producing various graphical representations such as the system dependence graph, procedure dependence graph, control flow graph and call graph. As a program-dependence-graph based analyzer, JavaPDG performs both intra- and inter-procedural dependence analysis, and enables researchers to apply a wide range of program analysis techniques that rely on dependence analysis. JavaPDG provides a graphical viewer to browse and analyze the various graphs and a convenient JSON based serialization format.

* **[Researchers](#people)**
* **[The workflow of JavaPDG](#workflow)**
* **[An example of Java system dependence graph](#program-dependence)**
* **[Screen Shots of JavaPDG Generator & Viewer](#screenshots)**
* **[Quick Manual](#configuration-options)**
* **[Publication](#publication)**
* **[Applications of JavaPDG](#applications)**
* **[Sponsors](#sponsors)**
--- 
## Researchers
```
Dr. H. Andy Podgurski	andy [at] eecs [dot] case [dot] edu
Dr. Gang Shu	gang.shu [at] case [dot] edu
Dr. Boya Sun	boya.sun [at] case [dot] edu
Tim Henderson	timothy.henderson [at] case [dot] edu
Xianghao Chen	xianghao.chen [at] case [dot] edu
```
---
## The workflow of JavaPDG
![solarized symmetry](http://selserver.case.edu:8080/javapdg/pic/workflow_big.JPG)
---
