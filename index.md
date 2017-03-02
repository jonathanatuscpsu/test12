# Stat 581
Keon Kim, Agnes Ge and Zhaohu(Jonathan) Fan  
February 16, 2017  




# Project 1
## Background

- Public schools, K-12, aggregated in terms of 500 districts and 27 counties in Pennsylvania, respectively. 
- Total revenue allocated to public school is fixed.
- Total enrollment is fixed.
- Only a fixed term, one year.

## Goals

- Max per-pupil revenue over two methods: districts-based method and counties-based method.
- Analysis: 1) Range method 2) Normalized Gini Index.


## Methodology

- Districts-based method 
    - Step 1  Total revenue, R, is divided by the total number of districts, D.
    
       \begin{equation}
         r_d=\frac{R}{D}
       \end{equation}
    - Step 2  Total revenue per district is divided by  total enrollment in each districts, E(i). 
    
      \begin{equation}
         r_d(i)=\frac{ r_d}{E(i)}, i=1,\cdots, 500.
       \end{equation}
- Counties-based method
    - Step 1 Total revenue, R, is divided by the total number of counties, C.
      \begin{equation}
         r_c=\frac{R}{C}
       \end{equation}
    - Step 2 Total revenue per county is divided by  total enrollment in each counties, E(j).
    
      \begin{equation}
         r_e(i)=\frac{ r_c}{ E^{\ast}(j)}, j=1,\cdots, 27.
       \end{equation}
- Cutoff 
         
      \begin{equation}
         Cutoff=\frac{R}{\sum_{i=1}^{500} E(i)}.
       \end{equation}

## Simulation
- Districts-based method 
![](index_files/figure-html/unnamed-chunk-1-1.png)<!-- -->
- Counties-based method
![](index_files/figure-html/unnamed-chunk-2-1.png)<!-- -->

## Analysis

 - Range method.
 - Normalized Gini Index.
 - Coefficient of Variation and McLoone Index. 
## Research questions

- Multiple years data sets available.


# Project 2

## Department: Graduate student from food science.

Background Information:
Our client, Molly, wants to learn of color-taste pairings. The pupose of her visit is to find a proper criteria for learning based on the probability of matching the stimuli to the correct color. To be more specific, she is interested in finding relationships between learning and gender, age, etc. and find ways to visually represent her data.

sucrose 

## Research Goals:

She has two major research questions:
### To find a criteria to distinguish  between learner and non-learner.
### To explore the relationships between learning and gender, age, etc.
### How does the probability of 'matching' change during the test. 

##  More Details:
1) Detailed about the experiments:
 1.1 In her first experiments, there were four compounds: 1) caffeine; 2) tetralone; 3) quinine 4) sucrose.
The first three compounds represent the tastes of bitter, and the last compound tastes as sweet. And each taste was assigned a unique color, such as red, blue,etc.

 1.2 With the similar setting for her second experiment, there were four compounds corresponding to the four different tastes: 1) bitter,2) sour, 3) sweet and 4) umami. Each compounds was assigned a unique color, respectively. In the first five days, subjects were given taste samples with certain color, and they learned which color matches with which taste. At the end of the experiment, subjects were randomly assigned sample tastes, and they would find the corresponding colors for those compounds based on their first five days' learning. 

# Project 3
