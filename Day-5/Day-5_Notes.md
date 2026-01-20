# Day 05: Downloading Files from the Internet in Linux

## Overview
Linux provides command-line tools to download files directly from the internet.
These commands are very useful on servers where browsers are not available.

They are commonly used to download software packages, scripts, and resources
from remote URLs.

---

## Commands

### wget
**Purpose:**  
Used to download files from the internet using a URL.

**Syntax:**
- wget URL

**Usage:**
- Downloads files directly to the current directory
- Works in background and supports large files
- Commonly used on servers

---

### curl
**Purpose:**  
Used to transfer data from or to a server using a URL.

**Syntax:**
- curl URL
- curl -O URL

**Usage:**
- Fetches content from a URL
- `-O` saves the file with its original name
- Supports many protocols like HTTP and HTTPS

---

## Why These Commands Matter
- Essential for working on remote Linux servers
- Helps download tools and scripts quickly
- Widely used in DevOps and cloud environments
- Useful for automation and scripting

---

## Summary
- wget → download files from the internet  
- curl → transfer and fetch data from URLs  

These commands make it easy to access online resources directly from the Linux terminal.
