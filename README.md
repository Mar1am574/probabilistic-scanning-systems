# probabilistic-scanning-systems

Barcodes & QR Codes Reliability Study

---

# 📌 Project Overview

This project studies how probability is used to improve the reliability of modern scanning systems such as barcodes and QR codes.

In real-world applications, scanners are affected by noise such as poor lighting, motion blur, or physical damage. This project explains how probability and error correction techniques help reduce data loss and improve decoding accuracy.

---

# 🎯 Objective

- Understand how scanning errors occur in digital systems
- Apply probability concepts to model these errors
- Study how redundancy improves data reliability
- Compare barcode and QR code error-handling methods

---

# ⚠️ Problem Statement

Manual data entry is slow and error-prone.
Although scanning systems solve this problem, they are still affected by random errors caused by real-world conditions.

Without correction methods, scanned data can be incomplete or incorrect.

---

# 🎲 Probability Concept

Bit Error Model

Each scanned bit can be correct or incorrect depending on environmental noise.

- Probability of error = p
- Probability of correct reading = (1 - p)

For a message with n bits:

P(All Correct) = (1 - p)^n

This shows how errors increase as data size increases.

---

# 🔁 Error Correction Idea

To improve reliability, extra redundant data is added to the code.

- More redundancy → higher accuracy
- Less redundancy → higher storage efficiency

This creates a trade-off between:
data capacity vs reliability

---

# 📊 Barcode vs QR Code

Feature             | Barcode         | QR Code
Structure           | 1D lines        | 2D matrix
Data Capacity       | Low             | High
Error Handling      | Basic checksums | Advanced correction (Reed-Solomon)
Damage Resistance   | Low             | High
Scanning Flexibility| Single direction| Multi-direction

---

# 🌍 Real-World Applications

- Retail checkout systems
- Inventory tracking
- Logistics and shipping
- Mobile payments and tickets

---

# 🧠 Key Learnings

- How probability models real-world scanning errors
- Why redundancy improves system reliability
- Difference between barcode and QR code structures
- Connection between mathematics and real systems

---

# 🧰 Tools Used

- Python (basic simulations)
- Mathematical modeling
- Probability theory
- PowerPoint

---

# 📦 Project Summary

This project connects probability theory with real-world scanning systems and shows how mathematical models improve reliability in modern digital communication.

---

# ⭐ Academic project in probability and data systems.
