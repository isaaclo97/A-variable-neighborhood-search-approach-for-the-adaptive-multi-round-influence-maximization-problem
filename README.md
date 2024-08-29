![Manintained](https://img.shields.io/badge/Maintained%3F-yes-green.svg)
![GitHub last commit (master)](https://img.shields.io/github/last-commit/isaaclo97/A-variable-neighborhood-search-approach-for-the-adaptive-multi-round-influence-maximization-problem)
![Starts](https://img.shields.io/github/stars/isaaclo97/A-variable-neighborhood-search-approach-for-the-adaptive-multi-round-influence-maximization-problem.svg)

# A variable neighborhood search approach for the adaptive multi round influence maximization problem

Social Networks have been in continuous growing during the last decades. The huge amount of information and applications has led to an increase in the interest of scientists and practitioners in the study of problems related to the influence in Social Networks. Some of the wide variety of real-world applications in this area are viral marketing, disease analysis, rumor detection, public opinion, among others. In this paper, the Adaptive Multi Round Influence Maximization problem is studied, in which the influence of a set of selected users (seed set) is propagated in multiple rounds independently, with the possibility of selecting different seed sets in each round. Therefore, seed sets can be adaptively selected based on the propagation results in the previous rounds. Since each node is activated with a certain probability, the total number of activated nodes must be calculated through an Influence Diffusion Model (IDM), which results in a rather computationally demanding method. In this research, the Independent Cascade Model is considered, which is one of the most extended IDMs, and also the one used in the best previous method. Practitioners highlight the relevance of designing an algorithm capable of efficiently solving the problem. In this research, the problem is addressed by considering the Variable Neighborhood Search methodology, proposing a novel constructive method that relies on independent probability based on events, and an intelligent local search method. Our best algorithm is compared with the state-of-the-art method, named AdaIMM, to analyze the performance of the proposal. The obtained results show the superiority of the proposal in both quality (influence spread) and computing time, obtaining the best solution in all the 40 instances considered requiring half of the computing time than the best previous approach (28 s vs. 53 s). Additionally, the best previous method presents an average deviation of 24.23%. These results are further confirmed by conducting non-parametric statistic tests.

- Journal: Social Network Analysis and Mining
- Impact Factor: 2.3 
- Paper link: https://doi.org/10.1007/s13278-024-01336-4
- Area: Computer Science - information systems
- Quartil: Q3 - 129/251

## Datasets

* [WikiVote](./instances/Wiki-Vote.txt)
* [NetHEPT](./instances/NetHEPT.txt)
* [ca-AstroPh](./instances/CA-AstroPh.txt)
* [ca-CondMat](./instances/CA-CondMat.txt)
* [cit-HepPh](./instances/Cit-HepPh.txt)
* [email-Enron](./instances/Email-Enron.txt)
* [p2p-Gnutella31](./instances/p2p-Gnutella31.txt)
* [Flixster](./instances/Flixster.txt)


All txt format instances can be found in instances folder.

## Repository folders

- code: source code of the proposal.
- instances: All the instances used in the research.
- communities: The communities obtained by the louvain algorithm used in the local search.
- results.xlsx: Table with instances with: objective value, computational time, and comparison with the previous algorithm showing the deviation and number of best solutions. There is also the latex code of the manuscript for the table.
- selected.xlsx: Shows the nodes chosen by our proposal per round and per instance.
- AMRIM.jar: It is the final executable of the application.

## Executable

You can just run the AMRIM.jar as follows.

```
java -jar AMRIM.jar
```

If you want new instances just replace folder instances.
Solution folder contains an excel with the results.

## Cite

Please cite our paper if you use it in your own work:

Bibtext
```
﻿@article{Lozano-Osorio2024,
author={Lozano-Osorio, Isaac and S{\'a}nchez-Oro, Jes{\'u}s and Duarte, Abraham},
title={A variable neighborhood search approach for the adaptive multi round influence maximization problem},
journal={Social Network Analysis and Mining},
year={2024},
month={Aug},
day={20},
volume={14},
number={1},
pages={165},
abstract={Social Networks have been in continuous growing during the last decades. The huge amount of information and applications has led to an increase in the interest of scientists and practitioners in the study of problems related to the influence in Social Networks. Some of the wide variety of real-world applications in this area are viral marketing, disease analysis, rumor detection, public opinion, among others. In this paper, the Adaptive Multi Round Influence Maximization problem is studied, in which the influence of a set of selected users (seed set) is propagated in multiple rounds independently, with the possibility of selecting different seed sets in each round. Therefore, seed sets can be adaptively selected based on the propagation results in the previous rounds. Since each node is activated with a certain probability, the total number of activated nodes must be calculated through an Influence Diffusion Model (IDM), which results in a rather computationally demanding method. In this research, the Independent Cascade Model is considered, which is one of the most extended IDMs, and also the one used in the best previous method. Practitioners highlight the relevance of designing an algorithm capable of efficiently solving the problem. In this research, the problem is addressed by considering the Variable Neighborhood Search methodology, proposing a novel constructive method that relies on independent probability based on events, and an intelligent local search method. Our best algorithm is compared with the state-of-the-art method, named AdaIMM, to analyze the performance of the proposal. The obtained results show the superiority of the proposal in both quality (influence spread) and computing time, obtaining the best solution in all the 40 instances considered requiring half of the computing time than the best previous approach (28 s vs. 53 s). Additionally, the best previous method presents an average deviation of 24.23{\%}. These results are further confirmed by conducting non-parametric statistic tests.},
issn={1869-5469},
doi={10.1007/s13278-024-01336-4}
}

```

MDPI and ACS Style
```
Lozano-Osorio, I.; Jesús Sánchez-Oro; Duarte, A. A Variable Neighborhood Search Approach for the Adaptive Multi Round Influence Maximization Problem. Social Network Analysis and Mining 2024, 14 (1). https://doi.org/10.1007/s13278-024-01336-4.
```

AMA Style
```
Lozano-Osorio I, Jesús Sánchez-Oro, Duarte A. A variable neighborhood search approach for the adaptive multi round influence maximization problem. Social Network Analysis and Mining. 2024;14(1). doi:https://doi.org/10.1007/s13278-024-01336-4.
```

Chicago/Turabian Style
```
Lozano-Osorio, Isaac, Jesús Sánchez-Oro, and Abraham Duarte. 2024. “A Variable Neighborhood Search Approach for the Adaptive Multi Round Influence Maximization Problem.” Social Network Analysis and Mining 14 (1). https://doi.org/10.1007/s13278-024-01336-4.
```