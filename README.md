# 🍳 Recipe Page - Frontend Mentor Solution

Esta é uma solução para o desafio da página de receita do [Frontend Mentor](https://www.frontendmentor.io). O foco deste projeto foi a aplicação de HTML semântico, estilização avançada de tabelas e listas, além do uso de variáveis CSS para um código mais limpo e profissional.

---

## 🚀 Demonstração

Você pode visualizar o projeto online aqui:  
**[https://jailsonmorais-lang.github.io/recipe-page/](https://jailsonmorais-lang.github.io/recipe-page/)**

---

## 📋 Índice

- [Visão Geral](#-visão-geral)
  - [O desafio](#o-desafio)
  - [Screenshot](#screenshot)
- [Meu processo](#️-meu-processo)
  - [Tecnologias utilizadas](#tecnologias-utilizadas)
  - [O que eu aprendi](#o-que-eu-aprendi)
- [Como executar o projeto](#-como-executar-o-projeto)
- [Autor](#-autor)

---

## 🔍 Visão Geral

### O desafio

Neste projeto, os principais objetivos foram:

- Construir uma estrutura HTML semântica e acessível
- Criar um layout responsivo que se adapta a diferentes tamanhos de tela
- Personalizar marcadores de listas (`ul` e `ol`) com cores específicas do guia de estilos
- Estilizar uma tabela nutricional com bordas seletivas, removendo a linha divisória do último item

### Screenshot

![Screenshot do projeto](./screenshot.png)

> _Adicione uma captura de tela do seu projeto aqui_

---

## 🛠️ Meu processo

### Tecnologias utilizadas

- **HTML5**: Tags semânticas (`main`, `article`, `section`) e estrutura de tabelas
- **CSS3**: Variáveis globais (`:root`), Flexbox e Pseudo-elementos (`::marker`)
- **Google Fonts**: Fontes Young Serif e Outfit para uma tipografia fiel ao design
- **VS Code**: Uso de extensões e atalhos Emmet para produtividade

### O que eu aprendi

Neste projeto, superei desafios técnicos importantes sobre como o CSS interage com elementos específicos:

#### 1. Manipulação de Tabelas

Aprendi a utilizar a propriedade `border-collapse: collapse` para unificar as bordas das células e o seletor `:last-child` para remover a borda inferior da última linha, garantindo um visual limpo.

```css
/* Código que utilizei para remover a borda da última linha da tabela */
.tabela tr:last-child td {
    border-bottom: none;
}
```

#### 2. Estilização de Listas

Descobri como usar o pseudo-elemento `::marker` para colorir e destacar apenas as bolinhas e números das listas, mantendo a cor original do texto nos itens.

#### 3. Arquitetura CSS

Implementei o uso de variáveis no `:root`, o que facilitou a gestão de cores como o `Brown-800` e o `Rose-800` em todo o documento.

#### 4. Box Model

Refinei o uso de `padding` e `margin` para criar o espaçamento interno ideal, evitando que elementos como pontos de lista passassem das bordas do container.

---

## 👤 Autor

- **GitHub** - [Jailson Morais](https://github.com/jailsonmorais-lang)
- **Frontend Mentor** - [@jailsonmorais-lang](https://www.frontendmentor.io/profile/jailsonmorais-lang)

---

<div align="center">
  <sub>Desenvolvido com 💜 por Jailson Morais</sub>
</div>
