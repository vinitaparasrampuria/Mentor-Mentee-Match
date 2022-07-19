# hackathon--alpharetta

Tech Alpharetta Women’s Forum is to advance opportunities for females working in STEM careers, by offering networking, educational and mentoring events in local community.

The goal of this project is to provide a website demo of user registration, mentor-mentee matching, and appointment scheduling for Tech Alpharetta.

Tech used:
1. Django 
- sign up, sign in, sign out
- appointment scheduling
2. AWS 
EC2 - Django project deployment
AWS Lex - use chatbot for mentor-mentee matching
AWS Lambda function - format data from chatbot, send back to Django, assign a mentor to a mentee
AWS Dynamo DB - database

![backend diagram](backend-architecture-diagram.png)

https://github.com/Qi1122/hackathon--alpharetta/blob/main/backend-architecture-diagram.png?raw=true