Rota: Endereço completo da requisição
Recurso: Qual entidade estamos acessando no sistema

GET: Buscar uma ou mais informações do back-end
POST: Criar uma nova informação no back-end
PUT: Atualizar uma informação existente no back-end
DELETE: Remover uma informação do back-end

POST: http://localhost:333/users = Criar um usuário
ET: http://localhost:333/users = Listar usuários
GET: http://localhost:333/users/users/5 = Buscar dados do usuário com ID 5

Request Param: Parâmetros que vem na própria rota que identificam o recurso
Query Param: Parâmetros que vem na própria rota, geralmente opcionais para filtros, paginação
Request Body: Parâmetros para criação/atualização de informações

Migrations = Histórico do banco de dados