# Financas da Familia

App web para controle financeiro familiar — inspirado em planilha de gastos mensais.

## Funcionalidades

- **Salários**: Cadastre o salário de Nicolas, Ana e o Vale Alimentação. Informe empréstimos já descontados na fonte.
- **Fixo**: Contas recorrentes mensais (luz, escola, clube, etc.) com classificação PIX ou Cartão.
- **Obrigatório**: Gastos essenciais estimados (mercado, farmácia, gasolina).
- **Extras / Lazer**: Gastos variáveis, lazer e compras não essenciais.
- **Assinaturas Conjuntas**: Streaming e serviços recorrentes (Netflix, Spotify, etc.).
- **Parceladas**: Compras no crédito com data de término — destaca em amarelo as que encerram em breve.
- **Resumo automático**: Calcula quanto você precisa reservar para pagar o **cartão de crédito** e quanto vai via **PIX**.

## Como usar

1. Abra o arquivo index.html em qualquer navegador moderno.
2. Os dados são salvos automaticamente no localStorage do navegador.
3. Não é necessário servidor, instalação ou conexão com internet após o primeiro carregamento.

## Tecnologias

- React 18 (via CDN)
- Tailwind CSS (via CDN)
- Babel Standalone (transpiler JSX)

## Como publicar no GitHub Pages

1. Crie um repositório no GitHub (pode ser privado ou público).
2. Faça upload do arquivo index.html.
3. Vá em **Settings → Pages → Deploy from branch → main / root**.
4. Seu app estará disponível em https://seu-usuario.github.io/nome-do-repo/.

## Dados

Os dados são armazenados **somente no seu navegador** (localStorage). Nada é enviado para servidores.
Para "sincronizar" entre dispositivos, use o botão de export (futuro) ou abra sempre no mesmo navegador/dispositivo.
