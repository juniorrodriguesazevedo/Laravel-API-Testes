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
POST | Registrar usuário | `localhost:8000/api/register`
POST | Login de usuário | `localhost:8000/api/login`
GET | Retorna usuário logado | `localhost:8000/api/profile`
POST | Cadastrar telefone | `localhost:8000/api/phones`
GET | Lista de todos os telefones | `localhost:8000/api/phones`
GET | Pega telefone por ID | `localhost:8000/api/phones/id`
PUT | Atualizar telefone por ID | `localhost:8000/api/phones/id`
POST | Deletar telefone por ID | `localhost:8000/api/phones/id`
