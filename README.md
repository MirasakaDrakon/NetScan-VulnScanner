# NetScan-VulnScanner
NetScan - This is Nmap based utility for Termux/Linux. Uses Nmap plugin "vulners" for scanning

DISCLAIMER!!
WARNING! This tool only for:
- Legal and authorized use
- Educational and research purposes
- Penetration testing with explicit permission

This project is distributed under the GNU/GPL Open‑Source License.
You are free to modify, study, and redistribute the code under the same license terms.

This program is distributed WITHOUT ANY WARRANTY; without even the implied warranty of
MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE. See the GNU General Public License
for more details.

You should have received a copy of the GNU General Public License along with this program.
If not, see https://www.gnu.org/licenses/gpl-3.0.txt . END OF DISCLAIMER.

[+] Features:

+Vulnerablity scan

+Whois Lookup

+SQLMap Integration

+DNS Reverse Lookup

+Traceroute

+DirBuster

[?] How to activate?

1. Copy the script to your Termux directory


2. Grant execution permissions:

chmod 700 scan.sh


3. Start the tool:

bash scan.sh

or

./scan.sh



!IMPORTANT!

Make sure you have Nmap and all required packages installed before running the tool.

Install everything with one command:

pkg update && pkg upgrade \
&& pkg install coreutils python python-pip bash nmap dnsutils bind-tools net-tools inetutils traceroute whois dirb bc \
&& pip install sqlmap
