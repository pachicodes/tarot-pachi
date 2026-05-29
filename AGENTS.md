# AGENTS.md

## 1. Visão Geral do Projeto

Este projeto é uma landing page estática de página única para **Pachi | Tarot Intuitivo & Direção**.

Ele entrega uma experiência calma, elegante e mobile-first para pessoas que chegam pelo Instagram. A página apresenta a marca, explica o processo de leitura, mostra os serviços disponíveis, inclui uma nota ética e conduz visitantes ao WhatsApp com um tom de confiança antes da conversão.

O objetivo final é uma landing page leve, responsiva, editorial, ritualística e madura, pronta para publicação direta no GitHub Pages.

## 2. Stack e Restrições

A stack é:

- HTML5 puro
- CSS3 puro

O projeto deve permanecer estático e sem dependências.

Não usar:

- React
- Vue
- Angular
- Tailwind CSS
- Bootstrap
- Qualquer framework SPA
- Qualquer backend
- Qualquer banco de dados
- Autenticação
- Etapa de build, a menos que isso seja solicitado explicitamente depois

O site deve rodar diretamente no navegador a partir de `index.html`.

## 3. Estrutura de Arquivos

Estrutura final esperada:

```text
tarot-pachi/
├── index.html
├── styles.css
├── AGENTS.md
├── ROADMAP.md
├── plano-landing-page.md
├── README.md
└── img/
    ├── TP-Logomarca.jpg
    └── TP-Submarca.jpg
```

## 4. Comandos Principais

Não existem scripts de pacote, comandos de build nem comandos de instalação de dependências para este projeto.

Para rodar localmente, abra `index.html` diretamente no navegador.

Se for desejável usar um servidor estático local para pré-visualizar caminhos relativos, use qualquer servidor estático simples fora da configuração do projeto. Não adicione tooling a menos que isso seja solicitado explicitamente.

Build de produção:

- Não existe build de produção.
- Não é necessário build de produção.
- A saída de produção é a raiz do repositório contendo `index.html`, `styles.css` e os assets em `img/`.

## 5. Convenções de Código

Usar HTML semântico:

- `header`
- `main`
- `section`
- `footer`
- headings significativos
- links e botões descritivos
- textos `alt` úteis para imagens

Usar CSS mobile-first:

- Começar pelo layout da menor tela.
- Adicionar media queries somente quando o layout precisar de mais espaço.
- Usar propriedades customizadas CSS em `:root` para cores, tipografia, espaçamento, raios e sombras.
- Usar `clamp()` para tipografia responsiva.
- Usar `grid` e `flexbox` para layout.

Convenções de nomenclatura:

- Usar nomes de classes claros e em minúsculas.
- Preferir nomes legíveis inspirados em BEM quando ajudar, como `service-card`, `section-heading` e `floating-whatsapp`.
- Manter os nomes das classes ligados à estrutura da página e ao propósito da marca, não a detalhes visuais acidentais.

Organização:

- Manter as seções do HTML na mesma ordem definida em `ROADMAP.md`.
- Manter o CSS agrupado por propósito: variáveis, reset/base, utilitários de layout, seções, componentes e regras responsivas.
- Adicionar comentários concisos apenas onde eles ajudam edições futuras, especialmente para substituir WhatsApp, Instagram, logomarca, submarca, foto pessoal e mensagens dos CTAs.

Tratamento de fetch:

- Este projeto não busca dados externos.
- Não adicionar lógica de fetch a menos que o escopo do projeto mude explicitamente.

## 6. Processo de Deploy

O GitHub Pages pode publicar este projeto diretamente porque ele é um site estático.

Expectativa de deploy:

- Arquivo de entrada: `index.html`
- Pasta de saída: raiz do repositório
- Etapa de build: nenhuma
- Branch de deploy: a branch configurada no GitHub Pages, geralmente `main`
- Fonte de publicação: raiz do repositório, a menos que as configurações do repositório especifiquem outra fonte

Manter todos os caminhos de assets relativos para que o site funcione corretamente no GitHub Pages.

## 7. O Que Não Fazer

Não inventar novas escolhas de stack, frameworks, gerenciadores de pacote, bundlers ou ferramentas de build.

Não substituir a abordagem estática em HTML/CSS por um app JavaScript.

Não adicionar serviços, preços, copy, seções ou etapas de funil que não estejam descritos em `ROADMAP.md` ou `plano-landing-page.md`.

Não afastar a direção da marca de off-white quente, verde-oliva escuro, dourado queimado, geometria ritualística sutil e espaçamento editorial maduro.

Não deixar a página visualmente infantil, excessivamente mística, neon, corporativa ou agressiva no tom de venda.

Não fazer promessas de previsão do futuro nem substituir apoio terapêutico, médico, jurídico ou financeiro.

Não remover a nota ética, o botão flutuante de WhatsApp, o comportamento mobile-first, os fundamentos de acessibilidade ou os comentários claros de substituição.

Não assumir URLs reais de WhatsApp ou Instagram se elas ainda não foram fornecidas. Usar placeholders claramente marcados.
