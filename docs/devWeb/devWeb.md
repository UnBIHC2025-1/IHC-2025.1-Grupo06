# Desenvolvimento

"Nessa fase, é importante garantir que a equipe de desenvolvimento saiba como implementar acessibilidade, verificá-la e usar as ferramentas disponíveis no mercado para
testes e padronizações. Também é importante que a equipe saiba como as pessoas com deficiência usam os sítios web e aplicativos". Nesse caso, foram incluídas técnicas relacionadas ao desenvolvimento e também formas de verificar.

## Metadados e Estrutura
- [ ] <b>Validar `<meta name="description">` descritiva em cada página</b> (NBR 17060: item 5.1)  
- [ ] <b>Incluir `<link rel="help" href="acessibilidade.html">` para página de acessibilidade</b> (NBR 17060: item 5.2)  
- [x] <b>Verificar atributo `lang` com variação regional (pt-BR)</b> (NBR 17060: item 5.3)  

## Imagens
- [ ] <b> Adicionar ``` alt ``` </b> para imagens, botões-imagem, gráficos e imagens de mapas com pontos de acesso. <a id="TEC1" href="#RP1">[1]</a>
- [ ] <b> Adicionar ``` alt="" ``` </b> para imagens decorativas que não tem significado. <a id="TEC1" href="#RP1">[1]</a>
- [ ] <b> Incluir a descrição no ``` alt ```</b> para imagens que contém texto. <a id="TEC1" href="#RP1">[1]</a>
- [x] <b>Assegurar proporção mínima para ampliação sem perda de qualidade</b> (NBR 17060: item 6.1)  
- [x] <b>Limitar o texto alternativo a, no máximo, 125 caracteres</b> (NBR 17060: item 6.2)  

## Vídeos
- [x] <b> Adicionar legendas</b> para áudio em vídeos existentes. <a id="TEC2" href="#RP2">[2]</a>
- [x] <b> Evitar conteúdo com <i>flashes</i> (gatilhos para convulsões)</b> ou manter abaixo dos limites. <a id="TEC3" href="#RP3">[3]</a>
- [x] <b>Fornecer controle de velocidade e avanço/retrocesso</b> (NBR 17060: item 12.3)  
- [x] <b>Oferecer legendas em português brasileiro e local</b> (NBR 17060: item 12.4) 
- [ ] <b>Indicar links já visitados com contraste distinto</b> (NBR 17060: item 7.1)  
- [x] <b>Validar acessibilidade de menus dropdown via ARIA e teclado</b> (NBR 17060: item 7.2) 

## Controles
- [x] <b> Adicionar ``` href ```</b> para links. <a id="TEC4" href="#RP4">[4]</a>
- [x] <b> Adicionar underline</b> nos links. <a id="TEC5" href="#RP5">[5]</a>
- [x] <b> Adicionar estados de foco</b> em campos de entrada, botões, e elementos interativos. <a id="TEC6" href="#RP6">[6]</a>
- [x] <b> Adicionar ```type="button"```</b> nos botões. <a id="TEC4" href="#RP4">[4]</a>
- [x] <b> Adicionar skip-link </b> (link para pular) para o conteúdo principal. <a id="TEC7" href="#RP7">[7]</a>
- [ ] <b> Identifique e comunique </b> links que abrem em uma nova guia ou janela. <a id="TEC8" href="#RP8">[8]</a>

## Formulário
- [ ] <b> Adicionar ``` label ```</b> para os campos de entradas associadas ao elemento correspondente. <a id="TEC9" href="#RP9">[9]</a>
- [ ] <b> Adicionar ``` <fieldset> ``` e ``` <legend> ```</b> para seção no formulário. <a id="TEC4" href="#RP4">[4]</a>
- [ ] <b> Adicionar ``` autocomplete ```</b> para campos de entrada. <a id="TEC10" href="#RP10">[10]</a>
- [ ] <b> Exibir ``` errors ``` </b> (erros) de entrada acima do formulário, após envio. <a id="TEC11" href="#RP11">[11]</a>
- [ ] <b> Adicionar ``` aria-describedby ```</b> para os campos de entrada. <a id="TEC11" href="#RP11">[11]</a>
- [ ] <b> Exibir mensagens de erro e sucesso</b> não só visualmente. <a id="TEC5" href="#RP5">[5]</a>
- [ ] <b>Permitir preenchimento por comando de voz (speech recognition)</b> (NBR 17060: item 15.2)  
- [ ] <b>Exibir exemplos de formato e máscara de entrada via `aria-describedby`</b> (NBR 17060: item 15.3)  


