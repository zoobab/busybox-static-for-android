Static busybox for android
==========================

busybox: ELF 32-bit LSB executable, ARM, EABI5 version 1 (SYSV), statically linked, for GNU/Linux 2.6.16, stripped

Available commands
==================

    # ./busybox
    BusyBox v1.16.0 (2010-03-22 20:28:28 MST) multi-call binary.
    Copyright (C) 1998-2009 Erik Andersen, Rob Landley, Denys Vlasenko
    and others. Licensed under GPLv2.
    See source distribution for full notice.
    
    Usage: busybox [function] [arguments]...
       or: function [arguments]...
    
            BusyBox is a multi-call binary that combines many common Unix
            utilities into a single executable.  Most people will create a
            link to busybox for each function they wish to use and BusyBox
            will act like whatever it was invoked as.
    
    Currently defined functions:
            [, [[, addgroup, adduser, adjtimex, ar, arp, arping, ash, awk,
            basename, beep, blkid, brctl, bunzip2, bzcat, bzip2, cal, cat, catv,
            chat, chattr, chgrp, chmod, chown, chpasswd, chpst, chroot, chrt, chvt,
            cksum, clear, cmp, comm, cp, cpio, crond, crontab, cryptpw, cttyhack,
            cut, date, dc, dd, deallocvt, delgroup, deluser, depmod, devmem, df,
            dhcprelay, diff, dirname, dmesg, dnsd, dnsdomainname, dos2unix, du,
            dumpkmap, dumpleases, echo, ed, egrep, eject, env, envdir, envuidgid,
            ether-wake, expand, expr, fakeidentd, false, fbset, fbsplash, fdflush,
            fdformat, fdisk, fgrep, find, findfs, fold, free, freeramdisk, fsck,
            fsck.minix, fsync, ftpd, ftpget, ftpput, fuser, getopt, getty, grep,
            gunzip, gzip, halt, hd, hdparm, head, hexdump, hostid, hostname, httpd,
            hush, hwclock, id, ifconfig, ifdown, ifenslave, ifplugd, ifup, inetd,
            init, insmod, install, ionice, ip, ipaddr, ipcalc, ipcrm, ipcs, iplink,
            iproute, iprule, iptunnel, kbd_mode, kill, killall, killall5, klogd,
            last, length, less, linux32, linux64, linuxrc, ln, loadfont, loadkmap,
            logger, login, logname, logread, losetup, ls, lsattr, lsmod, lspci,
            lsusb, lzmacat, lzop, lzopcat, makedevs, man, md5sum, mdev, mesg,
            microcom, mkdir, mkdosfs, mkfifo, mkfs.minix, mkfs.vfat, mknod,
            mkpasswd, mkswap, mktemp, modprobe, more, mount, mountpoint, msh, mt,
            mv, nameif, nc, netstat, nice, nmeter, nohup, nslookup, od, openvt,
            passwd, patch, pgrep, pidof, ping, ping6, pipe_progress, pivot_root,
            pkill, poweroff, printenv, printf, ps, pscan, pwd, raidautorun, rdate,
            rdev, readahead, readlink, readprofile, realpath, reboot, renice,
            reset, resize, rm, rmdir, rmmod, route, rtcwake, run-parts, runlevel,
            runsv, runsvdir, rx, script, scriptreplay, sed, seq, setarch,
            setconsole, setfont, setkeycodes, setlogcons, setsid, setuidgid, sh,
            sha1sum, sha256sum, sha512sum, showkey, slattach, sleep, softlimit,
            sort, split, start-stop-daemon, stat, strings, stty, su, sulogin, sum,
            sv, svlogd, swapoff, swapon, switch_root, sync, sysctl, syslogd, tac,
            tail, tar, tcpsvd, tee, telnet, telnetd, test, tftp, tftpd, time,
            timeout, top, touch, tr, traceroute, true, tty, ttysize, tunctl,
            udhcpc, udhcpd, udpsvd, umount, uname, uncompress, unexpand, uniq,
            unix2dos, unlzma, unlzop, unzip, uptime, usleep, uudecode, uuencode,
            vconfig, vi, vlock, volname, wall, watch, watchdog, wc, wget, which,
            who, whoami, xargs, yes, zcat, zcip

Tested devices
==============

Was succesfully run on:

* ARMv6-compatible processor rev 2 (v6l), HTC wildfire, http://www.zoobab.com/htc-wildfire

Create symlinks
===============

See this good webpage: http://www.jukie.net/~bart/blog/20081011081638
