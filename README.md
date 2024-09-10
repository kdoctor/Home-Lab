# Home Lab Project

## Objective

This project involves setting up a virtual home lab environment for learning cybersecurity, focusing on detection and response to cyberattacks. The lab will include two Windows targets, a Kali Linux attacker machine, and a Windows system running a Security Information and Event Management (SIEM) solution. This will simulate real-world attack scenarios, allowing analysis of logs and honing defensive skills.

### Skills Learned

- Configuring the SIEM to collect logs from multiple machines
- Proper memory and storage allocation 
- Configuring VirtualBox's internal, NAT, and bridged networks
- Creating and managing ISO files for different systems

### Tools Used

- VirtualBox
- Windows ISO creation tools
- Kali Linux
- SIEM software (e.g., Splunk, Elasticsearch)

## Steps
drag & drop screenshots here or use imgur and reference them using imgsrc

1. Download <a href="https://www.virtualbox.org/">VirtualBox</a>

- Navigate to the VirtualBox website and download the latest version.
- Install the version based on your host system.
  
2. Create ISO Images for Windows Targets and Monitoring Machine

- Visit the <a href="https://www.microsoft.com/en-us/software-download/windows10">Microsoft Evaluation Center</a> to download evaluation versions of Windows.
- Use the Media Creation Tool to generate ISO images for both Windows target systems and the Windows machine running the SIEM.
3. Download Kali Linux

- Go to the Kali Linux download page and download the ISO for the attacker machine.
4. Set Up Virtual Machines

- Open VirtualBox, create a new virtual machine for each Windows target and the monitoring system.
- For each, allocate memory (2GB or more), virtual storage (20GB or more), and attach the respective ISO files.
- Create another virtual machine for the Kali Linux attacker with similar settings.
5. Install Windows and Kali Linux

- Start each virtual machine and go through the operating system installation process.
- Ensure all machines are on the same virtual network within VirtualBox for communication.
5. Configure the SIEM

- Install your chosen SIEM on the Windows monitoring system (e.g., Splunk, ELK).
- Configure it to collect logs from both Windows targets.

