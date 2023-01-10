#AD Lab Configurations

Domain Name: LaG.com
Admin User: John Doe (john.doe)

Primary Domain Controller: 
    -Lag-DC1
        -ip: 192.168.30.5 -static mapping in pfsense

DNS Settings:
    -LagDC1 provides domain dns 
    -pfsense DHCP sets primary dns to LaG-DC1 on lab subnet
    -pfsense DHCP sets secondary dns to pfsense on lab subnet
    -pfsense is set to google dns

