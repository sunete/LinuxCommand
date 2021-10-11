# LinuxCommand
当前仓库搜集了 575 个 Linux 命令，可以生成 web 网站方便使用，网站内容包含 Linux 命令手册、详解、学习。

## 目录

- [LinuxCommand](#linuxcommand)
  - [目录](#目录)
  - [Linux命令分类](#linux命令分类)
    - [文件传输](#文件传输)
    - [备份压缩](#备份压缩)
    - [文件管理](#文件管理)
    - [磁盘管理](#磁盘管理)
    - [磁盘维护](#磁盘维护)
    - [系统设置](#系统设置)
    - [系统管理](#系统管理)
    - [文本处理](#文本处理)
    - [网络通讯](#网络通讯)
    - [设备管理](#设备管理)
    - [电子邮件与新闻组](#电子邮件与新闻组)
    - [其他命令](#其他命令)
  - [网站部署](#网站部署)
    - [部署到 Vercel](#部署到-vercel)
    - [部署到 Cloudflare Pages](#部署到-cloudflare-pages)


## Linux命令分类

*这里存放Linux 命令大全并不全，你可以通过[linux-command](https://jaywcjlove.github.io/linux-command/)来搜索，它是把 [command](./assets/command) 目录里面搜集的命令，生成了静态HTML并提供预览以及索引搜索。*

### 文件传输

bye、ftp、ftpcount、ftpshut、ftpwho、ncftp、tftp、uucico、uucp、uupick、uuto、scp

### 备份压缩

ar、bunzip2、bzip2、bzip2recover、compress、cpio、dump、gunzip、gzexe、gzip、lha、restore、tar、unarj、unzip、zip、zipinfo

### 文件管理

diff、diffstat、file、find、git、gitview、ln、locate、lsattr、mattrib、mc、mcopy、mdel、mdir、mktemp、mmove、mread、mren、mshowfat、mtools、mtoolstest、mv、od、paste、patch、rcp、rhmask、rm、slocate、split、tee、tmpwatch、touch、umask、whereis、which、cat、chattr、chgrp、chmod、chown、cksum、cmp、cp、cut、indent

### 磁盘管理

cd、df、dirs、du、edquota、eject、lndir、ls、mcd、mdeltree、mdu、mkdir、mlabel、mmd、mmount、mrd、mzip、pwd、quota、quotacheck、quotaoff、quotaon、repquota、rmdir、rmt、stat、tree、umount

### 磁盘维护

badblocks、cfdisk、dd、e2fsck、ext2ed、fdisk、fsck.ext2、fsck、fsck.minix、fsconf、hdparm、losetup、mbadblocks、mformat、mkbootdisk、mkdosfs、mke2fs、mkfs.ext2、mkfs、mkfs.minix、mkfs.msdos、mkinitrd、mkisofs、mkswap、mpartition、sfdisk、swapoff、swapon、symlinks、sync

### 系统设置

alias、apmd、aumix、bind、chkconfig、chroot、clock、crontab、declare、depmod、dircolors、dmesg、enable、eval、export、fbset、grpconv、grpunconv、hwclock、insmod、kbdconfig、lilo、liloconfig、lsmod、minfo、mkkickstart、modinfo、modprobe、mouseconfig、ntsysv、passwd、pwconv、pwunconv、rdate、resize、rmmod、rpm、set、setconsole、setenv、setup、sndconfig、SVGAText Mode、timeconfig、ulimit、unalias、unset

### 系统管理

adduser、chfn、chsh、date、exit、finger、free、fwhois、gitps、groupdel、groupmod、halt、id、kill、last、lastb、login、logname、logout、logrotate、newgrp、nice、procinfo、ps、pstree、reboot、renice、rlogin、rsh、rwho、screen、shutdown、sliplogin、su、sudo、suspend、swatch、tload、top、uname、useradd、userconf、userdel、usermod、vlock、w、who、whoami、whois

### 文本处理

awk、col、colrm、comm、csplit、ed、egrep、ex、fgrep、fmt、fold、grep、ispell、jed、joe、join、look、mtype、pico、rgrep、sed、sort、spell、tr、uniq、vi、wc

### 网络通讯

dip、getty、mingetty、ppp-off、smbd(samba daemon)、telnet、uulog、uustat、uux、cu、dnsconf、efax、httpd、ip、ifconfig、mesg、minicom、nc、netconf、netconfig、netstat、ping、pppstats、samba、setserial、shapecfg(shaper configuration)、smbd(samba daemon)、statserial(status ofserial port)、talk、tcpdump、testparm(test parameter)、traceroute、tty(teletypewriter)、uuname、wall(write all)、write、ytalk、arpwatch、apachectl、smbclient(samba client)、pppsetup

### 设备管理

dumpkeys、loadkeys、MAKEDEV、rdev、setleds

### 电子邮件与新闻组

archive、ctlinnd、elm、getlist、inncheck、mail、mailconf、mailq、messages、metamail、mutt、nntpget、pine、slrn、X WINDOWS SYSTEM、reconfig、startx(start X Window)、Xconfigurator、XF86Setup、xlsatoms、xlsclients、xlsfonts

### 其他命令

yes


## 网站部署
### 部署到 Vercel
支持一键部署到 Vercel

[![Deploy to Vercel](https://vercel.com/button)](https://vercel.com/import/project?template=https://github.com/sunete/LinuxCommand)

### 部署到 Cloudflare Pages
Fork 本项目，到 Cloudflare Pages 关联 GitHub 账号，创建项目 -> 从 GitHub 存储库创建项目 -> 选择 LinuxCommand -> 开始部署
