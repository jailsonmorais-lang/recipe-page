🍳 Recipe Page - Frontend Mentor Solution
Esta é uma solução para o desafio da página de receita do Frontend Mentor. O foco deste projeto foi a aplicação de HTML semântico, estilização avançada de tabelas e listas, além do uso de variáveis CSS para um código mais limpo e profissional.

🚀 Demonstração
Você pode visualizar o projeto online aqui:

https://jailsonmorais-lang.github.io/recipe-page/

📋 Índice
Visão Geral

O desafio

Screenshot

Meu processo

Tecnologias utilizadas

O que eu aprendi

Como executar o projeto

Autor

🔍 Visão Geral
O desafio
Neste projeto, os principais objetivos foram:

Construir uma estrutura HTML semântica e acessível.

Criar um layout responsivo que se adapta a diferentes tamanhos de tela.

Personalizar marcadores de listas (ul e ol) com cores específicas do guia de estilos.

Estilizar uma tabela nutricional com bordas seletivas, removendo a linha divisória do último item.

Screenshot
🛠️ Meu processo
Tecnologias utilizadas
HTML5: Tags semânticas (main, article, section) e estrutura de tabelas.

CSS3: Variáveis globais (:root), Flexbox e Pseudo-elementos (::marker).

Google Fonts: Fontes Young Serif e Outfit para uma tipografia fiel ao design.

VS Code: Uso de extensões e atalhos Emmet para produtividade.

O que eu aprendi
Neste projeto, superei desafios técnicos importantes sobre como o CSS interage com elementos específicos:

Manipulação de Tabelas: Aprendi a utilizar a propriedade border-collapse: collapse para unificar as bordas das células e o seletor :last-child para remover a borda inferior da última linha, garantindo um visual limpo.

Estilização de Listas: Descobri como usar o pseudo-elemento ::marker para colorir e destacar apenas as bolinhas e números das listas, mantendo a cor original do texto nos itens.

Arquitetura CSS: Implementei o uso de variáveis no :root, o que facilitou a gestão de cores como o Brown-800 e o Rose-800 em todo o documento.

Box Model: Refinei o uso de padding e margin para criar o espaçamento interno ideal, evitando que elementos como pontos de lista passassem das bordas do container.

CSS
/* Código que utilizei para remover a borda da última linha da tabela */
.tabela tr:last-child td {
    border-bottom: none;
}
🚀 Como executar o projeto
Clone o repositório:

Bash
git clone https://github.com/jailsonmorais-lang/recipe-page.git
Acesse a pasta do projeto.

Abra o arquivo index.html em seu navegador.

👤 Autor
GitHub - Jailson Morais

Frontend Mentor - @jailsonmorais-lang
