
Motion_analysis_KR README

Hello! Welcome to my R analysis code. Here are some few tips. \
\
Put all your data in the data/data_for_analysis folder. This subfolder is designed to just dump all your .csv files in but allow you to archive and store data in the main 'data' folder and the code will not see it an get confused 
\
First, ensure you have Outline enabled at the top right of the source panel in R studio, this way you can see the chunk labels and can jump around sections of the code. \
\
Second, ensure you load all the packages at the start (there are more to come later in each chunk, but be sure these base ones are right. \
\
Third, when it comes to load your data, ensure you change the file paths. \
\
Fourth, there are a number of hard-coded elements in the first few chunks that you will have to address. Please read through the code and comments carefully. Pay attention to how I divided up my data, because I used a double-pass where the same stimulus conditions were repeated twice to check for correlation. This consisted of two blocks of 150 trials, so my data files were each 300 rows long, yours may be different. \
\
Fifth, ensure you finish these first 5 steps in the early chunks because they set up the data frames and some functions that are used later, if you don\'92t want to or dont need to perform a double pass correlation test, you will have to find out a way to ensure the hierarchy/structure of the environment is kept the same. \
\
Good luck! \
\
Kallum :)) 