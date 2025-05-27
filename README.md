# CAESAR-CIPHER-PYTHON

**Encrypt, Decrypt, Repeat: Master the Art of Secret Messaging!**

---

## 🚀 Built With

* Python 🐍
* Basic Terminal/Command Line
* `ASCII` Logo Art

---

## 📚 Table of Contents

* [Overview](#overview)
* [Features](#features)
* [How It Works](#how-it-works)
* [How to Run](#how-to-run)
* [Example](#example)
* [Error Handling](#error-handling)
* [Restart Feature](#restart-feature)
* [Improvements](#improvements)

---

## 🧠 Overview

**Caesar-Cipher-Python** is a beginner-friendly project based on the Caesar cipher encryption technique. It takes in a message and shifts each letter by a defined number, supporting both encoding and decoding options with clean error handling.

---

## ✨ Features

* Encrypts and decrypts messages using Caesar Cipher logic.
* Ignores non-alphabetical characters (e.g., numbers, spaces, symbols).
* User-friendly prompts and results.
* Supports automatic wrap-around of the alphabet.
* Displays an ASCII logo for a polished start.
* Easy to restart the program (TODO included).

---

## ⚙️ How It Works

1. Prints a logo from `art.py`.
2. Asks user whether they want to encode or decode.
3. Accepts the input message and shift value.
4. Outputs the converted message.
5. Can ignore characters like punctuation, numbers, and spaces.

---

## 🧪 How to Run

```bash
# Step 1: Ensure you have Python installed
python --version

# Step 2: Place the following files in the same directory
# - main.py
# - art.py (contains logo variable)

# Step 3: Run the program
python main.py
```

---

## 💡 Example

```
Type 'encode' to encrypt, type 'decode' to decrypt:
encode
Type your message:
hello world!
Type the shift number:
5

Here is the encoded result: mjqqt btwqi!
```

---

## ❗ Error Handling

* ✔ Automatically skips unsupported characters (e.g., `!`, `@`, `123`)
* ✔ Wraps around if shift exceeds the alphabet length
* ✔ Notifies users to retry if input direction is invalid

---

## 🔁 Restart Feature

A future improvement could include wrapping the input logic inside a loop like:

```python
should_continue = True
while should_continue:
    # existing logic
    restart = input("Do you want to go again? Type 'yes' or 'no': ")
    if restart != "yes":
        should_continue = False
```

---

## 🌱 Improvements

* [ ] Add uppercase letter support
* [ ] Include GUI using Tkinter
* [ ] Add history log of encoded/decoded messages
* [ ] Add unit tests

---
