# Bandit Learning History

## Stage 1 — Linux access
Levels 0–3 introduce SSH, file reading, paths, shell quoting, and hidden files.

## Stage 2 — File discovery
Levels 4–6 introduce `file` and increasingly precise `find` searches.

## Stage 3 — Text processing
Levels 7–9 introduce `grep`, pipelines, `sort`, `uniq`, and `strings`.

## Stage 4 — Encoding and data transformation
Levels 10–12 introduce Base64, ROT13, hexdumps, and repeated compression.

## Stage 5 — Authentication and networking
Levels 13–15 introduce SSH private-key authentication, TCP services with netcat, and SSL/TLS with OpenSSL.

## Overall progression

```text
SSH
 ↓
Filesystem
 ↓
File discovery
 ↓
Text processing
 ↓
Encoding
 ↓
Compression
 ↓
SSH keys
 ↓
TCP
 ↓
TLS
```
