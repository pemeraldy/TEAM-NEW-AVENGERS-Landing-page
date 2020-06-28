# TEAM-NEW-AVENGERS-Landing-page

* 90% Bootstrap
* Responsive sites with mobile-first approach
* Comments, so anyone can understand
* Good class naming conventions
* Complete replica of the design


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
the branch name should at least be meaningful,  **make sure you have one story per branch (one(1) story ===  one(1) branch)** 

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


Write good commit messages, this is very important, so people reviewing can know what your fix, feature e.t.c. is doing
Your PR should carry the story / task URL (instruction from above).
if you are going to make changes to an existing code, state why you are doing so in the commit messages

it is not just about the code, user workflow matters too!!

### Happy hacking!!!!
