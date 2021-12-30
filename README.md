## API Para Testes

API em Laravel Framework feito para testes.

### Instalação: 

* Você precisará do PHP instalado em seu computador, [BAIXE AQUI](https://www.php.net/downloads). 
* Na raiz do projeto use o comando `composer install`. 
* No arquivo `.ENV` edite o campo `DB_CONNECTION` e coloque os dados do seu banco de dados.
* Use o comando `php artisan migrate:fresh --seed` para fazer as migrações.
* Use o comando `php artisan serve` para rodar em seu servidor.
* Navegue para `http://localhost:8000`. O aplicativo será carregado automaticamente.

#### Observações:
Ao propagar o banco ele já vem com alguns usuários cadastrados:

### Lista de todas as APIs:
Method   | Descrição | Rota
:--------- | :------ | :------
GET | Lista de usuários | `localhost:8000/api/users`
POST | Cadastrar usuário | `localhost:8000/api/users`
PUT | Atualizar usuário por ID | `localhost:8000/api/users/id`
POST | Deletar usuário por ID | `localhost:8000/api/users/id`
