# [Flask Dashboard Material](https://appseed.us/product/material-dashboard/flask/)

Open-source **Flask/Jinja Template** generated by `AppSeed` op top of **[Material Dashboard](https://appseed.us/product/material-dashboard/flask/)**, a modern `Bootstrap 5` dashboard design. The project is a super simple Flask project WITHOUT database, ORM, or any other hard dependency. The project can be used as a codebase for future project or to migrate the Jinja files and assets to a legacy Python-based project that uses Jinja as template engine (Flask, Bottle, Django).

- 👉 Free [support](https://appseed.us/support/) via Email & `Discord` 
- 🚀 [Custom Development Services](https://appseed.us/custom-development/) for `accelerated growth`
- ✅ [Deploy on AWS, DO, and Azure](https://deploypro.dev/) via `DeployPRO` service (read the [DOCS](https://www.docs.deploypro.dev/))

<br />

### `PROMO` [Discounts for Developers](https://appseed.us/discounts/) Up to `30%OFF`

> The **discount is applicable to all products and licenses** (no stock limits) 

[![Discounts for Developers and Designers - AppSeed](https://user-images.githubusercontent.com/51070104/229268648-6ded378f-33aa-4909-a090-31fca49caa49.png)](https://appseed.us/discounts/)

<br />

> Built with [App Generator](https://appseed.us/generator/), timestamp `2023-09-29 15:30`

- `Up-to-date dependencies`
- Render Engine: Flask / [Jinja2](https://jinja.palletsprojects.com/)

<br />

![Material Dashboard - Full-Stack Starter generated by AppSeed.](https://user-images.githubusercontent.com/51070104/169301658-6cf27993-c451-4cd4-9ffa-2968b8981167.png)

<br />



## ✨ How to use it

> Download the code 

```bash
$ # Get the code
$ git clone https://github.com/appseed-projects/8a2e5e9a-71ed-44b2-a223-103988be3196.git
$ cd 8a2e5e9a-71ed-44b2-a223-103988be3196
```

<br />

### 👉 Set Up for `Unix`, `MacOS` 

> Install modules via `VENV`  

```bash
$ virtualenv env
$ source env/bin/activate
$ pip3 install -r requirements.txt
```

<br />

> Set Up Flask Environment

```bash
$ export FLASK_APP=run.py
$ export FLASK_ENV=development
```

<br />

> Start the app

```bash
$ flask run
```

At this point, the app runs at `http://127.0.0.1:5000/`. 

<br />

### 👉 Set Up for `Windows` 

> Install modules via `VENV` (windows) 

```
$ virtualenv env
$ .\env\Scripts\activate
$ pip3 install -r requirements.txt
```

<br />

> Set Up Flask Environment

```bash
$ # CMD 
$ set FLASK_APP=run.py
$ set FLASK_ENV=development
$
$ # Powershell
$ $env:FLASK_APP = ".\run.py"
$ $env:FLASK_ENV = "development"
```

<br />

> Start the app

```bash
$ flask run
```

At this point, the app runs at `http://127.0.0.1:5000/`. 

<br />

## ✨ Code-base structure

The project has a simple, intuitive structure presented bellow:

```bash
< PROJECT ROOT >
   |
   |-- apps/__init__.py
   |-- apps/
   |    |-- static/
   |    |    |-- <css, JS, images>         # CSS files, Javascripts files
   |    |
   |    |-- templates/
   |         |
   |         |-- includes/                 # Page chunks, components
   |         |    |
   |         |    |-- navigation.html      # Top bar
   |         |    |-- sidebar.html         # Left sidebar
   |         |    |-- scripts.html         # JS scripts common to all pages
   |         |    |-- footer.html          # The common footer
   |         |
   |         |-- layouts/                  # App Layouts (the master pages)
   |         |    |
   |         |    |-- base.html            # Used by common pages like index, UI
   |         |    |-- base-fullscreen.html # Used by auth pages (login, register)
   |         |
   |      index.html                       # The default page
   |      page-404.html                    # Error 404 page (page not found)
   |      page-500.html                    # Error 500 page (server error)
   |         *.html                        # All other pages provided by the UI Kit
   |
   |-- requirements.txt
   |
   |-- run.py
   |
   |-- ************************************************************************
```

<br />



## [Material Dashboard PRO Flask](https://appseed.us/product/material-dashboard2-pro/flask/)

> For more components, pages and priority on support, feel free to take a look at this amazing starter:

Material Dashboard is a premium Bootstrap 5 Design now available for download in Flask. Made of hundred of elements, designed blocks, and fully coded pages, Material Dashboard PRO is ready to help you create stunning websites and web apps.

- 👉 [Material Dashboard PRO Flask](https://appseed.us/product/material-dashboard2-pro/flask/) - Product Page
  - ✅ `Enhanced UI` - more pages and components
  - ✅ `Priority` on support

<br >

![Material Dashboard PRO (Bootstrap 5) - Full-Stack Starter generated by AppSeed.](https://user-images.githubusercontent.com/51070104/169301785-a3140a44-9e34-40b5-945d-6ca4928227b8.png)

<br />

---
[Flask Dashboard Material](https://appseed.us/product/material-dashboard/flask/) - Open-source starter generated by **[App Generator](https://appseed.us/generator/)**.
