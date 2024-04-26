# Redes de Computadores

<br>

## INTERNET
* É a rede mundial de comunicação entre computadores, formada por milhares de redes telefônicas e informáticas que forcecem produtos e serviços.
* As grandes conexões de transferência de alta velocidade e alta capacidade que conectam os continentes são chamados de **backbone**.

## SERVIÇOS PRESENTES NA INTERNET

> ### Wiki
* Página web formada pela colaboração das pessoas e aberta a alteração por qualquer usuário, em que as mudanças são validadas por moderadores.

> ### Motor de busca
* É o software responsável por encontrar informações armazenadas a partir de palavras chave. O resultado das buscas é indexado a partir do navegador utilizado.
* O Buscador chamado de  Aranha da web (Spider, crawler, robô, bot) coleta as informações e é indexado pelo navegador (google, bing, etc).

#### Filtros do google

| FILTRO  | AÇÃO                                  | Exemplo                     |
| ------- | ------------------------------------- | --------------------------- |
| ""      | Pesquisa exata                        | "melhor carro"              |
| -       | Excluir da busca                      | velocidade do jaguar -carro |
| OR      | Resultados com as duas palavras chave | carro OR moto               |
| Inurl   | Páginas que contenham palavras da URL |                             |
| Related | Páginas do mesmo assunto              |                             |
| Link    | Páginas que fazem referência          |                             |
| ..      | Intervalo                             |                             |
| Site:   | Páginas do portal                     | site:google.com             |
| #       | Redes sociais                         | #nome                       | 
| @       | Twitter                               | @twitter palavra            |
| $       | Pesquisa de preços                    | celular $1000               | 
| *       | Termos desconhecidos                  | como criar * em python      |

## PROTOCOLOS DA INTERNET
* Conjunto de regras e convenções padronizadas paa troca de dados entre computadores ligados em rede.
* O principal modelo de protocolos utilizado é o TCP/IP que tem como referência o modelo OSI.

<br>
<div style="display:inline_block">
    <img align="left" height="200" width="500" src="../../img/tcp-e-osi.png">
</div>
<br><br><br><br><br><br><br><br><br><br><br>

<br>
<div style="display:inline_block">
    <img align="left" height="200" width="500" src="../../img/camadas.png">
</div>
<br><br><br><br><br><br><br><br><br><br><br>

<br>
<div style="display:inline_block">
    <img align="left" height="300" width="500" src="../../img/fluxo-camadas.png">
</div>
<br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br>

> ### Protocolo TCP
* O TCP (transmission control protocol), protocolo orientado para a conexão, possibilita a transferência de dados na internet, com as características de confiabilidade, isto é, a mensagem chega ao receptor ou mensagens enviadas chegam na ordem de envio. O TCP é o protocolo responsável em transportar os pacotes de dados da rede. Utilizado em transporte de pacotes que exigem confiabilidade. 
* São Exemplos: E-mail, transferência de sites, etc.

> ### Protocolo UDP
* O UDP (User Datagram Protocol), um protocolo não orientado para a conexão, possibilita a transferência de dados na internet, com as características de não confiabilidade, isto é, a mensagem pode não chegar ao receptor ou mensagens enviadas podem chegar fora da ordem de envio. Utilizado em transporte de pacotes que exigem velocidade e não confiabilidade.
* São Exemplos: Chamadas ao vivo etc.

> ### Protocolo IP
* O TCP e o Internet Protocol (IP - Protocolo de Internet), são os dois protocolos mais importantes da internet. Em suma, o protocolo IP especifica o formato dos pacotes que são enviados e recebidos entre roteadores e sistemas finais. 
* Endereço de Protocolo da Internet (Endereço IP/IP address), é um número atribuído a cada dispositivo (computador, impressora, smartphone etc.) conectado a uma rede de computadores que utiliza o Protocolo de Internet para comunicação. O IP não estabelece uma conexão para envio dos pacotes, nem garante um serviço confiável de envio de mensagens com retransmissão em caso de perda. Sendo assim, toda vez que se conecta a uma rede, ganha-se um número de identificação, chamado de IP.

> ### Protocolo NAT
* NAT (network address translation) é um protocolo que faz a tradução dos endereços Ip e portas TCP da rede local para a Internet. 
* Por exemplo, o pacote a ser enviado ou recebido de sua estação de trabalho na sua rede local, vai até o servidor onde seu ip é trocado pelo ip do servidor a substituição do ip da rede local valida o envio do pacote na internet, no retorno do pacote acontece a mesma coisa, porém ao contrário o que garante que o pacote chegue ao seu destino.
* Quando as máquinas na rede local mandam os pacotes para o roteador, o protocolo chamado NAT, pegará os pacotes e converterá o IP dessas máquinas para o do roteador e mandará
para a internet, quando devolver, faz o contrário (reconverte o IP do roteador para o IP local).

