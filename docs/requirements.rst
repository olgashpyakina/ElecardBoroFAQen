Technical requirements
======================

Server
------

Supported Browsers: 

* Chromium, version 51 and later
* Google Chrome, version 51 and later
* Mozilla Firefox, version 47 and later

For a smooth experience, make sure that your browser is updated to the latest version.
For loaded applications:

.. csv-table::
   :header: "Minimum requirements", "Recommended requirements"

   "Intel (R) Xeon (R) Processor E3-1276 v3", "Intel Xeon Processor E5-xxxx v3  x2"
   "16GB RAM", "32-64GB RAM"
   "1TB HDD Raid 10", "2TB HDD Raid 10 Hot Swap"
   "Linux 64bit CenOs 7.4 core ", "Linux 64bit CenOs 7.4 core "
   
Probe
-----
For loaded applications:

.. csv-table::
   :header: " ", "Delivery Continuity only (TR 101 290 + ClockContinuity)", "Delivery Continuity + VideoFreeze + Thumbnails"
   
   "IPTV 200SD+140HD", "Intel(R) Xeon(R) CPU E3-1270 v5 @ 3.60GHz 32GB RAM", "dual CPU Intel(R) Xeon 8 Core processors E5-2620v4 32GB RAM"
   "HLS 50SD(3)+50HD(2)", "Intel(R) Xeon(R) CPU E3-1270 v5 @ 3.60GHz 32GB RAM", "dual CPU Intel(R) Xeon 8 Core processors E5-2620v4 32GB RAM"
   
Sources: UDP, RTP [1]_, HTTP, HLS, DVB, file(TS).

Transport: MPEG-2 TS (SPTS /MPTS).

Videocodecs: MPEG-2, AVC/H.264, HEVC/H.265.

**System requirements:**

* Windows 7/8/8.1/10 32/64 bit, Server 2008/2012 32/64 bit
* Linux 32bit/64bit + glibc-2.11 (October 2009, Debian 6, Ubuntu 10.04, SLES 11, RHEL 6, CentOS 6) and later versions.

**Recommended OS:** CentOS 7.4

**Minimum hardware requirements:**
Processors supporting SSE2 (Intel(R) Pentium 4 and later, AMD(R) Opteron and Athlon 64, and later versions).

Supported formats
-----------------

Videocodecs: MPEG-2, AVC/H.264, HEVC/H.265

Transport: MPEG-2 TS (SPTS /MPTS)

Sources:

.. csv-table:: **Network delivery**
   :header: "Type [2]_", "URI example"
   
   "UDP", "udp://235.0.0.8:1234"
   "RTP", "rtp://235.0.0.10:4444"
   "http/https", "http://localhost:8888/stream, https://storage.streamsample.ru/stream5458993"  
   "HLS v3", "http://95.170.157.5:80/channel1.m3u8,  https://127.0.0.1:8080/channel25.m3u8"  

.. csv-table:: **File analysis**
   :header: "Type [3]_", "URI example" 
   
   "File", "file://d:\Streams\SPTS\dump45689.ts"
	"HLS v3 from folder", "file://c:\HLS\HLS_SD.m3u8"
   
   
.. [1] RTP over UDP (multicast) The stream should meet requirements of the specification RTP Payload Format for MPEG1/MPEG2 Video (rfc2250)

.. [2] Only MPEG-2 TS ( SPTS /MPTS ) is supported for all types of network delivery.

.. [3] Only MPEG-2 TS ( SPTS /MPTS ) is supported for all types of file analysis.

