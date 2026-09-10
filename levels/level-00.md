# Bandit Level 0 — SSH Login

## 🎯 Challenge

Log into the game using SSH. Host: `bandit.labs.overthewire.org`, port `2220`, user `bandit0`, password `bandit0`.

## 🔎 What we need to do

Read the clue carefully, identify what kind of Linux operation it requires, and use the smallest appropriate tool.

## 💻 Solution

```bash
ssh bandit0@bandit.labs.overthewire.org -p 2220
```

## 🧠 Why this works

SSH provides secure remote shell access. This level establishes the connection used for the rest of Bandit.

## 📚 Concept learned

**SSH**

## 🔐 Result / password

The output of the solution command is the credential/result required to continue to the next level.

```text
<PASSWORD_OBTAINED_HERE>
```

> Keep the real credential private if this repository is public.

## 📝 Notes

- What was difficult:
- What I learned:
- Useful command:
- Screenshot/evidence:

## ➡️ Next level

Use the resulting password to authenticate to the next Bandit level over SSH on port `2220`.
