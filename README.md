# Quizzit
This Django-based application presents an interactive platform where users can play quizzes, evaluate their performance, and compare scores with others. Through a user-friendly interface, players can select from various quiz categories, test their knowledge, and track their scores over time. The incorporation of a leaderboard feature fosters a sense of competition and community, motivating users to achieve higher ranks. With seamless integration between front-end and back-end components, robust security measures, and scalability, this application provides an engaging and secure environment for users to participate in quizzes, enhance their knowledge, and connect with fellow quiz enthusiasts.

Uses an external library, AJAX from Google APIs:
http://ajax.googleapis.com/ajax/libs/jquery/1.7.1/jquery.min.js

# How to run

Make sure to download all the requirements from the requirements.txt file using this command:

pip install -r requirements.txt

Once all the requirements are installed, please follow these instructions in order:

Run this command to migrate the changes in the database:

python manage.py migrate

Run this command to start the development server:

python manage.py runserver

Have fun playing the quizzes!
