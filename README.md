# PyEditorial
A free, open-source Blog CMS based on the "Django" and "Editorial" HTML5 theme.

------------
### Features

- "Blog" section to create and edit a blog + Blog Category
- "Videocast" section to create and edit a videocast + Videocast Category
- "Podcast" section to create and edit a podcast + podcast Category
- "Skill" section to create and edit a skill
- "CONSTANCE" Section to manage dynamic Django settings (Blog title, Social Networks links and ...)
- Displays the list of Blog posts as paged in archive
- Displays the list of Videocast as paged in archive
- Displays the list of podcast as paged in archive
- Used "Django Admin" to manage all models
- Used "Editorial" theme by HTML5 UP
- Used "Sqlite" to create DB
- Used "CKEditor"
- Translation ready
- Auth system (login & logout and forget a password)
- Front-end forms to create new object
------------
[![](https://s16.picofile.com/file/8419124942/buy_me_a_coffee.png)](https://www.blockchain.com/btc/payment_request?address=1ChqZPGhxpn6HB1WuQh55S3Mf8RydxMiFk&amount=0.00018711 "Buy me a coffee")
- You can buy me a coffee so I can turn it into more open source projects :)
------------
### Special Thanks

| Python | Django | Pycharm |
| ------------- | ------------- | ------------- |
| [![](https://s17.picofile.com/file/8418101118/python.png)](https://www.python.org "Python")  | [![](https://s17.picofile.com/file/8418100976/django.png)](https://www.djangoproject.com "Django")  | [![](https://s17.picofile.com/file/8418101034/pycharm.png)](https://www.jetbrains.com/pycharm/ "Pycharm")  |

------------
### Screenshots

![](Screenshots/Index.png)
> Index Page

![](Screenshots/Archive.png)
> Archive Page

![](Screenshots/Blog-Single.png)
> Blog Single Page

![](Screenshots/Podcast-Single.png)
> Podcast Single Page

![](Screenshots/Videocast-Single.png)
> Videocast Single Page

![](Screenshots/Admin.png)
> Admin Area

![](Screenshots/Constance.png)
> Dynamic Django Settings

![](Screenshots/Blog-Admin.png)
> Blog Section

![](Screenshots/Add-Blog.png)
> Add Blog

![](Screenshots/Add-Videocast.png)
> Add Videocast

![](Screenshots/Add-Skill.png)
> Add Skill

![](Screenshots/Add-Podcast.png)
> Add Podcast

------------
### How to install and run (GNU/Linux and Mac)
                
1. Install `git`,`python3`, `pip3`, `virtualenv` in your operating system
2. Create a development environment ready by using these commands
```
git clone https://github.com/artem712/CMS		# clone the project
cd PyEditorial		                                        # go to the project DIR
virtualenv -p python3 .venv		                        # Create virtualenv named .venv
source .venv/bin/activate		                        # Active virtualenv named .venv
pip install -r requirements.txt		                        # Install project requirements in .venv
python manage.py makemigrations		                        # Create migrations files
python manage.py migrate		                        # Create database tables
python manage.py collectstatic		                        # Create statics files
python manage.py runserver		                        # Run the project
```
3. Go to  `http://127.0.0.1:8000/` to use project
------------
------------
### Run with Docker

1. Install Docker on your operating system
2. Install docker-compose on your operating system
3. Run the following command to create and run the project
```
docker-compose up [-d]
```
3. Go to  `http://127.0.0.1:8000/` to use project
------------

