---
title: Switches-Firmware
type: docs
prev: docs/how-to/
---

## To Update Switch Firmware
* Download firmware from https://h10145.www1.hpe.com/downloads/ProductsList.aspx and copy to C:\tftp folder on `10.10.10.220``
* Launch tftpd64 (instructions here: http://techzain.com/how-to-setup-tftp-server-tftpd64-tfptd32-windows/ ) or here: https://support.hpe.com/hpsc/doc/public/display?docId=emr_na-c02597191
* CLI: copy tftp flash <IP address of TFTP server> <case-sensitive firmware filename>
* On switch command line, go to Menu, Download OS
