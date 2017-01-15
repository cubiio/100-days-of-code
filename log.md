# 100 Days Of Code - Log
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

- - - -
### Meta


