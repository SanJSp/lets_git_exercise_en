---
name: Aufgabe 1 Template
about: Das erste Issue, welches Aufgabe 1 abbildet.
title: Add title to the website
labels: good first issue
assignees: ''

---

#### Description
When visitors come to your website, they currently don't know what it's about, because nothing is being displayed yet. You should add a title so that visitors can understand what movie/book character the website is about.

#### Files
If you don't know how to create a title, take a look at this cheat sheet at Headers. You should use an H1 header. When using a Markdown symbol, you need to place a space behind it so that it will be rendered.
https://guides.github.com/pdfs/markdown-cheatsheet-online.pdf

#### Tasks
Perform the following steps:
- [ ] Navigate to your repository in Git Bash/your terminal. This should work with the command ``cd \<your GitHub name\>.github.io``.
- [ ] Because we want to practice the Github Flow you should create a new branch named ``feature1_new_title``. To do this you should enter the command ``git branch feature1_new_title``. Keep an eye on the spelling of the branch name, we can only test your work if the name is exactly as specified.
- [ ] Switch to the created branch with the command ``git checkout feature1_new_title``
- [ ] Now we want to open the repository in your file explorer(or any other program that can display folders). Just navigate to the folder where your repository was cloned to. As a help you can also try our shortcuts: To do this, enter the command ``explorer.exe .`` in the Git Bash on Windows. On Linux, enter the command ``nautilus .``. If you are a Mac user, you can use the command ``open .``
- [ ] Now you should add the title to the website. Open the index.md file with an editor. Delete everything that has already been added to the file and use Github flavoured Markdown (the one used in the cheat sheet) to add a title to the website. If you don't know how to do this, check out the cheat sheet.
- [ ] After you have added the title, you need to save the index.md file. Then add the index.md file to the staging area in the Git Bash. You do this with the command ``git add index.md``. Next, you need to commit the changes. Make a commit with the command ```git commit -m "Added Title"```. Then push the changes with the ``git push`` command. This may cause an error, which is why you might see an error message. Just copy the command from the error message and execute it.
- [ ] On GitHub, create a pull request to merge your feature branch into the master branch. You do this by switching to the Pull Requests Tab and then clicking the button "Compare & Pull Request". Choose a title to explain in a few words what happened in this pull request. In the body of the pull request, you describe the problem you solved. What was the problem? How did you solve it? Which files are affected?
- [ ] Now tests written by the teaching team will check your changes. If all tests (2 exist) have been passed, you can merge your changes into the Master Branch. If the tests fail, look into the comments of the pull request to find out what the problem was. Fix the bugs so that the tests pass. A good idea is to repeat the steps of the issue and see if everything is written correctly. You can also take a look at the Index.md file on Github (on your branch) and check the correct formatting. If you have tried it for 15 minutes without success, you can seek help in the [course forum](https://open.hpi.de/courses/git2020/question/16170091-c032-4fdf-9d79-0b774adf0c77).
- [ ] Enter the passphrase commented in the Pull Request by the bot in die openHPI quiz. 
- [ ] Delete your Feature Branch after merging the pull request. This needs to be done online on Github and in your local repository. Here on github you can delete the branch at the bottom of the Pull Request you created. To  delete the branch on your own machine switch to the master branch in your bash/terminal and run the command `git branch -d feature1_new_title`. Additionally you must update your local repository with the command ``git pull``.
- [ ] Close this issue.
- [ ] Check your website and see if anything has changed. You may have to update the page a few times.

If you have any questions, you can take a look at the course forum.
