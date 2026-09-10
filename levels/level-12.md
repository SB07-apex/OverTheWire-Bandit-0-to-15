# Bandit Level 12 — Repeated compression

## 🎯 Challenge

`data.txt` is a hexdump of a file that has been repeatedly compressed.

## 🔎 What we need to do

Read the clue carefully, identify what kind of Linux operation it requires, and use the smallest appropriate tool.

## 💻 Solution

```bash
mkdir /tmp/bandit12
a=$(mktemp -d)
cp data.txt "$a/"
xxd -r "$a/data.txt" "$a/data.bin"
file "$a/data.bin"
# Repeatedly identify and unpack each layer.
```

## 🧠 Why this works

The essential method is: reverse the hexdump, use `file` to identify each compression/archive format, then unpack and repeat.

## 📚 Concept learned

**xxd / file / gzip / bzip2 / tar**

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
