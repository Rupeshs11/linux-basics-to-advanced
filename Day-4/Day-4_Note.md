# Day 04: Zip and Unzip Commands in Linux

## Overview
Zip and unzip commands in Linux are used to compress and decompress
files and folders. Compression helps reduce file size, save storage,
and make file transfer faster.

These commands are commonly used in backups, file sharing,
and server management.

---

## Commands

### gzip / gunzip
**Purpose:**  
Used to compress and decompress files.

**Syntax:**
- gzip file
- gzip -d file
- gunzip file

**Usage:**
- Compresses a file to reduce its size
- Decompresses a `.gz` file back to original

---

### tar (compress folder)
**Purpose:**  
Used to compress a folder into a single archive file.

**Syntax:**
- tar -czf myfiles.tar.gz myfiles/

**Usage:**
- Combines multiple files into one archive
- Commonly used for backups

---

### tar (decompress folder)
**Purpose:**  
Used to extract files from a compressed archive.

**Syntax:**
- tar -xzf myfiles.tar.gz

**Usage:**
- Restores files from a backup archive
- Extracts all files into the current directory

---

### zip
**Purpose:**  
Used to compress multiple files into one zip file.

**Syntax:**
- zip myfiles.zip file1 file2

**Usage:**
- Creates a single zip file from multiple files
- Useful for sharing files

---

## Why These Commands Matter
- Reduce file size and save storage
- Make file transfer faster
- Widely used for backups and deployments
- Essential for server and cloud environments

---

## Summary
- gzip / gunzip → compress and decompress files  
- tar -czf → compress a folder  
- tar -xzf → extract a compressed folder  
- zip → compress multiple files into one zip file  
