# Site Integritii Igrejas

Este repositório contém a página oficial, responsiva e acessível do Integritii Igrejas.

## Arquivos principais

- `index.html`: estrutura e conteúdo integral do site.
- `styles.css`: identidade visual, layout, efeitos e responsividade.
- `assets/images`: logotipos, símbolo e imagens de fundo.
- `assets/fonts`: família Sora utilizada no projeto.
- `assets/downloads`: Kit Inicial em PDF.

## Como usar no Google Sites

O Google Sites não permite aplicar um arquivo CSS externo diretamente ao tema nativo. Para preservar fielmente este design, use o código como página incorporada.

1. Publique a pasta completa em um serviço de hospedagem estática, como GitHub Pages, Netlify, Cloudflare Pages ou Vercel.
2. Abra seu projeto no Google Sites.
3. No menu lateral, escolha **Inserir > Incorporar > Por URL**.
4. Cole o endereço público da página hospedada.
5. Clique em **Inserir** e amplie o bloco até ocupar toda a largura disponível.
6. Confira a página no computador e no celular antes de publicar o Google Sites.

Não envie somente o arquivo `index.html`: as pastas `assets`, as imagens, as fontes e o arquivo `styles.css` precisam permanecer juntos.

## Contato

Enquanto o formulário próprio do Integritii não é definido, o botão de manifestação de interesse abre uma mensagem destinada a `contato@valuii.com.br`.

## Publicação

O fluxo em `.github/workflows/pages.yml` publica automaticamente o conteúdo da raiz no GitHub Pages após cada atualização da branch `main`.

## Personalização rápida

As cores principais ficam no começo de `styles.css`:

```css
--navy-900: #042b63;
--turquoise-500: #01abc4;
```

O conteúdo pode ser alterado diretamente no `index.html`, preservando as marcações HTML ao redor de cada texto.

## Teste local

Para uma conferência simples, abra `index.html` no navegador. Para simular a hospedagem com maior fidelidade, execute um servidor local na pasta do projeto.

## Observação institucional

O site comunica corretamente a fase atual do Integritii: iniciativa voluntária, educativa, preventiva e orientativa. Ele não apresenta a marca como certificadora e registra expressamente que a participação não equivale a auditoria, certificação ou atestado de regularidade.
