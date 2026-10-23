
# Lab 06 Challenge

## 1. Install and run htop
Command: sudo apt install -y htop
Run command: htop
Answer: htop displays CPU usage, memory usage, and running processes.

## 2. Apache2 version
Command: apt show apache2 | grep '^Version:'
Answer: 2.4.66-2ubuntu2.6

## 3. Installed packages
Command: apt list --installed | wc -l
Answer: 729

## 4. Run Alpine container
Command: sudo docker run --rm alpine echo "Hello from Alpine"
Answer: Hello from Alpine

## 5. Docker file paths
Key file: /etc/apt/keyrings/docker.asc
Sources file: /etc/apt/sources.list.d/docker.sources

## 6. Remove htop
Command: sudo apt remove -y htop
Verification: hash -r, then run htop.
Answer: The htop command is no longer found.

