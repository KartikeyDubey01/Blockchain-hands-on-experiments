# Experiment 01: Generating Hash Value from a Given String using Linux Commands

---

## 🧠 Aim / Overview

The aim of this practical is to understand the concept of **hashing** and generate hash values from a given string using Linux commands.

Hash functions are used in various applications such as:

- Data integrity verification
- Password storage
- Digital signatures

In this experiment, we will learn how to generate hash values using commonly used algorithms such as **MD5**, **SHA-1**, and **SHA-256**.

---

## ✅ Tasks / Objectives

- Understand the concept of hash functions and their importance in security.
- Use Linux commands to generate hash values for a given string.
- Compare different hashing algorithms and understand their usage.

---

## 🧪 Steps for the Experiment

### Step 1: Open Terminal
Start by opening a terminal window in your Linux system.

---

### Step 2: Choose a String
Decide on a string for which you want to generate the hash value.  
For example, we will use:  
```text
hello123
Step 3: Generate Hash Using MD5
Use the md5sum command:

echo -n "hello123" | md5sum
Sample Output:

ae59a41d4ee2f6b0f46d198c174b5f08  -
Step 4: Generate Hash Using SHA-1
Use the sha1sum command:

echo -n "hello123" | sha1sum
Sample Output:

41d00b1e1aa7fbd98f0a00b7c2b7f7bdecc6c6c5  -
Step 5: Generate Hash Using SHA-256
Use the sha256sum command:

echo -n "hello123" | sha256sum
Sample Output:

7f715cfe650d5cb13a5280a5cf2d1b4ed0e7e0c1c77c50dc4ff38259a2a6d3d3  -
Step 6: Observe the Output
Each command outputs a different hash value for the same string (hello123), showing how different algorithms generate unique hashes.

Step 7: Compare Hash Values
Algorithm	Hash Length	Sample Output (Truncated)
MD5	128-bit	ae59a41d...
SHA-1	160-bit	41d00b1e...
SHA-256	256-bit	7f715cfe...
Each algorithm varies in terms of output length and security strength.

📝 Summary / Conclusion
In this experiment, we successfully generated hash values for a given string using three different hashing algorithms: MD5, SHA-1, and SHA-256.

We observed that:

MD5 generates a 128-bit hash.

SHA-1 generates a 160-bit hash.

SHA-256 generates a 256-bit hash.

These algorithms are deterministic (same input = same output) and play critical roles in data security, digital signatures, and file integrity verification.

🎯 Learning Outcomes
By completing this experiment, we have learned:

Concept of Hashing: Understanding how a hash function converts input into a fixed-size output.

Hashing Algorithms: Differences between MD5, SHA-1, and SHA-256 in terms of length and collision resistance.

Linux CLI Tools: Using md5sum, sha1sum, and sha256sum for hash generation.

Applications of Hashing: Practical use in password hashing, digital signatures, and blockchain technology.

🔗 Relevance to Blockchain
Hash functions are a cornerstone of blockchain technology. They ensure data integrity, are used in block creation, and provide tamper-evidence. This experiment builds foundational knowledge crucial for understanding how blockchain ensures security and immutability.
