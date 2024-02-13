# A02

### Part 1 (Tutorial on Git, WebStorm, and GitHub):
1. Download **Git**:
   - For Windows: You can download **Git** for free from https://git-scm.com/downloads.
   - For Mac: Typically, on MacOS, **Git** is already installed. However, if it is not, you can download it from Homebrew. First, install Homebrew by pasting "/bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"" into the terminal. Then, to install **Git**, paste "brew install git" into the terminal.
   - To verify **Git** was installed, type "**git** version" into the terminal/command prompt.
2. Join **GitHub**
   - To set up **Github**, start by creating an account at https://github.com/join.
4. Download Webstorm
   - Optional: Before installing Webstorm, create a Jetbrains account and apply for a student license at https://www.jetbrains.com/community/education/#students.
   - Webstorm can be downloaded from https://www.jetbrains.com/webstorm/.
4. Connect **Git** with Webstorm
   - Start Webstorm and open system preferences by pressing (Ctrl+Alt+S) on Windows or (Cmd + ,) on Mac.
   - On the left sidebar, press "Version Control," then select "**Git**," and enter the path to the **Git** executable file.
   - Click the "Test" button to ensure Webstorm is connected to **Git**; this should display its version number.
   - Now, you can press "OK" to exit.
5. Create a **Repository** on **GitHub**
   - Go to your homepage on **Github**, then click the "+" symbol in the upper right corner.
   - Select the first option, "New **Repository**," from the drop-down list.
   - After configuring your **repository**, click "Create **Repository**."
6. Import a **Repository** from **GitHub**
   - In the **repository**, click the green "Code" button and copy the HTTPS URL.
   - If you closed Webstorm, open it up again.
   - From the first screen (what you see after launching the app), select "Get from VCS."
   - Paste the HTTPS (**GitHub**) URL and click "**Clone**."
7. Push a File to **Github**
   - To create an HTML file, choose "File," then "HTML file."
   - To create a CSS file, choose "File," then "Stylesheet."
   - A dialog opens; click "Add" to add the files to **Git**.
   - At the top of Webstorm, click "**Git**" and then "**commit**."
   - A text box should appear; add your **commit** message and click "**Commit**."
   - **Push** your changes to the **remote** **repository** by selecting "**Git**" (at the top), then "**Push**."
   - Select the committed file and click "**Push**."

### Part 2 (Glossary):
- **Branch** - A copy of the **commit** history of the current (active) **branch**. This separate version allows users to work on features without affecting their master/main **branch**.
- **Clone** - A **clone** is creating a copy of an existing **repository**, for instance, copying a **repository** from **GitHub** to your local machine.
- **Commit** - The action of saving changes made to a file or set of files, almost like a checkpoint. Users should always have a message when they **commit**, such as a brief description of what has changed.
- **Fetch** - To download/copy the latest files from a **branch** (in a **remote** **repository** like **Github**) to your workstation.
- **GIT** - An open-source software used for tracking and documenting your changes in files via a version control system.
- **Github** - A platform that hosts repositories and helps users store files, track code, and collaborate on projects (with version control).
- **Merge** - To bring the content from one **branch** into another (typically main) **branch**, thus combining the changes.
- **Merge Conflict** - Inconsistent changes in the same part/line of a file that prevents **branches** from merging. Users have to manually resolve the issue by choosing which changes to include.
- **Push** - Updates your **remote** **repository** by uploading (local) committed changes to the **remote**.
- **Pull** - Grabs any changes from a **remote** **repository** and **merges** them into your local **repository**.
- **Remote** - This is a copy/version of your **repository** stored on another computer or server (like **GitHub**).
- **Repository** - This is an object database of your project. You can think of it as a storage location that holds project files, their versions, and **commit** history.

## References
Ajibola, Segun. “How to Use Git and GitHub – Introduction for Beginners.” freeCodeCamp, 26 Sept. 2022, www.freecodecamp.org/news/introduction-to-git-and-github/#what-are-git-and-github. 

GeeksforGeeks. “Git Merge and Merge Conflict.” GeeksforGeeks, 5 Apr. 2022, www.geeksforgeeks.org/git-merge-and-merge-conflict. 

Git. “A Git Glossary.” Git, git-scm.com/docs/gitglossary#def_chain. 

Hendela, Arthur. “Introduction to Github and Webstorm.” Canvas, 18 Mar. 2019, njit.instructure.com/courses/33677/files/5972199?module_item_id=1281701. 

Krout, Elle. “Git Definitions and Terminology Cheat Sheet.” Pluralsight, 8 June 2023, www.pluralsight.com/resources/blog/cloud/git-terms-explained#merge. 

W3Schools. “Git **Commit**.” W3Schools, www.w3schools.com/git/git_commit.asp.
