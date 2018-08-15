Readme

This program is designed to take a the set of documents stored in data/all-the-news and run NMF on all outlets except for one, then train a random forest to predict political leanings using document tagged by outlet. I determined how to classify different outlets as leaning left or right based on this analysis: http://www.allgeneralizationsarefalse.com/. Part of the difficulty with applying that to this project was that the data is very noisy. Outlets run articles that aren't about politics, and most outlets will try their best to be unbiased in their coverage and would, ideally, be largely indistinguishable from each other.  

 To run the code, you must have Jupyter lab installed. Then run: 'jupyter lab Final_Code.ipynb'. When the notebook pops up, click on the top window and click 'Shift-Enter' to import necessary libraries and define all functions used. When the window moves to the next block, press 'Shift-Enter' again to run kfolds validation on the dataset, where all articles from one outlet are left out, and then tests the remaining outlet. 


