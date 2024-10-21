# Guia de Contribuição para o Projeto Organizo

Olá! Estamos muito felizes que você está interessado em contribuir para o Organizo. Este documento fornecerá as diretrizes para contribuir com este projeto.

## Índice

- [Guia de Contribuição para o Projeto Organizo](#guia-de-contribuição-para-o-projeto-organizo)
  - [Índice](#índice)
  - [Código de Conduta](#código-de-conduta)
  - [Como Posso Contribuir?](#como-posso-contribuir)
    - [Reportando Bugs](#reportando-bugs)
    - [Sugerindo Melhorias](#sugerindo-melhorias)
    - [Seu Primeiro Código Contribuído](#seu-primeiro-código-contribuído)
  - [Estilo de Código](#estilo-de-código)
  - [Processo de Commit](#processo-de-commit)
  - [Processo de Pull Request](#processo-de-pull-request)

## Código de Conduta

Este projeto e todos os participantes dele são governados pelo [Código de Conduta do Organizo](CODE_OF_CONDUCT.md). Ao participar, espera-se que você cumpra este código. Por favor, reporte comportamento inaceitável para [EMAIL_DO_MANTENEDOR].

## Como Posso Contribuir?

### Reportando Bugs

Esta seção orienta você através da submissão de um relatório de bug. Seguir estas diretrizes ajuda os mantenedores e a comunidade a entender seu relatório, reproduzir o comportamento e encontrar relatórios relacionados.

Antes de criar relatórios de bugs, por favor verifique [esta lista](LINK_PARA_LISTA_DE_BUGS_CONHECIDOS) pois você pode descobrir que não precisa criar um. Quando você está criando um relatório de bug, por favor inclua o máximo de detalhes possível.

### Sugerindo Melhorias

Esta seção orienta você através da submissão de uma sugestão de melhoria para o Organizo, incluindo recursos completamente novos e melhorias menores nas funcionalidades existentes.

### Seu Primeiro Código Contribuído

Não sabe por onde começar contribuindo para o Organizo? Você pode começar olhando para issues com as tags `beginner` e `help-wanted`:

* Issues com a tag `beginner` devem exigir apenas algumas linhas de código e um ou dois testes.
* Issues com a tag `help-wanted` são issues um pouco mais envolventes que as de `beginner`.

## Estilo de Código

Para manter a consistência no código do Organizo, seguimos algumas diretrizes de estilo:

1. Usamos o [Prettier](https://prettier.io/) para formatação automática de código.
2. Seguimos o [Airbnb JavaScript Style Guide](https://github.com/airbnb/javascript) para JavaScript.
3. Para React, seguimos as [boas práticas oficiais do React](https://reactjs.org/docs/thinking-in-react.html).

Por favor, certifique-se de que seu código esteja de acordo com estas diretrizes antes de submeter um pull request.

## Processo de Commit

Seguimos a [Convenção de Commits](https://www.conventionalcommits.org/) para nossas mensagens de commit. Isso nos ajuda a manter um histórico de commits limpo e facilita a geração automática de changelogs.

A estrutura de uma mensagem de commit deve ser assim:

```
<tipo>[escopo opcional]: <descrição>

[corpo opcional]

[rodapé(s) opcional(is)]
```

O `tipo` deve ser um dos seguintes:

- `feat:` uma nova feature
- `fix:` uma correção de bug
- `docs:` mudanças na documentação
- `style:` formatação, ponto e vírgula faltando, etc; sem mudança de código
- `refactor:` refatoração do código de produção
- `test:` adição de testes, refatoração de testes; sem mudança de código de produção
- `chore:` atualização de tarefas de build, configurações de gerenciamento de pacotes, etc; sem mudança de código de produção

Por exemplo:

```
feat(tarefas): adiciona opção para definir prioridade

Adiciona um campo de seleção para definir a prioridade da tarefa (alta, média, baixa).

Closes #123
```

## Processo de Pull Request

1. Certifique-se de que quaisquer dependências de instalação ou build sejam removidas antes do fim da camada ao fazer um build.
2. Atualize o README.md com detalhes das mudanças na interface, isso inclui novas variáveis de ambiente, portas expostas, locais de arquivos úteis e parâmetros de contêiner.
3. Aumente os números de versão em quaisquer arquivos de exemplo e o README.md para a nova versão que este Pull Request representaria. O esquema de versionamento que usamos é [SemVer](http://semver.org/).
4. Você pode mergear o Pull Request uma vez que você tenha a aprovação de dois outros desenvolvedores, ou se você não tem permissão para fazer isso, você pode solicitar ao segundo revisor para mergear para você.

Obrigado por contribuir para o Organizo!
