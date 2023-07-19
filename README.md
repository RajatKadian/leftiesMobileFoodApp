# LeftiesFoodApp

## Figma Link
https://www.figma.com/file/pv5wiiEsC0jYM6q2fQevBO/Mobile-App-Food-Thing?node-id=58%3A1099&t=rPSklHOc2he20zIn-1

# Git Commands

## I. Updating your code to reflect everybody else's work
We do this often to ensure that our changes work in peace and harmony.
Otherwise... chaos.

1. Go to main branch `git checkout main` -- This is where everybody's work is saved
2. Pull the changes `git pull` -- This downloads everybody's work to your machine
3. Go back to your branch `git checkout <YOUR BRANCH NAME>` example: `git branch Raiyan`
4. Time to combine! `git merge main`  -- this combines the 'main' branch of the group in step 1 to your branch in step 3

## II. Apply your change to your branch
1. `git add .` - This will stage all your changes
2. Check that files with the changes are in green `git status`
3. Commit your code `git commit -m "Apply recycler view"` -- We use the message to identify what changed in this group of changes.
5. `git push`

## III. Making a pull request
(Requesting the team to add your changes to the main branch)
1. After you push your changes, you will find this popup in the github link. Click **'Compare and pull request'** 
![image](https://user-images.githubusercontent.com/35404436/225159941-010c5b80-7bda-48ee-a025-fa7aeedd9673.png)
2. It will being you to this page. 
![image](https://user-images.githubusercontent.com/35404436/225160835-74597a82-e16d-4ccc-9369-1b1535e0d1d5.png)
- Make sure that it says `base: main` and `compare: <your-branch-name>`.
- Hopefully on the right hand it says **'Able to merg'**. (If it says otherwise, merge main branch to your branch. See step  above _I. Updating your code..._
3. Click button **'Create pull request'** at lower right corner
4. You will see this page. Select the button **'Merge pull request'**
![image](https://user-images.githubusercontent.com/35404436/225161255-4f654ecc-2efd-4eed-8acd-5fe1bf47f2dd.png)
5. Click **'Confirm'**
6.  Let the team know so they can update their code with your changes.

