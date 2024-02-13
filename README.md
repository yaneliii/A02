# A02

###Part 1 (Tutorial on Git, WebStorm, and GitHub):
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
