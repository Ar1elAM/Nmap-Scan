# Nmap-Scan
Still work in progress

Empty for now

I'm lazy and I don't want to type "nmap ip" all the time, the script will be to run a simple nmap scan to a target IP, capture open ports, offer the user a chance for a custom nmap scan(-sS/-sN/-sF)
or just run a -A scan.

if port 80 is open, offer gobuster.
if port 22 is open, offer enum4linux and hydra.
