[![License](https://img.shields.io/badge/License-Apache%202.0-blue.svg)](https://opensource.org/licenses/Apache-2.0)

## Welcome

Hello. Want to get started with Flask quickly? Good. You came to the right place. This Flask application framework is pre-configured with **Flask-SQLAlchemy**, **Flask-WTF**, **Fabric**, **Coverage**, and the **Bootstrap** frontend (among others). This will get your Flask app up and running on Heroku or PythonAnywhere quickly. Use this starter, boilerplate for all you new Flask projects. Cheers!

<hr>

![real-python-logo](https://raw.githubusercontent.com/realpython/about/master/rp_small.png)

**Designed for the [Real Python](http://www.realpython.com) course.**

<hr>

Preview the skeleton app here - [http://www.flaskboilerplate.com/](http://www.flaskboilerplate.com/)

**What is Flask?** Flask is a microframework for Python based on Werkzeug and Jinja2.

Project Structure
--------

  ```sh
  ├── Procfile
  ├── Procfile.dev
  ├── README.md
  ├── app.py
  ├── main.py
  ├── server.py
  ├── config.py
  ├── error.log
  ├── forms.py
  ├── models.py
  ├── requirements.txt
  ├── static
  │   ├── css
  │   │   ├── bootstrap-3.0.0.min.css
  │   │   ├── bootstrap-theme-3.0.0.css
  │   │   ├── bootstrap-theme-3.0.0.min.css
  │   │   ├── font-awesome-3.2.1.min.css
  │   │   ├── layout.forms.css
  │   │   ├── layout.main.css
  │   │   ├── main.css
  │   │   ├── main.quickfix.css
  │   │   └── main.responsive.css
  │   ├── font
  │   │   ├── FontAwesome.otf
  │   │   ├── fontawesome-webfont.eot
  │   │   ├── fontawesome-webfont.svg
  │   │   ├── fontawesome-webfont.ttf
  │   │   └── fontawesome-webfont.woff
  │   ├── ico
  │   │   ├── apple-touch-icon-114-precomposed.png
  │   │   ├── apple-touch-icon-144-precomposed.png
  │   │   ├── apple-touch-icon-57-precomposed.png
  │   │   ├── apple-touch-icon-72-precomposed.png
  │   │   └── favicon.png
  │   ├── img
  │   └── js
  │       ├── libs
  │       │   ├── bootstrap-3.0.0.min.js
  │       │   ├── jquery-1.10.2.min.js
  │       │   ├── modernizr-2.6.2.min.js
  │       │   └── respond-1.3.0.min.js
  │       ├── plugins.js
  │       └── script.js
  └── templates
      ├── errors
      │   ├── 404.html
      │   └── 500.html
      ├── forms
      │   ├── forgot.html
      │   ├── login.html
      │   └── register.html
      ├── layouts
      │   ├── form.html
      │   └── main.html
      └── pages
          ├── placeholder.about.html
          └── placeholder.home.html
  ```


### Quick Start

1. Clone the repo
  ```
  $ git clone https://github.com/cheshyre/hn-app.git
  $ cd hn-app
  ```

2. Install the dependencies:
  ```
  $ pip3 install -r requirements.txt
  ```

3. Run the development application:
  ```
  $ python main.py
  ```


PUSH and PULL away!

### What's next?

1. Using Heroku? Make sure you deactivate your virtualenv once you're done deploying: `deactivate`
2. Need to reactivate? (1) Unix - `source venv/bin/activate` (2) Windows - `venv\scripts\activate`
4. Add your Google Analytics ID to the *main.html* file
5. Add a domain name to [Heroku](https://devcenter.heroku.com/articles/custom-domains) or PythonAnywhere via a [CNAME](http://en.wikipedia.org/wiki/CNAME_record) record
5. DEVELOP YOUR APP - need [help](http://realpython.com)?

### Learn More

1. [Getting Started with Python on Heroku](https://devcenter.heroku.com/articles/python)
2. [PythonAnywhere - Help](https://www.pythonanywhere.com/help/)
1. [Flask Documentation](http://flask.pocoo.org/docs/)
2. [Flask Extensions](http://flask.pocoo.org/extensions/)
1. [Real Python](http://www.realpythonfortheweb.com) :)

