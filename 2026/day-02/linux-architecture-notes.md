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