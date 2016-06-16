# BTI-Documents

Um compilado com alguns documentos que realizam um estudo dirigido de algumas
 disciplinas do Bacharelado em Tecnologia da Informação da Universidade Federal
 do Rio Grande do Norte.

O objetivo aqui é compartilhar conhecimento e informação para as outras pessoas,
e buscar direcionar o estudo por meio de um "documento-resumo".

## Sumário #

* [Documentos](#documentos)
  * [Tabela de Dispersão](#tabela-de-dispersão---hash_tablepdf)
  * [Teoria Axiomatica dos Conjuntos](#teoria-axiomatica-dos-conjuntos---fmc2_un2pdf)
  * [Dispositivos E/S e Sistema Operacional](#dispositivos-es-e-sistema-operacional---ioac_un3pdf)
  * [Modelos Probabilisticos](#modelos-probabilisticos---probpdf)
* [LaTeX](#latex)
  * [Como compilar os arquivos .tex](#como-compilar-os-arquivos-tex)
* [Contribua](#contribua)

## Documentos #

Essa é a organização dos documentos:

```plain-text
BTI-Documents/
├── [EDB] - Estruturas de Dados Básicas
│   ├── hash_table.pdf - Explicações sobre a TAD de Tabela de Dispersão
│   ├── hash_table.tex - Arquivo fonte do documento hash_table.pdf
├── [FMC2] - Fundamentos Matemáticos da Computação 2
│   ├── fmc2_un2.pdf - Teoria Axiomática dos Conjuntos e Lambda-Calculus
│   └── fmc2_un2.tex - Arquivo fonte do documento fmc2_un2.tex
├── [IOAC] - Introdução a Arquitetura e Organização de Computadores
│   └── ioac_un3.pdf - Dispostivos de E/S, Barramento, Multithreading e Sistema
Operacional
└── Probabilidade
    └── prob.pdf - Modelos Probabilisticos Discretos e Contínuos
```

### Tabela de Dispersão - hash_table.pdf #

Uma tabela de dispersão, ou Hash Table, é uma TAD que funciona como
um dicionário, contendo uma chave e uma informação para cada objeto
armazenado. Cada chave é mapeada em um determinado ponto da tabela.

### Teoria Axiomatica dos Conjuntos - fmc2_un2.pdf #

Explanações sobre a Teoria Axiomatica dos Conjuntos, com todos os axiomas
de Zermelo-Frankel. Também conta com um conteúdo de Lambda-Calculus,
um sistema que estuda funções recursivas computáveis.

### Dispositivos E/S e Sistema Operacional - ioac_un3.pdf #

Caracaterísticas e tipos dos dispositivos de entrada e saída, organização
e funções dos componentes de para E/S, introdução básica a Sistemas Operacionais
e explicações sobre Multithreading e Multicore.

### Modelos Probabilisticos - prob.pdf #

Alguns modelos Probabilisticos discretos e contínuos, com todas as respectivas
funções e exercícios com gabarito.

## LaTeX #

A maioria dos documentos aqui presentes estão feitos em LaTeX, uma linguagem de
diagramação de texto muito utilizada em textos cientifícos e matemáticos.
A maioria dos arquivos fontes estão disponíveis para edições e melhorias por
outros usuários.

### Como compilar os arquivos .tex #

Você é capaz de compilar os arquivos .tex e gerar um .pdf usando (Linux):

```plain-text
    $ pdflatex <nome>.tex
```

Caso você não possua um Latex instalado em sua máquina, [clique aqui](http://ubuntued.info/como-instalar-o-latex-no-ubuntu).

## Contribua #

Contribua com os documentos. Mande seu Pull Request com sugestões, outros
documentos e melhorias.

Não precisa enviar apenas documentos em formato .tex, deixe também seus estudos
em outros formatos (quem sabe se a gente não converte ele depois?).
