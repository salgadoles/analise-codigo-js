

# Análise de Códigos JavaScript - Proposta de Atividade

Este projeto consiste na análise de três códigos JavaScript fornecidos como parte de uma atividade proposta pelo docente Leonardo de Fundamentos Web. Cada código é acompanhado de uma página HTML que demonstra seu funcionamento.

## Código 1: Relógio Digital

Este código cria uma página HTML com um relógio digital que exibe a hora atual.

### Arquivos Incluídos:
- `main.css`: Estilos CSS para a página.
- `main.js`: Script JavaScript para atualizar o relógio.

### Funcionalidades:
- **HTML:**
  - Carrega os arquivos CSS e JavaScript necessários.
  - Define um elemento `<div>` com o ID "clock" para exibir a hora.

- **CSS:**
  - Estiliza o corpo da página e o relógio.
  - Define a fonte, cor de fundo, alinhamento e tamanho do relógio.

- **JavaScript:**
  - `startTime()`: Função para atualizar o relógio a cada 0.5 segundos.
  - `checkTime(i)`: Adiciona um zero à esquerda se o valor de `i` for menor que 10, garantindo dois dígitos para minutos e segundos.

## Código 2: Pop-up de Janela

Este código cria uma página HTML com um botão que abre uma nova janela pop-up.

### Funcionalidades:
- **HTML:**
  - Contém um botão que, quando clicado, abre uma nova janela pop-up.

- **CSS:**
  - Estiliza o corpo da página e o botão.

- **JavaScript:**
  - `NovaJanela(pagina, nome, w, h, scroll)`: Abre uma nova janela pop-up com as dimensões especificadas.
  - `openPopup()`: Chama `NovaJanela()` para abrir a página `pagina.html` em uma nova janela pop-up de 400x300 pixels com barras de rolagem.

## Código 3: Substituição de String

Este código cria uma página HTML que substitui parte de uma string e exibe o resultado.

### Funcionalidades:
- **HTML:**
  - Um elemento `<div>` é criado para exibir o resultado da operação.

- **CSS:**
  - Estiliza o corpo da página e o elemento de saída.

- **JavaScript:**
  - Uma string é definida e uma parte dela é substituída por outra usando o método `replace()`.
  - O resultado é inserido no elemento `<div>` para exibição.

---

Essa documentação descreve cada código e suas funcionalidades. Se precisar de mais informações ou alterações, sinta-se à vontade para entrar em contato! samuellimadoamaral.prof@gmail.com