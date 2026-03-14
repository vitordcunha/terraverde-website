# Plano de Implementação — Terra Verde & Co
**Plataforma:** Astro · **Prazo:** 4 semanas · **Objetivo:** Landing page para geração de leads via WhatsApp

---

## Visão geral

| Fase | Semana | Foco |
|------|--------|------|
| Fase 1 | Semana 1 | Base do projeto + preparação de conteúdo |
| Fase 2 | Semana 2 | Seções de alto impacto (hero + jardim vertical) |
| Fase 3 | Semana 3 | Seções de conversão e confiança |
| Fase 4 | Semana 4 | Polimento, SEO e deploy |
| Pós-lançamento | Após semana 4 | Melhorias contínuas |

---

## Fase 1 — Base do projeto + preparação de conteúdo
**Semana 1**

Antes de escrever uma linha de HTML, o conteúdo precisa estar pronto. Semana para montar o projeto Astro, definir a paleta e tipografia, e reunir todo o material (textos e fotos) para não travar nas fases seguintes.

### Tarefas

- [x] Criar projeto Astro + repositório Git
- [x] Configurar Tailwind CSS ou CSS vars globais
- [x] Definir paleta de cores e tipografia final
- [x] Criar componentes base (`Button`, `Section`, `Tag`)
- [x] Selecionar e otimizar fotos do portfólio
- [x] Escrever todos os textos do site (com base no design.json)
- [x] Definir domínio e plataforma de deploy (Netlify ou Vercel)
- [x] Configurar favicon, meta tags e Open Graph

### ✓ Entregável
Projeto rodando localmente com design system definido e conteúdo revisado pela Carmen.

---

## Fase 2 — Seções de alto impacto
**Semana 2**

As seções que o visitante vê primeiro e que mais influenciam a decisão de entrar em contato. São as mais trabalhosas visualmente — merecem atenção total nessa semana.

### Tarefas

- [x] Header com nav responsivo + botão WhatsApp
- [x] Hero section com foto full e stats animados
- [x] Barra de credibilidade (4 ícones + textos)
- [x] Seção Jardim Vertical — bloco principal
- [x] Cards de benefícios (purifica, valoriza o imóvel...)
- [x] Explicação visual da manta enraizadora (passos)
- [x] CTA flutuante / sticky no mobile
- [x] Testes de responsividade mobile e tablet

### ✓ Entregável
"Above the fold" completo e funcional — já parece um site profissional.

---

## Fase 3 — Seções de conversão e confiança
**Semana 3**

As seções que convencem quem ainda está em dúvida: portfólio real, o processo, a história da Carmen e os depoimentos. Também entra o grid de serviços secundários.

### Tarefas

- [x] Grid de serviços (8 cards com foto e hover)
- [x] Galeria de portfólio com filtro por categoria
- [x] Seção "Como funciona" (4 passos visuais)
- [x] Seção Sobre — foto e história da Carmen
- [x] Carrossel de depoimentos
- [x] CTA final com botão grande de WhatsApp
- [x] Footer completo com links e redes sociais
- [x] Lazy loading nas imagens do portfólio

### ✓ Entregável
Site 100% completo em conteúdo, pronto para revisão final da Carmen.

---

## Fase 4 — Polimento, SEO e deploy
**Semana 4**

Semana de refinamento e lançamento. Nada de features novas — foco total em performance, SEO local (Porto Alegre), ajustes de feedback e colocar o site no ar com domínio próprio.

### Tarefas

- [ ] Revisão geral de textos com a Carmen
- [x] Otimização de imagens (WebP + compressão)
- [x] SEO: `title`, `description`, hierarquia de headings
- [x] SEO local: schema.org `LocalBusiness`
- [ ] Teste no PageSpeed Insights (meta: 90+)
- [ ] Configurar domínio `terraverde.com.br`
- [x] Deploy na Vercel ou Netlify com HTTPS
- [x] Configurar Google Analytics + Search Console

### ✓ Entregável
Site no ar, rápido, indexável e com rastreamento ativo.

---

## Pós-lançamento — Melhorias futuras
**A partir da semana 5**

Itens que não bloqueiam o lançamento, mas que agregam valor ao longo do tempo. Podem entrar em sprints quinzenais depois do site no ar.

- [ ] Blog com dicas de paisagismo (SEO orgânico)
- [ ] Integração com feed do Instagram
- [ ] Página de cursos com calendário e inscrição
- [ ] Página de produtos do empório garden
- [ ] Pop-up de captura de lead (e-mail)
- [ ] Google Meu Negócio vinculado ao site

---

## Notas importantes

**Domínio:** o `terraverdeco.com` atual é genérico. Registrar `terraverde.com.br` transmite mais credibilidade ao público local e melhora o SEO regional de Porto Alegre.

**Conteúdo primeiro:** o maior risco do projeto é travar na implementação esperando foto ou texto da Carmen. Resolver isso na semana 1 garante que as semanas 2 e 3 fluam sem bloqueio.

**Portfólio por último:** é a seção mais dependente de assets externos (fotos otimizadas, categorização). Deixar para a semana 3 evita retrabalho antes da estrutura visual estar validada.