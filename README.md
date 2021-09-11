## jekyll-workshop-FA-2021

By the end of this workshop, you will have your own Portoflio website.

![Product Name Screen Shot][sample]

### Prerequisites
* Have a GitHub account
* Install VSCode
* Git

### Installation and setup
1. Fork the repo [https://github.com/sharu725/online-cv](https://github.com/sharu725/online-cv)
      * NOTE: This theme was one of many others available for free on the jekyll themes website [https://jekyllthemes.io/](https://jekyllthemes.io/)

2. Go to Settings -> Options tab on github, and rename your repository name to `user_name.github.io`

3. Go to Settings -> Pages tab and change the Source branch to master. Click Save.
    * TIP: During development, keep checking and reloading this tab to see if changes you make are reflecting on the website.
It will say `Your site is published at https://user_name.github.io/` when it is done.

4. Clone the forked repo in VSCode 
```git clone "https://github.com/your_username_/Project-Name.git"```

### Making the Portofolio yours!
1. Replace the text in the `data.yml` file with your data.
    * TIP: Commit and push your code once after every section you update. **Yaml file formatting can be tricky to deal with.**
    * If adding a link, wrap it in double quotes like this `"https://www.google.com/"`
3. switch out the `profile.png` with your own 100 x 100 profile picture.
    * TIP: Use online image resizers to get your iamge to the 100 x 100 dimension
5. Go to `config.yml` and change the title to `Name - Portofolio`

### Git commands to use
* `git add .` - adds all the files changed to the Staged Changes
* `git status` - allows you to check the if the files have been added or not
* `git commit -m "commit message"` - commits the changes 
* `git push` - pushes all the commits to GitHub for publishing the website

[sample]: images/sample.png











