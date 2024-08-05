### FUNCIONALIDADE: CARD DE CURSO

    Eu como usuária da aplicação,
    Gostaria de visualizar as informações dos cursos em cards,
    Porque quero poder rapidamente identificar os cursos cadastrados e acessar os detalhes  sobre aqueles que me interessam.

**REGRAS DE NEGÓCIO:**

**RN1** - Atualização em tempo real do card, garantindo que as informações apresentadas sejam sempre atuais e sem necessidade de atualização manual 

**RN2** - Exibição correta dos dados de acordo com os que foram inseridos para a  criação do curso

**RN3** - Layout consistente, independentemente do tamanho do conteúdo ou das imagens.

**RN4** - Deve ser possível excluir um curso diretamente a partir do card correspondente. A funcionalidade de exclusão deve estar claramente visível e acessível.

**RN5**- Ao clicar no card de um curso, deve haver um redirecionamento para a visualização de detalhes do curso;

**CRITÉRIOS DE ACEITAÇÃO:**

    CA1 - Dado que estou visualizando  os cards de curso
        - Quando há uma atualização nas informações dos cursos
        - Então eu devo ver as informações refletidas em tempo real, sem necessidade de atualizar manualmente a página

    CA2 - Dado que estou visualizando  os cards de curso
        - Então eu devo ver as informações corretas e precisas conforme os dados inseridos durante a criação do curso

    CA3 - Dado que estou visualizando  os cards de curso
        - Então o layout do card deve ser consistente, mantendo a mesma aparência e organização, independentemente do tamanho do conteúdo ou das imagens

    CA4 - Dado que estou visualizando  os cards de curso
        - Quando clico no botão de excluir curso 
        - Então uma mensagem perguntando a confirmação da ação deve ser emitida
        - E clicando em confirmo
        - Então uma chamada DELETE é executada com sucesso
        - E o curso deve ser removido imediatamente 
        - E uma mensagem de confirmação deve ser exibida ao usuário para garantir que a ação foi realizada com sucesso

    CA5 - Dado que estou visualizando  os cards de curso
        - Quando eu clico no card do curso
        - Então eu devo ser redirecionado para uma página ou modal que exibe os detalhes completos do curso selecionado
