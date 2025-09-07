# CS100_Module6_IntermediatCSSBootstrap Lecture Example Code

This repository contains all the **HTML** and **CSS** example files used in our lectures.  
You can use this code to review concepts, experiment, and practice.

---

## 📌 How to Use This Repository

### 1. Fork this repository
1. Make sure you are signed in to your GitHub account.
2. Go to the repository link provided by your instructor.
3. Click the **Fork** button in the top-right corner.
4. Select **your own GitHub account** as the destination.

This creates **your own copy** of the repository under your GitHub account.

---

### 2. Clone your fork to your computer
1. Go to **your forked repository** on GitHub.
2. Click the **Code** button (green) and copy the **HTTPS** URL.
3. Open **Terminal**, **Git Bash**, or **Command Prompt**.
4. Navigate to the folder where you want to store the code:
    ```bash
    cd path/to/your-folder
    ```
5. Run:
    ```bash
    git clone https://github.com/<your-username>/<repo-name>.git
    ```
    Replace `<your-username>` and `<repo-name>` with your own.

---

### 3. Open and try the code
- Open the project folder in **VS Code** (or your favorite code editor).
- Open `.html` files in the **Lecture** folder directly in a web browser, **or**  
  use **Live Server** in VS Code for better experience.
- Edit the files and experiment — you won’t affect the original repo.

---

## 🔄 Keeping your fork up-to-date (Optional)
If the instructor updates the original repo, you can pull changes into your fork:

1. Add the instructor's repo as an **upstream**:
    ```bash
    git remote add upstream https://github.com/<instructor-username>/<repo-name>.git
    ```
2. Fetch and merge the latest changes:
    ```bash
    git fetch upstream
    git merge upstream/main
    ```
    *(Replace `main` with `master` if needed.)*

