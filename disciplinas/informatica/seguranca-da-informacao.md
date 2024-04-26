# Segurança da Informação

## DEFINIÇÃO
* A segurança da informação é pautada pela confiabilidade.
* Princípios:
  - Confidencialidade;
  - Integridade;
  - Disponibilidade;
  - Autenticidade;
  - Não repúdio;
  - Conformidade.

> ### Confidencialidade
* Consiste em conseguir garantir que uma informação não seja acessada por terceiros.

> ### Integridade
* A integridade visa garantir que uma alteração não seja alterada (mexida).

> ### Disponibilidade
* A disponibilidade consiste em garantir que o sistema esteja sempre disponível para as pessoas devidamente autorizadas a usá-lo.

> ### Autenticidade 
* A autenticidade visa garantir a legitimidade, ou seja, garantir que uma informação é legítima.

> ### Não repúdio
* O não repúdio é o princípio da irretratabilidade, que prevê a impossibilidade de alguém negar que realizou um ato.

> ### Conformidade
* O princípio da Conformidade prevê que as empresas devem agir em conformidade com a Lei.

## POLÍTICAS DE SEGURANÇA
* As políticas de segurança são as normas e as regras que as empresas produzem para que os funcionários, servidores públicos e colaboradores sigam. 
* Se algum desses atores quebrar uma dessas políticas, poderá sofrer desde uma advertência até uma demissão.
* A política de segurança define os direitos e as responsabilidades de cada um em relação à segurança dos recursos computacionais que utiliza e as penalidades às quais está sujeito, caso não a cumpra.
* É considerada como um importante mecanismo de segurança, tanto para as instituições como para os usuários, pois com ela é possível deixar claro o comportamento esperado de cada um. 
* A política de segurança pode conter outras políticas específicas, como:
  - Política de senhas: define as regras sobre o uso de senhas nos recursos computacionais, como tamanho mínimo e máximo, regra de formação e periodicidade de troca.
  - Política de backup: define as regras sobre a realização de cópias de segurança, como tipo de mídia utilizada, período de retenção e frequência de execução.
  - Política de privacidade: define como são tratadas as informações pessoais, sejam elas de clientes, usuários ou funcionários.
  - Política de confidencialidade: define como são tratadas as informações institucionais, ou seja, se elas podem ser repassadas a terceiros.
  - Política de uso aceitável (PUA) ou Acceptable Use Policy (AUP): também chamada de Termo de Uso ou Termo de Serviço, define as regras de uso dos recursos computacionais, os direitos e as responsabilidades de quem os utiliza e as situações que são consideradas abusivas.

> ### Componentes de segurança

#### Controle de Acesso Físico
* Administram o acesso de pessoas, veículos e materiais a uma área restrita e protegida. 
* Exemplos: Alarmes, sensores de presença, câmeras de vídeo, catracas.

#### Controle de Acesso Lógico 
* Impedir que pessoas acessem documentos, dados ou qualquer tipo de informação sem a autorização adequada. 
* Exemlos: Senhas, firewalls, antivírus, encriptação de dados.

#### Senhas 
* Para senhas o fator a ser considerado é o nível de segurança (forte, Média e fraca).
* Para ser considerada forte, uma senha deve ser alfanumérica (deve conterletras e números), deve conter caracteres especiais, pode ser formada por meio de uma frase, pode ser case sensitive (diferenciação de maiúsculas e minúsculas).
* Tipos de senhas:
  - Uso de Tokens (O que o usuário possui);
  - Biometria (aquilo que o usuário é);
  - Uso de autenticação em DOIS fatores.

#### Firewall
* Filtragem de pacotes e acessos indevidos. (filtro, sistema, mecanismo, ferramenta, dispositivo, hardware ou software).
* O firewall pessoal presente no Windows é um firewall na forma de um software. Contudo, há um firewall de rede, na forma de um hardware.
* O firewall tem a capacidade de filtrar os pacotes de dados que entram nas portas TCP e UDP das máquinas. Ademais, por meio de regras específicas, é possível definir uma regra para que um firewall filtre determinado tipo de pacote.
* O firewall trabalha também com um filtro de IP (protocolo lógico pelo qual um dispositivo conecta à internet). Assim, é possível definir listas de IPs autorizados e IPs não autorizados a adentrar uma determinada rede.
* O Firewall pode impedir que pragas virtuais adentrem uma máquina e se espalhem pela rede, graças às políticas de segurança usadas para filtro e tráfego.

#### Proxy
* O Proxy é um tipo de firewall (firewall de aplicação da camada 7, do modelo OSI: Controle de acesso, Filtro de conteúdo e Cache).

