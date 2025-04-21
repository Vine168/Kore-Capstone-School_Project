# Kore - Pregnancy Management Web Application

## 🔍 Project Overview
A web application to support Cambodian pregnant women with:
- Health education
- AI chatbot assistance
- Community sharing

## 🎯 Main Features
- AI chatbot in Khmer
- Educational blogs and videos
- Community forum
- User profile management
- Admin dashboard

## 🛠 Technologies Used
- **Frontend:** React.js, Tailwind CSS
- **Backend:** Node.js, Express.js
- **Database:** MongoDB
- **AI/ML:** Python, FastAPI, XLM-RoBERTa
- **Tools:** GitHub, Postman, Figma, Jupyter

## 👨‍💻 Team
- Mean Piseth
- Morm Lyda
- Hour Livhoung
- Chim Vine
- Chort Sereivathana
- Channroy Channdararith

## 📅 Timeline
- Jan–Apr 2025 (3 months)

## 🧠 Goal
To improve maternal care access and education in Cambodia through digital solutions.

## Demo 
If you want to know more about this project, you can click on Demo Folder for know more about it 



server : cd backend/server/
         node server.js
         nodemon server.js

-open another terminal

run fast api as python file 
cd backend 

uvicorn backend.fast_api:app --reload --port 8000

add the missing file 

cd backend/server

mkdir .env 
download in google drive for save  .env
===================================================================
donwload and save in directory : https://drive.google.com/drive/folders/1DSenOnmcoM_KeJI-amZm13PcRKsInv4Z?usp=sharing
====================================================================


Ai part

download model to put for ai and move these file below into /backend/data/
open and download : https://drive.google.com/drive/folders/1lMyQ7v0yANRJqjdBr3PhxZ-1iK8Tt-pa?usp=sharing 
open and download : https://drive.google.com/drive/folders/1QYf7iQn0bQfjtmnQBwNBfGUBbtJy_wwN?usp=sharing

after download that model and save in the follow directory 
please rename it in /backend/fast_api.py line 86 
to your current directory that save on your model 
ex : "/Users/lsbizz/Documents/AllMyCode/Capstone_Project/Pregnancy_Project 2/backend/data/kore_xml2"

than change to specific yours
=====================================================================



the video and blog 

go to localhost:5173/login/admin/project

login as admin : email : dararithzone@gmail.com
                 password : admin123

upload the blog and video and then will display in user interface 

======================================================================

community part :

create the user account in signup after click on ( សហគមន៍ ) on the navbar 
after sign up then login with that account and can use the community 

can post and comment like 

after click post for post u need to approve in admin panel ( user request ) to approve or reject 

=======================================================================







