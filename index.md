## Welcome to Bojan Zunar's GitHub Pages

<p align = "justify">These pages show tasks completed throughout Coursera's <b><a href="https://www.coursera.org/specializations/jhu-data-science">Data Science</a></b> and 
<b><a href="https://www.coursera.org/specializations/genomic-data-science"> Genomic Data Science</a></b> Specializations.</p>

<p align = "justify"><a href="https://www.coursera.org/">Coursera</a> provides online courses from top universities and, to students that complete a course, offers a <a href="https://learner.coursera.help/hc/en-us/articles/208280196">Verified certificate</a>. Through ID verification, this document guarantees the identity of the person which completed the required assignments, thus ensuring academic integrity. Yet, while finishing the course highlights commitment, it does not illustrate what the students learned, i.e. what they can do.</p>

<p align = "justify">Most Coursera's courses include <a href="https://learner.coursera.help/hc/en-us/articles/208279946-See-feedback-and-grades-for-peer-reviewed-assignments">Peer Reviewed Assignments</a>, tasks which cannot be completed by merely "clicking-to-victory" and by answering interactive questions, but by implementing learned concepts to solve and document non-trivial problems reproducibly. This page lists few such reports to demonstrate the skills I acquired throughout the Specializations.</p>


## Courses:

- <b><a href="https://www.coursera.org/learn/bioconductor">Bioconductor for Genomic Data Science</a></b> [(certificate)](https://www.coursera.org/account/accomplishments/records/7XTSS4LNY5SJ)
  - <details>
     <summary style="color:#1e6bb8;">Assignment: <i>H3K4me3 vs. Transcription</i></summary>

    <small><p> </p><p align = "justify">The airway dataset contains more than 64k features. How many of these features overlaps with transcripts on the autosomes? A feature has to overlap the actual transcript, not the intron of a transcript.</p><p align = "justify">The expression measures of the airway dataset are the number of reads mapping to each feature. How many reads map to features which overlaps these transcripts?</p><p align = "justify">We should be able to very roughly divide these transcripts into expressed and non expressed transcript. Expressed transcripts should be marked by H3K4me3 at their promoter. What is the median number of counts per feature containing a H3K4me peak in their promoter? Compare this to the median number of counts for features without a H3K4me3 peak.</p></small>
    
    </details>
  - <details>
     <summary><a href="https://bzunar.github.io/bioconductor-assignment.html">Report</a></summary>
     
     <small><p> </p><p align = "center"><b><a href="https://bzunar.github.io/bioconductor-assignment.html">The R Markdown Report</a></b></p></small>
    
    </details>
<p> </p>

- <b><a href="https://www.coursera.org/learn/python-genomics">Python for Genomic Data Science</a></b> [(certificate)](https://www.coursera.org/account/accomplishments/records/ABLH3WHC64Y8)
  - <details>
     <summary style="color:#1e6bb8;">Assignment: <i>Finding ORFs and Repeats</i></summary>

    <small><p> </p><p align = "justify">Write a Python program that takes as input a file containing DNA sequences in multi-FASTA format, and computes the answers to the following questions.</p><p align = "justify">How many records are in the file? What are the lengths of the sequences in the file? What is the longest sequence and what is the shortest sequence? Is there more than one longest or shortest sequence? What are their identifiers?</p><p align = "justify">What is the length of the longest ORF in the file? What is the identifier of the sequence containing the longest ORF? For a given sequence identifier, what is the longest ORF contained in the sequence represented by that identifier? What is the starting position of the longest ORF in the sequence that contains it?</p><p align = "justify">Identify all repeats of length n in all sequences in the FASTA file. Determine how many times each repeat occurs in the file, and which is the most frequent repeat of a given length.</p></small>
    
    </details>
  - <details>
     <summary><a href="https://bzunar.github.io/python-assignment.html">Report</a></summary>
         
     <small><p> </p><p align = "center"><b><a href="https://bzunar.github.io/python-assignment.html">The R Markdown Report</a></b></p></small>
    
    </details>
<p> </p>

- <b><a href="https://www.coursera.org/learn/data-products">Developing Data Products</a></b> [(certificate)](https://www.coursera.org/account/accomplishments/records/98SLMCHQQUKQ)
  - <details>
     <summary style="color:#1e6bb8;">Assignment: <i>Shiny Nobel App</i></summary>

    <small><p> </p><p align = "justify">Create a Shiny app with supporting documentation. Think of documentation as whatever a user will need to start using your application. Deploy the application on RStudio's Shiny server. Share your server.R and ui.R code on GitHub.</p><p align = "justify">Then, use Slidify or RStudio Presenter to prepare a reproducible pitch about the application with an html5 slide deck. You get 5 slides (inclusive of the title slide) to pitch a your app. The presentation must contain some embedded R code that gets run when slidifying the document.</p></small>
    
    </details>
  - <details>
     <summary><a href="https://bzunar.github.io/shiny-presentation.html">The Pitch</a></summary>
              
     <small><p> </p><p align = "center"><b><a href="https://bzunar.github.io/shiny-presentation.html">The Pitch</a></b></p></small>
    
    </details>
  - <details>
     <summary><a href="https://bzunar.shinyapps.io/nobelbirthdeath/">Shiny App</a></summary>
              
     <small><p> </p><p align = "center"><b><a href="https://bzunar.shinyapps.io/nobelbirthdeath/">Shiny App</a></b></p></small>
    
    </details>
  - <details>
     <summary><a href="https://github.com/bzunar/DevelopingDataProducts/blob/master/server.R">server.R</a></summary>
              
     <small><p> </p><p align = "center"><b><a href="https://github.com/bzunar/DevelopingDataProducts/blob/master/server.R">server.R</a></b></p></small>
    
    </details>
  - <details>
     <summary><a href="https://github.com/bzunar/DevelopingDataProducts/blob/master/ui.R">ui.R</a></summary>
              
     <small><p> </p><p align = "center"><b><a href="https://github.com/bzunar/DevelopingDataProducts/blob/master/ui.R">ui.R</a></b></p></small>
    
    </details>
<p> </p>

- <b><a href="https://www.coursera.org/learn/practical-machine-learning">Practical Machine Learning</a></b> [(certificate)](https://www.coursera.org/account/accomplishments/records/CNJYP57WSYDJ)
  - <details>
     <summary style="color:#1e6bb8;">Assignment: <i>Weight Lifting</i></summary>

    <small><p> </p><p align = "justify">Devices like Jawbone Up, Nike FuelBand, and Fitbit collect a large amount of data about personal activity. They are a part of the quantified self movement – a group of enthusiasts who take measurements to improve their health, to find patterns in their behavior, or because they are tech geeks. People regularly quantify how much of a particular activity they do, but rarely how well they do it. In this project, you use data from accelerometers on the belt, forearm, arm, and dumbell of 6 participants <a href="http://web.archive.org/web/20161224072740/http:/groupware.les.inf.puc-rio.br/har">(Weight Lifting Exercises Dataset)</a>. They were asked to perform barbell lifts correctly and incorrectly in 5 different ways.</p><p align = "justify">The goal is to predict the manner in which they did the exercise. This is the "classe" variable in the training set. You may predict with any of the other variables. Describe how you built your model, how you used cross validation, what you think the expected out of sample error is, and why you made the choices you did. Use your machine learning algorithm to predict 20 different test cases.</p></small>
    
    </details>
  - <details>
     <summary><a href="https://bzunar.github.io/weight-lifting.html">Report</a></summary>
              
     <small><p> </p><p align = "center"><b><a href="https://bzunar.github.io/weight-lifting.html">The R Markdown Report</a></b></p></small>
    
    </details>
<p> </p>

- <b><a href="https://www.coursera.org/learn/regression-models">Regression Models</a></b> [(certificate)](https://www.coursera.org/account/accomplishments/records/XHXEYB7VEV63)
  - <details>
     <summary style="color:#1e6bb8;">Assignment: <i>'Motor Trend' Cars</i></summary>

    <small><p> </p><p align = "justify">'Motor Trend' is a magazine about the automobile industry. Looking at a <a href="https://stat.ethz.ch/R-manual/R-devel/library/datasets/html/mtcars.html">a collection of cars</a>, they wish to explore the relationship between a set of variables and fuel consumption (miles per gallon, MPG) (outcome). They are particularly interested in question:</p><p align = "center">Is an automatic or manual transmission better for MPG?<br>Quantify the MPG difference between automatic and manual transmissions.</p><p align = "justify">Perform exploratory analysis, detail strategy for model selection, interpret the coefficients, plot residuals, answer the questions of interest, and quantify the uncertainty in your conclusions.</p></small>

    </details>
  - <details>
     <summary><a href="https://bzunar.github.io/motor-trend.html">Report</a></summary>
    </details>
<p> </p>

- <b><a href="https://www.coursera.org/learn/statistical-inference">Statistical Inference</a></b> [(certificate)](https://www.coursera.org/account/accomplishments/records/CG6N5R7VWM6Z)
  - <details>
     <summary style="color:#1e6bb8;">Assignment: <i>Exponential Distribution</i></summary>

    <small><p> </p><p align = "justify">Investigate the exponential distribution in R and compare it with the Central Limit Theorem. The mean of exponential distribution is 1/lambda and the standard deviation is also 1/lambda, where lambda is the rate parameter. Set lambda = 0.2 for all of the simulations. Illustrate via simulation and associated explanatory text properties of the distribution of averages of 40 exponentials by doing a thousand simulations. Show the sample mean and compare it to the theoretical mean of the distribution. Show how variable the sample is (via variance) and compare it to the theoretical variance of the distribution. Show that the distribution is approximately normal.</p></small>
    
    </details>
  - <details>
     <summary><a href="https://bzunar.github.io/random-exponentials.html">Report</a></summary>
    </details>

  - <details>
     <summary style="color:#1e6bb8;">Assignment: <i>Teeth Growth</i></summary>
<p> </p>

    <small><p> </p><p align = "justify">Analyze the ToothGrowth data from the R datasets package. Perform exploratory data analyses and provide a basic summary of the data. Use confidence intervals and/or hypothesis tests to compare tooth growth by supplement and dose. State your conclusions and needed assumptions.</p><p align = "right"></p></small>
    
    </details>
  - <details>
     <summary><a href="https://bzunar.github.io/teeth-growth.html">Report</a></summary>
    </details>
<p> </p>

- <b><a href="https://www.coursera.org/learn/reproducible-research">Reproducible Research</a></b> [(certificate)](https://www.coursera.org/account/accomplishments/records/7XZKEGNBBNVB)
  - <details>
     <summary style="color:#1e6bb8;">Assignment: <i>Storm Database</i></summary>

    <small><p> </p><p align = "justify">Storms and other severe weather events cause both public health and economic problems. Many severe events result in fatalities, injuries, and property damage, and preventing such outcomes is a key concern. The basic goal of this assignment is to explore the U.S. National Oceanic and Atmospheric Administration's (NOAA) storm database which tracks characteristics of major storms and weather events in the United States. It details when and where they occur and estimates fatalities, injuries, and property damage. Use the database to address the following questions:</p><p align = "center">Across the United States, which types of events (as indicated in the EVTYPE variable) are most harmful with respect to population health?<br>Across the United States, which types of events have the greatest economic consequences?</p><p align = "justify">Show the code for your entire analysis. Write your report as if it were to be read by a government or municipal manager who might be responsible for preparing for severe weather events and will need to prioritize resources for different types of events. However, there is no need to make any specific recommendations in your report.</p></small>
    
    </details>
  - <details>
     <summary><a href="https://bzunar.github.io/storm-dataset.html">Report</a></summary>
    </details>
<p> </p>

- <b><a href="https://www.coursera.org/learn/exploratory-data-analysis">Exploratory Data Analysis</a></b> [(certificate)](https://www.coursera.org/account/accomplishments/records/PSH3J3SQDZHK)
<p> </p>

- <b><a href="https://www.coursera.org/learn/data-cleaning">Getting and Cleaning Data</a></b> [(certificate)](https://www.coursera.org/account/accomplishments/records/ZNT6SHP49FD9)
<p> </p>

- <b><a href="https://www.coursera.org/learn/r-programming</a></b> [(certificate)](https://www.coursera.org/account/accomplishments/records/BE8J2TGHS7W9)
<p> </p>


<br>
<large><p align = "center"><b>Thank you for visiting! :)</b></p></large>