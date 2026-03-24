# PFX Project 01 Animations on Console

This repository serves as a public gallery for the output submissions of Programming Fundamentals students. Students are required to upload screenshots and videos demonstrating the working of their project.

The purpose of this repository is to allow everyone in the class to view the outputs of different implementations while keeping the source code submissions separate.

---

## Initial Setup

1. Fork this repository to your own GitHub account.

2. Copy the link of your forked repository.

3. Open VS Code and clone your fork using:

```
git clone <your-forked-repo-link>
```

4. Open the cloned folder in VS Code.

5. Create your folder in the main root of the repository as instructed below and add your screenshots and video.

6. Open the terminal in VS Code and follow the commands given below.

---

## Git Authentication (Important)

Before pushing, make sure you are logged into the correct GitHub account.

If you face permission errors (403), do the following:

* Ensure you are using the same GitHub account where you created the fork
* Remove old credentials if needed (Windows Credential Manager)

---

## Submission Instructions

Follow the steps below carefully.

1. Create a new folder in the main root (same level as other folders) using the following naming format:

```
BSXX-25XXX-Name
```

Example:

```
BSCS-24009-Abdullah-Nawaz
```

2. Inside your folder upload your output screenshots and video.

Use the following naming format for files.

Screenshots:

```
ss01.png  
ss02.png  
ss03.png
```

Video:

```
vid01.mp4
```

---

## First Time Submission

Run the following commands in terminal (each command on a separate line):

```
git add .
git commit -m "initial submission"
git push origin main
```

Then go to GitHub and create a Pull Request:

* Click Contribute → Open Pull Request
* Ensure:

  * base repository = original repository
  * head repository = your fork

---

## Updating Your Submission Later

If you want to add more screenshots or videos later, run:

```
git pull origin main
git add .
git commit -m "updated submission"
git push origin main
```

Important:

* Run each command separately
* Your updates will only appear in your fork

After pushing updates, you must create a new Pull Request.

Steps:

1. Go to your forked repository
2. Click Contribute → Open Pull Request
3. Submit the new Pull Request

---

## Common Mistakes

* Running all git commands in one line
* Creating Pull Request from original repository instead of fork
* Being logged into the wrong GitHub account
* Not creating a new Pull Request after updates

---

## Important Guidelines

* Only upload screenshots and videos of the program output
* Do not upload source code in this repository
* Ensure your folder name follows the required format
* Ensure files are properly named before creating the Pull Request

---

## Final Note

* First submission requires a Pull Request
* Every update requires a new Pull Request

Once your Pull Request is submitted, it will be reviewed and merged.
