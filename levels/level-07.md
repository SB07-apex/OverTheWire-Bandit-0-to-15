# Bandit Level 7 — Search beside `millionth`

## 🎯 Challenge

The password is in `data.txt` next to the word `millionth`.

## 🔎 What we need to do

Read the clue carefully, identify what kind of Linux operation it requires, and use the smallest appropriate tool.

## 💻 Solution

```bash
grep millionth data.txt
```

## 🧠 Why this works

`grep` searches the contents of the file for the requested text.

## 📚 Concept learned

**grep**

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
