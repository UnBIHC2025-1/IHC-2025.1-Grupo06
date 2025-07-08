## Ferramentas de Acessibilidade (Atualizado)

Para auxiliar e facilitar o desenvolvimento de soluções acessíveis, foram elencadas abaixo ferramentas — inclusive algumas voltadas à conformidade com a NBR 17060:2022 — e instruções básicas de uso.

### Testes Automatizados
- **Google Accessibility Test Framework for Android**  
  - Serve para: executar testes de acessibilidade em aplicativos Android durante a instrumentação.  
  - Uso: instale via Gradle/Maven e invoque nos seus testes de instrumentação Android para gerar relatórios de violações.  
  - Link: [github.com/google/Accessibility-Test-Framework-for-Android](https://github.com/google/Accessibility-Test-Framework-for-Android)

- **Pa11y**  
  - Serve para: rodar auditorias de páginas web via linha de comando.  
  - Uso: `npm install -g pa11y` e rode `pa11y https://seudominio.com` para obter relatório JSON ou HTML.  
  - Link: [github.com/pa11y/pa11y](https://github.com/pa11y/pa11y)

- **Tenon.io**  
  - Serve para: analisar acessibilidade via API e receber feedback automatizado em JSON.  
  - Uso: cadastre-se na API, envie requisições POST com URL ou HTML e receba feedback detalhado em JSON.  
  - Link: [tenon.io](https://tenon.io)

- **AChecker**  
  - Serve para: validar conformidade com WCAG e NBR 17060 diretamente no navegador.  
  - Uso: acesse [achecker.ca](https://achecker.ca), cole sua URL, selecione “WCAG 2.2 + ABNT NBR 17060” e clique em “Check it”.  
  - Link: [achecker.ca](https://achecker.ca)

### Extensões de Navegador
- **axe DevTools**  
  - Serve para: inspecionar automaticamente violações de acessibilidade no front-end.  
  - Uso: instale a extensão no Chrome/Firefox, abra o painel “axe” no DevTools e clique em “Scan all pages”.  
  - Link: [github.com/dequelabs/axe-core](https://github.com/dequelabs/axe-core)

- **Accessibility Insights for Web (Microsoft)**  
  - Serve para: fazer avaliações rápidas (“FastPass”) e completas (“Assessment”) de acessibilidade.  
  - Uso: instale a extensão, abra a guia “Accessibility Insights” no DevTools e execute “FastPass” ou “Assessment”.  
  - Link: [accessibilityinsights.io](https://accessibilityinsights.io)

- **WAVE – Web Accessibility Evaluation Tool**  
  - Serve para: sobrepor ícones visuais que indicam erros e alertas de acessibilidade na página.  
  - Uso: instale o bookmarklet ou extensão, clique para sobrepor marcadores visuais na página.  
  - Link: [wave.webaim.org](https://wave.webaim.org)

- **Siteimprove Accessibility Checker**  
  - Serve para: identificar problemas de contraste, ARIA e semântica diretamente no navegador.  
  - Uso: extensão gratuita para Chrome; executa análise inline de problemas de contraste, ARIA e semântica.  
  - Link: [siteimprove.com/accessibility](https://siteimprove.com/accessibility)

### Linhas de Comando / CI
- **Lighthouse CI**  
  - Serve para: integrar auditorias de performance e acessibilidade em pipelines de integração contínua.  
  - Uso: instale `npm install -g @lhci/cli`, configure `lhci autorun` no seu pipeline para gerar relatórios de acessibilidade.  
  - Link: [github.com/GoogleChrome/lighthouse-ci](https://github.com/GoogleChrome/lighthouse-ci)

### Análise de Contraste
- **Color Contrast Analyzer (TPGi)**  
  - Serve para: medir a relação de contraste entre cores de primeiro plano e fundo no desktop.  
  - Uso: baixe o app desktop, aponte as cores de primeiro plano e fundo para obter relação de contraste e WCAG score.  
  - Link: [tpgi.com/color-contrast-checker](https://www.tpgi.com/color-contrast-checker)

- **WebAIM Contrast Checker**  
  - Serve para: testar rapidamente níveis de contraste conforme WCAG e NBR 17060.  
  - Uso: cole valores HEX das cores em fg/bg e confira se atendem a WCAG e NBR 17060 (3:1 para texto grande; 4.5:1 para texto normal).  
  - Link: [webaim.org/resources/contrastchecker](https://webaim.org/resources/contrastchecker/)

### Bookmarklet
- **tota11y**  
  - Serve para: injetar uma barra de ferramentas de acessibilidade em qualquer site via bookmarklet.  
  - Uso: adicione o bookmarklet do projeto, abra-o em qualquer página para sobrepor painéis de verificação de acessibilidade.  
  - Link: [khan.github.io/tota11y](https://khan.github.io/tota11y/)

### Ferramentas da ABNT / Governo Federal
- **eMAG Checker**  
  - Serve para: validar conformidade com o eMAG (modelo de acessibilidade do governo) e NBR 17060.  
  - Uso: acesse [emag.governoeletronico.gov.br](https://emag.governoeletronico.gov.br/), cole a URL do seu site, selecione “eMAG + NBR 17060” e execute a validação.  
  - Link: [emag.governoeletronico.gov.br](https://emag.governoeletronico.gov.br)

- **Validador ABNT (via Normas.com.br)**  
  - Serve para: consultar e revisar requisitos da norma NBR 17060:2022.  
  - Uso: consulte a norma NBR 17060:2022 em [abntcatalogo.com.br](https://www.abntcatalogo.com.br/norma/nbr-17060-2022) e siga os requisitos; para automação, combine com AChecker (WCAG+ABNT).  
  - Link: [abntcatalogo.com.br/norma/nbr-17060-2022](https://www.abntcatalogo.com.br/norma/nbr-17060-2022)

### Leitores de Tela (Contexto de Teste)
- **NVDA (Windows)**  
  - Serve para: testar experiência de usuário cego em navegadores Windows.  
  - Uso: baixe em [nvaccess.org](https://nvaccess.org), instale e use TAB, setas e comandos NVDA+ para navegar e testar suas páginas.  
- **JAWS (Windows)**  
  - Serve para: avaliação de acessibilidade avançada em Windows com leitura de telas comercial.  
  - Uso: adquira licença em [freedomscientific.com](https://www.freedomscientific.com), instale e teste com leitura de cabeçalhos, links e formulários.  
- **VoiceOver (macOS/iOS)**  
  - Serve para: verificar conformidade de páginas em Safari e apps iOS com leitor embutido.  
  - Uso: ative com Cmd+F5, use os comandos VO+setas para navegar; útil para testar em Safari.  
- **TalkBack (Android)**  
  - Serve para: testar navegação em apps móveis usando leitor de tela nativo Android.  
  - Uso: habilite em Configurações > Acessibilidade, use gestos de deslizar e tocar para testar navegação em apps móveis.