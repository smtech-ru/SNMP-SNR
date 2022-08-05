# SNR-private-OIDs
Use prometheus [```snmp_exporter```](https://github.com/prometheus/snmp_exporter) to get SNR metrics via snmp.

This dashboard represents the main metrics provided by a series of SNR devices and more metrics from the common MIB, which in my opinion seemed useful.

## How to use
Install [```snmp_exporter```](https://github.com/prometheus/snmp_exporter) and configure it with the [```snmp.yml```](/snr_all_used_OID's/snmp.yml) configuration file. Then install and import [```dashboard```](/SNMP_SNR_private_OID's.json). This dashboard is a template solution, you can remove unnecessary tabs or panels.

## SNR private OID's
[```OID parent is .1.3.6.1.4.1.40418```](https://mibs.observium.org/mib/SNR-SWITCH-MIB/#os)
![graphs of basic SNMP objects](/exmp_imgs/snr_private.png)

## SNMP OID's
Metrics generated snmp_exporter by default
![graphs of basic SNMP objects](/exmp_imgs/snmp_general.png)
## Common OID's 
[```OID parent is .1.3.6.1.2.1.31```](http://oidref.com/1.3.6.1.2.1.31)
![graphs of basic SNMP objects](/exmp_imgs/common_mib.png)
## Common OID's by port name
![graphs of basic SNMP objects](/exmp_imgs/common_mib_by_portName.png)
## Common stp bridge OID's
[```OID parent is .1.3.6.1.2.1.17```](http://oidref.com/1.3.6.1.2.1.17)
![graphs of basic SNMP objects](/exmp_imgs/common_stp_bridge.png)

## Useful endpoints
* More about snmp_exporter: https://github.com/prometheus/snmp_exporter
* MIB browser: http://oidref.com
* MIB SNR browser: https://mibs.observium.org/mib/SNR-SWITCH-MIB
* SNR-SWITCH private MIB file: https://data.nag.ru/SNR%20Switches/MIBs
#### Created by [zheleziv](https://github.com/zheleziv)
