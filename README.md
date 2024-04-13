# TryHackMe
# Task 1 Deploy
  No answer needed
# Task 2 Introduction
  1- What networking constructs are used to direct traffic to the right application on a server?
      ports
  2- How many of these are available on any network-enabled computer?
      65535
  3-  How many of these are considered "well-known"? (These are the "standard" numbers mentioned in the task)
      1024

# Task 3 Nmap Switches
  1-What is the first switch listed in the help menu for a 'Syn Scan' (more on this later!)?
      -sS
  2- Which switch would you use for a "UDP scan"?
      -sU
  3- If you wanted to detect which operating system the target is running on, which switch would you use?
      -o
  4- Nmap provides a switch to detect the version of the services running on the target. What is this switch?
      -sV
  5- The default output provided by nmap often does not provide enough information for a pentester. How would you increase the verbosity?
      -v
  6- Verbosity level one is good, but verbosity level two is better! How would you set the verbosity level to two?
      -vv
  7- What switch would you use to save the nmap results in three major formats?
      -oA 
  8- What switch would you use to save the nmap results in a "normal" format?
      -oN
  9- A very useful output format: how would you save results in a "grepable" format?
      -oG
  10- How would you activate this setting?
      -a
  11- How would you set the timing template to level 5?
      -t5
  12- How would you tell nmap to only scan port 80?
      -p 80
  13- How would you tell nmap to scan ports 1000-1500?
      -p 1000-1500
  14- How would you tell nmap to scan all ports?
      -p-
  15- How would you activate a script from the nmap scripting library (lots more on this later!)?
      --script
  16- How would you activate all of the scripts in the "vuln" category?
      --script=vuln
# Task 4 Overview
  No answer needed
# Task 5 TCP Connect Scans
  1- Which RFC defines the appropriate behaviour for the TCP protocol?
      RFC 9293
  2- If a port is closed, which flag should the server send back to indicate this?
      RST

# Task 6 SYN Scans
  1- There are two other names for a SYN scan, what are they?
      Half-open,Stealth
  2- Can Nmap use a SYN scan without Sudo permissions (Y/N)?
      N
# Task 7 UDP Scans
