
# Week 1 – Building My Professional Environment

#Student Information

* Name: Justine Mark R. Gahi
* Course: Bachelor of Science in Information Technology (BSIT)
* Section: BSIT 4-A 
* Date: August 8, 2026

# Objectives

1. Set up a fully functional, isolated workstation equipped with virtualization software, system administration tools, and text editors required for **ITEP 414 – System Administration and Maintenance**.
2. Establish professional online identities on GitHub and LinkedIn to document laboratory progress and build a career-ready technical portfolio.
3. Successfully create and structure the main course portfolio repository (`BSIT-SystemAdministration-Portfolio`) following strict directory conventions.
4. Document technical processes and troubleshoot software installation issues using standard Markdown formatting.

---

# Software Installed

* **Git:** Command-line version control system for tracking changes and managing infrastructure scripts.
* **GitHub Desktop:** Graphical user interface for streamlined repository management and Git workflows.
* **Visual Studio Code:** Primary code and configuration text editor with Markdown preview and extension capabilities.
* **Oracle VM VirtualBox:** Type-2 hypervisor used to create and manage local virtual machines.
* **Ubuntu Server / Desktop ISO:** Linux OS installer image for hands-on Linux system administration tasks.
* **Windows 11 Enterprise Evaluation ISO:** Windows Server/Client installer image for Windows environment administration.
* **Google Chrome / Microsoft Edge:** Web browsers for accessing cloud consoles, documentation, and professional platforms.

---

# Professional Accounts

* **GitHub:** `https://github.com/[YourGitHubUsername]`
* **LinkedIn:** `https://www.linkedin.com/in/[YourLinkedInUsername]`

---

# Installation Screenshots

### Software Installation & Launch

* **Git Installation Verification:** 
*Terminal showing `git --version` command output alongside Notepad with student name.*
* **GitHub Desktop:** 
*GitHub Desktop application running with student name visible in Notepad.*
* **Visual Studio Code:** 
*VS Code interface running with active workspace and student name visible in Notepad.*
* **VirtualBox Hypervisor:** 
*Oracle VM VirtualBox Manager open alongside Notepad displaying student credentials.*
* **Downloaded ISO Images (Ubuntu & Windows 11 Evaluation):** 
*File Explorer showing downloaded `.iso` files with Notepad overlay.*

### Account Setup Screenshots

* **GitHub Profile Page:** 
*Completed GitHub profile showing bio, photo, location, and customized profile README.*
* **LinkedIn Profile Page:** 
*Completed LinkedIn profile showing headline, photo, education (LSPU), and skills.*

---

# Challenges Encountered

1. **Hardware Virtualization (VT-x/AMD-V) Disabled in BIOS/UEFI**
* *Problem:* Upon attempting to configure a test 64-bit Virtual Machine in VirtualBox, an error was thrown indicating hardware acceleration was disabled on the host system.
* *Solution:* Rebooted the host computer, entered the UEFI/BIOS menu during bootup (pressing `F2`/`Del`), enabled **Intel Virtualization Technology (VT-x)** under the Advanced CPU Configuration tab, saved the settings, and restarted the machine.


2. **Git SSH Authentication Error (`Permission denied (publickey)`)**
* *Problem:* When attempting to push the local repository to GitHub via the terminal, the remote connection failed due to missing SSH authorization keys.
* *Solution:* Generated a new SSH key pair using `ssh-keygen -t ed25519 -C "student.email@lspu.edu.ph"`, copied the public key string from `id_ed25519.pub`, and added it under **GitHub > Settings > SSH and GPG Keys**.


3. **Missing PATH Environment Variable for VS Code Command Line Interface**
* *Problem:* Executing the command `code .` inside Git Bash failed to open Visual Studio Code in the current working directory.
* *Solution:* Re-ran the VS Code setup installer, selected the option **"Add to PATH (requires shell restart)"**, completed the setup, and restarted the terminal session.



---

# Reflection

Setting up a dedicated, structured development workstation during Week 1 of **ITEP 414: System Administration and Maintenance** served as a vital introduction to the discipline required in IT infrastructure management. System administrators must prioritize precision, proper documentation, and clean workspace organization before deploying complex systems. Preparing virtualization tools like VirtualBox along with ISO images for Linux and Windows allows for safe, isolated experimentation without risking host OS stability.

Integrating version control through Git and GitHub directly into the learning process establishes industry-standard habits early on. In modern enterprise environments, infrastructure settings, deployment scripts, and automation routines are treated as code (Infrastructure as Code). Using Git guarantees that configuration changes can be audited, tracked, and safely rolled back if errors occur. Furthermore, establishing professional presence on LinkedIn and maintaining an active GitHub profile transforms weekly academic tasks into a verifiable, public portfolio of practical skills.

Troubleshooting hardware settings such as UEFI virtualization and SSH key authorization reinforced the reality that environment setup is rarely a single-click process. Overcoming these initial technical hurdles builds critical problem-solving skills necessary for a future System Administrator tasked with managing servers, automating tasks, and maintaining continuous operational stability.

---

# References

* **Git Official Documentation:** [https://git-scm.com/doc](https://git-scm.com/doc)
* **GitHub Docs - Connecting with SSH:** [https://docs.github.com/en/authentication/connecting-to-github-with-ssh](https://docs.github.com/en/authentication/connecting-to-github-with-ssh)
* **Oracle VM VirtualBox User Manual:** [https://www.virtualbox.org/manual/UserManual.html](https://www.virtualbox.org/manual/UserManual.html)
* **Ubuntu Server Documentation:** [https://canonical.com/ubuntu/server/docs](https://www.google.com/search?q=https://canonical.com/ubuntu/server/docs)
* **Microsoft Evaluation Center (Windows 11 Enterprise):** [https://www.microsoft.com/en-us/evalcenter/](https://www.microsoft.com/en-us/evalcenter/)
* **Laguna State Polytechnic University - LSPU Course Module:** *ITEP 414 – System Administration and Maintenance (Week 1 Module by John Randolf M. Penaredondo, MIT)*
