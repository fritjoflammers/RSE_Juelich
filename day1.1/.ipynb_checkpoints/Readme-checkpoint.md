# 💻 Practicing GitHub (Day 1.1)

Welcome to **Day 1** of our **Research Software Engineering course**!  
Today, we’ll practice the **foundational skills for collaborating on GitHub**:  
**Forking, editing, creating issues, and submitting pull requests, and later, branches**.


---

<details>
<summary>Activity 1 - Commiting and pull requests</summary>

## Added random note to practice.

## ✅ Step-by-Step Tasks: 

### 1️⃣ Log into your GitHub account

- Make sure you're signed into [https://github.com](https://github.com).
- If you don’t have an account yet, [create one here](https://github.com/join).

---

### 2️⃣ Fork the course repository

> This step creates your **own copy** of the course repo, where you can make changes safely.

- Go to the course GitHub repository.
- Click the **🔱 Fork** button (top right of the page).
- GitHub will create a copy of the repository under **your username**.

✅ You now have your own editable version of the course repo.

---

### 3️⃣ Create a new file in the `day1.1/` folder

> This simulates contributing a small piece of content to a shared project.

- In your **forked repository**, navigate to the `day1.1/` folder.
- Click **"Add file" ➝ "Create new file"**.
- Name the file: `YourName.md`  
  (replace `YourName` with your actual first name, e.g., `Sophie.md`).
- In the file:
  - On the first line, write:  
    ```
    My favourite animal is: [your animal]
    ```
  - (You can add more lines if you like — have fun with it!)

- Commit the file with a meaningful message, e.g.,  
  `"Add Sophie.md with my favourite animal"`

---

### 4️⃣ Create a Pull Request (PR)

> Pull Requests are how we suggest changes to shared projects.

- Go back to your forked repository’s homepage.
- You should see a prompt saying: **“Compare & pull request”** — click it.
- If not, go to the **"Pull Requests"** tab and click **"New Pull Request"**.
- Make sure the base repo is the **original course repo**, and you're comparing from your fork.
- Give your PR a clear title (e.g., `"Add Sophie.md with my favourite animal"`).
- Click **"Create Pull Request"**.

✅ You’ve just proposed a change to a shared codebase — like a real open-source contributor!

---

### 5️⃣ Create an Issue and link your Pull Request

> Issues help track discussions, bugs, and requests. You'll link your PR to an Issue.

- Go to the **original course repository** (not your fork).
- Click the **"Issues"** tab ➝ **"New Issue"**.
- Title the issue something like:  
  `"My pull request to add my favourite animal"`
- In the description, explain that you created a markdown file and submitted a pull request.
- Paste the link to your Pull Request into the Issue description.

✅ Submit the Issue.

Bonus: GitHub may auto-link your PR and Issue — if not, you can also add  
`Closes #IssueNumber` to your PR comment to link them.

---

## 💡 Tips

- Don’t worry if something goes wrong — that’s part of the process!
- Ask for help if you're stuck — collaboration and asking questions are core RSE skills.
- If you're done early, try helping someone else or explore other folders in the repo.

---

## 🧠 What You’re Practicing

- ✅ Forking a repo
- ✅ Making your first contribution
- ✅ Creating pull requests and issues
- ✅ Communicating clearly in collaborative tools

---

> 🚀 _This is your first step toward working like a real research software engineer._

</details>

<details>
<summary>Activity 2 - Branches</summary>

# 🌿 Working with Branches in GitHub (Activity 2)

In this activity, you’ll practice **creating a branch**, making changes safely in it, and then **merging it back** into your main project.

This is how developers work without stepping on each other’s toes!



# ✅ Step-by-Step Instructions

### 1️⃣ Create a New Branch

> A branch is like a “sandbox” where you can work on changes without affecting the main code.

- Go to your **forked repository** on GitHub.
- Click the **branch selector dropdown** near the top-left (it likely says `main`).
- In the search bar, **type a name** for your new branch — for example:  
  `my-new-feature` (or something like `dev`, short for `development`)
- Press **Enter** or click **“Create branch”**.

🎉 You’ve now created a new branch!



### 2️⃣ Make Changes in Your Branch

- On GitHub, navigate to a file (e.g., `README.md`) in your **new branch**.
- Click the **pencil icon** (✏️) at the top right to edit the file.
- Make a small change — for example, add your name or a project description.
- Scroll down and write a **commit message** like:  
  `Updated README with my name`
- Make sure **“Commit directly to the \`my-new-feature\` branch”** is selected.
- Click **Commit changes**.

✅ You’ve now made changes **safely in your branch**.



### 3️⃣ Create a Pull Request (PR)

> A pull request is how you suggest merging your changes back into the main branch.

- Click the **"Pull requests"** tab at the top.
- Click **“New pull request”**.
- Select your branch (``my-new-feature`) to merge **into `main`**.
- GitHub will show a comparison — check that everything looks good.
- Click **“Create pull request”**.
- Give your pull request a title and description.
- Click **“Create pull request”** again.



