# open-source-demo
This is a repo created to facilitate the GSoC workshop conducted by The Programming Club, IIT Indore. It has been designed to explain the working of open source projects.
Participants will learn how to make an open source contribution from the scratch.
## Prerequisites
Git installed on your machine, along with any code editor of your choice. If you are using Windows, a shell such as Git Bash or WSL needs to be installed. 
## Get Started
- Fork the repo to your personal account by clicking on the fork button on the top right corner of this page.
- Open a terminal with Git installed in it.
- Clone the repository to your local machine.
```
git clone https://github.com/<your_github_id>/open-source-demo
```
- Change the directory of the terminal to the folder of this repository.
```
cd open-source-demo
```
- Create a new branch. You can name your branch as `<your_name>_submission`.
```
git branch <name_of_branch>
```
- Use/Checkout this branch.
```
git checkout <name_of_branch>
```
- Open the repository folder created in your code editor. If your using VS Code, you can type `code .` to open this folder directly from the terminal.
- Create a new file in the submission folder and name it as `<your_name>_<name_of_file_changed>.txt`.
- Type a brief explanation of the solution/corrections in that file and save it. 
- Stage the changes for the commit.
```
git add .
```
- Commit the changes to your forked repository.
```
git commit -m <commit_message>
```
- Push the changes from your local repository to the GitHub repository.
```
git push origin <name_of_branch>
```
- Create a pull request from the GitHub page of your forked repository. This will be a request to merge the branch you created in your forked repository to the main branch of this repository.
- Add suitable content in your pull request to make it stand out, for example, which issue has been addressed, list of all the tasks that were taken up in the pull request, etc.
- Await the approval by a maintainer.