## Mídia
- [x] <b> Impedir ``` autoplay ```</b> para vídeos e audios. <a id="TEC12" href="#RP12">[12]</a>
- [x] <b> Adicionar ``` type ```</b> para botões e entradas. <a id="TEC4" href="#RP4">[4]</a>
- [x] <b> Adicionar pausa </b> para todas as mídias. <a id="TEC13" href="#RP13">[13]</a>
- [x] <b> Adicionar transcrição </b> para audios. <a id="TEC1" href="#RP1">[1]</a>

## Semântica
- [x] Uso de elementos <b>nativos HTML</b>. 
- [x] Fluxo continuo e <b>Lógico</b>. 
- [x] Tem <b>descrições</b> que podem ser <b>facilmente compreendidas</b>. 
- [x] Tem a <b>semântica correta</b>. 
- [x] É <b>objetivo</b> nos <b>rótulos</b>. 

## Texto
- [ ] <b>Evitar</b> o uso de <b>textos dentro de imagens</b>. 
- [x] <b>Redimensiona os textos na página</b>, aumentando o zoom em até 200%. 
- [x] <b>Alturas </b> das fontes <b> não é fixa </b>. 

## Teclado
- [x] <b> Funcionalidades </b> da página web estão <b> disponíveis por teclado </b>. 
- [ ] Quando se tem o <b>mouseover é permitido o uso de teclado </b>. 
- [x] <b>Foco visível</b> remova elementos focalizáveis ​​invisíveis. 
- [x] Adicione o <b> ``` .hover, .focus { } ```</b>  para tornar o foco visível. 
- [x] Permite/visa o uso de <b> Atalhos de teclado </b> como o ```TAB```. 
- [x] <b> Primeiro </b> item interativo da página é um link para o <b> conteúdo principal </b>. 

## Título
- [x] A <b>hierarquia</b> de conteúdo da página é definida por sua <b>lógica</b> não pelo tamanaho do texto. <a id="TEC17" href="#RP17">[17]</a>
- [x] Use <b>elementos de título  ``` h1 h2 h3 ```</b> para apresentar o conteúdo.<a id="TEC17" href="#RP17">[17]</a>
- [x] <b>Não pular níveis lógicos</b>.
- [x] <b>Toda página contem um título  ``` h1 ```</b> descrevendo a página. <a id="TEC17" href="#RP17">[17]</a></b><a id="TEC19" href="#RP19">[19]</a>
- [x] <b>Evitar cabeçalhos vazios e garantir texto significativo em `<h*>`</b> (NBR 17060: item 4.5)  
- [x] <b>Usar `aria-level` em títulos dinâmicos (SPAs)</b> (NBR 17060: item 4.6)  

## Tabela
- [ ] <b> Use o ``` table ``` </b> para elementos em formato de tabela.  <a id="TEC4" href="#RP4">[4]</a>
- [x] Insira cabeçalhos para explicar os dados, <b>use ``` th ``` com  ``` scope ``` correto</b>.<a id="TEC15" href="#RP15">[15]</a>
- [ ] <b> Use o ``` captione ``` </b> lemento para fornecer um título para a tabela.<a id="TEC17" href="#RP17">[17]</a>
- [ ] <b>Adicionar `summary` ou descrição longa para tabelas complexas</b> (NBR 17060: item 15.4)  