### 4️⃣ Merge Your Branch into Main

- Once your pull request is open, scroll down and click **“Merge pull request”**.
- Click **“Confirm merge”**.

🚀 Congratulations — you’ve successfully used branching and merging!



</details>

<details>
<summary>Activity 3 - Code Reviews</summary>

## 🤝 Code Review in pairs

In this activity, you will practice **collaborative software development** using GitHub — just like real researchers and developers do.

> 🎯 **Goal:** Collaborate on each other’s repositories using forking, pull requests, and peer review.

You will:
- Work in **pairs**
- **Fork and edit** each other's repositories
- Create **pull requests**
- **Assign and review** contributions
- Practice **collaborative version control**

---

### 👯 Step-by-Step Instructions

### 1️⃣ Work in Pairs

- Choose a partner.
- Make sure both of you have a **fork of the course repository** with a personal file (e.g. `YourName.md` in `day1.1/`).
- If you did not create this file in Activity 1, have a look there to proceed. 

---

### 2️⃣ Fork Each Other’s Repository

> This simulates contributing to someone else's project.

- Navigate the browser to your partner’s GitHub repository.
- Click **“Fork”**.
- GitHub won’t allow you to fork a repo into the same name space if you already have a repo with the same name.
  - 🛠 If needed, **rename your fork** temporarily:
    - Go to **Settings** → Change the **Repository name**.

✅ Now you have a copy of your partner’s repo in your account.

---

### 3️⃣ Make a Change

> Add a friendly contribution to your partner’s repo.

- In your fork of your partner’s repository:
  - Navigate to the `day1.1/` folder.
  - Edit their `YourPartner.md` file.
  - Add a friendly sentence like:  
    `"Collaborated with Alex on Day 1 — we both like elephants!"`
- Commit the change with a clear message, e.g.:  
  `"Add collaboration note to Alex's file"`

---

### 4️⃣ Create a Pull Request (PR)

> Suggest your changes back to your partner’s repository.

- Go to your fork of their repository.
- Click **“Compare & pull request”**.
- Make sure you’re creating a PR **to your partner’s repo**, **not the course repo**.
- Write a clear title (e.g. `"Collaborative update to Alex.md"`) and message.

✅ This is your suggested contribution.

---

### 5️⃣ Assign Your Partner as a Reviewer

> Good practice: request review before merging.

- On the Pull Request page:
  - Click the **“Reviewers”** panel (top right).
  - Assign your partner as the reviewer.

---

### 6️⃣ Review Each Other’s Pull Requests

> Now switch roles: each of you will review the incoming PR.

- Go to your own repository (the one your partner submitted the PR to).
- Open the Pull Request.
- Click **“Files changed”** to review the diff.
- Click **“Review changes”** . You can leave a message at the direct location of change by clikcing the + button.
- Once you are happy with the change → Approve with a short message, e.g.  
  `"Nice touch — approved!"`

✅ Each partner should **review and approve** the PR from the other.

---

### 7️⃣ Merge the Pull Request

> Once reviewed, merge the contribution into your main branch.

- Click **“Merge pull request”** → then **“Confirm merge”**.
- (Optional) Delete the branch after merging.

✅ You’ve now successfully collaborated like professionals!

---

## 🧠 What This Activity Teaches

- 🔁 Working across repositories
- 🔧 Making safe changes using forks
- 🗂 Submitting and reviewing pull requests
- 🗨 Communicating code changes clearly
- ✅ Practicing real-world collaboration workflows

---

## 💡 Tips

- Be kind and constructive in review comments.
- Use clear commit messages and pull request titles.
- If you're confused, ask — this is a *learning* activity!

---

## ✅ What You’ve Practiced

- ✅ Forking another person's repo
- ✅ Editing someone else’s file
- ✅ Creating and assigning a Pull Request
- ✅ Reviewing and merging contributions
</details>
