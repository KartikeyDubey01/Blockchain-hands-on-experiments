# 🔗 Blockchain Hands-On Experiment Repository

Welcome to the **Blockchain Hands-On Experiment** repository! This collection contains practical experiments designed to help students and enthusiasts understand the foundational concepts of blockchain technology through real-world command-line cryptographic operations.

---

## 📚 Contents

### ✅ Experiment 01: Generating Hash Values Using Linux Commands

- Understand hashing and its role in data integrity and security.
- Use Linux commands to generate MD5, SHA-1, and SHA-256 hash values from a given string.
- Compare hash lengths and outputs across algorithms.
- Learn how hashing is applied in blockchain to secure data blocks.

➡️ [View `hashing_experiment.asciidoc`](./hashing_experiment.asciidoc)

---

### ✅ Experiment 02: Public/Private Key Generation using OpenSSL

- Generate RSA key pairs (public/private) using OpenSSL.
- Encrypt a message with the public key and decrypt with the private key.
- Understand asymmetric encryption and its importance in secure communication and digital signatures.
- Learn how public-key cryptography secures blockchain wallets and transactions.

➡️ [View `openssl_keygen_experiment.asciidoc`](./openssl_keygen_experiment.asciidoc)

---

## 🎯 Learning Outcomes

By completing these experiments, you will:

- Grasp core blockchain principles like cryptographic hashing and public-key cryptography.
- Use Linux and OpenSSL tools to simulate real-world blockchain security operations.
- Build foundational skills needed for advanced blockchain development and smart contracts.

---

## 🔗 Relevance to Blockchain

These experiments reinforce key blockchain security mechanisms:

- **Hashing** secures block data and creates tamper-proof chains.
- **Public-Key Cryptography** ensures user identity, wallet ownership, and transaction validation.
- These concepts are fundamental to understanding cryptocurrencies, digital signatures, and smart contracts.

---

## 🚀 How to Run

### Requirements:
- Linux/macOS terminal or WSL (Windows Subsystem for Linux)
- OpenSSL installed (`sudo apt install openssl`)
- Basic knowledge of CLI

### Running Commands:

```bash
# Example: Generate SHA-256 hash
echo -n "hello123" | sha256sum

# Example: Generate RSA private key
openssl genpkey -algorithm RSA -out private_key.pem -aes256
