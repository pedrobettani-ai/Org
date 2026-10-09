# Organograma PhizChat

Organograma interativo das BUs PhizChat (Brasil e China), publicado pelo GitHub Pages.

## Como abrir

Acesse o endereço do GitHub Pages deste repositório. O site abre em modo apresentação, na versão mais recente. O menu **Versão** troca entre as versões publicadas, e o link de cada versão pode ser compartilhado direto.

## Como editar

1. Clique em **Editar**.
2. Edite os cards (✎), arraste um card sobre outro para mudar o reporte e use **Inserir** para adicionar formas, selos, setas, conectores e molduras. Cada forma tem cor, espessura, tipo de traço e texto no painel lateral.
3. Defina as BUs de cada card no painel do card. **Gerenciar BUs** cria, renomeia ou muda a cor das BUs.
4. Para organizar o time de um gestor, arraste um card: soltar **em cima ou embaixo** de um colega empilha na mesma coluna, soltar **nas laterais** abre uma nova coluna e soltar **no centro** de um card faz a pessoa reportar a ele. O botão ⇅/⇄ no card do gestor alterna o time inteiro entre vertical e horizontal.
5. **+ Bloco** cria um bloco de simulação em branco. **Duplicar como simulação**, no painel do card, copia o time de alguém para um bloco novo. Arraste a faixa de título do bloco para posicioná-lo no canvas, e use ⋯ para renomear ou excluir.

## Visão por BU

Escolha **Por BU** e a BU (ou **Todas**, que coloca as BUs lado a lado). Aparece **só quem tem o rótulo da BU**, num organograma conectado:

- Cada pessoa se liga ao chefe mais próximo que também tem o rótulo (linha contínua).
- Quem fica sem chefe na BU se liga ao seu par de relação funcional na BU (linha pontilhada) ou, se não tiver, ao líder do seu lado, Brasil ou China (linha tracejada).
- O card mostra o chefe real ("↳ reporta a …") sempre que a ligação na BU for diferente do reporte.
- Para ajustar uma ligação, use "Visão por BU · ligar a" no painel do card.

A visão é calculada a partir dos rótulos: quem você rotular passa a aparecer automaticamente. Quem tem duas BUs aparece nas duas.

## Opções de exibição (menu Exibir)

- **Visão matricial:** mostra cada card junto do par definido em "Visão matricial · exibir junto de", com linha pontilhada. O reporte real aparece no card.
- **Unir blocos:** junta Brasil, China e simulações num desenho só, sem molduras.

## Como publicar uma nova versão

1. No modo edição, clique em **Gerar versão** e dê um nome (ex.: "To be Q1 2027"). A página baixa um arquivo `.json`.
2. Abra a pasta [`versoes`](versoes) neste repositório, use **Add file → Upload files**, arraste o arquivo e clique em **Commit changes**.
3. Em um ou dois minutos a versão aparece no menu **Versão** para todo mundo.

Para remover uma versão, apague o arquivo dela na pasta `versoes`.

## Atenção

O repositório e o site são públicos: qualquer pessoa com o link vê nomes, cargos e vagas.
