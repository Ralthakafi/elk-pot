# elk-pot
The main repository for the Elk-pot project. 
Honeypots
ELK-Pot uses Docker and Docker-Compose to bring up the following honeypots, automatically, with no configuration or extra steps necessary.

contpot - an ICS honeypot with the goal to collect intelligence about the motives and methods of adversaries targeting industrial control systems
cowrie - SSH/Telnet honeypot, originally based on Kippo, using the DockerHub image k0st/cowrie
dionaea, the dionaea honeypot, using the DockerHub image andrewmichaelsmith/dionaea
Requirements
ELK-Pot will run on any 64-bit computer that has git, Docker, and Docker-Compose installed and running. I've developed this in Linux, so it's been fully tested in Debian, Ubuntu, RHEL, and CentOS. I'd expect it to work pefectly under Mac OSX too, and while I haven't tried in Windows "it should work" since it all runs in Docker with no modifications. Give it a try and let me know if it works for you, pull requests welcome!

Usage
Install Docker
Install Docker-Compose
