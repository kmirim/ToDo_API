# ToDo_API

- [ ] O que é uma API:
 * Definição e propósito
 * Tipos de APIs (REST, SOAP, GraphQL)
 * Vantagens de usar APIs

- [ ] Arquitetura REST:
* Princípios e restrições
* Métodos HTTP (GET, POST, PUT, DELETE)
* Códigos de status HTTP
* Endpoints e recursos

- [ ] Formatos de dados:
* JSON: Sintaxe, estrutura, manipulação em JavaScript
* XML: Noções básicas, caso seja relevante para seu contexto

- [ ] Modelagem de dados:
* Definir a estrutura dos dados da tarefa (id, título, descrição, status, etc.)
* Escolher um banco de dados (pode ser em memória para simplificar)

- [ ] Rotas (Endpoints):
* GET /tarefas (listar todas as tarefas)
* GET /tarefas/:id (obter uma tarefa por ID)
* POST /tarefas (criar uma nova tarefa)
* PUT /tarefas/:id (atualizar uma tarefa)
* DELETE /tarefas/:id (excluir uma tarefa)

- [ ] Controladores (Controllers):
* Implementar a lógica de cada rota, interagindo com o modelo de dados

- [ ] Modelo (Model):
* Criar funções para realizar as operações CRUD no banco de dados (ou na estrutura de dados em memória)

- [ ] Testes:
* Escrever testes unitários para garantir o funcionamento correto da API

### O que é API: ###
* Uma Interface de Programação de Aplicativos (API) é um conjunto de regras e especificações que permite que diferentes softwares se comuniquem e troquem informações. Ela atua    como um intermediário, permitindo que um aplicativo (cliente) solicite dados ou serviços de outro aplicativo (servidor). <br>
  Exemplo: Ao fazer login em um site de e-commerce, o aplicativo (cliente) envia suas credenciais (login e senha) para a API. A API, por sua vez, consulta o banco de dados para   verificar se as credenciais são válidas. Se forem válidas, a API retorna uma resposta positiva ao aplicativo, permitindo o acesso à conta do usuário. Caso contrário, a API      retorna uma resposta negativa, informando que as credenciais estão incorretas.
