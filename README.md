# 🔐 GPG_Asymmetric_Encryption

A simple implementation of **asymmetric encryption and decryption** using **GPG (GNU Privacy Guard)**.  
This project demonstrates how to securely **encrypt**, **decrypt**, **sign**, and **verify** data using **public/private key pairs**.

---

## 📘 Overview

**Asymmetric encryption** (also called *public-key encryption*) uses two keys:

- **Public key** — used to encrypt data  
- **Private key** — used to decrypt data and create digital signatures

This project leverages the **GPG command-line tool** to handle key generation, encryption, and decryption operations.

---

## 🧰 Prerequisites

Make sure you have the following installed:

| Tool | Version | Description |
|------|----------|-------------|
| `gpg` | ≥ 2.2 | GNU Privacy Guard CLI tool |
| `bash` / `python` | any | (depending on your script implementation) |

Check your GPG installation:
```bash
gpg --version
