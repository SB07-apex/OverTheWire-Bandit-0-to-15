# Bandit Level 13 — SSH private key

## 🎯 Challenge

The password for the next level is protected so only `bandit14` can read it. Instead of a password, you receive a private SSH key that can log into the next level.

## 🔎 What we need to do

Read the clue carefully, identify what kind of Linux operation it requires, and use the smallest appropriate tool.

## 💻 Solution

```bash
ls
chmod 600 sshkey.private
ssh -i sshkey.private bandit14@localhost
```

## 🧠 Why this works

The private key authenticates as `bandit14`. `chmod 600` prevents SSH from rejecting an overly-permissive key.

## 📚 Concept learned

**SSH keys**

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
