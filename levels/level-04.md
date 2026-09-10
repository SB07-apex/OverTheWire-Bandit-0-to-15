# Bandit Level 4 — Human-readable file

## 🎯 Challenge

The password is in the only human-readable file in `inhere`.

## 🔎 What we need to do

Read the clue carefully, identify what kind of Linux operation it requires, and use the smallest appropriate tool.

## 💻 Solution

```bash
cd inhere
file ./*
cat ./<readable-file>
```

## 🧠 Why this works

`file` identifies the type/content of each candidate, letting us select the text file.

## 📚 Concept learned

**File identification**

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
