# Bandit Level 9 — Human-readable strings

## 🎯 Challenge

The password is one of the few human-readable strings in `data.txt`, preceded by several `=` characters.

## 🔎 What we need to do

Read the clue carefully, identify what kind of Linux operation it requires, and use the smallest appropriate tool.

## 💻 Solution

```bash
strings data.txt | grep '==='
```

## 🧠 Why this works

`strings` extracts printable text from binary-like data; `grep` narrows the results.

## 📚 Concept learned

**strings / binary inspection**

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
