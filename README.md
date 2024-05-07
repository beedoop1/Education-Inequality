# Education-Inequality

## Title: Project 2 (Inequality in Education Comparison)

### Description:
The purpose of this project is to determine whether school performance can be predicted by socioeconomic factors in the U.S. We will be taking a look at the average performance of a student on the ACT or SAT. The methods used were to create many graphs from both sides of a socioeconomic factor, and compare how the average ACT scores fair against each other. We can't predict the exact ACT score a student would get however, it can be assumed that students coming from a more fortunate background are more likely to do better on the ACT than students coming from a less fortunate background. So many factors are at play that can increase a student's chances of doing good and bad some out of their control. In conclusion, we can predict how a student might do based on their background, but there is also no way for certain we can tell what a student would score as that differs from person to person because two students with the same background could produce two entirely different results. One might perform well and the other might perform badly. This could be due to how hard one of their studies is compared to the other, so we can predict how someone could do based on their background or we can be entirely off. However, if we would have to assume based on a large set of students and how they would do, I believe we can predict the average ACT score on how they will do.

### Requirements: 
The software used for this project were Colab, Github, and Google Slides.

### Data:
Two data sets are being used. The primary data set is the Edgap data set from 2016 which includes about average ACT or SAT scores for schools and several socioeconomic characteristics (household income, unemployment, adult educational attainment, and family structure) of the school district.
Our second data set includes basic information about each school from the National Center for Education Statistics. 
https://drive.google.com/file/d/1HvW2w-o2XZzCm4KTvnb1Bb3BvoAa14BP/view?usp=sharing

Link to EdGap: https://www.edgap.org/#6/37.886/-96.868

Link to the National Center for Education Statistics: https://nces.ed.gov/ccd/pubschuniv.asp

### Steps Taken to Prepare Data:
The steps taken to alter the data were that I first changed the data type for one of the variables, selected columns that were needed to create graphs and also renamed the columns. After that, I merged the two data sets together. Then I dropped the negative percentages for the percent_lunch column and also dropped all the non-quantitative values from the data sets that we could impute. Then I created a train test split.

### File that performs data preparation: 
https://colab.research.google.com/drive/1grNK5zICWjSvZChM2dfAAL4MUofwMz1K

### Analyzing the Data:
Many graphs were created so we can directly compare two sides of the socioeconomic factor together. An example being how median income affects the average ACT scores and then having one graph with the average income being greater than $50000 and the other being less than or equal to $50000. Also performed linear regression on train/test split to determine how big the error was to get the ACT score.

### File with the analysis:
https://colab.research.google.com/github/beedoop1/Education-Inequality/blob/main/Jason_Rong_DATA_3320_Education_Analysis.ipynb#scrollTo=tw1XXDkUtsoD

### Authors:
Jia Jie Rong (Jason) LinkedIn: www.linkedin.com/in/jia-rong-468b2b26a

### License:
Anyone can use this information.
