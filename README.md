Album de fotos

Principais funções do sistema:
 - Login e registro
 - Cadastrar imagens
 - Editar uma imagem
 - Excluir uma imagem
 - Exibir imagens

 ## Instalação

1. Clone o repositório
```
git clone https://github.com/LuisFSouza/album.git
```

2. Crie um banco de dados em MySQL:
```
CREATE DATABASE nomedatabela;
```

3. Crie o arquivo `.env` seguindo o arquivo `.env.example`, adicionando os dados do banco de dados:
```
DB_USERNAME=Digite aqui o usuário do banco de dados
DB_PASSWORD=Digite aqui a senha do banco de dados
DB_DATABASE=Digite aqui o nome do banco de dados
DB_HOST=Digite aqui o hostname do banco de dados
DB_PORT=Digite aqui a porta do banco de dados
```

4. Digite os comandos abaixo:
```
composer update
php artisan migrate
php artisan key:generate
```

5. Rode o sistema. Ele estará na porta 8000:
```
php artisan serve
```
