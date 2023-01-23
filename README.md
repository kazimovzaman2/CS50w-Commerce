# CS50W Project 2 - Commerce
Status: completed and submitted (Pass)
  
## Description
* [Project specification](https://cs50.harvard.edu/web/2020/projects/2/commerce/#specification)
* **[Django](https://www.djangoproject.com) is used as web framework** and SQLite as the database.

## Setup 
> Python and [Git](https://git-scm.com) must be installed on your computer.  
> Creating a virtual environment is optional, but it is usually better to do so if you know how.
Clone this repository
```bash
git clone https://github.com/kazimovzaman2/CS50w-Commerce.git
cd cs50w_commerce
```  
Install any required dependencies
```
pip install -r requirements.txt
```  
Initialize the database
```
python manage.py makemigrations auctions
python manage.py migrate
```  
Run the development server
```
python manage.py runserver
```

## Demo
![image](https://user-images.githubusercontent.com/92586852/213959465-8bdca7bd-ce89-461b-af78-58b003cc6152.png)

## Note on academic honesty
If you're taking CS50W, either through [Harvard Extension School](https://extension.harvard.edu/), [Harvard Summer School](https://summer.harvard.edu/) or [OpenCourseWare](https://cs50.harvard.edu/web/), please do not blindly copy paste my code. You are putting yourself at a huge risk for getting excluded from the course by the staff themselves as they grade each project thoroughly. This is a course offered by Harvard, and you will be put up to their standard.
