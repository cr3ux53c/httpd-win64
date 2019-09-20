## Apache HTTPD for Windows NT amd64
> ApacheLounge에서 제공하는 Windows용 HTTPD 릴리즈를 실서버에 곧바로 구축하도록 최적화한 재배포 패키지입니다.
* 환경설정 최적화
* 불필요한 바이너리 및 문서 삭제
### Build Specifications
* Original Home: httpd.apache.org
* Binary by: Steffen
* Build with Visual Studio(R) 2017 (VC15) x64
* Mail: info@apachelounge.com
* Home: www.apachelounge.com
* [Announcement & Changelog](https://www.apachelounge.com/viewtopic.php?p=38419)
### Compile Options
* Server version: Apache/2.4.41 (Win64)
* Apache Lounge VC15 Server built:   Aug 11 2019 12:20:04
* Server's Module Magic Number: 20120211:88
* Server loaded:  APR 1.7.0, APR-UTIL 1.6.1
* Compiled using: APR 1.7.0, APR-UTIL 1.6.1
* Architecture:   64-bit
* Server MPM:     WinNT
* &nbsp;&nbsp;&nbsp;&nbsp;threaded:     yes (fixed thread count)
* &nbsp;&nbsp;&nbsp;&nbsp;forked:     no
* Server compiled with....
*  -D APR_HAS_SENDFILE
*  -D APR_HAS_MMAP
*  -D APR_HAVE_IPV6 (IPv4-mapped addresses disabled)
*  -D APR_HAS_OTHER_CHILD
*  -D AP_HAVE_RELIABLE_PIPED_LOGS
*  -D DYNAMIC_MODULE_LIMIT=256
*  -D HTTPD_ROOT="/apache"
*  -D SUEXEC_BIN="/apache/bin/suexec"
*  -D DEFAULT_PIDLOG="logs/httpd.pid"
*  -D DEFAULT_SCOREBOARD="logs/apache_runtime_status"
*  -D DEFAULT_ERRORLOG="logs/error.log"
*  -D AP_TYPES_CONFIG_FILE="conf/mime.types"
*  -D SERVER_CONFIG_FILE="conf/httpd.conf"
### System Requirements
* Windows 7 SP1
* Windows 8.1
* Windows 10
* Windows Server 2019
* Windows Server 2016
* Windows Server 2008 R2 SP1
* Windows Server 2012 / R2
* Visual C++ Redistributable for Visual Studio 2017 x64
---
### Powered by [ApacheLounge](https://apachelounge.com)