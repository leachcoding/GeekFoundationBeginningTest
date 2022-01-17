# GeekFoundationBeginningTest

Hello everyone, welcome to your first assignment! This assignment is simply to get you set up and successfully working within git, github, and a terminal. Down at the bottom of this list, you will find a section labeled 'NAMES HERE'. The assignment is to simply place your name there. In order to do this, we will follow a series of instructions listed so:

1. Please clone this repository. How you ask? There should be on the linked page https://github.com/leachcoding/GeekFoundationBeginningTest a green button labeled CODE, with several options available to its dropdown. HTTPS is the preferred option for this assignment, simply for ease of use, but all can be technically used to achieve the same result. Copy this link.

2. You should have downloaded VSCode by this point as well. If not, now is the time to do so here https://code.visualstudio.com/ . Once downloaded, please start. You should see a default welcome 'get started screen' with a tool bar at the top. Please select terminal on this toolbar, and click 'new terminal'. A terminal should come up at the bottom, with a line such as PS C:\Users\Jay or like https://git-scm.com/book/en/v2/Git-Basics-Getting-a-Git-Repository . This is where we follow the commands listed in that same chapter. $ git clone repo-link-here . The repo link is the link we copied above from the green code button.

3. You should see a success message akin to 

Cloning into 'GeekFoundationBeginningTest'...
remote: Enumerating objects: 3, done.
remote: Counting objects: 100% (3/3), done.
remote: Total 3 (delta 0), reused 0 (delta 0), pack-reused 0
Receiving objects: 100% (3/3), done.

If so, you are cloned. At this point, please cd into that same repository 'GeekFoundationBeginningTest'

cd GeekFoundationBeginningTest

and then, using the VSCode command, type the following command:

code .

This command opens up a new instance of vscode with the project you have cd'd into as the root. You will see a GEEKFOUNDATIONBEGINNINGTEST folder path in the upper left with this new instance with the README.md file listed as well. If so, success.

4. Now that we have our code downloaded locally, we must branch off on our own branch in order to work on a feature. Please in the new instance, open a new terminal and type in the following command:

git branch --show-current

This command shows the current branch you are currently on. This is useful if you are ever unsure. You should currently be on 'main', which is the default branch often used. However, once verified, we want to switch to our own. Please do so with:

git branch -checkout 'jay-leach'

with your own first-last name in the ''. Once this is done, please verify you are on your own branch with the prior --show-current command. More branching information can be found here: https://git-scm.com/book/en/v2/Git-Branching-Branches-in-a-Nutshell . 

5. Once this is done, you are now able to edit the readme. Please click on it, and on the NAMES HERE section, please enter your name.

6. Once finished, we are ready to push our code back up to github and create a pull request. The following commands are going to be some of the most used of your git career.

git add .
git commit -m "Useful message of feature here"
git push -u origin jay-leach

where the useful message should be descriptive, concise, and relevant to what you have done for a feature and where 'branch-name' is your branch name. There may be struggles here, and errors. That is okay and expected. Rather than give the solution, for those having issues, I wanted to work in discord to help answer if questions were had, and I wanted to work on the exercise of 'googling' another amazing skill that will help your development game. Stack Overflow and other associated forums are a main staple in my developer tabs I keep pretty nearly constantly open. This exercise will expound upon that. 

7. Once finished, we will show more about pull requests, code reviews, etc during Wednesdays conclusion of this exercise. 




# NAMES HERE
