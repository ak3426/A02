# A02

---

## Part 1 — Step by Step Directions

### 1. Install WebStorm
* WebStorm is an IDE by JetBrains. We'll use it to write code and interface with GIT and GitHub.
* Download WebStorm (free with a student license):
  (https://www.jetbrains.com/student/)

### 2. Install Git as a Local Program
* GIT is a distributed version control system that tracks changes in any set of computer files. It is installed locally to manage your project's history.
* Download Git for your operating system:
  [https://git-scm.com/downloads](https://git-scm.com/downloads)

### 3. Set Up GitHub

* Create a GitHub account if you don’t have one already:
  [https://github.com/join](https://github.com/join)

### 4. Connect GitHub with WebStorm

* Open WebStorm.
* Press `Ctrl + Alt + S` (Windows/Linux) or `⌘ + ,` (macOS) to open **Preferences**.
* Navigate to **Version Control → Git**.
* Enter the path to your `git.exe` (on Windows) or Git binary (on macOS/Linux).

### 5. Add GitHub Password to WebStorm

* In Preferences go to: **Appearance and Behavior → System Settings → Passwords**.
* Store your GitHub credentials or use GitHub token authentication.

### 6. Create a Repository on GitHub

* On GitHub, click the **+** sign in the top-right corner.
* Select **New repository**.
* Name it **A02** (capital A).
* Make the repository **public**.
* Check **Add a README file**.
* Click **Create**.

### 7. Create a Repository from WebStorm

* In WebStorm: `VCS → Import into Version Control`.
* Select **Create Git Repository** in your project folder.

### 8. Import a Repository from GitHub

* From the GitHub website or WebStorm:

  * **Main page**: Select *Checkout from Version Control → Git*.
  * Or in WebStorm: `VCS → Checkout from Version Control → Git`.
* Enter your GitHub repository URL.
* Enter your local path (where the project will be stored).

### 9. Create a WebStorm File

* In WebStorm: `File → New → HTML → HTML 5` or `File → New → Stylesheet`.
* This creates files in your project folder.

### 10. Add Files to Git

* When prompted, the **Add to Git** dialog appears.
* Click **Add** — this stages the file to your local Git repository.

### 11. Commit Your Changes

* Go to `VCS → Git → Commit`.
* Write a commit message (e.g., *Feature: add index.html*).
* Click **Commit**.

### 12. Push Changes to GitHub

* Shortcut: `Ctrl + Shift + K` (Windows/Linux) or `⌘ + Shift + K` (macOS).
* Or menu: `VCS → Git → Push`.
* Your file is now uploaded to GitHub.

### 13. Set Up GitHub Pages

* On GitHub, open your repository.
* Go to **Settings**.
* Scroll down to **GitHub Pages**.
* Under **Source**, select **main branch** (or **master branch** depending on repo).
* GitHub will give you a published URL, usually:

  ```
  https://yourusername.github.io/A02/
  ```

### 14. Test GitHub Pages

* Copy the GitHub Pages URL into your browser.
* Confirm your page loads.
* Submit the URL into Canvas along with your GitHub repo link.

---

## Part 2 — Glossary

* **Branch** — : A separate version of your code, like a parallel path, used for working on new features without messing up the main code.
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
* **Repository** — The code editor (IDE) we use to write code and manage GIT actions.

---

## References
1. Slides provided by Instructor.
2. Beer, B. (2018). *Introducing GitHub* (2nd ed.). O’Reilly Press.
3. JetBrains. (2019). *Using Git Integration in WebStorm*. Retrieved from [https://www.jetbrains.com/help/webstorm/using-git-integration.html](https://www.jetbrains.com/help/webstorm/using-git-integration.html)
4. GitHub. (2019). *Hello World Tutorial*. Retrieved from [https://guides.github.com/activities/hello-world/](https://guides.github.com/activities/hello-world/)

