# DEV_PLAN

## Fase 1: Base Estática Inicial

**Status:** CONCLUÍDA

**Objetivo:** Criar a estrutura mínima da página estática, abrindo diretamente no navegador e carregando a folha de estilos corretamente.

**Entregáveis:**

- Criar `index.html`
- Criar `styles.css`
- Vincular `styles.css` a partir de `index.html`
- Adicionar metadados base para idioma, charset, viewport, título, descrição e compartilhamento social
- Vincular as fontes web selecionadas: `Arbutus Slab` e `Poppins`
- Adicionar comentários para substituir WhatsApp, Instagram, logomarca, submarca, foto pessoal e mensagens dos CTAs

**Critérios de Aceite Manuais:**

- Ao abrir `index.html` no navegador, uma página válida aparece sem erros no console.
- A aba do navegador mostra o título da página da Pachi.
- A página usa metadados de idioma em português.
- A folha de estilos carrega corretamente.
- A página contém uma estrutura placeholder visível para a landing page.
- O código-fonte inclui comentários claros para todos os links e assets reais futuros.

## Fase 2: Conteúdo da Landing Page

**Status:** CONCLUÍDA

**Objetivo:** Adicionar todas as seções obrigatórias da landing page em HTML semântico, seguindo a ordem e a copy definidas no roadmap e no documento de planejamento.

**Entregáveis:**

- Atualizar `index.html`
- Adicionar a seção hero
- Adicionar a seção sobre/manifesto com placeholder de foto
- Adicionar a seção de serviços com quatro cards
- Adicionar a seção de processo com quatro etapas numeradas
- Adicionar a seção Rota de Decisão pós-Bússola
- Adicionar a seção Rituais & Alquimia com tags de intenção
- Adicionar a seção de CTA final
- Adicionar a nota ética
- Adicionar o footer

**Critérios de Aceite Manuais:**

- O navegador exibe todas as seções planejadas na ordem correta.
- O hero inclui título principal, subtítulo, texto de apoio e CTA primário para WhatsApp.
- A seção de serviços inclui as quatro ofertas planejadas: Bússola Intuitiva, Bússola Profissional, Norte da Semana e Rituais & Alquimia.
- Cada card de serviço inclui descrição, detalhes de entrega, preço ou orientação de preço e CTA planejados.
- A nota ética está presente e visível.
- A copy não promete previsão do futuro nem substitui apoio terapêutico, médico, jurídico ou financeiro.

## Fase 3: Sistema Visual da Marca

**Status:** TODO

**Objetivo:** Aplicar a direção visual mobile-first usando a logomarca e a submarca existentes como referência da marca.

**Entregáveis:**

- Atualizar `styles.css`
- Definir variáveis em `:root` para cores, fontes, espaçamento, raio de borda e sombras
- Estilizar a tipografia base com `Arbutus Slab` nos títulos e `Poppins` nos textos corridos, botões e interface
- Aplicar fundo off-white quente, texto em verde-oliva escuro e detalhes em dourado queimado
- Adicionar espaçamento mobile-first, ritmo de seções, cards, botões, tags e divisórias sutis
- Usar `img/TP-Logomarca.jpg` e `img/TP-Submarca.jpg` nos lugares apropriados

**Critérios de Aceite Manuais:**

- A página combina visualmente com a paleta da logomarca e da submarca existentes.
- O design parece maduro, editorial, ritualístico e minimalista, sem ficar infantil ou excessivamente místico.
- A logomarca e a submarca aparecem em tamanhos contidos e não dominam o layout mobile.
- Os cards têm bordas sutis, cantos arredondados e sombras suaves.
- Os CTAs são visualmente claros sem parecer agressivos.
- A tipografia escala bem em telas pequenas.

## Fase 4: Layout Responsivo

**Status:** TODO

**Objetivo:** Garantir que a página seja mobile-first e se adapte bem a larguras de tablet e desktop.

**Entregáveis:**

- Atualizar `styles.css`
- Adicionar breakpoints responsivos somente onde necessário
- Empilhar todo o conteúdo corretamente no mobile
- Transformar a seção sobre em duas colunas em telas maiores
- Transformar a seção de serviços de uma coluna no mobile para um grid com múltiplas colunas em telas maiores
- Manter a seção de processo legível em diferentes tamanhos de tela

**Critérios de Aceite Manuais:**

- Em uma viewport mobile estreita, a página é legível sem rolagem horizontal.
- No mobile, as seções empilham naturalmente e os CTAs são fáceis de tocar.
- No desktop, a seção sobre usa duas colunas.
- No desktop, a seção de serviços aparece como grid com múltiplas colunas.
- O espaçamento permanece equilibrado do mobile ao desktop.
- Imagens e placeholders não esticam nem distorcem.

## Fase 5: Interação e Acessibilidade

**Status:** TODO

**Objetivo:** Adicionar os estados de interação obrigatórios, o botão flutuante de WhatsApp e os fundamentos de acessibilidade.

**Entregáveis:**

- Atualizar `index.html`
- Atualizar `styles.css`
- Adicionar botão fixo de WhatsApp no canto inferior direito
- Adicionar estados de hover, active e focus-visible para todos os links e CTAs
- Adicionar textos `alt` descritivos para logomarca, submarca e placeholders de imagem
- Adicionar labels acessíveis onde necessário
- Confirmar contraste legível para textos, botões e links

**Critérios de Aceite Manuais:**

- O botão flutuante de WhatsApp permanece visível durante a rolagem.
- Todos os CTAs e links do footer têm estados visíveis de hover, active e foco por teclado.
- A navegação por teclado alcança todos os links interativos.
- Os estilos de foco são claramente visíveis.
- As imagens têm textos alternativos úteis.
- Os textos permanecem legíveis sobre as cores de fundo.

## Fase 6: Pronto para GitHub Pages

**Status:** TODO

**Objetivo:** Preparar o site estático finalizado para publicação direta no GitHub Pages sem etapa de build.

**Entregáveis:**

- Verificar que `index.html` está na raiz do repositório
- Verificar que `styles.css` está na raiz do repositório
- Verificar que os caminhos das imagens apontam para a pasta `img/` existente usando caminhos relativos
- Atualizar `README.md` com notas de pré-visualização local e deploy no GitHub Pages, se necessário
- Manter o projeto sem dependências, sem gerenciador de pacotes e sem configuração de build

**Critérios de Aceite Manuais:**

- O site funciona ao abrir `index.html` diretamente no navegador.
- Todas as imagens carregam por caminhos relativos.
- Nenhum comando de build é necessário.
- Nenhum comando de instalação de pacotes é necessário.
- A raiz do repositório contém os arquivos prontos para produção.
- O GitHub Pages pode ser configurado para publicar a partir da raiz do repositório na branch selecionada, geralmente `main`.
