# Ubuntu VM Installation

## Objective
Create an Ubuntu Linux virtual machine using VirtualBox to begin building a home lab environment for IT administration, troubleshooting, and CompTIA A+ studies.

---

## Environment

### Host Machine
- Windows 11
- Intel i5-11400F
- 16GB RAM
- NVIDIA RTX 3060

### Virtualization Software
- Oracle VirtualBox

### Guest Operating System
- Ubuntu Linux

---

## Installation Steps

### 1. Installed VirtualBox
Downloaded and installed Oracle VirtualBox on Windows 11.

---

### 2. Downloaded Ubuntu ISO
Downloaded Ubuntu Desktop ISO from the Ubuntu website.

---

### 3. Created Virtual Machine
Created a new virtual machine in VirtualBox with:
- 4GB RAM
- 2 CPU cores
- 25GB virtual disk

---

### 4. Installed Ubuntu
Mounted Ubuntu ISO and completed operating system installation.

---

### 5. Tested Linux Terminal Commands

Commands practiced:

```bash
pwd
ls
mkdir
cd
touch
rm
rmdir
```

---

### 6. Updated Package Lists

```bash
sudo apt update
```

---

### 7. Upgraded Installed Packages

```bash
sudo apt upgrade
```

---

### 8. Installed Fastfetch

```bash
sudo apt install fastfetch
```

Verified installation using:

```bash
fastfetch
```

---

## Screenshots Captured

- VirtualBox installed
- Ubuntu VM created
- Ubuntu desktop
- Linux terminal commands
- Package update output
- Fastfetch installed

---

## Issues Encountered

### Neofetch Package Error
Attempted to install `neofetch` but package was unavailable in repository.

Resolved by installing `fastfetch` instead.

Additional troubleshooting documented separately.

---

## Skills Learned

- Virtual machine creation
- Linux installation
- Basic Linux filesystem navigation
- Package management with APT
- Linux software installation
- Basic troubleshooting workflow
- Documentation practices
