# Design

"Existe uma lenda de que a acessibilidade torna um sítio web muito simples ou feio. Não é verdade: um sítio web bem estruturado pode ser bonito e criativo. É possível, inclusive, criar apresentações visuais diferentes para a mesma estrutura HTML de um sítio web com o uso de CSS e atender a diferentes necessidades". Dessa forma, nessa seção encontra-se checklist que garantam a acessibilidade no design.

## Aparência
- [ ] <b> Adicionar instrução</b> que não <b>dependa exclusivamente da cor</b>. <a id="TEC1" href="#RP1">[1]</a>
- [ ] <b> Adicionar informação</b> (como gráficos e diagramas) que não <b>dependa exclusivamente da cor</b>. <a id="TEC1" href="#RP1">[1]</a>
- [ ] <b> Tamanho do texto ajustável</b> para permitir ampliação. <a id="TEC2" href="#RP2">[2]</a>
- [ ] <b> Descrever os controles</b> pelo nome, não apenas pela aparência ou localização. <a id="TEC3"href="#RP3">[3]</a>
- [ ] <b> Garantir que dicas visuais</b> significativas atinjam 3:1 em relação ao fundo. <a id="TEC4" href="#RP4">[4]</a>
- [ ] <b> Fazer com que as linhas</b> de texto se ajustem ao viewport. <a id="TEC5"href="#RP5">[5]</a>
- [ ] Oferece uma <b> opção de alto contraste </b> (dark-mode) de suas páginas web e aumento de fontes.
- [ ] Parágrafos com no <b> máximo 80 caracteres por linha </b>.
- [ ] <b> Evita </b> o uso de <b> textos longos em caixa alta ou condensados </b>.
- [ ] Evita o alinhamento justificado.
- [ ] <b> Fontes são fluidas </b> e de fácil entendimento.
- [ ] Toma o devido cuidado com <b>``` display:none ``` e ``` visibility:hidden ``` para os recursos de tecnologia assistiva</b>
- [ ] Preferir <b> botões com texto e ícone </b>. E botões apenas com ícones tem o nome acessível.
- [ ] <b>Garantir espaçamento mínimo entre linhas de texto de 1,5× o tamanho da fonte</b> <a id="TEC10" href="#RP10">[10]</a>  
- [ ] <b>Usar fontes com altura-x legível (mínimo 8 px altura-x)</b> <a id="TEC11" href="#RP11">[11]</a>  
- [ ] <b>Evitar usar mais de duas famílias de fonte distintas em uma página</b> <a id="TEC12" href="#RP12">[12]</a>  
- [ ] <b>Oferecer contraste ≥ 3:1 entre ícones/texto e seu fundo</b> <a id="TEC13" href="#RP13">[13]</a>  
- [ ] <b>Manter orientação e layout consistentes em todas as páginas</b> <a id="TEC14" href="#RP14">[14]</a>  
- [ ] <b>Garantir que todos os controles gráficos (ícones, botões) tenham rótulos de texto ou `aria-label`</b> <a id="TEC15" href="#RP15">[15]</a>  


## Animação
- [ ] <b> Evitar conteúdo que pisque</b>, ou mantenha-o abaixo dos limites. <a id="TEC6" href="#RP6">[6]</a>
- [ ] <b> Permitir que os usuários controlem as alterações de conteúdo</b> que ocorrem em paralelo com outro conteúdo. <a id="TEC7" href="#RP7">[7]</a>
- [ ] <b> Toda a animação</b> deve obedecer à ```prefers-reduced-motion``` consulta de mídia. <a id="TEC8" href="#RP8">[8]</a>
- [ ] <b>Suspender automaticamente animações recorrentes após 5 segundos</b> <a id="TEC16" href="#RP16">[16]</a>  
- [ ] <b>Fornecer botão para desativar todas as animações não essenciais</b> <a id="TEC17" href="#RP17">[17]</a>  
- [ ] <b>Não usar animações de fundo em paralaxe que possam distrair ou causar desconforto</b> <a id="TEC18" href="#RP18">[18]</a>   

