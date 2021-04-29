## Deployment



Dash apps are web applications that use Flask as the web framework. One of the simplest ways to deploy an application is with **Heroku**.



#### Initialize Heroku, add files to Git, and deploy

```
$ heroku create lnclass 
$ git add . 
$ git commit -m 'Comment'
$ git push heroku master # deploy code to heroku
$ heroku ps:scale web=1  # run the app with a 1 heroku "dyno"

```

Source: [stackoverflow](https://stackoverflow.com/questions/47949173/deploy-a-python-app-to-heroku-using-conda-environments-instead-of-virtualenv)
