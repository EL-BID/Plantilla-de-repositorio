### Esta edição faz parte do processo de revisão dos Laboratory Code Squads novembro 2020 da iniciativa Code for the development of @EL-BID.

## Issue de revisão de avaliação técnica:

Ao comparar as informações apresentadas no repositório oficial com os campos solicitados no modelo README.md, encontramos os seguintes pontos a melhorar:

- [ ] Adicione o microsserviço de relatório de avaliação estática do código Sonarcloud, levando em consideração que as condições ideais de relatório são:

      1 Ausência de falhas estruturais
      2 Menos de 25% de linhas duplicadas
      3 Menos de 10 problemas críticos
      4 Mais de 50% das classes, interfaces e métodos documentados
      5 Dúvida técnica inferior a 30 dias
      6 Cobertura de teste superior a 25%
      
      Isso é validado automaticamente quando você executa o relatório de confirmação mais recente do repositório.
      
- [ ] Adicione o badge no markdown deste serviço visível no readme.md.

- [ ] Adicione um microsserviço de integração contínua de código, recomendamos o Travis CI (opcional).

- [ ] Adicione o badge de microsserviço de integração contínua de código visível no readme.md. A compilação deve estar em estado de passing. (opcional).

- [ ] Atualize a versão de todas as dependências.

## Caso de uso deste modelo:
https://github.com/datauy/ElijoEstudiar/issues/103
