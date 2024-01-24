# Hardware

<br>

## DEFINIÇÃO
* Hardware é a parte física dos sistemas computacionais.

## TIPOS DE HARDWARE

> ### Computadores de grande porte
* Compuradores utilizados por empresas, sendo conhecidos como servidores.
* Possuem arquitetura própria e são utilizados para oferecer serviços na internet, atendendo milhare de usuários ao mesmo tempo.

> ### Computadores pessoais
* Seu uso é voltado ao público geral.
* Principais modelos:
  - Desktop (computador de mesa);
  - Notebook;
  - Netbook;
  - Ultrabook.

> ### Dispositivos móveis
* Utilizados via touch screen, são dispositivos de uso na mão, sendo atualmente os mais utilizados.
* É formado por tablets e smartphones.

> ### Periféricos
* Dispositivos que auxiliares no processamento dos computadores. Podem ser internos ou externos.

#### Dispositivos de entrada
* Esses dispositivos enviam dados para a CPU.
* Exemplos:
  - Teclado;
  - Mouse;
  - Scanner;
  - Webcam;
  - Microfone;
  - Leito óptico.

#### Dispositivos de saída
* Recebem dados processados da CPU como porta de saída.
* Exemplos:
  - Monitor;
  - Datashow/Projetor;
  - Caixa de som;
  - Impressora.

#### Dispositivos de entrada e saída
* Enviam e recebem dados do processador.
* Exemplos:
  - Tela touchscreen;
  - Pen drive;
  - HD/SSD;
  - Gravador de CD/DVD;
  - Modem;
  - Impressora multifuncional.

## ORGANIÇÃO E ARQUITETURA DOS COMPUTADORES

> ### Placa mãe
* A placa mãe é responsável por integrar todos os componentes de hardware do computador e gerencia a comunicação entre eles.
* Na placa mãe existem os componentes onboard (integrados) e os offboard (conectados).
* A placa mãe possui slots de conexão de componentes, barramentos onde trafegam os dados e uma bateria que armazena dados de configurações da placa.

#### Chipset
* É um conjunto de circuitos integrados que controla a comunicação entre as partes do computador.
* É dividido em duas pontes: ponte norte que interliga componentes de rápido processamento(CPU, RAM, PCIe) e ponte sul que liga os componentes de processamento lento (dispositivos de E/S).

#### Barramentos
* São vias por onde os dados são transmitidos e que conectam os dispositivos do computador. Existem barramentos de 32 bits e de 64 bits.
* Barramentos de 32 bits suportam apenas 4gb de ram, já os de 64 bits alcançam até 18 bilhões de gigabytes de ram.
* Não há compatibilidade entre sistemas de 32 bits e aplicações de 64 bits, já os sistemas de 64 bits suportam apps de 32 bits, embora não seja o mais eficiente usa-los.
* Existem 3 tipos de barramentos:
  - Barramento de dados (tráfego de dados);
  - Barramento de endereço (endereçamento da memória);
  - Barramento de controle (gerencia o acesso aos dados).

##### Inteface/Barramento USB
* É uma tecnologia de transferência de dados de transmissão bit a bit. Possui diversas versões e com variados conectores. A sigla USB significa universal serial bus. Além de transmitir dados o USB também oferece alimentação por voltagem.
* Tipos de conectores:
 - Tipo A;
 - Tipo B;
 - Mini B;
 - Micro B;
 - Tipo C.
* Versões do USB:
  - 1.0 (1,5 Mbps);
  - 1.1 (12 Mbps);
  - 2.0 (480 Mbps);
  - 3.0 (4,8 Gbps);
  - 3.1 (10 Gbps);
  - 3.2 (20 Gbps);
  - 4 (40 Gbps).

#### Interface concorrentes do USB
* Além do USB outros padrões de interface foram desenvolvidos.
* Tipos:
  - FireWire (produtos apple);
  - Lightning (iphone);
  - Thunderbolt (conector semelhante ao USB, porém com barramento de tecnologia mais eficiente, tem como símbolo um raio).

#### Interface de vídeo/áudio
* Exitem variadas interfaces de vídeo e áudio.
* Tipos:
  - VGA (conexão de vídeo analógico com um único pacote de cores);
  - S-vídeo (conexão de vídeo analógico com diferentes pacotes de cores);
  - DVI (conexão de vídeo digital);
  - HDMI (conexão digital de vídeo e áudio);
  - DisplayPort (conexão digital de vídeo e áudio).

#### Interface de disco
* Inteface de conexão de dispositivos de armazenamento.
* Tipos:
  - IDE (hd e drivers antigos de cd/dvd);
  - SATA (hd, ssds, drivers de cd/dvd);
  - PCI NVMe (ssd).

> ### CPU
* É o componente responsável por realizar o processamento no computador. CPU significa unidade central de processamento.
* Componentes da CPU:
  - ULA - Unidade Lógica Aritmética (responsável pelos cálculos matemáticos e lógicos);
  - UC - Unidade de Controle (responsável pelo acesso aos dados na memória e nos dispositivos conectados);
  - Registradores (Memória de processamento de altíssima velocidade e tamanho pequeno).
* Tipos de registradores:
  - RDM - Registradores de Dados de Memória (armazenam os dados utilizados pela ULA);
  - REM - Registradores de Endereços de Memória;
  - RI - Registrador de Instrução (registra os comandos dos softwares);
  - CI - Contador de Instruções (registra a ordem de execução das instruções a serem processadas pela CPU);
  - DI - Decodificador de Instrução (realiza a identificação de qual operação será realizada);
  - Clock - Relógio Gerador de Pulso (determina a velocidade em ciclos por segundo).
* Caracteristicas dos processadores:
  - Geração;
  - Núcleo (core);
  - Clock (velocidade em Ghz). 

#### Marcas de processadores
* As duas principais fabricantes de processadores são AMD e Intel.
* Modelos AMD:
  - Ryzen;
  - Athlon;
  - Turion;
  - Phenom.
* Modelos Intel:
  - Core I (3, 5, 7 e 9);
  - Dual Core;
  - Pentium.

> ### Memórias