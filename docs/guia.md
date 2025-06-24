# 📘 Guia de Acessibilidade Digital

Este guia tem como objetivo fornecer orientações práticas para o desenvolvimento de interfaces acessíveis, com base nas recomendações da **WCAG 2.2**, da **norma brasileira NBR 17060:2022**, e nas experiências desenvolvidas ao longo da disciplina de IHC.

---

## 📌 1. Introdução

A acessibilidade digital garante que todas as pessoas, independentemente de suas capacidades físicas, sensoriais ou cognitivas, consigam utilizar sistemas, aplicativos e sites de maneira eficiente e com autonomia.

**Fontes principais:**
- [WCAG 2.2 – W3C](https://www.w3.org/WAI/standards-guidelines/wcag/)
- [NBR 17060:2022 – ABNT](https://www.abntcatalogo.com.br)
- Artigos e ferramentas abordadas na disciplina de IHC

---

## 🧑 2. Princípios de Acessibilidade (WCAG)

### ✅ Perceptível

- [ ] Fornecer texto alternativo para imagens (`alt`)
- [ ] Usar contraste adequado (mínimo 4.5:1 para textos normais)
- [ ] Evitar usar cor como única forma de transmitir informação

### ✅ Operável

- [ ] Tornar o site navegável por teclado
- [ ] Garantir foco visível em elementos interativos
- [ ] Evitar interações obrigatórias baseadas em arrastar (Dragging Movements – WCAG 2.2)

### ✅ Compreensível

- [ ] Utilizar linguagem simples e clara
- [ ] Organizar o conteúdo com cabeçalhos hierárquicos
- [ ] Fornecer mensagens de erro compreensíveis

### ✅ Robusto

- [ ] Utilizar HTML semântico (`<header>`, `<nav>`, `<main>`, etc.)
- [ ] Garantir compatibilidade com leitores de tela e tecnologias assistivas

---

## ⚖️ 3. Normas Brasileiras (NBR 17060)

- [ ] Utilizar corretamente os elementos de formulário
- [ ] Garantir navegabilidade apenas com teclado
- [ ] Identificar e destacar erros de preenchimento
- [ ] Assegurar compatibilidade com leitores de tela e ampliadores

---

## 🧪 4. Testes e Ferramentas de Validação

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

## 🧩 5. Boas Práticas Essenciais

- [ ] Garantir rótulos claros em botões e links
- [ ] Evitar conteúdo crítico em imagens sem alternativa textual
- [ ] Usar `aria-label`, `aria-labelledby`, `aria-describedby` quando necessário
- [ ] Garantir área mínima de 44x44px para elementos clicáveis
- [ ] Oferecer atalhos de navegação por teclado
- [ ] Disponibilizar uma página de acessibilidade no site
- [ ] Implementar autenticação acessível sem depender de memorização visual

---

## 🧱 6. Componentes a serem verificados

- [ ] Formulários
- [ ] Modais
- [ ] Navegação por teclado
- [ ] Responsividade
- [ ] Vídeos com legenda
- [ ] Imagens com `alt`
- [ ] Contraste de cores
- [ ] Áudio com transcrição

---

## 🧭 7. Checklist Final

- [ ] Todos os textos possuem contraste adequado  
- [ ] Imagens têm `alt` descritivo ou estão marcadas como decorativas  
- [ ] O site é navegável exclusivamente com teclado  
- [ ] O foco é visível em todos os elementos interativos  
- [ ] Formulários possuem rótulos e mensagens de erro claras  
- [ ] O site funciona corretamente com leitores de tela  
- [ ] Foram utilizados testes com Lighthouse, axe e WAVE

---

## 📎 8. Recursos Úteis

- [WCAG 2.2 (W3C)](https://www.w3.org/WAI/standards-guidelines/wcag/)
- [NBR 17060:2022 - Acessibilidade na Web (ABNT)](https://www.abntcatalogo.com.br)
- [Guia de Boas Práticas do Governo Federal (eMAG)](https://emag.governoeletronico.gov.br/)
- [Validador W3C](https://validator.w3.org/)

---

## 👨‍🏫 9. Sobre

Este guia foi elaborado pelos estudantes da disciplina de IHC – Turma V1 – com base nas atividades desenvolvidas ao longo do semestre, incrementado pelas principais diretrizes técnicas sobre acessibilidade digital.
