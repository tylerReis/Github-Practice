# Github Practice

## Assignment

## Task

Use Github to create a new Github repo and sync the local git repo you created in part one twith this remote repo.

## Instructions

### Part 1: Create a remote Github repo

1. Sign into Github or create an account if you haven't done so already

2. Check the + icon to the left of your profile on the main page

3. Choose 'new repository'

4. Select yourself as the owner and give the repo the name 'hello-world'

5. Make it public. Ignore the other options.

6. Click 'Create Repository'

### Part 2: Link your local Git repo to your Github repo

1. In the page you opened copy the repo url in the Quick Setup section. For me this looks like `https://github.com/AloofBuddha/hello-world.git`

2. Use `git remote ...` to associate the url with your local git repo

3. use `git push ...` to push the branch `main` to your new remote Github repo (`origin`)

4. Make a new commit and push that as well.

5. Confirm the changes are reflected on the Github page representing your repo.

### Part 3: Pull Request

1. Create a new feature branch `dev` on your local repo and make some changes and commit them

2. Push this branch to `origin`

3. Go to the associated Github page and click the alert to intitiate a Pull Request to pull the changes from `dev` into `main`

4. Now that you have merged the pull request, the `main` branch on the origin (Github) has changes the `main` branch on your local git repo (on your computer) does not. Checkout the main branch and run `git pull` to get the most recent changes on `main` from Githb.

### Part 4: Bonus

- add a `README.md` file locally and push it to remote. Github will display this file below the contents of the repo like a 'home page' explaining what the repo is for.
THIS IS A NEW CHANGE MADE ON MAIN BRANCH

THESE ARE ALL DEV CHANGES MADE ON DEV BRANCH

THESE ARE ALL DEV CHANGES MADE ON DEV2 BRANCH
DEV2 BRANCH CHANGE
