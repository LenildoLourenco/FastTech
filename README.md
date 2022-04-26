# FastTech

## Empresa de vendas FastTech

A empresa FastTech precisa de uma consultória que desenvolva um sistema de gestão de vendas, para controlar melhor todo o fluxo da sua empresa.

### 01 - Ações comuns

- Todas as entidades devem ter um CRUD.
- As entidades não podem ser excluídas, apenas desabilitadas.

### 02 - Controle de vendas

#### Vendedor

- O vendedor pode obter relatórios por data das suas vendas.
- O vendedor pode adicionar/cadastrar uma venda.
- O vendedor pode editar uma venda.
- O vendedor pode cancelar uma venda.

#### Gerente

- O gerente pode obter relatórios por data das vendas de um ou mais vendedores do setor.
- O gerente pode adicionar/cadastrar uma venda para um determinado vendedor.
- O gerente pode editar uma venda de um vendedor.
- O gerente pode cancelar uma venda de um vendedor.

#### Administrador

- O administrador do sistema, não pode manipular recursos de vendas.

### 03 - Gerenciamento do setor

#### Vendedor

- Não pode realizar alterações no setor.

#### Gerente

- Somente gerentes podem cadastrar vendedores no setor.
- Somente gerentes podem transferir vendedores de setor.
- Um vendedor não pode ser excluído de um setor.
- Um vendedor pode ser transferido de setor, mas as suas vendas ainda farão parte do setor em que foram cadastradas.

#### Administrador

- Somente administradores podem manipular os dados de um setor.

### 04 - Catalogo de produtos

#### Vendedor

- Um vendedor pode consultar produtos.

#### Gerente

- Um gerente pode consultar produtos.

#### Administrador

- Um administrador pode cadastrar produtos.
- Um administrador pode editar produtos.
- Um administrador pode desabilitar um produto.

### 05 - Controle de acesso

- Um usuario só poderá acessar a aplicação se estiver devidamente cadastrado e autenticado.
- O sistema deve ter 03 níveis de acesso, sendo eles: Administrador, Gerente e Vendedor.
- Um usuário só poderá acessar recurso que o seu nível de acesso permita.
- Um usuário não pode alterar o seu email.

As regras aqui descritas podem ser alteradas de acordo com o contexto em que essa aplicação vai ser utilizada. Sinta-se a vontade para dar dicas de melhorias. 

### Ferramentas

Esse projeto será criado utilizando a o SDK do dotnet na versao 6, você pode fazer o download [aqui](https://dotnet.microsoft.com/en-us/download)

Vamos aprender a implementar diversas funcionalidades e a utilizar diversas ferramentas, sendo elas: 

- ASP.NET 6 WEB API
- Entity Framework Core
- Fluent Validations
- Documentação com Swagger
- Autenticação
- Autorização
- JWT
- Permissões de acesso de acordo com regras
- E varias funcionalidades que conseguirmos colocar em prática.
