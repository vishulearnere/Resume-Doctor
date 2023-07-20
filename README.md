# Resume Doctor

[![forthebadge made-with-python](http://ForTheBadge.com/images/badges/made-with-python.svg)](https://www.python.org/)  
[![Python 3.8|3.9](https://img.shields.io/badge/python-3.8-blue.svg)](https://www.python.org/downloads/release/python-360/)
[![Open in Streamlit](https://static.streamlit.io/badges/streamlit_badge_black_white.svg)](https://resumedoctor.streamlit.app/)




![SRA_Logo](https://github.com/vishulearnere/Resume-Doctor/assets/63242162/8c5a6ca4-7a4a-41c4-bbb8-0654dcd90141)

<img src="https://raw.githubusercontent.com/vishulearnere/Resume-Doctor/main/SRA_Logo.png">


**Resume Doctor** is a web- app which is designed to help users extract information from their uploaded resumes and provide them with career recommendations based on their skills and experience level. <br> <br>
Resume Doctor App has two sections:- User’s & Admin Section <br>
- User's section:-
    - It also provides resume-writing tips and suggestions to help users improve their resumes. The project also provides a resume score which helps users understand how well their resume is written. The courses recommendations feature helps users find courses that are relevant to their skills and experience level. The skills recommendations feature helps users find skills that are relevant to their career goals. The youtube video recommendations feature helps users find videos that are relevant to their career goals.

- Admin Section:- 
    - The admin section of the project provides features such as fetching user’s data who have uploaded their resumes from a remote server and displaying it. It also allows the admin to download the user's data in CSV format. The analysis of all user’s data features provides insights into the predicted domain, experience level, resume score, and tech skills of all users.

## Source

- Extracting user's information from the Resume, I used [PyResparser](https://omkarpathak.in/pyresparser/).
- Extracting Resume PDF into Text, I used [PDFMiner](https://pypi.org/project/pdfminer/).
- For Creating UI, I used [Streamlit](http://streamlit.io/) Library.
- For Remote Database Access, I used [remotemysql](http://remotemysql.com/).
- To fetch videos from Youtube, I used youtube-dl 

## Features

- User's & Admin Section
- Connection of User's Data on Renote MYSQL server

### Users Section

- Extracting User's Info from resume
- Career Recommendations
- Resume writing Tips suggestions
- Resume Score
- Courses Recommendations
- Skills Recommendations
- Youtube video recommendations

### Admin Section 

- Fetch user's Data from Remote server and Display it.  
- Download the Users Data in CSV format
- Analysis of All User's Data
    - Predicted Domain 
    - Experience level
    - Resume Score
    - Tech Skills

- Analysis of All User's Data Filtered By Tech Domain


## Usage
- `App.py` is the main Python file of Streamlit Web-Application.
- `Courses.py` is the Python file that contains courses and youtube video 
- `Uploaded_Resumes` folder is contaning the user's uploaded resumes.


## Admin Side
[admin_video (1).webm](https://user-images.githubusercontent.com/63242162/194629070-db69e862-a055-4e63-a1bc-dd4a88ea52bd.webm)


## User side
[user_video (1).webm](https://user-images.githubusercontent.com/63242162/194629469-e1505d53-ca68-4915-92f3-f095caad7ba7.webm)



## All the Images, Media, Content and Code  are  __Copyright Protected__ and need my permission for further use.
