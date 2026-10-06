# 📰 TechNews Today — Portal de Tecnologia

> *As últimas novidades do mundo tech, agora com estilo.*

![Status](https://img.shields.io/badge/Status-Concluído-brightgreen?style=for-the-badge&logo=github)
![HTML5](https://img.shields.io/badge/HTML5-Estrutura-orange?style=for-the-badge&logo=html5)
![CSS3](https://img.shields.io/badge/CSS3-Estilização-1572B6?style=for-the-badge&logo=css3)

---

## Sobre o projeto

O **TechNews Today** é um portal de notícias sobre tecnologia desenvolvido como atividade prática de **Linguagem de Marcação**.

A proposta foi transformar uma estrutura HTML já construída em uma página moderna, utilizando apenas **HTML e CSS**, sem frameworks e sem JavaScript.

O resultado é um portal com visual escuro, elementos em degradê, efeito de vidro, cards modernos e layout responsivo.

---

## Objetivo

Praticar a utilização de recursos do **CSS3** para estilizar uma página HTML existente, trabalhando principalmente com:

- Glassmorphism
- Gradientes
- CSS Grid
- `position: sticky`
- Responsividade
- Transições e efeitos `hover`
- Organização visual de conteúdo

---

## Estrutura da página

O HTML utiliza elementos semânticos para organizar o conteúdo:

    <header>
     └── Logo + chamada principal

    <main>
     ├── <article>
     │    └── Notícia em destaque
     │
     ├── <section>
     │    └── Vídeo incorporado
     │
     └── <section>
          └── Newsletter

    <footer>
     └── Informações de contato

A página também utiliza recursos nativos do HTML, como `details` e `summary` para o "Leia mais", além de formulário com `input`, `select`, `checkbox` e `button`.

---

## Destaques do CSS

### ◈ Glassmorphism

O cabeçalho utiliza transparência, `backdrop-filter` e bordas sutis para criar o efeito de vidro.

    backdrop-filter: blur(10px);

### ◈ Texto em degradê

O nome **TechNews Today** recebe um gradiente aplicado diretamente ao texto.

    background: linear-gradient(90deg, #6366f1, #db2777);
    -webkit-background-clip: text;
    -webkit-text-fill-color: transparent;

### ◈ CSS Grid

O conteúdo principal utiliza **CSS Grid** para organizar os elementos e adaptar o layout em telas maiores.

    display: grid;
    grid-template-columns: 2fr 1fr;

### ◈ Interações

Os cards e o botão possuem efeitos `hover` com transformações suaves, deixando a interface mais dinâmica.

    transform: translateY(-5px);

### ◈ Responsividade

Uma `media query` adapta o layout para telas maiores, permitindo que o conteúdo seja reorganizado conforme o tamanho da tela.

    @media (min-width: 768px) {
        ...
    }

---

## Tecnologias

| Tecnologia | Utilização |
|---|---|
| HTML5 | Estrutura e conteúdo da página |
| CSS3 | Estilização e responsividade |
| CSS Grid | Organização do layout |
| Glassmorphism | Efeito visual do cabeçalho |
| Gradientes | Identidade visual |
| YouTube | Vídeo incorporado via `iframe` |

---

## Arquivos

    technews-today/
    │
    ├── desafio10a.html
    ├── 10a_desafio.css
    └── README.md

---

## Resultado

O projeto apresenta um portal de tecnologia com:

- Visual escuro e moderno
- Cabeçalho fixo
- Título com degradê
- Notícia em destaque
- Seção de vídeo
- Formulário de newsletter
- Efeitos de interação
- Layout responsivo

A proposta foi manter a estrutura HTML original e utilizar o CSS para transformar a apresentação visual da página.

---

## Atividade acadêmica

**Curso:** Técnico em Desenvolvimento de Sistemas  
**Disciplina:** Linguagem de Marcação — LIMA  
**Atividade:** Desafio 10A — TechNews Today  
**Tema:** Estilização de portal utilizando CSS3  
**Instituição:** SENAI

### Requisitos trabalhados

- [x] Glassmorphism
- [x] Gradiente no texto
- [x] CSS Grid
- [x] `position: sticky`
- [x] Media Query
- [x] Efeitos `hover`
- [x] HTML + CSS
- [x] Sem frameworks
- [x] Sem JavaScript

---

## Autoria

**Gabriel de Araujo Torres**

Projeto acadêmico desenvolvido para prática de **HTML5 e CSS3**, com foco em estrutura semântica, estilização moderna e responsividade.

---

<p align="center">
  <strong>TechNews Today</strong><br>
  HTML • CSS • LIMA • SENAI
</p>

<p align="center">
  Projeto acadêmico desenvolvido para prática de desenvolvimento web.
</p>

# 📰 TechNews Today — Portal de Tecnologia

> *"As últimas novidades do mundo tech, agora com estilo."* 𓆩 ⚡ 𓆪

![Status](https://img.shields.io/badge/Status-Concluído-brightgreen?style=for-the-badge&logo=github)
![Tecnologia](https://img.shields.io/badge/Tecnologia-HTML5%20%2B%20CSS3-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![Tema](https://img.shields.io/badge/Tema-TechNews-6366F1?style=for-the-badge&logo=css3&logoColor=white)

## ◈ Descrição e objetivo

O **TechNews Today** é um portal de notícias sobre tecnologia desenvolvido como atividade prática de **Linguagem de Marcação (LIMA)**.

A proposta foi transformar uma estrutura HTML já construída em uma página moderna, utilizando **CSS3** para criar um visual escuro, responsivo e inspirado em interfaces atuais.

◆ Estilizar uma página HTML existente utilizando CSS.

◆ Aplicar **Glassmorphism**, gradientes e efeitos visuais.

◆ Organizar o conteúdo utilizando **CSS Grid**.

◆ Criar uma interface responsiva para diferentes tamanhos de tela.

◆ Desenvolver o projeto sem frameworks e sem JavaScript.

## 📋 Detalhes da atividade

| Item | Descrição |
|---|---|
| Projeto | TechNews Today |
| Tema | Portal de Notícias de Tecnologia |
| Linguagens | HTML5 + CSS3 |
| Disciplina | LIMA |
| Foco | Estilização e responsividade |
| Frameworks | Nenhum |
| JavaScript | Não utilizado |

## ◇ Estrutura da página

O HTML utiliza elementos semânticos para organizar o portal:

◆ **`header`** — cabeçalho com logo e chamada principal.

◆ **`main`** — conteúdo principal da página.

◆ **`article`** — notícia em destaque sobre Inteligência Artificial.

◆ **`section`** — áreas de vídeo e newsletter.

◆ **`footer`** — informações de contato e direitos autorais.

Também foram utilizados elementos como `details`, `summary`, `iframe`, `form`, `input`, `select`, `checkbox` e `button`.

## 🎨 Destaques do CSS

### ◈ Glassmorphism

O cabeçalho utiliza transparência e `backdrop-filter` para criar o efeito de vidro fosco.

◆ `backdrop-filter: blur(10px);`

◆ Fundo com transparência e gradiente.

◆ `position: sticky` para manter o cabeçalho visível.

### ◈ Texto em degradê

O título **TechNews Today** recebe um gradiente utilizando `linear-gradient` e `background-clip`.

◆ Gradiente em tons de azul, roxo e rosa.

◆ Texto transparente para revelar o degradê.

### ◈ CSS Grid

O conteúdo principal utiliza **CSS Grid** para organizar os elementos da página.

◆ Layout dividido em colunas em telas maiores.

◆ Espaçamento e alinhamento controlados pelo Grid.

### ◈ Interações

Os cards e o botão possuem pequenas animações para deixar a interface mais dinâmica.

◆ Efeito `hover` nos cards.

◆ `transform: translateY()` para destacar a notícia.

◆ Efeito de escala no botão de inscrição.

### ◈ Responsividade

Uma `media query` adapta o layout para diferentes tamanhos de tela.

◆ Layout reorganizado a partir de **768px**.

◆ Estrutura preparada para dispositivos menores.

## 📰 Conteúdo do portal

A página apresenta uma notícia em destaque sobre **Inteligência Artificial**, acompanhada de uma seção de vídeo e uma área de inscrição para newsletter.

O formulário permite informar:

- E-mail
- Área de interesse
- Aceite dos termos

As opções de interesse incluem **Inteligência Artificial**, **Desenvolvimento Mobile** e **Tecnologias Web**.

## 🛠️ Tecnologias e ferramentas utilizadas

◆ **HTML5** — estrutura semântica e conteúdo da página.

◆ **CSS3** — estilização, efeitos, Grid e responsividade.

◆ **Visual Studio Code** — desenvolvimento e edição dos arquivos.

◆ **YouTube** — vídeo incorporado através de `iframe`.

◆ **GitHub** — versionamento e entrega do projeto.

## 📁 Arquivos do projeto

    technews-today/
    │
    ├── desafio10a.html
    ├── 10a_desafio.css
    └── README.md

## ◇ Conceitos praticados

◆ Estrutura semântica com HTML5.

◆ Formatação e organização de conteúdo.

◆ CSS Grid.

◆ Gradientes.

◆ Glassmorphism.

◆ `backdrop-filter`.

◆ `position: sticky`.

◆ Pseudo-classe `:hover`.

◆ Transições e transformações.

◆ Media Query.

◆ Design responsivo.

## 🖥️ Resultado

O resultado é um portal de tecnologia com uma identidade visual **escura, moderna e dinâmica**, combinando elementos de interface, conteúdo jornalístico e formulário de newsletter.

A atividade demonstra como uma estrutura HTML simples pode ganhar uma apresentação completamente diferente utilizando apenas **CSS3**, sem depender de frameworks ou JavaScript.

---

## 🎓 Atividade acadêmica

Esta atividade faz parte das aulas de **Linguagem de Marcação (LIMA)** do curso **Técnico em Desenvolvimento de Sistemas** do **SENAI**.

O desafio teve como foco a criação de uma estilização moderna para o portal **TechNews Today**, aplicando conceitos de CSS como **Glassmorphism, CSS Grid, gradientes, efeitos de interação e responsividade**.

A entrega foi realizada através de um **repositório público no GitHub**, contendo os arquivos HTML e CSS do projeto.

---

## 👾 Autoria

- **Aluno:** Gabriel de Araujo Torres (Nº 08)
- **Disciplina:** Linguagem de Marcação (LIMA) — `Desenvolvimento de Sistemas`
- **Atividade:** Desafio 10A — TechNews Today
- **Instituição:** SENAI A. Jacob Lafer

#### Projeto acadêmico desenvolvido para prática de desenvolvimento web.

---

<p align="center">
  <img src="https://media.tenor.com/2Xnh-2tG8pYAAAAi/scott-pilgrim-scott-pilgrim-takes-off.gif" width="275" height="auto" alt="Scott Pilgrim GIF" />
</p>

<div align="center">

[![GitHub](https://img.shields.io/badge/GitHub-GTawer-181717?style=for-the-badge&logo=github)](https://github.com/GTawer)

**⚡ HTML • CSS • LIMA • SENAI**

<sub>*Projeto acadêmico desenvolvido para prática de desenvolvimento web.*</sub>

</div>
