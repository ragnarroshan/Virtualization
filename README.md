# Virtualization
## Ex.3(A-C) Virtualization: Installation and Configuration of Oracle VirtualBox & Kali Linux, and Execution of Linux Commands

## NAME: kirthick roshan j

## REG NO: 212223040097

## Aim:

To set up a virtualized environment using Oracle VirtualBox, install Kali Linux as a guest OS, and execute fundamental Linux commands.

## 3.a) Installation and Configuration of Oracle VirtualBox

## Aim:

To install and configure Oracle VM VirtualBox.

## Pre-requisites:

Machine with Internet access

Minimum 4 GB RAM

Sufficient storage space

## Steps:

1.Download Oracle VM VirtualBox:

* Visit Oracle VirtualBox Official Site
  
* Download installer for your OS (Windows/macOS/Linux).

2.Install Oracle VM VirtualBox (Example: Windows):

* Launch Installer → Allow Changes → Click Next.
  
* Choose Installation Options → Click Next.
  
* Accept Network Interface Warning → Click Yes.
  
* Click Install.
  
* Finish Installation and Launch VirtualBox.

3.Configure VirtualBox:

* Open VirtualBox.
  
* Click New → Name VM → Select Type (Linux/Windows) and Version.
  
* Allocate:
  
     * Minimum 2 GB RAM
       
     * Create Virtual Hard Disk (20 GB recommended).
       
* Start Virtual Machine and provide ISO to install OS.

## Result:

Thus, Oracle VM VirtualBox was installed successfully.

## 3.b) Installation and Configuration of Kali Linux

## Aim:

To install and configure Kali Linux in Oracle VirtualBox.

## Pre-requisites:

Oracle VM VirtualBox Installed

4 GB RAM and 20 GB Storage Minimum

Kali Linux ISO image

## Steps:

1.Download Kali Linux ISO:

* Visit Kali Linux Official Site
  
* Download 64-bit ISO (Installer version).
  
2.Create a New Virtual Machine:

* Open VirtualBox → Click New.
  
* Name: "Kali Linux" → Type: Linux → Version: Debian (64-bit).
  
3.Allocate Memory:

* Minimum 2 GB RAM (recommended 4 GB).
  
4.Create Virtual Hard Disk:

* Select VDI (VirtualBox Disk Image).
  
* Choose Dynamically allocated.
  
* Set Disk size to 20 GB or more.
  
5.Configure ISO Image:

* Settings → Storage → Controller: IDE → Empty CD → Choose Disk File → Select Kali Linux ISO.
  
6.Start Installation:

* Boot Virtual Machine → Choose Graphical Install.
  
* Set Language, Region, Keyboard.
  
* Configure Network → Set Hostname (e.g., kali).
  
* Set root password.
  
* Disk Partitioning: Use entire disk → All files in one partition.
  
* Install System → Install GRUB Bootloader → Finish Installation.
  
7.Login to Kali Linux:

* Use root credentials.
  
8.(Optional) Install Guest Additions:

* Devices → Insert Guest Additions CD Image → Follow steps inside Kali.
  
## Snapshots:

AWS Account Creation Snapshot

Snapshot 1: Installing Oracle VirtualBox

<img width="1919" height="999" alt="image" src="https://github.com/user-attachments/assets/dde9d6d2-9df8-43b8-8a6d-11aaa8cdc204" />

Snapshot 2: Kali Running in Virtual

<img width="1603" height="974" alt="image" src="https://github.com/user-attachments/assets/38a29414-8de9-4782-a5d0-3188d89b2255" />

## 3.c) Execution of Linux Commands in Kali

## About Linux:

* Open-source operating system.
  
* Kernel manages communication between hardware and software.
  
* Commands are case-sensitive.
    
## Linux Commands:

1.ls Command

The ls command is used to display a list of content of a directory.

## Syntax:

     ls

<img width="714" height="70" alt="image" src="https://github.com/user-attachments/assets/746061eb-22dd-41ea-8af7-2a78ffaf01db" />

2.pwd Command

The pwd command is used to display the location of the current working directory.

## Syntax:

   pwd

<img width="193" height="67" alt="image" src="https://github.com/user-attachments/assets/73496655-b33e-4c04-855c-874225972999" />

3.mkdir Command

The mkdir command is used to create a new directory under any directory.

## Syntax:

    mkdir <directory_name>

<img width="364" height="49" alt="image" src="https://github.com/user-attachments/assets/23d4bdcc-05c3-497b-9364-4d33a5fd228e" />

4.rmdir Command

The rmdir command is used to delete a directory.

## Syntax:

  rmdir <directory_name>

<img width="308" height="50" alt="image" src="https://github.com/user-attachments/assets/aed07189-4fba-4042-b46c-6208e5f36f11" />

5.cd Command The cd command is used to change the current directory

## Syntax:

    cd <directory_name>

<img width="223" height="42" alt="image" src="https://github.com/user-attachments/assets/0b95bf2d-68f3-424c-97bc-59c04777138a" />

6.cat Command

The cat command is a multi-purpose utility in the Linux system. It can be used to create a file, display content ofthe file, copy the content of one file to another file, and more.

## Syntax:

    cat [options] [file_name]

<img width="632" height="73" alt="image" src="https://github.com/user-attachments/assets/0b2f687d-0639-4f0e-843d-985e0e1487b0" />

<img width="866" height="71" alt="image" src="https://github.com/user-attachments/assets/8b324585-79d9-4ffe-a9d5-2314bfcf726e" />

7.cp Command

The cp command is used to copy a file or directory.

## Syntax:

   cp [source] [destination]

<img width="300" height="52" alt="image" src="https://github.com/user-attachments/assets/81bb076f-561f-4925-a73d-d3f2504d6d25" />

<img width="831" height="62" alt="image" src="https://github.com/user-attachments/assets/fbf1d24b-a3be-443c-88f8-25071086ac91" />

8.mv Command

The mv command is used to move a file or a directory form one location to another location.

## Syntax:

    mv [source] [destination]

<img width="293" height="52" alt="image" src="https://github.com/user-attachments/assets/64010b26-45d3-4dd1-b437-914c4478671c" />

<img width="339" height="64" alt="image" src="https://github.com/user-attachments/assets/89a828b4-d1f8-44c9-93aa-df99f321a64e" />

9.touch Command

Create empty file.

## Syntax:

    touch [filename]

<img width="185" height="44" alt="image" src="https://github.com/user-attachments/assets/a1ff3c9d-71d6-44c5-94d4-c7f6689cb9aa" />

10.vi Command

Edit file contents using editor.

## Syntax:

   vi [filename]

<img width="192" height="51" alt="image" src="https://github.com/user-attachments/assets/938d9d1d-8ee2-436d-b89e-7fa5244a96a3" />

## Result:

Thus, various Linux commands were executed successfully in Kali Linux virtual machine.


