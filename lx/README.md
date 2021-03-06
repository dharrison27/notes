# Linux

<!-- Sources -->
[CLKF]: https://github.com/jasper-zanjani/notes/tree/master/sources/clkf.md "Cannon, Jason. _Command Line Kung Fu_."
[Eckert]: https://github.com/jasper-zanjani/notes/blob/master/sources/lglc.md 'Eckert, Jason. _Linux+ Guide to Linux Certification_. Course Technology, 2012'
[Haeder]: # 'Haeder, Adam. _LPI Linux Certification in a Nutshell_. 2010.'
[L5PMT-cpu]: https://subscription.packtpub.com/video/programming/9781838559250/p1/video1_2/cpu-run-queue-and-load-average 'Linux 5 Performance Monitoring and Tuning: "CPU - Run Queue and Load Average"'
[L5PMT-disk]: https://subscription.packtpub.com/video/programming/9781838559250/p1/video1_5/disk-io-operations-on-linux 'Linux 5 Performance Monitoring and Tuning: "Disk IO Operations on Linux"'
[L5PMT-glances]: https://subscription.packtpub.com/video/programming/9781838559250/p1/video1_3/glances-tool 'Linux 5 Performance Monitoring and Tuning: "Glances Tool"'
[L5PMT-memory]: https://subscription.packtpub.com/video/programming/9781838559250/p1/video1_4/memory-and-swap-management-on-linux 'Linux 5 Performance Monitoring and Tuning: "Memory and Swap Management on Linux"'
[L5PMT-network]: https://subscription.packtpub.com/video/programming/9781838559250/p1/video1_6/monitoring-and-understanding-network 'Linux 5 Performance Monitoring and Tuning: "Monitoring and Understanding Network"'
[L5PMT-subsystem]: https://subscription.packtpub.com/video/programming/9781838559250/p2/video2_1/subsystem-analysis-with-vmstat 'Linux 5 Performance Monitoring and Tuning: "Subsystem Analysis with vmstat"'
[LPM 231 Regolith Linux]: www.linux-magazine.com/Issues/2020/231 '"Timely Tiling: Exploring the i3 tiling window manager with Regolith Linux". _Linux Pro Magazine_. Issue 231'
[LXF 258]: https://www.linuxformat.com/archives?issue=258 '"Linux distribution reviews: Clear Linux 31530" _Linux Format_ 258'
[Schatz]: http://www.volkerschatz.com/noise/alsa.html "www.volkerschatz.com: \"A close look at ALSA\""
[Sec+ Lab]: https://pts.measureup.com/web/index.php#dashboard.php "Practice Lab: CompTIA Security+ (SY0-501)"
[Sobell]: https://github.com/jasper-zanjani/notes/blob/master/sources/pgl.md 'Sobell, Mark. _Practical Guide to Linux_. 2017.'
[http://www.linux-magazine.com/Issues/2017/197/Command-Line-bluetoothctl#article_i1]: http://www.linux-magazine.com/Issues/2017/197/Command-Line-bluetoothctl#article_i1 "Linux Magazine: \"Blue Control\""
[https://coderwall.com/p/kq9ghg/yakuake-scripting]: https://coderwall.com/p/kq9ghg/yakuake-scripting "coderwall.com: \"Yakuake scripting\""
[https://computingforgeeks.com/connect-to-bluetooth-device-from-linux-terminal/]: https://computingforgeeks.com/connect-to-bluetooth-device-from-linux-terminal/ "Computing for Geeks: \"How to connect to Bluetooth device from Linux terminal\""
[https://devconnected.com/user-administration-complete-guide-on-linux/#Setting_an_account_expiration_date_easily]: https://devconnected.com/user-administration-complete-guide-on-linux/#Setting_an_account_expiration_date_easily "devconnected.com: \"User administration complete guide on Linux\""
[https://docs.fedoraproject.org/en-US/quick-docs/getting-started-with-virtualization/]: https://docs.fedoraproject.org/en-US/quick-docs/getting-started-with-virtualization/ "Fedora Docs: \"Getting started with virtualization\""
[https://opensource.com/article/19/10/namespaces-and-containers-linux]: https://opensource.com/article/19/10/namespaces-and-containers-linux 'opensource.com - "Demistifying namespaces and containers in Linux"'
[https://opensource.com/article/19/8/introduction-bpftrace]: https://opensource.com/article/19/8/introduction-bpftrace "opensource.com: \"An introduction to bpftrace for Linux\""
[https://superuser.com/questions/1196241/how-to-remap-caps-lock-on-wayland]: https://superuser.com/questions/1196241/how-to-remap-caps-lock-on-wayland 'superuser.com - "How to remap CAPS LOCK on Wayland"'
[https://tools.kali.org/information-gathering/hping3]: https://tools.kali.org/information-gathering/hping3 "tools.kali.org: \"hping3 - Active Network Smashing Tool\""
[https://vitux.com/how-to-change-cursor-size-on-ubuntu-desktop/]: https://vitux.com/how-to-change-cursor-size-on-ubuntu-desktop/ 'vitux.com: "Change cursor size on Ubuntu through the command line"'
[https://vitux.com/how-to-install-and-configure-samba-on-ubuntu/]: https://vitux.com/how-to-install-and-configure-samba-on-ubuntu/ "vitux.com: \"How to Install and Configure Samba on Ubuntu\""
[https://www.networkworld.com/article/3433865/how-to-rename-a-group-of-files-on-linux.html#tk.rss_linux]: https://www.networkworld.com/article/3433865/how-to-rename-a-group-of-files-on-linux.html#tk.rss_linux "networkworld.com: \"How to rename a group of files on Linux\""
[ULSAH]: # 'Nemeth, Evi. _Unix and Linux System Administration Handbook, 5th ed._'

- [Commands](#linux-commands)
- [Configs](#linux-configs)

###### Tasks
- Set up SSH server on WSL
- [**Set custom resolution on a VM**](#custom-resolution)
- [Bash scripting](#bash-scripting)
- [Diagnosing network problems](#diagnosing-network-problems)
- [Distros](#linux-distributions-and-desktop-environments)
- [Samba](#samba)
- [X forwarding](#x-forwarding)

###### Concepts
<!-- Concepts -->
[AppArmor]: # 'AppArmor&#10;MAC system developed by Canonical, supported by Debian and Ubuntu&#10;Nemeth, Evi. _Unix and Linux System Administration Handbook, 5th ed._: 87'
[Autotools]: # "GNU autotools is a collection of three packages: `autoconf`, `automake`, and `libtool`"
[ProcFs]: # 'ProcFs&#10;Special filesystem in Unix-like operating systems that presents information about processes and other system information in a hierarchical file-like structure, typically mapped to /proc at boot time.&#10;"procfs". _Wikipedia_.'
[SELinux]: #selinux 'SELinux&#10;MAC system developed by the NSA, well-supported on CentOS and Fedora and enabled by default on RHEL&#10;Nemeth, Evi. _Unix and Linux System Administration Handbook, 5th ed._: 85'
[syscall]: # 'system call (syscall)&#10;Service provided by the kernel that can be called from user mode which typically handles device access requests or other privileged operations.&#10;For most cases, making a syscall breaks down into 3 steps:&#10;  1. Marshall parameters - user mode puts the syscall parameters and number at locations defined by the ABI.&#10;  2. Special instruction - user mode uses a special processor instruction to transition to kernel mode for the syscall.&#10;  3. Handle the return - after the syscall is serviced, the kernel uses a special processor instruction to return to user mode and user mode checks the return value.&#10;"WSL System calls". _Windows Subsystem for Linux_. Microsoft.'
[SysFs]: # 'SysFs&#10;Pseudo file system provided by the Linux kernel that exports information about various kernel subsystems, hardware devices, and associated device drivers from the device model of the kernel to user space through virtual files.&#10;"sysfs". _Wikipedia_.'
[SystemD]: #init-systems "De facto standard init system for all major Linux distributions today"
[target]: #init-systems 'target&#10;systemd term for the operational modes that sysvinit calls "run levels"&#10;Nemeth, Evi. _Unix and Linux System Administration Handbook, 5th ed._: 43'
[TmpFs]: # 'TmpFs&#10;Temporary file storage paradigm implemented in many Unix-like operating systems. It is intended to appear as a mounted file system, but data is stored in volatile memory instead of a persistent storage device.&#10;"tmpfs". Wikipedia.'
[configure script]: # 'configure script&#10;Script that converts a Makefile.in template into a Makefile, responsible for preparing the software build, ensuring dependencies are available, such as a C compiler for C programs.&#10;Not typically built by hand but packaged by another program in the `autotools` suite, like `autoconf`, `automake`, etc. '
[unit]: #init-systems 'unit&#10;Any resource managed by SystemD, including targets and services.'


- [AppArmor][AppArmor]
- [Autotools][Autotools]
- [Configure script][configure script]
- [ProcFs][ProcFs] 
- [SELinux][SELinux]
- [syscall][syscall] 
- [SysFs][SysFs] 
- [SystemD][SystemD]
- [Target][target]
- [TmpFs][TmpFs] 
- [Unit][unit]

###### Commands
<!-- Audio commands -->
[alsamixer]: #alsamixer '```&#10;$ alsamixer&#10;```&#10;Command-line mixer'
[amixer]: #amixer '```&#10;$ amixer&#10;```&#10;Command-line mixer for ALSA sound card driver'
[speaker-test]: #speaker-test '```&#10;$ speaker-test&#10;```&#10;Generates a tone that can be used to test the speakers of a computer'

<!-- Diagnostic and benchmarking commands -->
[ausearch]: #ausearch '```&#10;$ ausearch&#10;```&#10;Display audit logs'
[bpftrace]: #bpftrace '```&#10;$ bpftrace&#10;```&#10;New open-source tracer for analyzing production performance problems and troubleshooting software&#10;"An introduction to `bpftrace` for Linux". _opensource.com_'
[date]: #date '```&#10;$ date&#10;```&#10;Print the current date and time, specifying a format.&#10;Robbins, Arnold. _UNIX in a Nutshell_ 4th ed (2005): 51'
[df]: #df '```&#10;$ df&#10;```&#10;Display usage of partitions and logical devices&#10;Rothwell, William. _CompTIA Linux+ Portable Command Guide_.: 49'
[du]: #du '```&#10;$ du $DIRS&#10;```&#10;Display disk utilization information for `$DIRS`&#10;Haeder, Adam. _LPI Linux Certification in a Nutshell_. 2010.: 153'
[free]: #free '```&#10;$ free&#10;```&#10;Display amount of free and used memory&#10;Haeder, Adam. _LPI Linux Certification in a Nutshell_. 2010.: 114'
[glances]: #glances '```&#10;$ glances&#10;```&#10;Cross-platform monitoring tool, written in Python&#10;Olushile, Paul. _Linux 5 Performance Monitoring and Tuning_.'
[hwclock]: #hwclock '```&#10;$ hwclock&#10;```&#10;Access the BIOS clock&#10;Haeder, Adam. _LPI Linux Certification in a Nutshell_. 2010.: 340'
[loadaverage]: #loadaverage '```&#10;$ loadaverage&#10;```&#10;Display system load average (cf. `uptime`)&#10;Rothwell, William. _CompTIA Linux+ Portable Command Guide_.: 291'
[logger]: #logger '```&#10;$ logger&#10;```&#10;Create a one-time file entry specified by the user&#10;Haeder, Adam. _LPI Linux Certification in a Nutshell_. 2010.: 342'
[logrotate]: #logrotate '```&#10;$ logrotate&#10;```&#10;Rename ("rotate") log files on a cyclic basis using /etc/logrotate.conf to determine behavior&#10;Eckert, Jason. _Linux+ Guide to Linux Certification_. Course Technology, 2012: 445'
[lsb_release]: #lsb_release '```&#10;$ lsb_release&#10;```&#10;&#10;Print distribution-specific information'
[man]: #man '```&#10;$ man&#10;```&#10;Format and display system manual pages&#10;Haeder, Adam. _LPI Linux Certification in a Nutshell_. 2010.: 75'
[mpstat]: #mpstat '```&#10;$ mpstat&#10;```&#10;utility for monitoring CPU performance&#10;Eckert, Jason. _Linux+ Guide to Linux Certification_. Course Technology, 2012: 635-637'
[nproc]: #nproc '```&#10;$ nproc&#10;```&#10;Display number of CPU processors or cores&#10;Olushile, Paul. _Linux 5 Performance Monitoring and Tuning_.'
[ntpdate]: #ntpdate '```&#10;$ ntpdate&#10;```&#10;Set the time of the local system to match a remote NTP host&#10;Haeder, Adam. _LPI Linux Certification in a Nutshell_. 2010.: 336'
[printenv]: #printenv '```&#10;$ printenv&#10;```&#10;Display environment variables&#10;Rothwell, William. _CompTIA Linux+ Portable Command Guide_.: 331'
[rsyslogd]: #rsyslogd '```&#10;$ rsyslogd&#10;```&#10;Responsible for logging of application and system events&#10;Rothwell, William. _CompTIA Linux+ Portable Command Guide_.: 249'
[sar]: #sar '```&#10;$ sar&#10;```&#10;Displays the same information as `iostat`, but displayed as it occurs over time (typically at 10-minute intervals)&#10;Rothwell, William. _CompTIA Linux+ Portable Command Guide_.: 291'
[sysbench]: #sysbench '```&#10;$ sysbench&#10;```&#10;Multi-threaded benchmark tool for database systems'
[syslogd]: #syslogd '```&#10;$ syslogd&#10;```&#10;Responsible for logging of application and system events&#10;Rothwell, William. _CompTIA Linux+ Portable Command Guide_.: 249'
[time]: #time '```&#10;$ time&#10;```&#10;Determine how long it takes to run a command&#10;Rothwell, William. _CompTIA Linux+ Portable Command Guide_.: 302'
[timedatectl]: #timedatectl '```&#10;$ timedatectl&#10;```&#10;Display system clock&#10;Rothwell, William. _CompTIA Linux+ Portable Command Guide_.: 71'
[tty]: #tty '```&#10;$ tty&#10;```&#10;Determine terminal device file for current session&#10;Rothwell, William. _CompTIA Linux+ Portable Command Guide_.: 121'
[uname]: #uname '```&#10;$ uname&#10;```&#10;Print the current Unix system name&#10;Robbins, Arnold. _UNIX in a Nutshell_ 4th ed (2005): 221'
[uptime]: #uptime '```&#10;$ uptime&#10;```&#10;Display current time, how long the system has been running, how many users are currently logged on, and the system load averages for the past 1, 5, and 15 minutes&#10;Haeder, Adam. _LPI Linux Certification in a Nutshell_. 2010.: 114'
[vmstat]: #vmstat '```&#10;$ vmstat&#10;```&#10;provides more detail than `free`&#10;Rothwell, William. _CompTIA Linux+ Portable Command Guide_.: 293'

<!-- Applications -->
[git]: #git '```&#10;$ git&#10;```&#10;The stupid content tracker'
[gconf-editor]: #gconf-editor '```&#10;$ gconf-editor&#10;```&#10;GUI-based configuration editor for GNOME'
[kquitapp]: #kquitapp '```&#10;$ kquitapp&#10;```&#10;Allows you to quit a dbus enabled application'
[krunner]: #krunner '```&#10;$ krunner&#10;```&#10;Single-line application launcher, similar to dmenu or the Run command on Windows'
[kstart]: #kstart '```&#10;$ kstart&#10;```&#10;When used to launch an application, prevents the application from being tied to the terminal'
[lowriter]: #lowriter '```&#10;$ lowriter&#10;```&#10;Command-line utility installed with LibreOffice Writer'
[smbclient]: #smbclient '```&#10;smbclient&#10;```&#10;Connect to a Samba server&#10;Eckert, Jason. _Linux+ Guide to Linux Certification_. Course Technology, 2012: 592'
[smbpasswd]: #smbpasswd '```&#10;$ smbpasswd&#10;```&#10;Create a Samba password&#10;Eckert, Jason. _Linux+ Guide to Linux Certification_. Course Technology, 2012: 591'
[smbstatus]: #smbstatus '```&#10;$ smbstatus&#10;```&#10;Display current Samba connections'
[switchdesk]: #switchdesk '```&#10;switchdesk&#10;```&#10;Simply switch between various desktop environments&#10;Haeder, Adam. _LPI Linux Certification in a Nutshell_. 2010.: 315'

**[Applications](#applications)** 
[`git`][git]
[`imagemagick`](#imagemagick) 
[`mongod`](#mongod) 
**GNOME** 
`gsettings`
[`gconf-editor`][gconf-editor] 
**KDE** 
[`kquitapp`][kquitapp] 
[`krunner`][krunner] 
[`kstart`][kstart] 
**SMB**
[`smbclient`][smbclient] 
[`smbpasswd`][smbpasswd] 
[`smbstatus`][smbstatus] 

<!-- Archive commands -->
[ar]: #ar '```&#10;$ ar&#10;```&#10;Maintain a group of files that are combined into a file archive. Used most commonly to create and update library files as used by `ld`.&#10;Robbins, Arnold. _UNIX in a Nutshell_ 4th ed (2005): 16'
[bzcat]: #bzcat '```&#10;$ bzcat&#10;```&#10;Page through .bz2 files'
[bzip2]: #bzip2 '```&#10;$ bzip2&#10;```&#10;Compress or decompress archives using the Burrows-Wheeler block-sorting text-compression algorithm.&#10;Rothwell, William. _CompTIA Linux+ Portable Command Guide_.: 271'
[bzless]: #bzless '```&#10;$ bzless&#10;```&#10;Page through .bz2 files'
[bzmore]: #bzmore '```&#10;$ bzmore&#10;```&#10;Page through .bz2 files'
[compress]: #compress '```&#10;$ compress&#10;```&#10;Compress and expand data&#10;Compress reduces the size of the named files using adaptive Lempel-Ziv coding. Whenever possible, each file is replaced by one with the extension .Z, while keeping the same ownership modes, access and modification times. If no files are specified, the standard input is compressed to the standard output. Compress will only attempt to compress regular files. In particular, it will ignore symbolic links. If a file has multiple hard links, compress will refuse to compress it unless the -f flag is given.'
[cpio]: #cpio '```&#10;$ cpio&#10;```&#10;Create and extract archives, or copy files from one place to another - without compression. Each of the three control options (`-i`, `-o`, or `-p`) accepts different options.&#10;Haeder, Adam. _LPI Linux Certification in a Nutshell_. 2010.: 93'
[dar]: #dar '```&#10;$ dar&#10;```&#10;Backup tool that can make differential and incremental backups&#10;"`dar` manpage". _Ubuntu Manpage Repository_.'
[gunzip]: #gunzip '```&#10;$ gunzip&#10;```&#10;Identical to `gzip -d`, typically implemented as a link to `gzip`'
[gzcat]: #gzcat '```&#10;$ gzcat&#10;```&#10;Identical to `gzip -c`, typically implemented as a link to `gzip`'
[gzip]: #gzip '```&#10;$ gzip&#10;```&#10;"GNU Zip". Compress or decompress archives using the Lempel-Ziv (LZ77) compression algorithm.'
[tar]: #tar '```&#10;$ tar&#10;```&#10;Merge multiple files into a single file&#10;Rothwell, William. _CompTIA Linux+ Portable Command Guide_.: 268'
[uncompress]: #uncompress '```&#10;$ uncompress&#10;```&#10;Aliased to `gunzip` on Ubuntu&#10;Eckert, Jason. _Linux+ Guide to Linux Certification_. Course Technology, 2012: 480'
[unxz]: #unxz '```&#10;$ unxz&#10;```&#10;Decompress an archive created with `xz`&#10;Rothwell, William. _CompTIA Linux+ Portable Command Guide_.: 270'
[unzip]: #unzip '```&#10;$ unzip&#10;```&#10;Decompress a .zip archive'
[xz]: #xz '```&#10;$ xz&#10;```&#10;Compress or decompress archives using the LZMA and LZMA2 compression methods.&#10;Rothwell, William. _CompTIA Linux+ Portable Command Guide_.: 270'
[zcat]: #zcat '```&#10;$ zcat&#10;```&#10;Uncompress one or more compressed files to STDOUT. On Linux, this program is the version related to `gzip`, which can decompress .Z and .gz files&#10;Robbins, Arnold. _UNIX in a Nutshell_ 4th ed (2005): 238'
[zip]: #zip '```&#10;$ zip&#10;```&#10;Merge multiple files into a single, compressed file&#10;Rothwell, William. _CompTIA Linux+ Portable Command Guide_.: 271'
[zipcloak]: #zipcloak '```&#10;$ zipcloak&#10;```&#10;Password protect and encrypt zip files, equivalent to `zip --encrypt` or `zip -e`.&#10;_Linux Pro Magazine_. Issue 231. Feb 2020.: 37'
[zipcmp]: #zipcmp '```&#10;$ zipcmp $FILE $OTHER&#10;```&#10;Compare files in zip archives (no man page or help option available).&#10;_Linux Pro Magazine_. Issue 231. Feb 2020.: 37'
[zipdetails]: #zipdetails '```&#10;$ zipdetails&#10;```&#10;'
[zipgrep]: #zipgrep '```&#10;$ zipgrep&#10;```&#10;Search for patterns within a zip archive.&#10;_Linux Pro Magazine_. Issue 231. Feb 2020.: 37'
[zipinfo]: #zipinfo '```&#10;$ zipinfo&#10;```&#10;Display the attributes of all the files in a zip archive, including permissions, name, date created, uncompressed and compressed file sizes, and percentage compression.&#10;_Linux Pro Magazine_. Issue 231. Feb 2020.: 38'
[zipnote]: #zipnote '```&#10;$ zipnote&#10;```&#10;Read and edit comments in archives; particularly useful for changing filenames in an archive that start with "@home" in the comment&#10;_Linux Pro Magazine_. Issue 231. Feb 2020.: 38'
[zipsplit]: #zipsplit '```&#10;$ zipsplit&#10;```&#10;Divide existing archives into smaller ones, creating an index file to help reassemble them.&#10;_Linux Pro Magazine_. Issue 231. Feb 2020.: 38'

**[Archive](#archive)** 
[`ar`][ar] 
[`bzcat`][bzcat] 
[`bzip2`][bzip2] 
[`bzless`][bzless] 
[`bzmore`][bzmore] 
[`compress`][compress] 
[`cpio`][cpio] 
[`dar`][dar] 
[`gunzip`][gunzip] 
[`gzcat`][gzcat] 
[`gzip`][gzip] 
[`tar`][tar] 
[`uncompress`][uncompress] 
[`unxz`][unxz] 
[`unzip`][unzip] 
[`xz`][xz] 
[`zcat`][zcat] 
[`zip`][zip] 
[`zipcloak`][zipcloak] 
[`zipcmp`][zipcmp] 
[`zipdetails`][zipdetails] 
[`zipgrep`][zipgrep] 
[`zipinfo`][zipinfo] 
[`zipnote`][zipnote] 
[`zipsplit`][zipsplit] 

<!-- Bash builtins -->
[alias]: #alias '```&#10;$ alias&#10;```&#10;Assign a shorthand `$NAME` for `$CMD`, or display all aliases if not specified. (ref. `$BASH_ALIASES`)&#10;Robbins, Arnold. _Bash Pocket Reference_. O\'Reilly: 2016.: 74'
[bg]:   #bg '```&#10;$ bg&#10;```&#10;Put current job or `$JOB` in the background&#10;Robbins, Arnold. _Bash Pocket Reference_. O\'Reilly: 2016.: 74'
[bind]: #bind '```&#10;$ bind&#10;```&#10;Manage the readline library; nonoption arguments have the same form as in a .inputrc file.&#10;Robbins, Arnold. _Bash Pocket Reference_. O\'Reilly: 2016.: 75'
[break]: #break '```&#10;$ break&#10;```&#10;Exit from a `for`, `while`, `select`, or `until` loop.&#10;Robbins, Arnold. _Bash Pocket Reference_. O\'Reilly: 2016.: 76'
[builtin]: #builtin '```&#10;$ builtin&#10;```&#10;Run the shell built-in command `$CMD` with the optional given arguments `$ARGS`, bypassing functions and aliases.&#10;Robbins, Arnold. _Bash Pocket Reference_. O\'Reilly: 2016.: 76'
[caller]: #caller '```&#10;$ caller&#10;```&#10;Print line number and source filename of the current function call or dot file&#10;Robbins, Arnold. _Bash Pocket Reference_. O\'Reilly: 2016.: 77'
[case]: #case '```&#10;$ case&#10;```&#10;Execute `$CMDS1` if `$VALUE` matches `$PATTERN1`, etc&#10;Robbins, Arnold. _Bash Pocket Reference_. O\'Reilly: 2016.: 77'
[cd]:   #cd '```&#10;$ cd&#10;```&#10;&#10;Robbins, Arnold. _Bash Pocket Reference_. O\'Reilly: 2016.: 78'
[command]: #command '```&#10;$ command&#10;```&#10;Execute `$CMD`, bypassing any aliases or functions that may be defined for it&#10;Robbins, Arnold. _Bash Pocket Reference_. O\'Reilly: 2016.: 79'
[compgen]: #compgen '```&#10;$ compgen&#10;```&#10;Generate possible completions for `$STRING`&#10;Robbins, Arnold. _Bash Pocket Reference_. O\'Reilly: 2016.: 80'
[complete]: #complete '```&#10;$ complete&#10;```&#10;Specify how to complete arguments for each `$CMD`&#10;Robbins, Arnold. _Bash Pocket Reference_. O\'Reilly: 2016.: 80'
[compopt]: #compopt '```&#10;$ compopt&#10;```&#10;Modify existing compspecs for given `$CMD`, or for the currently executing completion when invoked without `$CMD`&#10;Robbins, Arnold. _Bash Pocket Reference_. O\'Reilly: 2016.: 84'
[continue]: #continue '```&#10;$ continue&#10;```&#10;Skip remaining commands in a `for`, `while`, `select`, or `until` loop, resuming the next iteration, or skipping `$N` nested loops&#10;Robbins, Arnold. _Bash Pocket Reference_. O\'Reilly: 2016.: 85'
[declare]: #declare '```&#10;$ declare&#10;```&#10;Declare variables and manage their attributes&#10;Robbins, Arnold. _Bash Pocket Reference_. O\'Reilly: 2016.: 85'
[dirs]: #dirs '```&#10;$ dirs&#10;```&#10;Print the directory stack managed by `pushd` and `popd`&#10;Robbins, Arnold. _Bash Pocket Reference_. O\'Reilly: 2016.: 87'
[disown]: #disown '```&#10;$ disown&#10;```&#10;Remove one or more `$JOB` from list of jobs managed by bash&#10;Robbins, Arnold. _Bash Pocket Reference_. O\'Reilly: 2016.: 87'
[do]:   #do '```&#10;$ do&#10;```&#10;Reserved word that precedes the command sequence in a `for`, `while`, `until`, or `select` statement&#10;Robbins, Arnold. _Bash Pocket Reference_. O\'Reilly: 2016.: 88'
[done]: #done '```&#10;$ done&#10;```&#10;Reserved word that ends a `for`, `while`, `until`, or `select` statement&#10;Robbins, Arnold. _Bash Pocket Reference_. O\'Reilly: 2016.: 88'
[echo]: #echo '```&#10;$ echo&#10;```&#10;Write `$STRING` to STDOUT&#10;Robbins, Arnold. _Bash Pocket Reference_. O\'Reilly: 2016.: 88'
[enable]: #enable '```&#10;$ enable&#10;```&#10;Enable or disable shell builtins, allowing an external version of a command like `echo` or `test` be used.&#10;Robbins, Arnold. _Bash Pocket Reference_. O\'Reilly: 2016.: 89'
[esac]: #esac '```&#10;$ esac&#10;```&#10;Reserved word that ends a `case` statement&#10;Robbins, Arnold. _Bash Pocket Reference_. O\'Reilly: 2016.: 90'
[eval]: #eval '```&#10;$ eval&#10;```&#10;Execute `$ARGS` after first performing variable expansion.&#10;Robbins, Arnold. _Bash Pocket Reference_. O\'Reilly: 2016.: 90'
[exec]: #exec '```&#10;$ exec&#10;```&#10;Execute `$CMD` in place of the current process.&#10;Robbins, Arnold. _Bash Pocket Reference_. O\'Reilly: 2016.: 91'
[exit]: #exit '```&#10;$ exit&#10;```&#10;Exit a shell script with status `$N`&#10;Robbins, Arnold. _Bash Pocket Reference_. O\'Reilly: 2016.: 92'
[export]: #export '```&#10;$ export&#10;```&#10;Convert `$VAR` to a global variable&#10;Robbins, Arnold. _Bash Pocket Reference_. O\'Reilly: 2016.: 92'
[false]: #false '```&#10;$ false&#10;```&#10;Built-in command that exits with a false return value.&#10;Robbins, Arnold. _Bash Pocket Reference_. O\'Reilly: 2016.: 93'
[fc]:   #fc '```&#10;$ fc&#10;```&#10;Display or edit commands in the history list&#10;Robbins, Arnold. _Bash Pocket Reference_. O\'Reilly: 2016.: 93'
[fg]:   #fg '```&#10;$ fg&#10;```&#10;Bring `$JOB` to the foreground&#10;Robbins, Arnold. _Bash Pocket Reference_. O\'Reilly: 2016.: 95'
[fi]:   #fi '```&#10;$ fi&#10;```&#10;Reserved word that ends an `if` statement&#10;Robbins, Arnold. _Bash Pocket Reference_. O\'Reilly: 2016.: 95'
[for]: #for '```&#10;$ for&#10;```&#10;For variable `$X`, do `$CMD`; if `$LIST` is omitted, use `$@`&#10;Robbins, Arnold. _Bash Pocket Reference_. O\'Reilly: 2016.: 95'
[function]: #function '```&#10;$ function&#10;```&#10;Define `$NAME` as a shell function&#10;Robbins, Arnold. _Bash Pocket Reference_. O\'Reilly: 2016.: 97'
[getopts]: #getopts '```&#10;$ getopts&#10;```&#10;Process command-line arguments and check for legal options&#10;Robbins, Arnold. _Bash Pocket Reference_. O\'Reilly: 2016.: 97'
[hash]: #hash '```&#10;$ hash&#10;```&#10;List the current set of hashed (previously found) commands&#10;Robbins, Arnold. _Bash Pocket Reference_. O\'Reilly: 2016.: 98'
[help]: #help '```&#10;$ help&#10;```&#10;Print usage information for each command that matches `$PATTERN` to STDOUT&#10;Robbins, Arnold. _Bash Pocket Reference_. O\'Reilly: 2016.: 99'
[history]: #history '```&#10;$ history&#10;```&#10;Print commands in the history list or manage the history file&#10;Robbins, Arnold. _Bash Pocket Reference_. O\'Reilly: 2016.: 100'
[if]:   #if '```&#10;$ if&#10;```&#10;Begin a conditional statement&#10;Robbins, Arnold. _Bash Pocket Reference_. O\'Reilly: 2016.: 101'
[jobs]: #jobs '```&#10;$ jobs&#10;```&#10;List all running or stopped jobs, or list those specified by `$JOBS`&#10;Robbins, Arnold. _Bash Pocket Reference_. O\'Reilly: 2016.: 102'
[kill]: #kill '```&#10;$ kill&#10;```&#10;Terminate each specified PID&#10;Robbins, Arnold. _Bash Pocket Reference_. O\'Reilly: 2016.: 103'
[let]: #let '```&#10;$ let&#10;```&#10;Perform arithmetic as specified by one or more `$EXPRESSIONS`&#10;Robbins, Arnold. _Bash Pocket Reference_. O\'Reilly: 2016.: 104'
[local]: #local '```&#10;$ local&#10;```&#10;Declare local variables for use inside functions&#10;Robbins, Arnold. _Bash Pocket Reference_. O\'Reilly: 2016.: 105'
[logout]: #logout '```&#10;$ logout&#10;```&#10;Exit a login shell, executing ~/.bash_logout if it exists&#10;Robbins, Arnold. _Bash Pocket Reference_. O\'Reilly: 2016.: 105'
[mapfile]: #mapfile '```&#10;$ mapfile&#10;```&#10;Read STDIN into `$ARRAY`, one line per element, or `$MAPFILE` shell variable if not specified&#10;Robbins, Arnold. _Bash Pocket Reference_. O\'Reilly: 2016.: 105'
[popd]: #popd '```&#10;$ popd&#10;```&#10;Pop the top directory off the directory stack and change to the new top directory&#10;Robbins, Arnold. _Bash Pocket Reference_. O\'Reilly: 2016.: 106'
[printf]: #printf '```&#10;$ printf&#10;```&#10;Formatted printing using escape sequences&#10;Robbins, Arnold. _Bash Pocket Reference_. O\'Reilly: 2016.: 107'
[pushd]: #pushd '```&#10;$ pushd&#10;```&#10;Add `$PATH` to the directory state, or rotate it if none provided&#10;Robbins, Arnold. _Bash Pocket Reference_. O\'Reilly: 2016.: 108'
[pwd]: #pwd '```&#10;$ pwd&#10;```&#10;Display current working directory on STDOUT&#10;Robbins, Arnold. _Bash Pocket Reference_. O\'Reilly: 2016.: 108'
[read]: #read '```&#10;$ read&#10;```&#10;Read one line from STDIN and assign each word to the corresonding `$VAR`&#10;Robbins, Arnold. _Bash Pocket Reference_. O\'Reilly: 2016.: 109'
[readarray]: #readarray '```&#10;$ readarray&#10;```&#10;Identical to `mapfile`&#10;Robbins, Arnold. _Bash Pocket Reference_. O\'Reilly: 2016.: 111'
[readonly]: #readonly '```&#10;$ readonly&#10;```&#10;Prevent specified shell variables $VAR1, $VAR2 from being assigned new values, optionally assigning initial values $VAL1, $VAL2&#10;Robbins, Arnold. _Bash Pocket Reference_. O\'Reilly: 2016.: 111'
[return]: #return '```&#10;$ return&#10;```&#10;Use inside a function definition, exiting with status `$N`&#10;Robbins, Arnold. _Bash Pocket Reference_. O\'Reilly: 2016.: 112'
[select]: #select '```&#10;$ select&#10;```&#10;&#10;Robbins, Arnold. _Bash Pocket Reference_. O\'Reilly: 2016.: 112'
[set]: #set '```&#10;$ set&#10;```&#10;Print values of all variables known to the current shell.&#10;Robbins, Arnold. _Bash Pocket Reference_. O\'Reilly: 2016.: 113'
[shift]: #shift '```&#10;$ shift&#10;```&#10;Shift positional arguments; intended for use in a loop.&#10;Robbins, Arnold. _Bash Pocket Reference_. O\'Reilly: 2016.: 119'
[shopt]: #shopt '```&#10;$ shopt&#10;```&#10;Set or unset shell options.&#10;Robbins, Arnold. _Bash Pocket Reference_. O\'Reilly: 2016.: 119'
[source]: #source '```&#10;$ source&#10;```&#10;Execute a bash script as if the commands within it were executed directly on the command line&#10;Rothwell, William. _CompTIA Linux+ Portable Command Guide_.: 332'
[source]: #source '```&#10;$ source&#10;```&#10;Read and execute a file in the current shell&#10;Robbins, Arnold. _Bash Pocket Reference_. O\'Reilly: 2016.: 120'
[suspend]: #suspend '```&#10;$ suspend&#10;```&#10;Suspend the current shell, often used to stop an `su` command&#10;Robbins, Arnold. _Bash Pocket Reference_. O\'Reilly: 2016.: 120'
[test]: #test '```&#10;$ test&#10;```&#10;Evaluate a condition and exit with status 0 if true, or with a nonzero exit status if false.&#10;Robbins, Arnold. _Bash Pocket Reference_. O\'Reilly: 2016.: 120'
[time]: #time '```&#10;$ time&#10;```&#10;Execute `$CMD` and print the total elapsed time, user time, and system time (in seconds). Similar to external `time` command, except that this builtin version can also time other builtin commands and all commands in a pipeline.&#10;Robbins, Arnold. _Bash Pocket Reference_. O\'Reilly: 2016.: 124'
[times]: #times '```&#10;$ times&#10;```&#10;Print accumulated user and system process times for the shell and the processes it has run&#10;Robbins, Arnold. _Bash Pocket Reference_. O\'Reilly: 2016.: 125'
[trap]: #trap '```&#10;$ trap&#10;```&#10;Execute `$CMD` if any `$SIGNALS` are received&#10;Robbins, Arnold. _Bash Pocket Reference_. O\'Reilly: 2016.: 125'
[true]: #true '```&#10;$ true&#10;```&#10;Built-in command that exits with a true return value&#10;Robbins, Arnold. _Bash Pocket Reference_. O\'Reilly: 2016.: 127'
[type]: #type '```&#10;$ type&#10;```&#10;Show whether each command name is an external command, a built-in command, an alias, shell keyword, or defined shell function&#10;Robbins, Arnold. _Bash Pocket Reference_. O\'Reilly: 2016.: 127'
[typeset]: #typeset '```&#10;$ typeset&#10;```&#10;Identical to `declare`&#10;Robbins, Arnold. _Bash Pocket Reference_. O\'Reilly: 2016.: 128'
[ulimit]: #ulimit '```&#10;$ ulimit&#10;```&#10;Print value of one or more resource limits&#10;Robbins, Arnold. _Bash Pocket Reference_. O\'Reilly: 2016.: 128'
[umask]: #umask '```&#10;$ umask&#10;```&#10;Set file creation mask to octal value `$MASK`, or display it if not provided.&#10;Robbins, Arnold. _Bash Pocket Reference_. O\'Reilly: 2016.: 130'
[unalias]: #unalias '```&#10;$ unalias&#10;```&#10;Remove `$NAMES` from the alias list.&#10;Robbins, Arnold. _Bash Pocket Reference_. O\'Reilly: 2016.: 130'
[unset]: #unset '```&#10;$ unset&#10;```&#10;Erase definitions of functions or variables listed in `$NAMES`&#10;Robbins, Arnold. _Bash Pocket Reference_. O\'Reilly: 2016.: 130'
[until]: #until '```&#10;$ until&#10;```&#10;Until `$CONDITION` is met, do `$CMDS`&#10;Robbins, Arnold. _Bash Pocket Reference_. O\'Reilly: 2016.: 131'
[wait]: #wait '```&#10;$ wait&#10;```&#10;Pause until the specified `$JOB`, which can be a job number or PID, completes, or until all background jobs complete if not provided.&#10;Robbins, Arnold. _Bash Pocket Reference_. O\'Reilly: 2016.: 131'
[while]: #while '```&#10;$ while&#10;```&#10;While `$CONDITION` is met, do `$CMDS`.&#10;Robbins, Arnold. _Bash Pocket Reference_. O\'Reilly: 2016.: 132'

**[Bash](#bash-builtins)** 
[`bg`][bg] 
[`bind`][bind] 
[`break`][break] 
[`builtin`][builtin]
[`caller`][caller]
[`case`][case]/[`esac`][esac]
[`cd`][cd]
[`command`][command]
[`compgen`][compgen]
[`complete`][complete]
[`compopt`][compopt]
[`continue`][continue]
[`declare`][declare]
[`dirs`][dirs]
[`disown`][disown]
[`do`][do]/[`done`][done]
[`echo`][echo]
[`enable`][enable]
[`eval`][eval]
[`exec`][exec]
[`exit`][exit]
[`export`][export]
[`false`][false]
[`fc`][fc]
[`fg`][fg]
[`for`][for]
[`function`][function]
[`getopts`][getopts]
[`hash`][hash]
[`help`][help]
[`history`][history]
[`if`][if]/[`fi`][fi]
[`jobs`][jobs]
[`kill`][kill]
[`let`][let]
[`local`][local]
[`logout`][logout]
[`mapfile`][mapfile]
[`popd`][popd]
[`printf`][printf]
[`pushd`][pushd]
[`pwd`][pwd]
[`read`][read]
[`readarray`][readarray]
[`readonly`][readonly]
[`return`][return]
[`select`][select]
[`set`][set]
[`shift`][shift]
[`shopt`][shopt]
[`source`][source]
[`suspend`][suspend]
[`test`][test]
[`time`][time]
[`times`][times]
[`trap`][trap]
[`true`][true]
[`type`][type]
[`typeset`][typeset]
[`ulimit`][ulimit]
[`umask`][umask]
[`unalias`][unalias]
[`unset`][unset]
[`until`][until]
[`wait`][wait]
[`while`][while] 

<!-- Boot commands -->
[grub-install]: #grub-install '```&#10;$ grub-install&#10;```&#10;Install GRUB on the MBR of a hard drive&#10;Haeder, Adam. _LPI Linux Certification in a Nutshell_. 2010.: 42'
[grub-mkconfig]: # ""
[grub2-editenv]: #grub2-editenv '```&#10;grub2-editenv&#10;```&#10;Manage the stored environment of GRUB&#10;"How to install the NVIDIA drivers on Fedora 31". Linuxconfig.org: 10/17/2019.'
[lilo]: #lilo '```&#10;$ lilo&#10;```&#10;`lilo` map installer reads a configuration file and writes a map file, which contains information needed by the boot loader to locate and launch Linux kernels or other operating systems.&#10;Haeder, Adam. _LPI Linux Certification in a Nutshell_. 2010.: 40'
[update-grub]: #update-grub '```&#10;$ update-grub&#10;```&#10;Make changes take effect for a GRUB2 configuration change'

**Boot commands**
[grub-install][grub-install]
[grub-mkconfig][grub-mkconfig]
[grub2-editenv][grub2-editenv]
[update-grub][update-grub]
[lilo][lilo]

<!-- Build tools-->
[aclocal]: #aclocal '```&#10;$ aclocal&#10;```&#10;Place m4 macro definitions needed by `autoconf` into a single file. `aclocal` first scans for macro definitions in m4 files in its default directory (/usr/share/aclocal) and in the file acinclude.m4, then in the configure.ac file. IT generates an aclocal.m4 file that contains definitions of all m4 macros required by `autoconf`.&#10;Robbins, Arnold. _UNIX in a Nutshell_ 4th ed (2005): 16'
[as]: #as '```&#10;$ as&#10;```&#10;Generate an object file from each specified assembly language source file. Primarily intended to assemble the output of the GNU C compiler `gcc` for use by the linker `ld`.&#10;Robbins, Arnold. _UNIX in a Nutshell_ 4th ed (2005): 18'
[autoconf]: #autoconf '```&#10;$ autoconf&#10;```&#10;Generate a configuration script from m4 macros defined in a template file, if given, or in a configure.ac or configure.in file in the CWD. The generated script is almost invariably called "configure".&#10;Robbins, Arnold. _UNIX in a Nutshell_ 4th ed (2005): 21'
[autoheader]: #autoheader '```&#10;$ autoheader&#10;```&#10;Generate a template file of C `#define` statements from m4 macros defined in a template file, if specified, or in configure.ac or configure.in in the CWD. The generated template file is almost invariably called config.h.in or config.hin&#10;Robbins, Arnold. _UNIX in a Nutshell_ 4th ed (2005): 22'
[automake]: #automake '```&#10;$ automake&#10;```&#10;Create GNU standards-compliant Makefile.in files from Makefile.am template files&#10;Robbins, Arnold. _UNIX in a Nutshell_ 4th ed (2005): 23'
[autoreconf]: #autoreconf '```&#10;$ autoreconf&#10;```&#10;Update configure scripts by running `autoconf`, `autoheader`, `aclocal`, `automake`, and `libtoolize` as needed&#10;Robbins, Arnold. _UNIX in a Nutshell_ 4th ed (2005): 21'
[autoscan]: #autoscan '```&#10;$ autoscan&#10;```&#10;Create or maintain a preliminary configure.ac file named configure.scan based on source files in specified directory or CWD.&#10;Robbins, Arnold. _UNIX in a Nutshell_ 4th ed (2005): 21'
[autoupdate]: #autoupdate '```&#10;$ autoupdate&#10;```&#10;Update the configure template file or configure.ac if none is specified&#10;Robbins, Arnold. _UNIX in a Nutshell_ 4th ed (2005): 21'
[bison]: #bison '```&#10;$ bison&#10;```&#10;Convert specified "file.y" containing a context-free grammar into tables for subsequent parsing while sending output to a new file named "file.c". Largely compatible with `yacc`, from which it derives its name.&#10;Originated as an adaptation of Bob Corbett\'s reimplementation of `yacc` which was distributed under the Berkeley license. Now maintained as a project of the FSF under a GPL license.'
[cc]: #cc '```&#10;$ cc&#10;```&#10;Compile one or more C (.c), assembler (.s), ore preprocessed C (.i) source files. Automatically invokes the loader `ld`, unless `-c` is suplied. In some cases, `cc` generates an object file having a .o suffix and a corresponding root name. By default, output is placed in `"a.out"&#10;Robbins, Arnold. _UNIX in a Nutshell_ 4th ed (2005): 32'
[ctags]: #ctags '```&#10;$ ctags $FILES&#10;```&#10;Create a list of function and macro names that are defined in the specified C, Pascal, FORTRAN, `yacc`, or `lex` source `$FILES`. Output is in three columns:&#10;  - `name`                function or macro name&#10;  - `file`                source file in which `name` is defined&#10;  - `context`             search pattern that shows the line of code containing `name`&#10;&#10;Robbins, Arnold. _UNIX in a Nutshell_ 4th ed (2005): 48'
[etags]: #etags '```&#10;$ etags&#10;```&#10;Create a list of function and macro names defined in a programming source file, generating tags for use by `emacs`&#10;Robbins, Arnold. _UNIX in a Nutshell_ 4th ed (2005): 75'
[flex]: #flex '```&#10;$ flex&#10;```&#10;"Fast Lexical Analyzer Generator", faster variant of `lex` translated into C by Vern Paxson&#10;Robbins, Arnold. _UNIX in a Nutshell_ 4th ed (2005): 92'
[g++]: #g++ '```&#10;$ g++&#10;```&#10;Invoke `gcc` with the options necessary to make it recognize C++.&#10;Robbins, Arnold. _UNIX in a Nutshell_ 4th ed (2005): 95'
[gcc]: #gcc '```&#10;$ gcc&#10;```&#10;"GNU Compiler Collection", formerly known as the "GNU C Compiler", compiles multiple languages to machine code.&#10;Robbins, Arnold. _UNIX in a Nutshell_ 4th ed (2005): 95'
[gcore]: #gcore '```&#10;$ gcore&#10;```&#10;Create a core image of each running process specified, which can be used with a debugger&#10;Robbins, Arnold. _UNIX in a Nutshell_ 4th ed (2005): 98'
[gdb]: #gdb '```&#10;$ gdb&#10;```&#10;"GNU DeBugger", allows you to step through the execution of a program in order to find the point at which it breaks&#10;Robbins, Arnold. _UNIX in a Nutshell_ 4th ed (2005): 99'
[gprof]: #gprof '```&#10;$ gprof&#10;```&#10;Display call-graph profile data of C programs'
[ldd]: #ldd '```&#10;$ ldd $FILE&#10;```&#10;List dynamic dependencies: shared objects that would be loaded if `$FILE` were executed&#10;Robbins, Arnold. _UNIX in a Nutshell_ 4th ed (2005): 115'
[lex]: #lex '```&#10;$ lex&#10;```&#10;Generate a lexical analysis program based on the regular expressions and C statements contained in one or more input files (also `flex`)&#10;Lexical analyzer generator written by Eric Schmidt&#10;Robbins, Arnold. _UNIX in a Nutshell_ 4th ed (2005): 119'
[make]: #make '```&#10;$ make&#10;```&#10;Utility for building and maintaining programs from source code using a makefile&#10;Rothwell, William. _CompTIA Linux+ Portable Command Guide_.: 86'
[xgettext]: #xgettext '```&#10;$ xgettext&#10;```&#10;Extract specially marked strings from C and C++ source files, placing them in a .po ("portable object" file for translation and compilation by `msgfmt`.&#10;Robbins, Arnold. _UNIX in a Nutshell_ 4th ed (2005): 234'
[yacc]: #yacc '```&#10;$ yacc&#10;```&#10;"yet another compiler-compiler", parser generator that converts a file containing a context-free LALR grmamar and converts it to tables for subsequent pasring, sending output to y.tab.c. Written between 1975 and 1978 by Stephen C. Johnson at Bell Labs.&#10;Robbins, Arnold. _UNIX in a Nutshell_ 4th ed (2005): 237'

**Build tools**
[`aclocal`][aclocal] 
[`as`][as] 
[`autoconf`][autoconf] 
[`autoheader`][autoheader] 
[`automake`][automake] 
[`autoreconf`][autoreconf] 
[`autoscan`][autoscan] 
[`autoupdate`][autoupdate] 
[`bison`][bison] 
[`cc`][cc] 
[`ctags`][ctags] 
[`etags`][etags] 
[`flex`][flex] 
[`g++`][g++] 
[`gcc`][gcc] 
[`gcore`][gcore] 
[`gdb`][gdb] 
[`gprof`][gprof] 
[`ldd`][ldd] 
[`lex`][lex] 
[`make`][make] 
[`xgettext`][xgettext] 
[`yacc`][yacc] 

<!-- Disk commands -->
[blkid]: #blkid '```&#10;$ blkid&#10;```&#10;Display label and UUIDs of block devices.&#10;Rothwell, William. _CompTIA Linux+ Portable Command Guide_.: 51'
[cryptsetup]: #cryptsetup '```&#10;$ cryptsetup&#10;```&#10;Encrypt a whole disk'
[dd]: #dd '```&#10;$ dd&#10;```&#10;Convert and copy files, operating directly on block devices rather than through the filesystem layer&#10;Haeder, Adam. _LPI Linux Certification in a Nutshell_. 2010.: 95'
[dm-crypt]: #dm-crypt '```&#10;$ dm-crypt&#10;```&#10;Disk encryption subsystem which serves as the backend to `cryptsetup`'
[dumpe2fs]: #dumpe2fs '```&#10;$ dumpe2fs&#10;```&#10;Display filesystem metadata&#10;Rothwell, William. _CompTIA Linux+/LPIC-1 Portable Command guide_.: 122'
[e2fsck]: #e2fsck '```&#10;$ e2fsck&#10;```&#10;Execute filesystem-specific utilities (executed by `fsck`)&#10;Rothwell, William. _CompTIA Linux+/LPIC-1 Portable Command guide_.: 121'
[e2label]: #e2label '```&#10;$ e2label $DEVICE $NAME&#10;```&#10;Create an image of important metadata for an ext3 filesystem; Assign label `$NAME` to `$DEVICE`&#10;Rothwell, William. _CompTIA Linux+ Portable Command Guide_.: 53'
[eject]: #eject '```&#10;$ eject&#10;```&#10;Eject removable media, such as a floppy disk or CD-ROM&#10;Robbins, Arnold. _UNIX in a Nutshell_ 4th ed (2005): 74'
[fdformat]: #fdformat '```&#10;$ fdformat $DEVICE&#10;```&#10;Format floppy disks and PCMCIA memory cards&#10;Robbins, Arnold. _UNIX in a Nutshell_ 4th ed (2005): 81'
[fdisk]: #fdisk '```&#10;$ fdisk&#10;```&#10;Text-based program used to manipulate or display the partition table for block devices.&#10;Haeder, Adam. _LPI Linux Certification in a Nutshell_. 2010.: 145'
[fsck]: #fsck '```&#10;$ fsck $FILESYSTEM&#10;```&#10;Check `$FILESYSTEM` for errors&#10;Haeder, Adam. _LPI Linux Certification in a Nutshell_. 2010.: 158'
[fstrim]: #fstrim '```&#10;$ fstrim&#10;```&#10;Discard unused blocks on a mounted filesystem'
[gdisk]: #gdisk '```&#10;$ gdisk&#10;```&#10;Interactive tool that allows you to display and modify GUID partition tables&#10;Rothwell, William. _CompTIA Linux+/LPIC-1 Portable Command guide_.: 114'
[hdiutil]: #hdiutil '```&#10;$ hdiutil&#10;```&#10;Manipulate disk images'
[hdparm]: #hdparm '```&#10;$ hdparm&#10;```&#10;Get/set SATA/IDE device parameters'
[ioping]: #ioping '```&#10;$ ioping&#10;```&#10;Perform simple latency tests on a disk&#10;Rothwell, William. _CompTIA Linux+ Portable Command Guide_.: 288'
[lsblk]: #lsblk '```&#10;$ lsblk&#10;```&#10;Display information about all block devices'
[mdadm]: #mdadm '```&#10;$ mdadm&#10;```&#10;Create and manager software RAID devices&#10;Rothwell, William. _CompTIA Linux+ Portable Command Guide_.: 45'
[mke2fs]: #mke2fs '```&#10;$ mke2fs&#10;```&#10;Create ext2/ext3/ext4 filesystems.&#10;Rothwell, William. _CompTIA Linux+/LPIC-1 Portable Command guide_.: 121'
[mkfs]: #mkfs '```&#10;$ mkfs&#10;```&#10;Deprecated frontend program for filesystem-specific creation tools such as `mkfs.ext2` and `mkfs.msdos`, which are in turn linked to `mke2fs` and `mkdosfs`&#10;Haeder, Adam. _LPI Linux Certification in a Nutshell_. 2010.: 149'
[mkswap]: #mkswap '```&#10;$ mkswap&#10;```&#10;Format a partition as a swap device&#10;Rothwell, William. _CompTIA Linux+ Portable Command Guide_.: 293'
[mount]: #mount '```&#10;$ mount&#10;```&#10;Mount filesystems into the filesystem hierarchy&#10;Haeder, Adam. _LPI Linux Certification in a Nutshell_. 2010.: 163'
[mt]: #mt '```&#10;$ mt&#10;```&#10;Control magnetic tape drive operation; operates on environment variable `$TAPE`'
[parted]: #parted '```&#10;$ parted&#10;```&#10;Interactive tool that allows you to display and modify both traditional and GUID partition tables.&#10;Rothwell, William. _CompTIA Linux+/LPIC-1 Portable Command guide_.: 115'
[partprobe]: #partprobe '```&#10;$ partprobe&#10;```&#10;Inform system of changes to partition table, typically used after making changes using `fdisk`&#10;Rothwell, William. _CompTIA Linux+ Portable Command Guide_.: 289'
[partx]: #partx '```&#10;$ partx&#10;```&#10;Utility that provides information on drive partitions to the Linux kernel'
[resize2fs]: #resize2fs '```&#10;$ resize2fs&#10;```&#10;Resize a logical volume&#10;Rothwell, William. _CompTIA Linux+ Portable Command Guide_.: 52'
[resize4fs]: #resize4fs '```&#10;$ resize4fs&#10;```&#10;Resize ext4 filesystem'
[sfdisk]: #sfdisk '```&#10;$ sfdisk&#10;```&#10;Script-based partition table editor, similar to `fdisk` and `gdisk`; does not interface with GPT format and not designed for large partitions.'
[swapoff]: #swapoff '```&#10;$ swapoff&#10;```&#10;Stop using a swap file or device&#10;Rothwell, William. _CompTIA Linux+ Portable Command Guide_.: 292'
[swapon]: #swapon '```&#10;$ swapon&#10;```&#10;Take a valid swap device and enable it to be used as virtual memory on the system.&#10;Rothwell, William. _CompTIA Linux+/LPIC-1 Portable Command guide_.: 117'
[tune2fs]: #tune2fs '```&#10;$ tune2fs $DEVICE&#10;```&#10;Modify tunable parameters on the ext2 or ext3 filesystem on `$DEVICE`&#10;Haeder, Adam. _LPI Linux Certification in a Nutshell_. 2010.: 155'
[umount]: #umount '```&#10;$ umount&#10;```&#10;Unmount filesystems from filesystem hierarchy&#10;Haeder, Adam. _LPI Linux Certification in a Nutshell_. 2010.: 167'
[vifs]: #vifs '```&#10;$ vifs&#10;```&#10;Safely edit /etc/fstab file'
[xfs_info]: #xfs_info '```&#10;$ xfs_info $DEVICE&#10;```&#10;Display information about the XFS partition&#10;Haeder, Adam. _LPI Linux Certification in a Nutshell_. 2010.: 157'
[xfs_metadump]: #xfs_metadump '```&#10;$ xfs_metadump&#10;```&#10;Debugging tool that copies the metadata from an XFS filesystem to a file.&#10;Haeder, Adam. _LPI Linux Certification in a Nutshell_. 2010.: 160'
[df]: #df '```&#10;$ df $NAME&#10;```&#10;Report the number of free disk blocks and inodes available on all mounted filesystems or on the given $NAME, which can be a device name, directory name of a mount point, directory, or remote filesystem name&#10;Robbins, Arnold. _UNIX in a Nutshell_ 4th ed (2005): 56'
[iostat]: #iostat '```&#10;$ iostat&#10;```&#10;Display input/output statistics on devices, including partitions&#10;Rothwell, William. _CompTIA Linux+ Portable Command Guide_.: 48'
[lvcreate]: #lvcreate '```&#10;$ lvcreate&#10;```&#10;&#10;Eckert, Jason. _Linux+ Guide to Linux Certification_. Course Technology, 2012: 223'
[lvdisplay]: #lvdisplay '```&#10;$ lvdisplay&#10;```&#10;&#10;Eckert, Jason. _Linux+ Guide to Linux Certification_. Course Technology, 2012: 223'
[lvextend]: #lvextend '```&#10;$ lvextend&#10;```&#10;&#10;Eckert, Jason. _Linux+ Guide to Linux Certification_. Course Technology, 2012: 225'
[lvremove]: #lvremove '```&#10;lvremove&#10;```&#10;'
[lvs]: #lvs '```&#10;lvs&#10;```&#10;'
[lvscan]: #lvscan '```&#10;lvscan&#10;```&#10;&#10;Eckert, Jason. _Linux+ Guide to Linux Certification_. Course Technology, 2012: 225'
[mkntfs]: #mkntfs '```&#10;mkntfs&#10;mkfs.ntfs&#10;```&#10;Create an NTFS file system'
[pvcreate]: #pvcreate '```&#10;pvcreate&#10;```&#10;Convert existing devices into LVM physical volumes&#10;Rothwell, William. _CompTIA Linux+/LPIC-1 Portable Command guide_.: 21'
[pvdisplay]: #pvdisplay '```&#10;pvdisplay&#10;```&#10;Display information about a PV&#10;Rothwell, William. _CompTIA Linux+ Portable Command Guide_.: 45'
[pvremove]: #pvremove '```&#10;pvremove&#10;```&#10;'
[pvs]: #pvs '```&#10;pvs&#10;```&#10;'
[pvscan]: #pvscan '```&#10;pvscan&#10;```&#10;&#10;Eckert, Jason. _Linux+ Guide to Linux Certification_. Course Technology, 2012: 225'
[vgcreate]: #vgcreate '```&#10;vgcreate&#10;```&#10;&#10;Eckert, Jason. _Linux+ Guide to Linux Certification_. Course Technology, 2012: 222'
[vgdisplay]: #vgdisplay '```&#10;vgdisplay&#10;```&#10;Display information about a VG&#10;Rothwell, William. _CompTIA Linux+ Portable Command Guide_.: 45'
[vgextend]: #vgextend '```&#10;vgextend&#10;```&#10;Add a PV to an existing VG&#10;Rothwell, William. _CompTIA Linux+ Portable Command Guide_.: 45'
[vgreduce]: #vgreduce '```&#10;vgreduce&#10;```&#10;Remove a PV from a VG&#10;Rothwell, William. _CompTIA Linux+ Portable Command Guide_.: 45'
[vgremove]: #vgremove '```&#10;$ vgremove&#10;```&#10;Delete a VG&#10;Rothwell, William. _CompTIA Linux+ Portable Command Guide_.: 45'
[vgs]: #vgs '```&#10;$ vgs&#10;```&#10;'
[vgscan]: #vgscan '```&#10;vgscan&#10;```&#10;&#10;Eckert, Jason. _Linux+ Guide to Linux Certification_. Course Technology, 2012: 225'

**[Disk](#disk)**
[`blkid`][blkid] 
[`cryptsetup`][cryptsetup] 
[`dd`][dd] 
[`df`][df] 
[`dm-crypt`][dm-crypt] 
[`dumpe2fs`][dumpe2fs] 
[`e2fsck`][e2fsck] 
[`e2label`][e2label] 
[`eject`][eject] 
[`fdformat`][fdformat] 
[`fdisk`][fdisk] 
[`fsck`][fsck] 
[`fstrim`][fstrim] 
[`gdisk`][gdisk] 
[`hdiutil`][hdiutil] 
[`hdparm`][hdparm] 
[`ioping`][ioping] 
[`iostat`][iostat] 
[`iscsiadm`][iscsiadm] 
[`lsblk`][lsblk] 
[`mdadm`][mdadm] 
[`mke2fs`][mke2fs] 
[`mkfs`][mkfs] 
[`mkntfs`][mkntfs]
[`mkswap`][mkswap] 
[`mount`][mount] 
[`mt`][mt] 
[`parted`][parted] 
[`partprobe`][partprobe] 
[`partx`][partx] 
[`resize2fs`][resize2fs] 
[`resize4fs`][resize4fs] 
[`sfdisk`][sfdisk] 
[`swapoff`][swapoff] 
[`swapon`][swapon] 
[`tune2fs`][tune2fs] 
[`umount`][umount] 
[`vifs`][vifs] 
[`xfs_info`][xfs_info] 
[`xfs_metadump`][xfs_metadump] 

**Logical volume management**
[`lvcreate`][lvcreate] 
[`lvdisplay`][lvdisplay] 
[`lvextend`][lvextend] 
[`lvremove`][lvremove] 
[`lvs`][lvs] 
[`lvscan`][lvscan] 
[`pvcreate`][pvcreate] 
[`pvdisplay`][pvdisplay] 
[`pvremove`][pvremove] 
[`pvs`][pvs] 
[`pvscan`][pvscan] 
[`vgcreate`][vgcreate] 
[`vgdisplay`][vgdisplay] 
[`vgextend`][vgextend] 
[`vgreduce`][vgreduce] 
[`vgremove`][vgremove] 
[`vgs`][vgs] 
[`vgscan`][vgscan] 

<!-- File commands -->
[chattr]: #chattr '```&#10;$ chattr&#10;```&#10;Change file attributes&#10;Rothwell, William. _CompTIA Linux+ Portable Command Guide_.: 311-312'
[chgrp]: #chgrp '```&#10;$ chgrp&#10;```&#10;Change the group of one or more files, which can be a group ID number or a group name (located in "/etc/group"). You must own the file or be a privileged user to succeed with the command.&#10;Robbins, Arnold. _UNIX in a Nutshell_ 4th ed (2005): 34'
[chmod]: #chmod '```&#10;$ chmod&#10;```&#10;Change the access mode of one or more files&#10;Robbins, Arnold. _UNIX in a Nutshell_ 4th ed (2005): 35'
[chown]: #chown '```&#10;$ chown&#10;```&#10;Change the ownership of one or more files, which can be either a user ID number or a login name (located in "/etc/passwd")&#10;Robbins, Arnold. _UNIX in a Nutshell_ 4th ed (2005): 37'
[cksum]: #cksum '```&#10;$ cksum&#10;```&#10;Calculate and print a CRC sum for each file. The CRC algorithm is based on the polynomial used for Ethernet packets&#10;Robbins, Arnold. _UNIX in a Nutshell_ 4th ed (2005): 38'
[cp]: #cp '```&#10;$ cp $FILE $PATH&#10;```&#10;Copy `$FILE` to `$PATH`. If `$PATH` is an existing file, it is overwritten. If the input is a directory use `-r`.&#10;Robbins, Arnold. _UNIX in a Nutshell_ 4th ed (2005): 40'
[curl]: #curl '```&#10;$ curl&#10;```&#10;Retrieve files from the Internet, most often using FTP or HTTP (cf. `wget`)&#10;Robbins, Arnold. _UNIX in a Nutshell_ 4th ed (2005): 49'
[dd]: #dd '```&#10;$ dd&#10;```&#10;Perform multiple operations related to backing up data and creating files. One common use is to make a backup of an entire drive.&#10;Rothwell, William. _CompTIA Linux+ Portable Command Guide_.: 269'
[dirname]: #dirname '```&#10;$ dirname $PATH&#10;```&#10;Strip filename from `$PATH` (cf. `basename`)'
[dos2unix]: #dos2unix '```&#10;$ dos2unix&#10;```&#10;Convert files using the DOS extended character set to their ISO standard counterparts&#10;Robbins, Arnold. _UNIX in a Nutshell_ 4th ed (2005): 66'
[exif]: #exif '```&#10;$ exif&#10;```&#10;View image metadata, producing columnar output'
[fallocate]: #fallocate '```&#10;$ fallocate&#10;```&#10;Allocate and deallocate space to a file'
[file]: #file '```&#10;$ file&#10;```&#10;View image metadata'
[find]: #find '```&#10;$ find&#10;```&#10;Search recursively through directory trees for files or directories that match certain characters, either printing the file or directory or performing other operations on matches&#10;Haeder, Adam. _LPI Linux Certification in a Nutshell_. 2010.: 96'
[getfacl]: #getfacl '```&#10;$ getfacl&#10;```&#10;Display the ACL of a file&#10;Rothwell, William. _CompTIA Linux+ Portable Command Guide_.: 199'
[install]: #install '```&#10;$ install&#10;```&#10;Copy files while maintaining metadata'
[link]: #link '```&#10;$ link $FILE $OTHER&#10;```&#10;Create a link between two files, similar to `ln` but with no error checking'
[ln]: #ln '```&#10;$ ln&#10;```&#10;Create a link&#10;Rothwell, William. _CompTIA Linux+ Portable Command Guide_.: 132'
[locate]: #locate '```&#10;$ locate&#10;```&#10;Search for files based on a database that is typically created daily.&#10;Rothwell, William. _CompTIA Linux+ Portable Command Guide_.: 138'
[ls]: #ls '```&#10;$ ls&#10;```&#10;List files in a directory&#10;Rothwell, William. _CompTIA Linux+ Portable Command Guide_.: 131'
[lsattr]: #lsattr '```&#10;$ lsattr&#10;```&#10;Display the attributes for a file&#10;Rothwell, William. _CompTIA Linux+ Portable Command Guide_.: 311'
[lsof]: #lsof '```&#10;$ lsof&#10;```&#10;Display open files, open network ports, and network connections&#10;Rothwell, William. _CompTIA Linux+ Portable Command Guide_.: 303'
[md5sum]: #md5sum '```&#10;$ md5sum&#10;```&#10;Display MD5 checksum value for a file&#10;Rothwell, William. _CompTIA Linux+ Portable Command Guide_.: 275'
[mkdir]: #mkdir '```&#10;$ mkdir&#10;```&#10;Create one or more directories&#10;Haeder, Adam. _LPI Linux Certification in a Nutshell_. 2010.: 98'
[mktemp]: #mktemp '```&#10;$ mktemp&#10;```&#10;Create a temporary file or directory safely and print its name. These will not need to be manually cleaned up because they will be placed in the temporary directory /tmp'
[mv]: #mv '```&#10;$ mv&#10;```&#10;Move or rename files and directories&#10;Haeder, Adam. _LPI Linux Certification in a Nutshell_. 2010.: 98'
[rename]: #rename '```&#10;$ rename&#10;```&#10;Rename files using regex'
[rm]: #rm '```&#10;$ rm&#10;```&#10;Delete one or more files from the filesystem&#10;Haeder, Adam. _LPI Linux Certification in a Nutshell_. 2010.: 99'
[rmdir]: #rmdir '```&#10;$ rmdir&#10;```&#10;Delete empty directories&#10;Rothwell, William. _CompTIA Linux+ Portable Command Guide_.: 132'
[rsync]: #rsync '```&#10;$ rsync&#10;```&#10;Copy files remotely; used in situations where only updated files are to be transferred in order to preserve bandwidth.&#10;Rothwell, William. _CompTIA Linux+ Portable Command Guide_.: 131'
[scp]: #scp '```&#10;$ scp&#10;```&#10;Copy files to and from remote systems via `ssh`&#10;Rothwell, William. _CompTIA Linux+ Portable Command Guide_.: 130'
[setfacl]: #setfacl '```&#10;$ setfacl&#10;```&#10;Create an ACL on a file or directory.&#10;Rothwell, William. _CompTIA Linux+ Portable Command Guide_.: 199'
[setuid]: #setuid '```&#10;$ setuid&#10;```&#10;"set-user identification": permission bit which, if set on an executable file, will ensure that the file is granted access based on the owner of the file, rather than the use who is running it'
[stat]: #stat '```&#10;$ stat&#10;```&#10;See inode information of a file&#10;Rothwell, William. _CompTIA Linux+ Portable Command Guide_.: 135'
[touch]: #touch '```&#10;$ touch&#10;```&#10;Used to create empty files and to update modification and access timestamps of existing files.&#10;Rothwell, William. _CompTIA Linux+ Portable Command Guide_.: 129'
[tree]: #tree '```&#10;$ tree&#10;```&#10;Display contents of directories in a tree-like format'
[umask]: #umask '```&#10;$ umask&#10;```&#10;Set default permissions for files and directories&#10;Rothwell, William. _CompTIA Linux+ Portable Command Guide_.: 195'
[unlink]: #unlink '```&#10;$ unlink&#10;```&#10;Does essentially what `rm` does, but in a subtly different way.&#10;Rothwell, William. _CompTIA Linux+ Portable Command Guide_.: 135'
[updatedb]: #updatedb '```&#10;$ updatedb&#10;```&#10;Refresh (or create) the `slocate` database at /var/lib/slocate/slocate.db&#10;Haeder, Adam. _LPI Linux Certification in a Nutshell_. 2010.: 202'
[whereis]: #whereis '```&#10;$ whereis&#10;```&#10;Search for binary executables, source code, and manual pages in standard locations as well as the PATH and `$MANPATH`&#10;Rothwell, William. _CompTIA Linux+ Portable Command Guide_.: 139'
[which]: #which '```&#10;$ which $CMD&#10;```&#10;Determine the location of `$CMD` and display its full path&#10;Haeder, Adam. _LPI Linux Certification in a Nutshell_. 2010.: 200'

**[Hardware settings](#hw)**
`bluetoothctl`
[`insmod`][insmod]
[`lsmod`][lsmod]
`lspci`
`lsusb`
[`modprobe`][modprobe]
[`rmmod`][rmmod] 

**[Printing]** 
[**CUPS**][CUPS]
`cupsaccept`
`cupsenable`
`cupsdisable`
`cupsreject`
`lp`
`cancel`
**LPD**
`lpc`
`lpq`
`lpr`
`lprm`

**[Information](#diagnostic-and-benchmarking)**
[`ausearch`][ausearch]
[`bpftrace`][bpftrace]
[`date`][date]
[`df`][df]
[`du`][du]
[`free`][free]
[`glances`][glances]
[`hwclock`][hwclock]
[`loadaverage`][loadaverage]
[`logger`][logger]
[`logrotate`][logrotate]
[`lsb_release`][lsb_release]
[`man`][man]
[`mpstat`][mpstat]
[`nproc`][nproc]
[`ntpdate`][ntpdate]
[`printenv`][printenv]
[`rsyslogd`][rsyslogd]
[`sar`][sar]
[`sysbench`][sysbench]
[`syslogd`][syslogd]
[`time`][time]
[`timedatectl`][timedatectl]
[`tty`][tty]
[`uname`][uname]
[`uptime`][uptime]
[`vmstat`][vmstat] 

**[Init](#init-systems)**
_[Systemd][SystemD]_
`hostnamectl`
[`journalctl`][journalctl]
`localectl`
`systemctl`
`systemd-delta`
[`timedatectl`][timedatectl] 
_Sysvinit_
`chkconfig`
`init`
`service`
`telinit`
_Upstart_
`initctl`

<!-- Kernel commands -->
[dbus-monitor]: #dbus-monitor '```&#10;$ dbus-monitor&#10;```&#10;Monitor messages going through a D-Bus message bus'
[depmod]: #depmod '```&#10;$ depmod&#10;```&#10;Builds the modules.dep file, which contains module dependencies and is used by `modprobe` to determine which modules need to be loaded&#10;Rothwell, William. _CompTIA Linux+ Portable Command Guide_.: 15'
[dmesg]: #dmesg '```&#10;$ dmesg&#10;```&#10;Display in-memory copy of the kernel ring buffer&#10;Rothwell, William. _CompTIA Linux+ Portable Command Guide_.: 178'
[dracut]: #dracut '```&#10;$ dracut&#10;```&#10;Executed by `mkinitrd` but rarely used manually&#10;Rothwell, William. _CompTIA Linux+ Portable Command Guide_.: 8'
[insmod]: #insmod '```&#10;$ insmod&#10;```&#10;Insert a module into the running kernel&#10;Haeder, Adam. _LPI Linux Certification in a Nutshell_. 2010.: 15'
[journalctl]: #journalctl '```&#10;$ journalctl&#10;```&#10;&#10;Rothwell, William. _CompTIA Linux+/LPIC-1 Portable Command guide_.: 219'
[ldconfig]: #ldconfig '```&#10;$ ldconfig $LIBDIRS&#10;```&#10;Update the ld.so cache file with shared libraries specified on the command line in /usr/lib, /lib, directories found in /etc/ld.so.conf, and `$LIBDIRS`&#10;Haeder, Adam. _LPI Linux Certification in a Nutshell_. 2010.: 45'
[lsmod]: #lsmod '```&#10;$ lsmod&#10;```&#10;Display kernel modules that are loaded into memory&#10;Rothwell, William. _CompTIA Linux+ Portable Command Guide_.: 11'
[mkinitrd]: #mkinitrd '```&#10;$ mkinitrd&#10;```&#10;Creates initramfs file&#10;Rothwell, William. _CompTIA Linux+ Portable Command Guide_.: 8'
[modinfo]: #modinfo '```&#10;$ modinfo&#10;```&#10;Display information about a module from its `module_object_file`&#10;Haeder, Adam. _LPI Linux Certification in a Nutshell_. 2010.: 17'
[modprobe]: #modprobe '```&#10;$ modprobe&#10;```&#10;Insert modules, like `insmod`. In fact, `modprobe` is a wrapper around `insmod` which provides additional functionality.&#10;Haeder, Adam. _LPI Linux Certification in a Nutshell_. 2010.: 18'
[rmmod]: #rmmod '```&#10;$ rmmod&#10;```&#10;Remove modules from the running kernel.&#10;Haeder, Adam. _LPI Linux Certification in a Nutshell_. 2010.: 16'
[udevadm]: #udevadm '```&#10;$ udevadm&#10;```&#10;Load new rules into kernel memory, or verify they have taken effect, after changing a udev rule.&#10;Rothwell, William. _CompTIA Linux+ Portable Command Guide_.: 181'

**[Kernel](#kernel)**
[`dbus-monitor`][dbus-monitor]
[`depmod`][depmod]
[`dmesg`][dmesg]
[`dracut`][dracut]
[`insmod`][insmod]
[`journalctl`][journalctl]
[`ldconfig`][ldconfig]
[`lsmod`][lsmod]
[`mkinitrd`][mkinitrd]
[`modinfo`][modinfo]
[`modprobe`][modprobe]
[`rmmod`][rmmod]
[`udevadm`][udevadm] 

<!-- Mail commands -->
[biff]: #biff '```&#10;$ biff&#10;```&#10;Turn mail notifications on or off. With no arguments, `biff` indicates the current status&#10;Robbins, Arnold. _UNIX in a Nutshell_ 4th ed (2005): 27'
[exim]: #exim '```&#10;$ exim&#10;```&#10;'
[mail]: #mail '```&#10;$ mail&#10;```&#10;&#10;Rothwell, William. _CompTIA Linux+/LPIC-1 Portable Command guide_.: 222'
[mailmerge]: #mailmerge '```&#10;$ mailmerge&#10;```&#10;'
[mailq]: #mailq '```&#10;$ mailq&#10;```&#10;&#10;Rothwell, William. _CompTIA Linux+/LPIC-1 Portable Command guide_.: 223'
[mailx]: #mailx '```&#10;$ mailx&#10;```&#10;'
[makemap]: #makemap '```&#10;$ makemap&#10;```&#10;Execute after making a change to the `sendmail` access database /etc/access'
[msmtp]: #msmtp '```&#10;$ msmtp&#10;```&#10;'
[newaliases]: #newaliases '```&#10;$ newaliases&#10;```&#10;&#10;Eckert, Jason. _Linux+ Guide to Linux Certification_. Course Technology, 2012: 602'
[pine]: #pine '```&#10;$ pine&#10;```&#10;"Program for Internet news and email", popular MUA during the 1990s which has since been replaced by Alpine'
[postalias]: #postalias '```&#10;$ postalias&#10;```&#10;&#10;Rothwell, William. _CompTIA Linux+/LPIC-1 Portable Command guide_.: 224'
[postfix]: #postfix '```&#10;$ postfix&#10;```&#10;'
[postqueue]: #postqueue '```&#10;postqueue&#10;```&#10;&#10;Rothwell, William. _CompTIA Linux+/LPIC-1 Portable Command guide_.: 224'
[qmail]: #qmail '```&#10;$ qmail&#10;```&#10;'
[sendmail]: #sendmail '```&#10;$ sendmail&#10;```&#10;'

**[Mail](#mail)** 
[`biff`][biff] 
[`makemap`][makemap] 
[`newaliases`][newaliases] 
[`pine`][pine] 
[`mail`][mail] 
[`mailmerge`][mailmerge] 
[`mailq`][mailq] 
[`mailx`][mailx] 
[`msmtp`][msmtp] 
[`newaliases`][newaliases] 
[`postalias`][postalias] 
[`postqueue`][postqueue] 

**SMTP servers**
[`exim`][exim] 
[`postfix`][postfix] 
[`qmail`][qmail] 
[`sendmail`][sendmail] 

<!-- Network commands -->
[bmon]: #bmon '```&#10;$ bmon&#10;```&#10;Terminal-based graphical bandwidth monitor'
[brctl]: #brctl '```&#10;$ brctl&#10;```&#10;Create, modify, or view an Ethernet bridge, which connects separate networks into a single network from the perspective of users.&#10;Rothwell, William. _CompTIA Linux+ Portable Command Guide_.: 27'
[curl]: #curl '```&#10;$ curl&#10;```&#10;Noninteractively transfer data from a large number of protocols, including FTP, FTPS, HTTP, SCP, SFTP, SMB, SMBS, Telnet, and TFTP&#10;Rothwell, William. _CompTIA Linux+ Portable Command Guide_.: 90'
[dig]: #dig '```&#10;$ dig&#10;```&#10;Query DNS servers&#10;Robbins, Arnold. _UNIX in a Nutshell_ 4th ed (2005): 64'
[ethtool]: #ethtool '```&#10;$ ethtool&#10;```&#10;Display and configure network device settings.&#10;Rothwell, William. _CompTIA Linux+ Portable Command Guide_.: 22'
[firewall-cmd]: #firewall-cmd '```&#10;$ firewall-cmd&#10;```&#10;In Red Hat systems, the successor to `iptables` and like it a frontend to the `netfilter` protocols; places network traffic into "zones". Commands have to be written twice: once to affect running config and again to have the change saved'
[host]: #host '```&#10;$ host&#10;```&#10;Perform simple DNS queries&#10;Rothwell, William. _CompTIA Linux+ Portable Command Guide_.: 20'
[hping3]: #hping3 '```&#10;$ hping3&#10;```&#10;Active network smashing tool'
[ifconfig]: #ifconfig '```&#10;$ ifconfig&#10;```&#10;Obsolete program that configures network interfaces&#10;Haeder, Adam. _LPI Linux Certification in a Nutshell_. 2010.: 386'
[iftop]: #iftop '```&#10;$ iftop&#10;```&#10;Display network connections using the most bandwidth&#10;Rothwell, William. _CompTIA Linux+ Portable Command Guide_.: 281'
[ifup-wireless]: #ifup-wireless '```&#10;$ ifup-wireless&#10;```&#10;Configure wireless networks&#10;Rothwell, William. _CompTIA Linux+ Portable Command Guide_.: 28'
[ip]: #ip '```&#10;$ ip&#10;```&#10;Newer alternative to the old `ifconfig`&#10;Rothwell, William. _CompTIA Linux+ Portable Command Guide_.: 21'
[iperf]: #iperf '```&#10;$ iperf&#10;```&#10;Create tests of the throughput between two systems, requiring setup on both client and server&#10;Rothwell, William. _CompTIA Linux+ Portable Command Guide_.: 281'
[ipset]: #ipset '```&#10;$ ipset&#10;```&#10;Create a "set" of IP addresses to which firewall rules can be applied&#10;Rothwell, William. _CompTIA Linux+ Portable Command Guide_.: 282'
[iscsiadm]: #iscsiadm '```&#10;$ iscsiadm&#10;```&#10;Command-line utility allowing discovery and login to iSCSI targets'
[iw]: #iw '```&#10;$ iw&#10;```&#10;Show or manipulate wireless devices and their configuration'
[iwconfig]: #iwconfig '```&#10;$ iwconfig&#10;```&#10;Display or set information about wireless network interfaces.&#10;Rothwell, William. _CompTIA Linux+ Portable Command Guide_.: 25'
[iwlist]: #iwlist '```&#10;$ iwlist&#10;```&#10;Get detailed wireless information about a wireless interface'
[kinit]: #kinit '```&#10;$ kinit&#10;```&#10;Kerberos utility to obtain an individual ticket, which is then cached on the local system.&#10;Rothwell, William. _CompTIA Linux+ Portable Command Guide_.: 239'
[klist]: #klist '```&#10;$ klist&#10;```&#10;Display a list of cached Kerberos tickets&#10;Rothwell, William. _CompTIA Linux+ Portable Command Guide_.: 239'
[mtr]: #mtr '```&#10;$ mtr&#10;```&#10;Performs a `traceroute`-like operation every second&#10;Rothwell, William. _CompTIA Linux+ Portable Command Guide_.: 285'
[netcat]: #netcat '```&#10;$ netcat&#10;```&#10;Versatile utility for TCP or UDP connections&#10;Rothwell, William. _CompTIA Linux+ Portable Command Guide_.: 284'
[netplan]: #netplan '```&#10;$ netplan&#10;```&#10;Ubuntu network configuration tool'
[netstat]: #netstat '```&#10;$ netstat&#10;```&#10;Print network connections, routing tables, interface statistics, masquerade connections, and multi-cast memberships&#10;Rothwell, William. _CompTIA Linux+ Portable Command Guide_.: 18'
[nmap]: #nmap '```&#10;$ nmap&#10;```&#10;Probe a system for open ports&#10;Rothwell, William. _CompTIA Linux+ Portable Command Guide_.: 280'
[nmblookup]: #nmblookup '```&#10;$ nmblookup&#10;```&#10;Test NetBIOS name resolution&#10;Eckert, Jason. _Linux+ Guide to Linux Certification_. Course Technology, 2012: 591'
[nmcli]: #nmcli '```&#10;$ nmcli&#10;```&#10;Configure NetworkManager&#10;Rothwell, William. _CompTIA Linux+ Portable Command Guide_.: 26'
[nmtui]: #nmtui '```&#10;$ nmtui&#10;```&#10;Provide a text-based to configure NetworkManager.&#10;Rothwell, William. _CompTIA Linux+ Portable Command Guide_.: 27'
[nslookup]: #nslookup '```&#10;$ nslookup&#10;```&#10;Perform simple queries on DNS servers&#10;Rothwell, William. _CompTIA Linux+ Portable Command Guide_.: 19'
[ping]: #ping '```&#10;$ ping&#10;```&#10;Verify a remote host can respond to a network&#10;Rothwell, William. _CompTIA Linux+ Portable Command Guide_.: 18'
[rfkill]: #rfkill '```&#10;$ rfkill&#10;```&#10;tool for enabling and disabling wireless devices'
[route]: #route '```&#10;$ route&#10;```&#10;Display or modify routing table&#10;Rothwell, William. _CompTIA Linux+ Portable Command Guide_.: 21'
[sftp]: #sftp '```&#10;$ sftp&#10;```&#10;Securely transfer files over ssh&#10;Rothwell, William. _CompTIA Linux+ Portable Command Guide_.: 274'
[ss]: #ss '```&#10;ss&#10;```&#10;Display socket information.&#10;Rothwell, William. _CompTIA Linux+ Portable Command Guide_.: 25'
[ssh]: #ssh '```&#10;ssh&#10;```&#10;&#10;Rothwell, William. _CompTIA Linux+/LPIC-1 Portable Command guide_.: 266'
[ssh-add]: #ssh-add '```&#10;ssh-add&#10;```&#10;&#10;Rothwell, William. _CompTIA Linux+/LPIC-1 Portable Command guide_.: 268'
[ssh-agent]: #ssh-agent '```&#10;ssh-agent&#10;```&#10;&#10;Rothwell, William. _CompTIA Linux+/LPIC-1 Portable Command guide_.: 268'
[ssh-keygen]: #ssh-keygen '```&#10;ssh-keygen&#10;```&#10;&#10;Rothwell, William. _CompTIA Linux+/LPIC-1 Portable Command guide_.: 267'
[ssh-keyscan]: #ssh-keyscan '```&#10;ssh-keyscan&#10;```&#10;'
[stty]: #stty '```&#10;$ stty&#10;```&#10;'
[tcpdump]: #tcpdump '```&#10;$ tcpdump&#10;```&#10;Inspect IP packets (Wireshark is a GUI-based alternative)&#10;Rothwell, William. _CompTIA Linux+ Portable Command Guide_.: 282'
[tracepath]: #tracepath '```&#10;tracepath&#10;```&#10;Similar to `traceroute`, but with fewer options and no requirement for superuser privileges&#10;Rothwell, William. _CompTIA Linux+ Portable Command Guide_.: 287'
[tracepath6]: #tracepath6 '```&#10;tracepath6&#10;```&#10;&#10;Rothwell, William. _CompTIA Linux+/LPIC-1 Portable Command guide_.: 246'
[traceroute]: #traceroute '```&#10;traceroute&#10;```&#10;Follow the path a packet takes between two hosts&#10;Rothwell, William. _CompTIA Linux+ Portable Command Guide_.: 285'
[tshark]: #tshark '```&#10;tshark&#10;```&#10;Wireshark terminal interface&#10;Rothwell, William. _CompTIA Linux+ Portable Command Guide_.: 283'
[wget]: #wget '```&#10;$ wget&#10;```&#10;Noninteractive tool to download files from remote systems via HTTP, HTTPS, or FTP.&#10;Rothwell, William. _CompTIA Linux+ Portable Command Guide_.: 89'
[whois]: #whois '```&#10;$ whois&#10;```&#10;Determine domain ownership&#10;Rothwell, William. _CompTIA Linux+ Portable Command Guide_.: 287'
[xinetd]: #xinetd '```&#10;$ xinetd&#10;```&#10;Internet Super Daemon provided an alternate method of connecting to various outdated network services. Should be turned off nowadays.'

**[Network](#networking)** 
[`bmon`][bmon] 
[`brctl`][brctl] 
[`curl`][curl] 
[`dig`][dig] 
[`ethtool`][ethtool] 
[`firewall-cmd`][firewall-cmd] 
[`host`][host] 
[`hping3`][hping3] 
[`ifconfig`][ifconfig] 
[`iftop`][iftop] 
[`ifup-wireless`][ifup-wireless] 
[`ip`][ip] 
[`iperf`][iperf] 
[`ipset`][ipset] 
[`iscsiadm`][iscsiadm] 
[`iw`][iw] 
[`iwconfig`][iwconfig] 
[`iwlist`][iwlist] 
[`kinit`][kinit] 
[`klist`][klist] 
[`mtr`][mtr] 
[`netcat`][netcat] 
[`netplan`][netplan] 
[`netstat`][netstat] 
[`nmap`][nmap] 
[`nmblookup`][nmblookup] 
[`nmcli`][nmcli] 
[`nmtui`][nmtui] 
[`nslookup`][nslookup] 
[`ping`][ping] 
[`rfkill`][rfkill] 
[`route`][route] 
[`sftp`][sftp] 
[`ss`][ss] 
[`ssh`][ssh] 
[`ssh-add`][ssh-add] 
[`ssh-agent`][ssh-agent] 
[`ssh-keygen`][ssh-keygen] 
[`ssh-keyscan`][ssh-keyscan] 
[`stty`][stty] 
[`tcpdump`][tcpdump] 
[`tracepath`][tracepath] 
[`tracepath6`][tracepath6] 
[`traceroute`][traceroute] 
[`tshark`][tshark] 
[`wget`][wget] 
[`whois`][whois] 
[`xinetd`][xinetd] 

<!-- Package managers -->
[add-apt-repository]: #add-apt-repository '```&#10;$ add-apt-repository&#10;```&#10;'
[alien]: #alien '```&#10;$ alien&#10;```&#10;Convert between or install package types native to other distributions, including Red Hat .rpm, Stampede .slp, Slackware .tgz, and generic .tar.gz files.&#10;Haeder, Adam. _LPI Linux Certification in a Nutshell_. 2010.: 52'
[apt]: #apt '```&#10;$ apt&#10;```&#10;'
[apt-cache]: #apt-cache '```&#10;$ apt-cache&#10;```&#10;Display package information regarding the package cache&#10;Rothwell, William. _CompTIA Linux+ Portable Command Guide_.: 81'
[apt-get]: #apt-get '```&#10;$ apt-get&#10;```&#10;Part of the Advanced Package Tool (APT) management system.&#10;Haeder, Adam. _LPI Linux Certification in a Nutshell_. 2010.: 50'
[apt-key]: #apt-key '```&#10;$ apt-key&#10;```&#10;Manage the list of keys used by apt for authentication.'
[brew]: #brew '```&#10;$ brew&#10;```&#10;'
[dnf]: #dnf '```&#10;$ dnf&#10;```&#10;Package manager for Red Hat systems that supercedes `yum`&#10;Rothwell, William. _CompTIA Linux+ Portable Command Guide_.: 86'
[dpkg]: #dpkg '```&#10;$ dpkg&#10;```&#10;Manage local Debian packages&#10;Rothwell, William. _CompTIA Linux+/LPIC-1 Portable Command guide_.: 39'
[dpkg-reconfigure]: #dpkg-reconfigure '```&#10;$ dpkg-reconfigure&#10;```&#10;Run the configuration script that is typically installed as part of the installation process.&#10;Rothwell, William. _CompTIA Linux+/LPIC-1 Portable Command guide_.: 39'
[dselect]: #dselect '```&#10;$ dselect&#10;```&#10;Interactive, menu-driven frontend tool for `dpkg`, usually invoked without parameters. It allows you to interactively manage packages by selecting them for installation, removal, configuration, etc.&#10;Haeder, Adam. _LPI Linux Certification in a Nutshell_. 2010.: 51'
[galliumos-repodist]: #galliumos-repodist '```&#10;$ galliumos-repodist&#10;```&#10;Display all available GalliumOS repository distributions, along with their current configuration status for your machine.'
[gem]: #gem '```&#10;$ gem&#10;```&#10;'
[pacman]: #pacman '```&#10;$ pacman&#10;```&#10;'
[pip]: #pip '```&#10;$ pip&#10;```&#10;'
[rpm]: #rpm '```&#10;$ rpm&#10;```&#10;Install, upgrade, and remove .rpm packages&#10;Rothwell, William. _CompTIA Linux+ Portable Command Guide_.: 78'
[snap]: #snap '```&#10;snap&#10;```&#10;'
[yay]: #yay '```&#10;$ yay&#10;```&#10;'
[yum]: #yum '```&#10;$ yum&#10;```&#10;Package manager for Red Hat systems&#10;Rothwell, William. _CompTIA Linux+ Portable Command Guide_.: 83'
[yumdownloader]: #yumdownloader '```&#10;$ yumdownloader&#10;```&#10;Download software packages without installing them&#10;Rothwell, William. _CompTIA Linux+ Portable Command Guide_.: 84'
[zypper]: #zypper '```&#10;$ zypper&#10;```&#10;Package manager for SUSE with a syntax similar to that of `yum`&#10;Rothwell, William. _CompTIA Linux+ Portable Command Guide_.: 86'

**[Package managers](#package-managers)** 
[`add-apt-repository`][add-apt-repository] 
[`alien`][alien] 
[`apt`][apt] 
[`apt-cache`][apt-cache] 
[`apt-get`][apt-get] 
[apt-key][apt-key]
[`brew`][brew] 
[`dnf`][dnf] 
[`dpkg`][dpkg] 
[`dpkg-reconfigure`][dpkg-reconfigure] 
[`dselect`][dselect] 
[galliumos-repodist][galliumos-repodist]
[`gem`][gem] 
[`pacman`][pacman] 
[`pip`][pip] 
[`rpm`][rpm] 
[`snap`][snap] 
[`yay`][yay] 
[`yum`][yum] 
[`yumdownloader`][yumdownloader] 
[`zypper`][zypper] 

<!-- Process control -->
[at]: #at '```&#10;$ at&#10;```&#10;Schedule one or more commands to be executed at a specific time in the future.&#10;After specifying a future time on the command-line, the `at>` prompt appears, allowing you to specify a series of shell commands which can be terminated with Ctrl+D (EOF)&#10;Rothwell, William. _CompTIA Linux+/LPIC-1 Portable Command guide_.: 195'
[atq]: #atq '```&#10;$ atq&#10;```&#10;'
[atrm]: #atrm '```&#10;$ atrm&#10;```&#10;'
[bg]: #bg '```&#10;$ bg&#10;```&#10;Restart a suspended process in the background. Specify the number of the job according to the output of `jobs`, preceded by "%".&#10;Rothwell, William. _CompTIA Linux+ Portable Command Guide_.: 171'
[fg]: #fg '```&#10;$ fg $JOB&#10;```&#10;Place `$JOB` in the foreground&#10;Haeder, Adam. _LPI Linux Certification in a Nutshell_. 2010.: 119'
[jobs]: #jobs '```&#10;$ jobs&#10;```&#10;List active jobs&#10;Haeder, Adam. _LPI Linux Certification in a Nutshell_. 2010.: 119'
[kill]: #kill '```&#10;$ kill&#10;```&#10;Send signals to processes&#10;Haeder, Adam. _LPI Linux Certification in a Nutshell_. 2010.: 116'
[killall]: #killall '```&#10;$ killall&#10;```&#10;Stop all processes of a given name&#10;Rothwell, William. _CompTIA Linux+/LPIC-1 Portable Command guide_.: 96'
[lsns]: #lsns '```&#10;$ lsns&#10;```&#10;List existing namespaces. Namespace with which PIDs can also be accessed'
[nice]: #nice '```&#10;$ nice&#10;```&#10;Assign a nice number to a new process at start time.&#10;Haeder, Adam. _LPI Linux Certification in a Nutshell_. 2010.: 120'
[nohup]: #nohup '```&#10;$ nohup&#10;```&#10;Run a command immune to hangups, with output to a non-TTY terminal.&#10;Haeder, Adam. _LPI Linux Certification in a Nutshell_. 2010.: 119'
[pgrep]: #pgrep '```&#10;$ pgrep&#10;```&#10;List PIDs associated with a program name, similar to `ps -e | grep`&#10;Rothwell, William. _CompTIA Linux+ Portable Command Guide_.: 304'
[pidof]: #pidof '```&#10;$ pidof&#10;```&#10;Query system to discover the PID of any named application'
[pkill]: #pkill '```&#10;$ pkill&#10;```&#10;Kill a process by providing a process name, user name, or group name&#10;Rothwell, William. _CompTIA Linux+ Portable Command Guide_.: 305'
[ps]: #ps '```&#10;$ ps&#10;```&#10;List processes that are running on the system&#10;Rothwell, William. _CompTIA Linux+ Portable Command Guide_.: 303'
[pstree]: #pstree '```&#10;$ pstree&#10;```&#10;Display a hierarchical list of processes in a tree format; handy for understanding how parent/child process relationships are setup&#10;Haeder, Adam. _LPI Linux Certification in a Nutshell_. 2010.: 110'
[renice]: #renice '```&#10;$ renice&#10;```&#10;Alter the nice number of a running process&#10;Haeder, Adam. _LPI Linux Certification in a Nutshell_. 2010.: 122'
[strace]: #system-calls '```&#10;$ strace&#10;```&#10;debugging tool that displays a trace of all system calls made by a process&#10;Sobell, Mark. _Practical Guide to Linux_. 2017.: 418'
[top]: #top '```&#10;$ top&#10;```&#10;Display continuously updated display of processes similar to `ps`&#10;Haeder, Adam. _LPI Linux Certification in a Nutshell_. 2010.: 112'

**[Process control](#process-control)** 
[`at`][at] 
[`atq`][atq] 
[`atrm`][atrm] 
[`bg`][bg] 
[`fg`][fg] 
[`jobs`][jobs] 
[`kill`][kill] 
[`killall`][killall] 
[`lsns`][lsns] 
[`nice`][nice] 
[`nohup`][nohup] 
[`pgrep`][pgrep] 
[`pidof`][pidof] 
[`pkill`][pkill] 
[`ps`][ps] 
[`pstree`][pstree] 
[`renice`][renice] 
[`strace`][strace] 
[`top`][top] 
`unshare`

**Kubernetes**
`kubeadm`
`kubectl`

<!-- Remote administration -->
[curl]: #curl '```&#10;$ curl&#10;```&#10;Noninteractively transfer data from a large number of protocols, including FTP, FTPS, HTTP, SCP, SFTP, SMB, SMBS, Telnet, and TFTP&#10;Rothwell, William. _CompTIA Linux+ Portable Command Guide_.: 90'
[ftp]: #ftp '```&#10;$ ftp&#10;```&#10;Establish an interactive FTP connection with a host to transfer files interactively.&#10;Haeder, Adam. _LPI Linux Certification in a Nutshell_. 2010.: 378'
[rsync]: #rsync '```&#10;rsync&#10;```&#10;Copy files remotely; used in situations where only updated files are to be transferred in order to preserve bandwidth.&#10;Rothwell, William. _CompTIA Linux+ Portable Command Guide_.: 131'
[ssh]: #ssh '```&#10;$ ssh&#10;```&#10;&#10;Rothwell, William. _CompTIA Linux+/LPIC-1 Portable Command guide_.: 266'
[ssh-add]: #ssh-add '```&#10;$ ssh-add&#10;```&#10;&#10;Rothwell, William. _CompTIA Linux+/LPIC-1 Portable Command guide_.: 268'
[ssh-agent]: #ssh-agent '```&#10;$ ssh-agent&#10;```&#10;&#10;Rothwell, William. _CompTIA Linux+/LPIC-1 Portable Command guide_.: 268'
[ssh-keygen]: #ssh-keygen '```&#10;$ ssh-keygen&#10;```&#10;&#10;Rothwell, William. _CompTIA Linux+/LPIC-1 Portable Command guide_.: 267'
[ssh-keyscan]: #ssh-keyscan '```&#10;$ ssh-keyscan&#10;```&#10;'
[stty]: #stty '```&#10;stty&#10;```&#10;'
[telnet]: #telnet '```&#10;telnet&#10;```&#10;Establish a connection to a host.&#10;Haeder, Adam. _LPI Linux Certification in a Nutshell_. 2010.: 380'
[vncpasswd]: #vncpasswd '```&#10;$ vncpasswd&#10;```&#10;&#10;Eckert, Jason. _Linux+ Guide to Linux Certification_. Course Technology, 2012: 561'
[vncviewer]: #vncviewer '```&#10;$ vncviewer&#10;```&#10;&#10;Eckert, Jason. _Linux+ Guide to Linux Certification_. Course Technology, 2012: 561'
[sshfs]: #sshfs '```&#10;sshfs&#10;```&#10;'

**[Remote administration](#remote-administration)** 
[`curl`][curl] 
[`ftp`][ftp] 
[`rsync`][rsync] 
[`ssh`][ssh] 
[`ssh-add`][ssh-add] 
[`ssh-agent`][ssh-agent] 
[`ssh-keygen`][ssh-keygen] 
[`ssh-keyscan`][ssh-keyscan] 
[`stty`][stty] 
[`telnet`][telnet] 
[`vncpasswd`][vncpasswd] 
[`vncviewer`][vncviewer] 
[`sshfs`][sshfs] 

<!-- SELinux -->
[chcon]: #chcon '```&#10;$ chcon&#10;```&#10;Change context of a file or directory&#10;Rothwell, William. _CompTIA Linux+ Portable Command Guide_.: 207'
[getenforce]: #getenforce '```&#10;$ getenforce&#10;```&#10;Determine the current SELinux mode&#10;Rothwell, William. _CompTIA Linux+ Portable Command Guide_.: 205'
[getsebool]: #getsebool '```&#10;$ getsebool&#10;```&#10;Display names and values of SELinux Booleans&#10;Rothwell, William. _CompTIA Linux+ Portable Command Guide_.: 206'
[restorecon]: #restorecon '```&#10;$ restorecon&#10;```&#10;Reset default security context on a file or directory&#10;Rothwell, William. _CompTIA Linux+ Portable Command Guide_.: 207'
[semanage]: #semanage '```&#10;$ semanage&#10;```&#10;Edit security contexts for files and ports&#10;Rothwell, William. _CompTIA Linux+ Portable Command Guide_.: 206'
[sestatus]: #sestatus '```&#10;$ sestatus&#10;```&#10;Display status of SELinux&#10;Rothwell, William. _CompTIA Linux+ Portable Command Guide_.: 205'
[setenforce]: #setenforce '```&#10;$ setenforce&#10;```&#10;Change SELinux mode&#10;Rothwell, William. _CompTIA Linux+ Portable Command Guide_.: 205'
[setsebool]: #setsebool '```&#10;$ setsebool&#10;```&#10;Set an SELinux Boolean&#10;Rothwell, William. _CompTIA Linux+ Portable Command Guide_.: 206'

**[SELinux][SELinux]** 
[`chcon`][chcon]
[`getenforce`][getenforce]
[`getsebool`][getsebool]
[`restorecon`][restorecon]
[`semanage`][semanage]
[`sestatus`][sestatus]
[`setenforce`][setenforce]
[`setsebool`][setsebool] 

<!-- Shell and environment commands -->
[apropos]: #apropos '```&#10;$ apropos $KEYWORDS&#10;```&#10;Look up one or more `$KEYWORDS` in the online manpages (equivalent to `man -k`)'
[env]: #env '```&#10;$ env&#10;```&#10;Display the current environment, or set them to a new value if specified.&#10;Robbins, Arnold. _UNIX in a Nutshell_ 4th ed (2005): 75'
[export]: #export '```&#10;$ export&#10;```&#10;Convert an existing local variable to an environment vairable&#10;Rothwell, William. _CompTIA Linux+/LPIC-1 Portable Command guide_.: 53'
[history]: #history '```&#10;$ history&#10;```&#10;Display the contents of the history command list&#10;Rothwell, William. _CompTIA Linux+/LPIC-1 Portable Command guide_.: 57'
[man]: #man '```&#10;$ man&#10;```&#10;Discover additional information about a command&#10;Rothwell, William. _CompTIA Linux+/LPIC-1 Portable Command guide_.: 55'
[nohup]: #nohup '```&#10;$ nohup&#10;```&#10;Start a child process which will not end when the parent does.&#10;Rothwell, William. _CompTIA Linux+/LPIC-1 Portable Command guide_.: 92'
[pwd]: #pwd '```&#10;$ pwd&#10;```&#10;Display the current directory of the shell&#10;Rothwell, William. _CompTIA Linux+/LPIC-1 Portable Command guide_.: 54'
[sleep]: #sleep '```&#10;sleep $N&#10;```&#10;Wait `$N` seconds before executing another command'
[su]: #su '```&#10;su&#10;```&#10;&#10;Rothwell, William. _CompTIA Linux+/LPIC-1 Portable Command guide_.: 254'
[sudo]: #sudo '```&#10;$ sudo&#10;```&#10;&#10;Rothwell, William. _CompTIA Linux+/LPIC-1 Portable Command guide_.: 253'
[tee]: #tee '```&#10;tee&#10;```&#10;Send STDOUT to the terminal and to a file&#10;Rothwell, William. _CompTIA Linux+/LPIC-1 Portable Command guide_.: 86'
[unalias]: #unalias '```&#10;unalias&#10;```&#10;&#10;Rothwell, William. _CompTIA Linux+/LPIC-1 Portable Command guide_.: 157'
[watch]: #watch '```&#10;watch&#10;```&#10;Repeat a command at regular intervals and watch its changing output'
[whatis]: #whatis '```&#10;whatis&#10;```&#10;Look up one or more commands in the online manpages and display a brief description'
[where]: #where '```&#10;where&#10;```&#10;&#10;Rothwell, William. _CompTIA Linux+/LPIC-1 Portable Command guide_.: 167'
[whereis]: #whereis '```&#10;whereis&#10;```&#10;&#10;Rothwell, William. _CompTIA Linux+/LPIC-1 Portable Command guide_.: 147'
[which]: #which '```&#10;which&#10;```&#10;&#10;Rothwell, William. _CompTIA Linux+/LPIC-1 Portable Command guide_.: 147'
[xargs]: #xargs '```&#10;xargs $CMD&#10;```&#10;Execute `$CMD` followed by optional arguments.&#10;Haeder, Adam. _LPI Linux Certification in a Nutshell_. 2010.: 107'

<!-- System administration commands -->
[adduser]: #adduser '```&#10;$ adduser&#10;```&#10;create a new user or update default new user information'
[chage]: #chage '```&#10;$ chage&#10;```&#10;Maintain the password aging limits on a user account&#10;Haeder, Adam. _LPI Linux Certification in a Nutshell_. 2010.: 416'
[chgrp]: #chgrp '```&#10;$ chgrp&#10;```&#10;&#10;Eckert, Jason. _Linux+ Guide to Linux Certification_. Course Technology, 2012: 155'
[chmod]: #chmod '```&#10;$ chmod&#10;```&#10;&#10;Eckert, Jason. _Linux+ Guide to Linux Certification_. Course Technology, 2012: 159'
[edquota]: #edquota '```&#10;$ edquota $USER&#10;```&#10;Create or edit disk quota of `$USER`&#10;Rothwell, William. _CompTIA Linux+ Portable Command Guide_.: 99'
[gpasswd]: #gpasswd '```&#10;$ gpasswd $GROUP&#10;```&#10;Interactively set the password for `$GROUP`&#10;Haeder, Adam. _LPI Linux Certification in a Nutshell_. 2010.: 326'
[groupadd]: #groupadd '```&#10;$ groupadd $GROUP&#10;```&#10;Add `$GROUP` to the system&#10;Haeder, Adam. _LPI Linux Certification in a Nutshell_. 2010.: 325'
[groupdel]: #groupdel '```&#10;$ groupdel $GROUP&#10;```&#10;Delete `$GROUP` from the system&#10;Haeder, Adam. _LPI Linux Certification in a Nutshell_. 2010.: 325'
[groupmod]: #groupmod '```&#10;$ groupmod $GROUP&#10;```&#10;Modify the parameters of `$GROUP`&#10;Haeder, Adam. _LPI Linux Certification in a Nutshell_. 2010.: 325'
[groups]: #groups '```&#10;$ groups $USER&#10;```&#10;Show the groups that `$USER` belongs to (default is effective user)'
[last]: #last '```&#10;$ last $USER&#10;```&#10;Display history of successful logins'
[lastb]: #lastb '```&#10;$ lastb&#10;```&#10;Display failed login attempts&#10;Rothwell, William. _CompTIA Linux+ Portable Command Guide_.: 255'
[passwd]: #passwd '```&#10;$ passwd $USER&#10;```&#10;Interactively set the password for `$USER`&#10;Haeder, Adam. _LPI Linux Certification in a Nutshell_. 2010.: 325'
[quota]: #quota '```&#10;$ quota&#10;```&#10;Display quota limits on user or group&#10;Haeder, Adam. _LPI Linux Certification in a Nutshell_. 2010.: 169'
[quotacheck]: #quotacheck '```&#10;$ quotacheck&#10;```&#10;Examine filesystems and compile quota databases&#10;Haeder, Adam. _LPI Linux Certification in a Nutshell_. 2010.: 171'
[quotaoff]: #quotaoff '```&#10;$ quotaoff&#10;```&#10;Disable disk quotas on one or more filesystems&#10;Haeder, Adam. _LPI Linux Certification in a Nutshell_. 2010.: 171'
[quotaon]: #quotaon '```&#10;$ quotaon&#10;```&#10;Enable previously configure disk quotas on one or more filesystems&#10;Haeder, Adam. _LPI Linux Certification in a Nutshell_. 2010.: 170'
[repquota]: #repquota '```&#10;$ repquota&#10;```&#10;Display quotas for an entire filesystem&#10;Rothwell, William. _CompTIA Linux+ Portable Command Guide_.: 101'
[su]: #su '```&#10;$ su&#10;```&#10;Allow a user to shift user accounts&#10;Rothwell, William. _CompTIA Linux+ Portable Command Guide_.: 209'
[sudo]: #sudo '```&#10;sudo&#10;```&#10;Run commands as other users (typically as the root user).&#10;Rothwell, William. _CompTIA Linux+ Portable Command Guide_.: 209'
[sudoedit]: #sudoedit '```&#10;sudoedit&#10;```&#10;Edit a file using sudo&#10;Rothwell, William. _CompTIA Linux+ Portable Command Guide_.: 210'
[timedatectl]: #timedatectl '```&#10;timedatectl&#10;```&#10;&#10;Rothwell, William. _CompTIA Linux+/LPIC-1 Portable Command guide_.: 205'
[tzconfig]: #tzconfig '```&#10;tzconfig&#10;```&#10;Set time zone by setting a symbolic link from /etc/localtime to a file in /usr/share/zoneinfo&#10;Haeder, Adam. _LPI Linux Certification in a Nutshell_. 2010.: 330'
[tzselect]: #tzselect '```&#10;tzselect&#10;```&#10;Menu-based script that interactively determines appropriate value for `$TZ` environment variable&#10;Haeder, Adam. _LPI Linux Certification in a Nutshell_. 2010.: 331'
[ulimit]: #ulimit '```&#10;ulimit $USER&#10;```&#10;Display or set a account limits of `$USER`&#10;Rothwell, William. _CompTIA Linux+ Portable Command Guide_.: 201'
[useradd]: #useradd '```&#10;useradd $USER&#10;```&#10;Create the account `$USER` according to system defaults and specified options.&#10;Haeder, Adam. _LPI Linux Certification in a Nutshell_. 2010.: 323'
[userdel]: #userdel '```&#10;userdel $USER&#10;```&#10;Delete an existing user account&#10;Haeder, Adam. _LPI Linux Certification in a Nutshell_. 2010.: 324'
[usermod]: #usermod '```&#10;usermod&#10;```&#10;Modify a user account&#10;Rothwell, William. _CompTIA Linux+ Portable Command Guide_.: 94'
[visudo]: #visudo '```&#10;visudo&#10;```&#10;Safely edit the /etc/sudoers file'
[w]: #w '```&#10;w&#10;```&#10;Display output similar to that of `uptime` for all logged-in users&#10;Rothwell, William. _CompTIA Linux+ Portable Command Guide_.: 97'
[wall]: #wall '```&#10;wall&#10;```&#10;Broadcast a message to all users who are currently logged in&#10;Rothwell, William. _CompTIA Linux+/LPIC-1 Portable Command guide_.: 16'
[who]: #who '```&#10;who&#10;```&#10;Display currently users currently logged in&#10;Rothwell, William. _CompTIA Linux+ Portable Command Guide_.: 97'
[whoami]: #whoami '```&#10;whoami&#10;```&#10;Display effective user ID&#10;Rothwell, William. _CompTIA Linux+ Portable Command Guide_.: 96'

**[System administration](#system-administration)** 
[`adduser`][adduser] 
[`chage`][chage] 
[`chgrp`][chgrp] 
[`chmod`][chmod] 
[`edquota`][edquota] 
[`gpasswd`][gpasswd] 
[`groupadd`][groupadd] 
[`groupdel`][groupdel] 
[`groupmod`][groupmod] 
[`groups`][groups] 
[`last`][last] 
[`lastb`][lastb] 
[`passwd`][passwd] 
[`quota`][quota] 
[`quotacheck`][quotacheck] 
[`quotaoff`][quotaoff] 
[`quotaon`][quotaon] 
[`repquota`][repquota] 
[`su`][su] 
[`sudo`][sudo] 
[`sudoedit`][sudoedit] 
[`timedatectl`][timedatectl] 
[`tzconfig`][tzconfig] 
[`tzselect`][tzselect] 
[`ulimit`][ulimit] 
[`useradd`][useradd] 
[`userdel`][userdel] 
[`usermod`][usermod] 
[`visudo`][visudo] 
[`w`][w] 
[`wall`][wall] 
[`who`][who] 
[`whoami`][whoami] 

<!-- Text commands -->
[cat]: #cat '```&#10;$ cat&#10;```&#10;Display contents of text files&#10;Rothwell, William. _CompTIA Linux+ Portable Command Guide_.: 115'
[cmp]: #cmp '```&#10;$ cmp $FILE $OTHER&#10;```&#10;Compare `$FILE` with `$OTHER`, or STDIN if one or the other is not provided (cf. `comm` and `diff`). Exits with 0 if files are identical or 1 if they are not.&#10;Robbins, Arnold. _UNIX in a Nutshell_ 4th ed (2005): 39'
[comm]: #comm '```&#10;$ comm $FILE $OTHER&#10;```&#10;Compare lines common to the sorted files `$FILE` and `$OTHER`. Output is in 3 colums: lines unique to `$FILE`, lines unique to `$OTHER`, and lines common to both.&#10;Robbins, Arnold. _UNIX in a Nutshell_ 4th ed (2005): 39'
[csplit]: #csplit '```&#10;$ csplit&#10;```&#10;Separate `$FILE` into sections and place sections in files named "xx00" through "xxn" (n < 100)&#10;Robbins, Arnold. _UNIX in a Nutshell_ 4th ed (2005): 46'
[cut]: #cut '```&#10;$ cut&#10;```&#10;Select a list of columns or fields from one or more files&#10;Robbins, Arnold. _UNIX in a Nutshell_ 4th ed (2005): 50'
[diff]: #diff '```&#10;$ diff $FILE $OTHER&#10;```&#10;Report lines that differ between `$FILE` and `$OTHER`. Output consists of lines of context from each file, with `$FILE` text flagged by a "&lt;" and `$OTHER` text by a "&gt;". (cf. `cmp`, `comm`, `diff3`, `dircmp`, and `sdiff`).&#10;Robbins, Arnold. _UNIX in a Nutshell_ 4th ed (2005): 58'
[diff3]: #diff3 '```&#10;$ diff3&#10;```&#10;Compare three files and report differences&#10;Robbins, Arnold. _UNIX in a Nutshell_ 4th ed (2005): 63'
[ed]: #ed '```&#10;$ ed&#10;```&#10;Line-oriented text editor, superceded by `vi` and `ex`&#10;Robbins, Arnold. _UNIX in a Nutshell_ 4th ed (2005): 70'
[egrep]: #egrep '```&#10;$ egrep&#10;```&#10;Equivalent to `grep -E`&#10;Rothwell, William. _CompTIA Linux+ Portable Command Guide_.: 128'
[ex]: #ex '```&#10;$ ex&#10;```&#10;Line-oriented text editor, a superset of `ed` and the root of `vi`.&#10;Robbins, Arnold. _UNIX in a Nutshell_ 4th ed (2005): 78'
[expand]: #expand '```&#10;$ expand&#10;```&#10;Convert Tabs to spaces&#10;Haeder, Adam. _LPI Linux Certification in a Nutshell_. 2010.: 79'
[fgrep]: #fgrep '```&#10;$ fgrep $PATTERN&#10;```&#10;Search one or more files for lines that match a literal, text-string `$PATTERN`&#10;Robbins, Arnold. _UNIX in a Nutshell_ 4th ed (2005): 82'
[fmt]: #fmt '```&#10;$ fmt&#10;```&#10;Format text to a specified width by filling lines and removing newline characters&#10;Haeder, Adam. _LPI Linux Certification in a Nutshell_. 2010.: 79'
[gettext]: #gettext '```&#10;$ gettext $STRING&#10;```&#10;Translate `$STRING`&#10;Robbins, Arnold. _UNIX in a Nutshell_ 4th ed (2005): 99'
[grep]: #grep '```&#10;$ grep $PATTERN $FILES&#10;```&#10;Search `$FILES` for lines containing a match to regex `$PATTERN`&#10;Haeder, Adam. _LPI Linux Certification in a Nutshell_. 2010.: 126'
[groff]: #groff '```&#10;$ groff&#10;```&#10;Format documents to screen or for laser printing; GNU version of `troff`'
[head]: #head '```&#10;$ head&#10;```&#10;Print the first few lines of one or more files&#10;Haeder, Adam. _LPI Linux Certification in a Nutshell_. 2010.: 79'
[join]: #join '```&#10;$ join $FILE $OTHER&#10;```&#10;Print a line for each pair of input lines, one each from `$FILE` and `$OTHER`, that have identical join fields.&#10;Haeder, Adam. _LPI Linux Certification in a Nutshell_. 2010.: 80'
[less]: #less '```&#10;$ less&#10;```&#10;Pager&#10;Robbins, Arnold. _UNIX in a Nutshell_ 4th ed (2005): 116'
[look]: #look '```&#10;$ look&#10;```&#10;Look through a sorted file and print all lines that begin with `$STRING`&#10;Robbins, Arnold. _UNIX in a Nutshell_ 4th ed (2005): 124'
[more]: #more '```&#10;$ more&#10;```&#10;Display text one page at a time; superceded by `less`.&#10;Rothwell, William. _CompTIA Linux+ Portable Command Guide_.: 116'
[nl]: #nl '```&#10;$ nl&#10;```&#10;Number the lines of files, which are concatenated in the output.&#10;Haeder, Adam. _LPI Linux Certification in a Nutshell_. 2010.: 81'
[od]: #od '```&#10;$ od&#10;```&#10;Dump files in octal and other formats&#10;Haeder, Adam. _LPI Linux Certification in a Nutshell_. 2010.: 82'
[paste]: #paste '```&#10;$ paste&#10;```&#10;Paste together corresponding lines of one or more files into vertical columns, similar to but simpler than `join`.&#10;Haeder, Adam. _LPI Linux Certification in a Nutshell_. 2010.: 83'
[pr]: #pr '```&#10;$ pr&#10;```&#10;Convert a text file into a paginated, columnar version, with headers and page fills&#10;Haeder, Adam. _LPI Linux Certification in a Nutshell_. 2010.: 84'
[sed]: #sed '```&#10;$ sed&#10;```&#10;"Stream editor", powerful filtering program found on nearly every Unix system.&#10;Haeder, Adam. _LPI Linux Certification in a Nutshell_. 2010.: 128'
[shuf]: #shuf '```&#10;$ shuf&#10;```&#10;Randomly permute input'
[sort]: #sort '```&#10;$ sort&#10;```&#10;Sort text data&#10;Rothwell, William. _CompTIA Linux+ Portable Command Guide_.: 124'
[split]: #split '```&#10;$ split $INFILE $OUTFILE&#10;```&#10;Split `$INFILE` into a specified number of line groups, named `$OUTFILE`aa, `$OUTFILE`ab, etc&#10;Haeder, Adam. _LPI Linux Certification in a Nutshell_. 2010.: 86'
[tac]: #tac '```&#10;$ tac&#10;```&#10;Print text files to STDOUT with lines in reverse order&#10;Haeder, Adam. _LPI Linux Certification in a Nutshell_. 2010.: 87'
[tail]: #tail '```&#10;$ tail&#10;```&#10;Display the bottom part of text data.&#10;Rothwell, William. _CompTIA Linux+ Portable Command Guide_.: 115'
[tee]: #tee '```&#10;$ tee&#10;```&#10;Send output to both STDOUT and to a file&#10;Rothwell, William. _CompTIA Linux+ Portable Command Guide_.: 122'
[tr]: #tr '```&#10;$ tr&#10;```&#10;Translate characters from one set to another&#10;Rothwell, William. _CompTIA Linux+ Portable Command Guide_.: 123'
[unexpand]: #unexpand '```&#10;$ unexpand&#10;```&#10;Convert spaces to tabs&#10;Haeder, Adam. _LPI Linux Certification in a Nutshell_. 2010.: 89'
[uniq]: #uniq '```&#10;$ uniq $INPUT $OUTPUT&#10;```&#10;Write $INPUT to $OUTPUT, eliminating adjacent duplicate lines&#10;Haeder, Adam. _LPI Linux Certification in a Nutshell_. 2010.: 89'
[wc]: #wc '```&#10;$ wc&#10;```&#10;Display number of lines, words, or characters of data.&#10;Rothwell, William. _CompTIA Linux+ Portable Command Guide_.: 128'

**[Text filters](#text)** 
[`cat`][cat]
[`cmp`][cmp]
[`comm`][comm]
[`csplit`][csplit]
[`cut`][cut]
[`diff`][diff]
[`diff3`][diff3]
[`ed`][ed]
[`egrep`][egrep]
[`ex`][ex]
[`expand`][expand]
[`fgrep`][fgrep]
[`fmt`][fmt]
[`gettext`][gettext]
[`grep`][grep]
[`groff`][groff]
[`head`][head]
[`join`][join]
[`less`][less]
[`look`][look]
[`more`][more]
[`nl`][nl]
[`od`][od]
[`paste`][paste]
[`pr`][pr]
[`sed`][sed]
[`shuf`][shuf]
[`sort`][sort]
[`split`][split]
[`tac`][tac]
[`tail`][tail]
[`tee`][tee]
[`tr`][tr]
[`unexpand`][unexpand]
[`uniq`][uniq]
[`wc`][wc] 

**[Virtualization](#virtualization)** 
[`virt-install`][virt-install]
[`virt-manager`][virt-manager]

<!-- X window system commands -->
[cvt]: #cvt '```&#10;$ cvt&#10;```&#10;&#10;Calculate VESA CVT mode lines'
[x]: #x '```&#10;$ x&#10;```&#10;Start the graphical interface from the command-line'
[xdpyinfo]: #xdpyinfo '```&#10;$ xdpyinfo&#10;```&#10;Show detailed information about display'
[xfs]: #xfs '```&#10;$ xfs&#10;```&#10;X fonts server; small daemon that sends fonts to clients on both local and remote systems.&#10;Haeder, Adam. _LPI Linux Certification in a Nutshell_. 2010.: 307'
[xhost]: #xhost '```&#10;$ xhost&#10;```&#10;Set access controls to X server'
[xlsclients]: #xlsclients '```&#10;$ xlsclients&#10;```&#10;Determine what applications are running on the legacy X11 server provided with Wayland.'
[xmodmap]: #xmodmap '```&#10;$ xmodmap&#10;```&#10;Utility for modifying keymaps and pointer button mappings in X'
[xorg]: #xorg '```&#10;$ xorg&#10;```&#10;Full featured X server that was originally designed for UNIX and UNIX-like operating systems running on Intel x86 hardware'
[xrandr]: #xrandr '```&#10;$ xrandr&#10;```&#10;Set size, orientation, and reflection of video output'
[xset]: #xset '```&#10;$ xset&#10;```&#10;Set various user preference options of the display&#10;Haeder, Adam. _LPI Linux Certification in a Nutshell_. 2010.: 307'
[xwininfo]: #xwininfo '```&#10;$ xwininfo&#10;```&#10;Utility that provides information about a clicked window, including dimensions, position, etc'

**[X](#x-windows-system)** 
[`cvt`][cvt]
[`x`][x]
[`xdpyinfo`][xdpyinfo]
[`xfs`][xfs]
[`xhost`][xhost]
[`xlsclients`][xlsclients]
[`xmodmap`][xmodmap]
[`xorg`][xorg]
[`xrandr`][xrandr]
[`xset`][xset]
[`xwininfo`][xwininfo] 


# Linux distributions and desktop environments
[Alpine Linux]: #alpine-linux "Security-oriented, lightweight Linux distribution used in containers and hardware."
[Clear Linux]: #clear-linux "Rolling release distro from Intel with a custom package management system based on **bundles**, collections of packages that contain everything an application requires, including dependencies. Clear's update process also has the ability to do **delta downloads**, preserving bandwidth. It does not provide access with unusual licenses, like ZFS, Chrome, or FFmpeg."
[Fedora]: #fedora 'Fedora&#10;Used as the initial testbed for software and configuratiosn that later find their way to RHEL&#10;Nemeth, Evi. _Unix and Linux System Administration Handbook, 5th ed._: 11'
[CentOS]: https://centos.org 'CentOS&#10;Virtually identical to RHEL, but free of charge.&#10;The CentOS Project is owned by Red Hat and employs its lead developers.&#10;Nemeth, Evi. _Unix and Linux System Administration Handbook, 5th ed._: 11'
[Fedora CoreOS]: #fedora-coreos "Fedora edition built for running containerized workloads securely and at scale. CoreOS systems are meant to be immutable, meaning they are only configured through the provisioning process and not modified in-place."
[WSL]: #windows-subsystem-for-linux "Linux virtual machine shipped with Windows with the ability to install several different distros."
[Yocto]: # 'Yocto&#10;Open-source project that facilitates the construction of custom Linux images for use in embedded and edge devices'

- [Alpine ][Alpine Linux] 
- [Arch ](#arch-linux) 
- [CentOS][CentOS] 
- [Clear ][Clear Linux] 
- [CoreOS][Fedora CoreOS] 
- [Fedora][Fedora] 
- [GNOME](#gnome)
- [Kali ](#kali-linux) 
- [KDE](#kde)
- [WSL][WSL]
- [Yocto][Yocto]

Fully-featured **desktop environments** are distinct from **window managers**, which are more focused in scope

### Alpine Linux
Security-oriented, lightweight Linux distribution used in containers and hardware.
### Arch Linux
### BSD
**Berkeley Software Distribution (BSD)** began in the 70s and was based on AT&T original code. First source distributions required user to purchase a source license from AT&T, since much of the BSD source was derivative of UNIX.

Berkeley finally released a "wholly-BSD" product as **Network Release 1** in 1989, which satisfied vendor demand for the TCP/IP networking code for PC.

Work immediately began to reconstruct the remaining functionality of UNIX, which was completed in Network Release 2, released in 1991, which was based entirely on Berkeley code. Eventually this resulted in the 386BSD distribution, which then spawned five interrelated BSD distros: BSDI (now Wind River), NetBSD, FreeBSD, OpenBSD, and Darwin/Mac OS X

**Unix System Laboratories (USL)** sued BSDI after BSDI attempted to market its product as a real UNIX, and other BSD distributions were affected by disputed code. Ultimately 3 out of the 18,000 files that made up the Network Release 2 distribution were removed, which became known as 4.4BSD-lite, released in 1994. This legal dispute was partly to blame for Linux's rapid ascent in popularity.\
Source: [Article](https://web.archive.org/web/20060315152051/http://www.applelust.com/alust/terminal/archives/terminal041202.shtml)
### Clear Linux
Rolling release distro from Intel with a custom package management system based on **bundles**, collections of packages that contain everything an application requires, including dependencies. Clear's update process also has the ability to do **delta downloads**, preserving bandwidth. It does not provide access with unusual licenses, like ZFS, Chrome, or FFmpeg. [^][LXF 258]
### Fedora
### Fedora CoreOS
**CoreOS** is a Fedora edition built specifically for running containerized workloads securely and at scale. Because containers can be deployed across many nodes for redundancy, the system can be updated and rebooted automatically without affecting uptime. [^](https://fedoramagazine.org/introducing-fedora-coreos/ "Fedora Magazine: \"Introducing Fedora CoreOS\"")

CoreOS systems are meant to be **immutable infrastructure**, meaning they are only configured through the provisioning process and not modified in-place. All systems start with a generic OS image, but on first boot it uses a system called **Ignition** to read an **Ignition config** (which is converted from a **Fedora CoreOS Config** file) from the cloud or a remote URL, by which it provisions itself, creating disk partitions, file systems, users, etc.\
CoreOS automatically installs upgrades automatically without user intervention, although they can be stopped if a problem is found.
### Kali Linux
[Aircrack-ng]: #kali-linux 'Aircrack-ng&#10;Monitor and compromise WiFi networks'
[BeEF]: #kali-linux 'BeEF&#10;Assess security of a web browser'
[Apktool]: #kali-linux 'Apktool&#10;Reverse engineer Android apps'
[AFB]: #kali-linux 'Autopsy Forensic Browser (AFB)&#10;Digital forensics'
[Burp Suite Scanner]: #kali-linux 'Burp Suite Scanner&#10;GUI-based web application security scanner'
[Hydra]: #kali-linux 'Hydra&#10;Crack login/password pairs'
[John the Ripper]: #kali-linux 'John the Ripper&#10;Crack passwords'
[King Phisher]: #kali-linux 'King Phisher&#10;Simulate phishing attacks'
[Lynis]: #kali-linux 'Lynis&#10;Security auditing, compliance testing'
[Maltego]: #kali-linux 'Maltego&#10;Data mining'
[Metasploit Framework]: #kali-linux 'Metasploit Framework&#10;Penetration testing framework'
[Nessus]: #kali-linux 'Nessus&#10;Paid tool to find vulnerabilities'
[Nikto]: #kali-linux 'Nikto&#10;Web server scanner'
[SET]: #kali-linux 'Social Engineering Toolkit (SET)'
[Skipfish]: #kali-linux 'Skipfish&#10;Web application scanner'
[Snort]: #kali-linux 'Snort&#10;Traffic analysis and packet logging'
[Sqlmap]: #kali-linux 'Sqlmap&#10;Exploit SQL injection flaws'
[Wireshark]: #kali-linux 'Wireshark&#10;Network analyzer'
[WPScan]: #kali-linux 'WPScan&#10;WordPress security auditing tool'
[Yersinia]: #kali-linux 'Yersinia&#10;Perform Layer 2 attacks'

###### Pentesting tools 
<sup>[itsfoss.com](https://itsfoss.com/best-kali-linux-tools/ "ItsFOSS: \"21 Best Kali Linux Tools for Hacking and Penetration Testing\"")</sup>

[Aircrack-ng][Aircrack-ng] 
[Apktool][Apktool] 
[Autopsy Forensic Browser][AFB]
[BeEF][BeEF] 
[Burp Suite Scanner][Burp Suite Scanner]
[Hydra][Hydra]
[John the Ripper][John the Ripper]
[King Phisher][King Phisher]
[Lynis][Lynis]
[Maltego][Maltego] 
[Metasploit][Metasploit Framework]
[Nikto][Nikto]
[SET][SET] 
[Skipfish][Skipfish] 
[Snort][Snort] 
[sqlmap][Sqlmap]
[Wireshark][Wireshark] [WPScan][WPScan]
[Yersinia][Yersinia]
### Windows Subsystem for Linux
[DrvFs]: #windows-subsystem-for-linux 'DrvFs&#10;Filesystem plugin to WSL that was designed to support interoperability between WSL and the Windows filesystem. DrvFs enables WSL to mount drives with supported file systems under /mnt, such as /mnt/c, /mnt/d, etc. &#10;"Chmod/Chown WSL Improvements". _Windows Command Line_. Microsoft: 01/12/2018.'
[lxss.sys]: #windows-subsystem-for-linux 'LXSS Manager service (lxss.sys)&#10;One of the WSL "pico drivers" that translates Linux syscalls to equivalent Windows NT calls. Where there is no reasonable mapping, lxss.sys must service the request directly.&#10;"WSL System calls". _Windows Subsystem for Linux_. Microsoft.'
[pico driver]: #windows-subsystem-for-linux 'pico driver&#10;Reference to lsxx.sys and lxcore.sys in WSL, responsible for handling Linux syscall requests in coordination with the NT kernel.&#10;"WSL System calls". _Windows Subsystem for Linux_. Microsoft.'
[VFS]: #windows-subsystem-for-linux 'Virtual File System (VFS)&#10;Abstraction of file system operations used by WSL, which provides an interface for user mode programs to interact with the file system and an interface that file systems have to implement.&#10;"WSL File System Support". _Windows Subsystem for Linux_. Microsoft: 06/15/2016.'
[VolFs]: #windows-subsystem-for-linux 'VolFs&#10;The primary file system used by WSL, which is used to store the Linux system files and the contents of the home directory.&#10;VolFs supports most features the Linux VFS provides, including Linux permissions, symbolic links, FIFOs, sockets, and device files.&#10;"WSL File System Support". _Windows Subsystem for Linux_. Microsoft: 06/15/2016.'


**Windows Subsystem for Linux (WSL)** is shipped with Windows and tied to the Windows release cycle. Windows ships from a single massive codebase, of which WSL is part. WSL was written mostly in C and and has 3 million monthly active users. <sup>[ADP 57](https://github.com/jasper-zanjani/notes/tree/master/sources/README.md#adp-57 "Azure DevOps Podcast 57: \"Craig Loewen on the Windows Subsystem for Linux story\"")</sup>

[DrvFs][DrvFs] 
[LXSS][lxss.sys]
[pico drivers][pico driver]
[VFS][VFS] 
[VolFs][VolFs]

WSL implements **user services** to connect to WSL distros and to run Windows-native applications like CMD.exe. WSL implements a **9P Protocol** file server to provide seamless integration of the virtualized Linux filesystem and that of the Windows host.

In version 1, WSL worked under a **translation architecture** where system calls were translated to NT kernel calls. This meant that applications that used system calls that were newer or more difficult to implement, like GUI applications or Docker, did not run on v1. But WSL2 shifted to a **lighweight virtualization** model using the Linux kernel. Now Docker runs on WSL2 and GUI applications can run by using an X server.

WSL v1 is available on Azure VMs if **nested virtualization** is enabled. WSL2 support is forthcoming.
### Mac OS X
Configure `iterm2` as a **Guake**-style dropdown terminal 
<sup>
[ref](https://superuser.com/questions/951393/pin-os-x-terminal-window-always-on-top-in-macos-yosemite) 
[ref](https://www.sharmaprakash.com.np/guake-like-dropdown-terminal-in-mac/#assign-hotkey) 
</sup>
#### `open`
Open path in Finder
```
open path
```
Open an application from Terminal
```
open -a /Applications/application.app
```
#### `screencapture`
Take a screenshot on Mac OS X [48](sources.md)

Option  | Effect
:---    | :---
`-c`    | send to clipboard
`-T $SECONDS` | take screenshot after `$SECONDS`
`-t $FORMAT`  | specify file `$FORMAT` (png by default)
`-x`    | take screenshot without shutter sound
### KDE
Appearance
- **Colors** affects the appearance of text
- **Workspace Theme** > **Look and Feel** allows selection of Look and Feel Themes that affect window appearance
- **Workspace Theme** > **Plasma theme** appears to affect the appearance of widgets only
#### Comparison with other OSes
File dialogs have highly configurable views, with icon sizes scalable from 16 to 128 px and filenames available to the side or below the icon.
- A view similar to the Icons view in Mac OS X or the List view in Windows can be reproduced by setting View to the icon size to the minimum 16px and placing the filename to the side (`Icon Position` > `Next to file name`)
#### Wallpapers
Wallpaper types "Haenau" and "Hunyango" are QML (Qt Modeling Language) animated wallpapers that were introduced in Plasma 5.1 (2014)
#### Widgets
"Plasmoids" are dragged and dropped onto the Desktop, where they function as buttons. A long click will allow them to be moved, rotated, or resized. Each plasmoid can be configured with a keyboard shortcut. They occupy all virtual desktops.

One plasmoid in particular is the "Grouping Plasmoid", which allows other plasmoids to be placed within it, where they occupy separate tabs. 
#### Login manager
Workspace > Startup and Shutdown > Login Screen (SDDM)
- The advanced tab allows you to select Mouse cursor theme and auto login of user and session type. These appear to affect specifically settings in /etc/sddm.conf (`Session=gnome-xorg` under `[Autologin]`)

Default shortcuts are found in **Workspace > Shortcuts > Global Shortcuts**
- "Run Command" refers to `krunner`, a single-line application launcher similar to the Run command on Windows.
- **Alt-t** : open a terminal window

### System logging
Traditionally, `syslogd` was the daemon in charge of this, but recently alternatives such as `rsyslog` and `syslog-ng` have emerged. 

\#    | Severity      | Description
:---  | :---          | :---  
0     | Emergencies   | Most severe error conditions that render the system unusable
1     | Alerts        | Conditions requiring immediate attention
2     | Critical      | Condition that should be addressed to prevent an interruption of service
3     | Error         | Error conditions that do not render the system unusable
4     | Warning       | Specific operations failed to complete successfully
5     | Notifications | Non-error notifications that alert an administrator about state changes within a system
6     | Informational | Detailed dinformation about the normal operation of a system
7     | Debugging     | Highly detailed information used for troubleshooting

### Filesystems
**Index node (inode)** is a data structure that stores all the information about a file except its name and data
Most modern Linux distributions use the `ext4` filesystem, which descends from `ext3` and `ext2`, and ultimately `ext`. Other filesystems in use include `btrfs`, `xfs`, and `zfs`
Source: [<sup>ref</sup>](https://opensource.com/article/18/4/ext4-filesystem "opensource.com: \"Understanding Linux filesystems: ext4 and beyond\"")

#### ext
**Extended File System** was first implemented in 1992 by Remy Card to address limitations in the MINIX filesystem, which was used to develop the first Linux kernel. It could address up to 2GB of storage and handle 255-character filenames and had only one timestap per file.

**ext2** was developed by Remy Card only a year after `ext`'s release as a commercial-grade filesystem, influenced by BSD's Berkeley Fast File System. It was prone to corruption if the system crashed or lost power while data was being written and performance losses due to fragmentation. Nevertheless, it was quickly and widely adopted, and still used as a format for USB drives.

**ext3** was adopted by mainline Linux in 2001 and uses **journaling**, whereby disk writes are stored as transactions in a special allocation, which allows a rebooted system to roll back incomplete transactions. 3 journaling modes: [journal](#ext "lowest risk journaling mode in ext3, writes both data and metadata to journal before commiting it to filesystem"), [ordered](#ext "default journaling mode in ext3, writes metadata to journal but commits data directly to the filesystem"), and [writeback](#ext "least safe journaling mode in ext3, metadata is journaled but data is not")

**ext4** was added to mainline Linux in 2008, developed by Theodore Ts'o, and improves upon `ext3` but is still reliant on old technology.

#### ZFS
- true next-generation filesystem with a problematic license
- **ZFS on Linux (ZOL)** is considered the ugly stepchild of the ZFS community despite the fact that the Linux implementation has the most features and the most community support
- ZFS is too tightly bound to the operation of the kernel to operate in true userspace, and that is why each implementation is different for operating systems 
  - ZFS is too tightly bound to the operation of the kernel to operate in true userspace, and that is why each implementation is different for operating systems 
- ZFS is too tightly bound to the operation of the kernel to operate in true userspace, and that is why each implementation is different for operating systems 
- LU: 284

**B-Tree Filesystem "butter fs"** was adopted by SUSE Enterprise Linux, but support was dropped by Red Hat in 2017.


### Security
#### Library injections
Similar to DLL files on Windows systems, .so ("shared object") library files on Linux allow code to be shared by various processes. They are vulnerable to injection attacks. One file in particular, **linux-vdso.so.1**, finds and locates other shared libraries and is mapped by the kernel into the address space of every process. This library-loading mechanism can be exploited through the use of the environment variable **`LD_PRELOAD`**, which is considered the most convenient way to load a shared library in a process at startup. If defined, this variable is read by the system and the library is loaded immediately after linux-vdso.so.1 into every process that is run. [^](https://www.networkworld.com/article/3404621/tracking-down-library-injections-on-linux.html "networkworld.com: \"Tracking down library injections on Linux\"")

This attack can be detected using the **[osquery](https://osquery.io/)** tool. This tool represents the system as a relational database which can then be queried, in particular against the **process_envs** table.

# Linux commands
## Applications
`git`
[`imagemagick`](#imagemagick) 
[`mongod`](#mongod) 
**GNOME** 
`gsettings`
[`gconf-editor`][gconf-editor] 
**KDE** 
[`kquitapp`][kquitapp] 
[`krunner`][krunner] 
[`kstart`][kstart] 
**SMB**
[`smbclient`][smbclient] 
[`smbpasswd`][smbpasswd] 
[`smbstatus`][smbstatus] 

#### git
[git-add]: #git-add '```&#10;$ git add &#10;```&#10;Add file contents to the index'
[git-branch]: #git-branch '```&#10;$ git branch &#10;```&#10;List, create, or delete branches'
[git-checkout]: #git-checkout '```&#10;$ git checkout &#10;```&#10;Switch branches or restore working tree files'
[git-cherry-pick]: #git-cherry-pick '```&#10;$ git cherry-pick &#10;```&#10;Apply the changes introduced by some existing commits'
[git-clean]: #git-clean '```&#10;$ git clean &#10;```&#10;Remove untracked files from the working tree'
[git-config]: #git-config '```&#10;$ git config &#10;```&#10;Get and set repository or global options'
[git-log]: #git-log '```&#10;$ git log &#10;```&#10;Show commit logs'
[git-ls-files]: #git-ls-files '```&#10;$ git ls-files &#10;```&#10;Show information about files in the index and the working tree'
[git-mv]: #git-mv '```&#10;$ git mv &#10;```&#10;Move or rename a file, a directory, or a symlink'
[git-push]: #git-push '```&#10;$ git push &#10;```&#10;Update remote refs along with associated objects'
[git-rebase]: #git-rebase '```&#10;$ git rebase &#10;```&#10;Reapply commits on top of another base tip'
[git-remote]: #git-remote '```&#10;$ git remote &#10;```&#10;Manage set of tracked repositories'
[git-reset]: #git-reset '```&#10;$ git reset &#10;```&#10;Reset current HEAD to the specified state'
[git-revert]: #git-revert '```&#10;$ git revert &#10;```&#10;Revert some existing commits'
[git-rm]: #git-rm '```&#10;$ git rm &#10;```&#10;Remove files from the working tree and from the index'
[git-stash]: #git-stash '```&#10;$ git stash &#10;```&#10;Stash changes away in a dirty working directory'

[doc:git-add]: https://git-scm.com/docs/git-add "git add documentation"
[doc:git-branch]: https://git-scm.com/docs/git-branch "git branch documentation"
[doc:git-checkout]: https://git-scm.com/docs/git-checkout "git checkout documentation"
[doc:git-cherry-pick]: https://git-scm.com/docs/git-cherry-pick "git cherry-pick documentation"
[doc:git-clean]: https://git-scm.com/docs/git-clean "git clean documentation"
[doc:git-config]: https://git-scm.com/docs/git-config "git config documentation"
[doc:git-log]: https://git-scm.com/docs/git-log "git log documentation"
[doc:git-ls-files]: https://git-scm.com/docs/git-ls-files "git ls-files documentation"
[doc:git-mv]: https://git-scm.com/docs/git-mv "git mv documentation"
[doc:git-push]: https://git-scm.com/docs/git-push "git push documentation"
[doc:git-rebase]: https://git-scm.com/docs/git-rebase "git rebase documentation"
[doc:git-remote]: https://git-scm.com/docs/git-remote "git remote documentation"
[doc:git-reset]: https://git-scm.com/docs/git-reset "git reset documentation"
[doc:git-revert]: https://git-scm.com/docs/git-revert "git revert documentation"
[doc:git-rm]: https://git-scm.com/docs/git-rm "git rm documentation"
[doc:git-stash]: https://git-scm.com/docs/git-stash "git stash documentation"

[`add`][git-add]<sup>[?][doc:git-add]</sup>
[`branch`][git-branch]<sup>[?][doc:git-branch]</sup>
[`checkout`][git-checkout]<sup>[?][doc:git-checkout]</sup>
[`cherry-pick`][git-cherry-pick]<sup>[?][doc:git-cherry-pick]</sup>
[`clean`][git-clean]<sup>[?][doc:git-clean]</sup>
[`config`][git-config]<sup>[?][doc:git-config]</sup>
[`log`][git-log]<sup>[?][doc:git-log]</sup>
[`ls-files`][git-ls-files]<sup>[?][doc:git-ls-files]</sup>
[`mv`][git-mv]<sup>[?][doc:git-mv]</sup>
[`push`][git-push]<sup>[?][doc:git-push]</sup>
[`rebase`][git-rebase]<sup>[?][doc:git-rebase]</sup>
[`remote`][git-remote]<sup>[?][doc:git-remote]</sup>
[`reset`][git-reset]<sup>[?][doc:git-reset]</sup>
[`revert`][git-revert]<sup>[?][doc:git-revert]</sup>
[`rm`][git-rm]<sup>[?][doc:git-rm]</sup>
[`stash`][git-stash]<sup>[?][doc:git-stash]</sup>

##### git clean
[git clean -&#102;]: #git-clean '```&#10;$ git clean -f&#10;```&#10;Remove untracked files without confirmation'
[git clean -&#100;]: #git-clean '```&#10;$ git clean -d $PATH&#10;```&#10;Remove untracked files from the specified directory'
[git clean -&#105;]: #git-clean '```&#10;$ git clean -i&#10;```&#10;Remove untracked files interactively'
[git clean -&#110;]: #git-clean '```&#10;$ git clean -n&#10;```&#10;Perform a dry run'
[git clean -&#120;]: #git-clean '```&#10;$ git clean -x&#10;```&#10;Remove ignored files'
[git clean -&#88;]: #git-clean '```&#10;$ git clean -X&#10;```&#10;Remove only ignored files'

<code>&nbsp;</code>   <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> [`d`][git clean -&#100;] <code>&nbsp;</code> [`f`][git clean -&#102;] <code>&nbsp;</code> <code>&nbsp;</code> [`i`][git clean -&#105;] <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> [`n`][git clean -&#110;] <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> [`x`][git clean -&#120;] <code>&nbsp;</code> <code>&nbsp;</code>  <br><code>&nbsp;</code>&nbsp;<code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> [`X`][git clean -&#88;] <code>&nbsp;</code> <code>&nbsp;</code> 

##### git add
Add file, located in `$HOME` to the git repo at `$PATH`
```sh
git --git-dir=$PATH.git --work-tree=$HOME add file
```
Update index to include all files in the working tree, including removals
```sh
git add -A
git add --no-ignore-removal
```
Stage all modifications in work-tree, including deletions
```sh
git add -u
```
##### git branch
See a list of branches. 
A "*" indicates that branch is checked out.
```sh
git branch
```
Display the last commit for each branch
```sh
git branch -v
```
Display branches that have not been merged
```sh
git branch --no-merged
```
##### git checkout
Discard unstaged uncommitted changes to file
```sh
git checkout -- file
```
Switch to branch
```sh
git checkout branch
```
##### git cherry-pick
Apply a single, specific commit from another branch
```sh
git cherry-pick commit
```
##### git config
Provides a frontend to the INI formatted config files typically found within `.git/config` (or `~/.gitconfig` when using `--global`)

Set up alias "br" for `branch`
```sh
git config --global alias.br branch
```
Equivalent to:
```ini
[alias]
br = branch
```
Store authentication details in a cache
```sh
git config --global credential.helper cache
```
Equivalent to 
```ini
[credential]
helper = cache
```
##### git log
Show commits between January 1 and January 5, 2016
```sh
git log --after="2016-01-01" --before="2016-01-05"
```
See commits that are on {branch} but not on {master}
```sh
git log master..branch
```
##### git ls-files
Show tracked files
```sh
git ls-files
```
Show tracked files, each line is terminated by a null byte
```sh
git ls-files -z
```
Show tracked files that have been deleted
```sh
git ls-files --deleted
```
##### git mv
Move or rename a tracked file
```sh
git mv file
```
##### git push
Transfer data from local branch {master} to remote {origin}
```sh
git push -u origin master
```
##### git rebase
Combine branches by replaying the changes made on one branch to another
```sh
git rebase
```
##### git remote
Manage repositories whose branches you track
```sh
git remote
```
Add remote repo
```sh
git remote add $REPO $URL
```
Display URL of remote repo
```sh
git remote get-url $REPO
```
Set url for existing repo
```sh
git remote set-url $URL $REPO
```
##### git reset
Undo unstaged changes since last commit
```sh
git reset --hard
```
Reset master to state before last commit
```sh
git reset --hard HEAD~
```
##### git revert
Remove (committed) changes in {commit}
```sh
git revert commit
```
##### git rm
Remove tracked file from repo
```sh
git rm file
```
##### git stash
Stash changes to work-tree
```bash
git stash
```
View stashes in stash stack
```bash
git stash list
```
Apply changes in most recent stash
```bash
git stash apply
```
Apply changes in stash `$STASH`
```bash
git stash apply stash@$STASH
```
##### Rebasing
Rebase changes committed to `branch` onto <master>
```sh
git checkout $BRANCH
git rebase $MASTER
```
This will rewind $BRANCH to the commit shared by the two branches, then applying all changes made subsequently to $MASTER. 
```sh
git checkout <master>
git merge <branch>
```
Now the history will appear as though all changes were made in series, when they were actually made in parallel on separate branches.
Move the last commit to a new branch
```sh
git branch test         # create a new branch with current HEAD
git reset --hard HEAD~  # reset master to before last commit 
git checkout test       # continue on new branch
```
Line endings
Git will automatically append CRLF endings on Windows. This setting can be displayed with the following command:
```bash
git config core.autocrlf
```
In order to disable this, adjust the setting
```bash
git config core.autocrlf false
```
##### Squashing
Sometimes many commits are made to resolve a single issue. These should be "squashed". To squash the last 4 commits:
```bash
git rebase -i HEAD~4
```
This will open a text editor where you will have to select what to do with each of the 4 commits. Most recent commits are at the bottom, and at least the top (oldest) commit has to remain "pick" in order to squash the others.
The repo will have to be force-pushed once these changes have been made. 
```bash
git push --force
```
To add changes to the most recent commit, stage changes as normal (including removals), but when committing use the `--amend` option. This will present an editor, allowing you to edit the commit message, if necessary. [[6](#sources)]
```git
git add README.md
git commit --amend 
```
To add changes to a commit that is not the most recent, a rebase is necessary. First [stash](#stash) the changes to be added, then initiate a rebase and mark the commit to be edited with `edit` or `e`. Leave the other commits alone, save, and drop back to the stash. Pop the stash (`git stash pop`), which will apply the changes stored in the most recent stash. Now you can stage the changes and commit:
```sh
git commit --amend --no-edit
```
Finally, continue the rebase, rewriting the rest of the commits against the new one.
```sh
git rebase --continue
```
To split up `$COMMIT`
```sh
git rebase -i "$COMMIT"^ # Start a rebase at the commit you want to split
```
Mark the commit to be split with `edit`. Now reset state to the previous commit
```sh
git reset HEAD^
```
The files are presented unstaged, and can be added to new commits as needed. Finally, finish the rebase
```sh
git rebase --continue
```
#### gsettings
Change function of Caps Lock key [<sup>ref</sup>][https://superuser.com/questions/1196241/how-to-remap-caps-lock-on-wayland]
```sh
gsettings set org.gnome.desktop.input-sources xkb-options "['caps:ctrl_modifier']"
```
Change mouse cursor size to `$SIZE`, which can be one of the values 24 (default), 32, 48, 64, or 96. [<sup>ref</sup>][https://vitux.com/how-to-change-cursor-size-on-ubuntu-desktop/]
```sh
gsettings set org.gnome.desktop.interface $SIZE
```
#### imagemagick
[imagemagick identify]: #imagemagick-identify                   '```&#10;$ imagemagick identify&#10;```&#10;Describe the format and characteristics of one or more image files'
[imagemagick mogrify]: #imagemagick-mogrify                    '```&#10;$ imagemagick mogrify&#10;```&#10;Resize, blur, crop, despeckle, dither, draw on, flip, join, resample, etc'

[`identify`][imagemagick identify] 
[`mogrify`][imagemagick mogrify] 

##### imagemagick identify
Option                            | Effect
:---                              | :---
`-format {string}`                | display formatted image characteristics; {string} is formatted string using `%[key]` escape sequences<br/> **%w** current width in pixels <br/> **%h** current height in pixels

##### imagemagick mogrify
Option               | Effect
:---                 | :---
`-write $FILENAME`   | save to `filename`
`-resize $Xx$Y`      | resize image to `$X` pixels by `$Y` pixels
`-crop $SIZE$OFFSET` | 
`-gravity $TYPE`     | set current gravity suggestion for various other options <br>possible values `NorthWest`, `North`, `NorthEast`, `West`, `Center`, `East`, `SouthWest`, `South`, or `SouthEast`
  
Argument patterns 
---           | ---
{geometry}    | **{size}{offset}**
{size}        | **{scale}%** height and weight are both scaled by a specified percentage<br/> **{width}x{height}** maximum values of height and width<br/> **{width}x{height}^** minimum values of height and width<br/>
{offset}      | also affected by `-gravity` setting<br/> **`+0+0`** top-left corner
gravity       | 

Resize images
```sh
magick mogrify -resize 1920x1200 -write mars-bg.jpg pia22511.jpg
magick identify -format "%w x %h" pia22511.jpg
```
Save the output of a command as an image (`convert` is from the ImageMagick software suite) [<sup>ref</sup>][CLKF]
```sh
cmd | convert label:@- image.png
``` 
View image metadata (`identify` is from the ImageMagick software suite) <sup>[ostechnix.com](https://www.ostechnix.com/how-to-view-image-metadata-on-linux/ "How to view image metadata")</sup>
```sh
identify image.png # => dimensions, color depth, color profile
identify -verbose image.png
```
#### krunner
Single-line application launcher similar to the Run command on Windows.
#### kquitapp
Allows you to quit a dbus enabled application. Two options:

Specify service to be stopped
```sh
kquitapp --service
```
Specify path to dbus interface 
```sh
kquitapp --path
```
#### kstart
Restarting KDE Plasma 4 <sup>[ref](https://www.lifewire.com/kubuntu-p2-2202573)</sup>
```sh
killall plasma-desktop
kstart plasma-desktop
```
Restarting KDE Plasma 5 <sup>[ref](https://www.lifewire.com/kubuntu-p2-2202573)</sup>
```sh
killall plasmashell
kstart plasmashell
```
```sh
kquitapp5 plasmashell
kstart plasmashell
```
#### lowriter
`lowriter` is a command-line utility installed with LibreOffice Writer. <sup>[vitux.com](https://vitux.com/how-to-convert-documents-to-pdf-format-on-the-ubuntu-command-line/ "vitux.com: \"How to convert documents to PDF format on the Ubuntu Command Line\"")</sup>

Convert a single file to PDF
```sh
lowriter --convert-to pdf filename.doc
```
Convert a batch of files using globbing
```sh
lowriter --convert-to pdf *.docx
```
#### mongod
Run MongoDB service in the background on port 80
```sh
mongod --dbpath $HOME/db --port 80 --fork --logpath /var/tmp/mongodb
```
#### tig
Provides a curses-based browser that allows you to navigate the commits in the current branch. It is essentially a wrapper around `git log`, and therefore accepts the same arguments that can be passed to it.[[34](sources.md)]

Config file   | Description
:---          | :---
$HOME/.tigrc  | 

Browse the commit history for a single {file}
```sh
tig file
```
Browse the commit history for a single {file}, filtering to a specific date range
```sh
tig --after="2017-01-01" --before="2018-05-16" -- README.md
```
Find who made a change toa  file and why
```sh
tig blame file
```
Browse stash
```sh
tig stash
```
Browse refs
```sh
tig refs
```
Navigate the output of `git grep`
```sh
tig grep -i foo lib/Bar
```
Pipe a list of commit IDs to tig
```sh
git rev-list --author=olaf HEAD | tig show --stdin
```


## Archive
[ar]:                          #ar                             '```&#10;$ ar&#10;```&#10;Maintain a group of files that are combined into a file archive. Used most commonly to create and update library files as used by `ld`.&#10;Robbins, Arnold. _UNIX in a Nutshell_ 4th ed (2005): 16'
[bzcat]:                       #bzcat                          '```&#10;$ bzcat&#10;```&#10;Page through .bz2 files'
[bzip2]:                       #bzip2                          '```&#10;$ bzip2&#10;```&#10;Compress or decompress archives using the Burrows-Wheeler block-sorting text-compression algorithm.&#10;Rothwell, William. _CompTIA Linux+ Portable Command Guide_.: 271'
[bzless]:                      #bzless                         '```&#10;$ bzless&#10;```&#10;Page through .bz2 files'
[bzmore]:                      #bzmore                         '```&#10;$ bzmore&#10;```&#10;Page through .bz2 files'
[compress]:                    #compress                       '```&#10;$ compress&#10;```&#10;Compress and expand data&#10;Compress reduces the size of the named files using adaptive Lempel-Ziv coding. Whenever possible, each file is replaced by one with the extension .Z, while keeping the same ownership modes, access and modification times. If no files are specified, the standard input is compressed to the standard output. Compress will only attempt to compress regular files. In particular, it will ignore symbolic links. If a file has multiple hard links, compress will refuse to compress it unless the -f flag is given.'
[cpio]:                        #cpio                           '```&#10;$ cpio&#10;```&#10;Create and extract archives, or copy files from one place to another - without compression. Each of the three control options (`-i`, `-o`, or `-p`) accepts different options.&#10;Haeder, Adam. _LPI Linux Certification in a Nutshell_. 2010.: 93'
[dar]:                         #dar                            '```&#10;$ dar&#10;```&#10;Backup tool that can make differential and incremental backups&#10;"`dar` manpage". _Ubuntu Manpage Repository_.'
[gunzip]:                      #gunzip                         '```&#10;$ gunzip&#10;```&#10;Identical to `gzip -d`, typically implemented as a link to `gzip`'
[gzcat]:                       #gzcat                          '```&#10;$ gzcat&#10;```&#10;Identical to `gzip -c`, typically implemented as a link to `gzip`'
[gzip]:                        #gzip                           '```&#10;$ gzip&#10;```&#10;"GNU Zip". Compress or decompress archives using the Lempel-Ziv (LZ77) compression algorithm.'
[tar]:                         #tar                            '```&#10;$ tar&#10;```&#10;Merge multiple files into a single file&#10;Rothwell, William. _CompTIA Linux+ Portable Command Guide_.: 268'
[uncompress]:                  #uncompress                     '```&#10;$ uncompress&#10;```&#10;Aliased to `gunzip` on Ubuntu&#10;Eckert, Jason. _Linux+ Guide to Linux Certification_. Course Technology, 2012: 480'
[unxz]:                        #unxz                           '```&#10;$ unxz&#10;```&#10;Decompress an archive created with `xz`&#10;Rothwell, William. _CompTIA Linux+ Portable Command Guide_.: 270'
[unzip]:                       #unzip                          '```&#10;$ unzip&#10;```&#10;Decompress a .zip archive'
[xz]:                          #xz                             '```&#10;$ xz&#10;```&#10;Compress or decompress archives using the LZMA and LZMA2 compression methods.&#10;Rothwell, William. _CompTIA Linux+ Portable Command Guide_.: 270'
[zcat]:                        #zcat                           '```&#10;$ zcat&#10;```&#10;Uncompress one or more compressed files to STDOUT. On Linux, this program is the version related to `gzip`, which can decompress .Z and .gz files&#10;Robbins, Arnold. _UNIX in a Nutshell_ 4th ed (2005): 238'
[zip]:                         #zip                            '```&#10;$ zip&#10;```&#10;Merge multiple files into a single, compressed file&#10;Rothwell, William. _CompTIA Linux+ Portable Command Guide_.: 271'
[zipcloak]:                    #zipcloak                       '```&#10;$ zipcloak&#10;```&#10;Password protect and encrypt zip files, equivalent to `zip --encrypt` or `zip -e`.&#10;_Linux Pro Magazine_. Issue 231. Feb 2020.: 37'
[zipcmp]:                      #zipcmp                         '```&#10;$ zipcmp $FILE $OTHER&#10;```&#10;Compare files in zip archives (no man page or help option available).&#10;_Linux Pro Magazine_. Issue 231. Feb 2020.: 37'
[zipdetails]:                  #zipdetails                     '```&#10;$ zipdetails&#10;```&#10;'
[zipgrep]:                     #zipgrep                        '```&#10;$ zipgrep&#10;```&#10;Search for patterns within a zip archive.&#10;_Linux Pro Magazine_. Issue 231. Feb 2020.: 37'
[zipinfo]:                     #zipinfo                        '```&#10;$ zipinfo&#10;```&#10;Display the attributes of all the files in a zip archive, including permissions, name, date created, uncompressed and compressed file sizes, and percentage compression.&#10;_Linux Pro Magazine_. Issue 231. Feb 2020.: 38'
[zipnote]:                     #zipnote                        '```&#10;$ zipnote&#10;```&#10;Read and edit comments in archives; particularly useful for changing filenames in an archive that start with "@home" in the comment&#10;_Linux Pro Magazine_. Issue 231. Feb 2020.: 38'
[zipsplit]:                    #zipsplit                       '```&#10;$ zipsplit&#10;```&#10;Divide existing archives into smaller ones, creating an index file to help reassemble them.&#10;_Linux Pro Magazine_. Issue 231. Feb 2020.: 38'

[`ar`][ar] 
[`bzcat`][bzcat] 
[`bzip2`][bzip2] 
[`bzless`][bzless] 
[`bzmore`][bzmore] 
[`compress`][compress] 
[`cpio`][cpio] 
[`dar`][dar] 
[`gunzip`][gunzip] 
[`gzcat`][gzcat] 
[`gzip`][gzip] 
[`tar`][tar] 
[`uncompress`][uncompress] 
[`unxz`][unxz] 
[`unzip`][unzip] 
[`xz`][xz] 
[`zcat`][zcat] 
[`zip`][zip] 
[`zipcloak`][zipcloak] 
[`zipcmp`][zipcmp] 
[`zipdetails`][zipdetails] 
[`zipgrep`][zipgrep] 
[`zipinfo`][zipinfo] 
[`zipnote`][zipnote] 
[`zipsplit`][zipsplit] 

### `bzip2`
[bzip2 -&#99;]:                 #bzip2                         '```&#10;$ bzip2 -&#99;&#10;$ bzip2 --stdout&#10;```&#10;Write output to STDOUT and do not replace the original file.&#10;Rothwell, William. _CompTIA Linux+ Portable Command Guide_.: 271'
[bzip2 -&#100;]:                #bzip2                         '```&#10;$ bzip2 -&#100;&#10;$ bzip2 --decompress&#10;```&#10;Decompress archive (equivalent to `bunzip2`)&#10;Rothwell, William. _CompTIA Linux+ Portable Command Guide_.: 271'
[bzip2 -&#118;]:                #bzip2                         '```&#10;$ bzip2 -&#118;&#10;```&#10;Verbose&#10;Rothwell, William. _CompTIA Linux+ Portable Command Guide_.: 271'
[bzip2 -&#102;]:                #bzip2                         '```&#10;$ bzip2 -&#102;&#10;$ bzip2 --force&#10;```&#10;force overwrite of output files'
[bzip2 -&#122;]:                #bzip2                         '```&#10;$ bzip2 -&#122;&#10;$ bzip2 --compress&#10;```&#10;force compression'

<code>&nbsp;</code>  <code>&nbsp;</code> <code>&nbsp;</code> [`c`][bzip2 -&#99;] [`d`][bzip2 -&#100;] <code>&nbsp;</code> [`f`][bzip2 -&#102;] <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> [`v`][bzip2 -&#118;] <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> [`z`][bzip2 -&#122;]

### `compress`
[compress -&#99;]:              #compress                      '```&#10;$ compress -&#99;&#10;```&#10;Display contents of the archive to STDOUT (same as using `zcat`)'
[compress -&#102;]:             #compress                      '```&#10;$ compress -&#102;&#10;```&#10;Compress symbolic links'
[compress -&#114;]:             #compress                      '```&#10;$ compress -&#114;&#10;```&#10;Compress files recursively within a specified directory'
[uncompress -&#102;]:           #compress                    '```&#10;$ uncompress -&#102;&#10;```&#10;overwrite existing files without prompting, if they exist'
[uncompress -&#114;]:           #compress                    '```&#10;$ uncompress -&#114;&#10;```&#10;decompress files recursively'

<code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> [`c`][compress -&#99;] <code>&nbsp;</code> <code>&nbsp;</code> [`f`][compress -&#102;] <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> [`r`][compress -&#114;] <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> 

### `cpio`
[cpio -&#48;]:                  #cpio                          '```&#10;$ cpio -&#48;&#10;$ cpio --null&#10;```&#10;With `-o` or `-p`, read a list of filenames terminated with a `NUL` byte (all zeros) instead of a newline.&#10;Robbins, Arnold. _UNIX in a Nutshell_ 4th ed (2005): 45'
[cpio -&#97;]:                  #cpio                          '```&#10;$ cpio -&#97;&#10;$ cpio --reset-access-time&#10;```&#10;Reset access times of input files&#10;Robbins, Arnold. _UNIX in a Nutshell_ 4th ed (2005): 43'
[cpio -&#65;]:                  #cpio                          '```&#10;$ cpio -&#65;&#10;$ cpio --append&#10;```&#10;Append files to an archive (must be used with `-O` or `-F`)&#10;Robbins, Arnold. _UNIX in a Nutshell_ 4th ed (2005): 43'
[cpio -&#98;]:                  #cpio                          '```&#10;$ cpio -&#98;&#10;$ cpio --swap&#10;```&#10;Swap bytes and half-words to convert between big-endian and little-endian 32-bit integers.&#10;Robbins, Arnold. _UNIX in a Nutshell_ 4th ed (2005): 43'
[cpio -&#66;]:                  #cpio                          '```&#10;$ cpio -&#66;&#10;```&#10;block input or output using 5120 bytes per record (512 bytes is default)&#10;Robbins, Arnold. _UNIX in a Nutshell_ 4th ed (2005): 43'
[cpio -&#99;]:                  #cpio                          '```&#10;$ cpio -&#99;&#10;```&#10;read or write header information as ASCII characters&#10;Robbins, Arnold. _UNIX in a Nutshell_ 4th ed (2005): 43'
[cpio -&#67;]:                  #cpio                          '```&#10;$ cpio -&#67; $N&#10;$ cpio --io-size $N&#10;```&#10;Like `-B`, but block size can be any positive integer `$N`&#10;Robbins, Arnold. _UNIX in a Nutshell_ 4th ed (2005): 43'
[cpio -&#100;]:                 #cpio                          '```&#10;$ cpio -&#100;&#10;$ cpio --make-directories&#10;```&#10;Create directories as needed&#10;Robbins, Arnold. _UNIX in a Nutshell_ 4th ed (2005): 43'
[cpio -&#69;]:                  #cpio                          '```&#10;$ cpio -&#69; $FILE&#10;$ cpio --pattern-file $FILE&#10;```&#10;Extract filenames listed in `$FILE` from the archive&#10;Robbins, Arnold. _UNIX in a Nutshell_ 4th ed (2005): 43'
[cpio -&#102;]:                 #cpio                          '```&#10;$ cpio -&#102;&#10;$ cpio --nonmatching&#10;```&#10;Reverse the sense of copying; copy all files except those that match `$PATTERNS`&#10;Robbins, Arnold. _UNIX in a Nutshell_ 4th ed (2005): 43'
[cpio -&#70;]:                  #cpio                          '```&#10;$ cpio -&#70; $FILE&#10;$ cpio --file $FILE&#10;```&#10;Same as `-O`&#10;Robbins, Arnold. _UNIX in a Nutshell_ 4th ed (2005): 44'
[cpio -&#72;]:                  #cpio                          '```&#10;$ cpio -&#72; $TYPE&#10;$ cpio --format $TYPE&#10;```&#10;Read or write header information according to `$TYPE`, whose values include:&#10;  - `bin`                 original binary format&#10;  - `crc`                 ASCII header containing expanded device numbers&#10;  - `hpbin`               obsolete binary format used by the HP-UX `cpio`&#10;  - `hpodc`               HP-UX portable format&#10;  - `newc`                SVR4 portable (ASCII) format&#10;  - `odc`                 old POSIX.1 portable (ASCII) format&#10;  - `tar`                 `tar` header&#10;  - `ustar`               IEEE/P1003 Data Interchange Standard header&#10;&#10;Robbins, Arnold. _UNIX in a Nutshell_ 4th ed (2005): 43'
[cpio -&#105;]:                 #cpio                          '```&#10;$ cpio -&#105; $PATTERNS&#10;$ cpio --extract $PATTERNS&#10;```&#10;Copy "in" (extract) files whose names match selected `$PATTERNS`, which can include bash filename metacharacters. If no patterns are provided, then all files are copied.&#10;Robbins, Arnold. _UNIX in a Nutshell_ 4th ed (2005): 42'
[cpio -&#73;]:                  #cpio                          '```&#10;$ cpio -&#73; $FILE&#10;```&#10;Read `$FILE` as an input archive&#10;Robbins, Arnold. _UNIX in a Nutshell_ 4th ed (2005): 43'
[cpio -&#107;]:                 #cpio                          '```&#10;$ cpio -&#107;&#10;```&#10;Ignored for compatibility'
[cpio -&#108;]:                 #cpio                          '```&#10;$ cpio -&#108;&#10;$ cpio --link&#10;```&#10;Link files instead of copying (can only be used with `-p`)&#10;Robbins, Arnold. _UNIX in a Nutshell_ 4th ed (2005): 43'
[cpio -&#76;]:                  #cpio                          '```&#10;$ cpio -&#76;&#10;$ cpio --dereference&#10;```&#10;Follow symbolic links&#10;Robbins, Arnold. _UNIX in a Nutshell_ 4th ed (2005): 43'
[cpio -&#109;]:                 #cpio                          '```&#10;$ cpio -&#109;&#10;$ cpio --preserve-modification-time&#10;```&#10;Retain previous file modification time&#10;Robbins, Arnold. _UNIX in a Nutshell_ 4th ed (2005): 44'
[cpio -&#77;]:                  #cpio                          '```&#10;$ cpio -&#77; $MESSAGE&#10;$ cpio --message $MESSAGE&#10;```&#10;Print `$MESSAGE` when switching media (valid only with `-I` or `-O`)&#10;Robbins, Arnold. _UNIX in a Nutshell_ 4th ed (2005): 44'
[cpio -&#110;]:                 #cpio                          '```&#10;$ cpio -&#110;&#10;$ cpio --numeric-uid-gid&#10;```&#10;When verbosely listing contents, show user ID and group ID numerically&#10;Robbins, Arnold. _UNIX in a Nutshell_ 4th ed (2005): 45'
[cpio -&#111;]:                 #cpio                          '```&#10;$ cpio -&#111;&#10;$ cpio --create&#10;```&#10;Copy "out" a list of files whose names are given on STDIN.&#10;Robbins, Arnold. _UNIX in a Nutshell_ 4th ed (2005): 42'
[cpio -&#79;]:                  #cpio                          '```&#10;$ cpio -&#79; $FILE&#10;```&#10;Direct output to `$FILE`&#10;Robbins, Arnold. _UNIX in a Nutshell_ 4th ed (2005): 44'
[cpio -&#112;]:                 #cpio                          '```&#10;$ cpio -&#112; $DIRECTORY&#10;$ cpio --create $DIRECTORY&#10;```&#10;Copy (pass) files to another local directory. Destination pathnames are interpreted relative to the named `$DIRECTORY`.&#10;Robbins, Arnold. _UNIX in a Nutshell_ 4th ed (2005): 42'
[cpio -&#114;]:                 #cpio                          '```&#10;$ cpio -&#114;&#10;$ cpio --rename&#10;```&#10;Rename files interactively&#10;Robbins, Arnold. _UNIX in a Nutshell_ 4th ed (2005): 44'
[cpio -&#82;]:                  #cpio                          '```&#10;$ cpio -&#82; $ID&#10;$ cpio --owner $ID&#10;```&#10;Reassign file ownership and group information to `$ID` (following the format "user:group")&#10;Robbins, Arnold. _UNIX in a Nutshell_ 4th ed (2005): 44'
[cpio -&#115;]:                 #cpio                          '```&#10;$ cpio -&#115;&#10;$ cpio --swap-bytes&#10;```&#10;Swap bytes of each two-byte half-word&#10;Robbins, Arnold. _UNIX in a Nutshell_ 4th ed (2005): 44'
[cpio -&#83;]:                  #cpio                          '```&#10;$ cpio -&#83;&#10;$ cpio --swap-halfwords&#10;```&#10;Swap half-words of each four-byte word&#10;Robbins, Arnold. _UNIX in a Nutshell_ 4th ed (2005): 44'
[cpio -&#116;]:                 #cpio                          '```&#10;$ cpio -&#116;&#10;$ cpio --list&#10;```&#10;Print a table of contents of the input (create no files). When used with `-v`, output resembles that of `ls -l`&#10;Robbins, Arnold. _UNIX in a Nutshell_ 4th ed (2005): 44'
[cpio -&#117;]:                 #cpio                          '```&#10;$ cpio -&#117;&#10;$ cpio --unconditional&#10;```&#10;Unconditional copy; old files can overwrite new ones&#10;Robbins, Arnold. _UNIX in a Nutshell_ 4th ed (2005): 44'
[cpio -&#118;]:                 #cpio                          '```&#10;$ cpio -&#118;&#10;$ cpio --verbose&#10;```&#10;Print a list of filenames processed&#10;Robbins, Arnold. _UNIX in a Nutshell_ 4th ed (2005): 44'
[cpio -&#86;]:                  #cpio                          '```&#10;$ cpio -&#86;&#10;$ cpio --dot&#10;```&#10;Print a dot for each file read or written (showing cpio working without cluttering the screen).&#10;Robbins, Arnold. _UNIX in a Nutshell_ 4th ed (2005): 44'

[`0`][cpio -&#48;]   [`a`][cpio -&#97;] [`b`][cpio -&#98;] [`c`][cpio -&#99;] [`d`][cpio -&#100;] <code>&nbsp;</code> [`f`][cpio -&#102;] <code>&nbsp;</code> <code>&nbsp;</code> [`i`][cpio -&#105;] <code>&nbsp;</code> [`k`][cpio -&#107;] [`l`][cpio -&#108;] [`m`][cpio -&#109;] [`n`][cpio -&#110;] [`o`][cpio -&#111;] [`p`][cpio -&#112;] <code>&nbsp;</code> [`r`][cpio -&#114;] [`s`][cpio -&#115;] [`t`][cpio -&#116;] [`u`][cpio -&#117;] [`v`][cpio -&#118;] <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code>  <br><code>&nbsp;</code>&nbsp;[`A`][cpio -&#65;] [`B`][cpio -&#66;] [`C`][cpio -&#67;] <code>&nbsp;</code> [`E`][cpio -&#69;] [`F`][cpio -&#70;] <code>&nbsp;</code> [`H`][cpio -&#72;] [`I`][cpio -&#73;] <code>&nbsp;</code> <code>&nbsp;</code> [`L`][cpio -&#76;] [`M`][cpio -&#77;] <code>&nbsp;</code> [`O`][cpio -&#79;] <code>&nbsp;</code> <code>&nbsp;</code> [`R`][cpio -&#82;] [`S`][cpio -&#83;] <code>&nbsp;</code> <code>&nbsp;</code> [`V`][cpio -&#86;] <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> 

Create an archive that contains all the files in the current working directory <sup>[Haeder][Haeder]: 94</sup>
```sh
ls | cpio -ov > /tmp/archive.cpio
```
Extract all the files from the archive we just created
```sh
cpio -iv < /tmp/archive.cpio
```
### `dar`
Create a differential (or incremental) backup of {file}, using full.bak as reference
```sh
dar -R /path/to/file -c diff1.bak -A full.bak
```
Create a full backup of {file}
```sh
dar -R /path/to/file -c full.bak
```
Restore full.bak
```sh
dar -x full.bak
```
### `gzip`
[gzip -&#99;]:                  #gzip                          '```&#10;$ gzip -&#99;&#10;```&#10;Write output to STDOUT and do not replace the original file.&#10;Rothwell, William. _CompTIA Linux+ Portable Command Guide_.: 270'
[gzip -&#100;]:                 #gzip                          '```&#10;$ gzip -&#100;&#10;```&#10;Decompress the file (equivalent to `gunzip`)&#10;Rothwell, William. _CompTIA Linux+ Portable Command Guide_.: 270'
[gzip -&#114;]:                 #gzip                          '```&#10;$ gzip -&#114;&#10;```&#10;Recursive: Used when a directory argument is given to compress all files within it, as well as subdirectories.&#10;Rothwell, William. _CompTIA Linux+ Portable Command Guide_.: 270'
[gzip -&#118;]:                 #gzip                          '```&#10;$ gzip -&#118;&#10;```&#10;Verbose: Display percentage of compression&#10;Rothwell, William. _CompTIA Linux+ Portable Command Guide_.: 270'

<code>&nbsp;</code>  <code>&nbsp;</code> <code>&nbsp;</code> [`c`][gzip -&#99;] [`d`][gzip -&#100;] <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> [`r`][gzip -&#114;] <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> [`v`][gzip -&#118;] <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code>

Zip a single file in-place; each file is replaced by one with the extension `.gz` or `.z`, maintaining ownership modes, access and modification times
```sh
gzip -#
gzip --fast
gzip --best
```
Compress {symlink}
```sh
gzip -f symlink
gzip --force symlink
```
Page through .gz files

### `tar`
[tar -&#65;]:                   #tar                           '```&#10;$ tar -&#65;&#10;$ tar --concatenate&#10;```&#10;Append new files to an archive&#10;Rothwell, William. _CompTIA Linux+ Portable Command Guide_.: 268'
[tar -&#99;]:                   #tar                           '```&#10;$ tar -&#99;&#10;$ tar --create&#10;```&#10;Create an archive&#10;Rothwell, William. _CompTIA Linux+ Portable Command Guide_.: 268'
[tar -&#67;]:                   #tar                           '```&#10;$ tar -&#67; $PATH $FILES&#10;$ tar --directory $PATH $FILES&#10;```&#10;change working directory to `$PATH` before adding $FILES; makes it possible to archive files that do not share a common ancestor directory'
[tar -&#100;]:                  #tar                           '```&#10;$ tar -&#100;&#10;```&#10;Compare the difference between the contents of an archive and the files in a directory&#10;Rothwell, William. _CompTIA Linux+ Portable Command Guide_.: 268'
[tar -&#102;]:                  #tar                           '```&#10;$ tar -&#102;&#10;$ tar --file&#10;```&#10;Specify the name of the archive&#10;Rothwell, William. _CompTIA Linux+ Portable Command Guide_.: 268'
[tar -&#106;]:                  #tar                           '```&#10;$ tar -&#106;&#10;$ tar --bzip2&#10;```&#10;Compress/uncompress archive using `bzip2`&#10;Rothwell, William. _CompTIA Linux+ Portable Command Guide_.: 268'
[tar -&#74;]:                   #tar                           '```&#10;$ tar -&#74;&#10;```&#10;Compress/uncompress archive using `xz`&#10;Rothwell, William. _CompTIA Linux+ Portable Command Guide_.: 268'
[tar -&#112;]:                  #tar                           '```&#10;$ tar -&#112;&#10;$ tar --preserve-permissions&#10;```&#10;extract information about file permissions'
[tar -&#114;]:                  #tar                           '```&#10;$ tar -&#114;&#10;$ tar --append&#10;```&#10;append files to the end of an archive'
[tar -&#116;]:                  #tar                           '```&#10;$ tar -&#116;&#10;$ tar --list&#10;```&#10;List the contents of an archive&#10;Rothwell, William. _CompTIA Linux+ Portable Command Guide_.: 268'
[tar -&#117;]:                  #tar                           '```&#10;$ tar -&#117;&#10;```&#10;Update; only append newer files into an existing archive&#10;Rothwell, William. _CompTIA Linux+ Portable Command Guide_.: 268'
[tar -&#118;]:                  #tar                           '```&#10;$ tar -&#118;&#10;$ tar --verbose&#10;```&#10;Verbose output&#10;Rothwell, William. _CompTIA Linux+ Portable Command Guide_.: 268'
[tar -&#120;]:                  #tar                           '```&#10;$ tar -&#120;&#10;$ tar --extract&#10;```&#10;Extract the contents of an archive&#10;Rothwell, William. _CompTIA Linux+ Portable Command Guide_.: 268'
[tar -&#122;]:                  #tar                           '```&#10;$ tar -&#122;&#10;$ tar --gzip&#10;```&#10;Compress/uncompress archive using `gzip`&#10;Rothwell, William. _CompTIA Linux+ Portable Command Guide_.: 268'
[tar -&#84;]:                   #tar                           '```&#10;$ tar -&#84; $FILENAMES&#10;$ tar --files-from $FILENAMES&#10;```&#10; a list of filenames to be archived, one filename per line, from `$FILENAMES`'

<code>&nbsp;</code>  <code>&nbsp;</code> <code>&nbsp;</code> [`c`][tar -&#99;] [`d`][tar -&#100;] <code>&nbsp;</code> [`f`][tar -&#102;] <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> [`j`][tar -&#106;] <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> [`p`][tar -&#112;] <code>&nbsp;</code> [`r`][tar -&#114;] <code>&nbsp;</code> [`t`][tar -&#116;] [`u`][tar -&#117;] [`v`][tar -&#118;] <code>&nbsp;</code> [`x`][tar -&#120;] <code>&nbsp;</code> [`z`][tar -&#122;]  <br><code>&nbsp;</code> [`A`][tar -&#65;] <code>&nbsp;</code> [`C`][tar -&#67;] <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> [`J`][tar -&#74;] <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> 

Create {archive} from contents of {path}
```sh
tar -cf archive path
tar --create --file archive path
```
Create bzip2-compressed {archive} from contents of {path}
```sh
tar -cfj archive path
tar --create --file --bzip archive path
```
Create gzip-compressed {archive} from contents of {path}
```sh
tar -cfz archive path
tar --create --file --gzip archive path
```
Add {file} to {archive}
```sh
tar -rf archive file
tar --append --file archive file
```
List the contents of {archive}
```sh
tar -tf archive
tar --list --file archive
```
Extract contents of {tarfile} in the current directory
```sh
tar -xf archive
tar --extract --file archive
```
Extract only {file} from {archive}
```sh
tar -xf archive file tar--extract --file archive file
```
Extract contents of gzip-compressed {archive} to {path}
```sh
tar -xzf archive -C path
```

### `unzip`
Extract compressed files in a zip archive

### `xz`
[xz -&#99;]:                    #xz                            '```&#10;$ xz -&#99;&#10;```&#10;Write output to STDOUT and do not replace the original file.&#10;Rothwell, William. _CompTIA Linux+ Portable Command Guide_.: 270'
[xz -&#100;]:                   #xz                            '```&#10;$ xz -&#100;&#10;```&#10;Decompress archive (equivalent to `unxz`)&#10;Rothwell, William. _CompTIA Linux+ Portable Command Guide_.: 270'
[xz -&#108;]:                   #xz                            '```&#10;$ xz -&#108;&#10;```&#10;List information about an existing archive&#10;Rothwell, William. _CompTIA Linux+ Portable Command Guide_.: 270'
[xz -&#118;]:                   #xz                            '```&#10;$ xz -&#118;&#10;```&#10;Display percentage of compression&#10;Rothwell, William. _CompTIA Linux+ Portable Command Guide_.: 270'

<code>&nbsp;</code>  <code>&nbsp;</code> <code>&nbsp;</code> [`c`][xz -&#99;] [`d`][xz -&#100;] <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> [`l`][xz -&#108;] <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> [`v`][xz -&#118;] <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code>

### `zip`
[zip -&#100;]:                  #zip                           '```&#10;$ zip -&#100;&#10;```&#10;Decompress archive (equivalent to `unzip`)&#10;Rothwell, William. _CompTIA Linux+ Portable Command Guide_.: 272'
[zip -&#118;]:                  #zip                           '```&#10;$ zip -&#118;&#10;```&#10;Verbose; display percentage of compression&#10;Rothwell, William. _CompTIA Linux+ Portable Command Guide_.: 272'
[zip -&#117;]:                  #zip                           '```&#10;$ zip -&#117;&#10;```&#10;Update an archive with new content&#10;Rothwell, William. _CompTIA Linux+ Portable Command Guide_.: 272'
[zip -&#114;]:                  #zip                           '```&#10;$ zip -&#114;&#10;```&#10;Zip recursively&#10;Rothwell, William. _CompTIA Linux+ Portable Command Guide_.: 272'
[zip -&#120;]:                  #zip                           '```&#10;$ zip -&#120; $FILES&#10;```&#10;Specify files to be excluded from the archive&#10;Rothwell, William. _CompTIA Linux+ Portable Command Guide_.: 272'

<code>&nbsp;</code>  <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> [`d`][zip -&#100;] <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> [`r`][zip -&#114;] <code>&nbsp;</code> <code>&nbsp;</code> [`u`][zip -&#117;] [`v`][zip -&#118;] <code>&nbsp;</code> [`x`][zip -&#120;] <code>&nbsp;</code> <code>&nbsp;</code>

Archive files in InfoZIP format
```sh
zip zipfile *files
```


## Audio
[alsamixer]:                   #alsamixer                      '```&#10;$ alsamixer&#10;```&#10;Command-line mixer'
[amixer]:                      #amixer                         '```&#10;$ amixer&#10;```&#10;Command-line mixer for ALSA sound card driver'
[speaker-test]:                #speaker-test                   '```&#10;$ speaker-test&#10;```&#10;Generates a tone that can be used to test the speakers of a computer'

[`alsamixer`][alsamixer] 
[`amixer`][amixer] 
[`speaker-test`][speaker-test] 

### ALSA
**Advanced Linux Sound Architecture (ALSA)** replaced the earlier "Open Sound System".<sup>[Schatz][Schatz]</sup>

ALSA kernel modules are designed to offer an interface that "corresponds to that of the hardware" to keep the modules simple, and similar cards will offer a similar interface. They offer two interfaces: **operational** and **configuration**

**Operational interface** through the `/dev/` tree, with 3 main types of devices
- **PCM** for recording or playing digitized sound samples
- **CTL** for manipulating the internal mixer and routing of the card
- **MIDI** to control the MIDI port, if it exists
- Optionally, **sequencer** devices may also exist if the card has a builtin sound synthesizer with an associated **timer** device

**Status and configuration interface** via the `/proc/asound/` tree (ref [`amixer`][amixer])

PCM devices come in two varieties: **output** and **input** and are numbered from 0, which is generally for analog multichannel sound.

Cards have input or output **sockets**, and the **mixer** is controlled by the CTL device and routes sound samples among devices and sockets.

Controls come in 3 types;
- **Playback** controls are associated with an output device or **copy (input-to-output)** routes
- **Capture** controls are associated with an input device or **copy (output-to-input)** routes
- **Feature** controls drive features of the card or mixer, usually just a switch to enable or disable the feature, though some also have levels. The **Master Volume** control is the most typical example, which allows control of the internal amplifier feature of the card. A more interesting example is that of a 3d spatializer that can be represented by a switch to enable or disable it as well as two levels.

Typical channel assignments
- **0**: front left
- **1**: front right
- **2**: rear left
- **3**: rear right

### PulseAudio
PulseAudio is a sound server for POSIX OSes and a fixture on many Linux distributions.

PulseAudio is built around **sources** and **sinks** (i.e. devices) connected to **source outputs** and **sink inputs** (streams)
- **Source** is an input device that produces samples, usually running a thread with its own event loop, generating sample chunks which are posted to all connected source outputs
- **Source output** is a recording stream which consumes samples from a source
- **Sink** is an output device that consumes samples, usually running a thread with its own event loop mixing sample chunks from connect sink inputs
- **Sink input** is a playback stream, connected to a sink and producing samples for it

### `alsamixer`
Command-line mixer
### `amixer`
Command-line mixer for ALSA sound card driver <sup>[Schatz][Schatz]</sup>

Display simplified list of controls 
```sh
amixer scontrols
```
Display full list of controls
```sh
amixer controls
```
Show information about a mixer device
```sh
amixer info
```
### `speaker-test`
Test loudspeakers with a 2-speaker setup
```sh
speaker-test -c 2
```

## Bash builtins

[`bg`][bg] 
[`bind`][bind] 
[`break`][break] 
[`builtin`][builtin] 
[`caller`][caller] 
[`case`][case]/[`esac`][esac] 
[`cd`][cd] 
[`command`][command] 
[`compgen`][compgen] 
[`complete`][complete] 
[`compopt`][compopt] 
[`continue`][continue] 
[`declare`][declare] 
[`dirs`][dirs] 
[`disown`][disown] 
[`do`][do]/[`done`][done] 
[`echo`][echo] 
[`enable`][enable] 
[`eval`][eval] 
[`exec`][exec] 
[`exit`][exit] 
[`export`][export] 
[`false`][false] 
[`fc`][fc] 
[`fg`][fg] 
[`for`][for] 
[`function`][function] 
[`getopts`][getopts] 
[`hash`][hash] 
[`help`][help] 
[`history`][history] 
[`if`][if]/[`fi`][fi] 
[`jobs`][jobs] 
[`kill`][kill] 
[`let`][let] 
[`local`][local] 
[`logout`][logout]
[`mapfile`][mapfile]
[`popd`][popd] 
[`printf`][printf] 
[`pushd`][pushd] 
[`pwd`][pwd] 
[`read`][read] 
[`readarray`][readarray] 
[`readonly`][readonly] 
[`return`][return] 
[`select`][select] 
[`set`][set] 
[`shift`][shift] 
[`shopt`][shopt] 
[`source`][source] 
[`suspend`][suspend] 
[`test`][test] 
[`time`][time] 
[`times`][times] 
[`trap`][trap] 
[`true`][true] 
[`type`][type] 
[`typeset`][typeset] 
[`ulimit`][ulimit] 
[`umask`][umask] 
[`unalias`][unalias] 
[`unset`][unset] 
[`until`][until] 
[`wait`][wait] 
[`while`][while] 

## Boot
[`grub-install`][grub-install] 
[`grub-mkconfig`][grub-mkconfig]
[`grub2-editenv`][grub2-editenv] 
[`lilo`][lilo] 
[`update-grub`][update-grub] 

Bootloaders like GRUB (GRand Unified Bootloader) or _u-boot_ turns on power supplies and scans buses and interfaces to locate the kernel image and the root filesystem. LILO (LInux LOader) is also another bootloader that can be found on older Linux systems (LALOS)

Microcontrollers may be listening when the system is nominally off; they typically have their own BIOS and kernels and are inaccessible from the main system
- **Baseboard Management Controller (BMC)** responds to **wake-on-LAN (WOL)**
- **Intel Management Engine (IME)** `x86_64` software suite for remote management of systems; firmware is based on `Minix` and runs on the **Platform Controller Hub** processor, not the main CPU
- **System Management Mode (SMM)** launches UEFI software

**`initrd`** (Initial RAM disk) is a temporary file system that's loaded into memory when the system boots

Linux kernel is typically named **vmlinux** (or **vmlinuz** when compressed). Kernel ring buffer contains messages related to the Linux kernel. A ring buffer is a data structure that is always the same size; old messages are discarded as new ones come in, once the buffer is full. `dmesg` is used to see its contents, and the messages are also stored in `/var/log/dmesg`

#### GRUB Rescue prompt
When GRUB2 is unable to find the GRUB folder or its contents are missing or corrupted, it displays the prompt `grub rescue>`. This means it failed to load the `normal` module. <sup>[howtoforge.com](https://www.howtoforge.com/tutorial/repair-linux-boot-with-grub-rescue/ "Repair Linux boot failures in GRUB 2 rescue mode")</sup>

From GRUB rescue prompt:
```grub
set prefix=(hd0,1)/boot/grub
set root=(hd0,1)
insmod normal
normal
```
After booting the system, GRUB should be updated and reinstalled:

Update GRUB config file
```sh
update-grub
```
Reinstall GRUB
```sh
grub-install /dev/sdx
```

#### `grub-install`
Install GRUB as bootloader
```sh
grub-install --target=i386-pc /dev/sdb
```
Install boot images within a directory other than /boot
```sh
grub-install --boot-directory
```
#### `grub-mkconfig`
Generate GRUB configuration
```sh
grub-mkconfig -o /boot/grub/grub.cfg
```
#### `grub2-mkconfig`
Send output of grub2-mkconfig to the correct location for booting
```sh
grub2-mkconfig --output=/boot/grub2/grub.cfg
```
#### `grub2-editenv`
Disable the Nouveau display driver while installing the proprietary Nvidia display driver on Fedora <sup>[linuxconfig.org](https://linuxconfig.org/how-to-install-the-nvidia-drivers-on-fedora-31 "How to install the NVIDIA drivers on Fedora 31")</sup>
```sh
grub2-editenv - set "$(grub2-editenv - list | grep kernelopts) nouveau.modeset=0"
```
#### `update-grub`
Update GRUB config file
```sh
update-grub
```

## Build
[`aclocal`][aclocal] 
[`as`][as] 
[`autoconf`][autoconf] 
[`autoheader`][autoheader] 
[`automake`][automake] 
[`autoreconf`][autoreconf] 
[`autoscan`][autoscan] 
[`autoupdate`][autoupdate] 
[`bison`][bison] 
[`cc`][cc] 
[`ctags`][ctags] 
[`etags`][etags] 
[`flex`][flex] 
[`g++`][g++] 
[`gcc`][gcc] 
[`gcore`][gcore] 
[`gdb`][gdb] 
[`gprof`][gprof] 
[`ldd`][ldd] 
[`lex`][lex] 
[`make`][make] 
[`xgettext`][xgettext] 
[`yacc`][yacc] 

#### `autoconf`
Other related programs are usually invoked automatically by tools in the `autoconf` suite: `autoreconf`, `autoscan`, and `autoupdate`
#### `cc`
[cc -&#99;]:                    #cc                            '```&#10;$ cc -&#99;&#10;```&#10;suppress loading and keep any object files that were produced&#10;Robbins, Arnold. _UNIX in a Nutshell_ 4th ed (2005): 32'
[cc -&#68;]:                    #cc                            '```&#10;$ cc -&#68; $NAME=$DEF&#10;```&#10;supply a `#define` directive, defining `$NAME` to be `$DEF` (or 1 by default)&#10;Robbins, Arnold. _UNIX in a Nutshell_ 4th ed (2005): 32'
[cc -&#69;]:                    #cc                            '```&#10;$ cc -&#69;&#10;```&#10;run only the macro preprocessor, sending results to STDOUT&#10;Robbins, Arnold. _UNIX in a Nutshell_ 4th ed (2005): 32'
[cc -&#103;]:                   #cc                            '```&#10;$ cc -&#103;&#10;```&#10;generate more symbol-table information needed for debuggers&#10;Robbins, Arnold. _UNIX in a Nutshell_ 4th ed (2005): 32'
[cc -&#73;]:                    #cc                            '```&#10;$ cc -&#73; $PATH&#10;```&#10;search for include files in directory `$PATH` (in addition to standard locations). Supply a `-I` for each new `$PATH` to be searched.&#10;Robbins, Arnold. _UNIX in a Nutshell_ 4th ed (2005): 32'
[cc -&#108;]:                   #cc                            '```&#10;$ cc -&#108; $NAME&#10;```&#10;Link source file with library files "lib$NAME.so" or "lib$NAME.a"&#10;Robbins, Arnold. _UNIX in a Nutshell_ 4th ed (2005): 32'
[cc -&#76;]:                    #cc                            '```&#10;$ cc -&#76; $PATH&#10;```&#10;Like `-I`, but search `$PATH` for library archives&#10;Robbins, Arnold. _UNIX in a Nutshell_ 4th ed (2005): 32'
[cc -&#111;]:                   #cc                            '```&#10;$ cc -&#111; $FILE&#10;```&#10;Send object output to `$FILE` instead of to a.out.&#10;Robbins, Arnold. _UNIX in a Nutshell_ 4th ed (2005): 32'
[cc -&#79;]:                    #cc                            '```&#10;$ cc -&#79;&#10;```&#10;Optimize object code (produced from .c or .i files). Some compilers accept an additional argument to `-O` specifying the optimization level.&#10;Robbins, Arnold. _UNIX in a Nutshell_ 4th ed (2005): 32'
[cc -&#112;]:                   #cc                            '```&#10;$ cc -&#112;&#10;```&#10;Generate benchmark code to count&#10;Robbins, Arnold. _UNIX in a Nutshell_ 4th ed (2005): 32'
[cc -&#80;]:                    #cc                            '```&#10;$ cc -&#80;&#10;```&#10;Run only the preprocessor and place the result in "file.i"&#10;Robbins, Arnold. _UNIX in a Nutshell_ 4th ed (2005): 32'
[cc -&#83;]:                    #cc                            '```&#10;$ cc -&#83;&#10;```&#10;Compile (and optimize, if `-O` is supplied), but do not assemble or load; assembler output is placed in "file.s".&#10;Robbins, Arnold. _UNIX in a Nutshell_ 4th ed (2005): 32'
[cc -&#85;]:                    #cc                            '```&#10;$ cc -&#85; $NAME&#10;```&#10;Remove definition of `$NAME`, as if through an `#undef` directive.&#10;Robbins, Arnold. _UNIX in a Nutshell_ 4th ed (2005): 32'

<code>&nbsp;</code>   <code>&nbsp;</code> <code>&nbsp;</code> [`c`][cc -&#99;] <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> [`g`][cc -&#103;] <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> [`l`][cc -&#108;] <code>&nbsp;</code> <code>&nbsp;</code> [`o`][cc -&#111;] [`p`][cc -&#112;] <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code>  <br><code>&nbsp;</code>&nbsp;<code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> [`D`][cc -&#68;] [`E`][cc -&#69;] <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> [`I`][cc -&#73;] <code>&nbsp;</code> <code>&nbsp;</code> [`L`][cc -&#76;] <code>&nbsp;</code> <code>&nbsp;</code> [`O`][cc -&#79;] [`P`][cc -&#80;] <code>&nbsp;</code> <code>&nbsp;</code> [`S`][cc -&#83;] <code>&nbsp;</code> [`U`][cc -&#85;] <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> 

#### `make`
[make -&#98;]:                  #make                          '```&#10;$ make -&#98;&#10;```&#10;Silently accepted, but ignored, for compatibility with other versions of `make`&#10;Robbins, Arnold. _UNIX in a Nutshell_ 4th ed (2005): 746'
[make -&#66;]:                  #make                          '```&#10;$ make -&#66;&#10;$ make --always-make&#10;```&#10;Treat all targets as out of date. All targets are remade, no matter what the actual status is of their prerequisites&#10;Robbins, Arnold. _UNIX in a Nutshell_ 4th ed (2005): 746'
[make -&#67;]:                  #make                          '```&#10;$ make -&#67; $PATH&#10;$ make --directory $PATH&#10;```&#10;Change directory to `$PATH` before reading makefiles; usually used for recursive invocations of `make`.'
[make -&#100;]:                 #make                          '```&#10;$ make -&#100;&#10;$ make --debug=a&#10;```&#10;Print debugging information in addition to regular output. This information includes which files are out of date, the file names being compared, '
[make -&#101;]:                 #make                          '```&#10;$ make -&#101;&#10;$ make --environment-overrides&#10;```&#10;Environment variables override any macros defined in makefiles.'
[make -&#102;]:                 #make                          '```&#10;$ make -&#102; $MAKEFILE&#10;$ make --file $MAKEFILE&#10;```&#10;Use `$MAKEFILE` as the makefile; can be used more than once to concatenate multiple makefiles. If not specified, `make` looks for "GNUmakefile", "makefile", and "Makefile" in that order.'
[make -&#104;]:                 #make                          '```&#10;$ make -&#104;&#10;$ make --help&#10;```&#10;Print a usage summary, and then exit.'
[make -&#105;]:                 #make                          '```&#10;$ make -&#105;&#10;$ make --ignore-errors&#10;```&#10;Ignore error codes from commands (equivalent to `.IGNORE`)'
[make -&#73;]:                  #make                          '```&#10;$ make -&#73; $PATH&#10;$ make --include-dir $PATH&#10;```&#10;Look in `$PATH` for makefiles included with the `include` directive. Multiple options add more directories to the list, which is searched by `make` in order.'
[make -&#106;]:                 #make                          '```&#10;$ make -&#106; $COUNT&#10;$ make --jobs $COUNT&#10;```&#10;Run commands in parallel.'
[make -&#107;]:                 #make                          '```&#10;$ make -&#107;&#10;$ make --keep-going&#10;```&#10;Abandon the current target when it fails, but keep working with unrelated targets.'
[make -&#108;]:                 #make                          '```&#10;$ make -&#108; $LOAD&#10;$ make --load-average $LOAD&#10;```&#10;If there are jobs running and the system load average is at least load, do not start any new jobs running.'
[make -&#109;]:                 #make                          '```&#10;$ make -&#109;&#10;```&#10;Silently accepted, but ignored, for compatibility with other version of `make`.'
[make -&#110;]:                 #make                          '```&#10;$ make -&#110;&#10;$ make --dry-run&#10;```&#10;Print commands but do not execute; used for testing.'
[make -&#111;]:                 #make                          '```&#10;$ make -&#111; $FILE&#10;$ make --assume-old $FILE&#10;```&#10;Pretend that `$FILE` is older than the files that depend upon it. This avoids remaking other files that depend on `$FILE`.'
[make -&#112;]:                 #make                          '```&#10;$ make -&#112;&#10;$ make --print-data-base&#10;```&#10;Print macro definitions, suffixes, and built-in rules. In a directory without a makefile, use `env -i make -p` to print out the default variable definitions and built-in rules.'
[make -&#113;]:                 #make                          '```&#10;$ make -&#113;&#10;$ make --question&#10;```&#10;Query; return 0 if the target is up to date; nonzero otherwise.'
[make -&#114;]:                 #make                          '```&#10;$ make -&#114;&#10;$ make --no-builtin-rules&#10;```&#10;Do not use the default rules. This also clears out the default list of suffixes and suffix rules.'
[make -&#115;]:                 #make                          '```&#10;$ make -&#115;&#10;$ make --silent&#10;```&#10;Do not display command lines (same as `.SILENT`)'
[make -&#83;]:                  #make                          '```&#10;$ make -&#83;&#10;$ make --stop&#10;```&#10;Cancel the effect of a previous `-k`. Only needed for recursive `make` invocations, where the `-k` option might be inherited via the `MAKEFLAGS` environment variable.'
[make -&#116;]:                 #make                          '```&#10;$ make -&#116;&#10;$ make --touch&#10;```&#10;Touch the target files, causing them to be updated.'
[make -&#118;]:                 #make                          '```&#10;$ make -&#118; Print version, copyright, and author information, and exit.&#10;$ make --version Print version, copyright, and author information, and exit.&#10;```&#10;'
[make -&#119;]:                 #make                          '```&#10;$ make -&#119;&#10;$ make --print-directory&#10;```&#10;Print the working directory, before and after executing the makefile. Useful for recursive `make` invocations. This is usually done by default, so this option is rarely seen.'
[make -&#87;]:                  #make                          '```&#10;$ make -&#87; $FILE&#10;$ make --assume-new $FILE&#10;```&#10;Treat $FILE as if it had just been modified. Together with `-n`, this lets you see what `make` would do if `$FILE` were modified, without actually doing anything.'

<code>&nbsp;</code>   <code>&nbsp;</code> [`b`][make -&#98;] <code>&nbsp;</code> [`d`][make -&#100;] [`e`][make -&#101;] [`f`][make -&#102;] <code>&nbsp;</code> [`h`][make -&#104;] [`i`][make -&#105;] [`j`][make -&#106;] [`k`][make -&#107;] [`l`][make -&#108;] [`m`][make -&#109;] [`n`][make -&#110;] [`o`][make -&#111;] [`p`][make -&#112;] [`q`][make -&#113;] [`r`][make -&#114;] [`s`][make -&#115;] [`t`][make -&#116;] <code>&nbsp;</code> [`v`][make -&#118;] [`w`][make -&#119;] <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code>  <br><code>&nbsp;</code>&nbsp;<code>&nbsp;</code> [`B`][make -&#66;] [`C`][make -&#67;] <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> [`I`][make -&#73;] <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> [`S`][make -&#83;] <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> [`W`][make -&#87;] <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> 

A common formula when installing software from source is the following sequence of commands 
<sup>[thoughtbot.com](https://thoughtbot.com/blog/the-magic-behind-configure-make-make-install "thoughtbot.com: \"The magic behind configure, make, make install\"")</sup>

```sh
./configure
make
make install
```

Recompile `sendmail`
```sh
make -C /etc/mail
```
Given there are 3 example files (main.cpp, message.cpp, and message.h) in a directory, it produces an executable file named `a.out`
```sh
g++ main.cpp message.cpp
```
Install an alternate version of a program like Python
```sh
cd /opt
wget https://www.python.org/ftp/python/3.8.0/Python-3.8.0.tgz
tar xzf Python-3.8.0.tgz
cd Python-3.8.0
./configure --enable-optimizations
make altinstall
```

##### makefiles
**Makefiles** are sensitive to whitespace, so indentation is significant. The format follows the pattern:
```makefile
{target}: {dependencies}
  {action}
```
where `{target}` is the filename produced by the operation `{action}`, each of which are shell commands.

For any changes in `main.o` and `message.o`, they will be recompiled into `output`, which is the executable. `g++ -c` will compile the code into an object file but not into a binary, creating `main.o`.
```makefile
output: main.o message.o
  g++ main.o message.o -o output

message.o: message.cpp message.h
  g++ -c message.cpp
  
main.o: main.cpp
  g++ -c main.cpp

clean:
  rm *.o output
```
Execute the operations specified in the makefile (if executed a second time without any changes, it will produce a notification that there have been no changes):
```sh
make
```
Execute the `clean` section, removing files
```sh
make clean
```
Targets
- `tinyconfig` smallest possible kernel configuration
- `allnoconfig` answer no to every question when creating a config file

A **configure script** is responsible for preparing the software build, ensuring dependencies are available, such as a C compiler for C programs. 
`make` is invoked after the `configure` script has done its job. 
The **configure** script converts a `Makefile.in` template into a **Makefile**. 
They are not built by hand but packaged by yet another program in the **autotools** suite, such as **autoconf**, **automake**, and others.

A configure.ac file written in **m4sh** (a combination of m4 macros and shell script) is prepared. The first m4 macro called i **AC_INIT**, which initializes autoconf:
```m4
AC_INIT([helloworld], [0.1], [george@thoughtbot.com])
```
The **AM_INIT_AUTOMAKE** macro is also called because we're using **automake**:
```m4
AM_INIT_AUTOMAKE
```
#### `xgettext`
[xgettext -&#97;]:              #xgettext                      '```&#10;$ xgettext -&#97;&#10;$ xgettext --extract-all&#10;```&#10;Extract all strings, not just those in calls to `gettext` or `dgettext` (applies to C, C++, Objective-C, Shell, Python, Lisp, EmacsLisp, librep, Scheme, Java, C#, awk, Tcl, Perl, PHP, GCC-source, and Glade)&#10;Robbins, Arnold. _UNIX in a Nutshell_ 4th ed (2005): 234'
[xgettext -&#99;]:              #xgettext                      '```&#10;$ xgettext -&#99; $TAG&#10;$ xgettext --add-comments $TAG&#10;```&#10;Copy source file comments marked with $TAG into the .po file as #-delimited comments&#10;Robbins, Arnold. _UNIX in a Nutshell_ 4th ed (2005): 235'
[xgettext -&#100;]:             #xgettext                      '```&#10;$ xgettext -&#100; $DOMAIN&#10;$ xgettext --default-domain $DOMAIN&#10;```&#10;Use $DOMAIN.po as the output file instead of messages.po&#10;Robbins, Arnold. _UNIX in a Nutshell_ 4th ed (2005): 235'
[xgettext -&#104;]:             #xgettext                      '```&#10;$ xgettext -&#104;&#10;$ xgettext --help&#10;```&#10;Print a help message on STDOUT&#10;Robbins, Arnold. _UNIX in a Nutshell_ 4th ed (2005): 235'
[xgettext -&#106;]:             #xgettext                      '```&#10;$ xgettext -&#106;&#10;$ xgettext --join-existing&#10;```&#10;Join (merge) extracted messages with those in the current .po file. Domain directives in the existing .po file are ignored&#10;Robbins, Arnold. _UNIX in a Nutshell_ 4th ed (2005): 235'
[xgettext -&#109;]:             #xgettext                      '```&#10;$ xgettext -&#109; $PREFIX&#10;$ xgettext --msgstr-prefix $PREFIX&#10;```&#10;Fill in each `msgstr` with $PREFIX. Intended for debugging.&#10;Robbins, Arnold. _UNIX in a Nutshell_ 4th ed (2005): 235'
[xgettext -&#77;]:              #xgettext                      '```&#10;$ xgettext -&#77; $SUFFIX&#10;$ xgettext --mststr-suffix $SUFFIX&#10;```&#10;Fill in each `msgstr` with $SUFFIX. Intended for debugging.&#10;Robbins, Arnold. _UNIX in a Nutshell_ 4th ed (2005): 235'
[xgettext -&#110;]:             #xgettext                      '```&#10;$ xgettext -&#110;&#10;$ xgettext --add-location&#10;```&#10;Add comments to the .po file indicating the source filename and line number where each string is used&#10;Robbins, Arnold. _UNIX in a Nutshell_ 4th ed (2005): 235'
[xgettext -&#112;]:             #xgettext                      '```&#10;$ xgettext -&#112; $PATH&#10;$ xgettext --output-dir $PATH&#10;```&#10;Place output files in the directory $PATH&#10;Robbins, Arnold. _UNIX in a Nutshell_ 4th ed (2005): 235'
[xgettext -&#115;]:             #xgettext                      '```&#10;$ xgettext -&#115;&#10;$ xgettext --sort-output&#10;```&#10;Sort the output by `msgid` (original string), with all duplicates removed.&#10;Robbins, Arnold. _UNIX in a Nutshell_ 4th ed (2005): 235'
[xgettext -&#120;]:             #xgettext                      '```&#10;$ xgettext -&#120; $EXFILE&#10;$ xgettext --exclude-file $EXFILE&#10;```&#10;$EXFILE is a .po file with `msgid`s that are not to be extracted (and thus excluded).&#10;Robbins, Arnold. _UNIX in a Nutshell_ 4th ed (2005): 235'

<code>&nbsp;</code>   [`a`][xgettext -&#97;] <code>&nbsp;</code> [`c`][xgettext -&#99;] [`d`][xgettext -&#100;] <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> [`h`][xgettext -&#104;] <code>&nbsp;</code> [`j`][xgettext -&#106;] <code>&nbsp;</code> <code>&nbsp;</code> [`m`][xgettext -&#109;] [`n`][xgettext -&#110;] <code>&nbsp;</code> [`p`][xgettext -&#112;] <code>&nbsp;</code> <code>&nbsp;</code> [`s`][xgettext -&#115;] <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> [`x`][xgettext -&#120;] <code>&nbsp;</code> <code>&nbsp;</code>  <br><code>&nbsp;</code>&nbsp;<code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> [`M`][xgettext -&#77;] <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> 

## Diagnostic and benchmarking
[`ausearch`][ausearch] 
[`bpftrace`][bpftrace] 
[`date`][date] 
[`df`][df] 
[`du`][du] 
[`free`][free] 
[`glances`][glances] 
[`hwclock`][hwclock] 
[`ldd`][ldd] 
[`loadaverage`][loadaverage] 
[`logger`][logger] 
[`logrotate`][logrotate] 
[`lsb_release`][lsb_release]
[`man`][man] 
[`mpstat`][mpstat] 
[`nproc`][nproc] 
[`ntpdate`][ntpdate] 
[`printenv`][printenv] 
[`rsyslogd`][rsyslogd] 
[`sar`][sar] 
[`sysbench`][sysbench] 
[`syslogd`][syslogd] 
[`time`][time] 
[`timedatectl`][timedatectl] 
[`tty`][tty] 
[`uname`][uname] 
[`uptime`][uptime] 
[`vmstat`][vmstat] 

#### `ausearch`
Display audit logs from {startdate} to {enddate}
```sh
ausearch --start startdate--end enddate
```
Search audit logs for today for logins of UID 500
```sh
ausearch --start today --loginuid500
```
#### `date`
[date -&#100;]:                 #date                          '```&#10;$ date -d $DATE&#10;$ date --date $DATE&#10;```&#10;Display `$DATE`, which should be quoted&#10;Robbins, Arnold. _UNIX in a Nutshell_ 4th ed (2005): 53'
[date -&#102;]:                 #date                          '```&#10;$ date -f $DATEFILE&#10;$ date --file $DATEFILE&#10;```&#10;Like `-d`, but printed once for each line of `$DATEFILE`&#10;Robbins, Arnold. _UNIX in a Nutshell_ 4th ed (2005): 53'
[date -&#73;]:                  #date                          '```&#10;$ date -I&#10;$ date --iso-8601&#10;```&#10;Display in ISO-8601 format&#10;Robbins, Arnold. _UNIX in a Nutshell_ 4th ed (2005): 53'
[date -&#114;]:                 #date                          '```&#10;$ date -r $FILE&#10;$ date --reference $FILE&#10;```&#10;Display the time `$FILE` was last modified.&#10;Robbins, Arnold. _UNIX in a Nutshell_ 4th ed (2005): 53'
[date -&#82;]:                  #date                          '```&#10;$ date -R&#10;$ date --rfc-822&#10;```&#10;Display the date in RFC 822 format&#10;Robbins, Arnold. _UNIX in a Nutshell_ 4th ed (2005): 53'
[date -&#115;]:                 #date                          '```&#10;$ date -s $DATE&#10;$ date --set $DATE&#10;```&#10;Set date to `$DATE`&#10;Robbins, Arnold. _UNIX in a Nutshell_ 4th ed (2005): 53'
[date -&#117;]:                 #date                          '```&#10;$ date -u&#10;$ date --utc&#10;```&#10;Print or set UTC time'


[date +%&#97;]:                 #date                          '```&#10;$ date +%a&#10;```&#10;Abbreviated weekday&#10;Robbins, Arnold. _UNIX in a Nutshell_ 4th ed (2005): 52'
[date +%&#65;]:                 #date                          '```&#10;$ date +%A&#10;```&#10;Full weekday&#10;Robbins, Arnold. _UNIX in a Nutshell_ 4th ed (2005): 52'
[date +%&#98;]:                 #date                          '```&#10;$ date +%b&#10;```&#10;Abbreviated month name&#10;Robbins, Arnold. _UNIX in a Nutshell_ 4th ed (2005): 52'
[date +%&#66;]:                 #date                          '```&#10;$ date +%B&#10;```&#10;Full month name&#10;Robbins, Arnold. _UNIX in a Nutshell_ 4th ed (2005): 52'
[date +%&#99;]:                 #date                          '```&#10;$ date +%c&#10;```&#10;Country-specific date and time format (default is `%a %b %e %T %Z %Y`)&#10;Robbins, Arnold. _UNIX in a Nutshell_ 4th ed (2005): 52'
[date +%&#68;]:                 #date                          '```&#10;$ date +%D&#10;```&#10;Date in `%m/%d/%y` format&#10;Robbins, Arnold. _UNIX in a Nutshell_ 4th ed (2005): 52'
[date +%&#100;]:                #date                          '```&#10;$ date +%d&#10;```&#10;Day of month (01-31)&#10;Robbins, Arnold. _UNIX in a Nutshell_ 4th ed (2005): 51'
[date +%&#101;]:                #date                          '```&#10;$ date +%e&#10;```&#10;Day of month (1-31); pad single digits with a space.&#10;Robbins, Arnold. _UNIX in a Nutshell_ 4th ed (2005): 52'
[date +%&#70;]:                 #date                          '```&#10;$ date +%F&#10;```&#10;ISO 8601 date format (`%Y-%m-%d`)&#10;Robbins, Arnold. _UNIX in a Nutshell_ 4th ed (2005): 52'
[date +%&#103;]:                #date                          '```&#10;$ date +%g&#10;```&#10;Week-based year within century (00-99)&#10;Robbins, Arnold. _UNIX in a Nutshell_ 4th ed (2005): 52'
[date +%&#71;]:                 #date                          '```&#10;$ date +%G&#10;```&#10;Week-based year, including the century (0000-9999)&#10;Robbins, Arnold. _UNIX in a Nutshell_ 4th ed (2005): 52'
[date +%&#72;]:                 #date                          '```&#10;$ date +%H&#10;```&#10;Hour in 24-hour format (00-23)&#10;Robbins, Arnold. _UNIX in a Nutshell_ 4th ed (2005): 52'
[date +%&#104;]:                #date                          '```&#10;$ date +%h&#10;```&#10;Same as `%b`&#10;Robbins, Arnold. _UNIX in a Nutshell_ 4th ed (2005): 52'
[date +%&#73;]:                 #date                          '```&#10;$ date +%I&#10;```&#10;Hour in 12-hour format (01-12)&#10;Robbins, Arnold. _UNIX in a Nutshell_ 4th ed (2005): 52'
[date +%&#106;]:                #date                          '```&#10;$ date +%j&#10;```&#10;Julian day of year (001-366)&#10;Robbins, Arnold. _UNIX in a Nutshell_ 4th ed (2005): 52'
[date +%&#107;]:                #date                          '```&#10;$ date +%k&#10;```&#10;Hour in 24-hour format (0-23); single digits are preceded by a space&#10;Robbins, Arnold. _UNIX in a Nutshell_ 4th ed (2005): 52'
[date +%&#108;]:                #date                          '```&#10;$ date +%l&#10;```&#10;Hour in 12-hour format (1-12); single digits are preceded by a space&#10;Robbins, Arnold. _UNIX in a Nutshell_ 4th ed (2005): 52'
[date +%&#77;]:                 #date                          '```&#10;$ date +%M&#10;```&#10;Minute (00-59)&#10;Robbins, Arnold. _UNIX in a Nutshell_ 4th ed (2005): 52'
[date +%&#109;]:                #date                          '```&#10;$ date +%m&#10;```&#10;Month of year (01-12)&#10;Robbins, Arnold. _UNIX in a Nutshell_ 4th ed (2005): 51'
[date +%&#110;]:                #date                          '```&#10;$ date +%n&#10;```&#10;insert a newline&#10;Robbins, Arnold. _UNIX in a Nutshell_ 4th ed (2005): 51'
[date +%&#78;]:                 #date                          '```&#10;$ date +%N&#10;```&#10;Number of nanoseconds within the current second&#10;Robbins, Arnold. _UNIX in a Nutshell_ 4th ed (2005): 52'
[date +%&#112;]:                #date                          '```&#10;$ date +%p&#10;```&#10;String to indicate AM or PM&#10;Robbins, Arnold. _UNIX in a Nutshell_ 4th ed (2005): 52'
[date +%&#82;]:                 #date                          '```&#10;$ date +%R&#10;```&#10;Time in `%H:%M` format&#10;Robbins, Arnold. _UNIX in a Nutshell_ 4th ed (2005): 52'
[date +%&#114;]:                #date                          '```&#10;$ date +%r&#10;```&#10;Time in `%I:%M:%SS %p` format&#10;Robbins, Arnold. _UNIX in a Nutshell_ 4th ed (2005): 52'
[date +%&#115;]:                #date                          '```&#10;$ date +%s&#10;```&#10;Date and seconds since the Epoch&#10;Robbins, Arnold. _UNIX in a Nutshell_ 4th ed (2005): 52'
[date +%&#83;]:                 #date                          '```&#10;$ date +%S&#10;```&#10;Second (00-61); 61 permits leap seconds and double leap seconds.&#10;Robbins, Arnold. _UNIX in a Nutshell_ 4th ed (2005): 52'
[date +%&#116;]:                #date                          '```&#10;$ date +%t&#10;```&#10;insert a tab&#10;Robbins, Arnold. _UNIX in a Nutshell_ 4th ed (2005): 51'
[date +%&#84;]:                 #date                          '```&#10;$ date +%T&#10;```&#10;Time in `%H:%M:%S` format&#10;Robbins, Arnold. _UNIX in a Nutshell_ 4th ed (2005): 52'
[date +%&#85;]:                 #date                          '```&#10;$ date +%U&#10;```&#10;Week number in year (00-53); start week on Sunday&#10;Robbins, Arnold. _UNIX in a Nutshell_ 4th ed (2005): 52'
[date +%&#117;]:                #date                          '```&#10;$ date +%u&#10;```&#10;Weekday as a decimal number (1-7, Sunday = 1)&#10;Robbins, Arnold. _UNIX in a Nutshell_ 4th ed (2005): 52'
[date +%&#86;]:                 #date                          '```&#10;$ date +%V&#10;```&#10;ISO-8601 week number (01-53)&#10;Robbins, Arnold. _UNIX in a Nutshell_ 4th ed (2005): 52'
[date +%&#119;]:                #date                          '```&#10;$ date +%w&#10;```&#10;Day of week (Sunday = 0)&#10;Robbins, Arnold. _UNIX in a Nutshell_ 4th ed (2005): 52'
[date +%&#87;]:                 #date                          '```&#10;$ date +%W&#10;```&#10;Week number in year (00-53); start week on Sunday&#10;Robbins, Arnold. _UNIX in a Nutshell_ 4th ed (2005): 52'
[date +%&#120;]:                #date                          '```&#10;$ date +%x&#10;```&#10;Country-specific date format&#10;Robbins, Arnold. _UNIX in a Nutshell_ 4th ed (2005): 52'
[date +%&#88;]:                 #date                          '```&#10;$ date +%X&#10;```&#10;Country-specific time format&#10;Robbins, Arnold. _UNIX in a Nutshell_ 4th ed (2005): 52'
[date +%&#89;]:                 #date                          '```&#10;$ date +%Y&#10;```&#10;Four-digit year (e.g. 1996)&#10;Robbins, Arnold. _UNIX in a Nutshell_ 4th ed (2005): 52'
[date +%&#121;]:                #date                          '```&#10;$ date +%y&#10;```&#10;Last two digits of year (00-99)&#10;Robbins, Arnold. _UNIX in a Nutshell_ 4th ed (2005): 52'
[date +%&#90;]:                 #date                          '```&#10;$ date +%Z&#10;```&#10;Time-zone name&#10;Robbins, Arnold. _UNIX in a Nutshell_ 4th ed (2005): 52'

<code>&nbsp;</code>   <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> [`d`][date -&#100;] <code>&nbsp;</code> [`f`][date -&#102;] <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> [`r`][date -&#114;] [`s`][date -&#115;] <code>&nbsp;</code> [`u`][date -&#117;] <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code>  <br><code>&nbsp;</code>&nbsp;<code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> [`I`][date -&#73;] <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> [`R`][date -&#82;] <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> 

Metacharacters

<code>&nbsp;</code>   [`a`][date +%&#97;] [`b`][date +%&#98;] [`c`][date +%&#99;] [`d`][date +%&#100;] [`e`][date +%&#101;] <code>&nbsp;</code> [`g`][date +%&#103;] [`h`][date +%&#104;] <code>&nbsp;</code> [`j`][date +%&#106;] [`k`][date +%&#107;] [`l`][date +%&#108;] [`m`][date +%&#109;] [`n`][date +%&#110;] <code>&nbsp;</code> [`p`][date +%&#112;] <code>&nbsp;</code> [`r`][date +%&#114;] [`s`][date +%&#115;] [`t`][date +%&#116;] [`u`][date +%&#117;] <code>&nbsp;</code> [`w`][date +%&#119;] [`x`][date +%&#120;] [`y`][date +%&#121;] <code>&nbsp;</code>  <br><code>&nbsp;</code>&nbsp;[`A`][date +%&#65;] [`B`][date +%&#66;] <code>&nbsp;</code> [`D`][date +%&#68;] <code>&nbsp;</code> [`F`][date +%&#70;] [`G`][date +%&#71;] [`H`][date +%&#72;] [`I`][date +%&#73;] <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> [`M`][date +%&#77;] [`N`][date +%&#78;] <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> [`R`][date +%&#82;] [`S`][date +%&#83;] [`T`][date +%&#84;] [`U`][date +%&#85;] [`V`][date +%&#86;] [`W`][date +%&#87;] [`X`][date +%&#88;] [`Y`][date +%&#89;] [`Z`][date +%&#90;] 


Set only the year using `"next year"` or `"last year"`
```sh
date -s "next year"
date -s "last year"
```
Set only the day
```sh
date -s "next day"
date -s "monday"
```
Display the date fifty days into the future [devconnected.com][https://devconnected.com/user-administration-complete-guide-on-linux/#Setting_an_account_expiration_date_easily]
```sh
date -d '+50days' +%F
```
#### `df`
<!-- `df` options -->
[df -&#97;]:                    #df                            '```&#10;$ df -&#97;&#10;$ df --all&#10;```&#10;Provide information about all filesystems, even ones marked in /etc/mnttab to be ignored&#10;Robbins, Arnold. _UNIX in a Nutshell_ 4th ed (2005): 57'
[df -&#66;]:                    #df                            '```&#10;$ df -&#66; $N&#10;$ df --block-size $N&#10;```&#10;Show space as `$N`-byte blocks. Historically, the default has been 512 B, but Linux uses 1,024 B.&#10;Robbins, Arnold. _UNIX in a Nutshell_ 4th ed (2005): 58'
[df -&#104;]:                   #df                            '```&#10;$ df -&#104;&#10;$ df --human-readable&#10;```&#10;Human-readable output&#10;Robbins, Arnold. _UNIX in a Nutshell_ 4th ed (2005): 57'
[df -&#72;]:                    #df                            '```&#10;$ df -&#72;&#10;$ df --si&#10;```&#10;Like `-h`, but use base 10 for sizes, not base 2.&#10;Robbins, Arnold. _UNIX in a Nutshell_ 4th ed (2005): 57'
[df -&#105;]:                   #df                            '```&#10;$ df -&#105;&#10;$ df --inodes&#10;```&#10;Show number of used and available inodes in a format similar to `df -k`&#10;Robbins, Arnold. _UNIX in a Nutshell_ 4th ed (2005): 57'
[df -&#107;]:                   #df                            '```&#10;$ df -&#107;&#10;$ df --kilobytes&#10;```&#10;Print allocation in kilobytes&#10;Robbins, Arnold. _UNIX in a Nutshell_ 4th ed (2005): 57'
[df -&#108;]:                   #df                            '```&#10;$ df -&#108;&#10;$ df --local&#10;```&#10;Report only on local filesystems&#10;Robbins, Arnold. _UNIX in a Nutshell_ 4th ed (2005): 57'
[df -&#109;]:                   #df                            '```&#10;$ df -&#109;&#10;$ df --megabytes&#10;```&#10;Use 1,048,576-byte (1-MB) blocks instead of the default.&#10;Robbins, Arnold. _UNIX in a Nutshell_ 4th ed (2005): 57'
[df -&#111;]:                   #df                            '```&#10;$ df -&#111; $OPTIONS&#10;```&#10;Supply a comma-delimited list of suboptions.&#10;Robbins, Arnold. _UNIX in a Nutshell_ 4th ed (2005): 57'
[df -&#80;]:                    #df                            '```&#10;$ df -&#80;&#10;$ df --portability&#10;```&#10;POSIX-conformant output but using 1024-byte blocks. (Set `POSIXLY_CORRECT` environment variable to force GNU `df` to use 512-byte blocks)&#10;Robbins, Arnold. _UNIX in a Nutshell_ 4th ed (2005): 57'
[df -&#116;]:                   #df                            '```&#10;$ df -&#116; $TYPE&#10;$ df --type $TYPE&#10;```&#10;Show only `$TYPE` filesystems.&#10;Robbins, Arnold. _UNIX in a Nutshell_ 4th ed (2005): 57'
[df -&#84;]:                    #df                            '```&#10;$ df -&#84;&#10;$ df --print-type&#10;```&#10;Print type of each filesystem in addition to the sizes.&#10;Robbins, Arnold. _UNIX in a Nutshell_ 4th ed (2005): 58'
[df -&#120;]:                   #df                            '```&#10;$ df -&#120; $TYPE&#10;$ df --exclude-type $TYPE&#10;```&#10;Show only filesystems that are not of type `$TYPE`&#10;Robbins, Arnold. _UNIX in a Nutshell_ 4th ed (2005): 58'

<code>&nbsp;</code>   [`a`][df -&#97;] <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> [`h`][df -&#104;] [`i`][df -&#105;] <code>&nbsp;</code> [`k`][df -&#107;] [`l`][df -&#108;] [`m`][df -&#109;] <code>&nbsp;</code> [`o`][df -&#111;] <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> [`t`][df -&#116;] <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> [`x`][df -&#120;] <code>&nbsp;</code> <code>&nbsp;</code>  <br><code>&nbsp;</code>&nbsp;<code>&nbsp;</code> [`B`][df -&#66;] <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> [`H`][df -&#72;] <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> [`P`][df -&#80;] <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> [`T`][df -&#84;] <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> 

#### `du`
<!-- `du` options -->
[du -&#48;]:                    #du                            '```&#10;$ du -0&#10;$ du --null&#10;```&#10;End each output line with a binary zero (NUL) character instead of a newline&#10;Robbins, Arnold. _UNIX in a Nutshell_ 4th ed (2005): 68'
[du -&#97;]:                    #du                            '```&#10;$ du -a&#10;$ du --all&#10;```&#10;Print usage for all files, not just subdirectories&#10;Robbins, Arnold. _UNIX in a Nutshell_ 4th ed (2005): 67'
[du -&#98;]:                    #du                            '```&#10;$ du -b&#10;$ du --bytes&#10;```&#10;Print sizes in bytes&#10;Robbins, Arnold. _UNIX in a Nutshell_ 4th ed (2005): 67'
[du -&#66;]:                    #du                            '```&#10;$ du -B $SIZE&#10;$ du --block-size $SIZE&#10;```&#10;Use a block size of `$SIZE` bytes&#10;Robbins, Arnold. _UNIX in a Nutshell_ 4th ed (2005): 67'
[du -&#99;]:                    #du                            '```&#10;$ du -c&#10;$ du --total&#10;```&#10;In addition to normal output, print grand total of all arguments&#10;Robbins, Arnold. _UNIX in a Nutshell_ 4th ed (2005): 68&#10;--------------------------&#10;Produce a grand total for all listed items&#10;Haeder, Adam. _LPI Linux Certification in a Nutshell_. 2010.: 153'
[du -&#68;]:                    #du                            '```&#10;$ du -D&#10;$ du --dereference-args&#10;```&#10;Follow symbolic links, but only if they are command-line arguments&#10;Robbins, Arnold. _UNIX in a Nutshell_ 4th ed (2005): 68'
[du -&#104;]:                   #du                            '```&#10;$ du -h&#10;$ du --human-readable&#10;```&#10;Print sizes in human-readable format&#10;Robbins, Arnold. _UNIX in a Nutshell_ 4th ed (2005): 67&#10;-------------------------&#10;Display results in human-readable format&#10;Haeder, Adam. _LPI Linux Certification in a Nutshell_. 2010.: 153'
[du -&#107;]:                   #du                            '```&#10;$ du -k&#10;$ du --kilobytes&#10;```&#10;Print information in units of kilobytes&#10;Robbins, Arnold. _UNIX in a Nutshell_ 4th ed (2005): 67'
[du -&#76;]:                    #du                            '```&#10;$ du -L&#10;$ du --dereference&#10;```&#10;For symbolic links, process the file or directory to which the link refers, not the link itself&#10;Robbins, Arnold. _UNIX in a Nutshell_ 4th ed (2005): 67'
[du -&#108;]:                   #du                            '```&#10;$ du -l&#10;$ du --count-links&#10;```&#10;Count the size of all files, whether or not they have already appeared&#10;Robbins, Arnold. _UNIX in a Nutshell_ 4th ed (2005): 68'
[du -&#109;]:                   #du                            '```&#10;$ du -m&#10;$ du --megabytes&#10;```&#10;Print sizes in megabytes&#10;Robbins, Arnold. _UNIX in a Nutshell_ 4th ed (2005): 68'
[du -&#80;]:                    #du                            '```&#10;$ du -P&#10;$ du --no-dereference&#10;```&#10;Do not follow any symbolic links (default)&#10;Robbins, Arnold. _UNIX in a Nutshell_ 4th ed (2005): 68'
[du -&#115;]:                   #du                            '```&#10;$ du -s&#10;$ du --summarize&#10;```&#10;Print only the grand total for each named directory&#10;Robbins, Arnold. _UNIX in a Nutshell_ 4th ed (2005): 67&#10;-----------------------------&#10;Print a summary for each of the `$DIRS` specified, instead of totals for each subdirectory found recursively&#10;Haeder, Adam. _LPI Linux Certification in a Nutshell_. 2010.: 153'
[du -&#83;]:                    #du                            '```&#10;$ du -S&#10;$ du --separate-dirs&#10;```&#10;Do not include the sizes of subdirectories when totaling the size of parent directories&#10;Robbins, Arnold. _UNIX in a Nutshell_ 4th ed (2005): 68&#10;--------------------------&#10;Exclude subdirectories from counts and totals, limiting totals to `$DIRS`&#10;Haeder, Adam. _LPI Linux Certification in a Nutshell_. 2010.: 153'
[du -&#120;]:                   #du                            '```&#10;$ du -x&#10;$ du --one-file-system&#10;```&#10;Restrict file size evaluations to files on the same filesystem as the command-line `$FILE` parameter&#10;Robbins, Arnold. _UNIX in a Nutshell_ 4th ed (2005): 67'
[du -&#88;]:                    #du                            '```&#10;$ du -X $FILE&#10;$ du --exclude-from $FILE&#10;```&#10;Exclude files that match any pattern in `$FILE`&#10;Robbins, Arnold. _UNIX in a Nutshell_ 4th ed (2005): 68'

[`0`][du -&#48;]   [`a`][du -&#97;] [`b`][du -&#98;] [`c`][du -&#99;] <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> [`h`][du -&#104;] <code>&nbsp;</code> <code>&nbsp;</code> [`k`][du -&#107;] [`l`][du -&#108;] [`m`][du -&#109;] <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> [`s`][du -&#115;] <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> [`x`][du -&#120;] <code>&nbsp;</code> <code>&nbsp;</code>  <br><code>&nbsp;</code>&nbsp;<code>&nbsp;</code> [`B`][du -&#66;] <code>&nbsp;</code> [`D`][du -&#68;] <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> [`L`][du -&#76;] <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> [`P`][du -&#80;] <code>&nbsp;</code> <code>&nbsp;</code> [`S`][du -&#83;] <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> [`X`][du -&#88;] <code>&nbsp;</code> <code>&nbsp;</code> 

#### `free`
Display amount of free and used memory in the system [<sup>ref</sup>][L5PMT-memory]
```sh
free -m
```
#### `glances`
Cross-platform monitoring tool, written in Python. [<sup>ref</sup>][L5PMT-glances]

Config                | Description
---                   | ---
/etc/default/glances  | Change value of `RUN` to `"True"` in order to have glances run on startup [<sup>ref</sup>][L5PMT-glances]

#### `hwclock`
Connection to an NTP server is necessary for a variety of services.

Linux systems have two clocks:
1. hardware clock/real-time clock (RTC)
2. system clock

Manually synchronize hardware clock to system clock (generally only required if **no NTP server is available**)
```bash
hwclock --hctosys
```
#### `ioping`
Displays disk latency in the same way that `ping` shows network latency [<sup>ref</sup>][L5PMT-disk]
#### `iotop`
#### `lsb_release`
Display version of Ubuntu
```sh
lsb_release -sc
```
#### `ldd`
Display dependencies of `$PROGRAM`
```sh
ldd $PROGRAM
```
#### `lscpu`
Display CPU architecture information [<sup>ref</sup>][L5PMT-cpu]
#### `mpstat`
Report processor-related statistics (part of "sysstat" package). [<sup>ref</sup>][L5PMT-network]
```sh
mpstat -P all
```
#### `netstat`
```sh
netstat -tulpn
```
#### `nproc`
Display number of CPU processors or cores [<sup>ref</sup>][L5PMT-cpu]
#### `ntpdate`
Synchronize system clock to that of an online Network Time Protocol server
```sh
ntpdate -upool.ntp.org
```
#### `pmap`
Report memory map of a process (part of "sysstat" package). [<sup>ref</sup>][L5PMT-network]
#### `sar`
<!-- `sar` options -->
[sar -&#65;]:                   #sar                           '```&#10;$ sar -&#65;&#10;```&#10;display the most information: equivalent to all options'
[sar -&#98;]:                   #sar                           '```&#10;$ sar -&#98;&#10;```&#10;display input/output statistics'
[sar -&#66;]:                   #sar                           '```&#10;$ sar -&#66;&#10;```&#10;display swap statistics'
[sar -&#100;]:                  #sar                           '```&#10;$ sar -&#100;&#10;```&#10;display input/output statistics for each block device on the system'
[sar -&#102;]:                  #sar                           '```&#10;$ sar -&#102;&#10;```&#10;display information from the specified $FILE (typically within /var/log/sa)'
[sar -&#110;]:                  #sar                           '```&#10;$ sar -&#110; ALL&#10;```&#10;report all network statistics'
[sar -&#111;]:                  #sar                           '```&#10;$ sar -&#111;&#10;```&#10;save output to $FILE in binary'
[sar -&#80;]:                   #sar                           '```&#10;$ sar -&#80;&#10;```&#10;specify statistics for a single CPU (0-indexed)'
[sar -&#113;]:                  #sar                           '```&#10;$ sar -&#113;&#10;```&#10;display statistics for the processor queue'
[sar -&#114;]:                  #sar                           '```&#10;$ sar -&#114;&#10;```&#10;display memory and swap statistics'
[sar -&#82;]:                   #sar                           '```&#10;$ sar -&#82;&#10;```&#10;display memory statistics'
[sar -&#117;]:                  #sar                           '```&#10;$ sar -&#117;&#10;```&#10;display CPU statistics (default when no options are specified)'
[sar -&#118;]:                  #sar                           '```&#10;$ sar -&#118;&#10;```&#10;display kernel-related statistics'
[sar -&#87;]:                   #sar                           '```&#10;$ sar -&#87;&#10;```&#10;display swapping statistics'

<code>&nbsp;</code>   <code>&nbsp;</code> [`b`][sar -&#98;] <code>&nbsp;</code> [`d`][sar -&#100;] <code>&nbsp;</code> [`f`][sar -&#102;] <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> [`n`][sar -&#110;] [`o`][sar -&#111;] <code>&nbsp;</code> [`q`][sar -&#113;] [`r`][sar -&#114;] <code>&nbsp;</code> <code>&nbsp;</code> [`u`][sar -&#117;] [`v`][sar -&#118;] <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code>  <br><code>&nbsp;</code>&nbsp;[`A`][sar -&#65;] [`B`][sar -&#66;] <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> [`P`][sar -&#80;] <code>&nbsp;</code> [`R`][sar -&#82;] <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> [`W`][sar -&#87;] <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> 

#### `sosreport`
**SOS** is an open-source data collection tool that can be used to collect system configuration details and diagnostic information from a Unix-like operating system. It is installed by default on Ubuntu Server. <sup>[howtoforge.com](https://www.howtoforge.com/how-to-install-and-use-sosreport-on-ubuntu-1804/ "howtoforge.com: \"How to install and use sosreport on Ubuntu\"")</sup>

Collect system configuration details (without arguments, the report will be generated and stored in `$TMPDIR`)
```sh
sosreport
```
Specify alternative temporary directory
```sh
sosreport --tmp-dir /opt
```
Specify alternative compression (`xz` by default)
```sh
sosreport --compression-type gzip
```
Generate report for only specific plugins
```sh
sosreport -o apache --batch
```
#### `sysbench`
Benchmark CPU by calculating prime numbers <sup>[YouTube](https://youtu.be/KkMWXVx-Ul8 "How to Benchmark your Linux system, Hak5 1502.1")</sup>
```sh
sysbench --test=cpu --cpu-max-prime=20000 run
```
File I/O benchmarking <sup>[YouTube](https://youtu.be/KkMWXVx-Ul8 "How to Benchmark your Linux system, Hak5 1502.1")</sup>
```sh
sysbench --test=fileio --file-total-size=10G --file-test-mode=rndrw --init-rng=on --max-time=300 --max-requests=0 run
```
#### `syslog`
System logging facility used for messages from the kernel
#### `uname`
<!-- `uname` options -->
[uname -&#97;]:                 #uname                         '```&#10;$ uname -a&#10;$ uname --all&#10;```&#10;Report the information supplied by all the other options&#10;Robbins, Arnold. _UNIX in a Nutshell_ 4th ed (2005): 221'
[uname -&#109;]:                #uname                         '```&#10;$ uname -m&#10;$ uname --machine&#10;```&#10;Hardware name&#10;Robbins, Arnold. _UNIX in a Nutshell_ 4th ed (2005): 221'
[uname -&#110;]:                #uname                         '```&#10;$ uname -n&#10;$ uname --nodename&#10;```&#10;Node name&#10;Robbins, Arnold. _UNIX in a Nutshell_ 4th ed (2005): 221'
[uname -&#112;]:                #uname                         '```&#10;$ uname -p&#10;$ uname --processor&#10;```&#10;Host processor type&#10;Robbins, Arnold. _UNIX in a Nutshell_ 4th ed (2005): 221'
[uname -&#114;]:                #uname                         '```&#10;$ uname -r&#10;$ uname --kernel-release&#10;```&#10;Operating system release&#10;Robbins, Arnold. _UNIX in a Nutshell_ 4th ed (2005): 221'
[uname -&#115;]:                #uname                         '```&#10;$ uname -s&#10;$ uname --kernel-name&#10;```&#10;System name (default when no options provided)&#10;Robbins, Arnold. _UNIX in a Nutshell_ 4th ed (2005): 221'
[uname -&#118;]:                #uname                         '```&#10;$ uname -v&#10;$ uname --kernel-version&#10;```&#10;Operating system version&#10;Robbins, Arnold. _UNIX in a Nutshell_ 4th ed (2005): 221'
[uname -&#105;]:                #uname                         '```&#10;$ uname -i&#10;$ uname --hardware-platform&#10;```&#10;Hardware platform name&#10;Robbins, Arnold. _UNIX in a Nutshell_ 4th ed (2005): 221'
[uname -&#111;]:                #uname                         '```&#10;$ uname -o&#10;$ uname --operating-system&#10;```&#10;Operating system name&#10;Robbins, Arnold. _UNIX in a Nutshell_ 4th ed (2005): 221'

<code>&nbsp;</code> [`a`][uname -&#97;] <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> [`i`][uname -&#105;] <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> [`m`][uname -&#109;] [`n`][uname -&#110;] [`o`][uname -&#111;] [`p`][uname -&#112;] <code>&nbsp;</code> [`r`][uname -&#114;] [`s`][uname -&#115;] <code>&nbsp;</code> <code>&nbsp;</code> [`v`][uname -&#118;] <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> 

#### `uptime`
[<sup>ref</sup>][L5PMT-cpu]
### `vmstat`

Output header | Description [<sup>ref</sup>][Eckert]
---           | ---
`r`           | number of processes waiting to be run
`b`           | number of sleeping processes
`swpd`        | amount of swap memory used (KB)
`free`        | free physical memory (KB)
`buff`        | memory used by buffers (KB)
`cache`       | memory used as cache
`si`          | memory swapped in to the disk (KB/s)
`so`          | memory swapped out to the disk (KB/s)
`bi`          | blocks per second sent to block devices
`bo`          | blocks per second received from block devices
`in`          | number of interrupts sent to the CPU per second
`cs`          | number of context changes sent to the CPU per second
`us`          | CPU user time
`sy`          | CPU system time
`id`          | CPU idle time
`wa`          | time spent waiting for I/O
`st`          | time stolen from a virtual machine

## Disk
[`blkid`][blkid] 
[`cryptsetup`][cryptsetup] 
[`dd`][dd] 
[`df`][df] 
[`dm-crypt`][dm-crypt] 
[`dumpe2fs`][dumpe2fs] 
[`e2fsck`][e2fsck] 
[`e2label`][e2label] 
[`eject`][eject] 
[`fdformat`][fdformat] 
[`fdisk`][fdisk] 
[`fsck`][fsck] 
[`fstrim`][fstrim] 
[`gdisk`][gdisk] 
[`hdiutil`][hdiutil] 
[`hdparm`][hdparm] 
[`ioping`][ioping] 
[`iostat`][iostat] 
[`iscsiadm`][iscsiadm] 
[`lsblk`][lsblk] 
[`mdadm`][mdadm] 
[`mke2fs`][mke2fs] 
[`mkfs`][mkfs] 
[`mkntfs`][mkntfs]
[`mkswap`][mkswap] 
[`mount`][mount] 
[`mt`][mt] 
[`parted`][parted] 
[`partprobe`][partprobe] 
[`partx`][partx] 
[`resize2fs`][resize2fs] 
[`resize4fs`][resize4fs] 
[`sfdisk`][sfdisk] 
[`swapoff`][swapoff] 
[`swapon`][swapon] 
[`tune2fs`][tune2fs] 
[`umount`][umount] 
[`vifs`][vifs] 
[`xfs_info`][xfs_info] 
[`xfs_metadump`][xfs_metadump] 

**Logical volume management**
[`lvcreate`][lvcreate] 
[`lvdisplay`][lvdisplay] 
[`lvextend`][lvextend] 
[`lvremove`][lvremove] 
[`lvs`][lvs] 
[`lvscan`][lvscan] 
[`pvcreate`][pvcreate] 
[`pvdisplay`][pvdisplay] 
[`pvremove`][pvremove] 
[`pvs`][pvs] 
[`pvscan`][pvscan] 
[`vgcreate`][vgcreate] 
[`vgdisplay`][vgdisplay] 
[`vgextend`][vgextend] 
[`vgreduce`][vgreduce] 
[`vgremove`][vgremove] 
[`vgs`][vgs] 
[`vgscan`][vgscan] 


#### `cryptsetup`
Incorporate full-disk encryption on /dev/sdb1, asking for passphrase twice
```sh
cryptsetup --verify-passphrase luksFormat /dev/sdb1
```
Assign virtual name "storage1" to encrypted disk /dev/sdb1
```sh
cryptsetup luksOpen /dev/sdb1 storage1
```
#### `dd`
Implement a simple CPU benchmark by writing 1 GB of zeroes and piping it to md5sum
```sh
dd if=/dev/zero bs=1M count=1024 | md5sum
```
#### `fdisk`
[fdisk -&#98;]: #fdisk '```&#10;$ fdisk -b&#10;$ fdisk --sector-size&#10;```&#10;Specify the sector size of the disk'
[fdisk -&#66;]: #fdisk '```&#10;$ fdisk -B&#10;$ fdisk --protect-boot&#10;```&#10;Do not erase the beginning of the first disk sector when creating a new disk label.'
[fdisk -&#99;]: #fdisk '```&#10;$ fdisk -c&#10;$ fdisk --compatibility&#10;```&#10;Specify the compatibility mode, "dos" or "nondos" ("nondos" by default)'
[fdisk -&#104;]: #fdisk '```&#10;$ fdisk -h&#10;$ fdisk --help&#10;```&#10;Display help'
[fdisk -&#76;]: #fdisk '```&#10;$ fdisk -L $WHEN&#10;$ fdisk --color $WHEN&#10;```&#10;Colorize output.'
[fdisk -&#108;]: #fdisk '```&#10;$ fdisk -l&#10;$ fdisk --list&#10;```&#10;List the partition tables for the specified devices and then exit.'
[fdisk -&#111;]: #fdisk '```&#10;$ fdisk -o&#10;$ fdisk --output&#10;```&#10;Specify the output columns to print.'
[fdisk -&#115;]: #fdisk '```&#10;$ fdisk -s&#10;$ fdisk --getsz&#10;```&#10;Print the size in 512-byte sectors of each given block device (deprecated in favor of `blockdev`)'
[fdisk -&#116;]: #fdisk '```&#10;$ fdisk -t&#10;$ fdisk --type&#10;```&#10;Enable support only for disklabels of the specified type, and disable support for all other types.'
[fdisk -&#117;]: #fdisk '```&#10;$ fdisk -u $UNIT&#10;$ fdisk --units $UNIT&#10;```&#10;When listing partition tables, show sizes in "sectors" or in "cylinders" ("sectors" by default).'
[fdisk -&#67;]: #fdisk '```&#10;$ fdisk -C $N&#10;$ fdisk --cylinders $N&#10;```&#10;Specify the number of cylinders of the disk'
[fdisk -&#72;]: #fdisk '```&#10;$ fdisk -H $N&#10;$ fdisk --heads $N&#10;```&#10;Specify the number of heads of the disk'
[fdisk -&#83;]: #fdisk '```&#10;$ fdisk -S $N&#10;$ fdisk --sectors $N&#10;```&#10;Specify the number of sectors per track of the disk.'
[fdisk -&#119;]: #fdisk '```&#10;$ fdisk -w $WHEN&#10;$ fdisk --wipe $WHEN&#10;```&#10;Wipe filesystem, RAID, and partition-table signatures from the device, in order to avoid possible collisions.'
[fdisk -&#87;]: #fdisk '```&#10;$ fdisk -W $WHEN&#10;$ fdisk --wipe-partition $WHEN&#10;```&#10;Wipe filesystem, RAID, and partition-table signatures from a newly created partitions, in order to avoid possible collisions.'
[fdisk -&#86;]: #fdisk '```&#10;$ fdisk -V&#10;$ fdisk --version&#10;```&#10;Display version information and exit.'

[fdisk &#97;]: #fdisk '```&#10;$ fdisk&#10;Command (m for help): a&#10;```&#10;Toggle a bootable flag'
[fdisk &#98;]: #fdisk '```&#10;$ fdisk&#10;Command (m for help): b&#10;```&#10;Edit nested BSD disklabel'
[fdisk &#99;]: #fdisk '```&#10;$ fdisk&#10;Command (m for help): c&#10;```&#10;Toggle the DOS compatibility flag'
[fdisk &#100;]: #fdisk '```&#10;$ fdisk&#10;Command (m for help): d&#10;```&#10;Delete a partition'
[fdisk &#70;]: #fdisk '```&#10;$ fdisk&#10;Command (m for help): F&#10;```&#10;List free unpartitioned space'
[fdisk &#108;]: #fdisk '```&#10;$ fdisk&#10;Command (m for help): l&#10;```&#10;List known partition types'
[fdisk &#110;]: #fdisk '```&#10;$ fdisk&#10;Command (m for help): n&#10;```&#10;Add a new partition'
[fdisk &#112;]: #fdisk '```&#10;$ fdisk&#10;Command (m for help): p&#10;```&#10;Print the partition table'
[fdisk &#116;]: #fdisk '```&#10;$ fdisk&#10;Command (m for help): t&#10;```&#10;Change a partition type'
[fdisk &#118;]: #fdisk '```&#10;$ fdisk&#10;Command (m for help): v&#10;```&#10;Verify the partition table'
[fdisk &#105;]: #fdisk '```&#10;$ fdisk&#10;Command (m for help): i&#10;```&#10;Print information about a partition'
[fdisk &#109;]: #fdisk '```&#10;$ fdisk&#10;Command (m for help): m&#10;```&#10;Print the help menu'
[fdisk &#117;]: #fdisk '```&#10;$ fdisk&#10;Command (m for help): u&#10;```&#10;Change display/entry units'
[fdisk &#120;]: #fdisk '```&#10;$ fdisk&#10;Command (m for help): x&#10;```&#10;Extra functionality (experts only)'
[fdisk &#73;]: #fdisk '```&#10;$ fdisk&#10;Command (m for help): I&#10;```&#10;Load disk layout from `sfdisk` script file'
[fdisk &#79;]: #fdisk '```&#10;$ fdisk&#10;Command (m for help): O&#10;```&#10;Dump disk layout to `sfdisk` script file'
[fdisk &#119;]: #fdisk '```&#10;$ fdisk&#10;Command (m for help): w&#10;```&#10;Write table to disk and exit'
[fdisk &#113;]: #fdisk '```&#10;$ fdisk&#10;Command (m for help): q&#10;```&#10;Quit without saving changes'
[fdisk &#103;]: #fdisk '```&#10;$ fdisk&#10;Command (m for help): g&#10;```&#10;Create a new empty GPT partition table'
[fdisk &#71;]: #fdisk '```&#10;$ fdisk&#10;Command (m for help): G&#10;```&#10;Create a new empty SGI (IRIX) partition table'
[fdisk &#111;]: #fdisk '```&#10;$ fdisk&#10;Command (m for help): o&#10;```&#10;Create a new empty DOS partition table.'
[fdisk &#115;]: #fdisk '```&#10;$ fdisk&#10;Command (m for help): s&#10;```&#10;Create a new empty Sun partition table.'

<code>&nbsp;</code>   <code>&nbsp;</code> [`b`][fdisk -&#98;] [`c`][fdisk -&#99;] <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> [`h`][fdisk -&#104;] <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> [`l`][fdisk -&#108;] <code>&nbsp;</code> <code>&nbsp;</code> [`o`][fdisk -&#111;] <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> [`s`][fdisk -&#115;] [`t`][fdisk -&#116;] [`u`][fdisk -&#117;] <code>&nbsp;</code> [`w`][fdisk -&#119;] <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code>  <br><code>&nbsp;</code>&nbsp;<code>&nbsp;</code> [`B`][fdisk -&#66;] [`C`][fdisk -&#67;] <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> [`H`][fdisk -&#72;] <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> [`L`][fdisk -&#76;] <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> [`S`][fdisk -&#83;] <code>&nbsp;</code> <code>&nbsp;</code> [`V`][fdisk -&#86;] [`W`][fdisk -&#87;] <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> 

###### Commands

<code>&nbsp;</code>   [`a`][fdisk &#97;] [`b`][fdisk &#98;] [`c`][fdisk &#99;] [`d`][fdisk &#100;] <code>&nbsp;</code> <code>&nbsp;</code> [`g`][fdisk &#103;] <code>&nbsp;</code> [`i`][fdisk &#105;] <code>&nbsp;</code> <code>&nbsp;</code> [`l`][fdisk &#108;] [`m`][fdisk &#109;] [`n`][fdisk &#110;] [`o`][fdisk &#111;] [`p`][fdisk &#112;] [`q`][fdisk &#113;] <code>&nbsp;</code> [`s`][fdisk &#115;] [`t`][fdisk &#116;] [`u`][fdisk &#117;] [`v`][fdisk &#118;] [`w`][fdisk &#119;] [`x`][fdisk &#120;] <code>&nbsp;</code> <code>&nbsp;</code>  <br><code>&nbsp;</code>&nbsp;<code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> [`F`][fdisk &#70;] [`G`][fdisk &#71;] <code>&nbsp;</code> [`I`][fdisk &#73;] <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> [`O`][fdisk &#79;] <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> 

#### `iscsiadm`
Discover iSCSI targets
```sh
iscsiadm discovery
```
#### `lvcreate`
Create a 20 gigabyte logical volume named "Marketing" from volume group {vg1}
```sh
lvcreate -L 20G vg1 -n Marketing
```
Create logical volume named `lv1` of size 500G from volume group `vg1`
```sh
lvcreate -L 500G vg1 -n lv1
```
#### `lvresize`
Resize existent logical volume {Marketing} in volume group {vg1} to have an additional 10 gigabytes of space
```sh
lvresize -L +10G /dev/vg1/Marketing
```
#### `mkfs`
Create an ext4 filesystem on {partition}
```sh
mkfs -t ext4 partition
```
Specify {filesystemtype} to be created
```sh
mkfs -T filesystemtype
```
#### `partx`
`partx` is a utility that provides information on drive partitions to the Linux kernel. [[12](sources.md)]
Display partition table of a drive
```bash
partx --show /dev/sda
```
Show details of only one partition of a drive
```bash
partx --show /dev/sda1
```
Specify a range of partitions on a drive
```bash
partx -o START, END --nr 10 /dev/sda
```
Add all partitions on a disk to the system
```bash
partx -a /dev/sda
```
Display length in sectors and human-readable size of a partition
```bash
partx -o SECTORS,SIZE /dev/sda1 /dev/sda
```
Remove the last partition
```bash
partx -d --nr -1:-1 /dev/sda
```
Disable headers
```bash
partx -o START -g --nr 5 /dev/sda
```
#### `sfdisk`
Script-based partition table editor, similar to [`fdisk`](#fdisk) and [`gdisk`](#gdisk), which can be run interactively. It does not interface with GPT format, neither is it designed for large partitions. [<sup>ref</sup>][11]

List partitions on all devices

Display size of {partition} or {device}
This command produces the size of {partition} (i.e. `/dev/sda1`) or even {device} (`/dev/sda`) in blocks
```sh
sfdisk -s partition
sfdisk -s device
```
Apply consistency checks to {partition} or {device}
```sh
sfdisk -V partition
sfdisk --verify device
```
Create a partition
```sh
sfdisk device
```
Save sectors changed
This command will allow recovery using the following command
```sh
sfdisk /dev/hdd -O hdd-partition-sectors.save
```
Recovery
Man page indicates this flag is no longer supported, and recommends use of `dd` instead.
```sh
sfdisk /dev/hdd -I hdd-partition-sectors.save
```
### `swapon`
Instruct system to begin using {partition} as a swap file
```sh
swapon partition
```
### `tune2fs`
Adjust various ...
Run `fsck` on {/dev/sdb1} on every boot
```sh
tune2fs -c 1 /dev/sdb1
```
Run `fsck` on {/dev/sda1} at intervals of 60 mounts or 6 months
```sh
tune2fs -c 60 -i 6m /dev/sda1
```
Enable journaling on ext2 partition {/dev/sdc1}
```sh
tune2fs -j /dev/sdc1
```
Assign label "Sales" to logical volume {/dev/vg1/Sales}
```sh
tune2fs -L Sales /dev/vg1/Sales
```

## File commands
[chattr]:                      #chattr                         '```&#10;$ chattr&#10;```&#10;Change file attributes&#10;Rothwell, William. _CompTIA Linux+ Portable Command Guide_.: 311-312'
[chgrp]:                       #chgrp                          '```&#10;$ chgrp&#10;```&#10;Change the group of one or more files, which can be a group ID number or a group name (located in "/etc/group"). You must own the file or be a privileged user to succeed with the command.&#10;Robbins, Arnold. _UNIX in a Nutshell_ 4th ed (2005): 34'
[chmod]:                       #chmod                          '```&#10;$ chmod&#10;```&#10;Change the access mode of one or more files&#10;Robbins, Arnold. _UNIX in a Nutshell_ 4th ed (2005): 35'
[chown]:                       #chown                          '```&#10;$ chown&#10;```&#10;Change the ownership of one or more files, which can be either a user ID number or a login name (located in "/etc/passwd")&#10;Robbins, Arnold. _UNIX in a Nutshell_ 4th ed (2005): 37'
[cksum]:                       #cksum                          '```&#10;$ cksum&#10;```&#10;Calculate and print a CRC sum for each file. The CRC algorithm is based on the polynomial used for Ethernet packets&#10;Robbins, Arnold. _UNIX in a Nutshell_ 4th ed (2005): 38'
[cp]:                          #cp                             '```&#10;$ cp $FILE $PATH&#10;```&#10;Copy `$FILE` to `$PATH`. If `$PATH` is an existing file, it is overwritten. If the input is a directory use `-r`.&#10;Robbins, Arnold. _UNIX in a Nutshell_ 4th ed (2005): 40'
[curl]:                        #curl                           '```&#10;$ curl&#10;```&#10;Retrieve files from the Internet, most often using FTP or HTTP (cf. `wget`)&#10;Robbins, Arnold. _UNIX in a Nutshell_ 4th ed (2005): 49'
[dd]:                          #dd                             '```&#10;$ dd&#10;```&#10;Perform multiple operations related to backing up data and creating files. One common use is to make a backup of an entire drive.&#10;Rothwell, William. _CompTIA Linux+ Portable Command Guide_.: 269'
[dirname]:                     #dirname                        '```&#10;$ dirname $PATH&#10;```&#10;Strip filename from `$PATH` (cf. `basename`)'
[dos2unix]:                    #dos2unix                       '```&#10;$ dos2unix&#10;```&#10;Convert files using the DOS extended character set to their ISO standard counterparts&#10;Robbins, Arnold. _UNIX in a Nutshell_ 4th ed (2005): 66'
[exif]:                        #exif                           '```&#10;$ exif&#10;```&#10;View image metadata, producing columnar output'
[fallocate]:                   #fallocate                      '```&#10;$ fallocate&#10;```&#10;Allocate and deallocate space to a file'
[file]:                        #file                           '```&#10;$ file&#10;```&#10;View image metadata'
[find]:                        #find                           '```&#10;$ find&#10;```&#10;Search recursively through directory trees for files or directories that match certain characters, either printing the file or directory or performing other operations on matches&#10;Haeder, Adam. _LPI Linux Certification in a Nutshell_. 2010.: 96'
[getfacl]:                     #getfacl                        '```&#10;$ getfacl&#10;```&#10;Display the ACL of a file&#10;Rothwell, William. _CompTIA Linux+ Portable Command Guide_.: 199'
[install]:                     #install                        '```&#10;$ install&#10;```&#10;Copy files while maintaining metadata'
[link]:                        #link                           '```&#10;$ link $FILE $OTHER&#10;```&#10;Create a link between two files, similar to `ln` but with no error checking'
[ln]:                          #ln                             '```&#10;$ ln&#10;```&#10;Create a link&#10;Rothwell, William. _CompTIA Linux+ Portable Command Guide_.: 132'
[locate]:                      #locate                         '```&#10;$ locate&#10;```&#10;Search for files based on a database that is typically created daily.&#10;Rothwell, William. _CompTIA Linux+ Portable Command Guide_.: 138'
[ls]:                          #ls                             '```&#10;$ ls&#10;```&#10;List files in a directory&#10;Rothwell, William. _CompTIA Linux+ Portable Command Guide_.: 131'
[lsattr]:                      #lsattr                         '```&#10;$ lsattr&#10;```&#10;Display the attributes for a file&#10;Rothwell, William. _CompTIA Linux+ Portable Command Guide_.: 311'
[lsof]:                        #lsof                           '```&#10;$ lsof&#10;```&#10;Display open files, open network ports, and network connections&#10;Rothwell, William. _CompTIA Linux+ Portable Command Guide_.: 303'
[md5sum]:                      #md5sum                         '```&#10;$ md5sum&#10;```&#10;Display MD5 checksum value for a file&#10;Rothwell, William. _CompTIA Linux+ Portable Command Guide_.: 275'
[mkdir]:                       #mkdir                          '```&#10;$ mkdir&#10;```&#10;Create one or more directories&#10;Haeder, Adam. _LPI Linux Certification in a Nutshell_. 2010.: 98'
[mktemp]:                      #mktemp                         '```&#10;$ mktemp&#10;```&#10;Create a temporary file or directory safely and print its name. These will not need to be manually cleaned up because they will be placed in the temporary directory /tmp'
[mv]:                          #mv                             '```&#10;$ mv&#10;```&#10;Move or rename files and directories&#10;Haeder, Adam. _LPI Linux Certification in a Nutshell_. 2010.: 98'
[rename]:                      #rename                         '```&#10;$ rename&#10;```&#10;Rename files using regex'
[rm]:                          #rm                             '```&#10;$ rm&#10;```&#10;Delete one or more files from the filesystem&#10;Haeder, Adam. _LPI Linux Certification in a Nutshell_. 2010.: 99'
[rmdir]:                       #rmdir                          '```&#10;$ rmdir&#10;```&#10;Delete empty directories&#10;Rothwell, William. _CompTIA Linux+ Portable Command Guide_.: 132'
[rsync]:                       #rsync                          '```&#10;$ rsync&#10;```&#10;Copy files remotely; used in situations where only updated files are to be transferred in order to preserve bandwidth.&#10;Rothwell, William. _CompTIA Linux+ Portable Command Guide_.: 131'
[scp]:                         #scp                            '```&#10;$ scp&#10;```&#10;Copy files to and from remote systems via `ssh`&#10;Rothwell, William. _CompTIA Linux+ Portable Command Guide_.: 130'
[setfacl]:                     #setfacl                        '```&#10;$ setfacl&#10;```&#10;Create an ACL on a file or directory.&#10;Rothwell, William. _CompTIA Linux+ Portable Command Guide_.: 199'
[setuid]:                      #setuid                         '```&#10;$ setuid&#10;```&#10;"set-user identification": permission bit which, if set on an executable file, will ensure that the file is granted access based on the owner of the file, rather than the use who is running it'
[stat]:                        #stat                           '```&#10;$ stat&#10;```&#10;See inode information of a file&#10;Rothwell, William. _CompTIA Linux+ Portable Command Guide_.: 135'
[touch]:                       #touch                          '```&#10;$ touch&#10;```&#10;Used to create empty files and to update modification and access timestamps of existing files.&#10;Rothwell, William. _CompTIA Linux+ Portable Command Guide_.: 129'
[tree]:                        #tree                           '```&#10;$ tree&#10;```&#10;Display contents of directories in a tree-like format'
[umask]:                       #umask                          '```&#10;$ umask&#10;```&#10;Set default permissions for files and directories&#10;Rothwell, William. _CompTIA Linux+ Portable Command Guide_.: 195'
[unlink]:                      #unlink                         '```&#10;$ unlink&#10;```&#10;Does essentially what `rm` does, but in a subtly different way.&#10;Rothwell, William. _CompTIA Linux+ Portable Command Guide_.: 135'
[updatedb]:                    #updatedb                       '```&#10;$ updatedb&#10;```&#10;Refresh (or create) the `slocate` database at /var/lib/slocate/slocate.db&#10;Haeder, Adam. _LPI Linux Certification in a Nutshell_. 2010.: 202'
[whereis]:                     #whereis                        '```&#10;$ whereis&#10;```&#10;Search for binary executables, source code, and manual pages in standard locations as well as the PATH and `$MANPATH`&#10;Rothwell, William. _CompTIA Linux+ Portable Command Guide_.: 139'
[which]:                       #which                          '```&#10;$ which $CMD&#10;```&#10;Determine the location of `$CMD` and display its full path&#10;Haeder, Adam. _LPI Linux Certification in a Nutshell_. 2010.: 200'

[`chattr`][chattr] 
[`chgrp`][chgrp] 
[`chmod`][chmod] 
[`chown`][chown] 
[`cksum`][cksum] 
[`cp`][cp] 
[`curl`][curl] 
[`dd`][dd] 
[`dirname`][dirname] 
[`dos2unix`][dos2unix] 
[`exif`][exif] 
[`fallocate`][fallocate] 
[`file`][file] 
[`find`][find] 
[`getfacl`][getfacl] 
[`install`][install] 
[`link`][link] 
[`ln`][ln] 
[`locate`][locate] 
[`ls`][ls] 
[`lsattr`][lsattr] 
[`lsof`][lsof] 
[`md5sum`][md5sum] 
[`mkdir`][mkdir] 
[`mktemp`][mktemp] 
[`mv`][mv] 
[`rename`][rename] 
[`rm`][rm] 
[`rmdir`][rmdir] 
[`rsync`][rsync] 
[`scp`][scp] 
[`setfacl`][setfacl] 
[`setuid`][setuid] 
[`stat`][stat] 
[`touch`][touch] 
[`tree`][tree] 
[`umask`][umask] 
[`unlink`][unlink] 
[`updatedb`][updatedb] 
[`whereis`][whereis] 
[`which`][which] 


### `exif`
View image metadata. Unlike alternatives like `file` and ImageMagick's `identify`, `exif` produces columnar output [<sup>ref</sup>][31]
```sh
exif image.png 
```
### `fallocate`
Create a file size of 1 gigabyte
```sh
fallocate -l 1G $FILENAME  # gibibyte
fallocate -l 1GB $FILENAME # gigabyte
```
### `file`
View image metadata <sup>[ostechnix.com](https://www.ostechnix.com/how-to-view-image-metadata-on-linux/ "How to view image metadata")</sup>
```sh
file image.png # => file type, dimensions, color depth
```
### `find`
Search for files in a directory hierarchy
Find all files in {$PATH} that are owned by {user}
```sh
find $PATH -user username
```
Find recently modified files/folders
There are 3 timestamps associated with files in Linux <sup>[2daygeek.com](https://www.2daygeek.com/check-find-recently-modified-files-folders-linux/ "How to find recently modified files/folders in Linux")</sup>
- `atime` "access time": last time file was accessed by a command or application
- `mtime` "modify time": last time file's contents were modified
- `ctime` "change time": last time file's attribute was modified 

Numerical arguments can be specified in 3 ways:
- `+n` greater than {n} days ago
- `-n` less than {n} days ago
- `n` exactly {n} days ago
```sh
find $PATH -type f -mtime +120 -ls # Find only files that were modified more than 120 days ago
find $PATH -type f -mtime -15 -ls # Modified less than 15 days ago
find $PATH -type f -mtime 10 -ls # Modified exactly 10 days ago

# Find files modified over the past day
find $PATH -type f -newermt "1 day ago" -ls
find $PATH -type f -newermt "-24 hours" -ls
find $PATH -type f -newermt "yesterday" -ls

find $PATH -type f -ctime -1 -ls # Find files created today
```
### `install`
Copy files while maintaining various metadata, including timestamp, owner, etc. [[9](sources.md)]

Copy a file while preserving timestamp. The copy will have the `install` default of `755`, but the original's `mtime` is maintained:
```sh
install --preserve-timestamp example/foo .
```
Copy a file, setting permissions, owner, and group
```sh
install --preserve-timestamp --owner=jdoe --group=sudoers --mode=753
```
### `ls`
[ls -&#97;]:                    #ls                            '```&#10;$ ls -a&#10;$ ls --all&#10;```&#10;List all files, including hidden files&#10;Rothwell, William. _CompTIA Linux+ Portable Command Guide_.: 131'
[ls -&#100;]:                   #ls                            '```&#10;$ ls -d&#10;$ ls --directory&#10;```&#10;List directory name, not its contents&#10;Rothwell, William. _CompTIA Linux+ Portable Command Guide_.: 131'
[ls -&#70;]:                    #ls                            '```&#10;$ ls -F&#10;$ ls --classify&#10;```&#10;Append a character to the end of the file to indicate its type. These characters include:&#10;  - `*`: executable file&#10;  - `/`: directory&#10;  - `@`: symbolic link&#10;&#10;Rothwell, William. _CompTIA Linux+ Portable Command Guide_.: 131'
[ls -&#104;]:                   #ls                            '```&#10;$ ls -h&#10;```&#10;Human-readable output&#10;Rothwell, William. _CompTIA Linux+ Portable Command Guide_.: 131'
[ls -&#105;]:                   #ls                            '```&#10;$ ls -i&#10;```&#10;Display inode value of each file&#10;Rothwell, William. _CompTIA Linux+ Portable Command Guide_.: 131'
[ls -&#108;]:                   #ls                            '```&#10;$ ls -l&#10;```&#10;Display a long listing&#10;Rothwell, William. _CompTIA Linux+ Portable Command Guide_.: 131'
[ls -&#114;]:                   #ls                            '```&#10;$ ls -r&#10;```&#10;Reverse the output order of the file listing&#10;Rothwell, William. _CompTIA Linux+ Portable Command Guide_.: 131'
[ls -&#83;]:                    #ls                            '```&#10;$ ls -S&#10;```&#10;sort by file size&#10;Rothwell, William. _CompTIA Linux+ Portable Command Guide_.: 131'
[ls -&#116;]:                   #ls                            '```&#10;$ ls -t&#10;```&#10;sort by modification time (newest first)&#10;Rothwell, William. _CompTIA Linux+ Portable Command Guide_.: 131'
[ls -&#90;]:                    #ls                            '```&#10;$ ls -Z&#10;```&#10;Display SELinux context for files'
[ls -&#65;]:                    #ls                            '```&#10;$ ls -A&#10;$ ls --almost-all&#10;```&#10;Like `-a`, but exclude `.` and `..`&#10;Robbins, Arnold. _UNIX in a Nutshell_ 4th ed (2005): 129'
[ls -&#98;]:                    #ls                            '```&#10;$ ls -b&#10;$ ls --escape&#10;```&#10;Show nonprinting characters in octal&#10;Robbins, Arnold. _UNIX in a Nutshell_ 4th ed (2005): 129'
[ls -&#99;]:                    #ls                            '```&#10;$ ls -c&#10;$ ls --time-ctime&#10;```&#10;List files by inode modification time&#10;Robbins, Arnold. _UNIX in a Nutshell_ 4th ed (2005): 129'
[ls -&#67;]:                    #ls                            '```&#10;$ ls -C&#10;$ ls --format=vertical&#10;```&#10;List files in columns&#10;Robbins, Arnold. _UNIX in a Nutshell_ 4th ed (2005): 129'
[ls -&#102;]:                   #ls                            '```&#10;$ ls -f&#10;```&#10;Interpret each `name` as a directory (files are ignored)&#10;Robbins, Arnold. _UNIX in a Nutshell_ 4th ed (2005): 130'

<code>&nbsp;</code>   [`a`][ls -&#97;] <code>&nbsp;</code> <code>&nbsp;</code> [`d`][ls -&#100;] <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> [`h`][ls -&#104;] [`i`][ls -&#105;] <code>&nbsp;</code> <code>&nbsp;</code> [`l`][ls -&#108;] <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> [`r`][ls -&#114;] <code>&nbsp;</code> [`t`][ls -&#116;] <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code>  <br><code>&nbsp;</code>&nbsp;<code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> [`F`][ls -&#70;] <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> [`S`][ls -&#83;] <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> [`Z`][ls -&#90;] 

### `lsof`
Display open files, open network ports, and network connections [[23](sources.md)]

Option  | Effect
:---    | :---
`-i`    | display network connections
`-n`    | prevent the conversion of IP addresses to hostnames
`-P`    | prevent the conversion of port numbers to port names

Show open network connections
```sh
sudo lsof -Pni
```
### `mkdir`
Quickly create multiple directories using brace expansion
```sh
mkdir -p ~/my-app/{bin,lib,log}
```
Create new directory {dirname} along with all of the parents in its pathname, if they do not exist
```sh
mkdir -p dirname
mkdir --parents dirname
```
### `rename`
`rename` uses regular expressions <sup>[Network World][https://www.networkworld.com/article/3433865/how-to-rename-a-group-of-files-on-linux.html#tk.rss_linux]</sup>

Option  | POSIX option            | Effect
:---    | :---                    | :---
`-n`    | `--nono`                | dry-run: describe the changes the command would make, without actually doing them

Rename multiple files
```sh
# Renaming file.old to file.new
rename 's/old/new/' this.old

# Use globbing to rename all matching files
rename 's/old/new/' *.old
rename 's/report/review/' *

# Change all uppercase letters to lowercase
rename 'y/A-Z/a-z/' *
```
### `rsync`
[rsync -&#116;]: #rsync '```&#10;$ rsync -t&#10;```&#10;Preserve original modification timestamp&#10;Rothwell, William. _CompTIA Linux+ Portable Command Guide_.: 132'
[rsync -&#118;]: #rsync '```&#10;$ rsync -v&#10;$ rsync --verbose&#10;```&#10;Verbose output&#10;Rothwell, William. _CompTIA Linux+ Portable Command Guide_.: 132'
[rsync -&#114;]: #rsync '```&#10;$ rsync -r&#10;```&#10;Recursive (transfer entire directory)&#10;Rothwell, William. _CompTIA Linux+ Portable Command Guide_.: 132'
[rsync -&#108;]: #rsync '```&#10;$ rsync -l&#10;```&#10;Maintain symbolic links&#10;Rothwell, William. _CompTIA Linux+ Portable Command Guide_.: 132'
[rsync -&#112;]: #rsync '```&#10;$ rsync -p&#10;```&#10;Preserve original permissions&#10;Rothwell, William. _CompTIA Linux+ Portable Command Guide_.: 132'
[rsync -&#97;]: #rsync '```&#10;$ rsync -a&#10;$ rsync --archive&#10;```&#10;Copy recursively, preserving group, owner, modification times, and device-files (if super-user) (equivalent to `-rptlgoD`)'
[rsync -&#98;]: #rsync '```&#10;$ rsync -b&#10;```&#10;Create a backup of every file transferred'
[rsync -&#101;]: #rsync '```&#10;$ rsync -e&#10;$ rsync --rsh&#10;```&#10;Specify remote shell to use'
[rsync -&#103;]: #rsync '```&#10;$ rsync -g&#10;$ rsync --group&#10;```&#10;Preserve group'
[rsync -&#111;]: #rsync '```&#10;$ rsync -o&#10;$ rsync --owner&#10;```&#10;Preserve owner'
[rsync --delete]: #rsync '```&#10;$ rsync --delete&#10;```&#10;Remove files and folders that are not in the sender system'
[rsync --exclude]: #rsync '```&#10;$ rsync --exclude&#10;```&#10;Exclude files (accepts globbing)'
[rsync --include]: #rsync '```&#10;$ rsync --include&#10;```&#10;Specify specific files (accepts globbing)'
[rsync --progress]: #rsync '```&#10;$ rsync --progress&#10;```&#10;Display a progress bar'
[rsync --remove-source-files]: #rsync '```&#10;$ rsync --remove-source-files&#10;```&#10;Remove original files after synchronization'
[rsync -&#122;]: #rsync '```&#10;$ rsync -z&#10;$ rsync --compress&#10;```&#10;Compress file data during the transfer'

<code>&nbsp;</code> [`a`][rsync -&#97;] [`b`][rsync -&#98;] <code>&nbsp;</code> <code>&nbsp;</code> [`e`][rsync -&#101;] <code>&nbsp;</code> [`g`][rsync -&#103;] <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> [`l`][rsync -&#108;] <code>&nbsp;</code> <code>&nbsp;</code> [`o`][rsync -&#111;] [`p`][rsync -&#112;] <code>&nbsp;</code> [`r`][rsync -&#114;] <code>&nbsp;</code> [`t`][rsync -&#116;] <code>&nbsp;</code> [`v`][rsync -&#118;] <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> [`z`][rsync -&#122;] 

[https://www.2daygeek.com/linux-rsync-command-local-remote-file-synchronization/]: https://www.2daygeek.com/linux-rsync-command-local-remote-file-synchronization/ "rsync (Remote Sync) command examples and usage"

Copy `$FILE` locally <sup>[2daygeek.com][https://www.2daygeek.com/linux-rsync-command-local-remote-file-synchronization/]</sup>
```sh
rsync -zvr $FILE $PATH
```
Copy `$FILE` to `$PATH` on remote `$HOST`
```sh
rsync $FILE $HOST:$PATH
```
Copy $FILE from $HOST to local $PATH
```sh
rsync $HOST:$FILE $PATH
```
Copy `$DIR` recursively <sup>[2daygeek.com][https://www.2daygeek.com/linux-rsync-command-local-remote-file-synchronization/]</sup>
```sh
rsync -zvr $DIR $PATH
rsync -avz $DIR $PATH
```
Copy to remote systems over SSH <sup>[2daygeek.com][https://www.2daygeek.com/linux-rsync-command-local-remote-file-synchronization/]</sup>
```sh
rsync -zvre ssh $DIR $HOST:$REMOTEPATH
rsync -avze ssh $DIR $HOST:$REMOTEPATH
```
Synchronize only specific file type <sup>[2daygeek.com][https://www.2daygeek.com/linux-rsync-command-local-remote-file-synchronization/]</sup>
```sh
rsync -zvre ssh --include '*.php' --exclude '*' $PATH
```
### `setfacl`
Set file access control list

Option  | POSIX option  | Description
:---    | :---          | :---
`-b`    | `--remove-all` | remove all extended ACL entries, retaining the base ACL entries of the owner, group, and others
`-k`    | `--remove-default` | remove the Default ACL
`-m`    | `--modify` | modify ACL of a directory
`-M`    | `--modify-file` | modify ACL of a file
`-s`    |               | overwrite or **s**et
`-x`    | `--remove` | remove ACL entries from a directory
`-X`    | `--remove-file` | remove ACL entries from a file

Grant user {lisa} right to read {file}
```sh
setfacl -m u:lisa:r file
```
Remove named group {staff} from {file}'s ACL
```sh
setfacl -x g:staff file
```
Modify file access control list for {file} to revoke write access from all groups and all named users
```sh
setfacl -m m::rx file
```
Grant read access to **o**ther users
```sh
setfacl -m o::rwx file4.txt
```
Add user {zach} to list of users of file4.txt
```sh
setfacl -m u:zach:rw file4.txt
```
### `shred`
Write random data to an unmounted disk for {n} passes
```sh
shred --iterations=n
```
### `touch`
<sup>[Network World](https://www.networkworld.com/article/3435279/unix-as-a-second-language-the-touch-command.html#tk.rss_linux "networkworld.com: \"Unix as a Second Language: The touch command\"")</sup>

### `tree`
Display contents of directories in a tree-like format <sup>[tecmint.com]</sup>(https://www.tecmint.com/linux-tree-command-examples/ "tecmint.com: \"Linux tree command usage examples for beginners\"")

Option  | Effect
:---    | :---
`-a`    | all files
`-d`    | display directories only
`-f`    | display full path prefix for each file
`-g`    | display group name or GID for each file
`-p`    | display permissions, similar to `ls -l`
`-u`    | display username or UID
`-L $N` | limit to `$N` maximum depth
`-I $PATTERN` | suppress files matching `$PATTERN`
`-P $PATTERN` | display only files matching `$PATTERN`
`--prune`     | suppress empty directories

## Hardware
### `bluetoothctl`
[bluetoothctl devices]:           hw.md#bluetoothctl             '```&#10;$ bluetoothctl&#10;[bluetooth]# devices&#10;```&#10;List available devices'
[bluetoothctl list]:              hw.md#bluetoothctl             '```&#10;$ bluetoothctl&#10;[bluetooth]# list&#10;```&#10;Display available controllers'
[bluetoothctl pair]:              hw.md#bluetoothctl             '```&#10;$ bluetoothctl&#10;[bluetooth]# pair&#10;```&#10;Pair with `$DEVICE`, which is the MAC address of the pairable device'
[bluetoothctl pairable on]:       hw.md#bluetoothctl             '```&#10;$ bluetoothctl&#10;[bluetooth]# pairable on&#10;```&#10;Prepare controller for pairing'
[bluetoothctl scan on]:           hw.md#bluetoothctl             '```&#10;$ bluetoothctl&#10;[bluetooth]# scan on&#10;```&#10;Receive a list of detected devices'
[bluetoothctl select]:            hw.md#bluetoothctl             '```&#10;$ bluetoothctl&#10;[bluetooth]# select&#10;```&#10;Select controller to pair, if the system has more than one'
[bluetoothctl show]:              hw.md#bluetoothctl             '```&#10;$ bluetoothctl&#10;[bluetooth]# show&#10;```&#10;Display more detailed inormation about available controllers'

[<sup>ref</sup>][http://www.linux-magazine.com/Issues/2017/197/Command-Line-bluetoothctl#article_i1] [<sup>ref</sup>][https://computingforgeeks.com/connect-to-bluetooth-device-from-linux-terminal/]

[`device`][bluetoothctl devices] &bull; [`list`][bluetoothctl list] &bull; [`pair`][bluetoothctl pair] &bull; [`pairable on`][bluetoothctl pairable on] [`scan on`][bluetoothctl scan on] [`select`][bluetoothctl select] [`show`][bluetoothctl show]


## Init systems
**SystemVinit** is a daemon process which was used by most distros until recently. 
Processes started serially and synchronously, wasting system resources; 
for years, a common hack was to run services in the background, simulating a sort of parallel processing.
**Upstart** was developed by Canonical for Ubuntu, but abandoned in 2014. 

**SystemD** was designed by a pair of Red Hat developers in 2010 to be a general purpose system manager.
It was intended to address multiple shortcomings with `sysvinit`.
It offers parallel execution, explicit dependencies between services, an escape from slow shell scripts, and per-daemon resource control and watchdogs.

SystemD introduces the concepts of [**Units**] which are subdivided into various unit types, each of which is associated with a filename extension.
<sup>[YouTube](https://youtu.be/NNgZXNQtil8 "We Need to Talk About Systemd: Boot Time Optimization for the New init daemon - Chris Simmonds, 2net") [Linode](https://www.linode.com/docs/quick-answers/linux-essentials/what-is-systemd/ "What is systemd?")</sup>

[Targets][target] (SystemD)   | Runlevels (System V Init)
---                 | ---
`poweroff.target`   | `0`
`rescue.target`     | `1`
`multi-user.target` | `3`
`graphical.target`  | `5`
`reboot.target`     | `6`
`emergency.target`  | `emergency`

SystemD searches for units from most specific to most general.
- `/usr/lib/systemd/system` default location where unit files are installed by packages
- `/run/systemd/system`: Runtime configuration
- `/etc/systemd/system` takes precedence over unit files located anywhere else

[**SystemD**][SystemD] components include:
- [`hostnamectl`][hostnamectl]
- [`journalctl`][journalctl]
- [`localectl`][localectl]
- [`loginctl`][loginctl]
- [`systemctl`][systemctl]
- [`systemd-delta`][systemd-delta]
- [`timedatectl`][timedatectl]

**Sysvinit**
`chkconfig`
`init`
`runlevel`
`service`
`telinit`

**Upstart**
`initctl`

##### `hostnamectl`
Permanently change hostname to `$HOSTNAME`
```sh
hostnamectl set-hostname $HOSTNAME
```
##### `journalctl`
Show current disk usage of all journal files
```sh
journalctl --disk-usage
```
Continuously update the display as new log entries are created
```sh
journalctl -f
```
Display output in reverse (newest entries first)
```sh
journalctl -r
```
##### `localectl`
Change locale to French
```sh
localectl set-locale LANG=fr_FR.utf8
```
##### `loginctl`
Control the systemd login manager
##### `systemctl`
[systemctl daemon-reload]:                 #systemctl                     '```&#10;$ systemctl daemon-reload&#10;```&#10;Reload unit files and systemd configuration&#10;Nemeth, Evi. _Unix and Linux System Administration Handbook, 5th ed._: 47'
[systemctl disable]:                       #systemctl                     '```&#10;$ systemctl disable $UNIT&#10;```&#10;Prevent `$UNIT` from activating at boot&#10;Nemeth, Evi. _Unix and Linux System Administration Handbook, 5th ed._: 47'
[systemctl enable]:                        #systemctl                     '```&#10;$ systemctl enable $UNIT&#10;```&#10;Enable `$UNIT` to activate it at boot&#10;Nemeth, Evi. _Unix and Linux System Administration Handbook, 5th ed._: 47'
[systemctl isolate]:                       #systemctl                     '```&#10;$ systemctl isolate $TARGET&#10;```&#10;Change operating mode to `$TARGET`&#10;Nemeth, Evi. _Unix and Linux System Administration Handbook, 5th ed._: 47'
[systemctl kill]:                          #systemctl                     '```&#10;$ systemctl kill $PATTERN&#10;```&#10;Send a signal to units matching `$PATTERN`&#10;Nemeth, Evi. _Unix and Linux System Administration Handbook, 5th ed._: 47'
[systemctl list-unit-files]:               #systemctl                     '```&#10;$ systemctl list-unit-files&#10;```&#10;&#10;Nemeth, Evi. _Unix and Linux System Administration Handbook, 5th ed._: 47'
[systemctl list-units]:                    #systemctl                     '```&#10;$ systemctl list-units $PATTERN&#10;```&#10;Show installed units; optionally matching `$PATTERN`&#10;Nemeth, Evi. _Unix and Linux System Administration Handbook, 5th ed._: 47'
[systemctl reboot]:                        #systemctl                     '```&#10;$ systemctl reboot&#10;```&#10;Reboot the computer&#10;Nemeth, Evi. _Unix and Linux System Administration Handbook, 5th ed._: 47'
[systemctl restart]:                       #systemctl                     '```&#10;$ systemctl restart $UNIT&#10;```&#10;Restart `$UNIT` immediately&#10;Nemeth, Evi. _Unix and Linux System Administration Handbook, 5th ed._: 47'
[systemctl start]:                         #systemctl                     '```&#10;$ systemctl start $UNIT&#10;```&#10;Activate `$UNIT` immediately&#10;Nemeth, Evi. _Unix and Linux System Administration Handbook, 5th ed._: 47'
[systemctl status]:                        #systemctl                     '```&#10;$ systemctl status $UNIT&#10;```&#10;Show status of `$UNIT` and recent log entries.&#10;Nemeth, Evi. _Unix and Linux System Administration Handbook, 5th ed._: 47'
[systemctl stop]:                          #systemctl                     '```&#10;$ systemctl stop $UNIT&#10;```&#10;Deactivate `$UNIT` immediately&#10;Nemeth, Evi. _Unix and Linux System Administration Handbook, 5th ed._: 47'
[systemctl mask]:                          #systemctl                     '```&#10;$ systemctl mask $UNIT&#10;```&#10;Prevent `$UNIT` from being started inadvertently by another process'
[systemctl set-default]:                   #systemctl                     '```&#10;$ systemctl set-default $TARGET&#10;```&#10;Configure system to boot to operating mode indicated by `$TARGET`'
[systemctl get-default]:                   #systemctl                     '```&#10;$ systemctl get-default&#10;```&#10;Display default operating mode'
[systemctl suspend]:                       #systemctl                     '```&#10;$ systemctl suspend&#10;```&#10;Suspend the system'

[`daemon-reload`][systemctl daemon-reload] 
[`disable`][systemctl disable] 
[`enable`][systemctl enable] 
[`get-default`][systemctl get-default] 
[`isolate`][systemctl isolate] 
[`kill`][systemctl kill] 
[`list-unit-files`][systemctl list-unit-files] 
[`list-units`][systemctl list-units] 
[`mask`][systemctl mask] 
[`reboot`][systemctl reboot] 
[`restart`][systemctl restart] 
[`set-default`][systemctl set-default] 
[`start`][systemctl start] 
[`status`][systemctl status] 
[`stop`][systemctl stop] 
[`suspend`][systemctl suspend] 

Configure iptables to start on boot and start it immediately
```sh
systemctl enable --now iptables
```
Disable `$SERVICE`, ensuring it does not run on boot
```sh
systemctl disable $SERVICE
```
Change signal type sent to process to be killed
```sh
systemctl kill -s
```
Equivalent to `chkconfig --list`
```sh
systemctl list-unit-files --type=service
```
Prevent firewalld from being started inadvertently by another process
```sh
systemctl mask firewalld
```
Restart `iptables.service`
```sh
systemctl restart iptables
```
Configure system to boot to a [GUI](#targets)
```sh
systemctl set-default graphical.target
```
Start `$SERVICE`
```sh
systemctl start $SERVICE
```
Check status of `$SERVICE`
```sh
systemctl status $SERVICE
sudo systemctl is-active $SERVICE
```
Terminate `$SERVICE`
```sh
systemctl stop $SERVICE
```
Stop `$SERVICE`
```sh
systemctl stop $SERVICE
```
Suspend the system
```sh
systemctl suspend
```
Change target to runlevel emergency
```sh
systemctl isolate emergency.target
```
##### `systemd-analyze`

##### `systemd-delta`
Show files that are overridden with systemd\
Display differences among files when they are overridden
```sh
systemd-delta --diff
```
##### `timedatectl`
##### `chkconfig`
Turn services on or off for runlevels
Without arguments, `chkconfig` defaults to runlevels 3 or 5:
```sh
chkconfig
```
Display all services and runlevels
```sh
chkconfig --list
```
Turn {daemon} on for runlevels 3 and 5
```sh
chkconfig --level 35 daemon on
```
Turn {daemon} off
```sh
chkconfig daemon off
chkconfig NetworkManager off
```
Turn {daemon} service on
```sh
chkconfig daemon on
```
##### `init`
Access different runlevels
```sh
init 
```
Switch to runlevel {n}
```sh
init n
init 6 # reboot
```
##### `runlevel`
Show runlevel for system
```sh
runlevel 
```
##### `service`
Restart network service 
```sh
service network restart
```
Check status of {daemon}
```sh
service daemon status
```
Stop {daemon}
```sh
service daemon stop
service mongodb stop
```
##### `telinit`
Refresh system after changes to `/etc/inittab`
```sh
telinit 
```
Cause operation to not send any notice to logged-on users
```sh
telinit--no-wall
```
##### `initctl`
Reload configuration files (on Upstart-controlled system)
```sh
initctl reload
```
## Kernel
[`dbus-monitor`][dbus-monitor] 
[`depmod`][depmod] 
[`dmesg`][dmesg] 
[`dracut`][dracut] 
[`insmod`][insmod] 
[`journalctl`][journalctl] 
[`ldconfig`][ldconfig] 
[`lsmod`][lsmod] 
[`mkinitrd`][mkinitrd] 
[`modinfo`][modinfo] 
[`modprobe`][modprobe] 
[`rmmod`][rmmod] 
[`udevadm`][udevadm] 

### System calls
<!-- Syscalls -->
[chmod()]: #system-calls 'chmod&#10;change file access permissions&#10;Sobell, Mark. _Practical Guide to Linux_. 2017.: 418'
[chown()]: #system-calls 'chown&#10;change file ownership&#10;Sobell, Mark. _Practical Guide to Linux_. 2017.: 418'
[close()]: #system-calls 'close&#10;close a file&#10;Sobell, Mark. _Practical Guide to Linux_. 2017.: 418'
[creat()]: #system-calls 'creat&#10;create a new file&#10;Sobell, Mark. _Practical Guide to Linux_. 2017.: 418'
[exec()]: #system-calls 'exec&#10;overlay a program in memory with another&#10;Sobell, Mark. _Practical Guide to Linux_. 2017.: 418'
[exit()]: #system-calls 'exit&#10;cause a process to exit&#10;Sobell, Mark. _Practical Guide to Linux_. 2017.: 418'
[fork()]: #system-calls 'fork&#10;create a copy of a process&#10;Sobell, Mark. _Practical Guide to Linux_. 2017.: 418'
[getpid()]: #system-calls 'getpid&#10;return the PID of the calling process&#10;Sobell, Mark. _Practical Guide to Linux_. 2017.: 418'
[kill()]: #system-calls 'kill&#10;send a signal to a process&#10;Sobell, Mark. _Practical Guide to Linux_. 2017.: 418'
[lseek()]: #system-calls 'lseek&#10;move to a position in the file&#10;Sobell, Mark. _Practical Guide to Linux_. 2017.: 418'
[nice()]: #system-calls 'nice&#10;change the priority of a process&#10;Sobell, Mark. _Practical Guide to Linux_. 2017.: 418'
[open()]: #system-calls 'open&#10;open an existing file&#10;Sobell, Mark. _Practical Guide to Linux_. 2017.: 418'
[read()]: #system-calls 'read&#10;read a file&#10;Sobell, Mark. _Practical Guide to Linux_. 2017.: 418'
[stat()]: #system-calls 'stat&#10;Get status information from an inode, such as the inode number, device on which it is located, owner and group information, and the size of the file&#10;Sobell, Mark. _Practical Guide to Linux_. 2017.: 418'
[unlink()]: #system-calls 'unlink&#10;unlink a fie (delete a name reference to the inode)&#10;Sobell, Mark. _Practical Guide to Linux_. 2017.: 418'
[wait()]: #system-calls 'wait&#10;cause the parent process to wait for the child to finish running before it resumes execution&#10;Sobell, Mark. _Practical Guide to Linux_. 2017.: 418'
[write()]: #system-calls 'write&#10;write a file&#10;Sobell, Mark. _Practical Guide to Linux_. 2017.: 418'

[`chmod()`][chmod()] 
[`chown()`][chown()] 
[`close()`][close()] 
[`creat()`][creat()] 
[`exec()`][exec()] 
[`exit()`][exit()] 
[`fork()`][fork()] 
[`getpid()`][getpid()] 
[`kill()`][kill()] 
[`lseek()`][lseek()] 
[`nice()`][nice()] 
[`open()`][open()] 
[`read()`][read()] 
[`stat()`][stat()] 
[`unlink()`][unlink()] 
[`wait()`][wait()] 
[`write()`][write()] 

### `dmesg`
[dmesg -&#100;]:                #dmesg                         '```&#10;$ dmesg -d&#10;```&#10;Disable kernel messages from being sent to the console'
[dmesg -&#101;]:                #dmesg                         '```&#10;$ dmesg -e&#10;$ dmesg --reltime&#10;```&#10;Enable kernel messages being sent to the console; display time in local time'

<code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> [`d`][dmesg -&#100;] [`e`][dmesg -&#101;] <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> 

### `insmod`
[insmod -&#115;]:               #insmod                        '```&#10;$ insmod -s&#10;```&#10;Direct output to `syslog` instead of STDOUT&#10;Haeder, Adam. _LPI Linux Certification in a Nutshell_. 2010.: 16'
[insmod -&#118;]:               #insmod                        '```&#10;$ insmod -v&#10;```&#10;Set verbose mode&#10;Haeder, Adam. _LPI Linux Certification in a Nutshell_. 2010.: 16'

<code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> [`s`][insmod -&#115;] <code>&nbsp;</code> <code>&nbsp;</code> [`v`][insmod -&#118;] <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> 

### `ldconfig`
[ldconfig -&#80;]:              #ldconfig                      '```&#10;$ ldconfig -P&#10;```&#10;Display the contents of the current cache instead of recreating it&#10;Haeder, Adam. _LPI Linux Certification in a Nutshell_. 2010.: 45'
[ldconfig -&#118;]:             #ldconfig                      '```&#10;$ ldconfig -v&#10;```&#10;Verbose output&#10;Haeder, Adam. _LPI Linux Certification in a Nutshell_. 2010.: 45'
[ldconfig -&#99;]:              #ldconfig                      '```&#10;$ ldconfig -c&#10;```&#10;Change location of cache to be updated'
[ldconfig -&#112;]:             #ldconfig                      '```&#10;$ ldconfig -p&#10;```&#10;Print current directories and libraries in cache'
[ldconfig -&#118;]:             #ldconfig                      '```&#10;$ ldconfig -v&#10;```&#10;Display all shared libraries'

<code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> [`c`][ldconfig -&#99;] <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> [`p`][ldconfig -&#112;] <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> [`v`][ldconfig -&#118;] <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> 

### `lsmod`
[lsmod -&#104;]:                #lsmod                         '```&#10;$ lsmod -h&#10;$ lsmod --help&#10;```&#10;Display help information&#10;Haeder, Adam. _LPI Linux Certification in a Nutshell_. 2010.: 13'
[lsmod -&#86;]:                 #lsmod                         '```&#10;$ lsmod -V&#10;$ lsmod --version&#10;```&#10;Display the version&#10;Haeder, Adam. _LPI Linux Certification in a Nutshell_. 2010.: 13'

<code>&nbsp;</code>   <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> [`h`][lsmod -&#104;] <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code>  <br><code>&nbsp;</code>&nbsp;<code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> [`V`][lsmod -&#86;] <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> 

Display currently loaded modules. Output in three columns:
1. Module name
2. Module size (bytes)
3. Processes, filesystems, or other modules using the module

### `modinfo`
[modinfo -&#97;]:               #modinfo                       '```&#10;$ modinfo -a&#10;```&#10;Display the author of the module&#10;Haeder, Adam. _LPI Linux Certification in a Nutshell_. 2010.: 17'
[modinfo -&#100;]:              #modinfo                       '```&#10;$ modinfo -d&#10;```&#10;Display the description of the module&#10;Haeder, Adam. _LPI Linux Certification in a Nutshell_. 2010.: 17'
[modinfo -&#112;]:              #modinfo                       '```&#10;$ modinfo -p&#10;```&#10;Display the typed parameters that a module supports&#10;Haeder, Adam. _LPI Linux Certification in a Nutshell_. 2010.: 17'

<code>&nbsp;</code> [`a`][modinfo -&#97;] <code>&nbsp;</code> <code>&nbsp;</code> [`d`][modinfo -&#100;] <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> [`p`][modinfo -&#112;] <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> 

### `modprobe`
[modprobe -&#97;]:              #modprobe                      '```&#10;$ modprobe -a&#10;```&#10;Load all modules&#10;Haeder, Adam. _LPI Linux Certification in a Nutshell_. 2010.: 18'
[modprobe -&#99;]:              #modprobe                      '```&#10;$ modprobe -c&#10;$ modprobe --showconfig&#10;```&#10;Display a complete module configuration, including defaults and directives found in /etc/modules.conf&#10;Haeder, Adam. _LPI Linux Certification in a Nutshell_. 2010.: 19'
[modprobe -&#108;]:             #modprobe                      '```&#10;$ modprobe -l&#10;```&#10;List modules&#10;Haeder, Adam. _LPI Linux Certification in a Nutshell_. 2010.: 19'
[modprobe -&#114;]:             #modprobe                      '```&#10;$ modprobe -r&#10;$ modprobe --remove&#10;```&#10;Remove `$MODULE`, similar to `rmmod`.&#10;Haeder, Adam. _LPI Linux Certification in a Nutshell_. 2010.: 19'
[modprobe -&#115;]:             #modprobe                      '```&#10;$ modprobe -s&#10;```&#10;Direct output to `syslog` instead of STDOUT&#10;Haeder, Adam. _LPI Linux Certification in a Nutshell_. 2010.: 19'
[modprobe -&#116;]:             #modprobe                      '```&#10;$ modprobe -t $MODULETYPE&#10;```&#10;Attempt to load multiple modules found in `$MODULETYPE` until a module success or all modules in `$MODULETYPE` are exhausted.&#10;Haeder, Adam. _LPI Linux Certification in a Nutshell_. 2010.: 19'
[modprobe -&#118;]:             #modprobe                      '```&#10;$ modprobe -v&#10;```&#10;Verbose output&#10;Haeder, Adam. _LPI Linux Certification in a Nutshell_. 2010.: 19'
[modprobe -&#82;]:              #modprobe                      '```&#10;$ modprobe -R&#10;$ modprobe --resolve-alias&#10;```&#10;Display all modules that match an alias'
[modprobe --show-depends]:                    #modprobe                      '```&#10;$ modprobe --show-depends&#10;```&#10;Show dependencies of the kernel module'
[modprobe -&#113;]:             #modprobe                      '```&#10;$ modprobe -q&#10;```&#10;Quiet mode&#10;Rothwell, William. _CompTIA Linux+/LPIC-1 Portable Command guide_.: 3'

<code>&nbsp;</code>   [`a`][modprobe -&#97;] <code>&nbsp;</code> [`c`][modprobe -&#99;] <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> [`l`][modprobe -&#108;] <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> [`q`][modprobe -&#113;] [`r`][modprobe -&#114;] [`s`][modprobe -&#115;] [`t`][modprobe -&#116;] <code>&nbsp;</code> [`v`][modprobe -&#118;] <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code>  <br><code>&nbsp;</code>&nbsp;<code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> [`R`][modprobe -&#82;] <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> 

### `rmmod`
[rmmod -&#97;]:                 #rmmod                         '```&#10;$ rmmod -a&#10;```&#10;Remove all unused modules&#10;Haeder, Adam. _LPI Linux Certification in a Nutshell_. 2010.: 17'
[rmmod -&#115;]:                #rmmod                         '```&#10;$ rmmod -s&#10;```&#10;Direct output to `syslog` instead of STDOUT&#10;Haeder, Adam. _LPI Linux Certification in a Nutshell_. 2010.: 17'
[rmmod -&#119;]:                #rmmod                         '```&#10;$ rmmod -w&#10;```&#10;Wait until a module is no longer in use before unloading'

<code>&nbsp;</code> [`a`][rmmod -&#97;] <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> [`s`][rmmod -&#115;] <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> [`w`][rmmod -&#119;] <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> 

### `sysctl`
View and configure kernel parameters at runtime

Display current hostname as known to the kernel
```sh
sysctl -n kernel.hostname
```

## Mail
[MDA]: #mail 'mail delivery agent (MDA)&#10;service that downloads email from an MTA, such as procmail and fetchmail&#10;Eckert, Jason. _Linux+ Guide to Linux Certification_. Course Technology, 2012: 23'
[MTA]: #mail 'mail transfer agent (MTA)&#10;email server, such as sendmail, postfix, smail, and qmail&#10;Eckert, Jason. _Linux+ Guide to Linux Certification_. Course Technology, 2012: 23'
[MUA]: #mail 'mail user agent (MUA)&#10;program that allows a user to view mail, such as mutt, pine, printmail, elm, mail, Thunderbird, Evolution, and Eudora&#10;Eckert, Jason. _Linux+ Guide to Linux Certification_. Course Technology, 2012: 23'

[MDA][MDA] 
[MTA][MTA] 
[MUA][MUA]

[pine]: #pine "\"Program for Internet news and email\", popular MUA during the 1990s which has since been replaced by Alpine."
[`biff`][biff] 
[`mail`][mail] 
[`mailmerge`][mailmerge] 
[`mailq`][mailq] 
[`mailx`][mailx] 
[`makemap`][makemap] 
[`msmtp`][msmtp] 
[`newaliases`][newaliases] 
[`newaliases`][newaliases] 
[`postalias`][postalias] 
[`postfix`][postfix] 
[`postqueue`][postqueue] 
[`qmail`][qmail] 
[`sendmail`][sendmail] 

### `mail`
**Mail User Agent (MUA)** which accepts interactive input using the `&` prompt
Check email of `$USER`
```sh
mail -u $USER
```
Send email to `$USER`
```sh
mail $USER
```
Send email from the command-line
Send email interactively
```sh
mail $ADDRESS
```
Send message via pipe 
```sh
echo 'message' | mail -s 'subject' recipient@domain.com
```
Send an email attachment from the command-line
```sh
mail -a /path/to/attachment
```
Send message via pipe
```sh
echo 'message' | mail -s 'subject' -a /path/to/attachment
```
### `mailmerge`
Mailmerge is a command-line Python program that provides a powerful way to send many customized emails by using Jinja2 templating. It is available from Fedora's repositories through `dnf` and is also available from PyPI. [[ref](https://opensource.com/article/19/8/sending-custom-emails-python "opensource.com: \"Sending custom emails with Python\"")]

Configuration file            | Description
:---                          | :---
$HOME/mailmerge_server.conf   | SMTP host configuration details
$HOME/mailmerge_database.csv  | custom data for each email, including email addresses of recipients. The email address to be used as test recipient (i.e. the user) is the first entry by convention.
$HOME/mailmerge_template.txt  | email's text with placeholder fields that will be replaced using data from mailmerge_database.csv

Review message to be sent to first recipient
This will display the message addressed to the first address specified in the recipient database in the terminal
```sh
mailmerge
```
Review every message to be sent
```sh
mailmerge --no-limit
```
Send test message to first recipient
```sh
mailmerge --no-dry-run
```
Send all emails
```sh
mailmerge --no-dry-run --no-limit
```
### `mailq`
Display the current mail queue on a Postfix server
### `mailstats`
Gather and display statistics about mail processed on a server running [ `sendmail` ](#sendmail)
### `msmtp`
<sup>[vitux.com](https://vitux.com/how-to-use-gmail-from-the-ubuntu-terminal-to-send-emails/ "How to use Gmail from the Ubuntu terminal to send emails")</sup>

~/.msmtprc

### `newaliases`
Refresh the mail system after a change to the [ /etc/aliases ](#configs) file; Must be run after making a change to email aliases on a server running [ `postfix` ](#postfix)
### `postqueue`
Cause mail queue to be processed on a Postfix server
```sh
postqueue -f
```
### `postsuper`
Delete all of the messages from the queue on a postfix server
```sh
postsuper -d
```
### `postfix`
Designed to replace Sendmail. 
- multiple processes with no particular parent/child relationship
Receives mail by two methods:
1. Local mail (sendmail)
2. Internet mail (SMTP)
Before mail is queued for delivery, it goes through a cleanup daemon, which can be configured to do header and body inspection using regex
`Qmgr` is the heart of postfix mail delivery; it maintains an active queue, which attempts delivery. It delivers mail using three methods:
1. Local inboxes
2. Internet (SMTP)
3. Piped to programs
### `qmail`
Mail Transfer Agent (MTA) designed as a drop-in replacement for Sendmail, notable for being the first to be "security-aware". Its various modular subcomponents run independently and are mutually untrustful. It uses SMTP to exchange messages with other MTAs. It was written by Dan Bernstein, a professor of mathematics famous for litigating against the US government with regard to export controls on encryption algorithms. Deprecated and removed from Arch repos in 2005. [[27](sources.md)]
### `sendmail`
Mail daemon once the de facto standard for accepting and redirecting mail on Linux distributions, long ago fallen into disuse. It was infamous for its difficulty to set up, with roots in ARPANET itself. [<sup>ref</sup>][Eckert]
### `ssmtp`
Installable client program [[25](sources.md)]

Configuration file                            | Description
:---                                          | :---
[/etc/ssmtp/ssmtp.conf](configs.md#etcssmtpssmtpconf) | Configuration file

Send {msg} to {recipient} from {user} at {host} using password {pw}
```sh
ssmtp -au recipient -ap pw user@host < msg
```
### `pine`
"Program for Internet news and email", a popular [MUA](# "\"mail user agent\", program that allows a user to view mail, such as mutt, pine, printmail, elm, mail, Thunderbird, Evolution, and Eudora") during the 1990s which has since been superceded by Alpine.

## Networking
[`bmon`][bmon] 
[`brctl`][brctl] 
[`curl`][curl] 
[`dig`][dig] 
[`ethtool`][ethtool] 
[`firewall-cmd`][firewall-cmd] 
[`host`][host] 
[`hping3`][hping3] 
[`ifconfig`][ifconfig] 
[`iftop`][iftop] 
[`ifup-wireless`][ifup-wireless] 
[`ip`][ip] 
[`iperf`][iperf] 
[`ipset`][ipset] 
[`iw`][iw] 
[`iwconfig`][iwconfig] 
[`iwlist`][iwlist] 
[`kinit`][kinit] 
[`klist`][klist] 
[`mtr`][mtr] 
[`netcat`][netcat] 
[`netplan`][netplan] 
[`netstat`][netstat] 
[`nmap`][nmap] 
[`nmblookup`][nmblookup] 
[`nmcli`][nmcli] 
[`nmtui`][nmtui] 
[`nslookup`][nslookup] 
[`ping`][ping] 
[`rfkill`][rfkill] 
[`route`][route] 
[`sftp`][sftp] 
[`ss`][ss] 
[`ssh`][ssh] 
[`ssh-add`][ssh-add] 
[`ssh-agent`][ssh-agent] 
[`ssh-keygen`][ssh-keygen] 
[`ssh-keyscan`][ssh-keyscan] 
[`stty`][stty] 
[`tcpdump`][tcpdump] 
[`tracepath`][tracepath] 
[`tracepath6`][tracepath6] 
[`traceroute`][traceroute] 
[`tshark`][tshark] 
[`wget`][wget] 
[`whois`][whois] 
[`xinetd`][xinetd] 


### `bmon`
[<sup>ref</sup>][https://www.networkworld.com/video/99387/how-to-use-the-bmon-command-2-minute-linux-tips] 
[<sup>ref</sup>][https://www.networkworld.com/article/3447936/viewing-network-bandwidth-usage-with-bmon.html]
### `dig`
DNS lookup tool that returns the text of the actual response from the DNS server, useful when troubleshooting a DNS issue (cf. [ `nslookup` ](nslookup.md))\
Nameserver
```
dig example.com NS
```
Mail server
```
dig example.com MX
```
Perform a reverse DNS lookup on an IP address
```sh
dig -x 8.8.8.8
```
Specify an alternate DNS server to query
```sh
dig @8.8.8.8 example.com
```
Find authoritative nameservers for the zone and display SOA records
```sh
dig +nsearch example.com
```
Lookup the IP associated with a domain name
```sh
dig +short example.com
```
Lookup the mail server IP associated with a domain name
```sh
dig +short example.com MX example.com MX
```
Perform iterative queries and display the entire trace path to resolve a domain name
```sh
dig +trace example.com
```
Get all types of records for a given domain name
```sh
dig example.com ANY
```
Display Start of Authority information for a domain
```sh
dig example.com soa
```
### `firewall-cmd`
<!-- `firewall-cmd` options -->
[firewall-cmd --state]:                #firewall-cmd                  '```&#10;$ firewall-cmd --state&#10;```&#10;Display status of service'
[firewall-cmd --get-default-zone]:                #firewall-cmd                  '```&#10;$ firewall-cmd --get-default-zone&#10;```&#10;Display default zone'
[firewall-cmd --get-active-zones]:                #firewall-cmd                  '```&#10;$ firewall-cmd --get-active-zones&#10;```&#10;Display zones that are attached to an interface'
[firewall-cmd --new-zone]:                #firewall-cmd                  '```&#10;$ firewall-cmd --new-zone $NAME&#10;```&#10;Add a new zone'
[firewall-cmd --permanent]:                #firewall-cmd                  '```&#10;$ firewall-cmd --permanent&#10;```&#10;Write the change tro disk'
[firewall-cmd --reload]:                #firewall-cmd                  '```&#10;$ firewall-cmd --reload&#10;```&#10;Load saved configuration'
[firewall-cmd --get-services]:                #firewall-cmd                  '```&#10;$ firewall-cmd --get-services&#10;```&#10;Display available services'
[firewall-cmd --add-service]:                #firewall-cmd                  '```&#10;$ firewall-cmd --add-service $SERVICE&#10;```&#10;Add a service, like "ftp"'
[firewall-cmd --list-services]:                #firewall-cmd                  '```&#10;$ firewall-cmd --list-services&#10;```&#10;Display loaded services'
[firewall-cmd --remove-service]:                #firewall-cmd                  '```&#10;$ firewall-cmd --remove-service&#10;```&#10;Remove service'
[firewall-cmd --add-port]:                #firewall-cmd                  '```&#10;$ firewall-cmd --add-port $PORTS/$PROTOCOL&#10;```&#10;Add nonstandard `$PORTS`, which can be a single port or a range.'

[`add-port`][firewall-cmd --add-port] 
[`add-service`][firewall-cmd --add-service] 
[`get-active-zones`][firewall-cmd --get-active-zones] 
[`get-default-zone`][firewall-cmd --get-default-zone] 
[`get-services`][firewall-cmd --get-services] 
[`list-services`][firewall-cmd --list-services] 
[`new-zone`][firewall-cmd --new-zone] 
[`permanent`][firewall-cmd --permanent] 
[`reload`][firewall-cmd --reload] 
[`remove-service`][firewall-cmd --remove-service] 
[`state`][firewall-cmd --state]

Successor to `iptables` in Red Hat, and like its predecessor a frontend to the netfilter protocols. Places network traffic into zones. Commands have to be written twice: once to affect running config and again to have the change saved

Configuration file                          | Description
:---                                        | :---
/etc/sysconfig/network-scripts/ifcfg-ens33  | interface settings
/usr/lib/firewalld/services                 | .xml files that define services ("ZONE=public")

Add a new zone, and write the change to disk
```
firewall-cmd --new-zone=testlab  --permanent
```

### `hping3`
Hping3 crafts "SYN" (sequence) packets from random spoofed IP addresses and sends them out at very short intervals. <sup>[Sec+ Lab][Sec+ Lab]</sup>

Option  | POSIX option            | Effect [<sup>ref</sup>][https://tools.kali.org/information-gathering/hping3]
:---    | :---                    | :---
`-i`    | `--interval`            | wait for specified number of microseconds
`-p`    | `--destport`            | destination port 
`-q`    | `--quiet`               | quiet
`-S`    | `--baseport`            | base source port (default random)
&nbsp;  | `--rand-source`         | random source address mode

```sh
hping3 192.168.0.2 -p 80 -i u10 -S -q --rand-source
```
### `ifconfig`
"RX" and "TX" stand for received and transmitted.

Apply a static IP address to interface {eth0} and turn it on ("up")
```
ifconfig eth0 up 10.1.230.245 netmask 255.255.255.0
```
Bring an interface up or down
```
ifup eth0
ifdown eth0
```
```
ifconfig eth0 up
ifconfig eth0 down
```
Display details of all interfaces (even disabled)
```sh
ifconfig -a
```
Disable eth0
```sh
ifconfig eth0 down
```
Configure eth0 with an additional IPv6 address
```sh
ifconfig eth0 inet6 add fdd6:551:b09e::/128
```
Enable eth0
```sh
ifconfig eth0 up
```
Turn network interface {eth0} on or off using `ifconfig`
```sh
ifconfig eth0 up
ifconfig eth0 down
```
Turn off network interface {eth0}
```sh
ifdown eth0
```
Bring online all interfaces marked as auto within the networking configuration
```sh
ifup -a
```
Turn on network interface {eth0}
```sh
ifup eth0
```
### `ip`
Newer alternative to the old `ifconfig`
```sh
ip addr
```
Show L2 status (links)
```sh
ip link
```
Listen for netlink messages
```sh
ip monitor 
```
Display routing information
```sh
ip route
```
Change the default gateway to 192.168.1.1 on eth0
```sh
ip route change default via 192.168.1.1 dev eth0
```
Turn on interface `wlp2s0`
```sh
sudo ip link set wlp2s0 up
```
### `iptables`
A popular firewall, like `firewalld`, a frontend for the kernel-level `netfilters` service. Interface configuration, used to assign a TCP/IP configuration to a network interface, but no longer installed on modern distros.

Config files  | Description
:---          | :---
/etc/sysconfig/iptables | location of saved config

Display rules as written on disk
```sh
iptables --list-rules
```
Accept SSH traffic from a particular IP
```sh
iptables -A INPUT -p ssh -s 10.0.222.222 -j ACCEPT
```
Accept incoming TCP traffic to port 80
```sh
iptables -A INPUT -p tcp --dport 80 -j ACCEPT
```
Reload configuration file
```sh
iptables -F
```
Show statistics for configuration lines
```sh
iptables -vnL --lines
```
Display rules as written on disk
```sh
iptables --list-rules
```
Set an iptable rule to accept SSH traffic from a particular IP
```sh
iptables -A INPUT -p ssh -s 10.0.222.222 -j ACCEPT
```
Set an iptable rule to accept incoming TCP traffic to port 80
```sh
iptables -A INPUT -p tcp --dport 80 -j ACCEPT
```
Reload configuration file
```sh
iptables -F
```
Show statistics for configuration lines
```sh
iptables -vnL --lines
```
### `iptables-save`
### `iw`
Show or manipulate wireless devices and their configuration; followed by `dev`, `phy`, or `reg` depending on the device.

Check the name of network device <sup>[Fedora Docs](https://docs.fedoraproject.org/en-US/quick-docs/adding-new-fonts-fedora/ "Fedora Docs - Adding new fonts in Fedora")</sup>
```sh
iw dev
```
Check the connecdtion status of the Wi-Fi device `wlp2s0`
```sh
iw wlp2s0 link
```
### `iwlist`
### `nc`
The netcat utility allows testing of a host's ports, similar to **ping**, but more versatile because **ping** only uses the portless ICMP protocol. GNU and OpenBSD versions available (itp-l+: 28)

Option  | Effect
:---    | :---
`-l`    | listening mode

Connect to host on port 80
```
nc example.com 80
```
Scan ports
```
# Scan a single port
nc -v -w 2 z 192.168.56.1 22

# Scan multiple ports
nc -v -w 2 z 192.168.56.1 22 80

# Scan a range of ports
nc -v -w 2 z 192.168.56.1 22-25
```
Transfer files between servers
This example uses the `pv` utility to monitor progress.
```
# Run `nc` in listening mode (`-l` option) on port 3000
tar -zcf - debian-10.0.0-amd64-xfce-CD-1.iso | pv | nc -l -p 3000 -q 5

# On the receiving client, to obtain the file:
nc 192.168.1.4 3000 | pv | tar -zxf -
```
Create a command-line chat server
```
# Create chat server listening on port 5000
nc -l -vv -p 5000

# Launch a chat session on the other system
nc 192.168.56.1 5000
```
Find a service running on port
Obtain port banners (`-n` disables DNS lookup)
```
nc -v -n 192.168.56.110 80
```
Create stream sockets
Create and listen on a UNIX-domain stream socket
```
nc -lU /var/tmp/mysocket &
ss -lpn | grep "/var/tmp/"
```
Create a backdoor
Netcat needs to listen on a chosen port (here 3001): `-d` disables reading from stdin; `-e` specifies the command to run on the target system
```
nc -L -p 3001 -d -e cmd.exe
```
Connect to {port} at {host}
```sh
nc host port
```
Netcat command that retrieves a webpage
```sh
nc host port \get
```
### `netstat`

[netstat -&#97;]:               #netstat                       '```&#10;$ netstat -a&#10;$ netstat --all&#10;```&#10;Apply to all&#10;Rothwell, William. _CompTIA Linux+ Portable Command Guide_.: 18'
[netstat -&#99;]:               #netstat                       '```&#10;$ netstat -c&#10;$ netstat --continuous&#10;```&#10;Continuous operation, yielding a `netstat` display every second until interrupted with Ctrl-C&#10;Haeder, Adam. _LPI Linux Certification in a Nutshell_. 2010.: 398'
[netstat -&#103;]:              #netstat                       '```&#10;$ netstat -g&#10;$ netstat --groups&#10;```&#10;Display multicast group membership information for IPv4 and IPv6'
[netstat -&#105;]:              #netstat                       '```&#10;$ netstat -i&#10;$ netstat --interfaces&#10;```&#10;Display a list of interfaces&#10;Haeder, Adam. _LPI Linux Certification in a Nutshell_. 2010.: 399'
[netstat -&#108;]:              #netstat                       '```&#10;$ netstat -l&#10;$ netstat --listening&#10;```&#10;Display only listening sockets'
[netstat -&#77;]:               #netstat                       '```&#10;$ netstat -M&#10;$ netstat --masquerade&#10;```&#10;Display masqueraded connections'
[netstat -&#110;]:              #netstat                       '```&#10;$ netstat -n&#10;$ netstat --numeric&#10;```&#10;Numeric mode; do not resolve hostnames&#10;Haeder, Adam. _LPI Linux Certification in a Nutshell_. 2010.: 399'
[netstat -&#111;]:              #netstat                       '```&#10;$ netstat -o&#10;$ netstat --timers&#10;```&#10;Display information related to networking timers'
[netstat -&#112;]:              #netstat                       '```&#10;$ netstat -p&#10;$ netstat --program&#10;```&#10;Programs mode; display the PID and process name&#10;Haeder, Adam. _LPI Linux Certification in a Nutshell_. 2010.: 399'
[netstat -&#114;]:              #netstat                       '```&#10;$ netstat -r&#10;$ netstat --route&#10;```&#10;Routing mode; display the routing table in the format of `route`&#10;Haeder, Adam. _LPI Linux Certification in a Nutshell_. 2010.: 399'
[netstat -&#115;]:              #netstat                       '```&#10;$ netstat -s&#10;$ netstat --statistics&#10;```&#10;Display statistics for the output&#10;Rothwell, William. _CompTIA Linux+ Portable Command Guide_.: 18'
[netstat -&#116;]:              #netstat                       '```&#10;$ netstat -t&#10;$ netstat --tcp&#10;```&#10;Display TCP information&#10;Rothwell, William. _CompTIA Linux+ Portable Command Guide_.: 18'
[netstat -&#117;]:              #netstat                       '```&#10;$ netstat -u&#10;$ netstat --udp&#10;```&#10;Display UDP information&#10;Rothwell, William. _CompTIA Linux+ Portable Command Guide_.: 18'
[netstat -&#118;]:              #netstat                       '```&#10;$ netstat -v&#10;$ netstat --verbose&#10;```&#10;Verbose output&#10;Rothwell, William. _CompTIA Linux+ Portable Command Guide_.: 18'

<code>&nbsp;</code>   [`a`][netstat -&#97;] <code>&nbsp;</code> [`c`][netstat -&#99;] <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> [`g`][netstat -&#103;] <code>&nbsp;</code> [`i`][netstat -&#105;] <code>&nbsp;</code> <code>&nbsp;</code> [`l`][netstat -&#108;] <code>&nbsp;</code> [`n`][netstat -&#110;] [`o`][netstat -&#111;] [`p`][netstat -&#112;] <code>&nbsp;</code> [`r`][netstat -&#114;] [`s`][netstat -&#115;] [`t`][netstat -&#116;] [`u`][netstat -&#117;] [`v`][netstat -&#118;] <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code>  <br><code>&nbsp;</code>&nbsp;<code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> [`M`][netstat -&#77;] <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> 

Show network traffic
```sh
netstat -an
```
Refresh every five seconds
```sh
netstat -c5
``` 
Show the current default route without performing DNS lookups on the IP addresses involved
```sh
netstat -rn
```
Count number of TCP connections 
```
netstat -a | grep tcp - | wc -l
``` 
Active sessions 
```
netstat -tp
``` 
All sessions
```
netstat -atp
``` 
Routing table with name resolution 
```
netstat -rn
``` 
Get the list of IPs and ports that are connected via https on your webserver every second
```
watch -n 1 'netstat -an | grep ":443"'
``` 
Get the total number of connections on port 80 every second
```
watch -n 1 'netstat -an | grep ":80" | wc -l'
```
### `nmcli`
Control NetworkManager and report network status

Display devices and statuses
```
nmcli device status
```

Display information on interfaces as well as status
Including other network connections not managed by network manager ("unmanaged") or not connected ("unavailable") 
```
nmcli dev status
```
Display what connections are enabled 
```
nmcli general status
```
Display UUIDs associated with network connections 
```
nmcli connection show --active
```
Display much more information on network devices
```
nmcli device show
```
Configure settings for network interface {ens01} via interactive shell
```sh
nmcli connection edit ens01
```
List all connections NetworkManager has
```sh
nmcli connection show
```
Show settings for network interface {ens01}
```sh
nmcli device show ens01
```
Show status for all devices
```sh
nmcli device status
```
Display devices and status
```sh
nmcli device status
```
Display currently configured hostname
```sh
nmcli general hostname
```
Set hostname to {hostname}
```sh
nmcli general hostname hostname
```
Show overall status of NetworkManager
```sh
nmcli general status
```

### `nmap`
Scan hosts and ports on a network\
Scan hosts from a text file
```sh
nmap -iL hosts.txt
```
Identify a host's operating system
```sh
nmap -A localhost.example.com
```
Determine whether a host has a firewall enabled
```sh
nmap -sA localhost.example.com
```
Scan a specified range of ports
```sh
nmap -p 10-300 localhost.example.com
```
Perform a SYN TCP scan, stealthier than the TCP connect scan
```sh
nmap -sT localhost.example.com
```
Aggressive scan
```sh
nmap -A 192.168.1.0/24
```
Ping scan home network (not bothering with ports)
```sh
nmap -sn 192.168.1.0/24
```
Fast port scan using SYN packets
```sh
nmap -sS -F 192.168.1.0/24
```
Port scan using SYN ("synchronize") packet, first element of TCP handshake
```sh
nmap -sS 192.168.1.0/24
```
Port scan using normal TCP
```sh
nmap -sT 192.168.1.0/24
```
Port scan using UDP
```sh
nmap -sU 192.168.1.0/24
```
Xmas scan
```sh
nmap -sX
```
Scan a range of IPs [<sup>ref</sup>][Sec+ Lab]
```sh
nmap 192.168.27.0/24 > hosts.txt
```
Identify operating system and scan ports using TCP SYN packets [<sup>ref</sup>][Sec+ Lab]
```sh
nmap -O -sS 192.168.27.0/24 > hosts.txt
```

### `nslookup`
Perform a DNS lookup in an interactive shell with cleaner output than **dig**. Enter a domain name and you get output in two sections. 
Retrieve IP address of {host}
```sh
nslookup host
```
Get IP address of a website
```
nslookup url
```
Get only nameservers
```
nslookup -type=ns url
```
Get only MX records
```
nslookup -type=mx url
```
Get Start of Authority (SOA) record
```
nslookup -type=soa url
```
Display all available records
```
nslookup -type=any url
```
Perform reverse DNS lookup on {ipaddress}
```
nslookup ipaddress
```
Specify port {portno} in the lookup
```
nslookup -port=portno url
```
### `rfkill`
[rfkill block]:                         #rfkill                        '```&#10;$ rfkill block&#10;```&#10;Disable specified devices'
[rfkill list]:                          #rfkill                        '```&#10;$ rfkill list&#10;```&#10;List the current state of all available devices using `rfkill`'
[rfkill unblock]:                       #rfkill                        '```&#10;$ rfkill unblock&#10;```&#10;Enable specified device'

[`block`][rfkill block] 
[`list`][rfkill list] 
[`unblock`][rfkill unblock] 

Tool for enabling and disabling wireless devices

Unblock Bluetooth, if it is blocked [<sup>ref</sup>][https://computingforgeeks.com/connect-to-bluetooth-device-from-linux-terminal/]
```sh
rfkill unblock bluetooth
```
### `route`
[route -&#67;]:                 #route                         '```&#10;$ route -C&#10;```&#10;Display the kernel routing cache&#10;Haeder, Adam. _LPI Linux Certification in a Nutshell_. 2010.: 388'
[route -&#70;]:                 #route                         '```&#10;$ route -F&#10;```&#10;Display the kernel routing table&#10;Haeder, Adam. _LPI Linux Certification in a Nutshell_. 2010.: 388'
[route -&#104;]:                #route                         '```&#10;$ route -h&#10;```&#10;Display a usage message&#10;Haeder, Adam. _LPI Linux Certification in a Nutshell_. 2010.: 388'
[route -&#110;]:                #route                         '```&#10;$ route -n&#10;```&#10;Numeric mode; do not resolve hostnames&#10;Haeder, Adam. _LPI Linux Certification in a Nutshell_. 2010.: 388'
[route -&#118;]:                #route                         '```&#10;$ route -v&#10;```&#10;Verbose output&#10;Haeder, Adam. _LPI Linux Certification in a Nutshell_. 2010.: 388'

<code>&nbsp;</code>   <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> [`h`][route -&#104;] <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> [`n`][route -&#110;] <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> [`v`][route -&#118;] <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code>  <br><code>&nbsp;</code>&nbsp;<code>&nbsp;</code> <code>&nbsp;</code> [`C`][route -&#67;] <code>&nbsp;</code> <code>&nbsp;</code> [`F`][route -&#70;] <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> 

### `ss`
[ss -&#108;]:                   #ss                            '```&#10;$ ss -l&#10;$ ss --listening&#10;```&#10;Display sockets that are listening'
[ss -&#97;]:                    #ss                            '```&#10;$ ss -a&#10;$ ss --all&#10;```&#10;Display both listening sockets and established connections'
[ss -&#116;]:                   #ss                            '```&#10;$ ss -t&#10;$ ss --tcp&#10;```&#10;Display TCP sockets'
[ss -&#117;]:                   #ss                            '```&#10;$ ss -u&#10;$ ss --udp&#10;```&#10;Display UDP sockets'
[ss -&#120;]:                   #ss                            '```&#10;$ ss -x&#10;$ ss --unix&#10;```&#10;Display Unix domain sockets'

<code>&nbsp;</code> [`a`][ss -&#97;] <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> [`l`][ss -&#108;] <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> [`t`][ss -&#116;] [`u`][ss -&#117;] <code>&nbsp;</code> <code>&nbsp;</code> [`x`][ss -&#120;] <code>&nbsp;</code> <code>&nbsp;</code> 

Options are of two kinds:
1. Connection type (listening or established)
2. Protocol type

Display port numbers instead of protocol names
```
ss -n
```
```
ss --numeric
```
Do **name** lookups and display **all** information
```
ss -an
```
Display all active TCP sessions
```
ss -atp
```
Display active TCP sessions
```
ss -tp
```
Display routing table (cf. `ip route`)
```
ss --route
```
Display programs with open ports 
```
ss --program
```
Show all running servers 
"Tuna please"
```
ss -tunapl
```
Do name lookups and display all information
```sh
ss -an
ss --all --numeric
```
Display all sessions, filtering to just TCP that are actively listening
```sh
ss -atp
ss --all --tcp --processes
```
Display active TCP connections
```sh
ss -tp
ss --tcp --processes
```
### `tcpdump`
Inspect actual IP packets

All network data will be displayed to STDOUT
```
tcpdump -i eth0   
```
Set snapshot length of capture (default 65,535B)
```sh
tcpdump -s
```
### `traceroute`
<!-- `traceroute` options -->
[traceroute -&#102;]:           #traceroute                    '```&#10;$ traceroute -&#102; $TTL&#10;```&#10;Set time-to-live value to `$TTL` (1 by default)'
[traceroute -&#105;]:           #traceroute                    '```&#10;$ traceroute -&#105;&#10;```&#10;Choose interface to be used'
[traceroute -&#110;]:           #traceroute                    '```&#10;$ traceroute -&#110;&#10;```&#10;Display numeric addresses instead of names'
[traceroute -&#115;]:           #traceroute                    '```&#10;$ traceroute -&#115;&#10;```&#10;Choose source address'
[traceroute -&#84;]:            #traceroute                    '```&#10;$ traceroute -T&#10;```&#10;Use TCP SYN packets for path trace'
[traceroute -&#116;]:           #traceroute                    '```&#10;$ traceroute -t&#10;```&#10;Set "type of service (ToS)" flag'
[traceroute -&#118;]:           #traceroute                    '```&#10;$ traceroute -v&#10;```&#10;Verbose output'
[traceroute -&#119;]:           #traceroute                    '```&#10;$ traceroute -w $N&#10;```&#10;Set timeout on returned ICMP packets to `$N` seconds (5 by default)'

<code>&nbsp;</code>   <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> [`f`][traceroute -&#102;] <code>&nbsp;</code> <code>&nbsp;</code> [`i`][traceroute -&#105;] <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> [`n`][traceroute -&#110;] <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> [`s`][traceroute -&#115;] [`t`][traceroute -&#116;] <code>&nbsp;</code> [`v`][traceroute -&#118;] [`w`][traceroute -&#119;] <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code>  <br><code>&nbsp;</code>&nbsp;<code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> [`T`][traceroute -&#84;] <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> 


[https://gist.github.com/zentralwerkstatt/9e6c83e757cdfe430d6710585b2275c7]: https://gist.github.com/zentralwerkstatt/9e6c83e757cdfe430d6710585b2275c7 "GitHub Gist - SSH into Linux Subsystem for Windows"]
[Cannon]: https://github.com/jasper-zanjani/notes/master/sources/clkf.md "Cannon, Jason. _Command Line Kung Fu_."

## Package managers
[`add-apt-repository`][add-apt-repository] 
[`alien`][alien] 
[`apt`][apt] 
[`apt-cache`][apt-cache] 
[`apt-get`][apt-get] 
[apt-key][apt-key]
[`brew`][brew] 
[`dnf`][dnf] 
[`dpkg`][dpkg] 
[`dpkg-reconfigure`][dpkg-reconfigure] 
[`dselect`][dselect] 
[galliumos-repodist][galliumos-repodist]
[`gem`][gem] 
[`pacman`][pacman] 
[`pip`][pip] 
`pydoc`
[`rpm`][rpm] 
[`snap`][snap] 
[`yay`][yay] 
[`yum`][yum] 
[`yumdownloader`][yumdownloader] 
[`zypper`][zypper] 


### `alien`
<!-- `alien` options -->
[alien -&#105;]:                #alien                         '```&#10;$ alien -&#105;&#10;```&#10;Automatically install the output package and remove the converted package file'
[alien -&#114;]:                #alien                         '```&#10;$ alien -&#114;&#10;```&#10;Convert package to RPM format'
[alien -&#116;]:                #alien                         '```&#10;$ alien -&#116;&#10;```&#10;Convert package to a `gzip` tar archive'

[`i`][alien -&#105;] [`r`][alien -&#114;] [`t`][alien -&#116;]  

### `apt`
<!-- `apt` commands -->
[apt dist-upgrade]:             #apt                 '```&#10;$ apt dist-upgrade&#10;```&#10;Upgrade distribution'
[apt install]:                  #apt                 '```&#10;$ apt install $PACKAGE&#10;```&#10;Install `$PACKAGE`'
[apt list]:                     #apt                 '```&#10;$ apt list $PATTERN&#10;```&#10;Search for packages matching `$PATTERN`'
[apt remove]:                   #apt                 '```&#10;$ apt remove $PACKAGE&#10;```&#10;Remove `$PACKAGE'
[apt update]:                   #apt                 '```&#10;$ apt update&#10;```&#10;Update package database'
[apt upgrade]:                  #apt                 '```&#10;$ apt upgrade&#10;```&#10;Upgrade all packages'


[`dist-upgrade`][apt dist-upgrade] [`install`][apt install] [`list`][apt list] [`remove`][apt remove] [`update`][apt update] [`upgrade`][apt upgrade] 

### `apt-cache`

<!-- `apt-cache` commands -->
[apt-cache dump]:               #apt-cache           '```&#10;$ apt-cache dump&#10;```&#10;Display basic information about each available package and its dependencies'
[apt-cache search]:             #apt-cache           '```&#10;$ apt-cache search&#10;```&#10;Display all packages with the search term listed in the package name or description'
[apt-cache showpkg]:            #apt-cache           '```&#10;$ apt-cache showpkg&#10;```&#10;Display information about a package'
[apt-cache stats]:              #apt-cache           '```&#10;$ apt-cache stats&#10;```&#10;Display statistics about the package cache'
[apt-cache showsrc]:            #apt-cache           '```&#10;$ apt-cache showsrc&#10;```&#10;Display information about a source package'
[apt-cache depends]:            #apt-cache           '```&#10;$ apt-cache depends&#10;```&#10;Display dependencies of a package'
[apt-cache rdepends]:           #apt-cache           '```&#10;$ apt-cache rdepends&#10;```&#10;Display reverse dependencies of a package, i.e. what packages for which this package is a dependency.'


[`depends`][apt-cache depends] [`dump`][apt-cache dump] [`rdepends`][apt-cache rdepends] [`search`][apt-cache search] [`showpkg`][apt-cache showpkg] [`showsrc`][apt-cache showsrc] [`stats`][apt-cache stats] 

Display package information regarding package cache

### apt-key
Add key specified by apt in error message <sup>[itsfoss.com](https://itsfoss.com/solve-gpg-error-signatures-verified-ubuntu/ "How to fix \"The following signatures couldn't be verified\" error in Ubuntu")</sup>
sudo apt-key adv --keyserver keyserver.ubuntu.com --recv-keys 68980A0EA10B4DE8
### `add-apt-repository`
Add a repository
```sh
add-apt-repository "deb [arch=amd64] https://download.docker.com/linux/ubuntu $(lsb_release -cs) stable"
add-apt-repository "deb http://security.ubuntu.com/ubuntu trusty-security main universe"
```
Convert Ubuntu to Regolith Linux [<sup>LPM 231</sup>][LPM 231 Regolith Linux]
```sh
add-apt-repository -y ppa:kgilmer/regolith-stable
apt updatelib
apt install regolith-desktop
```
### `apt-key`
Add a public GPG key to keyring
```sh
# Google Cloud SDK
curl https://packages.cloud.google.com/apt/doc/apt-key.gpg | sudo apt-key add -

# Docker
curl -fsSL https://download.docker.com/linux/ubuntu/gpg | sudo apt-key add -
```
Install key from Mono
```sh
apt-key adv --keyserver hkp://keyserver.ubuntu.com:80 --recv-keys 3FA7E0328081BFF6A14DA29AA6A19B38D3D831EF
```
### `dnf`
View all `dnf` commands
```sh
dnf history
```
View all packages installed by user
```sh
dnf history userinstalled
```
Display information about a **package group** [<sup>ref</sup>][https://docs.fedoraproject.org/en-US/quick-docs/getting-started-with-virtualization/]
```sh
dnf groupinfo virtualization
```
Install a package group [<sup>ref</sup>][https://docs.fedoraproject.org/en-US/quick-docs/getting-started-with-virtualization/]
```sh
dnf install @virtualization
```
Install a package group, including optional packages [<sup>ref</sup>][https://docs.fedoraproject.org/en-US/quick-docs/getting-started-with-virtualization/]
```sh
dnf group install --with-optional virtualization
```
### `dpkg`
<!-- `dpkg` options -->
[dpkg -&#67;]:                  #dpkg                          '```&#10;$ dpkg -C&#10;$ dpkg --audit&#10;```&#10;Check for broken packages'
[dpkg -&#69;]:                  #dpkg                          '```&#10;$ dpkg -E&#10;```&#10;Do not overwrite a previously installed package of the same version&#10;Haeder, Adam. _LPI Linux Certification in a Nutshell_. 2010.: 47'
[dpkg -&#71;]:                  #dpkg                          '```&#10;$ dpkg -G&#10;```&#10;Do not overwrite a previously installed package with an older version of that same package&#10;Haeder, Adam. _LPI Linux Certification in a Nutshell_. 2010.: 47'
[dpkg -&#73;]:                  #dpkg                          '```&#10;$ dpkg -I $PACKAGE&#10;$ dpkg --info $PACKAGE&#10;```&#10;Show information about `$PACKAGE`'
[dpkg -&#105;]:                 #dpkg                          '```&#10;$ dpkg -i $PACKAGE&#10;$ dpkg --install $PACKAGE&#10;```&#10;Install `$PACKAGE`&#10;Haeder, Adam. _LPI Linux Certification in a Nutshell_. 2010.: 48'
[dpkg -&#108;]:                 #dpkg                          '```&#10;$ dpkg -l $PATTERN&#10;$ dpkg --list $PATTERN&#10;```&#10;Display information for installed package names that match `$PATTERN`&#10;Haeder, Adam. _LPI Linux Certification in a Nutshell_. 2010.: 48'
[dpkg -&#76;]:                  #dpkg                          '```&#10;$ dpkg -L $PACKAGE&#10;$ dpkg --listfiles $PACKAGE&#10;```&#10;List files installed from `$PACKAGE`&#10;Haeder, Adam. _LPI Linux Certification in a Nutshell_. 2010.: 48'
[dpkg -&#112;]:                 #dpkg                          '```&#10;$ dpkg -p $PACKAGE&#10;$ dpkg --print-avail $PACKAGE&#10;```&#10;Show details about `$PACKAGE`'
[dpkg -&#80;]:                  #dpkg                          '```&#10;$ dpkg -P $PACKAGE&#10;$ dpkg --purge $PACKAGE&#10;```&#10;Remove everything for `$PACKAGE`&#10;Haeder, Adam. _LPI Linux Certification in a Nutshell_. 2010.: 48'
[dpkg -&#82;]:                  #dpkg                          '```&#10;$ dpkg -R&#10;$ dpkg --recursive&#10;```&#10;Recursively process package files in specified subdirectories&#10;Haeder, Adam. _LPI Linux Certification in a Nutshell_. 2010.: 48'
[dpkg -&#114;]:                 #dpkg                          '```&#10;$ dpkg -r $PACKAGE&#10;$ dpkg --remove $PACKAGE&#10;```&#10;Remove everything except configuration files for `$PACKAGE`&#10;Haeder, Adam. _LPI Linux Certification in a Nutshell_. 2010.: 48'
[dpkg -&#83;]:                  #dpkg                          '```&#10;$ dpkg -S $PATTERN&#10;$ dpkg --search $PATTERN&#10;```&#10;Search for a filename matching `$PATTERN` from installed packages&#10;Haeder, Adam. _LPI Linux Certification in a Nutshell_. 2010.: 48'
[dpkg -&#115;]:                 #dpkg                          '```&#10;$ dpkg -s $PACKAGE&#10;$ dpkg --status $PACKAGE&#10;```&#10;Report the status of `$PACKAGE`&#10;Haeder, Adam. _LPI Linux Certification in a Nutshell_. 2010.: 48'
[dpkg --configure]:             #dpkg                          '```&#10;$ dpkg --configure&#10;```&#10;Configure an unpacked package. This involves setup of configuration files&#10;Haeder, Adam. _LPI Linux Certification in a Nutshell_. 2010.: 48'
[dpkg --get-selections]:        #dpkg                          '```&#10;$ dpkg --get-selections&#10;```&#10;Display list of package selections'
[dpkg --print-avail]:           #dpkg                          '```&#10;$ dpkg --print-avail $PACKAGE&#10;```&#10;Display details found in /var/lib/dpkg/available about `$PACKAGE`&#10;Haeder, Adam. _LPI Linux Certification in a Nutshell_. 2010.: 48'
[dpkg --unpack]:                #dpkg                          '```&#10;$ dpkg --unpack $PACKAGE&#10;```&#10;Unpack `$PACKAGE` but do not install the package it contains&#10;Haeder, Adam. _LPI Linux Certification in a Nutshell_. 2010.: 48'

<code>&nbsp;</code>  <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> [`i`][dpkg -&#105;] <code>&nbsp;</code> <code>&nbsp;</code> [`l`][dpkg -&#108;] <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> [`p`][dpkg -&#112;] <code>&nbsp;</code> [`r`][dpkg -&#114;] [`s`][dpkg -&#115;] <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code>  <br><code>&nbsp;</code>&nbsp;<code>&nbsp;</code> <code>&nbsp;</code> [`C`][dpkg -&#67;] <code>&nbsp;</code> [`E`][dpkg -&#69;] <code>&nbsp;</code> [`G`][dpkg -&#71;] <code>&nbsp;</code> [`I`][dpkg -&#73;] <code>&nbsp;</code> <code>&nbsp;</code> [`L`][dpkg -&#76;] <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> [`P`][dpkg -&#80;] <code>&nbsp;</code> [`R`][dpkg -&#82;] [`S`][dpkg -&#83;] <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code>  <br> [`configure`][dpkg --configure] [`get-selections`][dpkg --get-selections] [`print-avail`][dpkg --print-avail] [`unpack`][dpkg --unpack]


### `dpkg-reconfigure`
Run a package's configuration script after it has already been installed.

Change the time zone on a Debian based system using package-based tools
```sh
dpkg-reconfigure tzdata
```
### galliumos-repodist
Enable "testing" and "prerelease" repositories <sup>[wiki.galliumos.org](https://wiki.galliumos.org/Repositories "Repositories")</sup>

sudo galliumos-repodist --enable prerelease
sudo galliumos-repodist --enable testing
sudo galliumos-update


### `gem`
Install a Ruby `$PACKAGE`
```sh
gem install $PACKAGE
```
Display currently installed Ruby packages
```sh
gem list
```
Remove `$PACKAGE`
```sh
gem uninstall package
```
Update `$PACKAGE`
```sh
gem update package
```
### `pacman`
Option  | POSIX option            | Effect
:---    | :---                    | :---
`Q`     | `--query`               | list all installed packages
`-R`    |                         | remove {pkg}, but leave dependencies
`-Qe`   |                         | list programs explicitly installed by user or program command
`-Qeq`  |                         | list only program names explicitly installed
`-Qm`   |                         | list programs only installed from AUR
`-Qn`   |                         | list programs only installed from main repositories
`-Qdt`  |                         | list dependencies no longer needed (orphans)
`-Ql`   | `--query` `--list`      | list all files owned by a package
`-S`    | `--sync`                | install {pkg}
`-Sy`   |                         | synchronize package database 
`-Su`   |                         | update programs 
`-Syu`  |                         | sync package database (`Sy`) and upgrade all programs (`u`) (equivalent to `apt-get update && apt-get upgrade`)
`-Syy`  |                         | force double-check of repositories
`-Syyuw` |                        | downloads programs but doesn't install them, for the option of manual installation
`-Rs`   |                         | remove {pkg} as well as its dependencies
`-Rns`  |                         | remove {pkg}, dependencies, as well as config files 
List installed packages
```sh
pacman -Q
pacman --query
```
List all orphaned dependencies (no longer needed)
```sh
pacman -Qdt
pacman --query --deps --unrequired
```
List only explicitly installed packages and versions
```sh
pacman -Qe
pacman --query --explicit
```
List explicitly installed packages, limiting output to program names
```sh
pacman -Qeq
pacman --query --explicit --quiet
```
List all packages installed from the AUR
```sh
pacman -Qm
pacman --query --foreign
```
List all packages installed from main repos
```sh
pacman -Qn
pacman --query --native
```
Find which package owns {file}
```sh
pacman -Qo file
pacman --query --owns file
```
List all install packages, filtering output to packages that are out-of-date on the local system
```sh
pacman -Qu
pacman --query --upgrades
```
Remove {package}
```sh
pacman -R package
pacman --remove package
```
Remove {package}, dependencies, and config files
```sh
pacman -Rns package
pacman --remove --recursive --nosave
```
Remove {package} as well as its dependencies
```sh
pacman -Rs
pacman --remove --recursive
```
Install {pkg} from the AUR
```sh
pacman -S package
pacman --sync package
```
Remove all packages from the cache as well as unused sync databases
```sh
pacman -Scc
pacman --sync --clean --clean
```
Display information about {package}
```sh
pacman -Si package
pacman --sync --info package
```
Search for {pkg} in AUR repos
```sh
pacman -Ss package
pacman --sync --search package
```
Search for packages matching {searchexpression}
```sh
pacman -Ss pattern
pacman --sync --search pattern
```
Update package database
```sh
pacman -Sy
pacman --sync --refresh
```
Update all packages from AUR and official repos
```sh
pacman -Syu
pacman --sync --refresh --sysupgrade
```
Force refresh of all package databases, even if they appear to be up-to-date
```sh
pacman -Syy
pacman --sync --refresh --refresh
```
Download program updates but don't install them
```sh
pacman -Syyuw
pacman --sync --refresh --refresh --sysupgrade --downloadonly
```
Get number of total installed packages
```sh
pacman -Q | wc -l
```
### `pip`
Display installed packages
```sh
pip list
```
Display information about {package}
```sh
pip show package
```
### `pydoc`
Display all installed Python modules
```sh
pydoc modules
```
### `rpm`

<!-- `rpm` options -->
[rpm -&#97;]:                   #rpm                           '```&#10;$ rpm -a&#10;$ rpm --all&#10;```&#10;In query mode, display a list of all packages installed on the system&#10;Haeder, Adam. _LPI Linux Certification in a Nutshell_. 2010.: 55'
[rpm -&#99;]:                   #rpm                           '```&#10;$ rpm -c $PACKAGE&#10;$ rpm --configfiles $PACKAGE&#10;```&#10;List only configuration files installed with specified package&#10;Haeder, Adam. _LPI Linux Certification in a Nutshell_. 2010.: 56'
[rpm -&#100;]:                  #rpm                           '```&#10;$ rpm -d $PACKAGE&#10;$ rpm --docfiles $PACKAGE&#10;```&#10;List only documentation files installed with specified package&#10;Haeder, Adam. _LPI Linux Certification in a Nutshell_. 2010.: 56'
[rpm -&#101;]:                  #rpm                           '```&#10;$ rpm -e $PACKAGE&#10;$ rpm --erase $PACKAGE&#10;```&#10;Remove specified package, including config files&#10;Haeder, Adam. _LPI Linux Certification in a Nutshell_. 2010.: 56'
[rpm -&#102;]:                  #rpm                           '```&#10;$ rpm -f $FILENAME&#10;$ rpm --file $FILENAME&#10;```&#10;In query mode, display the package that contains a particular file&#10;Haeder, Adam. _LPI Linux Certification in a Nutshell_. 2010.: 55'
[rpm -&#104;]:                  #rpm                           '```&#10;$ rpm -h&#10;$ rpm --hash&#10;```&#10;Prints a string of 50 hash marks during installation as a progress indicator&#10;Haeder, Adam. _LPI Linux Certification in a Nutshell_. 2010.: 54'
[rpm -&#105;]:                  #rpm                           '```&#10;$ rpm -i $PACKAGE&#10;$ rpm --install $PACKAGE&#10;```&#10;Install specified packages&#10;Haeder, Adam. _LPI Linux Certification in a Nutshell_. 2010.: 56'
[rpm -&#73;]:                   #rpm                           '```&#10;$ rpm -I $PACKAGE&#10;```&#10;Display information about specified package&#10;Haeder, Adam. _LPI Linux Certification in a Nutshell_. 2010.: 56'
[rpm -&#75;]:                   #rpm                           '```&#10;$ rpm -K $PACKAGE&#10;```&#10;Verify integrity of specified package'
[rpm -&#108;]:                  #rpm                           '```&#10;$ rpm -l $PACKAGE&#10;$ rpm --list $PACKAGE&#10;```&#10;List all files installed with specified package&#10;Haeder, Adam. _LPI Linux Certification in a Nutshell_. 2010.: 56'
[rpm -&#112;]:                  #rpm                           '```&#10;$ rpm -p $FILENAME&#10;```&#10;Query a package file (most useful with `-i`)&#10;Haeder, Adam. _LPI Linux Certification in a Nutshell_. 2010.'
[rpm -&#113;]:                  #rpm                           '```&#10;$ rpm -q $PACKAGE&#10;$ rpm --query $PACKAGE&#10;```&#10;Query for specified package'
[rpm -&#82;]:                   #rpm                           '```&#10;$ rpm -R $PACKAGE&#10;$ rpm --requires $PACKAGE&#10;```&#10;List packages on which this package depends&#10;Haeder, Adam. _LPI Linux Certification in a Nutshell_. 2010.: 56'
[rpm -&#115;]:                  #rpm                           '```&#10;$ rpm -s&#10;```&#10;Display the state of each file that was installed by the specified package (`normal`, `not installed`, or `replaced`)'
[rpm -&#85;]:                   #rpm                           '```&#10;$ rpm -U $PACKAGE&#10;$ rpm --upgrade $PACKAGE&#10;```&#10;Upgrade specified package'
[rpm -&#86;]:                   #rpm                           '```&#10;$ rpm -V&#10;$ rpm --verify&#10;```&#10;Compare files from installed packages against their expected configuration from the RPM database.&#10;Haeder, Adam. _LPI Linux Certification in a Nutshell_. 2010.: 58'
[rpm -&#118;]:                  #rpm                           '```&#10;$ rpm -v&#10;```&#10;Verbose output&#10;Haeder, Adam. _LPI Linux Certification in a Nutshell_. 2010.: 54'
[rpm --force]:                  #rpm                           '```&#10;$ rpm --force&#10;```&#10;Allows the replacement of existing packages and of files from previously installed packages; for upgrades, it allows the replacement of a newer package with an older one.&#10;Equivalent to using all of the following options:&#10;  `--replacepkgs`&#10;  `--replacefiles`&#10;  `--oldpackage`&#10;Haeder, Adam. _LPI Linux Certification in a Nutshell_. 2010.: 54'
[rpm --nodeps]:                 #rpm                           '```&#10;$ rpm --nodeps&#10;```&#10;Allows you to install a package without checking for dependencies.&#10;Haeder, Adam. _LPI Linux Certification in a Nutshell_. 2010.: 54'
[rpm --nofiles]:                #rpm                           '```&#10;$ rpm --nofiles&#10;```&#10;In verify mode, ignore missing files&#10;Haeder, Adam. _LPI Linux Certification in a Nutshell_. 2010.: 58'
[rpm --nomd5]:                  #rpm                           '```&#10;$ rpm --nomd5&#10;```&#10;In verify mode, ignore MD5 checksum errors&#10;Haeder, Adam. _LPI Linux Certification in a Nutshell_. 2010.: 58'
[rpm --nopgp]:                  #rpm                           '```&#10;$ rpm --nopgp&#10;```&#10;In verify mode, ignore PGP checking errors&#10;Haeder, Adam. _LPI Linux Certification in a Nutshell_. 2010.: 58'
[rpm --provides]:               #rpm                           '```&#10;$ rpm --provides $PACKAGE&#10;```&#10;List which capabilities the specified package provides'
[rpm --test]:                   #rpm                           '```&#10;$ rpm --test&#10;```&#10;Runs through all the motions except for actually writing files; useful to verify that a package will install correctly prior to making the attempt&#10;Haeder, Adam. _LPI Linux Certification in a Nutshell_. 2010.: 54'

<code>&nbsp;</code>  [`a`][rpm -&#97;] <code>&nbsp;</code> [`c`][rpm -&#99;] [`d`][rpm -&#100;] [`e`][rpm -&#101;] [`f`][rpm -&#102;] <code>&nbsp;</code> [`h`][rpm -&#104;] [`i`][rpm -&#105;] <code>&nbsp;</code> <code>&nbsp;</code> [`l`][rpm -&#108;] <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> [`p`][rpm -&#112;] [`q`][rpm -&#113;] <code>&nbsp;</code> [`s`][rpm -&#115;] <code>&nbsp;</code> <code>&nbsp;</code> [`v`][rpm -&#118;] <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code>  <br><code>&nbsp;</code>&nbsp;<code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> [`I`][rpm -&#73;] <code>&nbsp;</code> [`K`][rpm -&#75;] <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> [`R`][rpm -&#82;] <code>&nbsp;</code> <code>&nbsp;</code> [`U`][rpm -&#85;] [`V`][rpm -&#86;] <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> <br>[`force`][rpm --force] [`nodeps`][rpm --nodeps] [`nofiles`][rpm --nofiles] [`nomd5`][rpm --nomd5] [`nopgp`][rpm --nopgp] [`provides`][rpm --provides] [`test`][rpm --test] 


Query repos for information on {package}
```sh
rpm -qi package
rpm --query --info package
```
Upgrade or install {package}, with progress bars
```sh
rpm -Uvh package
rpm --upgrade --verbose --hash package
```
Display version of Fedora
```sh
rpm -E %fedora
```
### `snap`
[snap disable]:                       #snap                          '```&#10;$ snap disable $SNAP&#10;```&#10;Disable snap'
[snap enable]:                        #snap                          '```&#10;$ snap enable $SNAP&#10;```&#10;Enable disabled snap'
[snap info]:                          #snap                          '```&#10;$ snap info $SNAP&#10;```&#10;Display information about `$SNAP`'
[snap install]:                       #snap                          '```&#10;$ snap install $SNAP&#10;```&#10;Install snap'
[snap logs]:                          #snap                          '```&#10;$ snap logs $SNAP&#10;```&#10;Display logs of snap'
[snap refresh]:                       #snap                          '```&#10;$ snap refresh $SNAP&#10;```&#10;Check for snap updates'
[snap remove]:                        #snap                          '```&#10;$ snap remove $SNAP&#10;```&#10;Uninstall snap'

[`disable`][snap disable] 
[`enable`][snap enable] 
[`info`][snap info] 
[`install`][snap install] 
[`logs`][snap logs] 
[`refresh`][snap refresh] 
[`remove`][snap remove] 

### `yay`
[yay -&#81;]: #yay '```&#10;$ yay -Q&#10;$ yay --query&#10;```&#10;'
[yay -&#117;]: #yay '```&#10;$ yay -u&#10;$ yay --upgrades&#10;```&#10;'
[yay -&#83;]: #yay '```&#10;$ yay -S&#10;$ yay --sync&#10;```&#10;'
[yay -&#105;]: #yay '```&#10;$ yay -i&#10;$ yay --info&#10;```&#10;'
[yay -&#115;]: #yay '```&#10;$ yay -s&#10;$ yay --search&#10;```&#10;'
[yay -&#121;]: #yay '```&#10;$ yay -y&#10;$ yay --refresh&#10;```&#10;'
[yay -&#117;]: #yay '```&#10;$ yay -u&#10;$ yay --upgrades&#10;```&#10;'
[yay -&#99;]: #yay '```&#10;$ yay -c&#10;$ yay --clean&#10;```&#10;'
[yay -&#80;]: #yay '```&#10;$ yay -P&#10;$ yay --show&#10;```&#10;'

<code>&nbsp;</code>   <code>&nbsp;</code> <code>&nbsp;</code> [`c`][yay -&#99;] <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> [`i`][yay -&#105;] <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> [`s`][yay -&#115;] <code>&nbsp;</code> [`u`][yay -&#117;] <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> [`y`][yay -&#121;] <code>&nbsp;</code>  <br><code>&nbsp;</code>&nbsp;<code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> [`P`][yay -&#80;] [`Q`][yay -&#81;] <code>&nbsp;</code> [`S`][yay -&#83;] <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> 

### `yum`
[yum -&#121;]: #yum '```&#10;$ yum -y&#10;$ yum --assumeyes&#10;```&#10;Respond to any prompt with "yes" automatically'
[yum -&#120;]: #yum '```&#10;$ yum -x&#10;$ yum --exclude&#10;```&#10;Exclude specific packages from updates'


<!-- `yum` commands -->
[yum clean all]:                #yum                 '```&#10;$ yum clean all&#10;```&#10;Clear cache'
[yum erase]:                    #yum                 '```&#10;$ yum erase $PACKAGE&#10;```&#10;Remove package as well as the cached package'
[yum groupinstall]:             #yum                 '```&#10;$ yum groupinstall $GROUP&#10;```&#10;Install package group'
[yum groupremove]:              #yum                 '```&#10;$ yum groupremove $GROUP&#10;```&#10;Remove package group'
[yum history]:                  #yum                 '```&#10;$ yum history&#10;```&#10;View command history'
[yum info]:                     #yum                 '```&#10;$ yum info $PACKAGE&#10;```&#10;Query repos for information on `$PACKAGE`'
[yum install]:                  #yum                 '```&#10;$ yum install $PACKAGE&#10;```&#10;Install package'
[yum list]:                     #yum                 '```&#10;$ yum list&#10;```&#10;List all available packages in database'
[yum list installed]:           #yum                 '```&#10;$ yum list installed&#10;```&#10;List all installed packages'
[yum provides]:                 #yum                 '```&#10;$ yum provides $FILE&#10;```&#10;Find what package a configuration `$FILE` belongs to'
[yum remove]:                   #yum                 '```&#10;$ yum remove $PACKAGE&#10;```&#10;Remove package'
[yum repolist]:                 #yum                 '```&#10;$ yum repolist&#10;```&#10;Display repositories'
[yum repolist all]:             #yum                 '```&#10;$ yum repolist all&#10;```&#10;Display both enabled and disabled repositories'
[yum search]:                   #yum                 '```&#10;$ yum search $PATTERN&#10;```&#10;Search for package name matching `$PATTERN`'
[yum shell]:                    #yum                 '```&#10;$ yum shell&#10;```&#10;Interactive shell'
[yum update]:                   #yum                 '```&#10;$ yum update&#10;```&#10;Upgrade installed packages'

<code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> [`x`][yum -&#120;] [`y`][yum -&#121;] <code>&nbsp;</code> 

[`clean all`][yum clean all] 
[`erase`][yum erase] 
[`groupinstall`][yum groupinstall] 
[`groupremove`][yum groupremove] 
[`history`][yum history] 
[`info`][yum info] 
[`install`][yum install] 
[`list`][yum list] 
[`list installed`][yum list installed] 
[`provides`][yum provides] 
[`remove`][yum remove] 
[`repolist`][yum repolist] 
[`repolist all`][yum repolist all] 
[`search`][yum search] 
[`shell`][yum shell] 
[`update`][yum update] 

## Process control
[`bg`][bg] 
[`fg`][fg] 
[`jobs`][jobs] 
[`kill`][kill] 
[`killall`][killall] 
[`lsns`][lsns] 
[`nice`][nice] 
[`nohup`][nohup] 
[`pgrep`][pgrep] 
[`pidof`][pidof] 
[`pkill`][pkill] 
[`ps`][ps] 
[`pstree`][pstree] 
[`renice`][renice] 
[`strace`][strace] 
[`top`][top] 

- every process has a parent; a process can **spawn** children
- a process runs in its own **user address space**, a protected space which can't be disturbed by other users
- all processes on a Linux system are child processes of a common parent: the `init` process which is executed by the kernel at boot time (PID 1)
- every Linux process inherits the environment (PATH variable, etc) and other attributes of its parent process

Process creation:
1. `FORK` copy process invoking it as `fork()`
2. `EXEC` parent then overwrites this copy with the program that has to be executed which replaces or **overlays** the text and data areas as `exec()` system call
3. `WAIT` parent waits for `SIGTERM` signal which the child will send upon completion `wait()` system call

1. **`TEXT SEGMENT`**: executable code
2. **`DATA SEGMENT`**: variables and arrays the program uses during execution
3. **`USER SEGMENT`**: process attributes
  - process ID (PID)
  - real user ID of user who created it (stored in /etc/passwd)
  - real group ID
  - priority

- Internal commands (`cd`, `echo`, etc. and variable assignments) do not spawn child processes
- Shell scripts are executed by spawning a sub-shell, which becomes the script's parent
- External commands are spawned as children of the parent as described above

#### Niceness
Priorities range from 0-19 in `csh` (10 is default); higher values run at lower priority
```sh
nice
```
View priorities of jobs
```sh
ps -l
```
Run `cmd` at a higher priority
```sh
nice -5 cmd &
```
#### Cgroups
**Control group (cgroups)** is a Linux kernel feature that isolates a collection of processes.
- allow you to allocate resources (CPU time, system memory, network bandwidth, or combinations thereof) among user-defined groups of processes
- like processes, cgroups are hierarchical and inherit attributes from parents, but they from separate trees branching off from `subsystems` (also: `resource controller`, or just `controller`), each of which represent a single system resouce 
  - `blkio` sets limits on input/output access from block devices
  - `cpu` which provides access to the CPU
  - many more...
- different from `namespaces`
  - good for limiting the resources available to a container
  - `systemd` uses cgroups
  - first heard about in Linux Unplugged 289, in the context of Fedora supporting v2 whereas most userspace applications support v1

Process IDs in the same **namespace** can have access to one another, whereas those in different namespaces cannot. Spawning a process in a new namespace prevents it from seeing the host's context, so an interactive shell like `zsh` spawned in its own namespace will report its PID as `1`, even though the host will assign its own PID. This is the concept behind [**containers**](../devops/README.md#containers). [[55](sources.md)]
### `nice`
Run `$CMD` at a nice value of (positive) 10
```sh
nice -10 $CMD
nice -n 10
nice $CMD
```
### `unshare`
Run a program in a namespace **unshared** from its parent process. [<sup>ref</sup>][https://opensource.com/article/19/10/namespaces-and-containers-linux]
```sh
sudo unshare --fork --pid --mount-proc zsh
```

## Remote administration
[`curl`][curl] 
[`ftp`][ftp] 
[`rsync`][rsync] 
[`ssh`][ssh] 
[`ssh-add`][ssh-add] 
[`ssh-agent`][ssh-agent] 
[`ssh-keygen`][ssh-keygen] 
[`ssh-keyscan`][ssh-keyscan] 
[`stty`][stty] 
[`telnet`][telnet] 
[`vncpasswd`][vncpasswd] 
[`vncviewer`][vncviewer] 
[`sshfs`][sshfs] 

#### `curl`
[curl -&#35;]: #curl '```&#10;$ curl -#&#10;$ curl --progress-bar&#10;```&#10;Print progress information as a progress bar instead of as statistics&#10;Robbins, Arnold. _UNIX in a Nutshell_ 4th ed (2005): 50'
[curl -&#67;]: #curl '```&#10;$ curl -C $OFFSET&#10;$ curl --continue-at $OFFSET&#10;```&#10;continue a previous file transfer at `$OFFSET` bytes&#10;Robbins, Arnold. _UNIX in a Nutshell_ 4th ed (2005): 49'
[curl -&#102;]: #curl '```&#10;$ curl -f&#10;$ curl --fail&#10;```&#10;Fail silently upon HTTP server errors. Mainly useful for scripts.&#10;Robbins, Arnold. _UNIX in a Nutshell_ 4th ed (2005): 49'
[curl -&#104;]: #curl '```&#10;$ curl -h&#10;$ curl --help&#10;```&#10;Print a brief help message.&#10;Robbins, Arnold. _UNIX in a Nutshell_ 4th ed (2005): 49'
[curl -&#75;]: #curl '```&#10;$ curl -K $CONFIGFILE&#10;$ curl --config $CONFIGFILE&#10;```&#10;Use `$CONFIGFILE` as the configuration file, instead of the default "$HOME/.curlrc". Use `-` to read configuration information from STDIN.&#10;Robbins, Arnold. _UNIX in a Nutshell_ 4th ed (2005): 49'
[curl -&#109;]: #curl '```&#10;$ curl -m $SECONDS&#10;$ curl --max-time $SECONDS&#10;```&#10;Do not exceed `$SECONDS` for the entire operation.&#10;Robbins, Arnold. _UNIX in a Nutshell_ 4th ed (2005): 50'
[curl -&#77;]: #curl '```&#10;$ curl -M&#10;$ curl --manual&#10;```&#10;Display full help text (> 2400 lines) in the form of a manpage.&#10;Robbins, Arnold. _UNIX in a Nutshell_ 4th ed (2005): 50'
[curl -&#111;]: #curl '```&#10;$ curl -o $FILE&#10;$ curl --output $FILE&#10;```&#10;Write output to `$FILE` instead of to STDOUT&#10;Robbins, Arnold. _UNIX in a Nutshell_ 4th ed (2005): 50'
[curl -&#113;]: #curl '```&#10;$ curl -q&#10;```&#10;When used as the first parameter, do not read "$HOME/.curlrc"&#10;Robbins, Arnold. _UNIX in a Nutshell_ 4th ed (2005): 50'
[curl -&#115;]: #curl '```&#10;$ curl -s&#10;$ curl --silent&#10;```&#10;Do not print a progress meter or any error messages.&#10;Robbins, Arnold. _UNIX in a Nutshell_ 4th ed (2005): 50'
[curl -&#83;]: #curl '```&#10;$ curl -S&#10;$ curl --show-error&#10;```&#10;With `-s`, do display error messages.&#10;Robbins, Arnold. _UNIX in a Nutshell_ 4th ed (2005): 50'
[curl -&#84;]: #curl '```&#10;$ curl -T $FILE&#10;$ curl --upload-file $FILE&#10;```&#10;Upload `$FILE` to the URL on the command line.&#10;Robbins, Arnold. _UNIX in a Nutshell_ 4th ed (2005): 50'
[curl -&#117;]: #curl '```&#10;$ curl -u $USER:$PASSWORD&#10;$ curl --user $USER:$PASSWORD&#10;```&#10;Supply `$USER` and `$PASSWORD` to the server for authentication.&#10;Robbins, Arnold. _UNIX in a Nutshell_ 4th ed (2005): 50'
[curl -&#85;]: #curl '```&#10;$ curl -U $USER:$PASSWORD&#10;$ curl --proxy-user $USER:$PASSWORD&#10;```&#10;Supply `$USER` and `$PASSWORD` to the server for proxy authentication.&#10;Robbins, Arnold. _UNIX in a Nutshell_ 4th ed (2005): 50'
[curl -&#118;]: #curl '```&#10;$ curl -v&#10;$ curl --verbose&#10;```&#10;Be verbose during file retrieval.&#10;Robbins, Arnold. _UNIX in a Nutshell_ 4th ed (2005): 50'
[curl -&#86;]: #curl '```&#10;$ curl -V&#10;$ curl --version&#10;```&#10;Print version and supported-feature information&#10;Robbins, Arnold. _UNIX in a Nutshell_ 4th ed (2005): 50'
[curl -&#120;]: #curl '```&#10;$ curl -x $PROXYHOST:$PORT&#10;$ curl --proxy $PROXYHOST:$PORT&#10;```&#10;Use `$PROXYHOST` (and the optional `$PORT` which is 1080 by default), as the HTTP proxy&#10;Robbins, Arnold. _UNIX in a Nutshell_ 4th ed (2005): 50'
[curl --connect-timeout]: #curl '```&#10;$ curl --connect-timeout $SECONDS&#10;```&#10;Limit connection phase to `$SECONDS` seconds&#10;Robbins, Arnold. _UNIX in a Nutshell_ 4th ed (2005): 49'
[curl --create-dirs]: #curl '```&#10;$ curl --create-dirs&#10;```&#10;When used with `-o`, create local directories as needed&#10;Robbins, Arnold. _UNIX in a Nutshell_ 4th ed (2005): 49'
[curl --disable-epsv]: #curl '```&#10;$ curl --disable-epsv&#10;```&#10;Do not use the `EPSV` FTP command for passive FTP transfer. Normally `curl` tries `EPSV` before `PASV`.&#10;Robbins, Arnold. _UNIX in a Nutshell_ 4th ed (2005): 49'
[curl --ftp-pasv]: #curl '```&#10;$ curl --ftp-pasv&#10;```&#10;Use the FTP `PASV` command (default)&#10;Robbins, Arnold. _UNIX in a Nutshell_ 4th ed (2005): 49'
[curl --limit-rate]: #curl '```&#10;$ curl --limit-rate $SPEED&#10;```&#10;Limit transfers to `$SPEED` (bytes per second by default). Other possible units, placed at the end of the argument, include:&#10;  - `k`,`K`               kilboytes&#10;  - `m`,`M`               megabytes&#10;  - `g`,`G`               gigabytes&#10;&#10;Robbins, Arnold. _UNIX in a Nutshell_ 4th ed (2005): 49'
[curl --max-filesize]: #curl '```&#10;$ curl --max-filesize $BYTES&#10;```&#10;Do not download a file exceeding `$BYTES` in size.&#10;Robbins, Arnold. _UNIX in a Nutshell_ 4th ed (2005): 49'
[curl --url]: #curl '```&#10;$ curl --url $URL&#10;```&#10;Retrieve `$URL`&#10;Robbins, Arnold. _UNIX in a Nutshell_ 4th ed (2005): 50'
[curl -&#79;]: #curl '```&#10;$ curl -O $URL&#10;$ curl --remote-name $URL&#10;```&#10;download `$URL` saving output under the filename indicated by `$URL` itself'
[curl -&#100;]: #curl '```&#10;$ curl -d $NAME=$VALUE&#10;```&#10;Post form-encoded `$NAME` with value `$VALUE`'
[curl -&#76;]: #curl '```&#10;$ curl -L&#10;$ curl --location&#10;```&#10;Follow redirects'

[`#`][curl -&#35;]   <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> [`d`][curl -&#100;] <code>&nbsp;</code> [`f`][curl -&#102;] <code>&nbsp;</code> [`h`][curl -&#104;] <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> [`m`][curl -&#109;] <code>&nbsp;</code> [`o`][curl -&#111;] <code>&nbsp;</code> [`q`][curl -&#113;] <code>&nbsp;</code> [`s`][curl -&#115;] <code>&nbsp;</code> [`u`][curl -&#117;] [`v`][curl -&#118;] <code>&nbsp;</code> [`x`][curl -&#120;] <code>&nbsp;</code> <code>&nbsp;</code>  <br><code>&nbsp;</code>&nbsp;<code>&nbsp;</code> <code>&nbsp;</code> [`C`][curl -&#67;] <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> [`K`][curl -&#75;] [`L`][curl -&#76;] [`M`][curl -&#77;] <code>&nbsp;</code> [`O`][curl -&#79;] <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> [`S`][curl -&#83;] [`T`][curl -&#84;] [`U`][curl -&#85;] [`V`][curl -&#86;] <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code>\
[`connect-timeout`][curl --connect-timeout]
[`create-dirs`][curl --create-dirs]
[`disable-epsv`][curl --disable-epsv]
[`ftp-pasv`][curl --ftp-pasv]
[`limit-rate`][curl --limit-rate]
[`max-filesize`][curl --max-filesize]
[`url`][curl --url]

## Security
[`chcon`][chcon] 
[`getenforce`][getenforce] 
[`getsebool`][getsebool] 
`gpg`
[`restorecon`][restorecon] 
[`semanage`][semanage] 
[`sestatus`][sestatus] 
[`setenforce`][setenforce] 
[`setsebool`][setsebool] 

Display SELinux contexts for processes
```sh
ps auxZ
```
Display SELinux context for files
```sh
ls -Z
```
### `gpg`
Decrypt file
```sh
gpg file.txt
```
Export GPG public key
```sh
gpg --export --output ~/jdoe.pub
```
Import another person's public key
```sh
gpg --import jdoe.pub
```
List available GPG keys
```sh
gpg --list-key
```
Encrypt a file
```sh
gpg --encrypt -r jdoe@dplaptop.lab.itpro.tv ./file.txt
```
Sign {file} without encrypting it (produces file.asc)
```sh
gpg --clearsign file
```
Generate a key
```sh
gpg --generate-key
gpg --gen-key
```
Import another person's public key
```sh
gpg --import ~/jdoe.pub
```
Send keys to {keyserver}
```sh
gpg --send-keys keyIDs --keyserver keyserver
```
### `restorecon`
Restore security context default in the policy
```sh
restorecon -Rv website
```
### `sestatus`
Display status of SELinux
```sh
sestatus
```
### `setenforce`
Change SELinux mode
```sh
setenforce enforcing
setenforce 1
setenforce permissive
setenforce 0
setenforce disabled
```
### `semanage`
Amend policy to add a file context
```sh
semanage fcontext -a -t httpd_sys_content_t website
```
Add a port context
```sh
semanage port -a -t http_port_t -p tcp 8080
```
Display all ports with attached types
```sh
semanage port -l
```
## Shell and environment commands
[`apropos`][apropos] 
[`env`][env] 
[`export`][export] 
[`history`][history] 
[`man`][man] 
[`nohup`][nohup] 
[`pwd`][pwd] 
[`sleep`][sleep] 
[`su`][su] 
[`sudo`][sudo] 
[`tee`][tee] 
`tmux`
[`unalias`][unalias] 
[`watch`][watch] 
[`whatis`][whatis] 
[`where`][where] 
[`whereis`][whereis] 
[`which`][which] 
[`xargs`][xargs] 
#### `screen`
Share your screen session with another user
```sh
screen -x user/session
```
### `stty`
Return number of rows and columns of the terminal
```sh
stty size
```
#### `tmux`
---     | ---
Config  | `~/.tmux.conf`

Change prefix to vim-style `$KEYCOMBO` (`C-b` by default)
```sh
set-option -g prefix $KEYCOMBO
```
Name a new session
```sh
tmux new-session -s 'my rails project'
```
#### `tput`
Return width of current terminal window
```sh
tput cols 
```
Return height of current terminal window
```sh
tput lines
```
#### `watch`
Execute `$CMD` at periods of `$N` seconds, watching its output <sup>CLKF</sup>
```sh
watch $CMD -n $N
```
Check memory usage in megabytes (`-m`) every `5` seconds <sup>Enki</sup>
```sh
watch -n 5 free -m
```
## System administration
[`adduser`][adduser] 
[`chage`][chage] 
[`chgrp`][chgrp] 
[`chmod`][chmod] 
[`edquota`][edquota] 
[`gpasswd`][gpasswd] 
[`groupadd`][groupadd] 
[`groupdel`][groupdel] 
[`groupmod`][groupmod] 
[`groups`][groups] 
[`last`][last] 
[`lastb`][lastb] 
[`passwd`][passwd] 
[`quota`][quota] 
[`quotacheck`][quotacheck] 
[`quotaoff`][quotaoff] 
[`quotaon`][quotaon] 
[`repquota`][repquota] 
`shutdown`
[`su`][su] 
[`sudo`][sudo] 
[`sudoedit`][sudoedit] 
[`timedatectl`][timedatectl] 
[`tzconfig`][tzconfig] 
[`tzselect`][tzselect] 
[`ulimit`][ulimit] 
[`useradd`][useradd] 
[`userdel`][userdel] 
[`usermod`][usermod] 
[`visudo`][visudo] 
[`w`][w] 
[`wall`][wall] 
[`who`][who] 
[`whoami`][whoami] 

**Filesystem access control lists (FACL)** allow you to grant permissions to more than one group, i.e. in cases where more than one department of a corporation needs access to the same files.  They are made up of _access control entries_ (ACE). FACL permissions will be indicated in a `ls -l` command by the presence of a "+" after the symbolic notation for the traditional UGO permissions. **Acl** is a dependency of `systemd`.

To enable it, add ",acl" to options in `fstab` file, then mount/unmount disk. If enabling FACL on root partition, system has to be rebooted.

### `at`
Execute a command at a given time
```sh
echo "cmd" | at time
```
Execute `cmd` at `time`
```sh
at time
> cmd
```
### `chage`
<!-- `chage` options -->
[chage -&#100;]:                #chage                         '```&#10;$ chage -&#100;&#10;```&#10;Change the Last Change field of the /etc/shadow file for the user&#10;Rothwell, William. _CompTIA Linux+ Portable Command Guide_.: 95'
[chage -&#69;]:                 #chage                         '```&#10;$ chage -&#69;&#10;```&#10;Set the Expiration Date field of the /etc/shadow file for the user&#10;Rothwell, William. _CompTIA Linux+ Portable Command Guide_.: 95'
[chage -&#109;]:                #chage                         '```&#10;$ chage -&#109;&#10;```&#10;Change the Min field of the /etc/shadow file for the user&#10;Rothwell, William. _CompTIA Linux+ Portable Command Guide_.: 95'
[chage -&#77;]:                 #chage                         '```&#10;$ chage -&#77;&#10;```&#10;Change the Max field of the /etc/shadow file for the user&#10;Rothwell, William. _CompTIA Linux+ Portable Command Guide_.: 95'
[chage -&#87;]:                 #chage                         '```&#10;$ chage -&#87;&#10;```&#10;Change the Warn field of the /etc/shadow file for the user&#10;Rothwell, William. _CompTIA Linux+ Portable Command Guide_.: 95'
[chage -&#73;]:                 #chage                         '```&#10;$ chage -I&#10;```&#10;Set days of inactivity after a password has expired before account is locked&#10;Haeder, Adam. _LPI Linux Certification in a Nutshell_. 2010.: 417'
[chage -&#108;]:                #chage                         '```&#10;$ chage -l&#10;```&#10;Show password aging information for an account&#10;Haeder, Adam. _LPI Linux Certification in a Nutshell_. 2010.: 417'

<code>&nbsp;</code>   <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> [`d`][chage -&#100;] <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> [`l`][chage -&#108;] [`m`][chage -&#109;] <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code>  <br><code>&nbsp;</code>&nbsp;<code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> [`E`][chage -&#69;] <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> [`I`][chage -&#73;] <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> [`M`][chage -&#77;] <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> [`W`][chage -&#87;] <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> 

### `chgrp`
Change ownership of `$FILE` to `$USER` and `$GROUP`
```sh
chgrp $USER:$GROUP $FILE
```
### `chmod`
Set sticky bit on `$FILE`
```sh
chmod +t $FILE
```
Clear sticky bit on `$FILE`
```sh
chmod -t file
```
Clear SGID bit on `$FILE`
```sh
chmod g-s file
```
Set SGID bit on `$FILE`
```sh
chmod g+s file
```
Clear SUID bit on `$FILE`
```sh
chmod u-s file
```
Set SUID bit on `$FILE`
```sh
chmod u+s file
```
Set `setuid` permission on `$FILE`
```sh
chmod +s file
```
### `chown`
[chown -&#99;]: #chown '```&#10;$ chown -c&#10;$ chown --changes&#10;```&#10;Print information about files that are changed&#10;Robbins, Arnold. _UNIX in a Nutshell_ 4th ed (2005): 38'
[chown -&#102;]: #chown '```&#10;$ chown -f&#10;$ chown --quiet&#10;```&#10;Do not print error messages about files that cannot be changed.&#10;Robbins, Arnold. _UNIX in a Nutshell_ 4th ed (2005): 37'
[chown -&#104;]: #chown '```&#10;$ chown -h&#10;$ chown --no-dereference&#10;```&#10;Change the owner on symbolic links&#10;Robbins, Arnold. _UNIX in a Nutshell_ 4th ed (2005): 37'
[chown -&#72;]: #chown '```&#10;$ chown -H&#10;```&#10;When used with `-R`, if a command-line argument is a symbolic link to a directory, recursively traverse the directory.&#10;Robbins, Arnold. _UNIX in a Nutshell_ 4th ed (2005): 37'
[chown -&#76;]: #chown '```&#10;$ chown -L&#10;```&#10;When used with `-R`, if any symbolic link points to a directory, recursively traverse the directory&#10;Robbins, Arnold. _UNIX in a Nutshell_ 4th ed (2005): 37'
[chown -&#80;]: #chown '```&#10;$ chown -P&#10;```&#10;When used with `-R`, do not follow any symbolic links (default).&#10;Robbins, Arnold. _UNIX in a Nutshell_ 4th ed (2005): 38'
[chown -&#82;]: #chown '```&#10;$ chown -R&#10;$ chown --recursive&#10;```&#10;Recursively descend through the directory, including subdirectories and symbolic links. When used with `-H`, `-L`, and `-P` the latest takes precedence.&#10;Robbins, Arnold. _UNIX in a Nutshell_ 4th ed (2005): 37'
[chown -&#118;]: #chown '```&#10;$ chown -v&#10;$ chown --verbose&#10;```&#10;Verbose output&#10;Robbins, Arnold. _UNIX in a Nutshell_ 4th ed (2005): 38'
[chown --dereference]: #chown '```&#10;$ chown --dereference&#10;```&#10;Change the group of the file pointed to by a symbolic link, not the group of the symbolic link itself (default)&#10;Robbins, Arnold. _UNIX in a Nutshell_ 4th ed (2005): 38'
[chown --no-preserve-root]: #chown '```&#10;$ chown --no-preserve-root&#10;```&#10;Do not treat the root directory specially (default)&#10;Robbins, Arnold. _UNIX in a Nutshell_ 4th ed (2005): 38'
[chown --preserve-root]: #chown '```&#10;$ chown --preserve-root&#10;```&#10;Do not operate recusrsively on the root directory.&#10;Robbins, Arnold. _UNIX in a Nutshell_ 4th ed (2005): 38'
[chown --reference]: #chown '```&#10;$ chown --reference $FILENAME&#10;```&#10;change the group to that associated with `$FILENAME`. In this case, `$NEWGROUP` is not specified&#10;Robbins, Arnold. _UNIX in a Nutshell_ 4th ed (2005): 38'

<code>&nbsp;</code>   <code>&nbsp;</code> <code>&nbsp;</code> [`c`][chown -&#99;] <code>&nbsp;</code> <code>&nbsp;</code> [`f`][chown -&#102;] <code>&nbsp;</code> [`h`][chown -&#104;] <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> [`v`][chown -&#118;] <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code>  <br><code>&nbsp;</code>&nbsp;<code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> [`H`][chown -&#72;] <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> [`L`][chown -&#76;] <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> [`P`][chown -&#80;] <code>&nbsp;</code> [`R`][chown -&#82;] <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> 

Change a file or directory's ownership. To change the user and group owner of a file to {user} and {group}, `chown`'s syntax is of the format `user:group` [[32](sources.md)].
```sh
chown susan:delta file          # Assign {file} to user `susan` and group `delta`
chown alan file                 # Assign {file} to user `alan`
chown alan: file                # Assign {file} to user and group `alan`
chown :gamma file               # Assign {file} to the group `gamma`
```
Recursively grant {user} ownership to {path}
```sh
chown -R user path
```
Assign {path} to `susan` and group `delta`, recursively and with verbose output
```sh
chown --verbose --recursive susan:delta path 
chown -vR susan:delta path
```
```sh
chown -vR --reference=. path    # Use a `reference` file to match the configuration of a particular file
chown -cfR --preserve-root alan # `preserve-root` prevents changes to files in the root directory, but has no effect when not used with `recursive`
```
### `chpass`
Change default shell to Fish
```sh
chpass -s /usr/local/bin/fish
```
### `chrony`
Synchronize system time using NTP (cf. [`timedatectl`][timedatectl]

Stop the `systemd-timesyncd` service
```sh
sudo systemctl stop systemd-timesyncd.service
```
Install `chrony` if it is not already present and enable and start the service
```sh
sudo systemctl enable chronyd && sudo systemctl start chronyd
```
### `chsh`
Change the user's default shell to Bash
```sh
chsh-s /bin/bash
```
Change the user's default shell to Fish
```sh
chsh-s /usr/local/bin/fish
```
### `free`
[free -&#98;]:                  #free                          '```&#10;$ free -b&#10;```&#10;Show memory usage in bytes&#10;Haeder, Adam. _LPI Linux Certification in a Nutshell_. 2010.: 114'
[free -&#107;]:                 #free                          '```&#10;$ free -k&#10;```&#10;Show memory usage in kilobytes&#10;Haeder, Adam. _LPI Linux Certification in a Nutshell_. 2010.: 114'
[free -&#109;]:                 #free                          '```&#10;$ free -m&#10;```&#10;Show memory usage in megabytes&#10;Haeder, Adam. _LPI Linux Certification in a Nutshell_. 2010.: 114'
[free -&#116;]:                 #free                          '```&#10;$ free -t&#10;```&#10;Display a line showing total&#10;Haeder, Adam. _LPI Linux Certification in a Nutshell_. 2010.: 114'
[free -&#115;]:                 #free                          '```&#10;$ free -s $N&#10;```&#10;Continuous operation at `$N`-second intervals&#10;Haeder, Adam. _LPI Linux Certification in a Nutshell_. 2010.: 114'
[free -&#99;]:                  #free                          '```&#10;$ free -c $N&#10;```&#10;Run the program `$N` times'
[free -&#104;]:                 #free                          '```&#10;$ free -h&#10;```&#10;Human-readable output'

<code>&nbsp;</code> <code>&nbsp;</code> [`b`][free -&#98;] [`c`][free -&#99;] <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> [`h`][free -&#104;] <code>&nbsp;</code> <code>&nbsp;</code> [`k`][free -&#107;] <code>&nbsp;</code> [`m`][free -&#109;] <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> [`s`][free -&#115;] [`t`][free -&#116;] <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> 

List memory statistics in kilobytes. Without any options, `free` returns a table listing general statistics in kilobytes:
```bash
free
```
Command-line memory dashboard
```bash
watch free -h
```
### `getent`
Get entries from the `passwd` file [[50](sources.md)]
```sh
getent passwd sonny timmy
```
```
sonny:x:1001:1002:Sonny:/home/sonny:/bin/bash
timmy:x:1002:1003::/home/timmy:/bin/bash
```
```sh
getent group sonny timmy
```
```
sonny:x:1002:
timmy:x:1003:
```
### `gpasswd`
Add `$USER` to `$GROUP`
```sh
gpasswd -a $USER $GROUP
```
Add `$USER` as admin of `$GROUP`
```sh
gpasswd -A $USER $GROUP
```
Remove `$USER` from `$GROUP`
```sh
gpasswd -d $USER $GROUP
```
### `groupadd`
Create a new group
### `groupdel`
Delete a group
### `groupmod`
[groupmod -&#103;]:             #groupmod                      '```&#10;$ groupmod -g&#10;```&#10;Change GID&#10;Rothwell, William. _CompTIA Linux+ Portable Command Guide_.: 95'
[groupmod -&#110;]:             #groupmod                      '```&#10;$ groupmod -n $NAME&#10;$ groupmod --newname $NAME&#10;```&#10;Change name of the group to `$NAME`&#10;Rothwell, William. _CompTIA Linux+ Portable Command Guide_.: 95'

<code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> [`g`][groupmod -&#103;] <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> [`n`][groupmod -&#110;] <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> 

### `passwd`
<!-- `passwd` options -->
[passwd -&#100;]:               #passwd                        '```&#10;$ passwd -d&#10;```&#10;Delete password&#10;Rothwell, William. _CompTIA Linux+ Portable Command Guide_.: 95'
[passwd -&#101;]:               #passwd                        '```&#10;$ passwd -e&#10;$ passwd --expire&#10;```&#10;Immediately expire account&#10;Rothwell, William. _CompTIA Linux+ Portable Command Guide_.: 95'
[passwd -&#105;]:               #passwd                        '```&#10;$ passwd -i $N&#10;$ passwd --inactive $N&#10;```&#10;Disable account after `$N` days of inactivity'
[passwd -&#108;]:               #passwd                        '```&#10;$ passwd -l&#10;$ passwd --lock&#10;```&#10;Lock account&#10;Rothwell, William. _CompTIA Linux+ Portable Command Guide_.: 95'
[passwd -&#109;]:               #passwd                        '```&#10;$ passwd -m&#10;```&#10;Change the Min field of the /etc/shadow file for the user&#10;Rothwell, William. _CompTIA Linux+ Portable Command Guide_.: 95'
[passwd -&#77;]:                #passwd                        '```&#10;$ passwd -M&#10;```&#10;Change the Max field of the /etc/shadow file for the user&#10;Rothwell, William. _CompTIA Linux+ Portable Command Guide_.: 95'
[passwd -&#117;]:               #passwd                        '```&#10;$ passwd -u&#10;$ passwd --unlock&#10;```&#10;Unlock the account&#10;Rothwell, William. _CompTIA Linux+ Portable Command Guide_.: 95'
[passwd -&#119;]:               #passwd                        '```&#10;$ passwd -w&#10;```&#10;Change the Warn field of the /etc/shadow file for the user&#10;Rothwell, William. _CompTIA Linux+ Portable Command Guide_.: 95'

<code>&nbsp;</code>   <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> [`d`][passwd -&#100;] [`e`][passwd -&#101;] <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> [`i`][passwd -&#105;] <code>&nbsp;</code> <code>&nbsp;</code> [`l`][passwd -&#108;] [`m`][passwd -&#109;] <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> [`u`][passwd -&#117;] <code>&nbsp;</code> [`w`][passwd -&#119;] <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code>  <br><code>&nbsp;</code>&nbsp;<code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> [`M`][passwd -&#77;] <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> 

### `ps`
[ps -&#97;]:                    #ps                            '```&#10;$ ps -a&#10;$ ps xG&#10;```&#10;Show processes that are owned by other users and attached to a terminal&#10;Haeder, Adam. _LPI Linux Certification in a Nutshell_. 2010.: 109'
[ps -&#102;]:                   #ps                            '```&#10;$ ps -f&#10;```&#10;Full-format listing that prints command arguments in addition to the command itself&#10;Haeder, Adam. _LPI Linux Certification in a Nutshell_. 2010.: 109'
[ps -&#108;]:                   #ps                            '```&#10;$ ps -l&#10;```&#10;Long format that includes priority, parent PID, and other information&#10;Haeder, Adam. _LPI Linux Certification in a Nutshell_. 2010.: 109'
[ps -&#117;]:                   #ps                            '```&#10;$ ps -u&#10;```&#10;User format that includes usernames and the start time of processes&#10;Haeder, Adam. _LPI Linux Certification in a Nutshell_. 2010.: 109'
[ps -&#119;]:                   #ps                            '```&#10;$ ps -w&#10;```&#10;Wide output format, used to eliminate the default output line truncation.&#10;Haeder, Adam. _LPI Linux Certification in a Nutshell_. 2010.: 109'
[ps -&#120;]:                   #ps                            '```&#10;$ ps -x&#10;```&#10;Include processes without controlling terminals&#10;Haeder, Adam. _LPI Linux Certification in a Nutshell_. 2010.: 109'
[ps -&#67;]:                    #ps                            '```&#10;$ ps -C $CMD&#10;```&#10;Display instancess of `$CMD`&#10;Haeder, Adam. _LPI Linux Certification in a Nutshell_. 2010.: 109'
[ps -&#85;]:                    #ps                            '```&#10;$ ps -U $USER&#10;```&#10;Display processes owned by `$USER`&#10;Haeder, Adam. _LPI Linux Certification in a Nutshell_. 2010.: 109'
[ps -&#101;]:                   #ps                            '```&#10;$ ps -e&#10;$ ps ax&#10;```&#10;Show system processes'

<code>&nbsp;</code>   [`a`][ps -&#97;] <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> [`e`][ps -&#101;] [`f`][ps -&#102;] <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> [`l`][ps -&#108;] <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> [`u`][ps -&#117;] <code>&nbsp;</code> [`w`][ps -&#119;] [`x`][ps -&#120;] <code>&nbsp;</code> <code>&nbsp;</code>  <br><code>&nbsp;</code>&nbsp;<code>&nbsp;</code> <code>&nbsp;</code> [`C`][ps -&#67;] <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> [`U`][ps -&#85;] <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> 

Display processes in a tree-like display illustrating parent-child relationships
```sh
ps -f
ps --forest
```
Show system processes
```sh
ps ax
ps -e
```
Display full listing of processes
```sh
ps u
ps -f
```
Display user processes
```sh
ps xG
ps -a
```
Display SELinux contexts for processes
```sh
ps auxZ
```
### `setfacl`
[setfacl -&#98;]:               #setfacl                       '```&#10;$ setfacl -b&#10;$ setfacl --remove-all&#10;```&#10;Remove all extended ACL entries, retaining the base ACL entries of the owner, group, and others'
[setfacl -&#107;]:              #setfacl                       '```&#10;$ setfacl -k&#10;$ setfacl --remove-default&#10;```&#10;Remove the default ACL'
[setfacl -&#109;]:              #setfacl                       '```&#10;$ setfacl -m&#10;$ setfacl --modify&#10;```&#10;Modify ACL of a directory'
[setfacl -&#77;]:               #setfacl                       '```&#10;$ setfacl -M&#10;$ setfacl --modify-file&#10;```&#10;Modify ACL of a file'
[setfacl -&#115;]:              #setfacl                       '```&#10;$ setfacl -s&#10;```&#10;Overwrite or "set"'
[setfacl -&#120;]:              #setfacl                       '```&#10;$ setfacl -x&#10;$ setfacl --remove&#10;```&#10;Remove ACL entries from a directory'
[setfacl -&#88;]:               #setfacl                       '```&#10;$ setfacl -X&#10;$ setfacl --remove-file&#10;```&#10;Remove ACL entries from a file'

<code>&nbsp;</code>   <code>&nbsp;</code> [`b`][setfacl -&#98;] <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> [`k`][setfacl -&#107;] <code>&nbsp;</code> [`m`][setfacl -&#109;] <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> [`s`][setfacl -&#115;] <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> [`x`][setfacl -&#120;] <code>&nbsp;</code> <code>&nbsp;</code>  <br><code>&nbsp;</code>&nbsp;<code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> [`M`][setfacl -&#77;] <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> [`X`][setfacl -&#88;] <code>&nbsp;</code> <code>&nbsp;</code> 

Grant user {lisa} right to read {file}
```sh
setfacl -m u:lisa:r file
```
Remove named group {staff} from {file}'s ACL
```sh
setfacl -x g:staff file
```
Modify file access control list for {file} to revoke write access from all groups and all named users
```sh
setfacl -m m::rx file
```
Grant read access to **o**ther users
```sh
setfacl -m o::rwx file4.txt
```
Add user {zach} to list of users of file4.txt
```sh
setfacl -m u:zach:rw file4.txt
```
### `shutdown`
Shut down at 8 pm
```sh
shutdown 20:00
```
### `sudo`
`sudo` is installed by default on most distros, but it can be installed. [[52](sources.md)]\
In order to use `sudo`, users have to be added to special groups that vary based on distribution. The group `wheel` grants access to `sudo` on Red Hat derivatives, while there is a group named `sudo` on Debian, Ubuntu, and derivatives to do the same thing.\
Using `sudo` with output redirection will cause an error if the effective user doesn't have write permissions. 
- Invoke a new shell as root by using `sudo sh -c`
- Pipe output to `sudo tee` command

Prevent sudo from prompting for credentials or for any other reason
```sh
sudo --noprompt
```
### `su`
Obtain the normal login environment
```sh
su -
```
Execute a single command with a non-interactive session
```sh
su -c cmd
```
### `top`
Option  | Effect
:---    | :---
`-n`    | change update interval
### `uname`
[uname -&#97;]:                 #uname                         '```&#10;$ uname -a&#10;```&#10;Display all information'
[uname -&#115;]:                #uname                         '```&#10;$ uname -s&#10;```&#10;Display the kernel name'
[uname -&#110;]:                #uname                         '```&#10;$ uname -n&#10;```&#10;Display the network node (i.e. hostname)'
[uname -&#118;]:                #uname                         '```&#10;$ uname -v&#10;```&#10;Display version (date) of the kernel'
[uname -&#109;]:                #uname                         '```&#10;$ uname -m&#10;```&#10;Display the machine hardware name'
[uname -&#112;]:                #uname                         '```&#10;$ uname -p&#10;```&#10;Display the processor type'
[uname -&#114;]:                #uname                         '```&#10;$ uname -r&#10;```&#10;Display operating system release number'
[uname -&#111;]:                #uname                         '```&#10;$ uname -o&#10;```&#10;Display operating system'

<code>&nbsp;</code> [`a`][uname -&#97;] <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> [`m`][uname -&#109;] [`n`][uname -&#110;] [`o`][uname -&#111;] [`p`][uname -&#112;] <code>&nbsp;</code> [`r`][uname -&#114;] [`s`][uname -&#115;] <code>&nbsp;</code> <code>&nbsp;</code> [`v`][uname -&#118;] <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> 

Check kernel version
```bash
uname -srm
```
### `useradd`
[useradd -&#98;]:               #useradd                       '```&#10;$ useradd -b&#10;$ useradd --base-dir&#10;```&#10;Default base directory for the system if `$HOME_DIR` is not specified (sets `$HOME` variable in /etc/default/useradd)'
[useradd -&#99;]:               #useradd                       '```&#10;$ useradd -c $COMMENT&#10;$ useradd --comment $COMMENT&#10;```&#10;Set comment or GECOS field for user&#10;Rothwell, William. _CompTIA Linux+ Portable Command Guide_.: 94'
[useradd -&#100;]:              #useradd                       '```&#10;$ useradd -d $HOMEDIR&#10;$ useradd --home-dir $HOMEDIR&#10;```&#10;Specify home directory for user&#10;Rothwell, William. _CompTIA Linux+ Portable Command Guide_.: 94'
[useradd -&#68;]:               #useradd                       '```&#10;$ useradd -D&#10;$ useradd --defaults&#10;```&#10;List (and optionally change) system default values&#10;Haeder, Adam. _LPI Linux Certification in a Nutshell_. 2010.: 323'
[useradd -&#101;]:              #useradd                       '```&#10;$ useradd -e&#10;$ useradd --expire-date&#10;```&#10;Set account expiration date&#10;Rothwell, William. _CompTIA Linux+ Portable Command Guide_.: 94'
[useradd -&#102;]:              #useradd                       '```&#10;$ useradd -f&#10;```&#10;Set account inactive value&#10;Rothwell, William. _CompTIA Linux+ Portable Command Guide_.: 94'
[useradd -&#103;]:              #useradd                       '```&#10;$ useradd -g&#10;```&#10;Specify primary group&#10;Rothwell, William. _CompTIA Linux+ Portable Command Guide_.: 94'
[useradd -&#71;]:               #useradd                       '```&#10;$ useradd -G&#10;```&#10;Specify secondary groups&#10;Rothwell, William. _CompTIA Linux+ Portable Command Guide_.: 94'
[useradd -&#107;]:              #useradd                       '```&#10;$ useradd -k&#10;$ useradd --skel&#10;```&#10;Specify skel directory&#10;Rothwell, William. _CompTIA Linux+ Portable Command Guide_.: 94'
[useradd -&#109;]:              #useradd                       '```&#10;$ useradd -m&#10;$ useradd --create-home&#10;```&#10;Create and populate the home directory&#10;Haeder, Adam. _LPI Linux Certification in a Nutshell_. 2010.: 323'
[useradd -&#114;]:              #useradd                       '```&#10;$ useradd -r&#10;$ useradd --system&#10;```&#10;Create a system account'
[useradd -&#115;]:              #useradd                       '```&#10;$ useradd -s $SHELL&#10;$ useradd --shell $SHELL&#10;```&#10;Specify login shell&#10;Rothwell, William. _CompTIA Linux+ Portable Command Guide_.: 94'
[useradd -&#117;]:              #useradd                       '```&#10;$ useradd -u&#10;$ useradd --uid&#10;```&#10;Specify UID&#10;Rothwell, William. _CompTIA Linux+ Portable Command Guide_.: 94'

<code>&nbsp;</code>   <code>&nbsp;</code> [`b`][useradd -&#98;] [`c`][useradd -&#99;] [`d`][useradd -&#100;] [`e`][useradd -&#101;] [`f`][useradd -&#102;] [`g`][useradd -&#103;] <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> [`k`][useradd -&#107;] <code>&nbsp;</code> [`m`][useradd -&#109;] <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> [`r`][useradd -&#114;] [`s`][useradd -&#115;] <code>&nbsp;</code> [`u`][useradd -&#117;] <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code>  <br><code>&nbsp;</code>&nbsp;<code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> [`D`][useradd -&#68;] <code>&nbsp;</code> <code>&nbsp;</code> [`G`][useradd -&#71;] <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> 

Create a new user, setting their default shell to /bin/bash
```sh
useradd -s /bin/bash
```
Create a new user account {luke} belonging to default group {wheel}, creating a home directory
```sh
useradd -m -g wheel luke
```
Create a new user account with {comment}
```sh
useradd -c "comment"
```
Create a new user account, adding it to groups {grp1} and {grp2}
```sh
useradd -G grp1 grp2
```
Create a new user account, specifying {UUID}
```sh
useradd -u UUID
```
Add `$USER`
```sh
useradd $USER
```
Add `$USER`, noting her full `$NAME`
```sh
useradd $USER -c $NAME
```
Add `$USER`, specifying home directory at `$PATH`
```sh
useradd $USER -d $PATH
```
Add `$USER`, specifying expiration `$DATE` (YYYY-MM-DD)
```sh
useradd $USER -e $DATE
```
Create new `$USER` leaving a `$COMMENT` field (conventionally noting the full name of the user) and creating a home directory
```sh
useradd -c $COMMENT -m $USER
```
Create a system user rather than a normal user
```sh
useradd -r
```
### `userdel`

<!-- `userdel` options -->
[userdel -&#114;]:              #userdel                       '```&#10;$ userdel -r&#10;```&#10;Delete `$USER` as well as home directory&#10;Haeder, Adam. _LPI Linux Certification in a Nutshell_. 2010.: 324'

Delete an existing user account

Delete an existing user account as well as the user's home directory
```sh
userdel -r  user
```
### `usermod`
[usermod -&#76;]:               #usermod                       '```&#10;$ usermod -L&#10;```&#10;Lock password, disabling account&#10;Haeder, Adam. _LPI Linux Certification in a Nutshell_. 2010.: 324'
[usermod -&#85;]:               #usermod                       '```&#10;$ usermod -U&#10;```&#10;Unlock password, enabling account&#10;Haeder, Adam. _LPI Linux Certification in a Nutshell_. 2010.: 324'
[usermod -&#99;]:               #usermod                       '```&#10;$ usermod -c $COMMENT&#10;```&#10;Set or change the value of the Comment field &#10;Haeder, Adam. _LPI Linux Certification in a Nutshell_. 2010.: 413'
[usermod -&#100;]:              #usermod                       '```&#10;$ usermod -d $HOMEDIR&#10;```&#10;Set or change home directory of user&#10;Haeder, Adam. _LPI Linux Certification in a Nutshell_. 2010.: 413'
[usermod -&#103;]:              #usermod                       '```&#10;$ usermod -g $GROUP&#10;```&#10;Set primary GID of the user&#10;Haeder, Adam. _LPI Linux Certification in a Nutshell_. 2010.: 413'
[usermod -&#71;]:               #usermod                       '```&#10;$ usermod -G $GROUPS&#10;$ usermod --groups $GROUPS&#10;```&#10;Set supplementary GIDS for a user to `$GROUPS` (comma-delimited)&#10;Haeder, Adam. _LPI Linux Certification in a Nutshell_. 2010.: 413'
[usermod -&#108;]:              #usermod                       '```&#10;$ usermod -l $NAME&#10;$ usermod --login $NAME&#10;```&#10;Change username to `$NAME`&#10;Haeder, Adam. _LPI Linux Certification in a Nutshell_. 2010.: 413'
[usermod -&#115;]:              #usermod                       '```&#10;$ usermod -s $SHELL&#10;```&#10;Change shell to `$SHELL`&#10;Haeder, Adam. _LPI Linux Certification in a Nutshell_. 2010.: 413'
[usermod -&#97;]:               #usermod                       '```&#10;$ usermod -a&#10;```&#10;Add user to supplementary groups, only used with `-G`'
[usermod -&#76;]:               #usermod                       '```&#10;$ usermod -L&#10;$ usermod --lock&#10;```&#10;Lock password, disabling account'
[usermod -&#117;]:              #usermod                       '```&#10;$ usermod -u&#10;$ usermod --uid&#10;```&#10;Change UID'
[usermod -&#85;]:               #usermod                       '```&#10;$ usermod -U&#10;$ usermod --unlock&#10;```&#10;Unlock account'

<code>&nbsp;</code>   [`a`][usermod -&#97;] <code>&nbsp;</code> [`c`][usermod -&#99;] [`d`][usermod -&#100;] <code>&nbsp;</code> <code>&nbsp;</code> [`g`][usermod -&#103;] <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> [`l`][usermod -&#108;] <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> [`s`][usermod -&#115;] <code>&nbsp;</code> [`u`][usermod -&#117;] <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code>  <br><code>&nbsp;</code>&nbsp;<code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> [`G`][usermod -&#71;] <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> [`L`][usermod -&#76;] <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> [`U`][usermod -&#85;] <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> 

## Text
[cat]: #cat '```&#10;$ cat&#10;```&#10;Display contents of text files&#10;Rothwell, William. _CompTIA Linux+ Portable Command Guide_.: 115'
[cmp]: #cmp '```&#10;$ cmp $FILE $OTHER&#10;```&#10;Compare `$FILE` with `$OTHER`, or STDIN if one or the other is not provided (cf. `comm` and `diff`). Exits with 0 if files are identical or 1 if they are not.&#10;Robbins, Arnold. _UNIX in a Nutshell_ 4th ed (2005): 39'
[comm]: #comm '```&#10;$ comm $FILE $OTHER&#10;```&#10;Compare lines common to the sorted files `$FILE` and `$OTHER`. Output is in 3 colums: lines unique to `$FILE`, lines unique to `$OTHER`, and lines common to both.&#10;Robbins, Arnold. _UNIX in a Nutshell_ 4th ed (2005): 39'
[csplit]: #csplit '```&#10;$ csplit&#10;```&#10;Separate `$FILE` into sections and place sections in files named "xx00" through "xxn" (n < 100)&#10;Robbins, Arnold. _UNIX in a Nutshell_ 4th ed (2005): 46'
[cut]: #cut '```&#10;$ cut&#10;```&#10;Select a list of columns or fields from one or more files&#10;Robbins, Arnold. _UNIX in a Nutshell_ 4th ed (2005): 50'
[diff]: #diff '```&#10;$ diff $FILE $OTHER&#10;```&#10;Report lines that differ between `$FILE` and `$OTHER`. Output consists of lines of context from each file, with `$FILE` text flagged by a "&lt;" and `$OTHER` text by a "&gt;". (cf. `cmp`, `comm`, `diff3`, `dircmp`, and `sdiff`).&#10;Robbins, Arnold. _UNIX in a Nutshell_ 4th ed (2005): 58'
[diff3]: #diff3 '```&#10;$ diff3&#10;```&#10;Compare three files and report differences&#10;Robbins, Arnold. _UNIX in a Nutshell_ 4th ed (2005): 63'
[ed]: #ed '```&#10;$ ed&#10;```&#10;Line-oriented text editor, superceded by `vi` and `ex`&#10;Robbins, Arnold. _UNIX in a Nutshell_ 4th ed (2005): 70'
[egrep]: #egrep '```&#10;$ egrep&#10;```&#10;Equivalent to `grep -E`&#10;Rothwell, William. _CompTIA Linux+ Portable Command Guide_.: 128'
[ex]: #ex '```&#10;$ ex&#10;```&#10;Line-oriented text editor, a superset of `ed` and the root of `vi`.&#10;Robbins, Arnold. _UNIX in a Nutshell_ 4th ed (2005): 78'
[expand]: #expand '```&#10;$ expand&#10;```&#10;Convert Tabs to spaces&#10;Haeder, Adam. _LPI Linux Certification in a Nutshell_. 2010.: 79'
[fgrep]: #fgrep '```&#10;$ fgrep $PATTERN&#10;```&#10;Search one or more files for lines that match a literal, text-string `$PATTERN`&#10;Robbins, Arnold. _UNIX in a Nutshell_ 4th ed (2005): 82'
[fmt]: #fmt '```&#10;$ fmt&#10;```&#10;Format text to a specified width by filling lines and removing newline characters&#10;Haeder, Adam. _LPI Linux Certification in a Nutshell_. 2010.: 79'
[gettext]: #gettext '```&#10;$ gettext $STRING&#10;```&#10;Translate `$STRING`&#10;Robbins, Arnold. _UNIX in a Nutshell_ 4th ed (2005): 99'
[grep]: #grep '```&#10;$ grep $PATTERN $FILES&#10;```&#10;Search `$FILES` for lines containing a match to regex `$PATTERN`&#10;Haeder, Adam. _LPI Linux Certification in a Nutshell_. 2010.: 126'
[groff]: #groff '```&#10;$ groff&#10;```&#10;Format documents to screen or for laser printing; GNU version of `troff`'
[head]: #head '```&#10;$ head&#10;```&#10;Print the first few lines of one or more files&#10;Haeder, Adam. _LPI Linux Certification in a Nutshell_. 2010.: 79'
[join]: #join '```&#10;$ join $FILE $OTHER&#10;```&#10;Print a line for each pair of input lines, one each from `$FILE` and `$OTHER`, that have identical join fields.&#10;Haeder, Adam. _LPI Linux Certification in a Nutshell_. 2010.: 80'
[less]: #less '```&#10;$ less&#10;```&#10;Pager&#10;Robbins, Arnold. _UNIX in a Nutshell_ 4th ed (2005): 116'
[look]: #look '```&#10;$ look&#10;```&#10;Look through a sorted file and print all lines that begin with `$STRING`&#10;Robbins, Arnold. _UNIX in a Nutshell_ 4th ed (2005): 124'
[more]: #more '```&#10;$ more&#10;```&#10;Display text one page at a time; superceded by `less`.&#10;Rothwell, William. _CompTIA Linux+ Portable Command Guide_.: 116'
[nl]: #nl '```&#10;$ nl&#10;```&#10;Number the lines of files, which are concatenated in the output.&#10;Haeder, Adam. _LPI Linux Certification in a Nutshell_. 2010.: 81'
[od]: #od '```&#10;$ od&#10;```&#10;Dump files in octal and other formats&#10;Haeder, Adam. _LPI Linux Certification in a Nutshell_. 2010.: 82'
[paste]: #paste '```&#10;$ paste&#10;```&#10;Paste together corresponding lines of one or more files into vertical columns, similar to but simpler than `join`.&#10;Haeder, Adam. _LPI Linux Certification in a Nutshell_. 2010.: 83'
[pr]: #pr '```&#10;$ pr&#10;```&#10;Convert a text file into a paginated, columnar version, with headers and page fills&#10;Haeder, Adam. _LPI Linux Certification in a Nutshell_. 2010.: 84'
[sed]: #sed '```&#10;$ sed&#10;```&#10;"Stream editor", powerful filtering program found on nearly every Unix system.&#10;Haeder, Adam. _LPI Linux Certification in a Nutshell_. 2010.: 128'
[shuf]: #shuf '```&#10;$ shuf&#10;```&#10;Randomly permute input'
[sort]: #sort '```&#10;$ sort&#10;```&#10;Sort text data&#10;Rothwell, William. _CompTIA Linux+ Portable Command Guide_.: 124'
[split]: #split '```&#10;$ split $INFILE $OUTFILE&#10;```&#10;Split `$INFILE` into a specified number of line groups, named `$OUTFILE`aa, `$OUTFILE`ab, etc&#10;Haeder, Adam. _LPI Linux Certification in a Nutshell_. 2010.: 86'
[tac]: #tac '```&#10;$ tac&#10;```&#10;Print text files to STDOUT with lines in reverse order&#10;Haeder, Adam. _LPI Linux Certification in a Nutshell_. 2010.: 87'
[tail]: #tail '```&#10;$ tail&#10;```&#10;Display the bottom part of text data.&#10;Rothwell, William. _CompTIA Linux+ Portable Command Guide_.: 115'
[tee]: #tee '```&#10;$ tee&#10;```&#10;Send output to both STDOUT and to a file&#10;Rothwell, William. _CompTIA Linux+ Portable Command Guide_.: 122'
[tr]: #tr '```&#10;$ tr&#10;```&#10;Translate characters from one set to another&#10;Rothwell, William. _CompTIA Linux+ Portable Command Guide_.: 123'
[unexpand]: #unexpand '```&#10;$ unexpand&#10;```&#10;Convert spaces to tabs&#10;Haeder, Adam. _LPI Linux Certification in a Nutshell_. 2010.: 89'
[uniq]: #uniq '```&#10;$ uniq $INPUT $OUTPUT&#10;```&#10;Write $INPUT to $OUTPUT, eliminating adjacent duplicate lines&#10;Haeder, Adam. _LPI Linux Certification in a Nutshell_. 2010.: 89'
[wc]: #wc '```&#10;$ wc&#10;```&#10;Display number of lines, words, or characters of data.&#10;Rothwell, William. _CompTIA Linux+ Portable Command Guide_.: 128'

[`cat`][cat] 
[`cmp`][cmp] 
[`comm`][comm] 
[`csplit`][csplit] 
[`cut`][cut] 
[`diff`][diff] 
[`diff3`][diff3] 
[`ed`][ed] 
[`egrep`][egrep] 
[`ex`][ex] 
[`expand`][expand] 
[`fgrep`][fgrep] 
[`fmt`][fmt] 
[`gettext`][gettext] 
[`grep`][grep] 
[`groff`][groff] 
[`head`][head] 
[`join`][join] 
[`less`][less] 
[`look`][look] 
[`more`][more] 
[`nl`][nl] 
[`od`][od] 
[`paste`][paste] 
[`pr`][pr] 
[`sed`][sed] 
[`shuf`][shuf] 
[`sort`][sort] 
[`split`][split] 
[`tac`][tac] 
[`tail`][tail] 
[`tee`][tee] 
[`tr`][tr] 
[`unexpand`][unexpand] 
[`uniq`][uniq] 
[`wc`][wc] 

### `awk`
###### Options
[awk -&#70;]: #awk '```&#10;$ awk -F $C&#10;```&#10;Set field separator to `$C`'
[awk -&#102;]: #awk '```&#10;$ awk -f $PROGRAMFILE&#10;```&#10;Specify awk program-file `$PROGRAMFILE`'
[awk -&#118;]: #awk '```&#10;$ awk -v $VAR=$VAL&#10;$ awk --assign $VAR=$VAL&#10;```&#10;Set variable `$VAR` to value `$VAL` before script is executed'

<code>&nbsp;</code>   <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> [`f`][awk -&#102;] <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> [`v`][awk -&#118;] <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code>  <br><code>&nbsp;</code>&nbsp;<code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> [`F`][awk -&#70;] <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> 

###### Variables
[awk ARGC]: #awk '```&#10;$ ARGC&#10;```&#10;&#10;Number of arguments in command line'
[awk ARGV]: #awk '```&#10;$ ARGV&#10;```&#10;&#10;List of arguments'
[awk FILENAME]: #awk '```&#10;$ FILENAME&#10;```&#10;&#10;Current input filename'
[awk FNR]: #awk '```&#10;$ FNR&#10;```&#10;&#10;Number of the current record relative to the current input file'
[awk FS]: #awk '```&#10;$ FS&#10;```&#10;&#10;Field separator (whitespace by default)'
[awk NF]: #awk '```&#10;$ NF&#10;```&#10;&#10;Number of fields for the current input record'
[awk NR]: #awk '```&#10;$ NR&#10;```&#10;&#10;Number of the current input record'
[awk OFS]: #awk '```&#10;$ OFS&#10;```&#10;&#10;Output field separator (space by default)'
[awk ORS]: #awk '```&#10;$ ORS&#10;```&#10;&#10;Output record separator'
[awk RS]: #awk '```&#10;$ RS&#10;```&#10;&#10;Record separator (newline by default)'

[`ARGC`][awk ARGC] 
[`ARGV`][AWK ARGV] 
[`FILENAME`][AWK FILENAME] 
[`FNR`][AWK FNR] 
[`FS`][AWK FS] 
[`NF`][AWK NF] 
[`NR`][AWK NR] 
[`OFS`][AWK OFS] 
[`ORS`][AWK ORS] 
[`RS`][AWK RS] 

###### Functions
[awk gsub()]: #gsub() '```&#10;$ gsub()&#10;$ gsub($PATTERN,$SUBSTITUTION,$STRING)&#10;```&#10;&#10;Replace all instances of `$PATTERN` with `$SUBSTITUTION` in `$STRING` (`$0` if not specified)'
[awk sub()]: #sub() '```&#10;$ sub()&#10;$ sub($PATTERN,$SUBSTITUTION,$STRING)&#10;```&#10;&#10;Replace first instance of `$PATTERN` with `$SUBSTITUTION` in `$STRING` (`$0` if not specified)'
[awk index()]: #index() '```&#10;$ index()&#10;$ index($SUBSTR,$STRING)&#10;```&#10;&#10;Return (1-indexed) position of `$SUBSTR` within `$STRING` (or `$0` if not specified)'
[awk length()]: #length() '```&#10;$ length()&#10;$ length($STRING)&#10;```&#10;&#10;Return length of `$STRING` (or `$0` if not specified)'
[awk match()]: #match() '```&#10;$ match()&#10;$ match($STRING,$PATTERN)&#10;```&#10;&#10;Return position in `$STRING` where `$PATTERN` begins, or 0 if not found'
[awk printf()]: #printf() '```&#10;$ printf()&#10;$ printf "$CTRLSTR", *args&#10;```&#10;&#10;The "control-string" `$CTRLSTR` is interpolated with expressions called **conversion specifications**, with the syntax `%[-][x[.y]]conv` where `x` represents minimum field width, `y` number of places to the right of a decimal point in a number, and `conv` can be one of the following values&#10;  - `d` integer&#10;  - `e` exponential notation&#10;  - `f` floating point number&#10;  - `g` use `f` or `e`, whichever is shorter&#10;  - `o` unsigned octal&#10;  - `s` string&#10;  - `x` unsigned hexadecimal&#10;Olushile, Paul. _Linux 5 Performance Monitoring and Tuning_.: 534'
[awk split()]: #split() '```&#10;$ split()&#10;$ split($STRING,$ARRAY,$DELIM)&#10;```&#10;&#10;Break up `$STRING` by `$DELIM` and store the fields in `$ARRAY`&#10;"Universal Windows Platform apps". _Wikipedia_.: 481'
[awk substr()]: #substr() '```&#10;$ substr()&#10;$ substr($STRING,$N,$M)&#10;```&#10;&#10;Extract a substring from `$STRING`, where `$N` represents the starting position and `$M` the number of characters to be extracted from that point'
[awk tolower()]: #tolower() '```&#10;$ tolower()&#10;$ tolower($STRING)&#10;```&#10;&#10;Convert `$STRING` to lowercase letters'
[awk toupper()]: #toupper() '```&#10;$ toupper()&#10;$ toupper($STRING)&#10;```&#10;&#10;Convert `$STRING` to uppercase letters'

[`gsub()`][awk gsub()] 
[`sub()`][awk sub()] 
[`index()`][awk index()] 
[`length()`][awk length()] 
[`match()`][awk match()] 
[`printf()`][awk printf()] 
[`split()`][awk split()] 
[`substr()`][awk substr()] 
[`tolower()`][awk tolower()] 
[`toupper()`][awk toupper()] 

#### 

>"The basic function of awk is to search files for lines that contain certain patterns." ([GEAP](../sources/README.md): 17

Pattern-scanning utility and processing language, one of the two primary commands which accept regular expressions in Unix systems.

`awk` **programs** can be defined **inline** or in a **program-file** ([PGL](../sources/README.md): 528)
  - inline: `awk options 'program' input-files`
  - **program-file**, also "source-file" ([GEAP](../sources/README.md):18): `awk options -f program-file input-files` 

`awk` programs can be run without defining **input-files**, in which case awk will accept input from STDIN

`awk` **programs** are the equivalent of sed "instructions", and similarly combine **patterns** and **actions** ([PGL](../sources/README.md): 530, [GEAP](../sources/README.md): 17)

Patterns can be:
- regular expressions or fixed strings
- line numbers using builtin variable `NR`
- predefined patterns `BEGIN` or `END`, whose actions are executed before and after processing any lines of the data file, respectively

change ":" to newlines in PATH variable; equivalent to `echo $PATH \| tr ":" "\n"` 
```sh
echo $PATH | awk 'BEGIN {RS=":"} {print}'
```
print the first field of all files in the current directory, taking semicolon `;` as the field separator, outputting filename, line number, and first field of matches, with colon `:` between the filename and line number
```sh
awk 'BEGIN {FS=";"} /enable/ {print FILENAME ":" FNR,$1}' *
```
search for string `MA` in all files, outputting filename, line, and line number for matches
```sh
awk '/MA/ {OFS=" " print FILENAME OFS FNR OFS $0} *
``` 
change field separator (`FS`) to a colon (`:`) and run `awkscr`
```sh
awk -F: -f awkscr /etc/passwd
```
flag also works for awk
```sh
awk -f script files` `-f
```
print the first field of each line in the input file
```sh
awk '{ print $1 }' list
```
equivalent to `grep MA *` (`{print}` is implied)
```sh
awk '/MA/' * | awk '/MA/ {print}' *
```
`-F` flag is followed by field separator
```sh
awk -F, '/MA/ { print $1 }' list
```
pipe output of `free` to `awk` to get free memory and total memory
```sh
free -h | awk '/^Mem|/ {print $3 "/" $2}
```
pipe output of `sensors` to `awk` to get CPU temperature
```sh
sensors | awk '/^temp1/ {print $2}
```
replace initial "fake." with "real;" in file `fake_isbn`
```sh
awk 'sub(^fake.,"real;")' fake_isbn
```
print all lines
```sh
awk '1 { print }' file
```
remove file header
```sh
awk 'NR>1' file
```
remove file header
```sh
awk 'NR>1 { print } file
```
print lines in a range
```sh
awk 'NR>1 && NR < 4' file
```
remove whitespace-only lines
```sh
awk 'NF' file
```
remove all blank lines
```sh
awk '1' RS='' file
```
extract fields
```sh
awk '{ print $1, $3}' FS=, OFS=, file
```
perform column-wise calculations
```sh
awk '{ SUM=SUM+$1 } END { print SUM }' FS=, OFS=, file
```
count the number of nonempty lines
```sh
awk '/./ { COUNT+=1 } END { print COUNT }' file
```
count the number of nonempty lines
```sh
awk 'NF { COUNT+=1 } END { print COUNT }' file
```
count the number of nonempty lines
```sh
awk '+$1 { COUNT+=1 } END { print COUNT }' file
```
Arrays
```sh
awk '+$1 { CREDITS[$3]+=$1 } END { for (NAME in CREDITS) print NAME, CREDITS[NAME] }' FS=, file
```
Identify duplicate lines
```sh
awk 'a[$0]++' file
```
Remove duplicate lines
```sh
awk '!a[$0]++' file
```
Remove multiple spaces
```sh
awk '$1=$1' file
```
Join lines
```sh
awk '{ print $3 }' FS=, ORS=' ' file; echo
```
```sh
awk '+$1 { SUM+=$1; NUM+=1 } END { printf("AVG=%f",SUM/NUM); }' FS=, file` | format 
```
```sh
awk '+$1 { SUM+=$1; NUM+=1 } END { printf("AVG=%6.1f",SUM/NUM); }' FS=, file
```
Convert to uppercase 
```sh
awk '$3 { print toupper($0); }' file
```
Change part of a string
```sh
awk '{ $3 = toupper(substr($3,1,1)) substr($3,2) } $3' FS=, OFS=, file
```
Split the second field ("EXPDATE") by spaces, storing the result into the array DATE; then print credits ($1) and username ($3) as well as the month (DATE[2]) and year (DATE[3]) 
```sh
awk '+$1 { split($2, DATE, " "); print $1,$3, DATE[2], DATE[3] }' FS=, OFS=, file
```
```sh
awk '+$1 { split($4, GRP, ":"); print $3, GRP[1], GRP[2] }' FS=, file
```
```sh
awk '+$1 { split($4, GRP, /:+/); print $3, GRP[1], GRP[2] }' FS=, file
``` 
Search and replace with comma 
```sh
awk '+$1 { gsub(/ +/, "-", $2); print }' FS=, file
```
Adding date 
```sh
awk 'BEGIN { printf("UPDATED: "); system("date") } /^UPDATED:/ { next } 1' file
```
Modify a field externally 
```sh
awk '+$1 { CMD | getline $5; close(CMD); print }' CMD="uuid -v4" FS=, OFS=, file
```
Invoke dynamically generated command
```sh
awk '+$1 { cmd = sprintf(FMT, $2); cmd | getline $2; close(cmd); print }' FMT='date -I -d "%s"'  FS=, file
```
Join data
```sh
awk '+$1 { CMD | getline $5; print }' CMD='od -vAn -w4 -t x /dev/urandom' FS=, file
```
Add up all first records to {sum}, then print that number out at the end
```sh
awk '{sum += $1} END {print sum}' file
```

### `cat`
[cat -&#65;]: #cat '```&#10;$ cat -A&#10;```&#10;Display nonprinting characters; display `$` at the end of each line and `^I` for Tab characters&#10;Haeder, Adam. _LPI Linux Certification in a Nutshell_. 2010.: 78'
[cat -&#98;]: #cat '```&#10;$ cat -b&#10;$ cat --number-nonblank&#10;```&#10;number all nonblank output lines&#10;Robbins, Arnold. _UNIX in a Nutshell_ 4th ed (2005): 32'
[cat -&#69;]: #cat '```&#10;$ cat -E&#10;$ cat --show-ends&#10;```&#10;print "$" at the end of each line&#10;Robbins, Arnold. _UNIX in a Nutshell_ 4th ed (2005): 32'
[cat -&#101;]: #cat '```&#10;$ cat -e&#10;```&#10;same as `-vE`&#10;Robbins, Arnold. _UNIX in a Nutshell_ 4th ed (2005): 32'
[cat -&#110;]: #cat '```&#10;$ cat -n&#10;$ cat --number&#10;```&#10;number lines, including blank lines&#10;Robbins, Arnold. _UNIX in a Nutshell_ 4th ed (2005): 32'
[cat -&#115;]: #cat '```&#10;$ cat -s&#10;$ cat --squeeze-blank&#10;```&#10;collapse multiple blank lines to a single one&#10;Robbins, Arnold. _UNIX in a Nutshell_ 4th ed (2005): 32'
[cat -&#116;]: #cat '```&#10;$ cat -t&#10;```&#10;same as `-vT`&#10;Robbins, Arnold. _UNIX in a Nutshell_ 4th ed (2005): 32'
[cat -&#84;]: #cat '```&#10;$ cat -T&#10;$ cat --show-tabs&#10;```&#10;print TAB characters as "^I"&#10;Robbins, Arnold. _UNIX in a Nutshell_ 4th ed (2005): 32'
[cat -&#117;]: #cat '```&#10;$ cat -u&#10;```&#10;ignored; retained for Unix compatibility&#10;Robbins, Arnold. _UNIX in a Nutshell_ 4th ed (2005): 32'
[cat -&#118;]: #cat '```&#10;$ cat -v&#10;$ cat --show-nonprinting&#10;```&#10;display conrol characters and nonprinting characters, except LINEFEED and TAB&#10;Robbins, Arnold. _UNIX in a Nutshell_ 4th ed (2005): 32'

<code>&nbsp;</code>   <code>&nbsp;</code> [`b`][cat -&#98;] <code>&nbsp;</code> <code>&nbsp;</code> [`e`][cat -&#101;] <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> [`n`][cat -&#110;] <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> [`s`][cat -&#115;] [`t`][cat -&#116;] [`u`][cat -&#117;] [`v`][cat -&#118;] <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code>  <br><code>&nbsp;</code>&nbsp;[`A`][cat -&#65;] <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> [`E`][cat -&#69;] <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> [`T`][cat -&#84;] <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> 

### `diff`
[diff -&#97;]: #diff '```&#10;$ diff -a&#10;$ diff --text&#10;```&#10;Treat all files as text files&#10;Robbins, Arnold. _UNIX in a Nutshell_ 4th ed (2005): 60'
[diff -&#98;]: #diff '```&#10;$ diff -b&#10;$ diff --ignore-space-change&#10;```&#10;Treat successive blanks as one, including end-of-line blanks&#10;Robbins, Arnold. _UNIX in a Nutshell_ 4th ed (2005): 59'
[diff -&#66;]: #diff '```&#10;$ diff -B&#10;$ diff --ignore-blank-lines&#10;```&#10;Ignore blank lines in files&#10;Robbins, Arnold. _UNIX in a Nutshell_ 4th ed (2005): 60'
[diff -&#99;]: #diff '```&#10;$ diff -c&#10;```&#10;Produce output in "context diff" format, with three lines of context&#10;Robbins, Arnold. _UNIX in a Nutshell_ 4th ed (2005): 59'
[diff -&#67;]: #diff '```&#10;$ diff -C&#10;$ diff --$N&#10;```&#10;Like `-c`, but produce `$N` lines of context&#10;Robbins, Arnold. _UNIX in a Nutshell_ 4th ed (2005): 59'
[diff -&#68;]: #diff '```&#10;$ diff -D $SYMBOL&#10;$ diff --ifdef $SYMBOL&#10;```&#10;Merge files into a single one, containing conditional C preprocessor directives (`#ifdef`)&#10;Robbins, Arnold. _UNIX in a Nutshell_ 4th ed (2005): 59'
[diff -&#100;]: #diff '```&#10;$ diff -d&#10;$ diff --minimal&#10;```&#10;Ignore segments of numerous changes and output a smaller set of changes, to speed up comparison.&#10;Robbins, Arnold. _UNIX in a Nutshell_ 4th ed (2005): 60'
[diff -&#101;]: #diff '```&#10;$ diff -e&#10;$ diff --ed&#10;```&#10;Produce an `ed` script to recreate `$OTHER` from `$FILE`&#10;Robbins, Arnold. _UNIX in a Nutshell_ 4th ed (2005): 59'
[diff -&#69;]: #diff '```&#10;$ diff -E&#10;$ diff --ignore-tab-expansion&#10;```&#10;Ignore differences due to expanding tabs&#10;Robbins, Arnold. _UNIX in a Nutshell_ 4th ed (2005): 60'
[diff -&#102;]: #diff '```&#10;$ diff -f&#10;$ diff --forward-ed&#10;```&#10;Produce an `ed` script to recreate `$FILE` from `$OTHER`&#10;Robbins, Arnold. _UNIX in a Nutshell_ 4th ed (2005): 59'
[diff -&#70;]: #diff '```&#10;$ diff -F $PATTERN&#10;$ diff --show-function-line $PATTERN&#10;```&#10;For context and unified diffs, show the most recent line containing regex `$PATTERN` before each block of changed lines&#10;Robbins, Arnold. _UNIX in a Nutshell_ 4th ed (2005): 60'
[diff -&#104;]: #diff '```&#10;$ diff -h&#10;```&#10;Ignored by GNU `diff`&#10;Robbins, Arnold. _UNIX in a Nutshell_ 4th ed (2005): 59'
[diff -&#105;]: #diff '```&#10;$ diff -i&#10;$ diff --ignore-case&#10;```&#10;Case-insensitive comparison&#10;Robbins, Arnold. _UNIX in a Nutshell_ 4th ed (2005): 59'
[diff -&#108;]: #diff '```&#10;$ diff -l&#10;$ diff --paginate&#10;```&#10;Long format; output is paginated by `pr` so that diff listings for each file begin on a new page.&#10;Robbins, Arnold. _UNIX in a Nutshell_ 4th ed (2005): 59'
[diff -&#76;]: #diff '```&#10;$ diff -L $LABEL&#10;$ diff --label $LABEL&#10;```&#10;For context and unified diffs, print `$LABEL` in place of the filename being compared; use once for `$FILE` and again for `$OTHER`&#10;Robbins, Arnold. _UNIX in a Nutshell_ 4th ed (2005): 60'
[diff -&#110;]: #diff '```&#10;$ diff -n&#10;$ diff --rcs&#10;```&#10;Like `-f`, but counts changed lines the way `rcsdiff` does&#10;Robbins, Arnold. _UNIX in a Nutshell_ 4th ed (2005): 59'
[diff --normal]: #diff '```&#10;$ diff --normal&#10;```&#10;Produce a normal diff (default)&#10;Robbins, Arnold. _UNIX in a Nutshell_ 4th ed (2005): 60'
[diff -&#78;]: #diff '```&#10;$ diff -N&#10;$ diff --new-file&#10;```&#10;Treat nonexistent files as empty&#10;Robbins, Arnold. _UNIX in a Nutshell_ 4th ed (2005): 61'
[diff -&#112;]: #diff '```&#10;$ diff -p&#10;$ diff --show-c-function&#10;```&#10;When handling files in C or C-like languages such as Java, show the function containing each block of changed lines.&#10;Robbins, Arnold. _UNIX in a Nutshell_ 4th ed (2005): 61'
[diff -&#113;]: #diff '```&#10;$ diff -q&#10;$ diff --brief&#10;```&#10;Output only when files differ&#10;Robbins, Arnold. _UNIX in a Nutshell_ 4th ed (2005): 61'
[diff -&#114;]: #diff '```&#10;$ diff -r&#10;$ diff --recursive&#10;```&#10;Run `diff` recursively for files in common subdirectories&#10;Robbins, Arnold. _UNIX in a Nutshell_ 4th ed (2005): 59'
[diff -&#115;]: #diff '```&#10;$ diff -s&#10;$ diff --report-identical-files&#10;```&#10;Report files that are identical&#10;Robbins, Arnold. _UNIX in a Nutshell_ 4th ed (2005): 60'
[diff -&#83;]: #diff '```&#10;$ diff -S $FILENAME&#10;$ diff --starting-file $FILENAME&#10;```&#10;Begin directory comparisons with `$FILE`, skipping files whose filenames alphabetically precede `$FILENAME`&#10;Robbins, Arnold. _UNIX in a Nutshell_ 4th ed (2005): 60'
[diff -&#116;]: #diff '```&#10;$ diff -t&#10;$ diff --expand-tabs&#10;```&#10;Expand tabs in output lines; usefulf or preserving indentation changed by `-c`&#10;Robbins, Arnold. _UNIX in a Nutshell_ 4th ed (2005): 59'
[diff -&#84;]: #diff '```&#10;$ diff -T&#10;$ diff --initial-tab&#10;```&#10;Insert initial tabs into output to line up tabs properly&#10;Robbins, Arnold. _UNIX in a Nutshell_ 4th ed (2005): 61'
[diff -&#117;]: #diff '```&#10;$ diff -u&#10;```&#10;Produce output in "unified `diff`" format, with 3 lines of context&#10;Robbins, Arnold. _UNIX in a Nutshell_ 4th ed (2005): 59'
[diff -&#85;]: #diff '```&#10;$ diff -U $N&#10;$ diff --unified $N&#10;```&#10;Like `-u`, but produces output with `$N` lines of context&#10;Robbins, Arnold. _UNIX in a Nutshell_ 4th ed (2005): 59'
[diff -&#118;]: #diff '```&#10;$ diff -v&#10;$ diff --version&#10;```&#10;Print version number.&#10;Robbins, Arnold. _UNIX in a Nutshell_ 4th ed (2005): 61'
[diff -&#119;]: #diff '```&#10;$ diff -w&#10;$ diff --ignore-all-space&#10;```&#10;Ignore spaces and tabs&#10;Robbins, Arnold. _UNIX in a Nutshell_ 4th ed (2005): 59'
[diff -&#87;]: #diff '```&#10;$ diff -W $N&#10;$ diff --width $N&#10;```&#10;For two-column output (`-y`), produce columns with a maximum width of `$N` characters (130 by default)&#10;Robbins, Arnold. _UNIX in a Nutshell_ 4th ed (2005): 61'
[diff -&#120;]: #diff '```&#10;$ diff -x $PATTERN&#10;$ diff --exclude $PATTERN&#10;```&#10;Do not compare files in a directory whose names match regex `$PATTERN`&#10;Robbins, Arnold. _UNIX in a Nutshell_ 4th ed (2005): 61'
[diff -&#88;]: #diff '```&#10;$ diff -X $FILE&#10;$ diff --exclude-from $FILE&#10;```&#10;Do not compare files in a directory whose names match patterns described in `$FILE`&#10;Robbins, Arnold. _UNIX in a Nutshell_ 4th ed (2005): 61'
[diff -&#121;]: #diff '```&#10;$ diff -y&#10;$ diff --side-by-side&#10;```&#10;Two-column output&#10;Robbins, Arnold. _UNIX in a Nutshell_ 4th ed (2005): 61'

[diff --binary]: #diff '```&#10;$ diff --binary&#10;```&#10;Read and write data in binary mode&#10;Robbins, Arnold. _UNIX in a Nutshell_ 4th ed (2005): 60'
[diff --from-file]: #diff '```&#10;$ diff --from-file $FILE&#10;```&#10;&#10;Robbins, Arnold. _UNIX in a Nutshell_ 4th ed (2005): 60'
[diff --left-column]: #diff '```&#10;$ diff --left-column&#10;```&#10;For two-column output (`-y`, show only the left column of common lines&#10;Robbins, Arnold. _UNIX in a Nutshell_ 4th ed (2005): 60'
[diff --no-ignore-file-name-case]: #diff '```&#10;$ diff --no-ignore-file-name-case&#10;```&#10;Cancel the effect of a previous `--ignore-file-name-case` option&#10;Robbins, Arnold. _UNIX in a Nutshell_ 4th ed (2005): 60'
[diff --sdiff-merge-assist]: #diff '```&#10;$ diff --sdiff-merge-assist&#10;```&#10;Produce `sdiff`-style output. Used by GNU `sdiff` when invoking `diff`.&#10;Robbins, Arnold. _UNIX in a Nutshell_ 4th ed (2005): 61'
[diff --strip-trailing-cr]: #diff '```&#10;$ diff --strip-trailing-cr&#10;```&#10;Remove carriage return characters at the end of input lines.&#10;Robbins, Arnold. _UNIX in a Nutshell_ 4th ed (2005): 61'
[diff --to-file]: #diff '```&#10;$ diff --to-file $FILE&#10;```&#10;Compare each operand to `$FILE`, which may be a directory&#10;Robbins, Arnold. _UNIX in a Nutshell_ 4th ed (2005): 61'
[diff --suppress-common-lines]: #diff '```&#10;$ diff --suppress-common-lines&#10;```&#10;For two-column output (`-y`), do not show common lines.&#10;Robbins, Arnold. _UNIX in a Nutshell_ 4th ed (2005): 61'
[diff --unidirectional-new-file]: #diff '```&#10;$ diff --unidirectional-new-file&#10;```&#10;When doing directory comparisons, if a file is found only in the second directory, pretend it is present but empty in the first one.&#10;Robbins, Arnold. _UNIX in a Nutshell_ 4th ed (2005): 61'

<code>&nbsp;</code>   [`a`][diff -&#97;] [`b`][diff -&#98;] [`c`][diff -&#99;] [`d`][diff -&#100;] [`e`][diff -&#101;] [`f`][diff -&#102;] <code>&nbsp;</code> [`h`][diff -&#104;] [`i`][diff -&#105;] <code>&nbsp;</code> <code>&nbsp;</code> [`l`][diff -&#108;] <code>&nbsp;</code> [`n`][diff -&#110;] <code>&nbsp;</code> [`p`][diff -&#112;] [`q`][diff -&#113;] [`r`][diff -&#114;] [`s`][diff -&#115;] [`t`][diff -&#116;] [`u`][diff -&#117;] [`v`][diff -&#118;] [`w`][diff -&#119;] [`x`][diff -&#120;] [`y`][diff -&#121;] <code>&nbsp;</code>  <br><code>&nbsp;</code>&nbsp;<code>&nbsp;</code> [`B`][diff -&#66;] [`C`][diff -&#67;] [`D`][diff -&#68;] [`E`][diff -&#69;] [`F`][diff -&#70;] <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> [`L`][diff -&#76;] <code>&nbsp;</code> [`N`][diff -&#78;] <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> [`S`][diff -&#83;] [`T`][diff -&#84;] [`U`][diff -&#85;] <code>&nbsp;</code> [`W`][diff -&#87;] [`X`][diff -&#88;] <code>&nbsp;</code> <code>&nbsp;</code> 

[`binary`][diff --binary]
[`from-file`][diff --from-file]
[`left-column`][diff --left-column]
[`no-ignore-file-name-case`][diff --no-ignore-file-name-case]
[`sdiff-merge-assist`][diff --sdiff-merge-assist]
[`strip-trailing-cr`][diff --strip-trailing-cr]
[`to-file`][diff --to-file]
[`suppress-common-lines`][diff --suppress-common-lines]
[`unidirectional-new-file`][diff --unidirectional-new-file]

### `fold`
Display text of `$FILE`, wrapping long lines
```sh
fold $FILE
```
### `grep`
[grep -&#99;]:  #grep '```&#10;$ grep -c&#10;$ grep --count&#10;```&#10;Display only a count of matched lines, but not the lines themselves.&#10;Haeder, Adam. _LPI Linux Certification in a Nutshell_. 2010.: 126'
[grep -&#104;]: #grep '```&#10;$ grep -h&#10;```&#10;Display matched lines, but do not include filenames for multiple file input.&#10;Haeder, Adam. _LPI Linux Certification in a Nutshell_. 2010.: 126'
[grep -&#105;]: #grep '```&#10;$ grep -i&#10;```&#10;Case-insensitive search.&#10;Haeder, Adam. _LPI Linux Certification in a Nutshell_. 2010.: 126'
[grep -&#110;]: #grep '```&#10;$ grep -n&#10;$ grep --line-number&#10;```&#10;Display matched lines prefixed with their line numbers.&#10;Haeder, Adam. _LPI Linux Certification in a Nutshell_. 2010.: 126'
[grep -&#118;]: #grep '```&#10;$ grep -v&#10;$ grep --invert-match&#10;```&#10;Print all lines that do not match `$PATTERN`&#10;Haeder, Adam. _LPI Linux Certification in a Nutshell_. 2010.: 126'
[grep -&#69;]:  #grep '```&#10;$ grep -E&#10;```&#10;Interpret `$PATTERN` as an extended regular expression&#10;Haeder, Adam. _LPI Linux Certification in a Nutshell_. 2010.: 126'
[grep -&#108;]: #grep '```&#10;$ grep -l&#10;$ grep --files-with-matches&#10;```&#10;Display filenames that match the pattern, rather than the lines of matches themselves&#10;Rothwell, William. _CompTIA Linux+/LPIC-1 Portable Command guide_.: 100'
[grep -&#119;]: #grep '```&#10;$ grep -w&#10;```&#10;Match whole words only&#10;Rothwell, William. _CompTIA Linux+/LPIC-1 Portable Command guide_.: 100'
[grep -&#114;]: #grep '```&#10;$ grep -r&#10;```&#10;Recursively search all the files in the directory structure&#10;Rothwell, William. _CompTIA Linux+/LPIC-1 Portable Command guide_.: 100'
[grep -&#102;]: #grep '```&#10;$ grep -f&#10;```&#10;Fixed strings; all characters in the pattern will be treated as regular characters&#10;Rothwell, William. _CompTIA Linux+/LPIC-1 Portable Command guide_.: 100'
[grep -&#65;]:  #grep '```&#10;$ grep -A $N&#10;```&#10;print `$N` lines of trailing context from the file after each match'
[grep -&#66;]:  #grep '```&#10;$ grep -B $N&#10;```&#10;print `$N` lines of leading context from the file after each match'
[grep -&#67;]:  #grep '```&#10;$ grep -C $N&#10;```&#10;print `$N` lines of leading and trailing context surrounding each match'
[grep -&#69;]:  #grep '```&#10;$ grep -E&#10;$ grep --extended-regexp&#10;```&#10;force grep to use extended regular expressions, making it similar to `egrep`'
[grep -&#70;]:  #grep '```&#10;$ grep -F&#10;$ grep --fixed-strings&#10;```&#10;force grep to interpret pattern as fixed strings, making it similar to `fgrep`'
[grep -&#72;]:  #grep '```&#10;$ grep -H&#10;```&#10;always print filename headers with output lines'

<code>&nbsp;</code>   <code>&nbsp;</code> <code>&nbsp;</code> [`c`][grep -&#99;] <code>&nbsp;</code> <code>&nbsp;</code> [`f`][grep -&#102;] <code>&nbsp;</code> [`h`][grep -&#104;] [`i`][grep -&#105;] <code>&nbsp;</code> <code>&nbsp;</code> [`l`][grep -&#108;] <code>&nbsp;</code> [`n`][grep -&#110;] <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> [`r`][grep -&#114;] <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> [`v`][grep -&#118;] [`w`][grep -&#119;] <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code>  <br><code>&nbsp;</code>&nbsp;[`A`][grep -&#65;] [`B`][grep -&#66;] [`C`][grep -&#67;] <code>&nbsp;</code> [`E`][grep -&#69;] [`F`][grep -&#70;] <code>&nbsp;</code> [`H`][grep -&#72;] <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> 

### `head`
[head -&#99;]: #head '```&#10;$ head -c $N&#10;```&#10;Print the first `$N` bytes. If `$N` is followed by "k" or "m", the first `$N` kilobytes or megabytes, respectively.&#10;Haeder, Adam. _LPI Linux Certification in a Nutshell_. 2010.: 80'
[head -&#110;]: #head '```&#10;$ head -n $N&#10;```&#10;Print the first `$N` lines (10 by default)&#10;Haeder, Adam. _LPI Linux Certification in a Nutshell_. 2010.: 80'

<code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> [`c`][head -&#99;] <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> [`n`][head -&#110;] <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> 

Print first 8 characters of `$FILE`
```sh
head -c8 $FILE
```
### `nl`
[nl -&#98;]: #nl '```&#10;$ nl -b $STYLE&#10;$ nl --body-numbering $STYLE&#10;```&#10;Set body numbering style to `$STYLE`:&#10;  - `A`: Number all lines&#10;  - `t`: Number only nonempty lines&#10;  - `n`: Do not number lines&#10;  - `p$REGEXP`: Number only lines that contain a match for `$PATTERN`&#10;Haeder, Adam. _LPI Linux Certification in a Nutshell_. 2010.: 81'
[nl -&#102;]: #nl '```&#10;$ nl -f $STYLE&#10;```&#10;Set footer numbering style to `$STYLE`:&#10;  - `A`: Number all lines&#10;  - `t`: Number only nonempty lines&#10;  - `n`: Do not number lines&#10;  - `p$REGEXP`: Number only lines that contain a match for `$PATTERN`&#10;Haeder, Adam. _LPI Linux Certification in a Nutshell_. 2010.: 81'
[nl -&#104;]: #nl '```&#10;$ nl -h $STYLE&#10;```&#10;Set header numbering style to `$STYLE`:&#10;  - `A`: Number all lines&#10;  - `t`: Number only nonempty lines&#10;  - `n`: Do not number lines&#10;  - `p$REGEXP`: Number only lines that contain a match for `$PATTERN`&#10;Haeder, Adam. _LPI Linux Certification in a Nutshell_. 2010.: 81'

<code>&nbsp;</code> <code>&nbsp;</code> [`b`][nl -&#98;] <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> [`f`][nl -&#102;] <code>&nbsp;</code> [`h`][nl -&#104;] <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> 

Number all lines, including blank lines
```sh
nl -b a file
nl --body-numbering=a file
```
### `paste`
Merge lines of files

Make a .csv file from two lists
```sh
paste -d ',' file1 file2
```
Transpose rows
```sh
paste -s file1 file2
```
### `sed`
[sed -&#110;]: #sed '```&#10;$ sed -n&#10;$ sed --quiet&#10;```&#10;Suppress automatic printing of pattern space'
[sed -&#101;]: #sed '```&#10;$ sed -e&#10;```&#10;When providing more than one instruction, this flag precedes each one'
[sed -&#102;]: #sed '```&#10;$ sed -f&#10;$ sed --file&#10;```&#10;Read from a "command file" or "program file" (i.e., a sed script)'
[sed -&#105;]: #sed '```&#10;$ sed -i&#10;```&#10;Edit the file in-place instead of outputting to STDOUT'

<code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> [`e`][sed -&#101;] [`f`][sed -&#102;] <code>&nbsp;</code> <code>&nbsp;</code> [`i`][sed -&#105;] <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> [`n`][sed -&#110;] <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> 

Run sed commands in `$SCRIPT` on `$FILE`
```sh
sed -f $SCRIPT $FILE
```
Suppress automatic printing of pattern space
```sh
sed -n
sed --quiet
sed --silent
```
`sed` ("Stream-oriented editor") is typically used for applying repetitive edits across all lines of multiple files. In particular it is, alongside `awk` one of the two primary commands which accept regular expressions in Unix systems. 

Script syntax | Effect
---           | ---
`#`           | comments begin with **octothorpe**
`#n`          | If first line of script begins with these two characters, it is equivalent to using the `-n` flag

Invocation syntax has two forms:
```sh
# Inline
sed options 'instruction' $FILE

# "Command file"
sed options -f $SCRIPT $FILE
```
`sed` instructions are made of **addresses** and **procedures** . Sources do not use consistent terminology to describe the two components of most sed commands:

:---                                | :---
`sed 'pattern {procedure}' file`    | [[SA](../sources/README.md): 14]
`sed 'address {action}' file`       | [[YUG](../sources/README.md): 449]
`sed 'address {instruction}' file`  | [[PGL](../sources/README.md): 565]

Zero, one, or two addresses can precede a procedure.
  - In the absence of an address, the procedure is executed over every line of input
  - With one address, the procedure will be executed over every line of input that matches
  - With two addresses, the procedure will be executed over groups of lines whereby:
    - The first address selects the first line in the first group
    - The second address selects the next subsequent line that it matches, which becomes the last line in the first group
    - If no match for the second address is found, it point to the end of the file
    - After the match, the selection process for the next group begins by searching for a match to the first address
Addressing can be done in one of two ways:
  1. **Line addressing**, specifying line numbers separated by a comma (e.g. `3,7p`); `$` represents the last line of input
  2. **Context addressing**, using a regular expression enclosed by forward slashes (e.g. `/From:/p`)

Procedure   | Description
:---        | :---  
`!c`        | negation operator can be used with any procedure {c}
`a`         | append text to the addressed lines
`d`         | cause sed not to display the addressed lines ("delete"); can emulate `grep -v`, which selects lines which do _not_ match the specified pattern
`i`         | prepend text to the addressed lines
`n`         | write out the currently selected line if appropriate, read the next input line, and start processing the new line with the next instruction
`x`         | where {x} is a number, specifying occurrence (e.g. `2` would replace only the second occurrence of each pattern per line)
`g`         | replace all occurrences
`p`         | print original content (e.g. `sed -n 's/test/another test/p' myfile`)
`w outputfile`        | write results to {outputfile} (e.g. `sed 's/test/another test/w output' myfile`)
`s/pattern/replacement/flags`         | replace regex {pattern} with {replacement} ("substitute")
`g`         | replace **all** instances of the search pattern with the replacement, rather than the first instance (global)
`&`         | known as the **repeated pattern**, represents the represents the entire source string; the only special character used in the replacement string - all other characters are treated literally

Edit the file in-place, but save a backup copy of the original with {suffix} appended to - the filename
```sh
-i=suffix
```
Display first 3 lines <sup>[YUG](https://github.com/jasper-zanjani/tree/master/sources/README.md): 450</sup>
```sh
sed '3q' emp.lst
```
Display first 5 lines, similar to `head -5 emp.lst` [[PGL](../sources/README.md):569]
```sh
sed '5q' new
```
Pipe output of `ps` to `sed`, displaying top 10 memory-intensive processes
```sh
ps axch -o cmd,%mem --sort=-%mem | sed 11q
```
Pipe output of `ps` to `sed`, displaying top 10 CPU-intensive processes
```sh
ps axch -o cmd:15,%cpu --sort=-%cpu | sed 11q
```
Display first two lines of file
Without `-n`, each line will be printed twice
```sh
sed -n '1,2p' emp.lst
```
Prepending `!` to the procedure reverses the sense of the command <sup>[YUG](https://github.com/jasper-zanjani/tree/master/sources/README.md): 450</sup>
```sh
sed -n '3,$!p' emp.lst
```
Display a range of lines
```sh
sed -n '9,11p' emp.lst
```
Use the `-e` flag to precede multiple instructions
```sh
sed -n -e '1,2p' -e '7,9p' -e '$p' emp.lst
```
Delete lines
Delete second line alone
```sh
sed '2d' myfile
```
Delete a range of lines: from the 2nd through the 3rd
```sh
sed '2,3d' myfile
```
Delete a range of lines, from the first occurrence of 'second' to the line with the first occurrence of 'fourth'
```sh
sed '/second/,/fourth/d' myfile
```
Print all of a file except for specific lines
Suppress any line with 'test' in it
```sh
sed '/test/d' myfile
```
Suppress from the 3rd line to EOF
```sh
sed '3,$d' myfile
```
Replace text
Replace the first instance of the `|` character with `:` and display the first two lines [[YUG](../sources/README.md):455]
```sh
sed 's/|/:/ emp.lst | head -2
```
Replace all instances of the `|` character with `:`, displaying the first two lines [[YUG](../sources/README.md):455]
```sh
sed 's/|/:/g' emp.lst | head -2
```
Substitute HTML tags:
```sh
sed 's/<I>/<EM>/g'
```
These commands will replace "director" with "executive director"
```sh
sed 's/director/executive director/' emp.lst
```
```sh
sed 's/director/executive &/' emp.lst
```
```sh
sed '/director/s//executive &/' emp.lst
```
[[YUG](../sources/README.md): 456-457]
Searching for text\
Equivalent to `grep MA *`
```sh
sed -n '/MA/p' *
```
Stringing sed statements together with pipe
Take lines beginning with "fake" and remove all instances of "fake.", piping them... remove all parentheses with content and count lines of output (results)
```sh
sed -n '/^fake/s/fake\.//p' * | sed -nr 's/\(.*\)//p' | wc -l
```
Take lines of all files in CWD beginning with "fake" and remove all instances of string "fake." Then remove all parentheses with any content within them and print only the top 10 lines
```sh
sed -ne '/^fake/p' * | sed -n 's/fake\.//p' | sed -nr 's/\(.*\)//p' | sed 11q
```
Count the number of pipes replaced by piping output to `cmp`, which will use the `-l` option to output byte numbers of differing values, then counting the lines of output (YUG:456)
```sh
sed 's/|/:/g' emp.lst | cmp -l - emp.lst | wc -l
```
### `seq`
Sequence from 1 to 15
```sh
seq -f "%03g" 15
```
Sequence from 5 to 99, separated by a space instead of a newline
```sh
seq -s " " 5 99
```
Sequence every third number from 5 to 20
```sh
seq 5 320
```
Sequence from 1 to 8
```sh
seq 8
```
### `shuf`
Print random selection of integers from {x} to {y} (inclusive) without replacement
```sh
shuf -i x-y
```
Print random selection of integers from {x} to {y} (inclusive), with replacement
```sh
shuf -i x-y -r
```
Shuffle items separated by newline in file `cards.txt`, displaying only one <sup>[10](sources.md)</sup>
```sh
shuf -n 1 items.txt
```
### `sort`
[sort -&#102;]: #sort '```&#10;$ sort -f&#10;```&#10;Case-insensitive sort&#10;Haeder, Adam. _LPI Linux Certification in a Nutshell_. 2010.: 84'
[sort -&#107;]: #sort '```&#10;$ sort -k $N,$M&#10;```&#10;Sort on the key starting at `$N` and (optionally) ending at `$M`&#10;Haeder, Adam. _LPI Linux Certification in a Nutshell_. 2010.: 84'
[sort -&#110;]: #sort '```&#10;$ sort -n&#10;```&#10;Sort numerically&#10;Haeder, Adam. _LPI Linux Certification in a Nutshell_. 2010.: 85'
[sort -&#114;]: #sort '```&#10;$ sort -r&#10;```&#10;Sort in reverse order&#10;Haeder, Adam. _LPI Linux Certification in a Nutshell_. 2010.: 85'
[sort -&#116;]: #sort '```&#10;$ sort -t $SEP&#10;```&#10;Use `$SEP` as the key separator (whitespace by default)&#10;Haeder, Adam. _LPI Linux Certification in a Nutshell_. 2010.: 85'
[sort -&#104;]: #sort '```&#10;$ sort -h&#10;```&#10;Human-based numeric sort (i.e. "2K" is lower than "1G")&#10;Rothwell, William. _CompTIA Linux+/LPIC-1 Portable Command guide_.: 66'
[sort -&#77;]: #sort '```&#10;$ sort -M&#10;```&#10;Month-based sort&#10;Rothwell, William. _CompTIA Linux+/LPIC-1 Portable Command guide_.: 66'
[sort -&#117;]: #sort '```&#10;$ sort -u&#10;```&#10;Remove duplicate lines&#10;Rothwell, William. _CompTIA Linux+/LPIC-1 Portable Command guide_.: 66'

<code>&nbsp;</code>   <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> [`f`][sort -&#102;] <code>&nbsp;</code> [`h`][sort -&#104;] <code>&nbsp;</code> <code>&nbsp;</code> [`k`][sort -&#107;] <code>&nbsp;</code> <code>&nbsp;</code> [`n`][sort -&#110;] <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> [`r`][sort -&#114;] <code>&nbsp;</code> [`t`][sort -&#116;] [`u`][sort -&#117;] <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code>  <br><code>&nbsp;</code>&nbsp;<code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> [`M`][sort -&#77;] <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> 

Sort by space-delimited columns. Processes consuming the most memory will be at the bottom <sup>[23](sources.md)</sup>
```sh
ps aux | sort -nk 4
```
Processes consuming the most CPU will be at the bottom
```sh
ps aux | sort -nk 3
```
### `tail`
Output last lines beginning at 30th line from the start
```sh
tail -n=+30
tail --lines=+30
```
### `tr`
[tr -&#99;]: #tr '```&#10;$ tr -c&#10;```&#10;Use the complement of (or all characters not in) `$STRING`&#10;Haeder, Adam. _LPI Linux Certification in a Nutshell_. 2010.: 88'
[tr -&#100;]: #tr '```&#10;$ tr -d&#10;```&#10;Delete characters in `$STRING` from the output&#10;Haeder, Adam. _LPI Linux Certification in a Nutshell_. 2010.: 88'
[tr -&#115;]: #tr '```&#10;$ tr -s&#10;```&#10;Squeeze out repeated output characters in `$STRING`&#10;Haeder, Adam. _LPI Linux Certification in a Nutshell_. 2010.: 88'

<code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> [`c`][tr -&#99;] [`d`][tr -&#100;] <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> [`s`][tr -&#115;] <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> 

Change the case of a string [[23](sources.md)]
```sh
tr [:upper:] [:lower:]
```
Remove a character or set of characters from a string or line of output
```sh
tr -d "text"
```
### `wc`
[wc -&#99;]: #wc '```&#10;$ wc -c&#10;```&#10;Display only the number of bytes&#10;Rothwell, William. _CompTIA Linux+ Portable Command Guide_.: 128'
[wc -&#109;]: #wc '```&#10;$ wc -m&#10;```&#10;Display only the number of characters&#10;Rothwell, William. _CompTIA Linux+ Portable Command Guide_.: 128'
[wc -&#108;]: #wc '```&#10;$ wc -l&#10;```&#10;Display only the number of lines&#10;Rothwell, William. _CompTIA Linux+ Portable Command Guide_.: 128'
[wc -&#119;]: #wc '```&#10;$ wc -w&#10;```&#10;Display only the number of words&#10;Rothwell, William. _CompTIA Linux+ Portable Command Guide_.: 128'

<code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> [`c`][wc -&#99;] <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> [`l`][wc -&#108;] [`m`][wc -&#109;] <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> [`w`][wc -&#119;] <code>&nbsp;</code> <code>&nbsp;</code> <code>&nbsp;</code> 
## Virtualization
[virt-install]: #virt-install '`virt-install`&#10;Command-line tool for creating new KVM, Xen, or Linux container guests using the libvirt hypervisor management library'
[virt-manager]: #virt-manager '`virt-manager`&#10;"Virtual Machine Manager", GUI tool for managing VMs developed by Red Hat'

[`virt-install`][virt-install] 
[`virt-manager`][virt-manager] 

## X Windows System
[cvt]:                         #cvt '```&#10;$ cvt&#10;```&#10;&#10;Calculate VESA CVT mode lines'
[x]:                           #x                              '```&#10;$ x&#10;```&#10;Start the graphical interface from the command-line'
[xdpyinfo]:                    #xdpyinfo                       '```&#10;$ xdpyinfo&#10;```&#10;Show detailed information about display'
[xfs]:                         #xfs                            '```&#10;$ xfs&#10;```&#10;X fonts server; small daemon that sends fonts to clients on both local and remote systems.&#10;Haeder, Adam. _LPI Linux Certification in a Nutshell_. 2010.: 307'
[xhost]:                       #xhost                          '```&#10;$ xhost&#10;```&#10;Set access controls to X server'
[xlsclients]:                  #xlsclients                     '```&#10;$ xlsclients&#10;```&#10;Determine what applications are running on the legacy X11 server provided with Wayland.'
[xmodmap]:                     #xmodmap                        '```&#10;$ xmodmap&#10;```&#10;Utility for modifying keymaps and pointer button mappings in X'
[xorg]:                        #xorg                           '```&#10;$ xorg&#10;```&#10;Full featured X server that was originally designed for UNIX and UNIX-like operating systems running on Intel x86 hardware'
[xrandr]:                      #xrandr                         '```&#10;$ xrandr&#10;```&#10;Set size, orientation, and reflection of video output'
[xset]:                        #xset                           '```&#10;$ xset&#10;```&#10;Set various user preference options of the display&#10;Haeder, Adam. _LPI Linux Certification in a Nutshell_. 2010.: 307'
[xwininfo]:                    #xwininfo                       '```&#10;$ xwininfo&#10;```&#10;Utility that provides information about a clicked window, including dimensions, position, etc'
[`cvt`][cvt] 
[`x`][x] 
[`xdpyinfo`][xdpyinfo] 
[`xfs`][xfs] 
[`xhost`][xhost] 
[`xlsclients`][xlsclients] 
[`xmodmap`][xmodmap] 
[`xorg`][xorg] 
[`xrandr`][xrandr] 
[`xset`][xset] 
[`xwininfo`][xwininfo]

### `X`
Test X11 with the config file automatically generated after `Xorg -configure`
```sh
X -config $HOME/xorg.conf.new
```
### `xhost`
Enable access control to X server
```sh
xhost -
```
Disable access control to X server, allowing clients from any host to connect (not unsafe if you use a firewall that allows only SSH)
```sh
xhost +
```
Add `$HOST` to list of authorized clients for X server
```sh
xhost +$HOST
```
Remove `$HOST` from list of authorized clients for X server
```sh
xhost -$HOST
```
Add `$USER` to ACL
```sh
xhost si:localuser:$USER
```
### `xmodmap`
Replacing Caps Lock with Escape
```
! Swap caps lock and escape
remove Lock = Caps_Lock
keysym Escape = Caps_Lock
keysym Caps_Lock = Escape
add Lock = Caps_Lock
```
### `Xorg`
Enable automatic configuration of X11 server
```sh
Xorg -configure
```
### `xrandr`
Change resolution of DisplayPort1 to 1920x1080
```sh
xrandr --output DP1 --mode 1920x1080
```
Disable VGA1 output
```sh
xrandr --output VGA1 --off
```
Display current state of the system
```sh
xrandr -q  --query
```
### `xset`
Dynamically add fonts [<sup>Haeder: 307</sup>][Haeder]
```ssh
xset fp+ /usr/local/fonts
```
# Linux configs
[/etc/aliases]:                                     #etcaliases                   '```&#10;$ cat /etc/aliases&#10;```&#10;Systemwide email aliases'
[/etc/anacrontab]:                                  #etcanacrontab                '```&#10;/etc/anacrontab&#10;```&#10;Describes jobs controlled by `anacron`'
[/etc/apt/sources.list]: #etcaptsourceslist '```&#10;$ cat /etc/apt/sources.list&#10;$ cat /etc/apt/sources.list.d/*&#10;```&#10;`apt` repository definitions'
[/etc/crontab]:                                     #etccrontab                   '```&#10;$ cat /etc/crontab&#10;$ cat /etc/cron.allow /etc/cron.deny /etc/cron.daily /etc/cron.hourly /etc/cron.monthly /etc/cron.weekly /etc/cron.d/*&#10;```&#10;Describes jobs controlled by `cron`'
[/etc/files.dns]:                                   #etcfiles.dns                 '```&#10;$ cat /etc/files.dns&#10;```&#10;NIS+ servers for Solaris servers'
[/etc/fstab]:                                       #etcfstab                     '```&#10;$ cat /etc/fstab&#10;```&#10;Filesystems to be mounted by the system at boot'
[/etc/group]:                                       #etcgroup                     '```&#10;$ cat /etc/group&#10;```&#10;Colon-delimited file describing group membership'
[/etc/hostname]:                                    #etchostname                  '```&#10;$ cat /etc/hostname&#10;```&#10;Contains hostname'
[/etc/hosts]:                                       #etchosts                     '```&#10;$ cat /etc/hosts&#10;```&#10;Global hostnames'
[/etc/hotplug/usb/*]:                               #etchotplugusb             '```&#10;$ cat /etc/hotplug/usb/*&#10;```&#10;Location of scripts executed when a hotplug device is inserted'
[/etc/init.d/*]:                                    #etcinitd                  '```&#10;$ cat /etc/init.d/*&#10;```&#10;Sysvinit scripts run during startup and shutdown'
[/etc/inittab]:                                     #etcinittab                   '```&#10;$ cat /etc/inittab&#10;```&#10;Initialization table'
[/etc/ld.so.conf]:                                  #etcld.so.conf                '```&#10;$ cat /etc/ld.so.conf&#10;$ cat /etc/ld.so.conf.d/*&#10;```&#10;Specifies directories containing shared libraries'
[/etc/lightdm.conf]:                                #etclightdmconf              '```&#10;$ cat /etc/lightdm.conf&#10;$ cat /etc/lightdm/users.conf&#10;```&#10;LightDM'
[/etc/login.defs]:                                  #etclogin.defs                '```&#10;$ cat /etc/login.defs&#10;$ cat /etc/default/useradd&#10;```&#10;Default configuration values for `useradd`, `userdel`, `usermod` and `groupadd`'
[/etc/logrotate.conf]:                              #etclogrotate.conf            '```&#10;$ cat /etc/logrotate.conf&#10;```&#10;'
[/etc/lsb-release]:                                 #etclsb-release               '```&#10;$ cat /etc/lsb-release&#10;```&#10;Ubuntu version'
[/etc/modprobe.conf]:                               #etcmodprobeconf                                 '```&#10;$ cat /etc/modprobe.conf&#10;$ cat /etc/modprobe.d/*&#10;```&#10;Configuration files for `modprobe`'
[/etc/mtab]:                                        #etcmtab                      '```&#10;$ cat /etc/mtab&#10;```&#10;Updated dynamically with information about currently mounted filesystems'
[/etc/network]:                                     #etcnetwork                   '```&#10;$ cat /etc/network&#10;```&#10;Global network settings'
[/etc/nsswitch.conf]:                               #etcnsswitchconf             '```&#10;$ cat /etc/nsswitch.conf&#10;```&#10;Controls lookup system beyond just DNS'
[/etc/passwd]:                                      #etcpasswd                    '```&#10;$ cat /etc/passwd&#10;```&#10;Text-based database of information about users that may log into the system'
[/etc/postfix/main.cf]:                             #etcpostfixmaincf           '```&#10;$ cat /etc/postfix/main.cf&#10;```&#10;Postfix config'
[/etc/rc.d/rc.sysinit]:                             #etcrcdrcsysinit           '```&#10;$ cat /etc/rc.d/rc.sysinit&#10;```&#10;First script run by `init`'
[/etc/resolv.conf]:                                 #etcresolvconf               '```&#10;$ cat /etc/resolv.conf&#10;```&#10;Nameserver definitions (maximum of 6 domains with total of 256 characters)'
[/etc/samba/smb.conf]:                              #etcsambasmbconf            '```&#10;$ cat /etc/samba/smb.conf&#10;```&#10;Samba configuration file'
[/etc/services]:                                    #etcservices                  '```&#10;$ cat /etc/services&#10;```&#10;Used to resolve port numbers'
[/etc/shadow]:                                      #etcshadow                    '```&#10;$ cat /etc/shadow&#10;```&#10;Colon-delimited file containing password hashes for every user listed in /etc/passwd'
[/etc/ssh/ssh_config]:                              #etcsshssh_config            '```&#10;$ cat /etc/ssh/ssh_config&#10;```&#10;System-wide configuration file for OpenSSH which allows you to set options that modify the operation of the client programs'
[/etc/ssh/sshd_config]:                             #etcsshsshd_config           '```&#10;$ cat /etc/ssh/sshd_config&#10;```&#10;System-wide configuration file for OpenSSH which allows you to set options that modify the operation of the daemon'
[/etc/ssmtp/ssmtp.conf]:                            #etcssmtpssmtpconf          '```&#10;$ cat /etc/ssmtp/ssmtp.conf&#10;```&#10;'
[/etc/sysconfig/desktop]:                           #etcsysconfigdesktop         '```&#10;$ cat /etc/sysconfig/desktop&#10;```&#10;Specify display manager and desktops on Red Hat'
[/etc/sysconfig/iptables]:                          #etcsysconfigiptables        '```&#10;$ cat /etc/sysconfig/iptables&#10;```&#10;Where `iptables` configuration is written upon running `iptables-save`'
[/etc/sysconfig/network-scripts/]:                  #etcsysconfignetwork-scripts                    '```&#10;$ cat /etc/sysconfig/network-scripts/&#10;```&#10;Directory containing file configurations for each network device you may have or want to add on your system'
[/etc/syslog-ng/syslog-ng.conf]:                    #etcsyslog-ngsyslog-ngconf  '```&#10;$ cat /etc/syslog-ng/syslog-ng.conf&#10;```&#10;'
[/etc/xinetd.conf]:                                 #etcxinetdconf               '```&#10;$ cat /etc/xinetd.conf&#10;$ cat /etc/xinetd/*&#10;```&#10;Master `xinetd` configuration file'
[/etc/yum.conf]:                                    #etcyumconf                  '```&#10;$ cat /etc/yum.conf&#10;$ cat /etc/yum.repos.d/*&#10;```&#10;Repository definitions with filenames that follow the pattern "*.repo"'
[~/.forward]:                                       #~/.forward                     '```&#10;$ cat ~/.forward&#10;```&#10;Forwarding to only one address'
[~/.gnupg/pubring.gpg]:                             #~/.gnupg/pubringgpg           '```&#10;$ cat ~/.gnupg/pubring.gpg&#10;```&#10;Default storage for public `gpg` keyrings'
[~/.ssh/known_hosts]:                               #~/.ssh/known_hosts             '```&#10;$ cat ~/.ssh/known_hosts&#10;```&#10;Public keys of SSH hosts'
[~/xorg.conf]:                                      #~/xorg.conf                    '```&#10;$ cat ~/xorg.conf&#10;```&#10;User config which overrides system defaults'
[/etc/bluetooth/main.conf]: #etcbluetoothmainconf "Bluetooth config"
[/etc/hotplug/usb/]: # "Location of scripts executed when a hotplug device is inserted"
[/etc/init.d/]: # "sysvinit scripts run during startup and shutdown"
[/etc/mail/sendmail.mc]: # "Sendmail config which is compiled to sendmail.cf"
[/etc/mail/sendmail.cf]: # "Sendmail config which is compiled from sendmail.mc"
[/etc/skel/]: # "Default configs for new users"
[/etc/systemd/system/]: #systemd-service-files "systemd service files"
[/etc/udev/hwdb.bin]: # "udev hardware database"
[/lib/systemd/system/]: # "directory containing unit configs"
[/usr/share/config/kdm/kdmrc]: # "KDM config"
[/usr/share/lightdm/lightdm.conf.d/]: # "lightdm configs, whose filenames follow the pattern \"50-*.conf\""
[/usr/share/hwdata/pci.ids]: commands/README.md#lspci "PCI device names displayed by lspci"
[/var/log/dmesg]: # "Kernel ring buffer information"
[/var/log/audit/audit.log]: # "Audit file for SELinux, SSH"
[/var/spool/cron/]: # "Contains user crontables"
[/boot/grub/grub.cfg]: # "GRUB config file"
[/etc/selinux/config]: #etcselinuxconfig '/etc/selinux/config&#10;SELinux configuration file&#10;Nemeth, Evi. _Unix and Linux System Administration Handbook, 5th ed._: 87'


## `/etc`
[`aliases`][/etc/aliases] 
[`anacrontab`][/etc/anacrontab]
[`cmd.allow`](commands/README.md#xinetd) 
[`cmd.deny`](commands/README.md#xinetd) 
[`crontab`][/etc/crontab]
[`files.dns`][/etc/files.dns] 
[`fstab`][/etc/fstab] 
[`group`][/etc/group] 
[`hostname`][/etc/hostname] 
[`hosts`][/etc/hosts] 
[`inittab`][/etc/inittab] 
[`ld.so.conf`][/etc/ld.so.conf]
[`lightdm.conf`][/etc/lightdm.conf]
[`login.defs`][/etc/login.defs] 
[`logrotate.conf`][/etc/logrotate.conf] 
[`lsb-release`][/etc/lsb-release] 
[`modprobe.conf`][/etc/modprobe.conf]
[`mtab`][/etc/mtab] 
[`network`][/etc/network] 
[`nsswitch.conf`][/etc/nsswitch.conf] 
[`passwd`][/etc/passwd]
[`resolv.conf`][/etc/resolv.conf] 
[`services`][/etc/services] 
[`shadow`][/etc/shadow] 
[`sudoers`](#etcsudoers) 
[`xinetd.conf`][/etc/xinetd.conf] 
[`yum.conf`][/etc/yum.conf]

**`ansible`**
[`ansible.conf`][/etc/ansible/ansible.conf]

**`apt`**
[`sources.list`][/etc/apt/sources.list] 

**`bluetooth`**
[`input.conf`](#etcbluetoothinputconf)
[`main.conf`][/etc/bluetooth/main.conf]

**`mail`**
[`sendmail.cf`][/etc/mail/sendmail.cf]
[`sendmail.mc`][/etc/mail/sendmail.mc] 

**`rc.d`**
[`rc.sysinit`][/etc/rc.d/rc.sysinit] 

**`ssh`**
[`ssh_config`][/etc/ssh/ssh_config] 
[`sshd_config`][/etc/ssh/sshd_config] 

**`sysconfig`** 
[`desktop`][/etc/sysconfig/desktop] 
[`iptables`][/etc/sysconfig/iptables] 
[`network-scripts/`][/etc/sysconfig/network-scripts/] 

**`lvm`**
[`.cache`][/etc/lvm/.cache]

**`postfix`**
[`main.cf`][/etc/postfix/main.cf] 

**`samba`**
[`smb.conf`][/etc/samba/smb.conf]

**`selinux`**
[`config`][/etc/selinux/config] 

[**`skel`**][/etc/skel/]

**`ssmtp`**
[`ssmtp.conf`][/etc/ssmtp/ssmtp.conf] 

**`syslog-ng`** 
[`syslog-ng.conf`][/etc/syslog-ng/syslog-ng.conf] 

[**`systemd/system`**][/etc/systemd/system/] 

**`udev`** 
[`hwdb.bin`][/etc/udev/hwdb.bin] 

## /home
`.bashrc` 
[`.forward`][~/.forward] 
[`.mailrc`](#mailrc) 
`.vimrc` 
[`xorg.conf`][~/xorg.conf] 
**`.gnupg`** 
[`pubring.gpg`][~/.gnupg/pubring.gpg] 
**`.ssh`** 
[`known_hosts`][~/.ssh/known_hosts] 
###### /usr
[`local/lib/systemd/system/`](#systemd-service-files) 
[`share/config/kdm/kdmrc`][/usr/share/config/kdm/kdmrc] 
[`share/hwdata/pci.ids.gz`][/usr/share/hwdata/pci.ids] 
[`share/hwdata/pci.ids`][/usr/share/hwdata/pci.ids] 
[`share/lightdm/lightdm.conf.d/`][/usr/share/lightdm/lightdm.conf.d/] 
###### /var
[`log/audit/audit.log`][/var/log/audit/audit.log] 
[`log/dmesg`][/var/log/dmesg] 
[`spool/cron/`][/var/spool/cron/] 
###### /lib
[`systemd/system/`][/lib/systemd/system/] 
###### Boot
[`/boot/grub/grub.cfg`][/boot/grub/grub.cfg] 

#### SystemD service files
[https://www.redhat.com/sysadmin/replacing-rclocal-systemd]: https://www.redhat.com/sysadmin/replacing-rclocal-systemd "Red Hat: \"Replacing `rc.local` in systemd Linux systems\""

Creating a service file [<sup>ref</sup>][https://www.redhat.com/sysadmin/replacing-rclocal-systemd]
```ini
[Unit]
Description=Runs /usr/local/bin/mystartup.sh

[Service]
ExecStart=/usr/local/bin/mystartup.sh

[Install]
WantedBy=multi-user.target
```
###### crontab
Directive             | Effect
---                   | ---
`@hourly`             | equivalent to `0 * * * *`
`@midnight` `@daily`  | equivalent to `0 0 * * *`
`@weekly`             | equivalent to `0 0 * * 0`
`@monthly`            | equivalent to `0 0 1 * *`
`@annually` `@yearly` | equivalent to `0 0 1 1 *`
`@reboot`             | run at startup

Run /root/backup.sh at 0300 everyday
```sh
0 3 * * * /root/backup.sh
```
Run /path/to/script.sh at 16:30 on the 2nd of every month
```sh
30 16 2 * * /path/to/script.sh
```
Run /scripts/phpscript.php at 22:00 every weekday
```sh
0 22 * * 1-5 /scripts/phpscript.php
```
Run /path/to/perlscript.pl at 00:23, 02:23, and 04:23 everyday
```sh
23 0-23/2 * * * /path/to/perlscript.pl
```
Run `linuxcommand` at 04:05 every Sunday
```sh
5 4 * * sun /path/to/linuxcommand
```
#### /home/$USER
###### /home/$USER/.mailrc
```sh
set sendmail="/usr/bin/msmtp"
set message-sendmail-extra-arguments="-a gmail"
```
## /etc
/etc/lsb-release
```ini
DISTRIB_ID=Ubuntu
DISTRIB_RELEASE=14.04
DISTRIB_CODENAME=trusty
DISTRIB_DESCRIPTION="Ubuntu 14.04.6 LTS"
```

/etc/yum.conf
Exclude packages from updates permanently
[38](#sources)
```ini
[main]
exclude=kernel* php*
```
##### /etc/shadow
Colon-delimited file containing password hashes for every user listed in [/etc/passwd][/etc/passwd]
```
$USERNAME:$PASSWORD:$LASTCHANGED:$MIN:$MAX:$WARN:$INACTIVE:$EXPIRE
```
- `$USERNAME` Login name
- `$PASSWORD` Encrypted password; dollar signs delimit encryption hash function ([`$1`](#etcshadow "MD5"), [`$2a`](#etcshadow "Blowfish"), [`$2y`](#etcshadow "Blowfish"), [`$5`](#etcshadow "SHA-256"), or [`$6`](#etcshaodw "SHA-512")), then salt, then hash value. After locking the account with `usermod -L`, an exclamation point `!` is placed in front of this field, making the password inoperable and locking the account.  When an account has not yet had a password set, this value is `!!`
- `$LASTCHANGED` Days since 01/01/1970 that password was last changed
- `$MIN` minimum number of days required between password changes
- `$MAX` maximum number of days the password is valid before user is forced to change password
- `$WARN` number of days the password is to expire that user is warned that password must be changed
- `$INACTIVE` number of days after password expires that account is disabled
- `$EXPIRE` days since 01/01/1970 that account is disabled
##### /etc/group
Colon-delimited file describing group membership
```
$GROUP:$PASSWORD:$GID:$USER1:$USER2:$USER3...
```
/etc/resolv.conf
Use DNS queries prior to consulting /etc/hosts
```sh
nameserver dns
nameserver files
```
##### /etc/ansible
/etc/ansible/ansible.conf
##### /etc/apt
/etc/apt/sources.list

Entries are made of three parts, delimited by whitespace: <sup>[kali.training](https://kali.training/topic/introduction-to-apt/ "Introduction to APT")</sup>
1. Source type: `deb` for binary packages or `deb-src` for source packages
2. Base URL of the source: beginning with `http://`, `ftp://`, `file://`, or even `cdrom:`
3. Name of the chosen distribution followed by sections that differentiate packages by license. Kali, for example, contains `main`, `non-free`, and `contrib`.

```sh
deb http://us-central1.gce.archive.ubuntu.com/ubuntu/ bionic main restricted
deb http://us-central1.gce.archive.ubuntu.com/ubuntu/ bionic universe
deb http://us-central1.gce.archive.ubuntu.com/ubuntu/ bionic-updates main restricted
deb http://us-central1.gce.archive.ubuntu.com/ubuntu/ bionic-updates universe

# MongoDB repo
deb [ arch=amd64 ] https://repo.mongodb.org/apt/ubuntu bionic/mongodb-org/4.2 multiverse 

# gcloud
deb [signed-by=/usr/share/keyrings/cloud.google.gpg] http://packages.cloud.google.com/apt cloud-sdk main

# "Trusty-security" repository containing `mailx`
deb http://security.ubuntu.com/ubuntu trusty-security main universe
```
##### /etc/bluetooth
###### /etc/bluetooth/input.conf
Fix bluetooth mouse constantly disconnecting <sup>[askubuntu.com](https://askubuntu.com/questions/1065335/bluetooth-mouse-constantly-disconnects-and-reconnects 'Ask Ubuntu: "Bluetooth mouse constantly disconnects and reconnects"')</sup>
```ini
UserspaceHID=true
```
###### /etc/bluetooth/main.conf
Power on Bluetooth adapter at startup <sup>[askubuntu.com](https://askubuntu.com/questions/1065335/bluetooth-mouse-constantly-disconnects-and-reconnects 'Ask Ubuntu: "Bluetooth mouse constantly disconnects and reconnects"')</sup>
```ini
[Policy]
AutoEnable=true
```
##### /etc/default
###### /etc/default/useradd
Default values for account creation. Properties: `EXPIRE`, `GROUP`, `HOME`, `INACTIVE`, `SHELL`, `SKEL`
##### /etc/samba
###### /etc/samba/smb.conf
[https://vitux.com/how-to-install-and-configure-samba-on-ubuntu/]: https://vitux.com/how-to-install-and-configure-samba-on-ubuntu/ "vitux.com: \"How to Install and Configure Samba on Ubuntu\""

Configure Samba [<sup>ref</sup>][https://vitux.com/how-to-install-and-configure-samba-on-ubuntu/]
```ini
[samba-share]
comment = Samba on Ubuntu
path = /samba
read only = no
browsable = yes
```
Configure anonymous unsecured file sharing on a shared directory [[41](#sources)]
```ini
[global]
workgroup = WORKGROUP
netbios name = rhel
security = user
...
[Anonymous]
comment = Anonymous File Server Share
path = /srv/samba/anonymous
browsable =yes
writable = yes
guest ok = yes
read only = no
force user = nobody
```
##### /etc/selinux
###### /etc/selinux/config
<sup>[Nemeth][ULSAH]</sup>

```ini
SELINUX=setenforcing
SELINUXTYPE=targeted
```
##### /etc/ssmtp
###### /etc/ssmtp/ssmtp.conf
```ini
mailhub=smtp.gmail.com:587
UseTLS=YES
UseSTARTTLS=YES
```
###### /etc/sudoers
Allow sudo access to user `linuxize` only for command `/bin/mkdir`
```
linuxize ALL=/bin/mkdir
```
Allow user `linuxize` to run `sudo` commands without authenticating himself
```
linuxize ALL=(ALL) NOPASSWD: ALL
```
Change timeout to 10 minutes
```
Defaults timestamp_timeout=10
```
Change timeout to 10 minutes only for user `linuxize`
```
Defaults:linuxize timestamp_timeout=10
```
##### /etc/sysconfig
###### /etc/sysconfig/desktop
Specify desktop environment and display manager on Red Hat.
```ini
DESKTOP="KDE"
DISPLAYMANAGER="KDE"
```
```ini
DESKTOP="XFCE"
DISPLAYMANAGER="XDM"
```
```ini
DESKTOP="Gnome"
DISPLAYMANAGER="GDM"
```
###### /etc/sysconfig/network-scripts/
Directory containing file configurations for each network device you may have or want to add on your system [<sup>ref</sup>](https://web.mit.edu/rhel-doc/5/RHEL-5-manual/Deployment_Guide-en-US/s1-networkscripts-interfaces.html "Red Hat Documentation: 13.2. Interface Configuration Files")
```ini
DEVICE=eth0
IPADDR=208.164.186.1
NETMASK=255.255.255.0
NETWORK=208.164.186.0
BROADCAST=208.164.186.255
ONBOOT=yes
BOOTPROTO=none
USERCTL=no
```

###### /etc/postfix/main.cf
[Postfix](#postfix) config 

Set e-mail domain name <sup>[Eckert][Eckert]</sup>
```cfg
mydomain = sample.com
```
Set local access to domain name <sup>[Eckert][Eckert]</sup>
```cfg
myorigin = $mydomain
```
Configure postfix to listen for email on all interfaces <sup>[Eckert][Eckert]</sup>
```cfg
inet_interfaces = all
```
Configure destination domain for email <sup>[Eckert][Eckert]</sup>
```cfg
mydestination = $myhostname, localhost.$mydomain, localhost, $mydomain
```
Trust email from computers on the local network <sup>[Eckert][Eckert]</sup>
```cfg
mynetworks_style = class
```
# Tasks
#### Custom resolution
Specify a custom resolution in a VM <sup>[github.io](https://stafwag.github.io/blog/blog/2018/04/22/high-screen-resolution-on-a-kvm-virtual-machine-with-qxl/ 'stafwag.github.io: "High screen resolution on a KVM virtual machine with QXL")</sup>
```sh
cvt 2560 1440
xrandr --newmode "2560x1440_60.00" 312.25 2560 2752 3024 3488  1440 1443 1448 1493 -hsync +vsync
xrandr --addmode Virtual-1 2560x1440_60.00
xrandr --output Virtual-1 --mode 2560x1440_60.0
```
#### X forwarding
```sh
ssh -Y user@host
```
Have remote system use local computer {me.luna.edu}'s X display
```sh
export DISPLAY=me.luna.edu:0
```
#### Samba
Install and configure Samba server <sup>[vitux.com][https://vitux.com/how-to-install-and-configure-samba-on-ubuntu/]</sup>

Install `samba`
```sh
sudo apt install samba
```
Verify the samba service `smbd` is running
```sh
sudo systemctl status smbd
```
Configure Samba 
```sh
sudo mkdir /samba                   # Create a directory for the share
sudo chmod -R 0777 /samba
sudo chown -R nobody:nobody /samba  # Remove ownership
```
Open firewall rule
```sh
sudo firewall-cmd --permanent --add-service=samba
sudo firewall-cmd --reload
```
Configure Samba config file at [/etc/samba/smb.conf][/etc/samba/smb.conf]
```conf
[samba-share]
comment = Samba on Ubuntu
path = /samba
read only = no
browsable = yes
```
Set up a Samba account for `$USER`
```sh
sudo smbpasswd -a $USER
```
Restart Samba service <sup>[vitux.com][https://vitux.com/how-to-install-and-configure-samba-on-ubuntu/] [tecmint.com](https://www.tecmint.com/install-samba-on-rhel-8-for-file-sharing-on-windows/ "Install Samba4 on RHEL 8 for File Sharing on Windows")</sup>
```sh
sudo systemctl restart smbd.service
```
Install and configure Samba as a client
```sh
sudo apt install smbclient 
```
Access samba share at `$SHARE` at server `$HOST` using user credential `$USER`
```sh
sudo smbclient //$HOST/$USER -U $USER
```
This will display the Samba CLI
```
smb: \>
```
#### Bash scripting
Validating arguments <sup>[Sobell][Sobell]: 548</sup>
```sh 
if [ $# != 2 ]
then 
  echo "..."
  exit 1
fi
```
<sup>[YouTube](https://youtu.be/ksAfmJfdub0 "Easy Academic References on the Command Line")</sup>
```sh
[ -z "$1" ] && echo "..." && exit 1
```
<sup>[coderwall.com][https://coderwall.com/p/kq9ghg/yakuake-scripting]</sup>

```sh
if [ ! -z "$2" ] ; then ...; fi
```
Placed in a while loop, if user responds with anything except "y" (the read command will read only the first letter) the loop will terminate <sup>[Cannon][CLKF]</sup>
```bash
read -p "Backup another server? (y/n)" -n 1
["$BACKUP_AGAIN"="y"] || break
```
#### Diagnosing network problems
Test from the inside out, starting with the loopback
1. ping looback address, testing the TCP/IP stack
2. ping the hardware interface
3. ping another host on the network
4. ping the gateway
5. ping an IP address on the Internet
6. ping a hostname on the Internet

Display contents of a random file
```sh
ls | sort -R | sed 1q | xargs cat
```
Find out which commands you use most often
```sh
history | awk '{print $2' | sort | uniq -c | sort -rn | head
```
Count the number of occurrences of a string
```sh
| uniq -c | sort -
```
Change hostname 
```bash
sudo hostnamectl set-hostname newhostname
```
Check kernel version <sup>[linuxize.com](https://linuxize.com/post/how-to-check-the-kernel-version-in-linux/ "linuxize.com: \"How to check the Kernel version in Linux\"")</sup>
```bash
uname -srm
```
```bash
hostnamectl | grep "Kernel"
```
```bash
cat /proc/version
```
#### Install Arch Linux
Inspect available drives and partitions before/after inserting USB drive
```sh
lsblk
```
Mount ISO (`if`)to USB drive (`of`), with progress displayed
```sh
dd if=Downloads/archlinux-2018.03.01-x86_64.iso of=/dev/sdba status="progress"
```
Reboot from the USB drive. If there are values displayed a UEFI system is required and a different installation sequence is needed.
```sh
ls /sys/firmware/efi/efivars
```
Ensure an Ethernet internet connection  or `wi-fi menu` a valid Wi-Fi connection is present
```sh
timedatectl set-ntp true
```
Begin the process of partitioning the disk; enter the `fdisk` command prompt
```sh
fdisk /dev/sdb
```
Set up `ext4` filesystem on boot, root, and home partitions
```sh
mkfs.ext4 /dev/sdb1
mkfs.ext4 /dev/sdb3
mkfs.ext4 /dev/sdb4
```
Make the swap partition a swap drive
```sh
mkswap /dev/sdb2
swapon /dev/sdb2
```
Mount partitions
```sh
mount /dev/sdb3 /mnt
mkdir /mnt/home
mkdir /mnt/boot
mount /dev/sdb1 /mnt/boot
mount /dev/sdb4 /mnt/home
```
Install Arch Linux on the directory provided with the packages `base`, `base-devel` (which includes `sudo` and other development tools), `vim`
```sh
pacstrap /mnt base base-devel vim
```
Make an `fstab` file, taking all the drives mounted at that location, going off of UUIDs rather than the `sd` identifiers (which might change)
```sh
genfstab -U /mnt > /mnt/etc/fstab
```
Change root to new Arch Linux installation
```sh
arch-chroot /mnt
```
Install `networkmanager` which will allow Ethernet Internet connections upon reboot
```sh
pacman -S networkmanager
```
Tell SystemD to start NetworkManager upon login
```sh
systemctl enable NetworkManager
```
Install GRUB
```sh
pacman -S grub
```
Install GRUB as bootloader
```sh
grub-install --target=i386-pc /dev/sdb
```
Generate GRUB configuration
```sh
grub-mkconfig -o /boot/grub/grub.cfg
```
Set password for root
```sh
passwd
```
Uncomment the two lines referring to US English
```sh
vim /etc/locale.gen
```
Read that file and set locale
```sh
locale-gen
```
Set `LANG` language variable
```sh
echo "LANG=en-US.UTF-8" > /etc/locale.conf
```
Set timezone by making `localtime` a link to the correct timezone (this command is all that is required when resetting timezone during travel)
```sh
ln -sf /usr/share/zoneinfo/America/New_York /etc/localtime
```
Write new hostname
```sh
echo archizard > /etc/hostname
```
Return to USB shell
```sh
exit
```
Unmount hard drive for safety
```sh
umount -R /mnt
```
Reboot
```sh
reboot
```

###### Graphical environments
- Install `noto-fonts` and `ttf-linux-libertine` `ttf-inconsolata`
- `~/.config/fontconfig/fonts.conf` XML file that defines fonts as serif, monospace, etc
###### Example: installing `xfce4` desktop environment
```sh
pacman -S xfce4
exec xfce4-session
```
###### Installing user login screens
`sudo pacman -S lightdm lightdm-gtk-greeter`
`sudo systemctl enable lightdm.service`
###### Potential problems
- Ctrl+Alt+F2|F3|F4... bring up another TTY
- Alt+LeftArrow|RightArrow navigate to adjacent TTY
