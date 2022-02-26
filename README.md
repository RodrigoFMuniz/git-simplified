# Git

## Concepts

Git trata seus dados mais como um conjunto de imagens de um sistema de arquivos em miniatura.
Toda vez que você fizer um commit, ou salvar o estado de seu projeto no Git, ele basicamente tira uma foto de todos os seus arquivos e armazena uma referência para esse conjunto de arquivos. Para ser eficiente, se os arquivos não foram alterados, o Git não armazena o arquivo novamente, apenas um link para o arquivo idêntico anterior já armazenado. O Git trata seus dados mais como um fluxo do estado dos arquivos.

![Versionamento](./readme.md-assets/versionamento.png)

#

## Git work tree

![git work tree](./readme.md-assets/areas.png)

---

## Git init

```git
git init
```
