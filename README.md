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

##  Modelos de Dados (Models)
A lógica de negócio da plataforma de doações foi dividida em dois modelos principais:
- **Usuario.js**: Mapeia o perfil dos usuários (Nome, E-mail, Senha e Tipo de perfil).
- **Alimento.js**: Controla os itens cadastrados para doação (Descrição, Quantidade, Validade e Status).

## Rotas e Segurança
O controle de navegação da plataforma protege os dados dos usuários através de:
- **Middleware de Autenticação (`middleware/auth.js`)**: Restringe o acesso a páginas internas.
- **Rotas de Autenticação (`routes/authRoutes.js`)**: Gerencia os caminhos de login, registro e encerramento de sessão.

##  Interfaces Visuais (Views)
As telas do sistema foram desenvolvidas utilizando views dinâmicas em EJS:
- `login.ejs` e `cadastro.ejs`: Telas de acesso e criação de conta.
- `dashboard.ejs`: Painel principal de controle de doações e recebimentos.
- `editar alimentos.ejs`: Interface para modificação de itens no estoque de doações.

