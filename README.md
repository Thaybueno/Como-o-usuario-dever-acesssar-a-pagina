Valor: Autenticação do usuário na loja virtual é importante para que os clientes possam se cadastrar na plataforma com segurança e fazer pedidos. essa funcionalidade visa unificar fluxos de acesso ao site permitindo que o usuário possa se cadastrar, fazer login ou redefinir senha na loja virtual.

Narrativa do usuário:

          Como cliente 

          Eu quero acessar a pagina de login do usuário

          Para visualizar opçoes de login, cadastro e redefinição de senha na loja virtual

Requisitos :

Atores: Clientes

Interfaces: Ver documentos em anexo da UI/UX

Dados:          
        Criação de bancos de dados/tabelas para armazenar informações dos clientes cadastrados.

        Criação de API para integração com font- end e banco de criado.

        Criação de tela de login para permitir que o usuário acesse a pagina de login e a pagina de cadastro de usuário.

Plataforma/ Ambientes:

       WEB/ Web mobile. 

        Devem ser configurados ambiente +pipelines para desenvolver homologação de usuário, homologação QA e produção. 

Critérios de aceite:

      Usuário deverá visualizar formulário para fazer login e entrar na loja virtual.

      Usuário devera visualizar botão para acessar tela de cadastro do sistema.

      Usuário devera visualizar botão para acessar a tela “Esqueci minha senha”.


Cenário: 
  Cliente sem cadastro deseja criar conta 
  
  Dado que o cliente está na tela de login 
  
  E não está cadastrado no sistema 
  
  Quando clicar em criar conta 
  
  Então será redirecionado para uma tela de criação de conta nao existente 
  
 Cenário: 
 Cliente sem cadstro tenta fazer login 
 
Dado que o cliente está na tela de login 

E adicione um nome de usuário nao cadastrado 

Quando clicar em criar conta 

Então uma mensagem surgirá avisando que a conta não existe 

Cenário:
Cliente com cadastro informa dados incorretos de acesso

Dado que o cliente está na tela de login 

E adicione um nome de usuário correto 

Mas escreva uma senha incorreta 

Quando clicar em criar conta 

Então virá uma mensagem avisando que a senha está incorreta 