#### Uso de assinatura e certificação digital
* A certificação digital e a assinatura digital fazem parte da ICP Brasil (Infraestrutura de chaves públicas), criada pelo Governo de FHC em 2001, por meio de uma medida provisória que deu validade civil e jurídica a essas ferramentas.
* Autoridades criadas:
  - Autoridade de Registro (AR) – vendedora/terceirizada. Ela deve ser acessada quando se desejar adquirir uma assinatura ou uma certificação. Neste caso, a autoridade de registro apenas solicita a geração de assinatura ou certificação.
  - Autoridade certificadora (AC) – É o cartório ou entidade geradora da assinatura ou certificação.
  - Autoridade certificadora raiz (ACR) – É a autoridade que faz a homologação de toda a cadeia. É vinculada à Presidência da República, na Casa Civil.

##### Funcionamento da assinatura digital
1. O remetente assina o documento com a sua chave privada, gerando a chave pública que será enviada com o documento.
2. O destinatário recebe o documento com a chave pública do remetente para efetuar a conferência.
3. Durante este trâmite é usada a função hash, que é o resumo do conteúdo do documento que fica armazenado em uma chave criptográfica.

#### Certificado digital
* O certificado digital garante validade jurídica a pessoas ou a máquinas.
* Dentro de um certificado digital existe a criptografia (que vai garantir a confidencialidade) e assinatura digital (que deve garantir a integridade, a autenticidade e o não repúdio).

## MALWARES
* Malwares são softwares maliciosos.

> ### Vírus
* Vírus é um programa ou parte de um programa de computador, normalmente malicioso, que se propaga inserindo cópias de si mesmo e se tornando parte de outros programas e arquivos.
* O vírus busca contaminar arquivo ou programa. Ele nunca age sozinho, pois depende sempre de um hospedeiro.
* O vírus, além de não ser autônomo, precisa de alguém para se hospedar, com exceção do vírus de script (vírus de sites de navegadores).

> ### Worm
* Worm é um programa capaz de se propagar automaticamente pelas redes, enviando cópias de si mesmo de computador para computador.
* Diferente do vírus, o worm não se propaga por meio da inclusão de cópias de si mesmo em outros programas ou arquivos, mas sim pela execução direta de suas cópias ou pela exploração automática de vulnerabilidades existentes em programas instalados em computadores.

> ### Bot
* Bot é um programa que dispõe de mecanismos de comunicação com o invasor que permitem que ele seja controlado remotamente. Possui processo de infecção e propagação similar ao do worm, ou seja, é capaz de se propagar automaticamente, explorando vulnerabilidades existentes em programas instalados em computadores.

> ### Trojans ou cavalos de troia
* Programa que, além de executar as funções para as quais foi aparentemente projetado, também executa outras funções, normalmente maliciosas, e sem o conhecimento do usuário.
* Exemplos de trojans são programas que o usuário recebe ou obtém de sites na Internet e que parecem ser apenas cartões virtuais animados, álbuns de fotos, jogos e protetores de tela, entre outros. Estes programas, geralmente, consistem de um único arquivo e necessitam ser explicitamente executados para que sejam instalados no computador.

> ### Spyware
* Spyware é um programa projetado para monitorar as atividades de um sistema e enviar as informações coletadas para terceiros.
* O spyware age principalmente por meio dos cookies, que são os arquivos TXT que armazenam as preferências dos usuários.

> ### Keylogger
* Keylogger é capaz de capturar e armazenar as teclas digitadas pelo usuário no teclado do computador. Sua ativação, em muitos casos, é condicionada a uma ação prévia do
usuário, como o acesso a um site específico de comércio eletrônico ou de Internet Banking.

> ### Screenlogger
* Screenlogger é similar ao keylogger, capaz de armazenar a posição do cursor e a tela apresentada no monitor, nos momentos em que o mouse é clicado, ou a região que circunda a posição onde o mouse é clicado. É bastante utilizado por atacantes para capturar as teclas digitadas pelos usuários em teclados virtuais, disponíveis principalmente em sites de Internet Banking.

> ### Ransomware
* Ransomware é um tipo de código malicioso que torna inacessíveis os dados armazenados em um equipamento, geralmente usando criptografia, e que exige pagamento de resgate (ransom) para restabelecer o acesso ao usuário.
* O pagamento do resgate geralmente é feito via bitcoins.
* A melhor maneira de se livrar do ransomware é fazer backups regulares.

> ### Phishing
* Phishing, phishing-scam ou phishing/scam, é o tipo de fraude por meio da qual um golpista tenta obter dados pessoais e financeiros de um usuário, pela utilização combinada de meios técnicos e engenharia social.