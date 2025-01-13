# Weekly Assignment 1: Learning The Basics of GitHub 

## :octocat: Git and GitHub

Git is a **distributed Version Control System (VCS)**, which means it is a useful tool for easily tracking changes to your code, collaborating, and sharing. With Git you can track the changes you make to your project so you always have a record of what you’ve worked on and can easily revert back to an older version if need be. It also makes working with others easier—groups of people can work together on the same project and merge their changes into one final source!

GitHub is a way to use the same power of Git all online with an easy-to-use interface. It’s used across the software world and beyond to collaborate and maintain the history of projects.

GitHub is home to some of the most advanced technologies in the world. Whether you're visualizing data or building a new game, there's a whole community and set of tools on GitHub that can get you to the next step. This course starts with the basics of GitHub, but we'll dig into the rest later.

## :octocat: Understanding the GitHub flow 

The GitHub flow is a lightweight workflow that allows you to experiment and collaborate on your projects easily, without the risk of losing your previous work.

### Repositories

A repository is where your project work happens--think of it as your project folder. It contains all of your project’s files and revision history.  You can work within a repository alone or invite others to collaborate with you on those files.

Repositories also contain **README**s. You can add a README file to your repository to tell other people why your project is useful, what they can do with your project, and how they can use it. We are using this README to communicate how to learn Git and GitHub with you. 😄 
To learn more about repositories read ["Creating, Cloning, and Archiving Repositories](https://docs.github.com/en/github/creating-cloning-and-archiving-repositories/about-repositories) and ["About README's"](https://docs.github.com/en/github/creating-cloning-and-archiving-repositories/about-readmes). 

### Cloning 

When a repository is created with GitHub, it’s stored remotely in the ☁️. You can clone a repository to create a local copy on your computer and then use Git to sync the two. This makes it easier to fix issues, add or remove files, and push larger commits. You can also use the editing tool of your choice as opposed to the GitHub UI. Cloning a repository also pulls down all the repository data that GitHub has at that point in time, including all versions of every file and folder for the project! This can be helpful if you experiment with your project and then realize you liked a previous version more. 
To learn more about cloning, read ["Cloning a Repository"](https://docs.github.com/en/github/creating-cloning-and-archiving-repositories/cloning-a-repository). 

### Committing and pushing
**Committing** and **pushing** are how you can add the changes you made on your local machine to the remote repository in GitHub. That way your instructor and/or teammates can see your latest work when you’re ready to share it. You can make a commit when you have made changes to your project that you want to “checkpoint.” You can also add a helpful **commit message** to remind yourself or your teammates what work you did (e.g. “Added a README with information about our project”).

Once you have a commit or multiple commits that you’re ready to add to your repository, you can use the push command to add those changes to your remote repository. Committing and pushing may feel new at first, but we promise you’ll get used to it 🙂

Now that you have some basic understanding of Git and GitHub, before getting to the next part, please use the following link to fill out a form on your information such as you student ID and GitHub username and email ["Information form"](https://forms.office.com/Pages/ResponsePage.aspx?id=cZYxzedSaEqvqfz4-J8J6gTd9jPfD65CmAXl7XdQApRUQ09BVzVGSDhKTEtTRk9YTEU4VUFHU09VRS4u
).
## 📝 Deliverables

**Friendly Reminder: Please fill up [this form](https://forms.office.com/Pages/ResponsePage.aspx?id=cZYxzedSaEqvqfz4-J8J6gTd9jPfD65CmAXl7XdQApRUOUszSDk3WjhDUlk1N1AyWllGWVZUVjdaVi4u) so that we know which student ID corresponds to your GitHub username!**

1. **Clone the repository:**
   - Set up SSH keys to avoid entering your username and password repeatedly by following [this guide](https://github.com/McGill-ECSE250-2025W/Weekly-Assignment1-Template/blob/main/docs/ssh-key-guide.md).
   - Follow the instructions in [this guide](https://docs.github.com/en/repositories/creating-and-managing-repositories/cloning-a-repository) to clone this repository. If you're new to Git:
     - Open your terminal or Git Bash application. If you're using Windows, you can install [Git for Windows](https://git-scm.com/) to get Git Bash.
     - Copy the repository URL (you'll find it on the repository page under the green "Code" button).
     - Run the command: 
       ```bash
       git clone <repository-url>
       ```
       Replace `<repository-url>` with the link you copied. Press Enter.
     - A folder named `tutorial01-*` (where `*` is your GitHub username) will appear in your current directory.

2. **Complete the program:**
   - Navigate to the `src` folder inside the cloned repository. You will find a file named `HelloWorldClass.java`.
   - Edit this file to complete the program so that it outputs `Hello World!` to the console. Use any text editor or IDE (such as VS Code or IntelliJ IDEA) to make the changes.

3. **Open the terminal and navigate to the repository folder:**
   - If your terminal isn't already open, open it now.
   - Use the `cd` command to move into the `tutorial01-*` folder. For example:
     ```bash
     cd path/to/tutorial01-username
     ```
     Replace `path/to/tutorial01-username` with the path to the folder on your computer. If you're unsure of the exact path, you can drag the folder into the terminal to paste it.

4. **Add, commit, and push your changes:**
   - Run the following commands one by one in your terminal:
     ```bash
     git add src/HelloWorldClass.java
     ```
     This stages your changes, preparing them for the next commit.

     ```bash
     git commit -m "This is my first Java code!"
     ```
     This saves your changes in the local Git repository with a descriptive message.

     ```bash
     git push
     ```
     This uploads your changes to the remote repository on GitHub.

5. **Verify your changes:**
   - Go to the GitHub repository page in your browser.
   - Check if your changes appear in the `src/HelloWorldClass.java` file under your repository.


## 📚  Additional Resources
* [A short video explaining what GitHub is](https://www.youtube.com/watch?v=w3jLJU7DT5E&feature=youtu.be) 
* [Git and GitHub learning resources](https://docs.github.com/en/github/getting-started-with-github/git-and-github-learning-resources) 
* [Understanding the GitHub flow](https://guides.github.com/introduction/flow/)
* [Interactive Git training materials](https://githubtraining.github.io/training-manual/#/01_getting_ready_for_class)
* [GitHub's Learning Lab](https://github.com/apps/github-learning-lab)
* [Education community forum](https://education.github.community/)
* [GitHub community forum](https://github.community/)

## Sources
* This README is modified from the [original GitHub starter course](https://github.com/classroom-resources/github-starter-course)

