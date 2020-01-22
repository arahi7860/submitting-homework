# ![](https://ga-dash.s3.amazonaws.com/production/assets/logo-9f88ae6c9c3871690e33280fcf557f33.png)  SOFTWARE ENGINEERING IMMERSIVE

# Homework Submission Guidelines

1. Click on the fork button in the top right corner
    ![GitHub fork button](https://github-images.s3.amazonaws.com/help/bootcamp/Bootcamp-Fork.png)
    1. This will take a second (but will give you a nice loading screen)
    2. Once the repo is forked, notice that you have a new repo under your account, forked from sei-nyc-mandalorians/github-fork
2. Click the **clone or download** button and copy the clone URL for **your repo**
    ![GitHub clone or download button](https://help.github.com/assets/images/help/repository/clone-repo-clone-url-button.png)
3. Run the command: `git clone URL` -- a new copy of the repo will be created in your current working directory.
4. `cd` into the cloned repository and open the in your text editor `code .`
5. Repeat until finished
    1. Plan
    2. Write
    3. Test
    4. `add`
    5. `commit`
    6. `push`
6. Confirm the remote is up to date by either [setting an upstream](https://git-scm.com/book/en/v2/Git-Branching-Remote-Branches#_tracking_branches) and using `git status`, or by checking on GitHub that the remote and local histories are the same.

7. You can always confirm you forked correctly if you run `git remote -v`. You should be able to see the following:
```
origin	https://git.generalassemb.ly/your-username/name-of-the-repo.git (fetch)
origin	https://git.generalassemb.ly/your-username/name-of-the-repo.git (push)
```
### If you didn't fork correctly, follow these steps.

 1. Fork the repo on Github Enterprise.
 2. Click the clone or download button and copy the clone URL for your repo.
 3. Set the url of your remote from the command line with:
         `git remote set-url origin URL`
         
 4. Add, commit and push your changes.
    
For more information, click [here](https://help.github.com/en/articles/changing-a-remotes-url)

## Making the PR

Now that you have pushed new changes to your forked repo, you can create a pull request to the original repo to ask that repo's owners to bring the new commits published to your fork, into their repo:

1. Click the "New pull request" button in the repository ![pr](https://cloud.githubusercontent.com/assets/40461/8229344/d344aa8e-15ad-11e5-8578-08893bcee335.jpg)
2. On the compare page you select the repo/branch to and from which you're making the pull request
3. Review your proposed change
4. Click **create pull request**
5. Enter a title and description of the changes proposed for your pull request
    1. For the purposes of this class we will make one big pull request with an entire assignment and the comment will be used to report how the assignment went rather than the contents of the pull request
    2. In the description, include
        1. a level of **confidence** between 0 and 5 (required)
        2. a degree of **completion** between 0 and 3 (required)
        3. a **comment** noting any questions, challenges or lines where specific feedback is requested (if completion if below 3, comment is required)
6. Click 'Create pull request'

> Check that the original repo has a new pull request from you

Nice work! Take a moment to think about this flow because we'll be using it throughout the course!

Note: A pull request creates an association between the two branches to the commits at that point in time. That means that if you push more changes to GitHub before the pull request is merged or closed, those changes will also be included in the PR.

GitHub provides a lot of features for communicating around pull requests. The most fundamental is commenting. GitHub provides not only the mechanism to share code but also the forum to discuss that code. 

Being clear and concise in discussing code in text (on GitHub but also more generally in text) is an invaluable skill. It takes practice and is especially frustrating while developing a new technical vocabulary but effort here pays dividends.

The more clearly and concisely you can describe a problem, the more effectively and happily other developers will help you.

## Resources

- [GitHub Guides: Forking](https://guides.github.com/activities/forking/)
- [GitHub Bootcamp: Fork a Repo](https://help.github.com/articles/fork-a-repo/)
- [GitHub: About Pull Requests](https://help.github.com/articles/about-pull-requests/)
