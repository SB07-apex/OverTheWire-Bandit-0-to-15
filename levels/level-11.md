# Bandit Level 11 — ROT13

## 🎯 Challenge

The password is in `data.txt`; uppercase and lowercase letters have been rotated by 13 positions.

## 🔎 What we need to do

Read the clue carefully, identify what kind of Linux operation it requires, and use the smallest appropriate tool.

## 💻 Solution

```bash
cat data.txt | tr 'A-Za-z' 'N-ZA-Mn-za-m'
```

## 🧠 Why this works

`tr` maps each letter to its ROT13 counterpart.

## 📚 Concept learned

**ROT13 / substitution**

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