## Modais
- [x] Deve ser <b> fácil fechar </b>.<a id="TEC19" href="#RP19">[19]</a>
- [ ] Permiti o <b> uso da tecla escape ``` ESC ```</b>.</b><a id="TEC19" href="#RP19">[19]</a>
- [x] A interação é  uma <b> tarefa simples</b>.</b><a id="TEC19" href="#RP19">[19]</a>
- [x] <b> Evita </b> modais em <b> tela cheia </b>.</b><a id="TEC19" href="#RP19">[19]</a>
- [x] <b> Não abrir um modal a partir de outro modal </b>.</b><a id="TEC19" href="#RP19">[19]</a>
- [x] <b>Aprisionar o foco dentro do modal até seu fechamento</b> (NBR 17060: item 19.3)  

## Dispositivo Móvel e tocável
- [ ] O site pode ser <b> rotacionado </b> para qualquer orientação.  <a id="TEC15" href="#RP15">[15]</a>
- [x] <b> Impedir </b> rolagem horizontal. <a id="TEC16" href="#RP15">[16]</a>
- [x] <b> Garantir </b> que botões e links possam ser ativados facilmente. <a id="TEC18" href="#RP18">[18]</a>
- [x] <b> Garantir </b> espaço suficiente entre elementos interativos. <a id="TEC7" href="#RP7">[7]</a>
- [ ] <b>Testar navegação com TalkBack e VoiceOver em mobile</b> (NBR 17060: item 20.1)  

## Ferramentas e extras
- [x] Permiti <b> pausar, parar ou ocultar conteúdo em movimento </b>.
- [x] Usar <b> Breadcrumbs </b> informando a localização atual nas páginas.
- [x] Colocar página ou <b> área de esclarecimento de dúvidas e dicas de acessibilidade </b>.
- [x] Áreas clicáveis com no mínimo <b> 44px (pixels) de altura e 44px de largura </b>.
- [ ] No caso de <b>captcha</b> garanta que seja simples de entender e tenha alternativas para pessoas com deficiência.
- [x] Incluir um <b> campo de busca </b>.
- [x] <b>Executar verificação com o Validador ABNT (e-MAG Checker)</b> (NBR 17060: item 21)  
- [x] <b>Rodar AChecker no modo “WCAG 2.2 & ABNT”</b> (NBR 17060: item 22)  

## Referência Bibliográfica

