# FortigateConfig
Fortigate config

## Commande Line
FortiGate-VM64-KVM # config system interface

FortiGate-VM64-KVM (interface) # edit port1

FortiGate-VM64-KVM (port1) # set mode static

FortiGate-VM64-KVM (port1) # set ip 192.168.122.209 255.255.255.0

FortiGate-VM64-KVM (port1) # set allowaccess ping https ssh telnet http 

FortiGate-VM64-KVM (port1) # end

FortiGate-VM64-KVM # config system ntp 

FortiGate-VM64-KVM (ntp) # set ntpsync disable 

FortiGate-VM64-KVM (ntp) # set type custom 

FortiGate-VM64-KVM (ntp) # end

FortiGate-VM64-KVM # execute reboot 

This operation will reboot the system !
Do you want to continue? (y/n)

## Voir la liste des interfaces
FortiGate-VM64-KVM # show system interface ?

# Merci Beaucoup!
