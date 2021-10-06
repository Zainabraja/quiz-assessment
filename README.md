# Online Quiz Assessment
Online Quiz is a web application for candidate to appear for an
 online test in an effective way and there is no loss of time to
 check the paper. Organizations can also easily check the performance
 of the student that they give in an examination. As a result of this,
 organizations are releasing results in less time. It also helps the
 environment by saving paper. According to today’s requirement,
 online examination project in PHP is very useful to learn it.

https://user-images.githubusercontent.com/86065205/136245906-c9c3d7d4-7965-4e9c-91ac-08ae0b173461.mp4

 Website-link: http://walkoverquiz.pythonanywhere.com/
 
## For Admin Login:
- Username: `admin`
- Password: `admin`
 
## Authors
- [@Palak Gupta](https://github.com/Palakgupta0908)
- [@Paryank Namdeo](https://github.com/Paryank0419)
- [@Zainab Raja](https://github.com/Zainabraja/)

## Tech Stack:
1. `Frontend` : HTML5, CSS3, Javascript.
2. `Backend` : Python, Django.
3. `Database` : MySQL.

## Specifications Assigned:
1. Assessment shall be MCQ pattern.
2. There must be a question pool for the assessment. 
3. The questions displayed in the assessment shall be only from that pool.
4. Number of questions in the pool shall be more than questions displayed.
5. Set a time limit for the assessment (individual timer for a question/optional).
6. Question order shall be shuffled for each candidate appearing.
```
All specifications are satisfied 
```
# Getting Started ```project setup```
Clone the source code in your local machine and install the requirements by running
```bash
pip install -r requirements.txt
```
Finally, run the application using
```bash
python app.py
```
on your python interpreter
If everything executed well and in order then server with port 8000 must be given in terminal copy and paste in browser. Our site must be loaded on local server```.
# CI/CD
we have not used any integration tool
For continuous deployment we have used heroku
created new application on heroku
connected through git repository
Enabled automatic deployment of chnages in master branch of git repository
Deployed the master branch.

## Functions
### Admin
- Create Admin account using command
```
py manage.py createsuperuser
```
- After Login, can see Total Number Of Student, Teacher, Course, Questions are there in system on Dashboard.
- Can View, Update, Delete, Approve Teacher.
- Can View, Update, Delete Student.
- Can Also See Student Marks.
- Can Add, View, Delete Course/Exams.
- Can Add Questions To Respective Courses With Options, Correct Answer, And Marks.
- Can View And Delete Questions Too.

### Student
- Create account (No Approval Required By Admin, Can Login After Signup)
- After Login, Can See How Many Courses/Exam And Questions Are There In System On Dashboard.
- Can Give Exam Any Time, There Is No Limit On Number Of Attempt.
- Can View Marks Of Each Attempt Of Each Exam.
- Question Pattern Is MCQ With 4 Options And 1 Correct Answer.
---

## HOW TO RUN THIS PROJECT
- Install Python(3.7.6) (Dont Forget to Tick Add to Path while installing Python)
- Open Terminal and Execute Following Commands :
```
python -m pip install -r requirements. txt
```
- Download This Project Zip Folder and Extract it
- Move to project folder in Terminal. Then run following Commands :
```
py manage.py makemigrations
py manage.py migrate
py manage.py runserver
```
- Now enter following URL in Your Browser Installed On Your Pc
```
http://127.0.0.1:8000/
```

