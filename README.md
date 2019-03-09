# MarketPlace

MarketPlace (API Rest) NodeJS

Desafio Módulo 2 NodeJS (Bootcamp - RocketSeat)

- Operação CRUD, com validação de dados, filtros de consultas e paginação.
- Autenticação de usuário no banco, criptografia de senha, geração e validação de TOKEN.
- Emails com template e envio em fila usando o REDIS.
- Tratamento de erros.
- Parâmetros em variáveis ambiente

Tecnologia: NodeJs
Padrão de Arquitetura: MVC

ORM: Mongoose
BD: MongoDB

# Criar arquivo .env com as variáveis:

- NODE_ENV=development

Geração do Token de Autenticação
- APP_SECRET=MarketPlace

Url de conexão do MongoDB
- DB_URL=mongodb://localhost:27017/marketplace

Configuração do serviço SMTP para envio de e-mail
- MAIL_HOST=
- MAIL_PORT=
- MAIL_USER=
- MAIL_PASS=

Host e porta do REDIS para gerenciar as filas de envio de e-mail
- REDIS_HOST=127.0.0.1
- REDIS_PORT=6379

DNS de configuração do SENTRY para vizualização de LOG de erros
- SENTRY_DSN=https://



