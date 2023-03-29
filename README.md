# Aula-29-03-2023

Servidor DHCP e um protocolo de automatização de informações de internet no dispositivo conectado a Internet
Ele serve para facilitar o acesso a Internet, vale lembrar que o endereço IP fica alocado no dispositivo temporariamente, sendo nescessario periodicamente a atualização da alocação 

Cliente entra na rede e procura pelo servidor enviando uma mensagem e em BROADCAST;

CLASSES de Endereçamento IPv4 - CLASSE A (Não exsite mais)

Atribuidos a redes com um vasto numero de hosts (grandes provedores);

Permite a alocação de 126 redes e 16.777.214 host/redes

Faixa de endereçamento - Redes de 1 ate 126; (Classe A)

Mascara default de Sub-rede - 255.0.0.0 ou /8bits

CLASSES DE ENDEREÇAMENTO IPv4 - CLAASE B

Classe B Redes de 128 ate 191 
Mascara Default de Sub-Rede - 255.255.0.0 ou /16bits

CLASSES DE ENDEREÇAMENTO IPv4 - CLAASE C

Classe C Redes de 192 ate 223; 
Mascara Default de Sub-Rede - 255.255.255.0 ou /24bits

Categoria de endereço IPv4

Endereço Publicos 

-Aribuidos pela IANA
-Equivale a um IP publico, reconhecido mundialmente;
-Roteavel na Internet, ou seja, existem caminhos para seu acesso;

RUA PAULICO COELHO -265 PORTO ALEGRE/RS - BRASIL 

Endereços Privados (DECORAR)

-São reservados pela IANA;
-Podem ser ultilizados para endereçamentos dos hosts em redes não acessveis a Internet;
-Não roteavel na Internet,ou seja, não existem caminhos para seu acesso via Internet;

RAFAEL RUIVO HOUSE'S

CLASSSE IP (DECORAR)

10.0.0/8bits
172.16.0.0/12bits(reservados) falta 4 bits (240) (Identificar redes) a partir 172.16.0.0 ate 172.31.0.0 e ultilizado pela rede privada
127..0.0/8 LocalHost
169.254.0.0/16bits (Caso não tenha ip com o roteador )

TRADUÇÂO DE ENDEREÇOS NAT 

-Mecanismo de tradução de Endereços;

-Criado devido a escassez de endereços IPv4

-Consiste em ultilizar um ou (Ou N) IP Publico, roteavel para conectar um cojunto de maquinasd com IPs privados a Internet

Trabalho com Tradução Estatica (1:1), (1,N), (N,N)

NAT ESTATICO 

-Entrega um endereço publico para a maquina com endereço privado, para o recebimento de pacotes da internet

NAT ESTATICO OverLoad

-O BAT OverLoad, e o metodo mais ultilizado em todas as redes privadas, que se conectam a internet
-Multiplos IP's Privados Ultilizam 1 uinco IP Publico ;

Mantem a porta do endereço privado e troca o IP









