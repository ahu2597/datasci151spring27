# DATASCI 151: Introduction to Statistical Computing II, Spring 2027

This repository has all the lecture notebooks, homework files and datasets for the course. You have your own copy of it (your **fork**). Use it to get new materials and to back up your notes.

**Homework is submitted on Gradescope through Canvas, not on GitHub.** Pushing to GitHub doesn't count as submitting.

---

## The golden rule

> **Never run or edit the instructor's files. Copy them into `my_work` first.**

Jupyter saves outputs into the notebook file, so **even just running a notebook changes it**. If you change one of the instructor's files, the next update can cause a conflict.

**Before you work in any notebook:**
1. In VS Code, right-click the notebook and choose **Copy**.
2. Right-click `my_work` and choose **Paste**.
3. Rename the copy (for example `lecture07_notes.ipynb`) and work only in the copy.

---

## Before class: get new materials

1. **Commit and push** any work you haven't saved yet (see below).
2. On github.com, go to **your fork** and click **Sync fork → Update branch**.
3. In GitHub Desktop, click **Fetch origin**, then **Pull origin**.
4. Copy the new lecture notebook into `my_work`.

> **Never click "Discard commits."** It deletes your notes. If it's the only option, stop and post on the Canvas Discussions board.

## After class: back up your notes

1. Open GitHub Desktop.
2. Type a short summary at the bottom left (for example `lecture 7 notes`).
3. Click **Commit to main**, then **Push origin**.

Pushing only updates **your** fork. You can't change the instructor's repository, so push as often as you like.

---

## Fixing common problems

**"Your local changes would be overwritten" when pulling.**
You changed one of the instructor's files. If you have notes in it, copy the file into `my_work` first. Then, in GitHub Desktop's **Changes** tab, right-click the file, choose **Discard changes**, and pull again.

**Sync fork says there's a conflict.**
Don't click "Discard commits." In GitHub Desktop, choose **Branch → Merge into current branch → upstream/main**. For each conflicted file outside `my_work`, choose the **upstream/main** version, then commit the merge. Still stuck? Bring your laptop to office hours.

**I see changed files I don't remember editing.**
If they're outside `my_work`, you probably ran a notebook. Discard the changes (see above). Your copies in `my_work` are not affected.

---

## Submitting homework

1. Copy the homework notebook into `my_work` and rename it (for example `hw03_lastname.ipynb`).
2. List your collaborators and any AI use at the top.
3. **Restart and Run All**, check that every cell runs without errors, and **save**.
4. Upload the **.ipynb** file to **Gradescope** through Canvas, then open the preview to check it's the right file.

If Gradescope is down, email the notebook to the instructor or a TA **before the deadline**.

---

## Quick reference

| When | Do this |
| --- | --- |
| Before working in a notebook | Copy it into `my_work` |
| Before class | Commit and push, then Sync fork → Update branch, then Fetch origin → Pull origin |
| After class | Commit to main, then Push origin |
| Changed a file by accident | Changes tab: right-click → Discard changes |
| Homework due | Upload the .ipynb file to Gradescope via Canvas |
| Questions | Office hours |
