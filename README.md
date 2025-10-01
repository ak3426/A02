# A02

Git, GitHub, and WebStorm Tutorial
---

## Part 1 — Step by Step Directions

### 1.Create a GitHub Account
* Create a GitHub account if you don’t have one already:
  [https://github.com/join](https://github.com/join)
* Click Sign Up.
* Enter your email, username, and password.
* Verify your email and complete your profile setup.
### Create a Repository on GitHub
* On GitHub, click the **+** sign in the top-right corner.
* Select **New repository**.
* Name it **A02** (capital A).
* Make the repository **public**.
* Check **Add a README file**.
* Click **Create**.
* You will have now the link to your repository that must look like this: "https://github.com/yourUCID/A02"
  
### 2. Install WebStorm
* WebStorm is an IDE by JetBrains. We'll use it to write code and interface with GIT and GitHub.
* Download WebStorm (free with a student license):
  (https://www.jetbrains.com/student/)

### 3. Install Git as a Local Program
* GIT is a distributed version control system that tracks changes in any set of computer files. It is installed locally to manage your project's history.
* Download Git for your operating system:
  [https://git-scm.com/downloads](https://git-scm.com/downloads)

### 4. Connect GitHub with WebStorm and Set Up Repository

* Open WebStorm.
* On the welcome screen, click Get from VCS (Version Control System).
* In the dialog box, paste your GitHub repository URL (example: https://github.com/yourUCID/A02).
* Choose a local folder on your computer where the project will be saved.
* Click Clone. WebStorm will now download the repository and link it to your project.
* To add new files, go to File → New → HTML File (or Stylesheet, JavaScript, etc.).
* When WebStorm asks if you want to Add to Git, click Add. This stages your files for version control.


### 5. Modifications to README.md 

* Open README.md in WebStorm.
* Write your information in this file and save it.
* In WebStorm, go to Git > Commit.
* Write a clear message.
* Click Commit and Push to upload changes to GitHub.

### 6. Push Changes to GitHub

* After committing
* To send changes to GitHub, click in the top left toolbar then Git> Push .
* Your committed changes are now uploaded to your GitHub repository and will appear online.  
* You can check your repository on GitHub to confirm your files have been updated.

### 7. Set Up GitHub Pages

* On GitHub, open your repository.
* Go to **Settings**.
* Scroll down to **GitHub Pages**.
* Under **Source**, select **main branch** (or **master branch** depending on repo).
* GitHub will give you a published URL, usually:

  ```
  https://yourusername.github.io/A02/

---

## Part 2 — Glossary

* **Branch** — A separate version of your code, like a parallel path, used for working on new features without messing up the main code.
* **Clone** — To download a full copy of the online repository to your local computer.
* **Commit** —An action that saves a snapshot of your changes to your local GIT history.
* **Fetch** — Retrieves updates from the remote repository without merging.
* **GIT** —he free, local software that tracks all the changes in your project files.
* **Github** — The website that hosts your GIT repositories online and helps teams collaborate.
* **Merge** — The process of combining changes from one Branch back into another (like combining a feature branch into the main code).
* **Merge Conflict** — Happens when two branches change the same part of a file and Git cannot automatically combine them.
* **Push** — Uploads local commits to a remote repository.
* **Pull** — Fetches and merges changes from the remote into the current branch.
* **Remote** — The online version of your project code, typically hosted on GitHub.
* **Repository** — A container that stores project files and their version history.

---

## References
1. Slides provided by Instructor.
2. JetBrains. (2019). *Using Git Integration in WebStorm*. Retrieved from [https://www.jetbrains.com/help/webstorm/using-git-integration.html](https://www.jetbrains.com/help/webstorm/using-git-integration.html)
3. GitHub. (2019). *Hello World Tutorial*. Retrieved from [https://guides.github.com/activities/hello-world/](https://guides.github.com/activities/hello-world/)

