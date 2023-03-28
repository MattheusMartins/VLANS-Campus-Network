# VLANS-Campus-Network

Tarefas:

Configure a rede da seguinte forma:
1) 3650 = switch de camada 3 com endereços IP e roteamento interVLAN:
VLAN 1 = 10.1.1.254/24
VLAN 10 = 10.1.10.254/24,
VLAN 20 = 10.1.20.254/24
VLAN 30 = 10.1.30.254/24,
VLAN 100 = 10.1.100.254/24
2) Os switches da camada de acesso terão apenas endereços IP de gerenciamento na VLAN 1:
Interruptor 1 = 10.1.1.1/24
Interruptor 2 = 10.1.1.2/24
Interruptor 3 = 10.1.1.3/24
3) Configure as portas de acesso da seguinte forma:
PC1 na VLAN 10 - 10.1.10.10/24
PC2 na VLAN 20 - 10.1.20.20/24
PC3 na VLAN 30 - 10.1.30.30/24
Servidor1 na VLAN 100 - 10.1.100.100/24
4) Configurar portas entre switches como troncos
5) Certifique-se de que os PCs possam executar ping entre si e no servidor
6) Certifique-se de que os switches possam fazer ping nos PCs e no servidor

<img src="https://raw.githubusercontent.com/MattheusMartins/VLANS-Campus-Network/main/1.PNG">
