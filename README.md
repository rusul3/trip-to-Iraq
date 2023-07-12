# trip-to-Iraq

## CS50
>This was my final project for conclude the CS50 Introduction to Computer Sciense course.

>CS, python, flask, flask web framework, web development, CS50
## Features

- [Flask-SQLAlchemy](https://flask-sqlalchemy.palletsprojects.com/en/2.x/)
- [Flask](https://flask.palletsprojects.com/en/1.1.x/)

I've used Flask web framework based in Python
its was necessary flask-sqlalchemy for manage SQL database with sqlite

## Explaining the project and the database
My final project is a website that allow the user sign up and login for  planning of visite Iraq (my country ) and give a general introduction to Iraq area . 
The user can also after see the best place to visite add the places to his plan to trip and save it in the account.

All information about users ,selected places want to visit and the planning for trip for each people are stored in database.db.

I used sqlalchemy extension for connect the database to application and sqlite to manager her.

### Sqlachemy and sqlite:
I needed two tables for my database:

- First, table users. Where I put, id, username, hash (for password) and email, notice that id must be a primary key here.

- Second, table cases. I put person_id and email . In photo I store the filename of the static .

  
### Storing geographical_locations live map.
The templates file contain geographical_locations.html.
And attach by extension with the base.html also in templates file 

```html
{% extends "base.html" %} {% block title %}Geographical_location{% endblock %} {% block content
%}
<form method="POST">
    <h1>Geographical Locations</h1>
    <div class="form-group">
        <iframe src="https://www.google.com/maps/embed?pb=!1m18!1m12!1m3!1d6844427.4783130605!2d38.42440043650314!3d33.10893649390678!2m3!1f0!2f0!3f0!3m2!1i1024!2i768!4f13.1!3m3!1m2!1s0x1557823d54f54a11%3A0x6da561bba2061602!2sIraq!5e0!3m2!1sen!2suk!4v1688658185678!5m2!1sen!2suk" width="600" height="450" style="border:0;" allowfullscreen="" loading="lazy"></iframe>
    </div>
    <p>Iraq is located in the Middle East and has a diverse landscape with deserts, fertile plains, and mountainous regions.</p>
</form>
{% endblock %}
``` 



## Pictures
all photos save in static file with styles.css to manage the photos and extension the best_places.html with base.html also link it with the static file

| best_places |
| :---: |




## Demonstration on youtube
For the CS50 final project you have to make a video showning your project,
[My Final Project ]([https://www.youtube.com/watch?v=YAXmRfrcOVc](https://youtu.be/BNg1J6GJ_ho))

## Documentation
https://flask.palletsprojects.com/en/1.1.x/

https://flask-sqlalchemy.palletsprojects.com/en/2.x/


## About CS50
CS50 is a openware course from Havard University and taught by David J. Malan and lovely staff (Brenda Anderson,Doug Lloyd,Glenn Holloway and Rongxin Liu)

Introduction to the intellectual enterprises of computer science and the art of programming. This course teaches students how to think algorithmically and solve problems efficiently. Topics include abstraction, algorithms, data structures, encapsulation, resource management, security, and software engineering. Languages include C, Python, and SQL plus students’ choice of: HTML, CSS, and JavaScript (for web development).

Thank you for all CS50.

- Where I get CS50 course?
https://cs50.harvard.edu/x/2023/
