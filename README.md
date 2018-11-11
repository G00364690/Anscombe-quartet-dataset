# Anscombe Quartet Analysis
This assignment has been completed in accordance with the tasks set out in the coursework of the Fundamentals of Data Analysis module as part of the Higher Diploma in Data Analytics in Galway-Mayo Institute of Technology.

## Assignment completed by:
Declan Reidy - November 2018

## Instructions

In order to complete this assigment it was necessary to:
1. Download & install Anaconda
2. Download & install Console Emulator x64
3. Create directory and files such as this README, LICENSE and .gitignore using Linux commands
4. Launch a jupyter notebook from the command line and create Anscombe-quartet.ipynb
5. Download the Anscombe Quartet dataset and read the dataset into Anscombe-quartet.ipynb and perform analysis
6. Sync files on my local machine to repository on GitHub allow me to push/pull updates to the jupyter notebook over various commits


To review the analysis methods and conclusions from the assigment:
1. Simply launch the Jupyter Notebook entitled "Anscombe-Quartet.ipynb"
2. Review the full analysis in the Jupyter Notebook
3. Run individual elements of the python code by highlighting cells and using command SHIFT+ENTER
4. Consult the "Initial Research" section of this README file for information on my approach to this assignment
5. Consult the "Method" section of this README file for information on my approach to this assignment
6. Consult the "References & Research" section of this README file for finformation on my further reading in relation to this assigment

## Initial Research
From the lecture series and background material in the course throughout the opening 8 weeks it was clear that the assignment was likely to build on various aspects of the coursework introduced during the lecture series.

Much of our learning from the Win a car probability, the Lady tasting tea scenario, and Bayes theorem in relation to drug testing centred around the likelihood that our first instincts when it comes to thorough statistical analysis can be quite far from being accurate. In particular in the cases of the win a car probability - it's somewhat telling that most participants would elect to stay with their choice - and with Bayes theorem - where one would at first instinct rightly assume that a test with 99% accuracy would be robust - only to find out with further analysis that this is not true (at least under the test parameters we set for the simulation).

Initial research of the Anscombe Quartet points quickly to idea of a set of data designed to be a test case to highlight the perils of limiting analysis methods to purely numerical or statistical properties, rather than supplementing them with graphical analysis to contextualise the outcomes.

## Method
Given the initial research, it was clear our analysis method must comprise both the analysis of statistical properties as well as graphical analysis using plots.

The approach therefore became about determining statistical properties for the 4 datasets including:
1. Count
2. Mean
3. Standard Deviation
4. X and Y Correlation
5. Slope and Y-Intercept

But also about graphically representing the datasets individually to show that while the statistical properties of the datasets were almost indentical, there was significant influence on 3 the datasets from heavy outliers and as such the lesson - discussed more thoroughly in the analysis - is that because of outliers, analysis using statistical properties alone can lead you to overlooking the true pattern in data.

## References & Research
https://www.r-bloggers.com/using-and-abusing-data-visualization-anscombes-quartet-and-cheating-bonferroni/
Using and Abusing data visualisation
Identical statistical properties yet appear very different when graphed.
Mean, median, standard deviation, correlation coeff are all the same.
Linear regression tells a much different story IS THIS TRUE? - not sure
Lesson's - you can't use visualization to cheat on statistical significance

https://rstudio-pubs-static.s3.amazonaws.com/52381_36ec82827e4b476fb968d9143aec7c4f.html

Visualisation not as precise as statistics, but provides a unique view. Much easier to discover interesting structures than using numerical methods alone. Provides context necessary to make better choices and be more careful when fitting models. Anscombe is 4 datasets with identical statistical properties that are indeed very different.

1973, Francis J. Anscombe published a paper titled Graphs in Statistical Analysis. Using graphical methods was relatively new, but this approach still attracted a lot of skepticism. Anscombe's view was that textbooks of the era "indoctrinate" people with notions such as the idea that "numerical calculations are exact, but graphs are rough". The regression lines are the same, but influenced heavily by outliers.

http://complementarytraining.net/stats-playbook-what-is-anscombes-quartet-and-why-is-it-important/

It can be seen both graphically and from regression summary that each data set resulted in same statistical model.
Intercepts, coeficients and their p values are the same. SEE (standard error of the estimate, or SD of residuals), F-value and it’s p values are the same.

https://www.autodeskresearch.com/publications/samestats

The effectiveness of Anscombe's Quartet is not due to simply having four different datasets which generate the same statistical properties, it is that four clearly different and visually distinct datasets are producing the same statistical properties. In contrast the "Unstructured Quartet" shares the same statistical properties as Anscombe's Quartet, however without any obvious underlying structure to the individual datasets, this quartet is not nearly as effective at demonstrating the importance of visualizing your data

Not clear how Anscombe actually came up with it:
Best method applied since is to take an existing data set and modify it slightly to maintain the same statistical properties.
Method: choose a point at random and modify it and check the statistical properties haven't changed.

https://www.mathwarehouse.com/statistics/what-is-anscombes-quartet.php

Anscombe's quartet was introduced by Francis J. Anscombe in his paper titled: Graphs in Statistical Analysis published in 1973. The quartet is widely described across multiple sources as "four datasets that have nearly identical simple statistical properties, yet appear very different when graphed. Each dataset consists of eleven (x,y) points".

The statistical properties referenced are numerous and include: mean; median; standard deviation; correlation coefficients; linear regression lines and intercepts. Light research would indicate that in 1973, the use of graphical methods of analysis was still in its infancy relative to numerical methods of analysis and that there may have been scepticism about the concept of graphical analysis 

There appears to be some consensus that Ancombe's view of traditional text books and methods of analysis was that they gave rise to notions that numerical calculations were "exact", and graphs were "rough".

It is likely that Anscombe created the quartet to dispel long held theories that simple numerical statistical analyses could tell the whole story of a set of data, by showing how graphical analysis techniques could highlight the hidden influence of outliers in the statistical analysis of any dataset.

His motivation in creating 4 very different datasets with some carefully chosen heavy outliers to engineer or manipulate the uniformity of the more standard statistical analysis properties (mean; standard deviation and regression lines among others)becomes clearer with this logic.




