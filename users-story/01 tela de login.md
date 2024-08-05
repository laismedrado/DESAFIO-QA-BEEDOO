## Funcionalidade: Tela de login

    Eu como usuário da aplicação,
    Gostaria de acessar a tela de login,
    Porque eu quero inserir minhas credenciais e ter acesso às funcionalidades da aplicação, pois apenas usuários com autenticação correta podem utilizar essas funções.

**Regras de negócio:**

**RN1** - Deve conter um campo de entrada para a inserção do e-mail, para o  usuário digitar seu e-mail;

**RN2** - Deve conter um campo de entrada para inserção da senha, para o usuário digitar sua senha;

**RN3** - Deve conter um botão de login ,  que ao ser clicado, valide as credenciais inseridas e redirecionar o usuário para a tela principal da aplicação após a autenticação bem-sucedida. 

**RN4** - Deve haver um link de recuperação de senha, que redireciona o usuário para o processo de recuperação de senha em caso de esquecimento.

**RN5** - Deve haver um link, que redirecione novos usuários para a tela de registro para criar uma nova conta.

**RN6** - Deve conter um texto de boas vindas, para criar uma experiência mais acolhedora e amigável.

**RN7** - deve conter um subtítulo, que esclareça o propósito da tela e informe aos usuários sobre a necessidade de autenticação para acessar a aplicação;


**Critérios de aceitação:**

        CA1 - Dado que estou  na tela de login da aplicação 
            - Quando eu visualizo o campo de entrada para e-mail
            - Então consigo digitar o email 

        CA2 - Dado que estou  na tela de login da aplicação 
            - Quando eu visualizo o campo de entrada para senha
            - Então consigo digitar a senha

        CA3 - Dado que estou na tela de login da aplicação,
            - Quando insiro um e-mail e uma senha e clico no botão de login,
            - Então o sistema deve validar as credenciais:
            - E se forem válidas  devo ser redirecionada para a tela inicial 
            - E se forem inválidas devo ser sinalizada e permanecer na tela de login

        CA4 - Dado que estou na tela de login da aplicação 
            - Quando eu clico no link de recuperação de senha
            - Então eu devo ser redirecionado para a página de recuperação de senha;

        CA5 - Dado que estou na tela de login da aplicação 
            - Quando eu clico no link para novo cadastro
            - Então eu devo ser redirecionado para a página de registro, onde posso criar um novo cadastro.

        CA6 - Dado que estou na tela de login da aplicação 
            - Quando eu visualizo a tela
            - Então eu devo ver um texto de boas-vindas 

        CA7 - Dado que estou na tela de login da aplicação 
            - Quando eu visualizo a tela
            - Então eu devo ver um subtítulo que esclareça o propósito da tela 
