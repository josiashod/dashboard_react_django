# React Soft Ui Dashboard `full-stack`

## ✨ How to use it

Being a full-stack product, the backend and the frontend should be compiled and started separately. 
Before starting to compile the product, make sure you have the following tools installed in the environment:

- [NodeJS](https://nodejs.org/en/) - version `14.x` or higher
- [GIT](https://git-scm.com/) - used to clone tjhe sources from Github
- [Python3](https://www.python.org/) - used in many tools

<br />

### 👉 Start the Frontend 

> **Step 1** - Once the project is downloaded, change the directory to `react-ui`. 

```bash
$ cd react-ui
```

<br >

> **Step 2** - Install dependencies via NPM or yarn

```bash
$ npm i
// OR
$ yarn
```

<br />

> **Step 3** - Start in development mode

```bash
$ npm run start 
// OR
$ yarn start
```

<br />

At this point, the app is available in the browser `localhost:3000` (the default address).


<br /> 

### 👉 Start the Backend Server 

> **Step 1** - Change the directory to `api-server-django`

```bash
$ cd api-server-django
```

<br >

> **Step 2** - Install dependencies using a `virtual environment`

```bash
$ # Virtualenv modules installation (Unix based systems)
$ virtualenv env
$ source env/bin/activate
$
$ # Virtualenv modules installation (Windows based systems)
$ # virtualenv env
$ # .\env\Scripts\activate
$
$ pip install -r requirements.txt
```

<br />

> **Step 3** - Setup the database 

```bash
$ python manage.py makemigrations
$ python manage.py migrate
```

<br />

> **Step 4** - Start the API server (development mode)

```bash
$ python manage.py runserver 5000
```

Use the API via `POSTMAN` or `Swagger Dashboard` at `localhost:5000`.

<br />

