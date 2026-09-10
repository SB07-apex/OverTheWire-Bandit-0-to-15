# Bandit Level 14 — Submit password to port 30000

## 🎯 Challenge

Retrieve the next password by submitting the current password to port `30000` on `localhost`.

## 🔎 What we need to do

Read the clue carefully, identify what kind of Linux operation it requires, and use the smallest appropriate tool.

## 💻 Solution

```bash
cat /etc/bandit_pass/bandit14 | nc localhost 30000
```

## 🧠 Why this works

`nc` (netcat) opens a TCP connection and the pipe sends the current password to the service.

## 📚 Concept learned

**TCP / netcat**

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