## Contraste de Cores
- [ ] <b> Verificar o contraste</b> de  todo texto tamanho normal. <a id="TEC9" href="#RP9">[9]</a>
- [ ] <b> Verificar o contraste</b> de todo texto tamanho grande. <a id="TEC9" href="#RP9">[9]</a>
- [ ] <b> Verificar o contraste</b> de todos os ícones. <a id="TEC4" href="#RP4">[4]</a>
- [ ] <b> Verificar o contraste</b> das bordas dos elementos de entrada (entrada de texto, botões de opção, caixas de seleção, etc.). <a id="#RP4" href="#RP4">[4]</a>
- [ ] <b> Verificar o texto</b> que se sobrepõe a imagens ou vídeos. <a id="TEC9" href="#RP9">[9]</a>
- [ ] <b> Verificar ```::selection``` cores</b> personalizadas. <a id="TEC9" href="#RP9">[9]</a>
- [ ] <b>Verificar contraste de elementos de foco (outline, shadow) ≥ 3:1 em relação ao fundo</b> <a id="TEC19" href="#RP19">[19]</a>  
- [ ] <b>Assegurar contraste ≥ 4.5:1 em texto de tooltips e pop-ups</b> <a id="TEC20" href="#RP20">[20]</a>  
- [ ] <b>Verificar contraste de separadores e bordas de tabelas ≥ 3:1</b> <a id="TEC21" href="#RP21">[21]</a>  
- [ ] <b>Escore de acessibilidade de combinações de cores pelo e-MAG Checker ≥ 80 %</b> <a id="TEC22" href="#RP22">[22]</a>  

## Referências Bibliograficas

