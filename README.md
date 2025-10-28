# Webscan
Website scaning tool 

Features:

1. Port Scanning - Complete port scanning with Nmap

2. Service Detection Service detection of open ports

3. Vulnerability Checks:

SQL Injection

XSS

Directory Traversal

Admin Panel Exposure

Information Disclosure

4. Security Headers Check

5. Comprehensive Report - security score সহ

Installation on Kali Linux:

# প্রয়োজনীয় প্যাকেজ ইন্সটল
sudo apt update

sudo apt install nmap curl libcurl4-openssl-dev g++

# কম্পাইল এবং রান
g++ -o webscan webscan.cpp -lcurl -pthread

chmod +x webscan

./webscan your-target.com

