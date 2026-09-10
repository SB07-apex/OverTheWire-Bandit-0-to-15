# Bandit Level 8 — Unique line

## 🎯 Challenge

The password is the only line in `data.txt` that occurs once.

## 🔎 What we need to do

Read the clue carefully, identify what kind of Linux operation it requires, and use the smallest appropriate tool.

## 💻 Solution

```bash
sort data.txt | uniq -u
```

## 🧠 Why this works

Sorting places duplicates together; `uniq -u` prints lines occurring only once. The pipe passes output between commands.

## 📚 Concept learned

**sort / uniq / pipes**

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