> <a id="RP1" href="#TEC1">1.</a> WCAG 2.2 Understanding Docs. SC 1.4.1 Use of Color (Level A). Disponível em: [https://www.w3.org/WAI/WCAG22/Understanding/use-of-color.html](https://www.w3.org/WAI/WCAG22/Understanding/use-of-color.html). Acesso em: 9 Mai. 2024.

> <a id="RP2" href="#TEC2">2.</a> WCAG 2.2 Understanding Docs. SC 1.4.4 Resize Text (Level AA). Disponível em: [https://www.w3.org/WAI/WCAG22/Understanding/resize-text.html](https://www.w3.org/WAI/WCAG22/Understanding/resize-text.html). Acesso em: 9 Mai. 2024.

> <a id="RP3" href="#TEC3">3.</a> WCAG 2.2 Understanding Docs. SC 1.3.3 Sensory Characteristics (Level A). Disponível em: [https://www.w3.org/WAI/WCAG22/Understanding/sensory-characteristics.html](https://www.w3.org/WAI/WCAG22/Understanding/sensory-characteristics.html). Acesso em: 9 Mai. 2024.

> <a id="RP4" href="#TEC4">4.</a> WCAG 2.2 Understanding Docs. SC 1.4.11 Non-text Contrast (Level AA). Disponível em: [https://www.w3.org/WAI/WCAG22/Understanding/non-text-contrast.html](https://www.w3.org/WAI/WCAG22/Understanding/non-text-contrast.html). Acesso em: 9 Mai. 2024.

> <a id="RP5" href="#TEC5">5.</a> WCAG 2.2 Understanding Docs. SC 1.4.10 Reflow (Level AA). Disponível em: [https://www.w3.org/WAI/WCAG22/Understanding/reflow.html](https://www.w3.org/WAI/WCAG22/Understanding/reflow.html). Acesso em: 9 Mai. 2024.

> <a id="RP6" href="#TEC6">6.</a> WCAG 2.2 Understanding Docs. SC 2.3.1 Three Flashes or Below Threshold (Level A). Disponível em: [https://www.w3.org/WAI/WCAG22/Understanding/three-flashes-or-below-threshold.html](https://www.w3.org/WAI/WCAG22/Understanding/three-flashes-or-below-threshold.html). Acesso em: 9 Mai. 2024.

> <a id="RP7" href="#TEC7">7.</a> WCAG 2.2.2 Understanding Docs. SC 2.2.2 Pause, Stop, Hide (Level A). Disponível em: [https://www.w3.org/WAI/WCAG22/Understanding/pause-stop-hide.html](https://www.w3.org/WAI/WCAG22/Understanding/pause-stop-hide.html). Acesso em: 9 Mai. 2024.

> <a id="RP8" href="#TEC8">8.</a> WCAG 2.2 Understanding Docs. SC 2.3.3 Animation from Interactions (Level AAA). Disponível em: [https://www.w3.org/WAI/WCAG22/Understanding/animation-from-interactions.html](https://www.w3.org/WAI/WCAG22/Understanding/animation-from-interactions.html). Acesso em: 9 Mai. 2024.

> <a id="RP9" href="#TEC9">9.</a> WCAG 2.2 Understanding Docs. SC 1.4.3 Contrast (Minimum) (Level AA). Disponível em: [https://www.w3.org/WAI/WCAG22/Understanding/contrast-minimum.html](https://www.w3.org/WAI/WCAG22/Understanding/contrast-minimum.html). Acesso em: 9 Mai. 2024.

> <a id="RP10" href="#NBR6.3">10.</a> NBR 17060:2022, item 6.3 — Espaçamento entre linhas de no mínimo 1,5× o tamanho da fonte. Disponível em: **“Nova norma da ABNT para sistemas web amplia inclusão digital de pessoas com deficiência”**, NIC.br, 11 mar. 2025 :contentReference[oaicite:0]{index=0}

> <a id="RP11" href="#NBR6.4">11.</a> NBR 17060:2022, item 6.4 — Altura-x da fonte legível (mínimo 8 px). Disponível em: **“Norma da ABNT sobre acessibilidade para dispositivos móveis torna a navegação mais inclusiva”**, NIC.br :contentReference[oaicite:1]{index=1}

> <a id="RP12" href="#NBR6.5">12.</a> NBR 17060:2022, item 6.5 — Limitar a no máximo duas famílias de fonte distintas. Disponível em: **“Desenvolvida com coordenação do Ceweb.br, nova norma da ABNT estabelece requisitos para melhorar a acessibilidade de sites”**, CGI.br :contentReference[oaicite:2]{index=2}

> <a id="RP13" href="#NBR6.6">13.</a> NBR 17060:2022, item 6.6 — Contraste mínimo 3:1 entre ícones/texto e fundo. Disponível em: **“Normas da ABNT sobre acessibilidade”**, Câmara dos Deputados :contentReference[oaicite:3]{index=3}

> <a id="RP14" href="#NBR6.7">14.</a> NBR 17060:2022, item 6.7 — Layout e orientação consistentes em todas as páginas. Disponível em: **“ABNT lança norma de acessibilidade em aplicativos móveis”**, NIC.br :contentReference[oaicite:4]{index=4}

> <a id="RP15" href="#NBR6.8">15.</a> NBR 17060:2022, item 6.8 — Controles gráficos (ícones, botões) com rótulos de texto ou `aria-label`. Disponível em: **Norma ABNT NBR 17060:2022 — Acessibilidade em aplicativos de dispositivos móveis** :contentReference[oaicite:5]{index=5}

> <a id="RP16" href="#NBR7.3">16.</a> NBR 17060:2022, item 7.3 — Suspender automaticamente animações recorrentes após 5 s. Disponível em: **“Desenvolvida com coordenação do Ceweb.br…”**, CGI.br :contentReference[oaicite:6]{index=6}

> <a id="RP17" href="#NBR7.4">17.</a> NBR 17060:2022, item 7.4 — Botão para desativar todas as animações não essenciais. Disponível em: **“Normas da ABNT sobre acessibilidade”**, Câmara dos Deputados :contentReference[oaicite:7]{index=7}

> <a id="RP18" href="#NBR7.5">18.</a> NBR 17060:2022, item 7.5 — Não usar animações de paralaxe que causem distração. Disponível em: **“Nova norma da ABNT estabelece requisitos para melhorar a acessibilidade de sites”**, CGI.br :contentReference[oaicite:8]{index=8}

> <a id="RP19" href="#NBR8.1">19.</a> NBR 17060:2022, item 8.1 — Contraste de elementos de foco ≥ 3:1 em relação ao fundo. Disponível em: **Norma ABNT NBR 17060:2022 — Acessibilidade em aplicativos de dispositivos móveis** :contentReference[oaicite:9]{index=9}

> <a id="RP20" href="#NBR8.2">20.</a> NBR 17060:2022, item 8.2 — Contraste ≥ 4.5:1 em texto de tooltips e pop-ups. Disponível em: **“Desenvolvida com coordenação do Ceweb.br…”**, CGI.br :contentReference[oaicite:10]{index=10}

> <a id="RP21" href="#NBR8.3">21.</a> NBR 17060:2022, item 8.3 — Contraste de separadores e bordas de tabelas ≥ 3:1. Disponível em: **“Normas da ABNT sobre acessibilidade”**, Câmara dos Deputados :contentReference[oaicite:11]{index=11}

> <a id="RP22" href="#NBR8.4">22.</a> NBR 17060:2022, item 8.4 — Escore de acessibilidade de cores pelo e-MAG Checker ≥ 80 %. Disponível em: **NIC.br – Norma da ABNT sobre acessibilidade para dispositivos móveis** :contentReference[oaicite:12]{index=12}

## Bibliografia

> </a> DINIZ, V.; FERRAZ, R.; NASCIMENTO, C. M.; CREDIDIO, R. Guia de Boas Práticas para Acessibilidade Digital. Programa de Cooperação entre Reino Unido e Brasil em Acesso Digital, 2023. Disponível em: [https://www.gov.br/governodigital/pt-br/acessibilidade-e-usuario/acessibilidade-digital/guiaboaspraaticasparaacessibilidadedigital.pdf](https://www.gov.br/governodigital/pt-br/acessibilidade-e-usuario/acessibilidade-digital/guiaboaspraaticasparaacessibilidadedigital.pdf). Acesso em: 9 Mai. 2024.