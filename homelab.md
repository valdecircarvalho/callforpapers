Meu Homelab
http://homelaber.com.br/meu-homelab/

My Homelab
http://homelaber.com.br/meu-homelab/



Homelab 2018

Um pouco de história.
Eu comecei com um lab de VMware vSphere rodando em um notebook e ao longo do tempo fui comprando, trocando e conseguindo uma tonelada de equipamentos, já tive quase que um datacenter em casa – servidor de rack, storage, etc – mas o consumo de energia era proibitivo para deixar ligado 24X7 e o calor e ruído eram excessivos e causava um incômodo desnecessário.

Fiz um downgrade e o equipamento que tenho hoje atendem plenamente aos meus requisitos:

Custo acessível
Baixo ruído
Baixo consumo de energia
Potência – poder de processamento.
Equipamento:
Hoje o meu lab é composto de 3 Hosts vSphere, sendo um servidor “Enterprise” e dois “Desk Servers” e também um Switch Layer 3.

HPE ML 110 G9 – falei sobre esse servidor aqui
Intel(R) Xeon(R) CPU E5-1603 v3 @ 2.80GHz
64GB RAM
2X HD 2.0 TB
2X SSD 256 GB

Lenovo M92p
Intel(R) Core(TM) i7-3770 CPU @ 3.40GHz
32GB RAM
1X HD 2.5 TB
1X SSD 256 GB

Lenovo M92p
Intel(R) Core(TM) i7-3770 CPU @ 3.40GHz
28GB RAM
1X HD 1.5 TB
1X SSD 256 GB

Switch Cisco SG500X-24 24-Port Gigabit

Esse é um switch Cisco da linha Small Business, que atende perfeitamente o meu Lab para tudo o que eu quiser fazer. Link para o datasheet


Arquitetura do Lab
Não vou postar aqui uma arquitetura do lab, pois ela está sempre mudando, mas basicamente esses equipamentos estão atrás do modem da minha operadora e rodando em uma rede (VLAN) isolada do resto da rede da minha casa.

Software
A base do meu lab é o VMware ESXi. Em cima dele consigo rodar praticamente qualquer workload que eu desejar, até mesmo outros hypervisors utilizando Nested Virtualization.

Tenho acesso a todo o portfólio de produtos VMware através do programa VMware vExpert e também do VMUG Advantange. Então #ficaadica

Felizmente, por causa do vExpert, acabo tendo acesso a licenças NFR (Not For Resale) de vários outros fabricantes, como Veeam, Vembu, Zerto, Nutanix, etc.

Os software que não tenho acesso NFR – no caso de produtos Microsoft – acabo utilizando uma assinatura MSDN que eu tenho – e está acabando – ou ainda em Trial Mode.



Lab dos Sonhos
SE eu tivesse grana para investir em um lab dos sonhos, HOJE ele seria assim:

3 Hosts SuperMicro SYS-E300-8D com 128GB de RAM com 1X SSD 1TB + 1 SSD 512 GB em cada (All Flash baby!!)
1 Intel NUC SKULL (NUC6i7KYK) com 32Gb e SSD 512GB
1 Switch 10GB Netgear XS708T-100NES (8 portas 10GB)
1 Switch Cisco L3 24 portas (um 2960 já estaria de bom tamanho ou um ainda menor)
1 NAS Synology DS1517+ com interface 10GB
Tudo isso dentro de um Rack pequenininho para caber embaixo da minha mesa 🙂

Deixe ai nos comentários, qual é o seu lab e qual é o seu lab dos sonhos!
