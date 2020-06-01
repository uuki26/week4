Problems I encoutered when doing Excel:

My sum result was different than the correct one which was 19530, and then I found out I supposed to selected ‘Ottawa-Gatineau (Ontario Part)’
rather than 'Ottawa-Gatineau'

Counting and Plotting in R

Frist I installed install.packages("RCurl") and library("RCurl").

Then, I do x <- getURL("https://raw.githubusercontent.com/shawngraham/exercise/gh-pages/CND.csv", .opts = list(ssl.verifypeer = FALSE))

I got variables in my global environment pane. 

To extract the data, I put documents <- read.csv(text = x, col.names=c("Article_ID", "Newspaper Title", "Newspaper City", "Newspaper Province", "Newspaper Country", "Year", "Month", "Day", "Article Type", "Text", "Keywords"), colClasses=rep("character", 3), sep=",", quote="")

After I followed every steps, I got my final chart.

Using Voyant tools

I think voyant is an amazing tool for people to organize and statistic data and words. And it is easy to use as well.

My snippet from voyant:
<iframe style='width: 385px; height: 317px;' src='https://voyant-tools.org/tool/Cirrus/?corpus=7b82209560f281a106d0f2623a0f1a38'></iframe>



 

