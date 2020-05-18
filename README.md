# Mobile Pattern

## Introdução

Neste documento, serão apresentado as melhores práticas para auxiliar e padronizar o desenvolvimento do projeto. Será útil para novos desenvolvedores seguirem o padrão, afim de manter um código limpo e conciso. 

O padrão está baseado [neste](https://medium.com/@parthibansudhaman/flutter-scalable-app-folder-structure-6f2b0bc139c4) artigo, porém adequando ao nosso projeto.

## 1. Estrutura

O projeto segue os seguintes padrões de arquitetura:

<img src="https://i.imgur.com/Og1hmsb.png" width="25%" />

**assets**: Pasta para armazenar as imagens utilizadas no projeto.

**models**: Armazenará os *models* de cada entidade que o projeto venha necessitar.

**screens**: Nesta pasta contém as telas que serão utilizadas no layout.

**services**: Esta pasta é para operações back-end, como realizar chamar chamadas HTTP, etc.

**utils**: Todos os itens comuns estão aqui, como por exemplo: constantes e widgets genéricos utilizados no projeto.

## 2. Linguagem

Todo o projeto (estrutura de pastas, constantes, classes, variáveis e afins) estão em **inglês**. Isso torna o desenvolvedor mais apto a trabalhar a linguagem e se preparar para projetos maiores.

## 3. Colaboração

Este tópico é somente o mobile pattern, o arquivo de como contribuir com o projeto encontra-se clicando [aqui](CONTRIBUTING.md).
