# Day 02 – Linux Architecture and Process Management 🚀

## Core Components of Linux

  ### 1. Kernel
  The Kernel is the heart of the Linux operating system. It directly communicates with the hardware and manages system resources.

  Responsibilities:
  - Process management
  - Memory management
  - Device management
  - File system management
  - CPU scheduling
  - Hardware communication
  - Security and access control

  Examples:
  - Managing RAM usage
  - Controlling CPU tasks
  - Interacting with devices like keyboard, disk, and network cards

  ---

  ### 2. Shell
  User Space is the environment where users interact with the system and applications run.

  Responsibilities:
  * Running user applications
  * Executing shell commands
  * Providing user interaction
  * Handling software utilities and services
  * Communicating with the kernel through system calls

  Examples:
  * Bash shell
  * Python applications
  * Browsers
  * Text editors

  ---
  ### 3. Init / systemd
  `init` or `systemd` is the first process that starts during the Linux boot process. Modern Linux distributions mainly use `systemd`.

  Responsibilities:

  * Initializing the operating system during boot
  * Starting and stopping services
  * Managing background processes (daemons)
  * Monitoring system services
  * Maintaining logs and service status
  * Handling system shutdown and restart processes

### Common Commands:

  ```bash id="i11j70"
  systemctl start nginx
  systemctl stop docker
  systemctl status ssh
  ```
  
  ---

# Simple Summary

| Component    | Main Responsibility                   |
| ------------ | ------------------------------------- |
| Kernel       | Manages hardware and system resources |
| User Space   | Runs applications and user processes  |
| systemd/init | Manages system startup and services   |

---

## Task
Today’s goal is to **understand how Linux works under the hood**.

You will create a short note that explains:
- The core components of Linux (kernel, user space, init/systemd)
- How processes are created and managed
- What systemd does and why it matters

This is the foundation for all troubleshooting you will do as a DevOps engineer.

---

## Expected Output
By the end of today, you should have:

- A markdown file named:  
  `linux-architecture-notes.md`

or

- A hand written set of notes (Recommended)

Your notes should be clear enough that someone new to Linux can follow them.

---

## Guidelines
Follow these rules while creating your notes:

- Explain **process states** (running, sleeping, zombie, etc.)
- List **5 commands** you would use daily
- Keep it **short and practical** (under 1 page)
- Use bullet points and short headings

---

## Resources
You may refer to:

- Linux `man` pages (`ps`, `top`, `systemctl`)
- Official systemd docs
- Your class notes

Avoid copying/pasting AI Generated content.
Focus on understanding.

---

## Why This Matters for DevOps
Linux is the base OS for almost every production system.

If you know how processes and systemd work, you can:
- Debug crashed services faster
- Fix CPU/memory issues
- Understand logs and service restarts confidently

This knowledge saves hours during incidents.

---

## Submission
1. Fork this `90DaysOfDevOps` repository  
2. Navigate to the `2026/day-02/` folder  
3. Add your `linux-architecture-notes.md` file  
4. Commit and push your changes to your fork  

---

## Learn in Public
Share your Day 02 progress on LinkedIn:

- Post 2–3 lines on what you learned about Linux internals
- Share one systemd command you found useful
- Optional: screenshot of your notes

Use hashtags:
#90DaysOfDevOps
#DevOpsKaJosh
#TrainWithShubham


Happy Learning  
**TrainWithShubham**