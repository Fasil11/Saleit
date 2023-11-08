Saleit an e-commerce App Project
Saleit is a web application built using Django Rest Framework for the backend and React for the frontend.
It is mainly Design to sale second hand items focusing on Bags, clothes and Shoes

Table of Contents
Installation
Setup
Usage
Libraries Used
Contributing
License
Installation
To get started with the Saleit project, follow these steps:

Clone the repository to your local machine:
bash
Copy code
git clone https://github.com/Fasil11/SALEIT.git
Navigate to the project directory:
bash
Copy code
cd SALEIT
Setup
Backend (Django Rest Framework)
Create a virtual environment (optional but recommended):
Copy code
python3 -m venv venv
Activate the virtual environment:
bash
Copy code
source venv/bin/activate   # On Windows, use: venv\Scripts\activate
Install the required libraries:
Copy code
pip install -r requirements.txt
Apply migrations:
Copy code
python manage.py migrate
Start the Django development server:
Copy code
python manage.py runserver
Frontend (React)
Navigate to the frontend directory:
bash
Copy code
cd Saleit/client
Install the required libraries:
Copy code
npm install
Usage
To run the project, make sure both the backend and frontend servers are running. Follow the setup instructions above, and then navigate to http://localhost:8000 in your web browser.

Libraries Used
Django Rest Framework
React