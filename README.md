Dicas Material Design Lite

div - principal que engloba
.mdl-layout
.mdl-js-layout
.mdl-layout--fixed-header # fixar a barra de cima
.mdl-layout--fixed-drawer # fixar drawer aberto por padrão

Tag header
.mdl-layout__header
.mdl-layout__header--transparent #deixar o fundo da barra transparent
Linha do header
.mdl-layout__header-row

Titulo 
.mdl-layout-title

Tag nav para o menu deve estar dentro do mdl-header
.mdl-navigation

Div com essa classe vai espaçar e jogar o nav para a direita
.mdl-layout-spacer


Div que deve ser irmã da tag header
.mdl-layout__drawer
- Dentro dela ficará os links que aparecem no menu escondido (drawer é gaveta)

Tag com o conteudo principal
.mdl-layout__content

Div com os grids do conteudo
.mdl-grid

Div filha do .mdl-grid
.mdl-cell # indica que é uma célula (padrão de tamanho de 4 colunas)

.mdl-cell--X-col # definição de colunas (precisa do mdl-cell) onde x é o número de colunas de 1 a 12
.mdl-cell--X-col-desktop # coluna específica para desktop
.mdl-cell--X-col-tablet # coluna específica para tablet
.mdl-cell--X-col-phone # coluna específica para phone

.mdl-cell--hide-desktop # esconde celula em desktop
.mdl-cell--hide-tablet # esconde celula em tablet
.mdl-cell--hide-phone # esconde celula em phone

# Rodapé Mega
.mdl-mega-footer

.mdl-mega-footer--top-section # seção do topo do rodapé mega
.mdl-mega-footer--middle-section # seção do meio do rodapé mega
.mdl-mega-footer--bottom-section # seção de baixo do rodapé mega

.mdl-mega-footer--drop-down-section # seção de links com dropdown do rodapé mega
.mdl-mega-footer--heading-checkbox # input do tipo checkbox para controlar o  dropdown em dispositivos menores no rodapé mega
.mdl-mega-footer--heading # cabeçalho ou titulo de bloco do rodapé mega
.mdl-mega-footer--link-list # classe ul dos links de rodapé mega

#Rodapé Mini
Tag Footer rodapé deve se encontrar dentro da div com a classe mdl-layout__content
.mdl-mini-footer

Div dentro da tag footer com a classe .mdl-mini-footer
.mdl-mini-footer--left-section
.mdl-mini-footer--right-section

Classe para adicionar em uma logo
.mdl-logo

Classe para a tag ul pai dos links do rodapé
.mdl-mini-footer--link-list

Badges com atributo data-badge="4" mostrará um badge com número 4 (mostra até 3 caractéres)
.mdl-badge
ex: <span class="mdl-badge" data-badge="4">Inbox</span>

Ícones
Usar underline para os nomes com espaço
.material-icons

Botões
.mdl-button # Classe base do botão
.mdl-js-button # Classe base do botão
.mdl-js-ripple-effect # Efeito ao clique
.mdl-button--fab # Botão redondo
.mdl-button--raised # botão "levantado" # parecer um botão com sombra, etc
.mdl-button--icon # para usar um ícone interno
#Destaques
.mdl-button--primary # cor primária
.mdl-button--accent # cor destaque