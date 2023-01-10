# Machine-learning-health-outcome-predictions
Using machine learning algorithms to test the viability of health outcome predictions, based on CPS survey data.

<p>This project was intended to test the viability of predicting health outcomes based on a variety of factors.  In a 2002 study, researcher's 
  tested the hypothesis that income was the single most important factor in determinding health outcomes.  Theis 2002 analysis was largely conducted with ordinary 
  least square regression techiniques.  In this project, I wanted to test the viability of their conclusions with a variety of machine learning techniques to see what factors (if any) were significant.</p>
  
<h4 align="left">Languages:</h4>
<p align="left">
  <a href="https://www.r-project.org/" target="_blank" rel="noreferrer"> <img src="https://www.r-project.org/logo/Rlogo.svg" alt="R" width="40" height="40"/> </a>
  
<h3>Naviation of Files</h3>
<p>There are quite a few files.  To view the final product: download the final_project.zip where you can view the paper and knitted(to pdf) RMD files.  
  When selecting the zip folder on the main repository page, select "view raw" to download the zipped file.</p>
  
<p>If you would like to view the code in R, open the RMD's in your IDE of choice (I use R studio).  There is no single RMD file due to 
  the time constraint of running many computationally intensive algorithms across a large data set.  The SVM alrogithms in particular may take several hours 
  to run.  When you see the warnings during SVM analysis, do not stop your IDE. </p>
  
<h4>Intitial Set Up</h4>
<p>First set up your working directory so that when the data sets are called, your working directory is able to pull from the folder in which they 
  are. If you are new to this, it may be easier to put every file in the same folder so that you have no need to change directories.</p>

<h4>Dependencies</h4>
<p>Many packages are required in R to run this code.  There is a series of library() statements at the beginning.  If you are downloading R for the first time
  or are a new user: you will see an error when you run the chunk of code with the library() statements: indicating a missing package.  run the commands 
  "install.packages(“_______”)" individually for whatever packages are missing to download them.  Library() only calls them to allow them for immediate use (again) after they have been installed.
</p>
  
