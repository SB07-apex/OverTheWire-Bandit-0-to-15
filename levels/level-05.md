# Bandit Level 5 — File properties

## 🎯 Challenge

Find the file that is human-readable, 1033 bytes, and not executable.

## 🔎 What we need to do

Read the clue carefully, identify what kind of Linux operation it requires, and use the smallest appropriate tool.

## 💻 Solution

```bash
find . -type f -size 1033c ! -executable
cat ./<result>
```

## 🧠 Why this works

`find` can combine type, exact size, and executable predicates.

## 📚 Concept learned

**find / file metadata**

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
