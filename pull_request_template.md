## 📌 Description
<!-- Provide a clear and concise description of what your pull request does. Include details about the issue or feature it addresses. -->

## 🔗 Related Issue
<!-- Link the issue this PR is solving. -->
Closes #ISSUE_NUMBER  

## ✅ Checklist (Must complete before submitting)
- [ ] I have searched for existing pull requests for this issue.
- [ ] My code follows the code style guidelines of the repository.
- [ ] I have performed a self-review of my code.
- [ ] I have commented my code, particularly in hard-to-understand areas.
- [ ] I have added necessary documentation (if applicable).
- [ ] My changes do not introduce new warnings or errors.
- [ ] I have tested my changes and ensured they work as expected.

## 📸 Screenshots (if applicable)
<!-- If UI changes were made, attach relevant screenshots here. -->

## ❗ Additional Information
<!-- Add any additional context or questions related to this PR. -->

🚀 How to Fork, Clone, and Raise a Pull Request

Step 1: Fork the MOSS Repository
1. Go to the MOSS Organization repository on GitHub.
2. Click the Fork button at the top-right corner.
3. GitHub will create a copy of the repository under your account.

Step 2: Clone Your Forked Repository
1. Open a terminal or Git Bash.
2. Run the following command to clone your fork:
    git clone https://github.com/YOUR_GITHUB_USERNAME/REPO_NAME.git
3. Navigate into the cloned repository:
   cd REPO_NAME
4. Set up the upstream repository:
   git remote add upstream https://github.com/moss-org/REPO_NAME.git
5. Verify the remotes:
   git remote -v
 You should see both origin (your fork) and upstream (the original MOSS repository).

Step 3: Create a New Branch
1. Fetch the latest changes from the original repository:
  git fetch upstream
  git checkout main
  git merge upstream/main
2. Create and switch to a new branch for your feature or bug fix:
   git checkout -b feature-branch
 (Replace feature-branch with a meaningful name (e.g., fix-navbar-bug)).
Step 4: Make Changes and Commit
1. Make the required code changes.
2. Add the modified files to staging:
   git add .
3. Commit the changes with a descriptive message:
  git commit -m "Fix: Navbar alignment issue #42"

Step 5: Push Changes to Your Fork
1. Push your branch to your forked repository:
   git push origin feature-branch

Step 6: Create a Pull Request (PR)
1. Go to your forked repository on GitHub.
2. Click "Compare & pull request".
3. Add a title and description for your PR.
4. Ensure the base repository is set to moss-org/REPO_NAME and the base branch is main.
5. Click Create pull request.


Step 7: Sync Your Fork with Upstream (If Needed)
   If the main repository is updated, update your fork:
    git checkout main
    git fetch upstream
    git merge upstream/main
    git push origin main

To update your feature branch:

  git checkout feature-branch
  git merge main
  git push origin feature-branch


🎯 Final Notes
Wait for the maintainers to review your PR.
If requested, make changes and push updates.
Once approved, your PR will be merged into the MOSS Organization repository.

