<img src="https://cdn.abranhe.com/projects/jenkins/jenkins.png" height="200">

# Jenkins on Heroku 

[![Deploy](https://www.herokucdn.com/deploy/button.svg)](https://heroku.com/deploy?template=https://github.com/abranhe/jenkins/tree/master)

After you deploy your application you will get a login page and it will ask you for a password.

![](https://cdn.abranhe.com/projects/jenkins/login.png)

You will need to install the Heroku cli ([cli.heroku.com](https://cli.heroku.com)) to get the logs of your application.
After you installed the Heroku cli you can run:

```
$ heroku logs --app <yourappname>
```

The password can be found on the logs. If you cant see it, then restart the dynos.

![](https://cdn.abranhe.com/projects/jenkins/log.png)

In this case the password would be:

```
82nljalk29jk8sj83mn76sh52h27
```

## License

MIT © [Carlos Abraham](https://go.abranhe.com/github)
