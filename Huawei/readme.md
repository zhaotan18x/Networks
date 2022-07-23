# Huawei kytkimien porttien konffaukset ja muut tarkistukset, että tarkista kytkimen porttien tilanne ja mitä on konffattu sisään

| komento   |  Kuvaus | 
| ----- | ------- |
| $display current-configuration | tulosta laitteen konffaukset tai lyhenne $dis cur |
| $display interface brief | kytkemn laitteen fyysinen status ja kaikki porttien käyttöjärjestelmät |
| $display interface *interface-type interface-number*  | tulosta kytkimen yksittäisen porttien status, ja sisäinen järjestelmä kuvaus | 
| $display arp | tulostaa arppi taulukkon, että mitä kyseisen reitittimen laiteitta löytyy, mutta mahdollista näkyy ip-osoite ja porttien numero|
| $display mac address-table | mac-osoitteiden taulukko |
| $display logbuffer | logbufferi kyseisen reitittimen porttien status on/off tilanne, snmp ongelmia ja muita reserointien taustojen historien takana olevia toimintoja |
| $display  lldp neighbors | näyttää LLDP havaitut naapureiden laitteet |
| $display dhcp snooping  | näyttää DHCP-snooping-ajotiedot. Jos liitäntää tai VLAN:ia ei ole määritetty, globaalit DHCP-snooping-ajotiedot näytetään. Jos liitäntä tai VLAN-tunnus on määritetty, näyttöön tulee DHCP-snooping-tiedot käyttöliittymästä tai VLAN:ista. |
| $ display dhcp snooping user-bind interface <portNumber 0/X/Y> | tarkistaa kyseisen porttien dchp ajotiedon, että tulostuu mac-osoite ja saako kyseinen portti IP-osoitetta |
| <br> | |
| ping -vpn-instance <rf> -a <sourceIP-add> <destinationIP> | jos tarve tarkistaa jokin tietty vrf, käytä vpn-instance & kuin testaa tietyn vrf reitityksen pinggaus yhteyden pelittäminen |

