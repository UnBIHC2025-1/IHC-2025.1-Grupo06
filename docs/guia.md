#  Guia de Acessibilidade Digital

Este guia tem como objetivo fornecer orientações práticas para o desenvolvimento de interfaces acessíveis, com base nas recomendações da **WCAG 2.2**, da **norma brasileira NBR 17060:2022**, e nas experiências desenvolvidas ao longo da disciplina de IHC.

---

##  1. Introdução

A acessibilidade digital garante que todas as pessoas, independentemente de suas capacidades físicas, sensoriais ou cognitivas, consigam utilizar sistemas, aplicativos e sites de maneira eficiente e com autonomia.

**Fontes principais:**
- [WCAG 2.2 – W3C](https://www.w3.org/WAI/standards-guidelines/wcag/)
- [NBR 17060:2022 – ABNT](https://www.abntcatalogo.com.br)
- Artigos e ferramentas abordadas na disciplina de IHC

---

##  2. Princípios de Acessibilidade (WCAG)

###  Perceptível

- [ ] Fornecer texto alternativo para imagens (`alt`)
- [ ] Usar contraste adequado (mínimo 4.5:1 para textos normais)
- [ ] Evitar usar cor como única forma de transmitir informação

###  Operável

- [ ] Tornar o site navegável por teclado
- [ ] Garantir foco visível em elementos interativos
- [ ] Evitar interações obrigatórias baseadas em arrastar (Dragging Movements – WCAG 2.2)

###  Compreensível

- [ ] Utilizar linguagem simples e clara
- [ ] Organizar o conteúdo com cabeçalhos hierárquicos
- [ ] Fornecer mensagens de erro compreensíveis

###  Robusto

- [ ] Utilizar HTML semântico (`<header>`, `<nav>`, `<main>`, etc.)
- [ ] Garantir compatibilidade com leitores de tela e tecnologias assistivas

---

##  3. Normas Brasileiras (NBR 17060)

- [ ] Utilizar corretamente os elementos de formulário
- [ ] Garantir navegabilidade apenas com teclado
- [ ] Identificar e destacar erros de preenchimento
- [ ] Assegurar compatibilidade com leitores de tela e ampliadores

---

##  4. Testes e Ferramentas de Validação

| Ferramenta                   | Finalidade                                         |
|-----------------------------|----------------------------------------------------|
| **Google Lighthouse**       | Auditoria automática no navegador Chrome           |
| **axe DevTools**            | Extensão para inspeção de acessibilidade           |
| **WAVE WebAIM**             | Análise visual de problemas                        |
| **NVDA / JAWS / VoiceOver** | Leitores de tela                                   |
| **Accessibility Insights**  | Testes detalhados com foco em WCAG                 |
| **Keyboard-only Testing**   | Navegação com TAB, ENTER e SHIFT+TAB               |
| **Zoom 200% Test**          | Verificação de usabilidade com zoom ampliado       |

---

##  5. Boas Práticas Essenciais

- [ ] Garantir rótulos claros em botões e links
- [ ] Evitar conteúdo crítico em imagens sem alternativa textual
- [ ] Usar `aria-label`, `aria-labelledby`, `aria-describedby` quando necessário
- [ ] Garantir área mínima de 44x44px para elementos clicáveis
- [ ] Oferecer atalhos de navegação por teclado
- [ ] Disponibilizar uma página de acessibilidade no site
- [ ] Implementar autenticação acessível sem depender de memorização visual

---

##  6. Componentes a serem verificados

- [ ] Formulários
- [ ] Modais
- [ ] Navegação por teclado
- [ ] Responsividade
- [ ] Vídeos com legenda
- [ ] Imagens com `alt`
- [ ] Contraste de cores
- [ ] Áudio com transcrição

---

##  7. Checklist Final

- [ ] Todos os textos possuem contraste adequado  
- [ ] Imagens têm `alt` descritivo ou estão marcadas como decorativas  
- [ ] O site é navegável exclusivamente com teclado  
- [ ] O foco é visível em todos os elementos interativos  
- [ ] Formulários possuem rótulos e mensagens de erro claras  
- [ ] O site funciona corretamente com leitores de tela  
- [ ] Foram utilizados testes com Lighthouse, axe e WAVE

---

##  8. Recursos Úteis

- [WCAG 2.2 (W3C)](https://www.w3.org/WAI/standards-guidelines/wcag/)
- [NBR 17060:2022 - Acessibilidade na Web (ABNT)](https://www.abntcatalogo.com.br)
- [Guia de Boas Práticas do Governo Federal (eMAG)](https://emag.governoeletronico.gov.br/)
- [Validador W3C](https://validator.w3.org/)

---

##  9. Sobre

Este guia foi elaborado pelos estudantes da disciplina de IHC – Turma V1 – com base nas atividades desenvolvidas ao longo do semestre, incrementado pelas principais diretrizes técnicas sobre acessibilidade digital.

## 10. Checklist NBR e WCAG (WCAG 2.2 & NBR 17060)

Checklist para verificar a conformidade do seu projeto com as **diretrizes internacionais WCAG 2.2** e a **norma brasileira NBR 17060:2022**.

---

###  a. Meta e Estrutura Geral
- [ ] Definir a linguagem principal da página (`<html lang="pt-BR">`).  
- [ ] Incluir `<title>` descritivo e único em cada página.  
- [ ] Fornecer link “Pular para o conteúdo” no topo de cada página.  
- [ ] Disponibilizar mapa do site ou índice de conteúdos navegável.  
- [ ] Garantir URLs semânticas e amigáveis (p.ex. `/produtos/acessorios`).  

---

###  b. Texto Alternativo & Mídia Estática
- [ ] Todas as imagens informativas têm `alt` descritivo (WCAG 1.1.1).  
- [ ] Imagens decorativas usam `role="presentation"` ou `aria-hidden="true"`.  
- [ ] Gráficos e infográficos têm descrição longa (`<figure><figcaption>`).  
- [ ] Captchas usam métodos acessíveis (áudio, lógica simples).  

---

###  c. Conteúdo de Tempo Variável (Áudio/Vídeo)
- [ ] Vídeos apresentam legendas sincronizadas (WCAG 1.2.2).  
- [ ] Áudiodescrição ou descrição textual para vídeos (WCAG 1.2.5).  
- [ ] Transcrição completa de áudios e podcasts (NBR).  
- [ ] Controle de reprodução: pausar, parar, ocultar (WCAG 2.2.2).  

---

###  d. Semântica e Adaptabilidade
- [ ] Utilizar elementos semânticos: `<header>`, `<nav>`, `<main>`, `<section>`, `<article>`, `<footer>`.  
- [ ] Cabeçalhos em ordem hierárquica (`<h1>` → `<h2>` → …).  
- [ ] Listas marcadas com `<ul>`, `<ol>`, `<li>`.  
- [ ] Tabelas de dados estruturadas com `<table>`, `<thead>`, `<tbody>`, `<caption>`, `<th>`.  
- [ ] Uso correto de landmarks ARIA (`role="banner"`, `"navigation"`, `"main"`, etc.).  

---

###  e. Distinguibilidade e Contraste
- [ ] Contraste mínimo 4.5:1 para texto normal (WCAG 1.4.3).  
- [ ] Contraste mínimo 3:1 para texto grande (WCAG 1.4.6).  
- [ ] Não usar cor como único meio de transmitir informação (WCAG 1.4.1).  
- [ ] Garantir espaçamento de linha ≥ 1.5 e parágrafos visíveis (NBR).  
- [ ] Área mínima de clique/toque de 44 × 44 CSS px (WCAG 2.2.8).  

---

###  f. Operabilidade por Teclado
- [ ] Navegação completa pelo teclado (WCAG 2.1.1).  
- [ ] Foco visível em todos os controles (WCAG 2.4.7).  
- [ ] Ordem de foco lógica e intuitiva (WCAG 2.4.3).  
- [ ] Atalhos de teclado (`accesskey`) consistentes (NBR).  
- [ ] Modais e diálogos têm foco aprisionado e podem ser fechados com ESC (WCAG 2.4.1).  

---

###  g. Tempo e Dinâmica
- [ ] Usuário pode ampliar tempo de operações automáticas (WCAG 2.2.1).  
- [ ] Evitar conteúdo piscante/flash que cause risco de convulsão (WCAG 2.3.1).  
- [ ] Detectar preferência do usuário por redução de movimento (`prefers-reduced-motion`).  

---

###  h. Navegação e Consistência
- [ ] Oferecer múltiplas formas de navegação (barra, busca, breadcrumbs) (WCAG 2.4.5).  
- [ ] Breadcrumbs que reflitam a posição atual (NBR).  
- [ ] Indicar links que abrem em nova janela (`aria-label="abre em nova guia"`).  
- [ ] Texto de link significativo — sem “clique aqui” (WCAG 2.4.4).  

---

###  i. Legibilidade e Compreensão
- [ ] Linguagem principal clara e simples (WCAG 3.1.1).  
- [ ] Vocabulário consistente em todo o site (NBR).  
- [ ] Fornecer glossário para termos técnicos.  
- [ ] Resumos e destaques em seções extensas.  

---

###  j. Formulários e Entrada de Dados
- [ ] Cada campo tem `<label>` associado (WCAG 1.3.1).  
- [ ] Agrupamento lógico de campos em `<fieldset>`/`<legend>` (NBR).  
- [ ] Mensagens de erro claras e sugestões de correção (WCAG 3.3.3).  
- [ ] Assistência contextual via `aria-describedby` ou dicas nativas.  
- [ ] Campos obrigatórios e opcionais claramente identificados.  

---

###  k. Feedback e Atualizações
- [ ] Áreas dinâmicas sinalizam mudanças via `aria-live` (WCAG 4.1.3).  
- [ ] Barra de progresso ou indicador de carregamento para processos longos.  
- [ ] Controle manual para atualizar conteúdo dinâmico.  

---

###  l. Dispositivos Móveis & Responsividade
- [ ] Layout reflow sem scroll horizontal em zoom 200% (WCAG 1.4.10).  
- [ ] Adaptação simples a orientação retrato/paisagem (WCAG 1.3.4).  
- [ ] Gestos alternativos a swipe/drag, se não suportados (WCAG 2.5.7).  
- [ ] Elementos de toque com área mínima de 44 × 44 CSS px.  

---

###  m. Autenticação e Segurança
- [ ] Autofill compatível com navegadores e leitores de tela.  
- [ ] Evitar quebra-cabeças visuais para login (WCAG 3.3.7).  
- [ ] Autenticação de múltiplos fatores acessível (NBR).  

---

###  n. Documentos e PDF
- [ ] PDFs possuem tags de acessibilidade e ordem de leitura lógica.  
- [ ] Metadados definidos (`Title`, `Language`, `Subject`).  
- [ ] Elementos marcados (títulos, listas, tabelas, formulários).  

---

###  o. Suporte e Contato
- [ ] Informação de contato (e-mail, telefone) em local de fácil acesso.  
- [ ] Formulário de feedback acessível para reportar barreiras.  
- [ ] FAQs navegáveis por tópico e com links internos.  

---

###  p. Recursos Visuais e Design
- [ ] Evitar animações e transições bruscas — oferecer modo reduzido.  
- [ ] Contraste de ícones e elementos gráficos adequados.  
- [ ] Tipografia legível: fontes sans-serif, tamanho mínimo 16 px.  
- [ ] Ícones com texto alternativo (`aria-label`).  

---

###  q. Recursos Adicionais & Referências
- [ ] Incluir seção “Recursos Úteis” com links às diretrizes oficiais.  
- [ ] Atualizar documentação sempre que a norma ou WCAG forem revisadas.  
- [ ] Incluir licença e escopo de cobertura no README.

---
