

# Exemplo de estrutura de pastas para projetos

> Este arquivo tem como objetivo mostrar exemplo de estrutura de pastas para um projeto em Node;




- src 
  - app.js          # Classe app 
  - server.js       # Server para iniciar o app 
  - api             # Pasta da api
    - controllers   # Funções da controllers 
    - models        # Modelos do banco de dados   
    - services      # Regras de negócio
    - repositories  # Query builders
  - middlewares     # Utilizada para os middlewres da aplicação
  - errors          # Utilizada para os erros da aplicação
  - constants       # Pasta utilizada para as Constants
  - jobs            # Pasta utilizada para as Tarefas de rotinas da aplicação
  - utils           # Trechos de códigos ou funções uteis para o sistema
  - database        # Pasta utilizada para as migrations e para os seeders(que vai popular nosso banco) 
  - routes          # Pasta utilizada para as rotas do sitema
  - types           # Pasta utilizada para a Tipagem (d.ts) do Typescript
- config            # Configuração das variaveis de ambiente