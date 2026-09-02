# Experiência Prática II — Estilização e layouts

## Design system

O design system está centralizado nas variáveis do arquivo `assets/css/style.css`. A paleta combina verde institucional, azul-escuro, tons claros e amarelo de destaque. Espaçamentos, raio, sombra e cores são reutilizados para manter consistência.

## Estrutura responsiva

Foram usados Grid e Flexbox na seção principal, cartões, navegação e formulário. Em telas de até 760 pixels, as estruturas passam a uma coluna e a navegação é substituída por um menu expansível.

## Componentes visuais

O projeto inclui botões primário e secundário, cartões, etiquetas, bloco de chamada, indicador de impacto, cabeçalho fixo e mensagens de estado. Os componentes compartilham propriedades e podem ser reutilizados nas três páginas.

## Navegação

O menu destaca a página atual por `aria-current`. Em dispositivos móveis, o botão informa seu estado por `aria-expanded`. O link “Pular para o conteúdo” auxilia usuários de teclado e leitores de tela.

## Formulário estilizado

Campos, seletores e área de texto possuem rótulos visíveis, foco destacado, dimensões adequadas e organização em grupos. A composição se adapta a telas menores sem rolagem horizontal.

## Reflexão

A estilização foi tratada como parte da comunicação e da usabilidade, e não apenas como decoração. Um sistema visual consistente facilita a compreensão da interface e reduz o esforço de manutenção do CSS.

## Autoavaliação

O projeto apresenta consistência visual, responsividade e componentes reutilizáveis. Como evolução, podem ser realizados testes de contraste automatizados e avaliações com diferentes tamanhos de tela.