> ### Protocolo ARP
* ARP pega o IP e associa ao MAC ADRESS. Ele tem um papel fundamental entre os protocolos da camada Internet da suíte TCP/IP, porque permite conhecer o endereço físico de uma placa de rede que corresponde a um endereço IP. 

> ### Protocolo RARP 
* Faz o contrário do ARP, pois pega o MAC (endereço físico) e associa ao lógico (IP).
* Cada máquina ligada à rede possui um número de identificação de 48 bits. Este número é um número único, fixado a partir da fabricação da placa de rede na fábrica. Entretanto, a
comunicação na Internet não é feita diretamente a partir deste número (porque seria necessário alterar o endereçamento dos computadores cada vez que se alterasse uma placa de
rede), mas a partir de um endereço dito lógico, atribuído por um organismo, o endereço IP.
* Assim, para fazer a correspondência entre os endereços físicos e os endereços lógicos, o protocolo ARP pergunta às máquinas da rede para conhecer o seu endereço físico e depois cria uma tabela de correspondência entre os endereços lógicos e os endereços físicos numa memória.

> ### Protocolo DHCP
* Dynamic Host Configuration Protocol é um protocolo de serviço TCP/IP que oferece configuração dinâmica de terminais, com concessão de endereços IP de host e outros parâmetros de configuração para clientes de rede.
* Ao colocar o dispositivo no modo avião, perdem-se as conexões de rede. Quando sai do modo avião, o telefone procura o sinal da operadora, encontra, conecta por intermédio do chip, realiza a autenticação e o protocolo da operadora gera o IP, desse modo, só se pode acessar a rede, pois o protocolo gerou o IP para se conectar a ela.

> ### Protocolo DNS
* Cada domínio possui um registro no DNS que define qual o endereço IP do servidor de hospedagem e o IP do servidor de e-mail que responderão por este domínio. 
* O processo para a descoberta dos servidores que respondem por um domínio é denominado resolução do nome ou resolução do domínio. 
Sendo assim, todo endereço que se digita um nome, é um número (Ip, o computador só entende endereços numéricos), desse modo, para não ter que memorizar milhares de sites acessados, assim que se digita o endereço e aperta enter, o nome irá para um DNS, que irá usar esse nome e procurar pelo IP em uma tabela, se existir, a página retornará para o usuário; se for digitado errado, não achará o IP e haverá o erro 404.

> ### Protocolo HTTP
* HyperText Transfer Protocol (Protocolo de transferência de Hipertexto) é o conjunto de regras que permite a transferência de informações na Web. Responsável pelo acesso as páginas da WWW via navegador.
* O HTTP não é seguro, trabalha com texto cru, é de fácil de interceptação e leitura de dados de terceiros na rede. 

> ### Protocolo HTTPS 
* HyperText Transfer Protocol secure, é uma implementação do protocolo HTTP sobre uma camada SSL ou do TLS, essa camada adicional permite que os dados sejam transmitidos através de uma conexão criptografada e que se verifique a autenticidade do servidor e do cliente através de certificados digitais.
* Ao se conectar a um navegador, por exemplo, é aberta uma porta entre o usuário e servidor acessado, que são numeradas, os protocolos atuam em portas fixas, como o HTTP (porta 80, por norma), HTTPS (porta 443), DNS e protocolos de e-mails também têm suas portas.

> ### Protocolo FTP 
* File Transfer Protocol (Protocolo de Transferência de Arquivos), é uma forma bastante rápida e versátil de transferir arquivos (também conhecidos como ficheiros), sendo uma das mais usadas na internet. 

> ### Protocolo SMTP 
* Simple Mail Transfer Protocol é o protocolo padrão para envio de e-mails através da Internet. 

> ### Protocolo POP 
* Post Office Protocol (POP3) é um protocolo utilizado no acesso remoto a uma caixa de correio eletrônico. O POP3 está permite que todas as mensagens contidas numa caixa
de correio eletrônico possam ser transferidas sequencialmente para um computador local.
* Esse é um protocolo antigo. O servidor fica sem os e-mails, se precisar acessar de outro computador, não será possível.

> ### Protocolo IMAP 
* Internet Message Access Protocol é um protocolo de gerenciamento de correio eletrônico que as mensagens ficam armazenadas no servidor e o internauta pode ter acesso a suas pastas e mensagens em qualquer computador, tanto por webmail como por cliente de correio eletrônico.
É o protocolo mais usado. As mensagens ficam sincronizadas no servidor e na máquina, assim, ao ir em outro computador, será possível ter acesso aos e-mails.