# QXlsx-issue-184

- QXlsx issue #184 
- https://github.com/QtExcel/QXlsx/issues/184


## Build

```sh
cd test
mkdir build 
cd build
qmake ../test.pro
make
```

## Tested Environment 

- Ubuntu x64

```
$ qmake --version
QMake version 3.1
Using Qt version 6.4.1 in /home/j2doll/Qt/6.4.1/gcc_64/lib

$ g++ --version
g++ (Ubuntu 11.3.0-1ubuntu1~22.04) 11.3.0

$ make --version
GNU Make 4.3
Built for x86_64-pc-linux-gnu
```

```
$ cat /etc/*release*
   DISTRIB_ID=Ubuntu
   DISTRIB_RELEASE=22.04
   DISTRIB_CODENAME=jammy
   DISTRIB_DESCRIPTION="Ubuntu 22.04.1 LTS"
   PRETTY_NAME="Ubuntu 22.04.1 LTS"
   NAME="Ubuntu"
   VERSION_ID="22.04"
   VERSION="22.04.1 LTS (Jammy Jellyfish)"
   VERSION_CODENAME=jammy
   ID=ubuntu
   ID_LIKE=debian
   HOME_URL="https://www.ubuntu.com/"
   SUPPORT_URL="https://help.ubuntu.com/"
   BUG_REPORT_URL="https://bugs.launchpad.net/ubuntu/"
   PRIVACY_POLICY_URL="https://www.ubuntu.com/legal/terms-and-policies/privacy-policy"
   UBUNTU_CODENAME=jammy
```

- QXlsx version 

https://github.com/QtExcel/QXlsx/commit/ffad8c07f9d32d7dc5c974595775a6d0929b94c8


