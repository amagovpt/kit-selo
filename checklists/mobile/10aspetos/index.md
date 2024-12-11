---
title: 10 Aspetos Críticos de Acessibilidade Funcional para Aplicações Móveis
---
<h1>{{ page.title }}</h1>

nota: o presente documento pode ser comentado no seu [repositório no GitHub](https://github.com/amagovpt/booka11y/tree/main/mobile-v2). Se tem algo que nos queira dizer abra um [issue](https://github.com/amagovpt/booka11y/issues).

- Documento de recolha de evidências em formato .xlsx: [ficheiro de recolha de evidências para a lista de verficação 10 aspetos críticos de acessibilidade funcional para aplicações móveis (xlsx, 163Kb)](sintese-10aspetos-mobile.xlsx). Use este ficheiro para recolher na aplicação móvel as evidências de satisfação dos requisitos de acessibilidade e anexe-a à sua Declaração de Acessibilidade. 

## 1. Crie <em lang="en">designs</em> para ecrãs de dimensão reduzida

Na experiência com dispositivos móveis os ecrãs são, em regra, muito mais pequenos do que nos computadores de secretária ou mesmo nos portáteis. A leitura e a interação num ecrã de dimensão reduzida obriga a que a informação seja apresentada de forma mais concisa e, para o caso da interação, esta deva ser construída dando particular atenção às dimensões reduzidas  dos alvos de toque. 

- [1.1 Quantidade razoável de conteúdo exibida de cada vez](1.md/#11-quantidade-razoável-de-conteúdo-exibida-de-cada-vez)
- [1.2 Botões e controlos suficientemente grandes para serem percecionados pela visão e selecionáveis pelo toque](1.md/#12-botões-e-controlos-suficientemente-grandes-para-serem-percecionados-pela-visão-e-selecionáveis-pelo-toque)
- [1.3 Campos de formulário posicionados abaixo dos seus rótulos](1.md/#13-campos-de-formulário-posicionados-abaixo-dos-seus-rótulos)

## 2. Crie gestos simples e disponibilize opções acessíveis

Normalmente os dispositivos móveis são controlados por gestos, tais como passar um ou mais dedos em várias direções ou dar um ou mais toques com um ou mais dedos. No entanto, os gestos disponíveis por defeito nos dispositivos não funcionam para todas as pessoas. Gestos complexos, como sejam os gestos para desenhar formas, que obrigam a usar vários dedos ou a efetuar múltiplos toques, são difíceis, ou mesmo impossíveis, de compreender ou executar por alguns utilizadores. Por isso, é importante que os gestos sejam sempre acompanhados por opções alternativas que permitam o controlo via tecnologias de apoio ou que respondam aos diferentes métodos de controlo alternativos. Os movimentos involuntários dos utilizadores podem colidir com funcionalidades que são ativadas com o movimento dos dispositivos. É por isso importante que os dispositivos permitam a sua desativação e a existência de formas alternativas de executar tais funcionalidades.

- [2.1 Controlos de toque são ativados após deixar de exercer pressão (up event) e não após o toque inicial (down event)](2.md/#21-controlos-de-toque-são-ativados-após-deixar-de-exercer-pressão-up-event-e-não-após-o-toque-inicial-down-event)
- [2.2 Funcionalidades ativadas através do movimento, inclinação, ou do sacudir físico do dispositivo podem ser desativadas](2.md/#22-funcionalidades-ativadas-através-do-movimento-inclinação-ou-do-sacudir-físico-do-dispositivo-podem-ser-desativadas)
- [2.3 Funcionalidades ativadas através do movimento físico do dispositivo podem ser operadas através de componentes de interface](2.md/#23-funcionalidades-ativadas-através-do-movimento-físico-do-dispositivo-podem-ser-operadas-através-de-componentes-de-interface)
- [2.4 Gestos Multiponto (uso simultâneo de vários dedos) ou gestos baseados no desenho de uma trajetória estão também disponíveis com gestos que fazem uso do toque de um só ponto ou que não obrigam a desenhar uma trajetória](2.md/#24-gestos-multiponto-uso-simultâneo-de-vários-dedos-ou-gestos-baseados-no-desenho-de-uma-trajetória-estão-também-disponíveis-com-gestos-que-fazem-uso-do-toque-de-um-só-ponto-ou-que-não-obrigam-a-desenhar-uma-trajetória)

## 3. Forneça indicações para gestos e ações

Os gestos nem sempre são intuitivos, especialmente quando fogem do padrão regular ou correspondem a padrões pouco utilizados. Algo semelhante acontece com as ações disponíveis num determinado momento - nem sempre é óbvio para todos os utilizadores que ações estão disponíveis e que decisão tomar.

Para que os utilizadores não façam involuntariamente coisas como abrir um menu que não queriam ou sair de um processo que desejavam continuar, é importante fornecer contexto e instruções de como prosseguir num dado ponto de um sítio Web ou de uma aplicação móvel.

- [3.1 Sempre que se faz uso de gestos não padronizados, são fornecidas indicações no ecra e texto acessível que dão conta da sua existência e de como se usam](3.md#31-sempre-que-se-faz-uso-de-gestos-n%C3%A3o-padronizados-s%C3%A3o-fornecidas-indica%C3%A7%C3%B5es-no-ecra-e-texto-acess%C3%ADvel-que-d%C3%A3o-conta-da-sua-exist%C3%AAncia-e-de-como-se-usam)
- [3.2 Sempre que se faz uso de elementos ativáveis pouco óbvios, são fornecidas indicações no ecrã e texto acessível que explicitam o caráter ativável dos respetivos elementos](3.md#32-sempre-que-se-faz-uso-de-elementos-ativ%C3%A1veis-pouco-%C3%B3bvios-s%C3%A3o-fornecidas-indica%C3%A7%C3%B5es-no-ecr%C3%A3-e-texto-acess%C3%ADvel-que-explicitam-o-car%C3%A1ter-ativ%C3%A1vel-dos-respetivos-elementos)
- [3.3 Elementos ativáveis estão agrupados intuitivamente](3.md#33-elementos-ativ%C3%A1veis-est%C3%A3o-agrupados-intuitivamente)
- [3.4 Estão disponíveis instruções claras, em texto, para interações complexas](3.md#34-est%C3%A3o-dispon%C3%ADveis-instru%C3%A7%C3%B5es-claras-em-texto-para-intera%C3%A7%C3%B5es-complexas)

## 4. Permita o uso de múltiplos métodos de entrada e inserção de dados

Uma das caraterísticas mais distintivas dos dispositivos móveis é a existência de um ecrã sensível ao toque. No entanto, nem todos podem navegar ou inserir dados através de gestos ou toques precisos no ecrã. O conteúdo não deve impedir o uso de outros métodos de operar a interface ou de inserir dados que existem para além do toque no ecrã. É importante que os métodos de operação e inserção de dados disponíveis suportem dispositivos de entrada alternativos, como sejam os teclados externos, dispositivos apontadores, manipulos e outras opções acessíveis. A diversidade dos métodos de operação e inserção torna o conteúdo móvel mais acessível e utilizável a pessoas que têm dificuldade em usar ecrãs sensíveis ao toque.

- [4.1 Teclado virtual definido para o tipo de entrada de dados](4.md#41-teclado-virtual-definido-para-o-tipo-de-entrada-de-dados)
- [4.2 Métodos de entrada de dados simples e previsíveis](4.md#42-m%C3%A9todos-de-entrada-de-dados-simples-e-previs%C3%ADveis)
- [4.3 Suporte a teclados e outros dispositivos de entrada, alternativos ao ecrã sensível ao toque](4.md#43-suporte-a-teclados-e-outros-dispositivos-de-entrada-alternativos-ao-ecr%C3%A3-sens%C3%ADvel-ao-toque)


## 5. Permita a ativação da ampliação e o redimensionamento do texto

O tamanho reduzido dos ecrãs dos dispositivos móveis levam os utilizadores a redimensionar frequentemente o tamanho do texto. Dada a sua importância, hoje em dia, esta é uma função que se encontra disponível em quase todos os dispositivos móveis. É importante que programadores e <em lang="en">designers</em> não a desativem e que garantam que o conteúdo funciona como esperado, mesmo quando ampliado ou redimensionado. Práticas de conceção responsivas permitem que o conteúdo se adapte a variações do tamanho do texto e diferentes posicionamentos, de acordo com as especificações do dispositivo, do software e das preferências do utilizador. A existência de opções nas páginas para redimensionar texto pode ser útil e contribbuir para aumentar a facilidade de uso da aplicação.

- [5.1 - Usando a funcionalidade de ampliação de texto do sistema operativo, no mínimo, é possível redimensionar o texto em 200% sem a utilização de tecnologias de apoio](5.md#51---usando-a-funcionalidade-de-ampliação-de-texto-do-sistema-operativo-no-mínimo-é-possível-redimensionar-o-texto-em-200-sem-a-utilização-de-tecnologias-de-apoio)
- [5.2 - Usando a funcionalidade de ampliação de texto do navegador web, no mínimo, é possível redimensionar o texto em 200% sem a utilização de tecnologias de apoio](5.md#52---usando-a-funcionalidade-de-ampliação-de-texto-do-navegador-web-no-mínimo-é-possível-redimensionar-o-texto-em-200-sem-a-utilização-de-tecnologias-de-apoio)
- [5.3 - Usando mecanismos de ampliação existentes na interface da página Web/app, no mínimo, é possível redimensionar o texto em 200% sem a utilização de tecnologias de apoio](5.md#53---usando-mecanismos-de-ampliação-existentes-na-interface-da-página-webapp-no-mínimo-é-possível-redimensionar-o-texto-em-200-sem-a-utilização-de-tecnologias-de-apoio)
- [5.4 - Usando as 3 funcionalidades de ampliação anteriores, verifique se o texto dos controlos de formulário (e.g. campos de edição, botões) pode ser ampliado até aos 200%](5.md#54---usando-as-3-funcionalidades-de-amplia%C3%A7%C3%A3o-anteriores-verifique-se-o-texto-dos-controlos-de-formul%C3%A1rio-eg-campos-de-edi%C3%A7%C3%A3o-bot%C3%B5es-pode-ser-ampliado-at%C3%A9-aos-200)

## 6. Certifique-se que a orientação do dispositivo e o layout da página não limitam o uso

Algumas experiências móveis são concebidas de origem para visualizações espcíficas em modo retrato ou paisagem, no entanto há pessoas que precisam ou preferem ter a opção de troca entre modos de visualização retrato/paisagem sempre ativo ou que usam sempre um dos modos. Para além disso, todos os utilizadores dizem que os sítios Web ou as aplicações móveis são mais fáceis de usar quando as suas páginas se apresentam com padrões esperados e se apresentam de forma consistente entre páginas e entre funções.

- [6.1 A orientação do ecrã pode ser alterado entre modo retrato e modo paisagem](6.md#61-a-orienta%C3%A7%C3%A3o-do-ecr%C3%A3-pode-ser-alterado-entre-modo-retrato-e-modo-paisagem)
- [6.2 O layout da página é consistente e previsível](6.md#62-o-layout-da-p%C3%A1gina-%C3%A9-consistente-e-previs%C3%ADvel)

## 7. Faça com que a estrutura e a navegação se apresentem a todos os utilizadores

Mesmo que a regra seja a de mostrar quantidades mais pequenas de conteúdo de uma só vez, a organização e a etiquetagem adequada dos conteúdos em dispositivos móveis são tão relevantes   quanto na experiência em computador. Todas as páginas e conteúdos precisam de ser intuitivamente navegáveis através da visão ou de qualquer tecnologia de apoio utilizada - um leitor de ecrã, por exemplo. Construir páginas fáceis de pesquisar, com funcionalidades fáceis de compreender e assegurar que a experiência se encontra otimizada para qualquer utilizador independentemente da forma de uso.

- [7.1 As páginas têm títulos descritivos](7.md#71-as-p%C3%A1ginas-t%C3%AAm-t%C3%ADtulos-descritivos)
- [7.2 Os títulos encontram-se hierarquicamente aninhados, numa ordem de leitura apropriada e ao alcance das tecnologias de apoio](7.md#72-os-t%C3%ADtulos-encontram-se-hierarquicamente-aninhados-numa-ordem-de-leitura-apropriada-e-ao-alcance-das-tecnologias-de-apoio)
- [7.3 Menus, controlos e hiperligações funcionam quer através do toque no ecrã quer através do teclado](7.md#73-menus-controlos-e-hiperliga%C3%A7%C3%B5es-funcionam-quer-atrav%C3%A9s-do-toque-no-ecr%C3%A3-quer-atrav%C3%A9s-do-teclado)
- [7.4 Menus, controlos e hiperligações apresentam-se sempre claramente etiquetados independentemente de se usarem ou não tecnologias de apoio](7.md#74-menus-controlos-e-hiperliga%C3%A7%C3%B5es-apresentam-se-sempre-claramente-etiquetados-independentemente-de-se-usarem-ou-n%C3%A3o-tecnologias-de-apoio)

## 8. Forneça alternativas em texto para gráficos e multimédia

Tal como num sítio Web, ou em qualquer outra plataforma digital, a disponibilização de alternativas em texto é crítica. Esta técnica permite que os utilizadores de tecnologias de apoio, mas também todos aqueles que tenham conexões lentas à Internet ou que, por qualquer razão técnica ou ambiental, se vejam impedidos de aceder a uma imagem, um gráfico, um vídeo ou um registo áudio, disponham de uma forma alternativa em texto que lhes permita aceder à mensagem veiculada por aqueles.

- [8.1 Conteúdo gráfico tem um alternativo em texto acessível](8.md#81-conte%C3%BAdo-gr%C3%A1fico-tem-um-alternativo-em-texto-acess%C3%ADvel)
- [8.2 Vídeos contêm legendas sincronizadas e sem erros](8.md#82-v%C3%ADdeos-cont%C3%AAm-legendas-sincronizadas-e-sem-erros)
- [8.3 Vídeos contêm, se necessário, áudiodescrição](8.md#83-v%C3%ADdeos-cont%C3%AAm-se-necess%C3%A1rio-%C3%A1udiodescri%C3%A7%C3%A3o)
- [8.4 Textos e não imagens de texto são usados sempre que possível](8.md#84-textos-e-n%C3%A3o-imagens-de-texto-s%C3%A3o-usados-sempre-que-poss%C3%ADvel)

## 9. Utilize a cor de modo efetivo

As cores são elementos importantes para personalizar marcas e interfaces. A regra é usar a cor de forma criativa, mas efetiva, que funcione para vários utilizadores. Na verdade, existem apenas duas importantes considerações de acessibilidade a ter em conta: (1) usar um contraste suficiente e (2) evitar a cor como única pista visual para veicular informações importantes. Embora o uso adequado de cores seja igualmente importante em computadores, nos dispositivos móveis o uso da cor torna-se ainda mais crítico. A utilização dos dispositivos móveis nos mais diversos ambientes, com diferentes condições de luminosidade, torna a tarefa de ver o ecrã um desafio mais sensível às cores em uso. Desafio que afeta em maior ou menor grau todos os utilizadores e não apenas pessoas com dificuldades de perceção da cor ou com baixa visão.

- [9.1 O texto normal apresenta-se com um rácio de contraste de, no mínimo, 4.5 para 1](9.md#91-o-texto-normal-apresenta-se-com-um-r%C3%A1cio-de-contraste-de-no-m%C3%ADnimo-45-para-1)
- [9.2 O texto grande apresenta-se com um rácio de contraste de, no mínimo, 3 para 1](9.md#92-o-texto-grande-apresenta-se-com-um-r%C3%A1cio-de-contraste-de-no-m%C3%ADnimo-3-para-1)
- [9.3 As componentes de interface e as componentes gráficas apresentam-se com um rácio de contraste de, no mínimo, 3 para 1](9.md#93-as-componentes-de-interface-e-as-componentes-gr%C3%A1ficas-apresentam-se-com-um-r%C3%A1cio-de-contraste-de-no-m%C3%ADnimo-3-para-1)
- [9.4 Informação ou significado (por exemplo um erro) não é veiculado apenas pela cor](9.md#94-informa%C3%A7%C3%A3o-ou-significado-por-exemplo-um-erro-n%C3%A3o-%C3%A9-veiculado-apenas-pela-cor)

## 10. Idioma da aplicação

- [10.1 O idioma principal codificado na página da aplicação corresponde ao idioma escrito](10.md)

## Créditos

A presente lista de requisitos foi compilada pelo Núcleo de Acessibilidade e Experiência Digital da AMA, I.P.

Principais autores:

- Jorge Fernandes
- Victória Santos

## Referências

Apple. (2024). [Human Interface Guidelines - Accessibility](https://developer.apple.com/design/human-interface-guidelines/accessibility).

Appt. (2024). [Appt Evaluation Methodology (Appt-EM)](https://appt.org/en/guidelines/appt-em)

Bureau of Internet Accessibility. (2021). [The definitive mobile accessibility checklist: Open your mobile website and apps to a wider audience](https://www.boia.org/definitive-mobile-accessibility-checklist). Estados Unidos da América: [BOIA](https://www.boia.org).

Deque. (2024). [Rules & Remediation](https://docs.deque.com/devtools-mobile/2024.9.18/en/rules)

Evinced. (2024). [MCAG - Mobile Content Accessibility Guidellines](https://getevinced.github.io/mcag/).

Google. (2024). [Principles for improving app accessibility](https://developer.android.com/guide/topics/ui/accessibility/principles).

Paul J. Adam. (??). [Mobile Accessibility QA Testing Checklist](https://pauljadam.com/demos/mobilechecklist.html).

W3C/WAI. (2023). [Techniques for WCAG 2.1](https://www.w3.org/WAI/WCAG21/Techniques/). Developed by Accessibility Guidelines Working Group (AG WG) Participants. Updated 20 June 2023.

W3C/WAI. (2015). [Mobile Accessibility: How WCAG 2.0 and Other W3C/WAI Guidelines Apply to Mobile](https://www.w3.org/TR/mobile-accessibility-mapping/). W3C First Public Working Draft 26 February 2015.
