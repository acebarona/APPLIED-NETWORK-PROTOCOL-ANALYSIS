# Brute Force 3-Digit PIN using Socket and HTTP

## Overview
This project is part of my IT6 take-home drill. The goal is to brute-force a 3-digit PIN from a local web server.

## Requirements
- Python
- Only the `socket` library used
- Analyzing server behavior via Wireshark

## How it Works
- Connects to 127.0.0.1:8888
- Sends POST requests to `/verify`
- Tries all combinations from 000 to 999
- Adds delay to respect server rate limits

## What I Learned
- HTTP protocol basics
- Crafting raw HTTP requests
- Network traffic analysis with Wireshark
- Basic brute-force techniques

## Security Recommendation
To protect against brute-force attacks:
- Add rate limits
- Use CAPTCHA
- Track failed attempts and ban IPs


## 🎥 Video Presentation

Watch the full video tutorial here: [Google Drive Video](https://drive.google.com/file/d/1uedMRDI8xbukXssxmye0OrDD6a0Jn0Fx/view?usp=sharing)

> Note: I included the video here in the README file because the storage limit on GitHub is only up to 100MB, and the video file is too large.