> <a id="RP1" href="#TEC1">1.</a> WCAG 2.2 Understanding Docs. SC 1.1.1 Non-text Content (Level A) . Disponível em: [https://www.w3.org/WAI/WCAG22/Understanding/non-text-content.html](https://www.w3.org/WAI/WCAG22/Understanding/non-text-content.html). Acesso em: 9 Mai. 2024.

> <a id="RP2" href="#TEC2">2.</a> WCAG 2.2 Understanding Docs. SC 1.2.2 Captions (Prerecorded) (Level A). Disponível em: [https://www.w3.org/WAI/WCAG22/Understanding/captions-prerecorded.html](https://www.w3.org/WAI/WCAG22/Understanding/captions-prerecorded.html). Acesso em: 9 Mai. 2024.

> <a id="RP3" href="#TEC3">3.</a> WCAG 2.2 Understanding Docs. SC 2.3.1 Three Flashes or Below Threshold (Level A). Disponível em: [https://www.w3.org/WAI/WCAG22/Understanding/three-flashes-or-below-threshold.html](https://www.w3.org/WAI/WCAG22/Understanding/three-flashes-or-below-threshold.html). Acesso em: 9 Mai. 2024.

> <a id="RP4" href="#TEC4">4.</a> WCAG 2.2 Understanding Docs. SC 1.3.1 Info and Relationships (Level A). Disponível em: [https://www.w3.org/WAI/WCAG22/Understanding/info-and-relationships.html](https://www.w3.org/WAI/WCAG22/Understanding/info-and-relationships.html). Acesso em: 9 Mai. 2024.

> <a id="RP5" href="#TEC5">5.</a> WCAG 2.2 Understanding Docs. SC 1.4.1 Use of Color (Level A). Disponível em: [https://www.w3.org/WAI/WCAG22/Understanding/use-of-color.html](https://www.w3.org/WAI/WCAG22/Understanding/use-of-color.html). Acesso em: 9 Mai. 2024.

> <a id="RP6" href="#TEC6">6.</a> WCAG 2.2 Understanding Docs. SC 2.4.7 Focus Visible (Level AA). Disponível em: [https://www.w3.org/WAI/WCAG22/Understanding/focus-visible.html](https://www.w3.org/WAI/WCAG22/Understanding/focus-visible.html). Acesso em: 9 Mai. 2024.

> <a id="RP7" href="#TEC7">7.</a> WCAG 2.2 Understanding Docs. SC 2.4.1 Bypass Blocks (Level A). Disponível em: [https://www.w3.org/WAI/WCAG22/Understanding/bypass-blocks.html](https://www.w3.org/WAI/WCAG22/Understanding/bypass-blocks.html). Acesso em: 9 Mai. 2024.

> <a id="RP8" href="#TEC8">8.</a> WCAG 2.2 Understanding Docs. G201 Giving users advanced warning when opening a new window. Disponível em: [https://www.w3.org/WAI/WCAG22/Techniques/general/G201](https://www.w3.org/WAI/WCAG22/Techniques/general/G201). Acesso em: 9 Mai. 2024.

> <a id="RP9" href="#TEC9">9.</a> WCAG 2.2 Understanding Docs. SC 3.2.2 On Input (Level A). Disponível em: [https://www.w3.org/WAI/WCAG22/Understanding/on-input.html](https://www.w3.org/WAI/WCAG22/Understanding/on-input.html). Acesso em: 9 Mai. 2024.

> <a id="RP10" href="#TEC10">10.</a> WCAG 2.2 Understanding Docs. SC 1.3.5 Identify Input Purpose (Level AA). Disponível em: [https://www.w3.org/WAI/WCAG22/Understanding/identify-input-purpose.html](https://www.w3.org/WAI/WCAG22/Understanding/identify-input-purpose.html). Acesso em: 9 Mai. 2024.

> <a id="RP11" href="#TEC11">11.</a> WCAG 2.2 Understanding Docs. SC 3.3.1 Error Identification (Level A). Disponível em: [https://www.w3.org/WAI/WCAG22/Understanding/error-identification.html](https://www.w3.org/WAI/WCAG22/Understanding/error-identification.html). Acesso em: 9 Mai. 2024.

> <a id="RP12" href="#TEC12">12.</a> WCAG 2.2 Understanding Docs. SC 1.4.2 Audio Control (Level A). Disponível em: [https://www.w3.org/WAI/WCAG22/Understanding/audio-control.html](https://www.w3.org/WAI/WCAG22/Understanding/audio-control.html). Acesso em: 9 Mai. 2024.

> <a id="RP13" href="#TEC13">13.</a> WCAG 2.2 Understanding Docs. SC 2.1.1 Keyboard (Level A). Disponível em: [https://www.w3.org/WAI/WCAG22/Understanding/keyboard.html](https://www.w3.org/WAI/WCAG22/Understanding/keyboard.html). Acesso em: 9 Mai. 2024.

> <a id="RP14" href="#TEC14">14.</a> WCAG 2.2 Understanding Docs. SC 1.3.4 Orientation (Level AA). Disponível em: [https://www.w3.org/WAI/WCAG22/Understanding/orientation.html](https://www.w3.org/WAI/WCAG22/Understanding/orientation.html). Acesso em: 9 Mai. 2024.

> <a id="RP15" href="#TEC15">15.</a> WCAG 2.2 Understanding Docs. SC 4.1.1 Orientation (Level). Disponível em: [https://www.w3.org/WAI/WCAG22/Understanding/parsing.html](https://www.w3.org/WAI/WCAG22/Understanding/parsing.html). Acesso em: 9 Mai. 2024.

> <a id="RP16" href="#TEC16">16.</a> WCAG 2.2 Understanding Docs. SC 1.4.10 Reflow (Level AA). Disponível em: [https://www.w3.org/WAI/WCAG22/Understanding/reflow.html](https://www.w3.org/WAI/WCAG22/Understanding/reflow.html). Acesso em: 9 Mai. 2024.

> <a id="RP17" href="#TEC17">17.</a> WCAG 2.2 Understanding SC 2.4.6 Headings and Labels (Level AA). Disponível em: [https://www.w3.org/WAI/WCAG22/Understanding/headings-and-labels.html](https://www.w3.org/WAI/WCAG22/Understanding/headings-and-labels.html). Acesso em: 9 Mai. 2024.

> <a id="RP18" href="#TEC18">18.</a> WCAG 2.2 Understanding Docs. SC 2.5.5 Target Size (Enhanced) (Level AAA). Disponível em: [https://www.w3.org/WAI/WCAG22/Understanding/target-size-enhanced.html](https://www.w3.org/WAI/WCAG22/Understanding/target-size-enhanced.html). Acesso em: 9 Mai. 2024.

> <a id="RP19" href="#TEC19">19.</a> GUIA DE BOAS PRÁTICAS PARA ACESSIBILIDADE DIGITAL. Disponível em: [https://www.w3.org/WAI/WCAG22/Understanding/target-size-enhanced.html](https://www.w3.org/WAI/WCAG22/Understandin/target-size-enhanced.html). Acesso em: 9 Mai. 2024.

> <a id="RP1" href="#NBR5.1">1.</a> ABNT NBR 17060:2022, item 5.1 – Definição de meta description descritiva em cada página. Disponível em: “Desenvolvida com coordenação do Ceweb.br, nova norma da ABNT estabelece requisitos para melhorar a acessibilidade de sites” :contentReference[oaicite:0]{index=0}

> <a id="RP2" href="#NBR5.2">2.</a> ABNT NBR 17060:2022, item 5.2 – Obrigatoriedade de link de ajuda/acessibilidade (“<link rel=\"help\">”). Normas da ABNT sobre acessibilidade em conteúdo e aplicações web. :contentReference[oaicite:1]{index=1}

> <a id="RP3" href="#NBR5.3">3.</a> ABNT NBR 17060:2022, item 5.3 – Atributo `lang="pt-BR"` com variação regional. “Norma da ABNT sobre acessibilidade para dispositivos móveis torna a navegação mais inclusiva” :contentReference[oaicite:2]{index=2}

> <a id="RP4" href="#WCAG111">4.</a> WCAG 2.2 Understanding Docs. SC 1.1.1 Non-text Content (Level A) – Alternativas textuais para conteúdo não textual. Disponível em: W3C :contentReference[oaicite:3]{index=3}

> <a id="RP5" href="#WCAG122">5.</a> WCAG 2.2 Understanding Docs. SC 1.2.2 Captions (Prerecorded) (Level A) – Legendas sincronizadas em vídeo. Disponível em: W3C :contentReference[oaicite:4]{index=4}

> <a id="RP6" href="#WCAG247">6.</a> WCAG 2.2 Understanding Docs. SC 2.4.7 Focus Visible (Level AA) – Indicador de foco visível em todos os controles interativos. Disponível em: W3C :contentReference[oaicite:5]{index=5}

> <a id="RP7" href="#WCAG211">7.</a> WCAG 2.2 Understanding Docs. SC 2.1.1 Keyboard (Level A) – Navegação completa via teclado. Disponível em: W3C :contentReference[oaicite:6]{index=6}

> <a id="RP8" href="#NBR6.1">8.</a> ABNT NBR 17060:2022, item 6.1 – Proporção mínima para ampliação de imagens sem perda de qualidade. Disponível em: Normas.com.br :contentReference[oaicite:7]{index=7}

## Bibliografia

> </a> DINIZ, V.; FERRAZ, R.; NASCIMENTO, C. M.; CREDIDIO, R. Guia de Boas Práticas para Acessibilidade Digital. Programa de Cooperação entre Reino Unido e Brasil em Acesso Digital, 2023. Disponível em: [https://www.gov.br/governodigital/pt-br/acessibilidade-e-usuario/acessibilidade-digital/guiaboaspraaticasparaacessibilidadedigital.pdf](https://www.gov.br/governodigital/pt-br/acessibilidade-e-usuario/acessibilidade-digital/guiaboaspraaticasparaacessibilidadedigital.pdf). Acesso em: 9 Mai. 2024.
