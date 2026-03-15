# Network Infrastructure Analysis Toolkit

## Overview

This project is a **Python-based network reconnaissance and analysis toolkit** created for **educational and cybersecurity research purposes**.
It demonstrates how security researchers analyze web infrastructure, CDN usage, DNS history, and publicly available information during **authorized security assessments**.

The tool combines several techniques commonly discussed in cybersecurity courses such as:

* DNS record analysis
* Subdomain enumeration
* SSL certificate inspection
* Email server record inspection
* Historical web data analysis
* HTTP header inspection

The goal of this project is to help students understand **how modern web infrastructure works** and how security researchers gather publicly available information.

---

## ⚠️ Ethical Use Notice

This project is intended **strictly for educational purposes and authorized security testing only**.

Do NOT use this tool against:

* Systems you do not own
* Websites without explicit permission
* Any infrastructure where testing is not legally authorized

Unauthorized scanning or attempts to bypass security controls may violate **laws and platform policies**.

Always follow responsible cybersecurity practices.

---

## Features

* CDN provider detection
* DNS record analysis
* Subdomain enumeration
* SSL certificate inspection
* Email (MX/SPF) record analysis
* HTTP header analysis
* Historical web archive analysis
* Multi-threaded scanning for faster research

---

## Requirements

Python 3.6 or higher

Required packages:

```
pip install requests dnspython
```

---

## Installation

Clone the repository:

```
git clone https://github.com/yourusername/network-analysis-toolkit.git
cd network-analysis-toolkit
```

Install dependencies:

```
pip install -r requirements.txt
```

---

## Usage

Run the program:

```
python main.py
```

The program will display an interactive menu where you can choose different analysis modules.

---

## Educational Purpose

This project helps students learn:

* How CDNs protect websites
* How DNS infrastructure works
* How SSL certificates store metadata
* How publicly available data can reveal infrastructure information
* Basic network reconnaissance concepts used in **ethical hacking labs**

---

## Recommended Learning Path

If you are learning cybersecurity, combine this project with topics such as:

* Networking fundamentals
* DNS architecture
* Web security basics
* Ethical hacking methodology
* Responsible disclosure practices

---

## Disclaimer

The author is not responsible for misuse of this software.
Users are responsible for ensuring that they comply with all applicable laws and regulation.
