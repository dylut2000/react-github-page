# Deploy react on github page

- create a react app using `create-react-app`

- install the github page:

```
npm i gh-pages -D
```

- add the following Key:Value to your **package.json**

```
"homepage": "https://user-name.github.io/project-name",
```

`(replace user-name with your Github username, and project-name with your project name)`

- add the following Key:Value to your **scripts** in your **package.json**

```
"predeploy": "npm run build",
"deploy": "gh-pages -d build",
```

- create a new repo on your github, and make sure that it a **public** repo

- push your project online (push the project in your laptop to your Github repo you created)

- and then run the follwing command in your terminal

```
npm run deploy
```

And we are done

[Check the Link](https://dylut2000.github.io/react-github-page/")

<br>

[😉 Twitter](https://twitter.com/dylut2000?lang=en)
