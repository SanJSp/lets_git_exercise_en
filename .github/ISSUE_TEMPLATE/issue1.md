---
name: Aufgabe 1 Template
about: Das erste Issue, welches Aufgabe 1 abbildet.
title: Add title to the website
labels: good first issue
assignees: ''

---

#### Description
When visitors come to your website, they currently don't know what it's, because nothing is being displayed yet. You should add a title so that visitors understand what movie/book character the website is about.

#### Files
If you don't know how to create a title, take a look at this cheatsheet at Headers. You should use an H1 header.
https://guides.github.com/pdfs/markdown-cheatsheet-online.pdf

#### Tasks
Perform the following steps:
- [ ] Navigate to your repository in Git Bash. This should work with the command ``cd \<your github name\>.github.io``.
- [ ] Create a new branch named ``feature1_new_title``. To do this you should enter the command ``git branch feature1_new_title``.
- [ ] Switch to the created branch with the command ``git checkout feature1_new_title``
- [ ] Now we want to open the repository in your file explorer(or any other program that can display folders). Just navigate to the folder where your repository was cloned to. As a help you can also try our shortcuts: To do this, enter the command ``explorer.exe .exe`` in the Git Bash on Windows. On Linux, enter the command ``nautilus./``. If you are a Mac user, you can use the command ``open .``
- [ ] Now you should add the title to the website. Open the index.md file with an editor. Delete everything that has already been added to the file and use Github flavoured Markdown to add a title to the website. If you don't know how to do this, check out the cheatsheet.
- After you have added the title, you need to save the index.md file. Then add the index.md file to the staging area in the Git Bash. You do this with the command ``git add index.md``. Next you need to commit the changes. Make a commit with the command ```git commit -m "Added Title"```. Then push the changes with the ``git push`` command. This may cause an error, which is why you might see an error message. Just copy the command from the error message and execute it.
- On Github, create a pull request to merge your feature branch into the master branch. Choose a title to eplain in a few words what happened in this pull request. In the body of the pull request you describe the problem you solved. What was the problem? How did you solve it? Which files are affected?
- [ ] Now tests written by the teaching team will check your changes. If all tests (2 exist) have been passed, you can merge your changes into the Master Branch. If the tests fail, look into the comments of the pull request to find out what the problem was. Fix the bugs so that the tests pass. A good idea is to repeat the steps of the issue and see if everything is written correctly. You can also take a look at the Index.md file on Github and check the correct formatting. If you have tried it for 15 minutes without success, you can have a look in the course forum.
- [ ] Delete your Feature Branch. Switch to the master branch in your git bash and run ``git pull`` to update your local repository.
- [ ] Close this issue.
- [ ] Check your website and see if anything has changed. You may have to update the page a few times.

If you have any questions, you can take a look at the course forum.
