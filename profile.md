Sho ip  arp ip address
sho int gi1/0/20
sho enviorment
clear ip arp

sh interfaces link

test cable-diagnostics tdr int gi2/0/48

sho mac address-table | include last 4

sho power inline

sho mac address-table | include port#

Set-ADAccountExpiration -Identity fmlast -DateTime "06/16/2022 22:30"

[6/16 4:41 PM] Mike Daly
# Check Account expiration
Get-ADUser -Identity fmlast -Properties AccountExpirationDate | Select-Object -Property Name, SamAccountName, AccountExpirationDate
 like 1

sho ip access-list | inc 192.168.100.72


w32tm /query /peers

sho mac address gi1/0/13
