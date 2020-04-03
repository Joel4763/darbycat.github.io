<b>If you ever need any help, feel free to add an issue.</b>
# How to write pages for DarbyCAT.github.io
## Using GitHub—Part One
### Step One: Make a GitHub account
Go to [https://github.com](github.com) and sign up for an account.
### Step Two: Installing Git
Go [https://git-scm.com/book/en/v2/Getting-Started-Installing-Git](here) and follow the instructions.

If you want a GUI (which is strongly reccomended), we reccomend (and will use in the turorial) [https://desktop.github.com](GitHub desktop) for Mac and Windows, but there are more [https://git-scm.com/downloads/guis](here). If you already know how to use GitHub, you don't have to do this, and if you don't have Mac or Windows, we can help you.
### Step Three: Clone DarbyCAT
Scroll up and click on "Clone or Download". Then, click Open in Desktop and select where to put you're clone.
### Step Four: Edit The Files
Now, you read the other sections.
## Jekyll
Jekyll is a static site genorator, and it's used for this website. You don't really have to install it, but if you want to:
[http://jekyllrb.com/](link.)
## Adding an author
Before you start writing, you should create an author to use for your posts. Go to `_data/authors.yml` to add yourself.
You'll add your information in a second, but to explain what everything means:
name is your first name, with proper capitalization, like `George`<br>
alias is your username, like `george42`<br>
If those were the values, it would look like this:
<pre>
    george42:
            name: George
            alias: george42
</pre>
Notice that the top line and the alias are the same. That's important. Also, make sure to indent.  
<h2>Making your profile</h2>
Next, you need to create a profile page. Create a file in the `profile` folder called `george42.html` (with george42 replaced by your alias.) Inside, add some metadata. If you were George, you would write:
<pre>
---
layout: profile
permalink: /profile/george42
profile: george42
---
</pre>
You would replace any `george42` with your alias. Below that write profile information, such as `42 is the answer to life, the universe, and 21*2`. Now, you can start writing!  
<h2>Writing</h2>
To create a post, go to the folder `_posts` and make a file called `YYYY-MM-DD-title-like-this.markdown` (so on March 5, 2017, to create "I Like Pizza" it would be `2017-03-05-i-like-pizza.markdown`.) The metadata will look like this:
<pre>
---
layout: post
title:  "Title Like This"
date:   YYYY-MM-DD HH:MM:SS -0500
categories: categories seperated by spaces
author: youralias
---
</pre>
or for the example:
<pre>
---
layout: post
title: "I Like Pizza"
date: 2017-03-05 19:06:51 -0500
categories: pizza food greatness
author: george42
---
</pre>
Below that, get writing!
## Using GitHub—Part 2
### Step Five: Commiting your changes
Go back to GitHub Desktop and go to the "# Uncomitted Changes" tab. Now click the new branch button. <img src="data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHZpZXdCb3g9IjAgMCAxMCAxNiIgd2lkdGg9IjEwIiBoZWlnaHQ9IjE2Ij48cGF0aCBmaWxsLXJ1bGU9ImV2ZW5vZGQiIGQ9Ik0xMCA1YzAtMS4xMS0uODktMi0yLTJhMS45OTMgMS45OTMgMCAwMC0xIDMuNzJ2LjNjLS4wMi41Mi0uMjMuOTgtLjYzIDEuMzgtLjQuNC0uODYuNjEtMS4zOC42My0uODMuMDItMS40OC4xNi0yIC40NVY0LjcyYTEuOTkzIDEuOTkzIDAgMDAtMS0zLjcyQy44OCAxIDAgMS44OSAwIDNhMiAyIDAgMDAxIDEuNzJ2Ni41NmMtLjU5LjM1LTEgLjk5LTEgMS43MiAwIDEuMTEuODkgMiAyIDIgMS4xMSAwIDItLjg5IDItMiAwLS41My0uMi0xLS41My0xLjM2LjA5LS4wNi40OC0uNDEuNTktLjQ3LjI1LS4xMS41Ni0uMTcuOTQtLjE3IDEuMDUtLjA1IDEuOTUtLjQ1IDIuNzUtMS4yNVM4Ljk1IDcuNzcgOSA2LjczaC0uMDJDOS41OSA2LjM3IDEwIDUuNzMgMTAgNXpNMiAxLjhjLjY2IDAgMS4yLjU1IDEuMiAxLjIgMCAuNjUtLjU1IDEuMi0xLjIgMS4yQzEuMzUgNC4yLjggMy42NS44IDNjMC0uNjUuNTUtMS4yIDEuMi0xLjJ6bTAgMTIuNDFjLS42NiAwLTEuMi0uNTUtMS4yLTEuMiAwLS42NS41NS0xLjIgMS4yLTEuMi42NSAwIDEuMi41NSAxLjIgMS4yIDAgLjY1LS41NSAxLjItMS4yIDEuMnptNi04Yy0uNjYgMC0xLjItLjU1LTEuMi0xLjIgMC0uNjUuNTUtMS4yIDEuMi0xLjIuNjUgMCAxLjIuNTUgMS4yIDEuMiAwIC42NS0uNTUgMS4yLTEuMiAxLjJ6Ij48L3BhdGg+PC9zdmc+" alt="Git Branch"> Give it a descriptive name, like `approval-post`, or something, that <b>relates to what you are adding.</b> A text box should pop up and you can make a descriptive summaray, like `Added a post saying we were approved`, and, if you want, an extanded description. Click "commit to (your-branch).
### Step Six: Making a pull request (when you are ready to publish changes)
Click "Pull Request" in the top right. Give it a nice title and description, and "click send pull request." If a big scary error message pops up, click Sync a little to the left. Then, when the president approves it, it will be added to the site.
