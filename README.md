# RecipeAnalysis
A data science approach to analyzing recipe data

Data and much of inspiration credit to:

https://www.kaggle.com/veereshelango/curious-on-epicurious-recipes

Requirements

Python 2.7
anaconda for python 2.7

Setup word cloud:
git clone https://github.com/amueller/word_cloud/  
you will have to run the setup instructions found in the associated readme.md file
I had to run the setup from both anaconda prompt and my python 2.7

inside your conda environment, install the data science packages:
pandas
numpy
matplotlib
seaborn
* it is recommended to create a virtual environment, and install into that.  I can show you how.  

make a folder for the repository.  go to that folder, then:

git clone https://github.com/royjackson419/RecipeAnalysis

enter the RecipeAnalysis folder you just got

jupyter notebook

from jupyter, open Salt%20Analysis.ipynb
or
wordcloud.ipynb

You can now run either program, and see some sweet analysis of recipes!

To make edits:

git checkout -b Rahul's work

after you change code

git add *    
#causes github to see changes

git commit -m " a message about what you did"
#you typically do commits after completing some set of changes.   I commit 6x a day.  

git push
#pushes the changes to the repository

once you have changes to pass to message, go to github, choose your branch, select new pull request. 

I can show the rest once we make it that far



To update your code - say if I made changes you want

commit your changes

git pull
git merge master

your branch and master will now be in sync
