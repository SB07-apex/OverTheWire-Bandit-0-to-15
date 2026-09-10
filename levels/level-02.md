# Bandit Level 2 — Filename with spaces

## 🎯 Challenge

The password is in a file called `--spaces in this filename--` in the home directory.

## 🔎 What we need to do

Read the clue carefully, identify what kind of Linux operation it requires, and use the smallest appropriate tool.

## 💻 Solution

```bash
ls
cat "./--spaces in this filename--"
```

## 🧠 Why this works

Quotes make the filename, including its spaces, a single shell argument.

## 📚 Concept learned

**Shell quoting**

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
