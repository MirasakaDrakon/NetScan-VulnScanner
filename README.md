# NetScan-VulnScanner
NetScan - This is Nmap based utility for Termux/Linux. Uses Nmap plugin "vulners" for scanning

WARNING! This tool only for:
- Legal and authorized use
- Educational and research purposes
- Penetration testing with explicit permission

This project is distributed under the GNU/GPL Open‑Source License.
You are free to modify, study, and redistribute the code under the same license terms.

Features:

+Vulnerablity scan

+Whois Lookup

+SQLMap Integration

+DNS Reverse Lookup

+Traceroute

+DirBuster

📌 How to activate?

1. Copy the script to your Termux directory


2. Grant execution permissions:

chmod 700 scan.sh


3. Start the tool:

bash scan.sh

or

./scan.sh



⚠️ IMPORTANT

Make sure you have Nmap and all required packages installed before running the tool.

Install everything with one command:

pkg update && pkg upgrade \
&& pkg install coreutils python python-pip bash nmap dnsutils bind-tools net-tools inetutils traceroute whois dirb bc \
&& pip install sqlmap
