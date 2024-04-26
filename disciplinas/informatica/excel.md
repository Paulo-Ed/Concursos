# Excel

<br>

## DEFINIÇÃO
* Editor de planilhas da microsoft.

#### Características
* Formatos: XML.XLSX, .XLS, .XLSM, XLT, XLTX, .ODS, .CSV, .XML, .HTML, .PDF.
* Cria pdf.
* É um software proprietário.
* É pago.
* O excel organiza as informações verticalmente em colunas, identificadas por letras, e horizontalmente em linhas, representadas por números.
* No Excel existem 1.048.576 linhas e 16.384 colunas, começando da coluna A e indo até a coluna XFD, cada vez que uma linha se cruza com uma coluna, forma-se uma célula, também conhecida como referência.

> ### Guia fórmula
* Contém ferramentas relacionadas a cálculos.

> ### Guia dados
* Apresenta ferramentas mais avançadas, que demandam maior habilidade do usuário.

> ### Operadores do Excel 365

| ARITMÉTICOS     | COMPARADORES          | CONCATENAÇÃO          | NÚMEROS E VALORES DE TEXTO | REFERÊNCIAS                 |
| --------------- | --------------------- | --------------------- | -------------------------- | --------------------------- |
| + (somar)       | = (igual)             | & (concatenar/juntar) | ""                         | ; (e)                       |
| - (subtrair)    | <> (diferente)        |                       | '                          | : (até)                     |
| * (Multiplicar) | > (maior)             |                       |                            | Espaço simples (interseção) |
| / (dividir)     | < (menor)             |                       |                            |                             |
| ^ (exponencial) | >= (maior igual)      |                       |                            |                             |
|                 | <= (menor igual)      |                       |                            |                             |

| TABELA DE PRIORIDADES DO EXCEL 365 |
| ---------------------------------- |
| 1º - ()                            |
| 2º - Funções - =soma(a1:a4)        |
| 3º - %                             |
| 4º - ˆ                             |
| 5º - * /                           |
| 6º - + -                           |
| 7º - concatenar - &                |
| 8º - comparações - =,<>, >,=,<=    |

## FUNÇÕES

#### Função CONT.SE
* Função que conta o número de células que atendem a um critério.
* Estrutura:
  - =CONT.SE(INTERVALO; CRITÉRIOS)

Ex: =CONT.SE(A2:A5;"Londres")

#### Função CONT.VALORES
* Conta o número de células que não estão vazias em um intervalo.
* Estrutura:
  - =CONT.VALORES(valor1;[valor2];...)

Ex: =CONT.VALORES(A2:A5) 

#### Função CONTAR.VAZIO
* Conta a quantidade de células vazias em um intervalo.
* Estrutura:
  - =CONTAR.VAZIO(INTERVALO)

#### Função CONT.NUM
* Conta o número de células que contêm números e conta os números na lista de argumentos.
* Estrutura:
  - =CONT.NUM(valor1;[valor2];...)

Ex: =CONT.NUM(A1:A20)

#### FUNÇÃO PROCV (VLOOKUP)
* A função PROCV é um recurso útil no Excel, empregado para buscar dados verticalmente em uma planilha. Geralmente, é utilizada para localizar informações associadas a
um determinado critério.
* Essa função é essencialmente uma ferramenta de pesquisa e sua sintaxe precisa ser compreendida para aplicá-la corretamente.
* Por exemplo, encontrar o nome de uma pessoa a partir do seu cpf.
* Estrutura:
  - =PROCV (QUEM PROCURAR; ONDE PROCURAR; COLUNA RETORNO; VALOR APROXIMADO)