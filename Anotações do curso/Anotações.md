# Anotações do Curso Git/GitHub da DIO

## O que é o Git?

- O git é um sistema de versionamento de código distribuido:
  - Ele ajuda a ciar e a monitorar diversas versões do nosso código. 

- O git e o github não são a mesma coisa

## O que pode ser feito?

1. Controle de versão;
2. Armazenmento em nuvem;
3. Trabalho em equive;
4. Melhorar o seu código;
5. Reconheciomento.

### Como o git funciona por baixo dos panos?

- SHA1
  - Algoritimo de encriptação HASH;
  - A encriptação gera um conjunto de caracteres com 40 digitos;
  - Unico;
  - Forma mais curta de representar um arquivo.
- BLOBS
  - O tipo do objeto estar contio no BLOB;
  - Contém o tamanho do objeto.
- TREES
  - Armazena os BLOBS;
  - Armazena o nome do arquivo;
  - Arma toda a estrutura dos arquivos.
- COMMIT
  - Aponta para uma TREE, parente, autor e mensagem;
  - Tambem tem encriptação.