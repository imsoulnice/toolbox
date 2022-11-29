# 大盘机
## Hosthatch
荷兰阿姆斯特丹 1C2G2T 20T@10Gbps
```
1.wget -qO- bench.sh | bash
-------------------- A Bench.sh Script By Teddysun -------------------
 Version            : v2022-06-01
 Usage              : wget -qO- bench.sh | bash
----------------------------------------------------------------------
 CPU Model          : AMD EPYC 7551P 32-Core Processor
 CPU Cores          : 1 @ 1999.973 MHz
 CPU Cache          : 512 KB
 AES-NI             : Enabled
 VM-x/AMD-V         : Enabled
 Total Disk         : 1.8 TB (30.2 GB Used)
 Total Mem          : 1.9 GB (59.6 MB Used)
 System uptime      : 0 days, 0 hour 8 min
 Load average       : 0.13, 0.09, 0.05
 OS                 : Debian GNU/Linux 11
 Arch               : x86_64 (64 Bit)
 Kernel             : 5.10.0-9-amd64
 TCP CC             : cubic
 Virtualization     : KVM
 Organization       : AS63473 HostHatch, LLC
 Location           : Tricht / NL
 Region             : Gelderland
----------------------------------------------------------------------
 I/O Speed(1st run) : 967 MB/s
 I/O Speed(2nd run) : 888 MB/s
 I/O Speed(3rd run) : 985 MB/s
 I/O Speed(average) : 946.7 MB/s
----------------------------------------------------------------------
 Node Name        Upload Speed      Download Speed      Latency
 Speedtest.net    9146.20 Mbps      7138.24 Mbps        0.20 ms
 Los Angeles, US  373.81 Mbps       3086.43 Mbps        139.39 ms
 Dallas, US       231.88 Mbps       4498.29 Mbps        116.30 ms
 Montreal, CA     71.98 Mbps        730.39 Mbps         80.22 ms
 Paris, FR        817.81 Mbps       6847.59 Mbps        9.80 ms
 Amsterdam, NL    6910.68 Mbps      7093.45 Mbps        1.03 ms
 Shanghai, CN     53.33 Mbps        1712.13 Mbps        235.24 ms
 Guangzhou, CN    1.41 Mbps         139.99 Mbps         257.45 ms
 Hongkong, CN     263.58 Mbps       2875.24 Mbps        245.23 ms
 Seoul, KR        42.75 Mbps        714.11 Mbps         248.61 ms
 Singapore, SG    114.12 Mbps       1045.03 Mbps        162.21 ms
 Tokyo, JP        188.47 Mbps       2315.55 Mbps        234.88 ms
----------------------------------------------------------------------
 Finished in        : 6 min 19 sec
 Timestamp          : 2022-11-28 16:38:25 UTC
----------------------------------------------------------------------

2.curl -sL yabs.sh | bash
# ## ## ## ## ## ## ## ## ## ## ## ## ## ## ## ## ## #
#              Yet-Another-Bench-Script              #
#                     v2022-11-22                    #
# https://github.com/masonr/yet-another-bench-script #
# ## ## ## ## ## ## ## ## ## ## ## ## ## ## ## ## ## #

Mon Nov 28 16:39:26 UTC 2022

Basic System Information:
---------------------------------
Uptime     : 0 days, 0 hours, 15 minutes
Processor  : AMD EPYC 7551P 32-Core Processor
CPU cores  : 1 @ 1999.973 MHz
AES-NI     : ✔ Enabled
VM-x/AMD-V : ✔ Enabled
RAM        : 1.9 GiB
Swap       : 0.0 KiB
Disk       : 1.8 TiB
Distro     : Debian GNU/Linux 11 (bullseye)
Kernel     : 5.10.0-9-amd64

fio Disk Speed Tests (Mixed R/W 50/50):
---------------------------------
Block Size | 4k            (IOPS) | 64k           (IOPS)
  ------   | ---            ----  | ----           ----
Read       | 6.27 MB/s     (1.5k) | 70.41 MB/s    (1.1k)
Write      | 6.28 MB/s     (1.5k) | 70.78 MB/s    (1.1k)
Total      | 12.55 MB/s    (3.1k) | 141.20 MB/s   (2.2k)
           |                      |
Block Size | 512k          (IOPS) | 1m            (IOPS)
  ------   | ---            ----  | ----           ----
Read       | 213.86 MB/s    (417) | 373.28 MB/s    (364)
Write      | 225.23 MB/s    (439) | 398.14 MB/s    (388)
Total      | 439.10 MB/s    (856) | 771.43 MB/s    (752)

iperf3 Network Speed Tests (IPv4):
---------------------------------
Provider        | Location (Link)           | Send Speed      | Recv Speed      | Ping
-----           | -----                     | ----            | ----            | ----
Clouvider       | London, UK (10G)          | 1.74 Gbits/sec  | 4.35 Gbits/sec  | 5.77 ms
Scaleway        | Paris, FR (10G)           | 2.09 Gbits/sec  | busy            | 11.9 ms
NovoServe       | North Holland, NL (40G)   | 7.63 Gbits/sec  | 9.41 Gbits/sec  | 1.37 ms
Uztelecom       | Tashkent, UZ (10G)        | 796 Mbits/sec   | 172 Mbits/sec   | 83.3 ms
Clouvider       | NYC, NY, US (10G)         | 715 Mbits/sec   | 2.05 Gbits/sec  | 74.1 ms
Clouvider       | Dallas, TX, US (10G)      | 589 Mbits/sec   | 1.62 Gbits/sec  | 112 ms
Clouvider       | Los Angeles, CA, US (10G) | 582 Mbits/sec   | 1.36 Gbits/sec  | 135 ms

iperf3 Network Speed Tests (IPv6):
---------------------------------
Provider        | Location (Link)           | Send Speed      | Recv Speed      | Ping
-----           | -----                     | ----            | ----            | ----
Clouvider       | London, UK (10G)          | 2.79 Gbits/sec  | 2.55 Gbits/sec  | 5.58 ms
Scaleway        | Paris, FR (10G)           | 2.06 Gbits/sec  | 9.00 Gbits/sec  | 11.3 ms
NovoServe       | North Holland, NL (40G)   | busy            | 12.2 Gbits/sec  | 1.26 ms
Uztelecom       | Tashkent, UZ (10G)        | 378 Mbits/sec   | 1.43 Gbits/sec  | 83.5 ms
Clouvider       | NYC, NY, US (10G)         | 732 Mbits/sec   | 2.49 Gbits/sec  | 74.1 ms
Clouvider       | Dallas, TX, US (10G)      | 429 Mbits/sec   | 1.61 Gbits/sec  | 112 ms
Clouvider       | Los Angeles, CA, US (10G) | 565 Mbits/sec   | 1.34 Gbits/sec  | 135 ms

Geekbench 5 Benchmark Test:
---------------------------------
Test            | Value
                |
Single Core     | 734
Multi Core      | 739
Full Test       | https://browser.geekbench.com/v5/cpu/18943311

```

