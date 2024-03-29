### Peter Hyman's Github

## About Me
Program development has mostly been a hobby, not an avocation. I am expert in **C**. spent some years with **Java**, and program and configure databases. 

### Linux and me
My journey to Linux began when the alternative Windows Desktop called `DesqView/X` by **Quarterdeck Systems**. then with `SCO/Xenix`, and finally, my distro of choice, `Slackware` in the late '90s which I continue to use and support to this day. I run Windows only when I have to, and that, under a VM.

### Professional
I have been a consultant where I used C and designed and configured databases in a variety of industry verticals:
* Television, Film, Media, and Advertising
* Recording arts
* Banking, Insurance, and Financial Services
* Healthcare and Life Sciences

### Some career highlights:
* Developed one of the first Ratings Analysis Systems for the Cable TV Industry
* Debugged and reprogrammed a global stock market index database that was providing inaccurate results by 200 basis points
* Designed Executive Compensation Systems used by a multi-national in 63 countries
* Designed and Developed a Music Video Licensing System
* Was Product Manager at an Enterprise Quality Management Software company
* More recently, have been involved in Regulatory Compliance for Medical Device, Biotech, and Pharma Companies designing and configuring reporting systems for Adverse Events, Device Registrations, CAPA, etc.

### Github Activities
[lrzip-next](https://github.com/pete4abw/lrzip-next) is the project I work on the most. It is a detached fork of the `lrzip` long range data compression program by Con Kolivas. I began contributing to that project in 2007 and eventually, my modifications became too divergent to manage two forks. So, `lrzip-next` was born in 2019 and continues to this day. Features include:
* Updated APIs for LZMA and ZPAQ
* Enhanced and more readable print and info output
* Updated x86 ASM routines for LZMA
* Additions of new compression backends, **bzip3** and **zstd**

See the FEATURES file for more info.

[bitpacker](https://github.com/pete4abw/bitpacker) is a C project that will pack 7-bit ASCII strings into 8-bit bytes. This is accomplished by successively shifting bytes 1 bit at a time, rotating throughout the array of bytes. The result is a string which is obfuscated with unprintable characters. While not encryption, this result will be made printable by using Base64 encoding. So a string like **password** would become unreadable and with base64 readable again and can be used. It is useful because unlike you can control what the password will be and it is still packed and then obfuscated. Even if someone decoded the base64 string, your password would still not be readable. This was really a small mental exercise for an old-school programmer!
```
$ ./bitp p password
Base64 encoding of password is 4YefPvv5ZA==

$ ./bitp u 4YefPvv5ZA==
base64 Decoded packed password is: password
```

[makesbld](https://github.com/pete4abw/makesbld) is a shell program to create `Slackware` Build files. Similar to Gentoo ebuilds, it uses a library of shell functions to systemetize package automation.

[Kernel-Install](https://github.com/pete4abw/Kernel-Install) is a shell script to automate upgrading and installing kernels.

[lrzip-fe](https://github.com/pete4abw/lrzip-fe) is a shell script using `Dialog` to launch `lrzip-next` with all options menu-selectable (although this project is a little behind right now).

Other projects are also available for perusal but are not as actively maintained. [ps2lrz](https://github.com/pete4abw/ps2lrz) is an intereting one because it has the capability to rewrite `lrzip` and `lrzip-next` headers or just decode them. Interesting stuff!

## Personal
I majored in **Piano Performance** and minored in **Music Theory** at Oberlin Conservatory of Music. Earned a Masters in **Cable Communications** at New York University.
I enjoy travel. A lot.

## Contact
I may be reached through the `Issues` and `Discussions` tabs on any repo or by email: <a href="mailto:pete@peterhyman.com?subject=Mail from Github Profile">Send Email</a>
