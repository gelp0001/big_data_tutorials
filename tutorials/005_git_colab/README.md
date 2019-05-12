# Collaboration on GitHub

This is a very brief guide to collaboration on GitHub. In this guide, I assume there is a public repository already created and made available to us. Pretty much like this repository!

## Simple Approach

In this approach, we just use the GitHub web interface. Easy!

1. Go to the repository main page

2. Click on **Fork** button at up-right corner. It makes a copy of the current content of repository into your account.

3. Find the file you want to update. Click on the **Edit** button (the icon looks like a pen positioned between a rubbish bin icon and a display icon).

4. Make your changes. It is better to do small changes each time.

5. At the bottom of the page, provide some context about what changes you made (e.g., *some typos are fixed* or *Python version changed from 3.7 to 3.8*). Then click on the green button at the bottom (**propose file change**).

6. Repeat steps 3 to 5 as many times as necessary.

7. Go to **Pull Requests** tab and click on **New pull request** and create a new Pull Request. This means you are happy with the changes you made and proposing the repository owners/admins to incorporate your changes to their repository (usually *master* branch). Provide as many information as you can and complete the process.

8. The owners will review your proposed changes, alter it if required, and finally reject or accept it. Sometimes, they may comment on your proposal or ask you to make some other changes before they include it.

9. Done! Thank you for your collaboration!

## More Common Approach

I do not discuss [this approach](https://www.youtube.com/watch?v=MnUd31TvBoU) and wait for a collaborator to do it!

This section may be useful in a small team with multiple collaborators.

1. Clone a repository to your local machine

2. `git pull origin master` Will pull will merge the master branch from the remote server (origin) into our master branch
    
3. `git checkout -b my-branch-name` Will create a new branch.  This is done so that the master is preserved.
    
4. Make the required edits to code on you new branch

5. `git push origin my-branch-name` Will push the banch up to the remote repository
    NOTE: We should NOT merge to master on your local repo and push to remote - this is BAD because it overwrites the master branch!
    
6. In the repo click the "Compare and pull request" button
    Add a message and comment for audit purposes - you may regret it later if you don't!
    
7. Click the "Create pull request button"
    This says "I want to merge this branch into the master brance of this repository".
    
8. TBC...........
