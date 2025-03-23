Auto-scaling is an important feature in modern cloud computing that helps adjust resources automatically based on demand. The main idea is to create or remove virtual machines (VMs) depending on how much the CPU is being used. For example, if CPU usage goes above 75%, more VMs are added, and if it drops, extra VMs are removed. This helps keep things running smoothly and makes sure that resources are used efficiently, so companies only pay for what they actually use.
dependencies required:sudo apt install apt-transport-https ca-certificates gnupg curl –y,curl -fsSL https://packages.cloud.google.com/apt/doc/apt-key.g pg | sudo gpg --dearmor -o /usr/share/keyrings/cloud.google.gpg, sudo apt update apt install google-cloud-cli -y


