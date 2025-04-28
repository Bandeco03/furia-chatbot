# Chatbot FURIA

Chat simples feito em **HTML**, **CSS** e **JavaScript** para responder mensagens rápidas sobre a FURIA.

## Funcionalidades

- Exibe mensagens do usuário e do bot no chat, com lateralidade (usuário à direita, bot à esquerda).
- Envio de mensagens via:
  - Tecla `Enter`.
  - Botão de envio `▶`.
- Botões rápidos para atalhos de mensagens:
  - **Próximo Jogo**
  - **Estatísticas**
  - **Dicas** (resposta aleatória entre dicas pré-definidas).
- Scroll automático para a última mensagem.

## Tecnologias Usadas

- **HTML5** (estrutura)
- **CSS3** (estilização)
- **JavaScript** (lógica do chat)

Tudo organizado em **um único arquivo** `.html`.

## Como Rodar

1. Clone o repositório ou baixe o arquivo `.html`.
2. Abra o arquivo em qualquer navegador moderno (Chrome, Firefox, Edge, etc).
3. Comece a usar o chat.

### Ou

1. Acesse o link: [furia-chatbot](https://bandeco03.github.io/furia-chatbot/)
2. Comece a usar o chat.

Nenhuma instalação ou dependência externa necessária.

## Estrutura do Projeto

```
index.html
```

- Dentro do `index.html`:
  - `<style>` contém todo o CSS.
  - `<script>` no final do `<body>` contém todo o JavaScript.
  - Layout responsivo até 400px de largura máxima do chat.

## Observações

- O bot responde apenas a palavras-chave específicas.
- Caso a entrada não seja reconhecida, uma mensagem padrão de erro é enviada.
