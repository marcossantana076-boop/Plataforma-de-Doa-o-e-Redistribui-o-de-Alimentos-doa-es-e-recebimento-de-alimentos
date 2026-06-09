# Plataforma-de-Doa-o-e-Redistribui-o-de-Alimentos-doa-es-e-recebimento-de-alimentos
Projeto simples de Login e Logout desenvolvido com Node.js, Express, PostgreSQL, Sequelize e EJS. Possui autenticação de usuários, sessões com express-session, proteção de rotas e criptografia de senhas com bcrypt. Criado para fins acadêmicos e prática de autenticação web.
## Configuração do Ambiente
O projeto foi desenvolvido utilizando a plataforma Node.js. As dependências estruturais do ambiente incluem:
- **Express**: Framework para gerenciamento de rotas e requisições HTTP.
- **EJS (Embedded JavaScript templates)**: Mecanismo de renderização para as telas.
- **Dotenv**: Gerenciamento de variáveis de ambiente seguras.

##  Banco de Dados
A persistência de dados da plataforma é estruturada através de uma conexão centralizada:
- Configurada no arquivo `config/database.js`.
- Garante o armazenamento seguro das informações de usuários e dos itens doados.
- Integração direta com os modelos de dados da aplicação.
