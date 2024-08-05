Funcionalidade: Card de curso

Eu como usuária da aplicação,
Gostaria de visualizar as informações dos cursos em cards,
Porque quero poder rapidamente identificar os cursos cadastrados e acessar os detalhes  sobre aqueles que me interessam.

Regras de negócio:

RN1 - Atualização em tempo real, garantindo que as informações apresentadas sejam sempre atuais.

RN2 - Exibição correta de acordo com os dados inseridos para criação do curso

RN3 - layout consistente, independentemente do tamanho do conteúdo ou das imagens.

RN4 - deve ser possível excluir um curso diretamente a partir do card correspondente. A funcionalidade de exclusão deve estar claramente visível e acessível.

RN5- Ao clicar no card de um curso, deve haver um redirecionamento para a visualização de detalhes do curso;

Critérios de aceitação: 

CA1 - Dado que estou visualizando  os cards de curso
    - Quando há uma atualização nas informações dos cursos
    - Então eu devo ver as informações refletidas em tempo real, sem necessidade de atualizar manualmente a página

CA2 - Dado que estou visualizando  os cards de curso
    - Então eu devo ver as informações corretas e precisas conforme os dados inseridos durante a criação do curso

CA3 - Dado que estou visualizando  os cards de curso
    - Então o layout do card deve ser consistente, mantendo a mesma aparência e organização, independentemente do tamanho do conteúdo ou das imagens

CA4 - Dado que estou visualizando  os cards de curso
    - Quando clico no botão de excluir curso 
    - Então o curso deve ser removido imediatamente 
    - E uma mensagem de confirmação deve ser exibida para garantir que a ação foi realizada com sucesso

CA5 - Dado que estou visualizando  os cards de curso
    - Quando eu clico no card do curso
    - Então eu devo ser redirecionado para uma página ou modal que exibe os detalhes completos do curso selecionado