# Bandit Level 6 — Owner, group and size

## 🎯 Challenge

Find a file somewhere on the server that is owned by `bandit7`, belongs to group `bandit6`, and is 33 bytes.

## 🔎 What we need to do

Read the clue carefully, identify what kind of Linux operation it requires, and use the smallest appropriate tool.

## 💻 Solution

```bash
find / -type f -user bandit7 -group bandit6 -size 33c 2>/dev/null
cat <result>
```

## 🧠 Why this works

The search starts at `/`; stderr is redirected to hide permission-denied messages.

## 📚 Concept learned

**find / ownership / groups**

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
