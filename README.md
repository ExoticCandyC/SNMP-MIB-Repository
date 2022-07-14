# SNMP MIB Repository

All the MIB files provided in this directory are ASN.1 compliant and can be loaded by any standard MIB browser.

# MIB monitoring suggestions

My suggestion is the ireasoning MIB browser, as it is fast, lightweight and supports the SMI syntax used in the MIB files. It is multi-platform and supports Linux, Mac-OS and Windows.

https://www.ireasoning.com/mibbrowser.shtml

For Android devices, my suggestion is "SNMP Manager" by "Gao Feng"

https://play.google.com/store/apps/details?id=snmpmanager.feng.gao&hl=en&gl=US

# Operating system

The official supported operating system for all my codes is GNU-Linux based operating systems. All the testings are done on Arch-Linux using the community packages, not the testing or AUR packages.

SNMP tools are pre-installed on GNU-Linux based operating systems and all of them are supported.

For example, to read a table from the SNMP enabled device/software, you can use the following code:

```bash
snmptable -v [SNMP-VERSION] -c [COMMUNITY-STRING] -M [PATH-TO-THE-MIB-FOLDER] -m [PATH-TO-THE-MIB-FILE] [DEVICE-IP]:[DEVICE-SNMP-PORT] [TABLE-OID]
```

# SNMP Project Files
| Project Name | MIB file name | Project Version |
| --- | --- | --- |
| MIB dependencies | EC-Base.mib | v1.0.0 |
| SNMP monitoring | EC-SNMP-Monitoring.mib | v4.0.1a |