## GreenCloud
**美国丹佛 4C6G2T 8T流量**
```
curl -sL yabs.sh | bash
# ## ## ## ## ## ## ## ## ## ## ## ## ## ## ## ## ## #
#              Yet-Another-Bench-Script              #
#                     v2022-11-22                    #
# https://github.com/masonr/yet-another-bench-script #
# ## ## ## ## ## ## ## ## ## ## ## ## ## ## ## ## ## #

Tue 29 Nov 2022 12:57:38 PM CST

Basic System Information:
---------------------------------
Uptime     : 1 days, 15 hours, 32 minutes
Processor  : Intel(R) Xeon(R) CPU E5-2690 v3 @ 2.60GHz
CPU cores  : 4 @ 2599.996 MHz
AES-NI     : ✔ Enabled
VM-x/AMD-V : ❌ Disabled
RAM        : 5.8 GiB
Swap       : 975.0 MiB
Disk       : 2.0 TiB
Distro     : Debian GNU/Linux 11 (bullseye)
Kernel     : 5.10.0-19-amd64

fio Disk Speed Tests (Mixed R/W 50/50):
---------------------------------
Block Size | 4k            (IOPS) | 64k           (IOPS)
  ------   | ---            ----  | ----           ----
Read       | 9.48 MB/s     (2.3k) | 137.39 MB/s   (2.1k)
Write      | 9.51 MB/s     (2.3k) | 138.11 MB/s   (2.1k)
Total      | 18.99 MB/s    (4.7k) | 275.50 MB/s   (4.3k)
           |                      |
Block Size | 512k          (IOPS) | 1m            (IOPS)
  ------   | ---            ----  | ----           ----
Read       | 440.56 MB/s    (860) | 533.39 MB/s    (520)
Write      | 463.96 MB/s    (906) | 568.91 MB/s    (555)
Total      | 904.52 MB/s   (1.7k) | 1.10 GB/s     (1.0k)

iperf3 Network Speed Tests (IPv4):
---------------------------------
Provider        | Location (Link)           | Send Speed      | Recv Speed      | Ping
-----           | -----                     | ----            | ----            | ----
Clouvider       | London, UK (10G)          | 132 Mbits/sec   | 53.9 Mbits/sec  | 111 ms
Scaleway        | Paris, FR (10G)           | 238 Mbits/sec   | 120 Mbits/sec   | 117 ms
NovoServe       | North Holland, NL (40G)   | 485 Mbits/sec   | 607 Mbits/sec   | 122 ms
Uztelecom       | Tashkent, UZ (10G)        | 313 Mbits/sec   | 122 Mbits/sec   | 232 ms
Clouvider       | NYC, NY, US (10G)         | 615 Mbits/sec   | 278 Mbits/sec   | 36.6 ms
Clouvider       | Dallas, TX, US (10G)      | 790 Mbits/sec   | 264 Mbits/sec   | 19.3 ms
Clouvider       | Los Angeles, CA, US (10G) | 751 Mbits/sec   | 244 Mbits/sec   | 38.9 ms

iperf3 Network Speed Tests (IPv6):
---------------------------------
Provider        | Location (Link)           | Send Speed      | Recv Speed      | Ping
-----           | -----                     | ----            | ----            | ----
Clouvider       | London, UK (10G)          | 674 Mbits/sec   | 75.9 Mbits/sec  | 111 ms
Scaleway        | Paris, FR (10G)           | 538 Mbits/sec   | 80.2 Mbits/sec  | 115 ms
NovoServe       | North Holland, NL (40G)   | 523 Mbits/sec   | 583 Mbits/sec   | 122 ms
Uztelecom       | Tashkent, UZ (10G)        | 488 Mbits/sec   | 81.5 Mbits/sec  | 232 ms
Clouvider       | NYC, NY, US (10G)         | 808 Mbits/sec   | busy            | 36.6 ms
Clouvider       | Dallas, TX, US (10G)      | 783 Mbits/sec   | 473 Mbits/sec   | 19.3 ms
Clouvider       | Los Angeles, CA, US (10G) | 740 Mbits/sec   | 229 Mbits/sec   | 31.4 ms

Geekbench 5 Benchmark Test:
---------------------------------
Test            | Value
                |
Single Core     | 671
Multi Core      | 2337
Full Test       | https://browser.geekbench.com/v5/cpu/18953840
```
