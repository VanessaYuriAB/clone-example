# Clone Example — Git & GitHub Fundamentals

> Este é um projeto **educacional** guiado, com foco no entendimento do fluxo Git/GitHub.

O repositório faz parte do meu aprendizado prático em **Git e GitHub**, com foco nos
comandos essenciais e no fluxo de trabalho utilizado no desenvolvimento de software
moderno.

O projeto foi desenvolvido como parte do **Bootcamp de Desenvolvimento Web da TripleTen
Brasil**, durante a **Sprint 3 — Fluxo de Desenvolvimento**.

---

## 📌 Objetivo do projeto

Demonstrar, de forma simples e organizada, como:

- Clonar um repositório remoto
- Trabalhar localmente em um projeto versionado com Git
- Criar e versionar arquivos
- Enviar alterações para o GitHub
- Utilizar boas práticas iniciais de controle de versão

---

## 🧠 Conceitos

- Clonagem de repositórios com `git clone`
- Navegação no terminal (_bash_)
- Criação de arquivos via _linha de comando_
- Versionamento com Git (`add`, `commit`, `push`)
- Integração entre repositório local e remoto
- Uso do arquivo `.gitignore`
- Boas práticas iniciais de versionamento

---

## 🛠️ Tecnologias utilizadas

- Git
- GitHub
- Terminal / Bash
- HTML
- CSS

---

## 📂 Estrutura do projeto

```bash
clone-example/
├── .gitignore
├── index.html
├── README.md
└── style.css
```

---

## 🔄 Fluxo de trabalho aplicado

- Clonagem do repositório remoto
- Criação dos arquivos do projeto
- Adição dos arquivos à área de stage
- Criação de commits
- Envio das alterações para o GitHub

### Comandos utilizados

```Shell
git clone git@github.com:VanessaYuriAB/clone-example.git
cd clone-example
git status
git add .
git commit -m "Mensagem de commit"
git push -u origin main
```

## 🔒 .gitignore

O projeto utiliza um arquivo `.gitignore` para evitar que arquivos desnecessários ou
dependentes do sistema operacional sejam versionados.

Exemplo:

```Shell
.DS_Store
```

Essa prática ajuda a manter o repositório limpo, seguro e multiplataforma.

---

## ✅ Status do projeto

Concluído — projeto educacional finalizado conforme proposto na Sprint 3.

---

## 👩‍💻 Autora

Vanessa Yuri A. Brito

Projeto de estudo em desenvolvimento web, com foco em fundamentos de Git e GitHub.
