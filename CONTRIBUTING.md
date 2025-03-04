# Participant: How to Contribute

1. **Visit the HackNight 6.0 Leaderboard**:
   Browse the leaderboard and choose a repository you'd like to contribute to!

2. **Check for Open Issues**:
   Look for any open issues in the repository. If you find one that interests you, ask to be assigned to it by commenting on the issue.

3. **Setup Your Codebase**:
   - **Fork** the repository to your GitHub account and copy it's clone URL
   - **Clone** your forked repository to your local machine using [Git](https://docs.github.com/en/get-started/getting-started-with-git/set-up-git) (make sure it's installed)

   ```bash
   git clone git@github.com:your-username/chess-opengl.git
   cd chess-opengl
   ```

4. **Build project**:
   > *Note*: The Makefile provided currently works only on Windows with MSYS2/MinGW. Building on other platforms will require tweaking it.

   - **Prerequisites**:  gcc, make
   - Build project using make
   ```bash
   make
   ```
   - Run
   ```
   "./build/chess"
   ```
   
5. **Make Your Changes**
   After you've setup the project, make the necessary changes to the code in your IDE. The directory structure is provided in [README.md](README.md).

6. **Commit and Push**:
   Commit your changes and push them to your fork:

   ```bash
   git commit -m "Describe the changes you made"
   git push
   ```

   Alternatively, use VSCode's inbuilt Git source control pane `Ctrl+Shift+G` if you're uncomfortable with a CLI

7. **Submit a Pull Request**:
   After pushing your changes, open a pull request to pull changes from your fork to the original repository.

8. **Get Feedback**
   Wait for a maintainer to review your pull request (PR) and provide feedback.

9. **Gain Bounty Points**
   If everything is approved, your issue will be closed, and you'll gain bounty points on the leaderboard!