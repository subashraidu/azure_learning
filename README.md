# azure_learning

azure login : venkatachallamsurendra@outlook.com
password : ther@6

 linux command to check opearing system details
1. uname -a
2. cat /etc/os-release


Linux SandboxHost-638649245973367321 5.10.102.2-microsoft-standard #1 SMP Mon Mar 7 17:36:34 UTC 2022 x86_64 x86_64 x86_64 GNU/Linux

This output is from the uname -a command and provides several details about your Linux system. Here’s a breakdown of each part:

    Linux: This indicates the kernel name.

    SandboxHost-638649245973367321: This is the hostname of the system. It typically identifies the machine on the network.

    5.10.102.2-microsoft-standard: This is the kernel version. The version number indicates the specific release of the Linux kernel you are running. The "microsoft-standard" part suggests that this kernel is a version tailored for running on Windows, likely under WSL (Windows Subsystem for Linux).

    #1 SMP Mon Mar 7 17:36:34 UTC 2022: This part includes several pieces of information:
        #1: This indicates the build number of the kernel.
        SMP: Stands for Symmetric Multi-Processing, indicating that the kernel supports multiple processors.
        Mon Mar 7 17:36:34 UTC 2022: This is the date and time when the kernel was built.

    x86_64 x86_64 x86_64: This indicates the architecture of the machine. It shows that you are running a 64-bit version of Linux on an x86 architecture.

    GNU/Linux: This indicates that the system uses the GNU operating system tools alongside the Linux kernel.

Overall, this output tells you that you're running a 64-bit Linux system, specifically a Microsoft-optimized kernel, likely in a virtualized environment like WSL.



NAME="Common Base Linux Mariner"
VERSION="2.0.20240829"
ID=mariner
VERSION_ID="2.0"
PRETTY_NAME="CBL-Mariner/Linux"
ANSI_COLOR="1;34"
HOME_URL="https://aka.ms/cbl-mariner"
BUG_REPORT_URL="https://aka.ms/cbl-mariner"
SUPPORT_URL="https://aka.ms/cbl-mariner"



This output is from the /etc/os-release file, which provides details about the Linux distribution. Here's a breakdown of each field:

    NAME="Common Base Linux Mariner": This indicates the name of the operating system. In this case, it's "Common Base Linux Mariner" (CBL-Mariner).

    VERSION="2.0.20240829": This specifies the version of the operating system. Here, it is version 2.0 with a build date or identifier of 20240829.

    ID=mariner: This is a short identifier for the operating system, used by scripts and applications to determine the OS type.

    VERSION_ID="2.0": This provides a more concise version identifier, which is "2.0" in this case.

    PRETTY_NAME="CBL-Mariner/Linux": This is a human-readable name for the OS that can be displayed in user interfaces.

    ANSI_COLOR="1;34": This indicates the color code used in terminal outputs. The code "1;34" typically corresponds to a blue color.

    HOME_URL="https://aka.ms/cbl-mariner": This URL leads to the official homepage for CBL-Mariner, where you can find more information about the distribution.

    BUG_REPORT_URL="https://aka.ms/cbl-mariner": This URL is provided for reporting bugs related to the operating system.

    SUPPORT_URL="https://aka.ms/cbl-mariner": This URL directs users to support resources for CBL-Mariner.

Overall, this output tells you that you are using CBL-Mariner, a Linux distribution developed by Microsoft, and provides various resources for further information and support.

