# Market Prediction Application (GitHub Repository)
This repository contains the initial setup and structure for a market prediction application, designed as a blueprint for a potential website. The project was created to practice and demonstrate Git commands, version control, and branching concepts. The files in this project serve as placeholders for what could be the frontend and backend structure of a market prediction website.

Description
The files included in this project are:

- index.html: A basic HTML structure representing the homepage of the market prediction website.
- main.py: A Python script intended to represent the backend logic (though no real market prediction functionality is implemented yet).
- styles.css: A CSS file for potential styling of the webpage (no styles have been applied yet).
- appinfo.txt: A text file that explains the application, what the project is for, and how it was structured.

Installation
To set up the project locally, follow these steps:
- Clone the repository: https://github.com/mariaianc/market-prediction
- Navigate to the project directory: cd market-prediction

Usage
This project structure is basic and designed for version control purposes. Here's an overview of the current structure:
- index.html: The main entry point of the website, which is empty for now.
- styles.css: The directory containing CSS styles for the site (currently not styled).
- appinfo.txt: A text file explaining the project's structure and purpose.
- main.py: The Python script that could contain the logic for market prediction (currently only contains placeholder code).

Contributing
Branches
- main: The primary branch containing the stable version of the website, with basic HTML, CSS, and Python files set up for the project.
- feature/add-about-project: Branch created for adding the "About the Application" section in a text file (appinfo.txt).
  
How to Contribute
- Fork the repository.
- Create a new branch from main for your feature or bug fix: git checkout -b feature/your-feature-name
- Make changes and commit them with descriptive messages: git add .        git commit -m "Your commit message"
- Push your branch to your forked repository: git push origin feature/your-feature-name
- Create a pull request explaining your changes and their purpose.


--------------------------------------------WHAT I DID FOR THE ASSIGNMENT------------------------------------------------------

1. GitHub Account Creation
Created a GitHub account by signing up on GitHub.


2. Local Git Repository Setup
Created a new project in PyCharm:

Open PyCharm, created a new project called market-prediction.
Initialized a local Git repository:

Inside PyCharm, opened the Terminal and ran:
git init


3. Added Files to the Project and Committed
Created project files:

Created index.html, main.py, and styles.css files inside the project.
Staged the files for commit:

Used the command to add all files to the staging area:
git add .
git commit -m "Initial commit: added index.html, main.py, and styles.css"


4. Created a Remote Repository on GitHub
Created a remote repository:
On GitHub, created a new repository named market-prediction (with the default settings).
URL: https://github.com/mariaianc/market-prediction


5. Connected Local and Remote Repositories
Linked the local repository to GitHub:
Connected the local Git repository to the remote GitHub repository using:
git remote add origin https://github.com/mariaianc/market-prediction


6. Pushed Local Changes to GitHub
Pushed local commits to GitHub:
Pushed the initial commit to the remote repository
git push -u origin master


7. Created a New Branch for Feature Development
Created a new feature branch:
Created a new branch feature/add-about-project for the 'About the application' section
git checkout -b feature/add-about-project

Created a new file appinfo.txt:
Added details about the project in appinfo.txt on the feature/add-about-project branch.

Staged and committed the new file:
git add appinfo.txt
git commit -m "Added appinfo.txt with details about the application"


8. Pushed the New Branch to GitHub
Pushed the feature/add-about-project branch to GitHub:
Pushed the new branch to the remote repository:
git push origin feature/add-about-project


9. Incorporated Changes from the Master Branch
Made a change in the master branch:
Switched back to master and modified main.py.
Committed the changes in master:
Committed the changes in main.py
git commit -am "Modified main.py in master"
Switched back to feature/add-about-project branch:
git checkout feature/add-about-project
Pulled changes from master into feature/add-about-project:
git pull origin master


10. Finalized Changes and Pushed the Feature Branch
Made further changes (e.g., updating index.html):
Edited index.html on the feature/add-about-project branch.
Staged and committed the changes:
Staged and committed changes to the index.html file:
git add index.html
git commit -m "Updated index.html with new content"
Pushed the changes to GitHub:
git push origin feature/add-about-project



-------------Recap git commands used in the asignment---------------------

git init

git add .

git commit -m "Initial commit: added index.html, main.py, and styles.css"

git remote add origin https://github.com/mariaianc/market-prediction

git push -u origin master

git checkout -b feature/add-about-project

git add appinfo.txt

git commit -m "Added appinfo.txt with details about the application"

git push origin feature/add-about-project

git checkout master

git commit -am "Modified main.py in master"

git checkout feature/add-about-project

git pull origin master

git add index.html

git commit -m "Updated index.html with new content"

git push origin feature/add-about-project






