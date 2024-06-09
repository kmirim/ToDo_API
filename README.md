# ToDo_API

<a href = "#API">O que é uma API: </a> 
- [ ] Definição e propósito.
- [ ] Tipos de APIs (REST, SOAP, GraphQL).
- [ ] Vantagens de usar APIs.

<a href = "#REST">Arquitetura REST:</a> 
- [ ] Princípios e restrições.
- [ ] Métodos HTTP (GET, POST, PUT, DELETE).
- [ ] Códigos de status HTTP.
- [ ] Endpoints e recursos.

<a href = "#DADOS">Formato de dados:</a>
- [ ] Noções básicas de sintaxe, estrutura, manipulação:
* JSON
* XML
  
<a href = "#MOL_DADOS">Modelagem de dados:</a> 
- [ ] Definição, como funciona e como se relaciona com uma API.
  
<a href = "#ROUTS">Rotas (Endpoints)</a> 
- [ ] GET /tarefas (listar todas as tarefas)
- [ ] GET /tarefas/:id (obter uma tarefa por ID)
- [ ] POST /tarefas (criar uma nova tarefa)
- [ ] PUT /tarefas/:id (atualizar uma tarefa)
- [ ] DELETE /tarefas/:id (excluir uma tarefa)

<a href = "#CONTROL">Controladores (Controllers)</a>
- [ ] Implementa a lógica de cada rota, interagindo com o modelo de dados.

<a href = "#MODEL">Controladores (Controllers)</a>
- [ ] Cria funções para realizar as operações CRUD no banco de dados (ou na estrutura de dados em memória).

<a href = "#TEST">Testes:</a>
- [ ] Testes unitários para garantir o funcionamento correto da API.
<hr>
 
<div id="#API"> 
### O que é API:

- Uma Interface de Programação de Aplicativos (API) é um conjunto de regras e especificações que permite que diferentes softwares se comuniquem e troquem informações. Ela atua    como um intermediário, permitindo que um aplicativo (cliente) solicite dados ou serviços de outro aplicativo (servidor).
  - Exemplo: Ao fazer login em um site de e-commerce, o aplicativo (cliente) envia suas credenciais (login e senha) para a API. A API, por sua vez, consulta o banco de dados para   verificar se as credenciais são válidas. Se forem válidas, a API retorna uma resposta positiva ao aplicativo, permitindo o acesso à conta do usuário. Caso contrário, a API      retorna uma resposta negativa, informando que as credenciais estão incorretas.
</div>
