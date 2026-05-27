# RSA & AES Encryption System

A Java-based cryptography project implementing RSA and AES encryption algorithms with a graphical user interface using Java Swing.

---

## Features

- RSA key generation
- RSA encryption/decryption
- AES encryption/decryption
- Graphical User Interface (GUI)
- Text encryption & decryption
- File handling support
- Educational implementation of cryptographic algorithms

---

## Technologies Used

- Java
- Java Swing
- BigInteger
- Object-Oriented Programming (OOP)

---

## Project Structure

```text
ProjectMaHoa_NhapMonATTT-master/
│
├── src/
│   │
│   ├── Main/
│   │   └── Main.java
│   │
│   ├── ThuatToan/
│   │   ├── AES.java
│   │   ├── ThuatToanRSA_v1.java
│   │   └── ThuatToanRSA_v2.java
│   │
│   └── gui/
│       └── GUI_MaHoa.java
│
├── build/
│
├── nbproject/
│
├── dist/
│
├── README.md
│
└── .gitignore
```

---

## RSA Workflow

1. Generate two prime numbers `p` and `q`
2. Compute:
   ```text
   n = p × q
   φ(n) = (p − 1)(q − 1)
   ```

3. Choose public key `e`

4. Compute private key `d`

5. Encrypt:
   ```text
   C = M^e mod n
   ```

6. Decrypt:
   ```text
   M = C^d mod n
   ```

---

## AES Workflow

Implemented AES components include:

- SubBytes
- ShiftRows
- MixColumns
- AddRoundKey
- Key Expansion

This project manually implements AES logic instead of using built-in cryptography libraries.

---

## GUI Overview

The application includes a Java Swing GUI that allows users to:

- Enter plaintext
- Encrypt messages
- Decrypt ciphertext
- Load/save files
- Interact with RSA and AES functions visually

---

## How to Run

### 1. Clone Repository

```bash
git clone https://github.com/YOUR_USERNAME/rsa-aes-encryption-java.git
```

### 2. Open Project

Recommended IDEs:
- IntelliJ IDEA
- NetBeans
- Eclipse

### 3. Run Application

Run:

```text
src/Main/Main.java
```

or launch GUI:

```text
src/gui/GUI_MaHoa.java
```

---

## Screenshots

### Main GUI

```md
![GUI](screenshots/gui.png)
```

### Encryption Example

```md
![Encrypt](screenshots/encrypt.png)
```

---

## Educational Objectives

This project was developed for learning purposes in:
- Information Security
- Cryptography fundamentals
- RSA algorithm
- AES algorithm
- Java GUI programming

---

## Limitations

- Educational implementation only
- Small RSA key size
- No OAEP/PKCS#1 padding
- Not suitable for production security systems

---

## Future Improvements

- Increase RSA key size
- Add UTF-8 support
- Implement secure padding
- Improve GUI design
- Add file encryption support
- Refactor code structure


