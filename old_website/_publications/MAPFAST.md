---
title: "MAPFAST: A Deep Algorithm Selector for Multi Agent Path Finding using Shortest Path Embeddings"
collection: publications
permalink: /publication/MAPFAST
excerpt: 
date: 2021-02-01
venue: 'AAMAS 2021'
paperurl: 'https://arxiv.org/abs/2102.12461'
citation: 'Ren, Jingyao, et al. "MAPFAST: A Deep Algorithm Selector for Multi Agent Path Finding using Shortest Path Embeddings." AAMAS 2021'
---
Solving the Multi-Agent Path Finding (MAPF) problem optimally is known to be NP-Hard for both make-span and total arrival time minimization. While many algorithms have been developed to solve MAPF problems, there is no dominating optimal MAPF algorithm that works well in all types of problems and no standard guidelines for when to use which algorithm. In this work, we develop the deep convolutional network MAPFAST (Multi-Agent Path Finding Algorithm SelecTor), which takes a MAPF problem instance and attempts to select the fastest algorithm to use from a portfolio of algorithms. We improve the performance of our model by including single-agent shortest paths in the instance embedding given to our model and by utilizing supplemental loss functions in addition to a classification loss. We evaluate our model on a large and diverse dataset of MAPF instances, showing that it outperforms all individual algorithms in its portfolio as well as the state-of-the-art optimal MAPF algorithm selector. We also provide an analysis of algorithm behavior in our dataset to gain a deeper understanding of optimal MAPF algorithms' strengths and weaknesses to help other researchers leverage different heuristics in algorithm designs. 
