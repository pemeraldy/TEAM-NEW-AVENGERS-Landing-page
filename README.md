# TEAM-NEW-AVENGERS-Landing-page

* 90% Bootstrap
* Responsive sites with mobile-first approach
* Comments, so anyone can understand
* Good class naming conventions
* Complete replica of the design

# Folder Structures - guidlines

* all html files goes into the **landing-pages** folder
* all CSS files goes into the <pre><code> CSS/custom-css/</code></pre> folder
* all js files goes into the <pre><code> js/custom-js/</code></pre> folder
* Please leave the bootstrap files as is, avoid modifying to them.


This process here should be able to guide you on how to contribute effectively to this project, follow the steps below. You should not be new to the git workflow process however if you still are, the guide should still be able to help you through the process.

### Develop is the default branch.


* Fork the repository to generate a copy of your own.

* Clone the repository.

   ```
    git clone https://github.com/pemeraldy/TEAM-NEW-AVENGERS-Landing-page.git
   ```
    
* Make the original HNGi/TEAM-NEW-AVENGERS-Landing-page repo the remote upstream (at upstream)
    ```
    git remote add upstream https://github.com/hngi/TEAM-NEW-AVENGERS-Landing-page.git
    ```
* Create a branch FROM develop, ALWAYS CREATE YOUR BRANCH FROM DEVELOP,

    ```
    git checkout -b (name-of-branch)
    ```

* After changes have been made, **RUN**:
    ```
    git pull upstream develop
    ```
Consistently pull from the develop branch to avoid not getting your pull request merged and to avoid conflicts.
This way you can resolve conflicts from your local computer even before pushing always check what branch you are on when making changes
 
* Make your changes, add them and make your commits

   ``` 
   git commit -m "your message"
   ```
Write good commit messages, this is very important, so people reviewing can know what your fix, feature e.t.c. is doing

* Push your codes to the new branch on your forked remote upstream repository

    ```
    git push origin (name-of-branch)
   ```

Make your Pull request from that branch of your repo to the develop branch of this (the HNG) repo and wait for it to be merged.

