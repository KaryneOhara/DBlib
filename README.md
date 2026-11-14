# DBlib: Biblioteca para criação e gerenciamento de bancos de dados em C

## Descrição

O projeto consiste no desenvolvimento de uma biblioteca em linguagem C
voltada à criação, organização, armazenamento e manipulação de pequenos
bancos de dados.

A biblioteca permitirá que programas externos criem e abram arquivos de
dados, insiram, consultem, atualizem e excluam registros, além de
recuperar informações previamente armazenadas.

O armazenamento das informações será realizado por meio de arquivos
binários, garantindo a persistência dos dados entre diferentes execuções
dos programas. A estrutura dos registros será definida pelo próprio
usuário por meio de estruturas (`struct`), permitindo que a biblioteca
seja utilizada em diferentes aplicações sem depender de um modelo fixo
de dados.

O objetivo é oferecer uma alternativa simples e reutilizável para o
gerenciamento de dados em aplicações desenvolvidas em C, explorando
conceitos como alocação dinâmica de memória, manipulação de arquivos e
ponteiros. Dessa forma, busca-se disponibilizar uma solução simples,
reutilizável e eficiente para o gerenciamento de informações.
