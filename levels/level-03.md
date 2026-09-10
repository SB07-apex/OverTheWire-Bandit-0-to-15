# Bandit Level 3 — Hidden file

## 🎯 Challenge

The password is in a hidden file inside the `inhere` directory.

## 🔎 What we need to do

Read the clue carefully, identify what kind of Linux operation it requires, and use the smallest appropriate tool.

## 💻 Solution

```bash
cd inhere
ls -la
cat ./<hidden-file>
```

## 🧠 Why this works

`ls -la` displays hidden entries. Linux hidden filenames normally begin with `.`.

## 📚 Concept learned

**Hidden files**

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
