# 📦 Java File Archiver & Extractor

## 📝 Overview

A simple console-based Java application that packs multiple `.txt` files from a directory into a single archive file and extracts them back when needed.
The program uses a custom header format to store file metadata and applies XOR-based encryption for basic data protection.

---

## 🚀 Features

* Packs multiple text files into one archive
* Preserves file name and file size (metadata)
* XOR-based encryption and decryption
* Byte-level file processing using Java streams

---

## 🧩 Project Structure

```
FileArchiver.java    → Packs and encrypts files from a folder
FileExtractor.java   → Extracts and decrypts files from the archive
```

---

## ⚙️ Tech Stack

* Java
* FileInputStream / FileOutputStream
* Byte-level file handling

---

## ▶️ How to Run

### Compile

```
javac FileArchiver.java
javac FileExtractor.java
```

### Run Archiver

```
java FileArchiver
```

### Run Extractor

```
java FileExtractor
```

---

## 🎯 Purpose

This project demonstrates **Java file handling, custom archive creation, and basic encryption techniques**.
