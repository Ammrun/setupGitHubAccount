# Set Up a GitHub Account

A video demonstration of how to set up a GitHub account is available at: https://www.youtube.com/watch?v=w5-4WeyOtN4

A video demonstration of setting the configuration files in Git after you set up a GitHub account is available at: https://youtu.be/Ilbiqu79JI0

## GitHub

* If you don't already have a GitHub account, you'll need to set one up.
* Go to https://www.github.com/
* Sign up for an account.
  * Make sure you note what username, email, and password you use to create your account somewhere. You'll need them later.
  
## Configure username and email for GitHub to work with Git

* In a terminal run the code `git config --global user.email email@example.com`
  * Make sure the email you use is the email address you used when you created your GitHub account (Github > Profile > Settings > Email > Add Email)
* Then check to see if it worked by running `git config --global user.email`
  * You should see your email after you execute the command.
* Also set the user name by running `git config --global user.name GitHubUserName`
  * Your GitHub user name can also be seen at the top of the GitHub Settings page.
  * (Instructions came from answer on StackOverflow: https://stackoverflow.com/questions/56970149/how-do-i-change-the-user-in-vscode-and-link-my-github-account)
* Then check to see if it worked by running `git config --global user.name`
  * You should see your username after you execute the command.
* Post a screenshot in the discussion board or come to office hours if you run into problems.

## Turn in Assignment

* Turn in a screenshot of your terminal or command prompt window showing your Git config user email and username
