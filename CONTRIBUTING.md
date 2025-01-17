# Contributing to Beauty Salon

Obrigado por considerar contribuir para o projeto! Este guia ajudará você a configurar o ambiente de desenvolvimento e seguir as diretrizes para garantir que as contribuições sejam consistentes e de alta qualidade.

## Pré-requisitos

Antes de começar, certifique-se de ter as seguintes ferramentas instaladas:
- [Node.js](https://nodejs.org/) (versão 18 ou superior)
- [npm](https://www.npmjs.com/) ou [yarn](https://yarnpkg.com/)
- [Git](https://git-scm.com/)

## Diretrizes para Commits
Estamos usando Conventional Commits para padronizar as mensagens de commit. Isso ajuda a manter um histórico de mudanças limpo e facilita a automação de processos como geração de changelogs.

### Formato de Commit
Cada mensagem de commit deve seguir o formato:

```
<tipo>[escopo opcional]: <descrição>

[corpo opcional]

[rodapé opcional]

Exemplo: feat: atualizar contributing do projeto
---
PS: O escopo, corpo e rodapé são opcionais e recomendamos não serem usados por agora
```

### Tipos aceitos

- build
- chore
- ci
- docs
- feat
- fix
- perf
- refactor
- revert
- style
- test

## Ferramentas de Verificação
Este projeto usa o commitlint para validar as mensagens de commit. Se uma mensagem não seguir o formato correto, o commit será rejeitado.
Além dele, também está sendo usado o **husky** com o pre-commit. Por enquanto, o único script do pre-commit é o de lint.

## Criando uma Pull Request

- Faça um clone do repositório
- Crie uma nova branch a partir da branch de **develop**
    - git checkout -b minha-funcionalidade
        - *PS: Para mantermos o padrão de nomenclatura nas branchs, recomendamos usar o type com uma breve descrição do que está sendo feito. Descrição essa com duas, no máximo três palavras. Exemplo: bug/corrigir-bug ; feat/adicionar-navbar*
- Adicione suas alterações e faça commits seguindo as diretrizes acima.
- Envie as alterações para o remoto:
    - git push origin minha-funcionalidade
- Abra um Pull Request no repositório principal para a branch **develop**
- Aguarde o code review dos owners do projeto e seja feliz!

Obrigado por contribuir! 🎉