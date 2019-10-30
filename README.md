## Welcome to Homepage of Winglets

We present **Winglets** as a new technique to enhance the grouping perception in multiclass scatterplot. Winglets are designed as the two-sided strokes attached to the dots in scatterplot. With the **Gestalt Principle of Closure**, the global association of points can be mentally completed by those local strokes. 

Min Lu, Shuaiqi Wang, Joel Lanir, Noa Fish, Yue Yang and Cohen-Or Daniel and Hui Huang. IEEE Transactions on Visualization and Computer Graphics (Proceedings of InfoVis 2019).
<a href='https://deardeer.github.io/pub/InfoVis19_Winglet.pdf'> 
 <img src = 'https://raw.githubusercontent.com/deardeer/Winglets/gh-pages/images/pdf.jpeg' width='3.5%' height = '3.5%' style='margin-top:5px'></a>

Below we demonstrate the POWER of the closure effect indicated by winglets. 

<!-- To see the full paper, please access the link: [Winglets: Visualizing Association with Uncertainty in Multi-class Scatterplots](https://deardeer.github.io/pub/InfoVis19_Winglet.pdf) -->



### Winglets with Different Orientations

![Different Oriented Winglets](
https://raw.githubusercontent.com/deardeer/Winglets/gh-pages/images/diff_orient.png)

Here on the left, we see a scatterplot with four groups of color. 
For the right two figures, we take exactly the same points, but enhance them with differently oriented Winglets.
We get a totally different visual perception of the grouping, although it is colored with four different colors.
In the middle, we see two horizontal classes and two vertical classes in the right. 

This suggests the closure principle has a stronger perceptual affect than the similarity principle.


### Winglets in Colorless Scatterplot

![Single Colored Winglets](
https://raw.githubusercontent.com/deardeer/Winglets/gh-pages/images/single_color.png)

Here on the left, we show a single color scatterplot. It 's very hard to tell how many clusters there are. 
In the middle, we enhance it with winglets. Although they are overlapping and single color, we can still perceive that there are two clusters. And on the right, of course, the colors add a lot.

This is an extreme case, but it does show the power of winglet in cluster expression, even in colorless case.

### Enclosure v.s. Winglets

<!-- ![Enclosure and Winglets](
https://raw.githubusercontent.com/deardeer/Winglets/gh-pages/images/enclosure.png){width='90%' height='90%'} -->
<!-- <div align='center'> -->
<img src = 'https://raw.githubusercontent.com/deardeer/Winglets/gh-pages/images/enclosure.png' width='90%' height='90%'>
<!-- </div> -->

Enclosing points with a boundary is a ‘hard’ visually design to associate points as a group. Points in the overlap regions remain ambiguous, we cannot tell which cluster the point belongs to. 

With wings, the associating of groups are much softer. Even for dots in the overlapping region, with very short strokes, points can be easily associated with their cluster, and also in the way it reflects the uncertainty. 

### Acknowledgement   
We thank the reviewers for their valuable comments. This work is supported in parts by NSFC (61802265, 41671387, 61761146002, 61861130365), LHTD (20170003), Guangdong Provincial Natural Science Foundation (2018A030310426, 2015A030312015), and the National Engineering Laboratory for Big Data System Computing Technology.

### Bibtex  
```
@article{lu2019winglets,  
title = {Winglets: Visualizing Association with Uncertainty in Multi-class Scatterplots},  
author={Lu, Min and Wang, Shuaiqi and Lanir, Joel and Fish, Noa and Yue, Yang and Cohen-Or, Daniel and Huang, Hui},  
journal={IEEE transactions on visualization and computer graphics},  
pages = {1 - 1},   
year={2019}  
}
```

