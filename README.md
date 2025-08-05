# Jogo da Memória - Desafio Software Livre

Este é um simples e interativo Jogo da Memória criado como uma ferramenta de gamificação para a "Oficina de Software Livre", realizada no meu local de trabalho. O objetivo do jogo é ajudar os participantes a fixar conceitos e associações sobre softwares livres e seus propósitos de uma maneira divertida.

## ✨ Funcionalidades

- **Interface Limpa e Moderna:** Construído com Tailwind CSS para um visual agradável.
- **Responsivo:** Funciona bem em desktops, tablets e smartphones.
- **Contador de Tentativas:** Acompanha o número de jogadas do usuário.
- **Animações Fluidas:** Efeitos de virar as cartas para uma experiência mais dinâmica.
- **Feedback Imediato:** As cartas corretas ficam verdes e as incorretas viram de volta.
- **Tela de Vitória:** Um modal parabeniza o jogador ao completar o desafio.
- **Fácil de Reiniciar:** Um botão permite começar um novo jogo a qualquer momento.

## 🚀 Como Usar

Este projeto consiste em um único arquivo `index.html`. Para executá-lo, basta:

1.  Fazer o download do arquivo.
2.  Abrir o arquivo `index.html` em qualquer navegador de internet moderno (como Chrome, Firefox, Edge, etc.).

Não é necessário nenhum servidor ou processo de compilação.

## 🔧 Personalização

É muito fácil adaptar o jogo para outros temas ou adicionar mais pares de conceitos.

1.  Abra o arquivo `index.html` em um editor de texto.
2.  Navegue até a tag `<script>` no final do arquivo.
3.  Encontre a constante `cardData`:

    ```javascript
    const cardData = [
        { id: 1, content: 'LibreOffice', pairId: 1 }, { id: 2, content: 'Pacote de Escritório', pairId: 1 },
        { id: 3, content: 'GIMP', pairId: 2 }, { id: 4, content: 'Editor de Imagens', pairId: 2 },
        // ...outros pares
    ];
    ```

4.  Para alterar o conteúdo, simplesmente edite os valores de `content`.
5.  Para adicionar um novo par, adicione dois novos objetos ao array, garantindo que eles compartilhem o mesmo `pairId` e tenham `id`s únicos. Por exemplo:

    ```javascript
     { id: 13, content: 'Audacity', pairId: 7 }, { id: 14, content: 'Editor de Áudio', pairId: 7 },
    ```

## 🛠️ Tecnologias Utilizadas

- **HTML5**
- **CSS3**
- **JavaScript (ES6)**
- **[Tailwind CSS](https://tailwindcss.com/)** - Para estilização rápida da interface.

