# Experiência Prática III — Interatividade e funcionalidades

## Fundamentos e organização

O arquivo `assets/js/app.js` concentra comportamentos progressivos e verifica a existência dos elementos antes de associar eventos. Dessa forma, o mesmo script pode ser reutilizado nas três páginas.

## Controle de eventos

O evento de clique controla o menu móvel e mantém `aria-expanded` sincronizado. Eventos de entrada formatam CPF, telefone e CEP enquanto o usuário digita. O evento de envio impede uma submissão fictícia e executa a validação local.

## Interatividade

As máscaras removem caracteres inválidos, limitam o tamanho e aplicam a pontuação correspondente. Quando o formulário está incompleto, a validação nativa destaca o problema; quando está válido, uma mensagem acessível confirma a demonstração sem enviar informações.

## Modularização e refinamento

As responsabilidades estão separadas em funções pequenas: extração de dígitos, máscaras específicas, controle de navegação e validação. Não há dependências externas, o que facilita testes, manutenção e publicação.

## Reflexão

A atividade evidenciou a importância de associar JavaScript a uma estrutura HTML funcional. A página continua apresentando conteúdo sem o script, enquanto a camada de comportamento acrescenta conveniência e feedback.

## Autoavaliação

As funcionalidades atendem ao escopo proposto e evitam coleta real de dados. Como continuidade, o código pode receber testes unitários e integração com uma API segura.
