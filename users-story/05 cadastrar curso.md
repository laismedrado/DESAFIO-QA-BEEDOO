Funcionalidade: Cadastrar curso

Eu como usuário da aplicação
Gostaria de cadastrar um novo curso 
Porque quero  adicionar novas ofertas à plataforma


Regras de negócio:

RN1: Ao clicar no botão Listar cursos na página , estando na página de cadastro, devo ser redirecionada pra página inicial da aplicação

RN2: A página de cadastro de curso deve possuir um título principal que sinalize claramente o conteúdo da tela.

RN3: Deve haver um campo obrigatório para a inserção do nome do curso, contendo o atributo `aria-label="Nome do curso"`.

RN4: Deve haver um campo obrigatório para a inserção da descrição do curso, com validação para um número mínimo e máximo de caracteres, contendo o atributo `aria-label="Descrição do curso"`.

RN5: Deve haver um campo obrigatório para a inserção do nome do instrutor, contendo o atributo `aria-label="Instrutor"`.

RN6: Deve haver um campo para a inserção da URL da imagem do curso, contendo o atributo `aria-label="URL da imagem de capa"`.

RN7: Deve haver campos obrigatórios para a inserção das datas de início e término do curso, no formato brasileiro (DD/MM/YYYY), contendo os atributos `aria-label="Data de início"` e `aria-label="Data de fim"`.

RN9: Deve haver um campo de input do tipo número onde o usuário pode especificar a quantidade de vagas, contendo o atributo `aria-label="Número de vagas"`.

RN10: Deve haver um campo de seleção (select) que permite ao usuário escolher se o curso é online ou presencial, contendo o atributo `aria-label="Tipo de curso"`.

RN11: Deve haver um botão "Cadastrar Curso" que, ao ser clicado, realiza o cadastro do curso na aplicação.


Critérios de aceitação:

CA1 - Dado que estou na tela de Cadastro de cursos
    - Quando eu clico no botão Listar curso
    - Então devo ser redirecionada para a tela inicial da aplicação

CA2 - Dado que estou na tela de cadastro de curso, 
    - ENTÃO eu devo ver um título principal claro e descritivo que sinalize o propósito do conteúdo da tela

CA3 - Dado que estou na tela de cadastro de curso
    - Quando visualizo o campo de input com o arial-label: "Nome do curso"
    - Então consigo adicionar o nome do curso

CA4 - Dado que estou na tela de cadastro de curso
    - Quando visualizo o campo de input com o arial-label: "Descrição do curso"
    - Então consigo adicionar a descrição do curso
  
CA5 - Dado que estou na tela de cadastro de curso
    - Quando adiciono uma descrição ao campo,
    - Então o campo deve validar o número de caracteres inseridos, garantindo que a descrição atenda aos requisitos de mínimo e máximo de caracteres especificados.
    - E uma mensagem de erro deve ser exibida se a descrição não atender ao número mínimo ou máximo de caracteres permitidos.

CA6 - Dado que estou na tela de cadastro de curso
    - Quando visualizo o campo de input com o arial-label: "URL da imagem de capa"
    - Então consigo adicionar a URL da imagem

CA7 - Dado que estou na tela de cadastro de curso
    - Quando visualizo o campo de input com o arial-label: "Instrutor"
    - Então consigo adicionar o nome do instrutor do curso

CA8 - Dado que estou na tela de cadastro de curso
    - Quando visualizo o campo de input com o arial-label: "Data de início"
    - Então consigo adicionar a data

CA9 - Dado que estou na tela de cadastro de curso
     - Quando visualizo o campo de input com o arial-label: "Data de fim"
     - Então consigo adicionar a data

CA10 - Dado que estou na tela de cadastro de curso
     - Quando visualizo o campo de input com o arial-label: "Número de vagas"
     - Então consigo adicionar o número de vagas

CA11 - Dado que estou na tela de cadastro de curso
     - Quando visualizo o campo de input com o arial-label: "Tipo de curso"
     - Então consigo adicionar o tipo de curso

CA12  - Dado que estou na tela de cadastro de curso
      - Quando clico no botão "Cadastrar curso"
      - Então o curso deve ser cadastrado
      - E uma mensagem de sucesso deve ser impressa para o usuário
      - E todos os campos de inputs devem ser limpos 
      - E deve se permanecer na mesma tela

CA13  - Dado que estou na tela de cadastro de curso
      - Quando clico no botão "Cadastrar curso"
      - Então a chamada POST para criar o curso deve ser feita corretamente


