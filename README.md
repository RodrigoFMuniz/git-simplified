# Git

## Concepts

Git trata seus dados mais como um conjunto de imagens de um sistema de arquivos em miniatura.
Toda vez que você fizer um commit, ou salvar o estado de seu projeto no Git, ele basicamente tira uma foto de todos os seus arquivos e armazena uma referência para esse conjunto de arquivos. Para ser eficiente, se os arquivos não foram alterados, o Git não armazena o arquivo novamente, apenas um link para o arquivo idêntico anterior já armazenado. O Git trata seus dados mais como um fluxo do estado dos arquivos.

![Versionamento](./readme.md-assets/versionamento.png)

Armazenando dados como um estado do conjunto de arquivos do projeto ao longo do tempo.
Esta é uma diferença importante entre o Git e quase todos os outros VCSs. Isto faz o Git reconsiderar quase todos os aspectos de controle de versão que a maioria dos outros sistemas copiaram da geração anterior.

---

## Integrity

O mecanismo que o Git utiliza para esta soma de verificação é chamado um hash SHA-1. Esta é uma sequência de 40 caracteres composta de caracteres hexadecimais (0-9 e-f) e é calculada com base no conteúdo de uma estrutura de arquivo ou diretório no Git. Um hash SHA-1 é algo como o seguinte:

```
24b9da6552252987aa493b52f8696cd6d3b00373
```

#

## Git work tree

![git work tree](./readme.md-assets/areas.png)

---

## Git init

```git
git init
```

---

## Git config

```git
git config <argument>
```

---
