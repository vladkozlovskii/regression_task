# Regression task

I want to make regression model with pricing target where I'll use skills what i have at this moment (oct 2025)  
I think most direct and clear way for this task is using dataset about housing prices or car prices (previously I made some similar projects in learning tasks and few with housing prices in big cities)  
  
Here i dicided to use dataset from Tbilisi becasue:
- This city interesting for me and sometimes I visit it
- It is not so popular for this task in compare with some US, European or Russian cities
- It have some non-standard geographical characteristics  

May be a chose not best dataset for this task but my goal here is just present process of analysis and selection of best model using EDA, data preparation, working with geographical features, feature engineering, pipelines, hyperparams tuning etc.  
Unfortunately in this project there are luck of working with datetime, but I use it in another repositories.  
So project goal in this task - prediction of prices

Dataset taken from Kaggle:  

https://www.kaggle.com/datasets/tornikeonoprishvili/tbilisi-housing-challenge-2020

I also seen some pages with analysis of this data on Kaggle but I didn't read them for independent view of data

Here I made EDA, apply some geopandas and h3 instruments, make additional features and select optional number throw selectors.
Most procedures using with pipelines in the last two cells of the notebook examples of making all task in one cell.
Hyperparams tuning and model selection were performed to each model separately for more accurate control of the process.