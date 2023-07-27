# BlackByte

Use this query to look for ransomware BlackByte behavior in the environment.

## EDR CDM [Cloud Console queries]

## Query

Disable Firewall using netsh
```
Event Type Id:8001-Process Activity AND Disposition:1 AND Process Name:netsh.exe AND Process Command Line:/.*advfirewall set allprofiles state off.*/

```