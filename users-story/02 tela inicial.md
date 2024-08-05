Funcionalidade: Tela inicial

Eu como usuária da aplicação,
Gostaria de acessar a página inicial,
Porque eu quero visualizar a lista de cursos disponíveis, acessar outras funcionalidades e encontrar informações importantes sobre a instituição e suporte.


Regras de negócio:

RN1 - Deve possuir um campo com a listagem dos cursos

RN2 - Deve possuir um título princípal sinalizando o que se trata o conteúdo da tela

RN3 - Caso não haja nenhum curso listado, deve imprimir essa informação na tela ao usuário e oferecer a opção de adicionar um novo curso.

RN4 - Deve possuir um header que permiti acesso a demais   funcionalidades da aplicação 

RN5 - Deve possuir um footer contendo informações instituicionais como detalhes de contato, endereço da instituição e links para políticas e termos de uso.

RN6 - Toda ação realizada na tela, como a adição, edição ou exclusão de um curso, deve gerar uma mensagem de retorno clara para o usuário. 

RN7: Ao clicar no botão "Cadastrar Curso", o usuário deve ser redirecionado para a página de cadastro do curso.

RN8: Ao clicar no botão "Listar cursos", o usuário deve ser redirecionado para a página de Lista de  cursos.

Critérios de aceitação:


CA1 - Dado que estou na tela inicial da aplicação 
    - Quando eu visualizo a página
    - Então eu devo ver um campo com a lista de cursos disponíveis, se houver algum cadastrado.

CA2 - Dado que estou na tela inicial da aplicação 
    - Quando eu visualizo a página
    - Então eu devo ver um título principal claro e descritivo que sinalize o propósito da tela

CA3 - Dado que estou na tela inicial da aplicação 
    - E não há cursos listados
    - Então eu devo ver uma mensagem informando que não há  cursos cadastrados  no momento
    - E devo ver uma opção ou botão para adicionar um novo curso diretamente na tela.

CA4 - Dado que estou na tela inicial da aplicação 
    - Então eu devo ver um header que me permita acessar outras funcionalidades da aplicação

CA5 - Dado que estou na tela inicial da aplicação 
    - Então eu devo ver um footer contendo informações institucionais

CA6 - Dado que estou na tela inicial da aplicação
    - Quando eu clico no botão Cadastrar curso
    - Então devo ser redirecionado para a tela de 
    Cadastrar curso


