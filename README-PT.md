
![analytics image (flat)](https://raw.githubusercontent.com/vitr/google-analytics-beacon/master/static/badge-flat.gif)
![analytics](https://www.google-analytics.com/collect?v=1&cid=555&t=pageview&ec=repo&ea=open&dp=/Plantilla-de-repositorio/readme&dt=&tid=UA-4677001-16)

## Modelo de Documentação de Suporte e Uso de Ferramenta Digital - README.md
Este é um modelo baseado nos padrões do Guia de Publicação de Ferramentas Digitais do BID. Sabemos que não existe um padrão único para a documentação de suporte e uso de ferramentas digitais, mas compilamos essas importantes características que um readme.md deve ter para facilitar seu uso e ampliar seu potencial impacto. Para quaisquer comentários ou recomendações, pedimos que você gere um problema de consulta ou escreva diretamente para code@iadb.org.

## O modelo começa aqui 👇


*Esta ferramenta digital faz parte do catálogo de ferramentas do **Banco Interamericano de Desenvolvimento**. Você pode saber mais sobre a iniciativa do BID em [code.iadb.org](https://code.iadb.org)*

<h1 align="center"> Nome da ferramenta</h1>
<p align="center"> Logo e imagem ou gif da interface principal da ferramenta</p>
<p align="center"><img src="https://www.webdevelopersnotes.com/wp-content/uploads/create-a-simple-home-page.png"/></p>

## Tabela de conteúdos:
---

- [Badges ou escudos](#badges-o-escudos)
- [Descrição e contexto](#description-and-context)
- [Guia do usuário](#user-guide)
- [Guia de instalação](#install-guide)
- [Como contribuir](#how-to-contribute)
- [Codigo de conduta](#código_de_conduta)
- [Autor/es](#autores)
- [Informações adicionais](#informações-adicionais)
- [Licença](#licença)
- [Limitação de responsabilidades - somente BID](#limitação-de-responsabilidades)

## Badges ou escudos
---
É comum em muitos repositórios open source usar badges ou shields para dar visibilidade ao uso de microsserviços, licenças, downloads, etc. Recomendamos revisar a iniciativa https://shields.io/ onde, conforme julgar necessário, você pode gerar badges para seu repositório.

### Exemplos de Badges

- porcentagem de cobertura de código: ![coverage](https://img.shields.io/badge/coverage-80%25-yellowgreen)
- versão de lançamento estável: ![versão](https://img.shields.io/badge/version-1.2.3-blue)
- versão do gerenciador de pacotes: ![gem](https://img.shields.io/badge/gem-2.2.0-blue)
- status de dependências de terceiros: ![dependencies](https://img.shields.io/badge/dependencies-out%20of%20date-orange)
- grau de análise de código estático: ![codacy](https://img.shields.io/badge/codacy-B-green)
- [SemVer](https://semver.org/) observância da versão: ![semver](https://img.shields.io/badge/semver-2.0.0-blue)
- quantidade de [Liberapay](https://liberapay.com/) doações por semana: ![recebe](https://img.shields.io/badge/receives-2.00%20USD%2Fweek-yellow)
- Downloads de pacotes Python: ![downloads](https://img.shields.io/badge/downloads-13k%2Fmonth-brightgreen)
- Classificação da extensão da Chrome Web Store: ![rating](https://img.shields.io/badge/rating-★★★★☆-brightgreen)
- [Uptime Robot](https://uptimerobot.com) porcentagem: ![uptime](https://img.shields.io/badge/uptime-100%25-brightgreen)

### Badges que solicitamos:
---
Na iniciativa Code for Development, solicitamos às equipes que adicionam suas ferramentas ao catálogo que adicionem o badge gerado pelo uso do microsserviço de avaliação de código estático SonarCloud.

O badge fica assim e redireciona para o relatório de avaliação estática do último commit da ferramenta:

[![Status do Quality Gate](https://sonarcloud.io/api/project_badges/measure?project=EL-BID_guia-de-publicacion&metric=alert_status)](https://sonarcloud.io/dashboard?id=EL- BID_guia de publicação)


## Descrição e contexto
---
Este é um arquivo README. Deve conter a documentação de suporte para o uso da ferramenta digital. As seções a seguir são as seções recomendadas que você deve incluir em qualquer ferramenta digital. Você pode baixar este arquivo para servir como modelo.

Certifique-se de iniciar este arquivo com uma breve descrição sobre as funcionalidades e o contexto da ferramenta digital. Seja conciso e direto ao ponto.

## Guia do usuário
---
Ele explica os passos básicos sobre como usar a ferramenta digital. É uma boa seção para mostrar capturas de tela ou gifs que ajudam a entender a ferramenta digital.
 
## Guia de instalação
---
Passo a passo de como instalar a ferramenta digital. Nesta seção é recomendado explicar a arquitetura de pastas e módulos que compõem o sistema.

Dependendo do tipo de ferramenta digital, o nível de complexidade pode variar. Em algumas ocasiões pode ser necessário instalar componentes dependentes da ferramenta digital. Se este for o caso, adicione a próxima seção também.

O guia de instalação deve conter especificamente:
- Os requisitos do sistema operacional para a compilação (versões específicas de bibliotecas, software de gerenciamento de pacotes e dependências, SDKs e compiladores, etc.).
- As dependências próprias do projeto, tanto externas quanto internas (ordem de compilação dos submódulos, configuração de localização de bibliotecas dinâmicas, etc.).
- Etapas específicas para a compilação do código fonte e execução de testes unitários caso o projeto os possua.

### Dependências
Descrição dos recursos externos que geram dependência para a reutilização da ferramenta digital (bibliotecas, frameworks, acesso a bancos de dados e licenças para cada recurso). É uma boa prática descrever as versões mais recentes nas quais a ferramenta digital foi testada.

    Você pode usar este estilo de fonte para diferenciar os comandos de instalação.

## Como contribuir
---
Esta seção explica aos desenvolvedores quais são as formas usuais de enviar uma nova solicitação pull de código, como declarar bugs na ferramenta e quais guias de estilo usar ao escrever mais linhas de código. Você também pode fazer uma lista de pontos que podem ser melhorados em seu código para criar ideias de melhoria.

## Código de conduta
---
O código de conduta estabelece as normas sociais, regras e responsabilidades que indivíduos e organizações devem seguir ao interagir de qualquer forma com a ferramenta digital ou sua comunidade. É uma boa prática criar
