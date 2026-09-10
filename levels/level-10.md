# Bandit Level 10 — Base64

## 🎯 Challenge

The password is in `data.txt`, which contains Base64-encoded data.

## 🔎 What we need to do

Read the clue carefully, identify what kind of Linux operation it requires, and use the smallest appropriate tool.

## 💻 Solution

```bash
base64 -d data.txt
```

## 🧠 Why this works

Base64 is an encoding, so decoding reverses the representation.

## 📚 Concept learned

**Base64**

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
