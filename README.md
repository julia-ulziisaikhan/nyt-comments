# nyt-comments

Welcome to Julia Ulziisaikhan's and Edgardo Zelaya's GitHub repository for our New York Times comment text data mining project. This was a final project completed for Professor Wayne Lee's Data Mining class.

![image](https://static01.nyt.com/images/2017/10/27/reader-center/27comment-readers-13/27comment-readers-13-articleLarge.png?quality=75&auto=webp&disable=upscale)

## Project summary

We are interested in: (a) the text mining insights that can be gained from a NYT article's comments, and (b) from a political science standpoint, quantifying and analyzing _polarization_, AKA divisiveness in opinion, in a given comment section. To do this we engineered a polarization metric, and calculated the proportions of comments with negative, positive, and neutral sentiment per article. We found that political articles (compared to non-political articles) and Op-Eds (compared to non-Op-Eds) tended to be both **more polarized** and have **higher negative sentiment** comments and have **lower positive sentiment** comments (all at the 0.001 significance level). With the predictors of sentiment, polarization, and article word count,  our best binary classification model was able to predict whether an article was political or not with 20% classification error, 81% precision, and 86% recall. 

## This repository includes...

* `final_report.pdf` our written final report
* `final_code.Rmd` the code
* `processed_data.csv` the data, processed from @AashitaK 's NYT comments and article data https://www.kaggle.com/datasets/aashita/nyt-comments
* `political_lexicon.csv` the political content lexicon, used to categorize a given article into political or non-political content
* `project_requirements.pdf` our Professor's requirements/prompts for the assignment

Thank you,

-Julia and Edgardo
