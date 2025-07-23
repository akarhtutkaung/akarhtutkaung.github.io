---
title: "Analysis of Cloth Simulation Using Sequential and Parallel Processing"
collection: publications
category: independent_research
permalink: /publication/Analysis_of_Cloth_Simulation_Using_Sequential_and_Parallel_Processing
excerpt: 'This independent research analyzes cloth simulation performance using sequential vs. parallel processing with row, column, and block decomposition methods.'
date: 2023-05-01
venue: 'Independent Research'
# slidesurl: 'http://academicpages.github.io/files/slides2.pdf'
paperurl: 'http://akarhtutkaung.github.io/files/2023_03_01_Analysis_of_Cloth_Simulation_Using_Sequential_and_Parallel_Processing'
citation: 'Kaung, Akar. (2023). <i>Analysis of Cloth Simulation Using Sequential and Parallel Processing</i>. Independent Research.'
---

## Abstract

This paper presents a study on the performance analysis of cloth simulation using parallel programming and different decomposition methods. The goal of the study is to identify the best approach to achieve optimal performance on three different sizes of clothes with varying qualities. Three types of clothes were used in the study, including a small cloth with a dimension of 100×100, a medium cloth with a dimension of 200×200, and a large cloth with a dimension of 300×300. The decomposition methods used in the study included row, column, and block decomposition. The performance of each method was evaluated using different numbers of threads.

The results of the study show that the row decomposition method consistently performs well across all three sizes of clothes, while the performance of the column and block decomposition methods varies depending on the size of the cloth and the number of threads used. Meanwhile, the normal sequential method produces the lowest performance among all four methods. The findings suggest that parallel programming with appropriate decomposition methods and thread configurations can greatly improve the performance of cloth simulation.