# Sprint 1 - CLOUD

PI desenvolvida em ASP.NET Core para gerenciamento de motocicletas, funcionários e pátios.
Parte do projeto acadêmico para a Mottu.

💡 Sobre o Projeto
Este projeto é uma API RESTful em ASP.NET Core desenvolvida para gerenciar motos, funcionários e pátios de uma empresa de entregas.

Faz parte de um sistema maior que busca organizar a frota de motocicletas, controlar a alocação em pátios e o cadastro de funcionários.

A API se conecta a um banco de dados Oracle e permite realizar operações de criação, leitura, atualização e exclusão (CRUD) para cada entidade.

📌 Descrição do Projeto
Esta API fornece endpoints RESTful para cadastrar, consultar, atualizar e excluir informações sobre:

🏍️ Motos
👷 Funcionários
🏢 Pátios
Ela faz parte do sistema de atendimento automotivo Mottu, promovendo uma solução eficiente para a gestão de oficinas e veículos.

🔗 Rotas da API
📍 Motos
Método	Rota	Descrição
GET	/v1/motos	Lista todas as motos
GET	/v1/motos/{id}	Retorna uma moto específica
POST	/v1/motos	Cadastra uma nova moto
PUT	/v1/motos/{id}	Atualiza os dados de uma moto
DELETE	/v1/motos/{id}	Remove uma moto do sistema
image

📍 Funcionários
Método	Rota	Descrição
GET	/v1/funcionarios	Lista todos os funcionários
GET	/v1/funcionarios/{id}	Retorna um funcionário específico
GET	/v1/funcionarios/busca?nome={nome}	Busca um funcionário por nome
POST	/v1/funcionarios	Cadastra um novo funcionário
PUT	/v1/funcionarios/{id}	Atualiza os dados de um funcionário
DELETE	/v1/funcionarios/{id}	Remove um funcionário do sistema
image

📍 Pátios
Método	Rota	Descrição
GET	/v1/patios	Lista todos os pátios
GET	/v1/patios/{id}	Retorna um pátio específico
POST	/v1/patios	Cadastra um novo pátio
PUT	/v1/patios/{id}	Atualiza os dados de um pátio
DELETE	/v1/patios/{id}	Remove um pátio do sistema

✅ Pré-requisitos
.NET SDK 9.0 ou superior
Oracle SQL Developer
Oracle Data Access Components (ODAC)
Oracle Instant Client
Visual Studio, Rider ou outro editor compatível com .NET




