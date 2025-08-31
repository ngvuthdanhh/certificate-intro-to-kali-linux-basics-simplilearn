# Basic Network Scanning Tutorial

## Overview
Learn how to perform a simple network scan using Nmap.

## Steps
1. Open terminal in Kali Linux
2. Identify your network interface: `ifconfig`
3. Scan local network: `nmap -sP 192.168.1.0/24`
4. Identify live hosts and open ports: `nmap -sV 192.168.1.5`
5. Document results for further analysis
