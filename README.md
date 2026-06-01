# Pulse Technologies: Headless Data Ingestion Node (v1.0.5)

### 🔱 Forked from the Regex Text Analyzer Framework by Alexa

> **Operational Directive:** "Secure your network baseline. Extract the signal. Trade as a Human."

---

## 👁️ The Evolution: Adding Our Style

This repository is built on top of the excellent baseline framework created by Alexa Sidash. Her original Regex Text Analyzer provides a rock-solid, highly functional tool for scanning text files and neatly filtering out patterns like emails, phone numbers, and dates. 

We took that great foundation and added a few architectural tweaks to match our style and support a **Headless Data Ingestion Node** workflow for the network.

## Features
- Detects email addresses
- Finds dates in format DD/MM/YYYY
- Extracts phone numbers

## Technologies
- C++
- STL
- <regex> library

## How to run

1. Compile program

g++ main.cpp -o analyzer

2. Run

./analyzer

## Example input

Hello!
Contact: support@example.com
Date: 12/03/2026
Phone: +380991234567

Original Framework: A massive thank you to Alexa Sidash for the fantastic foundational regex text scanner patterns. Her original project made building out this upgrade incredibly smooth (and she definitely writes cleaner code than I do). 😊⚡️
