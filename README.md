# ExploringData
 Web App to explore data

### Instructions for setting up locally


### Instructions for setting up add on Heroku
Produces a Streamlit Web App hosted on Heroku.

https://exploringdata.herokuapp.com/

Set up 4 different files:

- Procfile
- setup.sh
- requirements.txt
- app.py

Simple web app using Streamlit to explore your data

```shell
heroku login
```

```shell
heroku create
```

```shell
git remote rm heroku
```

```shell
git remote add heroku https://git.heroku.com/CustomName.git
```

```shell
git add .
```

```shell
git commit -m "Commit Comment"
```

Push to your git repository
```shell
git push heroku master
```
