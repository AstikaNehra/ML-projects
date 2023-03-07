# ML-Projects repository

Contains all my ML-projects in a single repository

## Project 1 - Phishing website prediction

A flask web app consisting of Random forest classifier algorithm to detect phishing websites by considering a few parameters.
Accuracy of the algorithm is 99.8%

### About

1. run the command: pip install -r requirements.txt
-  Troubleshooting: If certain errors pop up related to incorrect versioning of modules, try installing all the modules listed in requirements.txt separately
2. run the command, inside the mysite directory in console: python manage.py migrate
3. run the command in same directory: python manage.py runserver
-  Check the web app here: http://127.0.0.1:8000/
4. Add all the required inputs related to the website/url you want to check, the output will be shown at the bottom of the web-page.

### Future Scope

1. Dockerizing the entire web-app along with dependencies so the devs don't face any dependancy errors while importing the project.
2. Comparing other algos to Random forest.