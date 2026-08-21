Part 1 – Creating a Windows Server VM
Open VirtualBox

Start VirtualBox from your desktop or applications menu.

Create New VM

Click New → Name: Windows_Server

Type: Microsoft Windows

Version: Windows 2019 (64-bit) or Windows 2022 (64-bit)

Allocate Resources

RAM: 4096 MB (minimum)

CPU: 2 Cores (if available)

Create Virtual Hard Disk

Select VDI (VirtualBox Disk Image) → Dynamically allocated → Size: 50 GB

Attach ISO

Go to Settings → Storage

Click the empty optical drive → Choose your Windows Server ISO file.

Start VM & Install Windows

Follow Windows Server installation wizard.

Username: Admin

Password: P@ssw0rd123

Enable Network

In VirtualBox → Settings → Network → Adapter 1: Bridged Adapter or NAT (as instructed).

Take a Snapshot

Name: Clean Install – Windows Server

Part 2 – Creating an Ubuntu Server VM
Create New VM

Name: Ubuntu_Server

Type: Linux

Version: Ubuntu (64-bit)

Allocate Resources

RAM: 2048 MB (minimum)

CPU: 2 Cores

Create Virtual Hard Disk

VDI → Dynamically allocated → Size: 30 GB

Attach ISO

Settings → Storage → Empty optical drive → Select ubuntu-22.04-live-server-amd64.iso

Start VM & Install Ubuntu

Language: English

Install OpenSSH Server (will be useful in later labs)

Username: admin

Password: P@ssw0rd123

Enable Network

Same method as in Windows VM.

Take a Snapshot

Name: Clean Install – Ubuntu Server
