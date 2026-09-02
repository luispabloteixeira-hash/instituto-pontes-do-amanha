# Experiência Prática I — Fundamentos e estruturação

## Identificação do projeto

**Título:** Instituto Pontes do Amanhã — Plataforma digital para uma ONG  
**Curso:** Engenharia de Software  
**Disciplina:** Desenvolvimento Front-End para Web  
**Estudante:** identificação preservada na versão pública

## Estrutura semântica e hierarquia

O projeto utiliza elementos semânticos do HTML5 para organizar a informação e ampliar a acessibilidade e a compreensão por mecanismos de busca. O cabeçalho contém a identidade e a navegação principal; o elemento `main` concentra o conteúdo exclusivo de cada página; as seções possuem títulos associados; os projetos são apresentados como artigos independentes; informações complementares aparecem em `aside`; e o rodapé reúne a identificação acadêmica do site.

## Página inicial

O arquivo `index.html` apresenta a organização fictícia, sua missão, indicadores de impacto e formas de participação. A hierarquia começa em um único `h1` e prossegue com seções identificadas por `h2`. Os links conduzem às páginas de projetos e cadastro.

## Projetos sociais

O arquivo `projetos.html` apresenta três iniciativas: Aprender Juntos, Conexão Cidadã e Rede que Acolhe. Cada projeto possui descrição, área de atuação e características objetivas, mantendo uma estrutura coerente e reutilizável.

## Formulário de cadastro

O arquivo `cadastro.html` agrupa os campos em dados pessoais, endereço e forma de participação. Foram empregados `label`, `fieldset`, `legend`, atributos de preenchimento automático, campos obrigatórios e tipos apropriados para e-mail e telefone.

## Validações nativas e máscaras

CPF, telefone e CEP possuem expressões regulares no atributo `pattern`, limites de caracteres, teclado numérico em dispositivos móveis e máscaras implementadas em JavaScript. O formulário demonstra a validação sem transmitir dados pessoais.

## Validação de conformidade I — HTML

Os três documentos foram processados por um analisador HTML sem erros estruturais. Antes do envio acadêmico, recomenda-se anexar também capturas do W3C Markup Validation Service mostrando os arquivos sem erros.

## Validação de conformidade II — acessibilidade

Foram incorporados link de salto, navegação identificada, foco visível, mensagens com `aria-live`, ordem hierárquica de títulos e suporte a redução de movimento. Recomenda-se registrar a auditoria final do Lighthouse após a publicação.

## Revisão da experiência prática

O resultado atende ao desafio de criar uma presença digital clara e organizada para uma organização do terceiro setor. A separação em três páginas facilita a navegação e a manutenção, enquanto a semântica e as validações tornam a solução mais confiável.

## Reflexão final

A atividade demonstrou que HTML semântico não serve apenas para organizar visualmente uma página. Ele melhora a acessibilidade, a indexação e a manutenção do código. A construção do formulário também mostrou como validações nativas e máscaras podem reduzir erros de preenchimento sem substituir cuidados com privacidade e validação no servidor.

## Autoavaliação

Considero que alcancei os objetivos propostos ao estruturar as páginas, organizar a navegação e desenvolver um formulário coerente com o contexto da ONG. Como aprimoramento futuro, pretendo realizar testes com usuários e integrar o formulário a um serviço seguro de armazenamento, respeitando a LGPD.
