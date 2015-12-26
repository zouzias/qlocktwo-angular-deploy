Deploy of [qlocktwo-angular](https://github.com/zouzias/qlocktwo-angular.git) to heroku.

### Instructions

First, install [Heroku Toolbelt](https://toolbelt.heroku.com)

Login in heroku
```
heroku login
```

Go to [qlocktwo-angular](https://github.com/zouzias/qlocktwo-angular.git) and type `grunt build`. Then copy the dist directory on the root directory of this project.

To publish the relase to heroku, type:

```
git push heroku master
```

### References

[Deploying Yeoman apps to Heroku](https://gist.github.com/zouzias/da124031c5d68d49f0d8)
