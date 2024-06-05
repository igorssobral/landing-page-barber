# Dev Barber

Este é o repositório do site da Dev Barber, uma barbearia moderna que combina estilo e atendimento de qualidade. Aqui você encontra informações sobre os serviços oferecidos, horários de funcionamento e a possibilidade de agendar um horário diretamente pelo WhatsApp.

## Índice

- [Funcionalidades](#funcionalidades)
- [Tecnologias Utilizadas](#tecnologias-utilizadas)
- [Como Executar o Projeto](#como-executar-o-projeto)
- [Estrutura do Código](#estrutura-do-código)

## Funcionalidades

- Página inicial com informações sobre a barbearia e horário de funcionamento.
- Seção "Sobre" com detalhes adicionais sobre a barbearia.
- Seção de serviços oferecidos com preços.
- Integração com Google Maps para localização.
- Links para redes sociais.
- Botão de agendamento via WhatsApp.

## Tecnologias Utilizadas

- HTML
- SASS (CSS pré-processado)
- JavaScript
- [AOS (Animate On Scroll)](https://michalsnik.github.io/aos/)
- [Font Awesome](https://fontawesome.com/)
- Google Maps Embed API

## Como Executar o Projeto

### Pré-requisitos

Certifique-se de ter um navegador web atualizado e o Node.js instalado.

### Passos

1. Clone este repositório:
    ```bash
    git clone https://github.com/igorssobral/landing-page-barber.git
    ```

2. Navegue até o diretório do projeto:
    ```bash
    cd landing-page-barber
    ```

3. Abra o arquivo `index.html` em um navegador:
    ```bash
    open index.html
    ```

## Estrutura do Código

### HTML

A estrutura do HTML define a página e inclui as seguintes seções principais:

- Header com navegação e logotipo.
- Seção principal (hero) com mensagem de boas-vindas e horário de funcionamento.
- Seção "Sobre" com descrição da barbearia.
- Seção de serviços com detalhes dos cortes e preços.
- Integração com Google Maps para mostrar a localização.
- Footer com links para redes sociais e logotipo.

### SASS

Os estilos são escritos em SASS e compilados para CSS. O arquivo principal de estilos é `style.scss`, que importa parciais para melhor organização:

- `_layout.scss`: Estilos para o layout.
- `_header.scss`: Estilos para o header.
- `_footer.scss`: Estilos para o footer.
- `_colors.scss`: Cores para o Layout.


### JavaScript

O arquivo `index.js` inicializa as animações do AOS.

---

