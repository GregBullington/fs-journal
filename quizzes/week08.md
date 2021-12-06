# Deploying Applications

**1.** What is the package.json file used for?
<!-- enter you answer in the space below -->
```
Holds the projects metadata and records its dependencies 
``` 
**2.** At what level of your project do you need package.json when deploying your application? Why?
<!-- enter you answer in the space below -->
```
in the root of the project and its needed to give information to npm allowing it to identify and handle the projects dependencies.
```
**3.** What command will ensure that your Vue code is compiled properly for deployment?
<!-- enter you answer in the space below -->
```
production
```
**4.** _______ are used to provide your application with specific data based on it's environment. For example: connections strings, private keys or port. Fill in the blank.
<!-- enter you answer in the space below -->
```
environment variables
```
**5.** What are the two ways to view the logs from your Heroku app.
<!-- enter you answer in the space below -->
```
heroku dashboard on the web or the CLI with logs
```
**6.** How do you update an app already deployed on Heroku?
<!-- enter you answer in the space below -->
```
1. Clone the repository from GitHub to your local device:
git clone <YOUR HTTPS URL FROM GITHUB>
2. Make your changes, and commit them to GitHub:
git add .
git commit -m "<YOUR COMMIT MESSAGE>"
git push origin <YOUR BRANCH NAME>
3. Login to your Heroku account:
heroku login
Follow the directions on the screen to login to your account through the browser, then return to the terminal.
4. Set remote for your project:
heroku git:remote -a <YOUR PROJECT NAME>
5. Push to Heroku master to deploy updates:
git push heroku master
```
**7.** Why is branching important to version control?
<!-- enter you answer in the space below -->
```
allows for independent changed without affecting main branch 
```
**8.** When should code review happen?
<!-- enter you answer in the space below -->
```
before code merges to main branch but after automated checks
```
**9.** What is the term used to define combining two branches?
<!-- enter you answer in the space below -->
```
merging
```