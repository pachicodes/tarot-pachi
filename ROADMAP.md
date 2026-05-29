# ROADMAP

## Resumo do Produto

Pachi é uma landing page de página única para **Pachi | Tarot Intuitivo & Direção**, pensada como uma entrada calma, elegante e acolhedora para pessoas que chegam pelo Instagram. O site vai apresentar a marca, explicar o processo de leitura, mostrar os serviços disponíveis e conduzir visitantes ao WhatsApp com um tom de confiança antes da conversão.

A experiência final deve ser editorial, ritualística, madura, mobile-first e leve.

## Stack Escolhida

O projeto usará **HTML5 e CSS3 puros**.

Essa é a direção correta porque a landing page é estática, não tem backend, banco de dados, autenticação nem necessidade de JavaScript ou framework. Manter o site sem dependências deixa a página mais rápida, simples de publicar e fácil de manter.

## Funcionalidades Principais

1. **Construir a estrutura estática da página**
   - Criar um `index.html` semântico com todas as seções necessárias da landing page.
   - Incluir comentários claros indicando onde substituir WhatsApp, Instagram, logomarca, submarca, foto pessoal e mensagens dos CTAs.

2. **Criar o sistema visual**
   - Criar um `styles.css` mobile-first usando variáveis CSS para cores, tipografia, espaçamento, bordas e sombras.
   - Usar os assets existentes em `img/TP-Logomarca.jpg` e `img/TP-Submarca.jpg` como referência visual.
   - Aplicar fundo off-white quente, texto em verde-oliva escuro, detalhes em dourado queimado, símbolos ritualísticos sutis e espaçamento editorial.

3. **Renderizar a landing page completa**
   - Implementar hero, manifesto, serviços, processo, rota de decisão, rituais, CTA final, nota ética, footer e botão flutuante de WhatsApp.
   - Garantir que a página seja responsiva de telas mobile até layouts desktop.

## Estrutura Esperada de Arquivos

```text
tarot-pachi/
├── index.html
├── styles.css
├── ROADMAP.md
├── plano-landing-page.md
├── README.md
└── img/
    ├── TP-Logomarca.jpg
    └── TP-Submarca.jpg
```

## Sequência de Desenvolvimento

### 1. Criar o documento HTML base

- Adicionar `index.html`.
- Definir o idioma da página como português.
- Adicionar metadados para layout responsivo, título da página, descrição e informações básicas de compartilhamento social.
- Vincular Google Fonts e `styles.css`.
- Adicionar comentários para substituir WhatsApp, Instagram, logomarca, submarca e futura foto pessoal.

### 2. Implementar todas as seções da landing page

- Adicionar a seção hero com a promessa principal e CTA primário para WhatsApp.
- Adicionar a seção sobre/manifesto com placeholder de imagem.
- Adicionar o grid de serviços com as quatro ofertas oficiais.
- Adicionar a seção de processo com quatro etapas numeradas.
- Adicionar a seção Rota de Decisão pós-Bússola.
- Adicionar a seção Rituais & Alquimia com tags de intenção.
- Adicionar CTA final, nota ética e footer.

### 3. Construir o sistema visual mobile-first

- Adicionar `styles.css`.
- Definir variáveis em `:root` para paleta da marca, fontes, espaçamento, raios e sombras.
- Estilizar a página primeiro para mobile.
- Adicionar breakpoints para desktop somente onde o layout precisar de mais largura, como na seção sobre e no grid de serviços.

### 4. Adicionar polimento de interação e acessibilidade

- Adicionar estados de hover, active e focus-visible para todos os links e CTAs.
- Adicionar o botão fixo de WhatsApp no canto inferior direito.
- Confirmar que todas as imagens tenham textos `alt` úteis.
- Confirmar que o contraste das cores seja legível e que a navegação por teclado permaneça visível.

### 5. Preparar para GitHub Pages

- Manter todos os caminhos relativos para que o site funcione no GitHub Pages.
- Confirmar que `index.html` esteja na raiz do repositório.
- Documentar que o GitHub Pages deve publicar a partir da raiz do repositório ou da branch/pasta configurada.

## Critérios de Aceite

- O projeto contém `index.html` e `styles.css` na raiz do repositório.
- O site usa apenas HTML5 e CSS3, sem React, Tailwind, Bootstrap, framework SPA, backend, banco de dados ou etapa de build.
- O layout é mobile-first e se adapta bem ao desktop.
- A direção visual combina com a logomarca e a submarca existentes: off-white quente, verde-oliva escuro, dourado queimado, geometria ritualística sutil e espaçamento editorial maduro.
- A página inclui todas as seções planejadas: hero, manifesto, serviços, processo, rota de decisão, rituais, CTA final, nota ética e footer.
- A seção de serviços inclui as quatro ofertas especificadas com nomes, descrições, detalhes de entrega, preços ou orientação de preço e CTAs.
- Os CTAs de WhatsApp usam comentários claros para substituição e incluem a mensagem pré-preenchida planejada.
- Um botão flutuante de WhatsApp permanece visível durante a rolagem.
- A página tem HTML semântico, contraste legível, estados de foco visíveis, textos alternativos úteis e labels acessíveis para links.
- A copy evita promessas de previsão do futuro, misticismo infantilizado, linguagem agressiva de venda e tom corporativo frio.

## Nota Sobre GitHub Pages

O GitHub Pages pode publicar este projeto diretamente porque o site é estático e o arquivo de entrada será `index.html` na raiz do repositório. Após a implementação, ative o GitHub Pages para o repositório e selecione a branch/pasta que contém `index.html`.
