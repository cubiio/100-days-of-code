# 100 Days Of Code - Log
- - - -
### Day 36: Tue 7-Feb-2017

**Progress / Thoughts:**

- My first code using MV* (* = Octopus i.e. the Controller). I understand the concept, applying and writing code is not so easy! Made a good stab of it with the Cat Clicker project, and saw how it is easier to add new functionality. My issue was adding functionality that actually worked :) although I got some aspects working in the time available.
- On my ‘To Do’ list is to research and understand better the JavaScript keyword `this`. Used it in the code but not fully sure how it works (I think it is similar to `self` in Python…?)

**Link(s) to work:**

- [Udacity FSND mini-project: Cat Clicker](https://github.com/cubiio/fsnd-cat-clicker/tree/master)

- - - -
### Day 35: Mon 6-Feb-2017

**Progress / Thoughts:**

- Completed one Python challenge on Code Wars. Next project is JavaScript so want to continue learning more about Python
- Udacity lesson code and started to learn about MV*, interesting stuff and can’t wait to get started on the project itself. Lots to learn before then though…

**Link(s) to work:**

- [Udacity FSND mini-project: Cat Clicker](https://github.com/cubiio/fsnd-cat-clicker/tree/master)

- - - -
### Day 34: Sun 5-Feb-2017

**Progress / Thoughts:**

- Sunday morning fun doing some Code Wars, practising my Python skills
- Leveled up: I’m now **7kyu** 
- [cubiio | Codewars](https://www.codewars.com/users/cubiio)

- - - -
### Day 33: Sat 4-Feb-2017

**Progress / Thoughts:**

- Udacity lesssons re AJAX requests
- Added NYT AJAX request, adding articles and anchor links relevant to the city submitted in the form 

**Link(s) to work:**

- [FSND mini-project: Move Planner using Javascript and AJAX requests](https://github.com/cubiio/fsnd-movePlanner)

- - - -
### Day 32: Fri 3-Feb-2017

**Progress / Thoughts**

- Web scraping. Thoughts: interesting but picked a bad example to try it out(restrictions web scraping a search engine?)
- Not strictly speaking ‘building shit’ but I followed this excellent [post](https://janikarhunen.fi/three-steps-to-lint-python-3-6-in-sublime-text.html) to install Flake8 Python linter for Sublime Text 3
- Played around with Pelican - Python static blog generator. Verdict? I’m sticking with [Hugo](https://www.gohugo.io/)
- Start lessons for my next project - a Neighbourhood Map built with JavaScript, and utilising various AJAX requests

- - - -

### Day 31: Thu 2-Feb-2017

**Progress / Thoughts**

- Played around with modals but couldn't get it to work as I liked it. Will revisit another time.
- Probably not part of the rules but did some Code Wars too.

**Link(s) to work:**

[GitHub - cubiio/portfolio: My Portfolio](https://github.com/cubiio/portfolio)

- - - -
### Day 30: Wed 1-Feb-2017

**Progress:**

* Updates to my Portfolio site including
	* refactor Gulp tasks to simplify and remove folder structure
	* add Nunjucks 
	* refactor code into Nunjucks templates and partials
	* add a for loop for my portfolio images and supporting info


**Thoughts:**

* Nice to play around with Nunjucks which feels just like a front-end version of Jinja2
* Portfolio is now update to date with my latest Udacity projects

**Link(s) to work:**

* [GitHub: My Portfolio](https://github.com/cubiio/portfolio)

- - - -
### Day 29: Tue 31-Jan-2017

**Progress:**

* Bootstrap, bootstrap and more bootstrap
* Finished the README document


**Thoughts:**

* Bootstrap is great when it works, fast and relatively easy to get a good looking, responsive site up and running. The difficulty is when you want to apply your own CSS and it doesn’t work, difficult to resolve as you don’t have the detail of what is in Bootstrap. Pros and cons of using Bootstrap I guess!

**Link(s) to work:**

* [GitHub - FSND project - Item Catalog](https://github.com/cubiio/fsnd-item_catalog)


- - - -
### Day 28: Mon 30-Jan-2017

**Progress:**

* Refactored to `Flask Blueprint` including resolving various bugs (in particular making sure `url_for()` worked across all pages
* Refactored my `database.py` file, and other modules are now DRY i.e. using `db_session` to connect to `database.py`
* Implemented CSRF protection for my forms 
* Added a `config.py` file
* Linted my code with `pylint`
* Added Bootstrap css files to the `/static/css` folder. Styling fun starts tomorrow!


**Thoughts:**

* Pleased with the refactoring achieved today
* Backend mostly complete, will now shift to front-end

**Link(s) to work:**

* [GitHub - FSND project - Item Catalog](https://github.com/cubiio/fsnd-item_catalog)


- - - -
### Day 27: Sun 29-Jan-2017

Weekend and family time, whilst also recovering from a cold, meant limited time to code.

**Today’s Progress**:

* Played around with `Flask Blueprint` creating a new skeleton repo to see how it all fits together.
* Researched various topics to action tomorrow including CSRF tokens for WTForms.

**Thoughts**

* It was a good idea to simplify and start a new skeleton Blueprint repo to see how it works. I now get (via the excellent tracebackk from Werkzerug that `url_for()` in a Jinja template should read `{{url_for(‘BluePrintRouteName.MethodName’)}}`
* Actually taking a day off from coding and my projects is a good thing mentally. I want to complete the 100 day challenge but as I’m able (currently at least) to put in significantly more than 1 hour a day into my projects, I might take Sundays off going forwards

- - - -

### Day 26: Sat 28-Jan-2017

**Today’s Progress:**

Continued to work on my item catalogue using Python Flask.

* Refactoring using `Flask Blueprint`

**Thoughts:**

* Refactored my `.py`  files and put in new folder structure, but getting some `BuildError`. Coming down with a cold, plus it’s the weekend, so bug squashing will have to wait. 


**Link(s) to work:**

* [GitHub - Item_catalog - dev branch](https://github.com/cubiio/fsnd-item_catalog/tree/dev)



- - - -

### Day 25: Fri 27-Jan-2017

**Today’s Progress**:

Continued to work on my item catalogue using Python Flask.

* Completed OAuth 2.0 login / logout functionality via Google
* Added local permission systems i.e. only ‘authors’ can edit / delete their own content

**Thoughts**

* I can see the advantages of using a micro framework like Flask, good functionality available with minimal code. One of the downsides is not knowing exactly how the underlying code works exactly.


**Link(s) to work**:

* [GitHub - FSND project - Item Catalog](https://github.com/cubiio/fsnd-item_catalog)


- - - -

### Day 24: Thu 26-Jan-2017

**Today’s Progress**:

Continued to work on my item catalogue using Python Flask.

* Users can edit categories, and books
* Users can delete categories, and books 
* Added form validation using WTForms
* Stared to build OAuth 2.0 login / logout functionality via Google

**Thoughts**

* Making good use of WTForms, and worked it out from using the documentation.


**Link(s) to work**:

* [GitHub - FSND project - Item Catalog](https://github.com/cubiio/fsnd-item_catalog)


- - - -

### Day 23: Wed 25-Jan-2017

**Today’s Progress**:

Started my next project, building an item catalogue (or catalog if you prefer) using Python Flask.

* Design the database structure and built the code
* Coded a database populater so I have some data for dev purposes
* Built routes to render basic Jinja2 templates 
* Added a form to add a new category
Built a `POST` method to persist a new category to the Db
* Added a form to add a new book, including a dropdown menu built with `{{category.variables}}`.
* Built a `POST` method to persist a new book to the Db

**Thoughts**

* Feels good to be seriously coding again after a couple of days studying.
* Particular pleased with my variable based dropdown menu, and how the `POST` method works alongside it.


**Link(s) to work**:

* [GitHub - FSND project - Item Catalog](https://github.com/cubiio/fsnd-item_catalog)


- - - -

### Day 22: Tue 24-Jan-2017

**Today’s Progress**:

* Learned about OAuth. Coded a Google Plus OAuth access, following along with the Udacity course videos and notes.


**Thoughts**

* Need to revisit some of the code tomorrow to make sure I understand it.
* Will also start my next project in earnest tomorrow which will provide a good opportunity to practice building some OAuth integrations. I’m thinking of building Google and GitHub OAuth authorisations into my app.


**Link(s) to work**:

* [Oauth lesson code and mini-project](https://github.com/cubiio/oauth)


- - - -

### Day 21: Mon 23-Jan-2017

**Today’s Progress**:

Study time. Today I built a simple Python web server, then learned about Flask, using CRUD with Flask and RESTful APIs.

**Thoughts**

* The benefit of using a framework is clear, really reduces the amount of repetitive code. That said, I fully understand the argument that you should know the language before diving into using a framework.
* It was also very interesting to compare the Google App Engine framework with Flask. 


**Link(s) to work**:

* [Udacity lesson code](https://github.com/cubiio/fsnd-fsFoundations)


- - - -

### Day 20: Sun 22-Jan-2017

**Today’s Progress**:

Final tidy-up of my blog project: 

* Removed redundant Jinja controls on the templates. My code reviewer said all controls must be done server side and I wrote the decorators for various `get()` and `post()` methods to achieve this. 


Then back to the item catalogue project, watched a few more of the videos from lesson 1, and worked on the first problem set.

**Thoughts**

* Learned about building a database and using queries via  `SQLAlchemy`. Interesting to compare it against Google App Engine, used in the last project. 

**Link(s) to work**:

* [Animal shelter: Problem Set](https://github.com/cubiio/animalshelter)
* [Udacity lesson code](https://github.com/cubiio/fsnd-fsFoundations)
* [Udacity project: Blog](https://github.com/cubiio/fsnd-blog)


- - - -

### Day 19: Sat 21-Jan-2017

**Today’s Progress**:

Tidy-up of my blog project: 

* I corrected the `@user_logged_in` decorator to check for secure values 
* Added tag v3.0
* Updated the README

Then on to the next project: item catalogue. 

Watched a few of the videos from lesson 1 and created the database setup file to use with SQLAlchemy. 


**Thoughts**

* Good to get started on the next project. I got the Vagrant virtual box set-up. I last used this months ago for the Intro to Programming Nanodegree. 

**Link(s) to work**:

* [Udacity lesson code](https://github.com/cubiio/fsnd-fsFoundations)
* [Udacity project: Blog](https://github.com/cubiio/fsnd-blog)


- - - -

### Day 18: Fri 20-Jan-2017

**Today’s Progress**:

Now it’s official: my project passed the Udacity code review! In addition to this great news, today I built my first Python decorators. Finally got how they work and was able to write 4 different `@decorators` to control some of `get()` and `post()` methods.


**Thoughts**

* Great to have completed the project! I really feel like I’m making progress.

**Link(s) to work**:

* [Udacity project: blog](https://github.com/cubiio/fsnd-blog)
* [Demo: Cubiio Blog](https://cubiio-blog.appspot.com/)

- - - -

### Day 17: Thu 19-Jan-2017

**Today’s Progress**:

My Build a blog project is complete! Well almost. :) Submitted today for review by Udacity. The final functionality was completed including editing/deleting comments. I also did improved some styling (relatively speaking - I’m freely admit I’m no designer). And I installed Pylint and linted my code. 

Let’s see what the Udacity reviewer says…

**Thoughts**

* Great feeling to complete the project (subject to Udacity’s feedback and decision of course). This is why I’m learning to code!
* Onwards tomorrow with the next project…

**Link(s) to work**:

* [Udacity project: blog](https://github.com/cubiio/fsnd-blog)
* [Demo: Cubiio Blog](https://cubiio-blog.appspot.com/)


- - - -

### Day 16: Wed 18-Jan-2017

**Today’s Progress**:

_Build a blog project_

* Users can like and unlike posts.
* A like counter shows how many people liked a post.
* Added styling including making anchors look like buttons. (Neat trick - found how to do this in CSS on Stack Overflow).
* Started to build edit comments functionality.


**Thoughts**

* Finally cracked finding an entity id in order to modify / delete the entity. 
* I was much more methodical in my work today, following a planned build, test, iterate approach. Really helped my productivity.

**Link(s) to work**:

* [Udacity project: blog](https://github.com/cubiio/fsnd-blog)

- - - -

### Day 15: Tue 17-Jan-2017

**Today’s Progress**:

Project: build a blog 

* Users can like blogposts
* Constraint: authors can’t like their own posts
* Wrote my very first `@classmethod`


**Thoughts**

* Some good progress but mainly a day of frustration trying to figure our database queries and why my code either throw errors or wasn’t giving the expected result.
* A tough day but learned a lot. 
* Key lesson: write, test, iterate. 
	* **Write** small pieces of code / functionality
	* **Test** to see if it works and gives the expected result
	* **Iterate** i.e. write the next small piece of code / functionality.
	* Final thought: plan the **write / test / iterate** approach so you understand how to develop more and more functionality, whilst testing as you go to make sure it works. 


**Link(s) to work**:

* [Udacity project: blog](https://github.com/cubiio/fsnd-blog)

- - - -

### Day 14: Mon 16-Jan-2017

**Today’s Progress**:

Project: build a blog 

* Added user commenting functionality 
* Add authors (query) to display who wrote the post
* Added author based constraints i.e. only authors can edit and delete their own posts 
* Think I've designed how the like functionality will work. Will build and test tomorrow. 
* Worked out how to build and use my first `@classmethod`  !! :) 


**Thoughts**

* Good progress. Plenty of head scratching how to build my data Model and build queries but once I got it, huge satisfaction. 
* Really excited to build and test my like design to see if it works and in particular to code my very own first `@classmethod` decorator.


**Link(s) to work**:

* [Udacity project: blog](https://github.com/cubiio/fsnd-blog)

- - - -
### Day 13: Sun 15-Jan-2016

**Today’s Progress**:

Family day but managed just over an hour early morning to work on adding authors, to the Model and Page Handlers, and working datastore queries. 

**Thoughts**:

* Spent my hour coding and testing datastore queries to include in my blog app.


**Link(s) to work**:

* [Udacity project: blog](https://github.com/cubiio/fsnd-blog)

- - - -
### Day 12: Sat 14-Jan-2016

**Today’s Progress**:

Family day but managed just over an hour early morning to work on adding authors, to the Model and Page Handlers, as well as the Jinja template e.g. “Post written by …”.


**Thoughts**:

* Busy day on other stuff but pleased I still managed to get my hour in. 
* In addition, I research various articles on Python and Google App Engine when I had a few spare moments. Plenty to read and I think Monday will be a busy day implementing all these ideas.

**Link(s) to work**:

* [Udacity project: blog](https://github.com/cubiio/fsnd-blog)


- - - -
### Day 11: Fri 13-Jan-2016

**Today’s Progress**:

Continuing to add functionality to my build a blog project:

* Users can edit blogposts
* Users can delete blogposts

**Thoughts**:

* A lot going on today so less time to work on this than originally planned, still pleased with the progress and am getting to grips with how Google App Engine works. The documentation is really good, great examples of how it all works. 

**Link(s) to work**:

* [Udacity project: blog](https://github.com/cubiio/fsnd-blog)


- - - -
### Day 10: Thu 12-Jan-2016

**Today’s Progress**:

A day of solid achievement:

* Migrated from Google App Engine (GAE) Datastore `db` to `ndb` 
* Updated my project README including a breakdown and explanation of the revised repo structure
* Read lots of GAE documentation
* Extended user login across all pages, thereby enabling a restriction that only users may write blog posts
* On the main page, changed the blogpost title to a URL redirecting through to the permalink page of the blogpost

**Thoughts**:

* Really pleased with the progress. Laid the groundwork now to move on to address the specific user requirements for the project i.e. comment, likes, edit and delete posts.

**Link(s) to work**:

* [Udacity project: blog](https://github.com/cubiio/fsnd-blog)

- - - -
### Day 9: Wed 11-Jan-2016

**Today’s Progress**:

* A good day! :) 
* Found and fixed a bug in the cookie hashing helper functions
* Got user registration, login and logout working. 
* Added bonus, I restructured my repository per Python best practices.


**Thoughts**:

* After the lows of yesterday, the highs of a good day, really pleasing to work through `Set-Cookie` and to implement it in user registration, login and logout.
* Yesterday I was getting frustrated wading through a file with over 250 lines of code, so was pleasing to work through how to restructure the repository in line with best practices. 
* Looking forward to tomorrow’s challenges of adding further functionality to the blog.

**Link(s) to work**:

* [Udacity project: blog](https://github.com/cubiio/fsnd-blog)


- - - -
### Day 8: Tue 10-Jan-2016

**Today’s Progress**:

* A quick win in the morning: redid my front-end workflow to include Nunjucks, and then did a simple imitation of Yeoman to scaffold a front end project using Python. Nothing fancy but folder structure gets set-up and the Github clone takes place, all from the command line.
* Udacity FSND studies: 
	* Jinja templates set-up
	* Password and cookie hashing added
	* Cookie checking and setting added
	* Handlers for different pages added

**Thoughts**:

* Udacity FSND studies: a lot of frustration trying to make progress with the blog project. Setting cookies and determining if a user is logged in caused me problems, perhaps a problem with inheritance from a handler? I think I’ll review it against the tutor’s solution, study the code and rationale behind it, then start again to really get to grips with it and understand it. 
* To end on a positive, pleased with my basic Yeoman scaffolding tool. Used `gitpython` this time to script a `git clone` command.


**Link(s) to work**:

* [Automation experiments](https://github.com/cubiio/automate-boring-stuff-python)
* [Udacity project: blog](https://github.com/cubiio/fsnd-blog)


- - - -
### Day 7: Mon 9-Jan-2016

**Today’s Progress**:

*Morning*

* Experiment 1: played around with Nunjucks and Gulp. Got a Gulp task up and running to render html based on `.njk` templates.
* Experiment 2: Wrote a Python script to automate deploying  my Hugo powered [blog](https://cubiio.github.io/). 

*Afternoon*

* Back to my Udacity FSND studies, focussing on my build a blog project and the first problem set - user registration.

**Thoughts**:

* Really like the excellent Python `sh` module which I discovered via StackOverflow. Used it for my Python automation experiments.
* Regarding my project to build a blog, pleased with some of the progress I made but need to get my head around some of the new teaching content e.g. setting cookies. 

**Link(s) to work**:

* [Automation experiments](https://github.com/cubiio/automate-boring-stuff-python)
* [Nunjucks template](https://github.com/cubiio/nunjucks-template)
* [Udacity project: blog](https://github.com/cubiio/fsnd-blog)

- - - -
### Day 6: Sun 8-Jan-2016

**Today’s Progress**:

* Switching gears today and learning some Python with the book “Automate the Boring Stuff with Python”. Played with some regex stuff and finalised the mini-project for an email and phone number finder.

**Thoughts**:

* Regex always seemed very daunting but this book had a good intro to what it is and how it works with lots of good examples. I think it is still hard to master but I understand more about how it works.

**Link(s) to work**:

* [GitHub - Follow along with the book ‘Automate the boring stuff with Python’](https://github.com/cubiio/automate-boring-stuff-python)

- - - -
### Day 5: Sat 7-Jan-2016

**Today’s Progress**:

* For my ‘build a blog using Python’ project, I added a header, navbar and footer to the Jinja `base.html` template.

**Thoughts**:

* I gave some thought on how to develop the next level of functionality for the blog:
	* User registration
	* User login
	* User logout
* These form part of the problem sets and I will look to start coding these next week.

**Link(s) to work**:

* Source code [Python blog project](https://github.com/cubiio/fsnd-blog)

- - - -
### Day 4: Friday, 6th January 2017
**Today's Progress**:

* Completed Udacity's User Accounts & Security module.
* Topics and code covered today include hashing and salting, and using bcrypt.

**Thoughts**:

* Interesting topic and keen to put into practice in the upcoming problem sets.

**Link(s) to work**:

* [Security lesson code](https://github.com/cubiio/fsnd-security)

- - - -
### Day 3: Thursday, 5th January 2017
**Today's Progress**:

* Finalised a basic blog using Python, Jinja and Google App Engine.
* Today I added a handler to redirect to a permalink after a post is successfully submitted.
* I also revised the Jinja templates so all the child html pages inherit from a `base.html` parent which includes a header.
* Continued my Udacity learning with User Accounts & Security module.

**Thoughts**:

* Pleasing to work through the permalink solution. The Udacity video on this was very helpful although still frustrated I couldn't work it out from the webapp2 and App Engine documentation.

**Link(s) to work**:

* [Blog GitHub Repo](https://github.com/cubiio/fsnd-blog)
* [Basic blog demo](https://cubiio-blog.appspot.com/)
* [Security lesson code](https://github.com/cubiio/fsnd-security)

- - - -
### Day 2: Wednesday, 4th January 2017
**Today's Progress**:

* Built a basic blog using Python, Jinja and Google App Engine

**Thoughts**:

* All went well but got stuck on building URLs for new blog-posts. Couldn't get to grips with the documentation for Webapp2 and Google App Engine. *Frustrating*.
* Tomorrow's task is to complete the URLs and permalink, further refine my Jinja templates and add some CSS.

**Link(s) to work**:

* [Blog GitHub Repo](https://github.com/cubiio/fsnd-blog)

- - - -
### Day 1: Tuesday, 3rd January 2017
**Today's Progress**:

* Udacity FSND (Full-Stack Nanodegree) Intro to Databases module:
	* More SQL (Structured Query Language) content, including the use of indices and the ACID principle
	* Started ASCII Chan mini project: Python project using Google App Engine including the Datastore, and Jinja for HTML templates

**Thoughts**:

* Useful intro to databases but also feels good to be working on a mini-project and following along with the tutor to build a web app.
* Good fun to build a first app using the Google App Engine Datastore. Next up is the database problem set so looking forward to that.

**Link(s) to work**:

* [Ascii Chan repo](https://github.com/cubiio/fsnd-aschiiChan)
* [Database lesson repo](https://github.com/cubiio/fsnd-databases)

- - - -
### Day 0: Monday, 2nd January 2017
**Today's Progress**:

* Udacity FSND (Full-Stack Nanodegree) Intro to Databases module.
	* Learned about SQL (Structured Query Language)
	* SQL queries in Python

**Thoughts**:

* I like the clean readability of SQL queries
* The intro course is good and it also feels like a refresher course which I like. I did the [tournament planner](https://github.com/cubiio/tournament-planner) project in PostgreSQL as part of the **Intro to Programming Nanodegree** earlier this year.

**Link(s) to work**:

* [Github repo](https://github.com/cubiio/fsnd-databases)

- - - -
### Day -1: Sunday, 1st January 2017
**Today's Progress**:

* Completed Udacity backend problem set no 2 - user sign-up form
* Languages: Python and Jinja2 templates

**Thoughts**:

* Placing the {{variables}} in the Jinja template threw me at first as I thought  my Python code didn't work but actually it was because I had no {{ }}.
* The use of the dictionary for the params in the solution is really smart and something to read up and consider for future coding / projects.

**Link(s) to work**:

* [Sign-Up Form](https://cubiio-rot13.appspot.com/signup)

- - - -
## Template / Example

- - - -
### Day x: Tuesday, 3rd January 2017
**Today's Progress**:

* Add comments here

**Thoughts**:

* Add thoughts

**Link(s) to work**:

* [this link](http://samatkins.me/)




