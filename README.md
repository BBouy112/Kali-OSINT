# KALI-OSINT

**[KALi-OSINT]** ![Screenshot 2023-12-31 221246](https://github.com/BBouy112/Kali-OSINT/assets/155302174/a044dfbf-776e-49c7-a82a-a2aa39abae81)

# The Project

KALI-OSINT is a customized Kali Linux-based ISO image with pre-installed packages and scripts with extra OSINT tools. The idea behind this project is to combine a portion of Kali Linux tools and some OSINT scripts that are freely available on GitHub. 

I started KALI-OSINT as an educational and fun project to dive deeply into Kali Linux OSINT strategy. My idea was to create a VM with some Kali generic tools and pre-installed OSINT scripts. I learned a lot, and although it may not seem like it at first glance, configuring XFCE menues and correctly placing Python scripts and their dependencies has its challenges when embedding them in an installable ISO.  

However, I am not the one that got this idea first. I was inspired by [Trace Labs VM](https://github.com/tracelabs/tlosint-live) and [CyberPunkOS](https://github.com/cyberpunkOS/CyberPunkOS).

# Requirements

The official Kali documentation states that you will need a bootable USB drive or virualization tool to run the distro. A minimum of 3GB of RAM and 20GB of hard disk is required. 

# Download

Download the OVF file from Cloud Storage mega (https://mega.nz/folder/lHcTVICZ#Sjr2STWriFGdzXiH-SHdnQ) and install it on your preferred virtualization tool. I have tested it on VMWare Workstation 16 Pro. The file size is of almost 14.1 GB.

## Frameworks

- [LinkScope](https://github.com/AccentuSoft/LinkScope_Client)
- [Maltego](https://www.maltego.com/)
- [Netcat](https://netcat.sourceforge.net/)
- [Nmap](https://nmap.org/download.html)
- [Recon-ng](https://github.com/lanmaster53/recon-ng)
- [Spiderfoot](https://github.com/smicallef/spiderfoot)
- [Tcpdump](https://github.com/the-tcpdump-group/tcpdump)
- [theHarvester](https://github.com/laramies/theHarvester)
- [Wireshark](https://github.com/wireshark/wireshark)
- [Knock](https://github.com/guelfoweb/knock.git)
- [DnsEnum](https://github.com/fwaeytens/dnsenum.git)
- [MOSINT](https://github.com/alpkeskin/mosint.git)
- [OWASP MARYAM]( https://github.com/saeeddhqan/Maryam.git)



## OSINT

## Kali Linux Usual Application
s
- Accessories
- Development
- Graphics
- Internet
- Multimedia
- Office
- Other
- System

- # A note on Python scripts: Kali is retiring pip install

In the [blog post](https://www.kali.org/blog/python-externally-managed/) from 6th of July this year, Kali Linux distro developers announced that Python packages outside the package manager should be in the future installed in a virtual environment. Though pip install still works, it wont be for too long. With the next Python3.12, Kali will officially retire it. 

# Feedback

If you have any feedback,suggestions or comments please reach out to me at owaiskhan.corvitccna24@gmail.com

# Disclaimer

**Educational Purpose Only: This software is provided for educational purposes only. It is not intended for production use or any critical applications.**

By using this software, you understand and agree that:

- This software is for educational purposes and should not be used in any mission-critical or production environments.

- The software may contain errors, bugs, or vulnerabilities, and should not be relied upon for any real-world applications.

- You are solely responsible for any consequences, including but not limited to data loss, damage, or security breaches, that may occur as a result of using this software.

- The authors and contributors of this software are not responsible for any damages or losses, direct or indirect, that may result from the use of this software.

Please use this software responsibly and with the understanding that it is for educational purposes only. If you require a production-ready solution, it is recommended to seek professional software or services.

**You use this software at your own risk.**


