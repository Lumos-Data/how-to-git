# A Friendly Guide to Git and GitHub

Welcome! If you're looking for a simple, clear explanation of **Git** and **GitHub**—whether you're a seasoned coder, a project manager, or just someone interested in how we manage our files—you're in the right place.

This guide is designed for **our members** and anyone interested in understanding the essential tools of modern project collaboration.

---

## 1. What Exactly Are Git and GitHub?

People often use these two terms interchangeably, but they are actually two different things that work perfectly together.

### What is Git? (The Time Machine)

**Git** is a system that lives on your computer. Its entire purpose is **Version Control**.

Imagine you’re working on a document and constantly hitting "Save As Version 1," "Save As Version 2," etc. Git does this automatically, but much better.

* **A Perfect History:** Git tracks **every change** made to every file in your project. This means you can instantly go back to any previous version, making mistakes easy to fix and major crashes a non-issue.
* **Proof of Work:** It records exactly *who* made *what* change and *when*. This is the core of how teams keep track of their work.

### What is GitHub? (The Online Hub)

**GitHub** is a website (a cloud service) that acts as the central meeting place for all projects managed by Git. Think of it as **our club’s central digital archive.**

* **Project Hosting:** It's where we store the main, official copy of our project files (called a **Repository** or **Repo**).
* **Collaboration Tools:** GitHub provides the features we use to work together, like asking for feedback on changes and holding discussions before changes go live.
* **Networking:** It’s a huge platform for showing off your work and connecting with others who are building cool things.

### Why Do We Use Them?

| For Individual Projects | For Team Collaboration |
| :--- | :--- |
| **It's Safe:** You never have to worry about accidentally deleting a critical file. | **Work Together, Apart:** Multiple people can work on the same project files at the exact same time without interfering with each other. |
| **Experiment Freely:** You can create isolated spaces (**Branches**) to try out radical new ideas, knowing you won't break the main, working version. | **Review and Approve:** We use a process to review each other's work (called a Pull Request) to catch errors and maintain quality before a change is finalized. |

---

## 2. Key Terms to Know

You don't need to learn a whole new language, just a few core concepts will help you follow along with any technical discussion:

| Term | What It Is in Plain English |
| :--- | :--- |
| **Repository (Repo)** | The project folder. It holds all the files and the entire history of those files. |
| **Branch** | An alternate, temporary version of the project. We use a branch to do our work without messing up the main version (often called `main`). |
| **Commit** | A "save point" or snapshot of your changes. Every time you save your work in Git, you write a short message explaining what you did. |
| **Push** | The act of sending your saved changes (Commits) from your computer up to the central repository on GitHub. |
| **Pull** | The act of grabbing the newest changes that other people have pushed, bringing them down to your computer. |
| **Pull Request (PR)** | This is how you submit your completed work. It’s a formal request for someone to look at your Branch and merge it into the main project. |
| **Clone** | Downloading a copy of the online project (the Repo) onto your own computer so you can work on it. |

---

## 3. The Basic Workflow

How you use Git and GitHub depends on your role.

### Option A: Using the GitHub Website (Easy for Non-Tech Roles)

If your work is mainly in documentation (like this `README.md`) or simple file updates, you can often do everything right in your web browser.

1.  **Find the File:** Navigate to the file you want to change in the repository on GitHub.
2.  **Edit:** Click the **Edit** icon (it looks like a pencil).
3.  **Commit:** After making your changes, scroll to the bottom. Write a short, clear **Commit Message** (e.g., "Updated contact email in README") and click **Commit changes**.
    * *That's it!* Your change is immediately saved and part of the project's history.

### Option B: Using the Git Command Line (Standard for Developers)

For more in-depth work (like coding), developers use the command line on their computer.

1.  **Get the Project (Clone):** Download a copy of the repo to your machine.
    ```bash
    git clone [REPO_URL]
    ```
2.  **Start Your Work (Branch):** Create a new branch so your changes are isolated.
    ```bash
    git switch -c my-new-feature
    ```
3.  **Save Your Work (Commit):** Once you've made file edits, you take a "snapshot" and save it.
    ```bash
    git add . 
    # Stagging all changes for the commit
    git commit -m "My descriptive commit message"
    ```
4.  **Share Your Work (Push):** Upload your saved commits to GitHub.
    ```bash
    git push -u origin my-new-feature
    ```
5.  **Submit for Review (Pull Request):** Go to the GitHub website and create a **Pull Request** to get feedback and merge your work into `main`.

---

## Further Resources

Ready to learn more? Check out these excellent, human-friendly tutorials:

* **Git for Beginners:** This is a fantastic, simple guide with all the basic commands: [git - the simple guide](https://rogerdudler.github.io/git-guide/)
* **GitHub’s Official Tutorial:** The "Hello World" guide walks you through the website workflow: [Hello World - GitHub Docs](https://docs.github.com/get-started/quickstart/hello-world)
* **Video Walkthrough:** This video offers a good visual introduction to the process: [How To Use GitHub For Beginners - YouTube](https://www.youtube.com/watch?v=a9u2yZvsqHA)

We hope this helps clear up any confusion! Now you have a better understanding of how we collaborate and manage our projects. Feel free to ask a member if you have any questions!
