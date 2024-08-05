

### FUNCIONALIDADE: LISTAGEM DE CURSOS


    Eu como usuária da aplicação
    Gostaria de visualizar a lista de cursos na tela inicial
    Porque isso me permitirá ver os cursos já cadastrados, explorar suas informações e acessar detalhes importantes sobre cada um deles.


**REGRAS DE NEGÓCIO:**

**RN1** - Exibição de  todos os cursos criados, refletindo com precisão a quantidade total de cursos cadastrados no sistema.

**RN2** - Atualização em tempo real, garantindo que as informações apresentadas sejam sempre atuais.

**RN3** - Suporta paginação ou rolagem infinita para cursos em excesso, a fim de manter a performance do sistema e proporcionar uma experiência de usuário fluida.

**RN4** - Ordenação  e filtragem com base em critérios como nome, data de criação ou instrutor, se aplicável, para facilitar a busca e a organização dos cursos.

**RN5** - O grid onde os cursos são exibidos deve ser bem estruturado, com uma disposição de colunas e linhas adequada que permita uma visualização clara e fácil dos cursos.

**RN6** - No ordenamento da página , os últimos cursos criados (os mais recentes), devem estar no início da listagem dos cursos

**CRITÉRIOS DE ACEITAÇÃO:**

    CA1 - Dado que estou visualizando a lista de cursos
        - Então devo ver todos os cursos cadastrados exibidos corretamente, refletindo a quantidade total de cursos criados no sistema.

    CA2 - Dado que estou visualizando a lista de cursos
        - Quando há uma adição ou remoção de cursos
        - Então a lista de cursos deve ser atualizada em tempo real para refletir essas mudanças.

    CA3 - Dado que estou visualizando a lista de cursos
        - E existem muitos cursos cadastrados
        - Então a lista deve ter paginação para exibir os cursos sem comprometer a performance do sistema.

    CA4 - Dado que estou visualizando a lista de cursos
        - Quando aplico uma ordenação ou filtragem na lista de cursos
        - Então a lista deve ser ajustada conforme os critérios selecionados

    CA5 - Dado que estou visualizando a lista de cursos
        - Então os cursos devem estar organizados em um grid bem estruturado, com uma disposição de colunas e linhas adequada que permita uma visualização clara e fácil dos cursos.



