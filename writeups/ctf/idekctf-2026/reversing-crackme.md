# reversing crackme

_2026-07-14_

## setup
- responder listening on the test vlan
- proxychains + burp chained

## findings
- mssql linked server to dc
- snmp community 'public' read-all

## next
- try esc4 template misconfig
