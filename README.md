# Project 3: Movie Revenue Prediction

## Setup - git and pipenv

1.  Open an command prompt (Windows command line, terminal or Git Bash) and change to the directory you want the project to land in.  I think most of you have a folder called **bootcamp** in **desktop**.  So this will probably be **cd desktop** and then **cd bootcamp**.  

2.  After accepting the assignment, click on the **Clone or download** button and copy the link.  

3. At the command prompt, type in **git clone paste_the_link**

4. Change into the directory for the new project: **cd project_name**

5. Install the needed packages to set up the virtual environment: **pipenv install**

6. Run the virtual environment: **pipenv shell**

7. Launch Jupyter Lab:  **jupyter lab**

8. The command prompt will be tied up running the jupyter server.  Open a second command prompt so you can commit your changes using git. Again, navigate to the directory for your project.  

9. As you make progress, commit your changes along the way.  A rule of thumb for how often to commit is every 15 minutes or 15 lines of code.  Make your commit messages short and informative.  

* Tell what files have changed **git status**
* Add the files to be commited **git add filename**
* Commit the changes **git commit -m "commit message"**
* Push changes to github **git push**

## Project Description

In this dataset, you are provided with 7398 movies and a variety of metadata. Movies are labeled with id. Data points include cast, crew, plot keywords, budget, posters, release dates, languages, production companies, and countries.

You are predicting the worldwide revenue for 4398 movies in the test file.

Note - many movies are remade over the years, therefore it may seem like multiple instance of a movie may appear in the data, however they are different and should be considered separate movies. In addition, some movies may share a title, but be entirely unrelated.

E.g. The Karate Kid (id: 5266) was released in 1986, while a clearly (or maybe just subjectively) inferior remake (id: 1987) was released in 2010. Also, while the Frozen (id: 5295) released by Disney in 2013 may be the household name, don't forget about the less-popular Frozen (id: 139) released three years earlier about skiers who are stranded on a chairlift.

The project is to use the Decision Tree Regression and Random Forest techniques discussed in class to predict the revenue of the films.

The data is in the class Google drive "Deep Dive Data Science - Cohort 1/Data/box_off_train.csv".
