# Bandit Level 1 — Read a file named `-`

## 🎯 Challenge

The password for the next level is in a file called `-` in the home directory.

## 🔎 What we need to do

Read the clue carefully, identify what kind of Linux operation it requires, and use the smallest appropriate tool.

## 💻 Solution

```bash
ls -la
cat ./-
```

## 🧠 Why this works

`-` can be interpreted specially by command-line tools. `./-` explicitly identifies the file path.

## 📚 Concept learned

**Linux paths / special filenames**

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
