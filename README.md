# Windows-server-2025-on-Apple-Silicon
In this repository, I am going to show you how to virtualize Windows Server 2025 on Apple Silicon (ARM64) processors.

<img src="https://github.com/AnderMendoza/AnderMendoza/raw/main/assets/line-neon.gif" width="100%">


The first step will be to create the ISO from <a href="https://uupdump.net/known.php?q=windows+server+arm64"> UUP Dump </a>. We need to install it precisely. I recommend installing it on Windows since it has given me quite a few problems on macOS.

<br>
</br>

We download the marked option.

<img src/img/1.png />

Next

2.png

And next again.

3.png

Click on "Create download package"

4.png

We unzip the file.

5.png

Run this file as administrator.

6.png

If you see this message, don't worry. Run it, it doesn't have malware.

7.png

If you get an error when running the script, open a new cmd, copy the path, and run it from that new cmd.

<br>
</br>

Press Z

8.png

We wait for it to finish.

If you encounter any other errors or it gets stuck in a loop while installing the ISO, I recommend disabling Windows Defender. I faced that issue and resolved it this way.

Move the ISO you downloaded to an external hard drive or upload it to the cloud.

9.png

Download <a href="https://mac.getutm.app/"> UTM </a> from the oficial website. 

Create a new virtual machine.

10.png

Virtualize.

11.png

Select Windows.

12.png

Select search.

13.png

Select the ISO that we downloaded.

14.png

Configure your hardware and start the VM.

Once started, proceed with the installation of the operating system.

And welcome to your virtual machine Windows Server 2025 on Apple Silicon processors (M1, M2, M3, M4).

15.png
