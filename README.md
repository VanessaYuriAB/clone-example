# Clone Example (Git & GitHub Fundamentals)

Este repositório faz parte do meu aprendizado prático em **Git e GitHub**, com foco nos
principais comandos e no fluxo de trabalho utilizado no desenvolvimento de software
moderno.

Foi desenvolvido como parte do programa do _bootcamp de Desenvolvimento Web da Triple Ten
Brasil_, durante a _Sprint 3_ que aborda o **Fluxo de Desenvolvimento**.

O objetivo do projeto é demonstrar, de forma simples e organizada, como clonar um
repositório, criar arquivos, versionar mudanças e enviá-las para um repositório remoto no
GitHub.

![Git](https://img.shields.io/badge/Git-Controle%20de%20Vers%C3%A3o-orange)
![Status](https://img.shields.io/badge/Status-Conclu%C3%ADdo-success)

## 📌 Conceitos

Foram trabalhados os seguintes conceitos fundamentais:

- Clonagem de repositórios com `git clone`
- Navegação no terminal (_bash_)
- Criação de arquivos via _linha de comando_
- Versionamento com _Git_ (`add`, `commit`, `push`)
- Integração entre repositório local e remoto
- Uso do arquivo `.gitignore`
- Boas práticas iniciais de controle de versão

## 🛠️ Tecnologias utilizadas

- Git
- GitHub
- Terminal / Bash
- HTML
- CSS

## 📂 Estrutura do projeto

```Shell
clone-example/
├── .gitignore
├── index.html
├── README.md
└── style.css
```

## 🚀 Fluxo de trabalho utilizado

O fluxo de trabalho seguido neste projeto foi:

1. Clonagem do repositório remoto
2. Criação dos arquivos do projeto
3. Adição dos arquivos à área de stage
4. Criação de commits
5. Envio das alterações para o GitHub

Comandos principais utilizados:

```bash
git clone git@github.com:VanessaYuriAB/clone-example.git
git status
git add .
git commit -m "Mensagem de commit"
git push -u origin main
```

## 🔒 .gitignore

O projeto utiliza um arquivo `.gitignore` para evitar que arquivos desnecessários ou
sensíveis sejam versionados, como o `.DS_Store`.

Essa prática ajuda a manter o repositório limpo e independente do sistema operacional.

## 🎯 Objetivo do projeto

Projeto de caráter educacional, que faz parte do meu portfólio de estudos em
desenvolvimento web. Demonstra familiaridade com ferramentas essenciais do dia a dia de
qualquer desenvolvedor, especialmente no trabalho colaborativo com Git e GitHub.
