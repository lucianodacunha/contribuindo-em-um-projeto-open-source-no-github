# Contribuindo em um Projeto Open Source no GitHub

## Objetivo Geral e Percurso

- Aprender o básico sobre contribuição no Github.
- O que são e como contribuir em projetos Open Source.
- Desenvolver e Enviar uma contribuição.
- Dicas e materiais de apoio.

## O que são e como contribuir em projetos Open Source.

- Projeto de código aberto
- Exemplos: Linux, Roadmpas DIO

## Formas de contrubuição em um projeto

- Relatar algum bug identificado
- Sugerir melhorias
- Documentação
- Divulgar/Apoiar

### Enviando contribuições

- Issues: podem ser adicionadas diretamenta no repositório do projeto.
- Pull requests: pode ser enviados através de forks do projeto.

## Criando templates para issues

- Settings > Features > Check Issues > Set up templates
- Add templates > Custom templates > Preview and Edit
- Defina:
  - Template name, ex. Community challenge
  - About, ex. Crie uma issue sobre a ..
  - Template content:
    - **Sugestão**
      - Descreva aqui sua sugestão
    - **Descrição**
      - Descrição
    - **Links**
      - Links
  - Issue default title: [Adicione um prefixo utilizado no título]
  - Label
- Salve o template > Propose changes > Commit changes

Será criado um novo template na pasta .github
Quando alguém criar uma nova issue, o novo template estará entre os sugeridos.

## Conectando o repositório local ao repositório original

Depois de clonar localmente o repositório `forkado`, adicione um link remoto para um upstream:

```
$ git remote add upstream https://github.com/elidianaandrade/dio-lab-open-source.git
```

Para atualizar com o repositório original, execute:

```
$ git pull upstream main
```

Outra forma de atualizar-se com o repositório remoto, é atualizar primeiramente o fork, e depois realizar um pull com o origin.

