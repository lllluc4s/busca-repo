<h1 align="center">BuscaRepo</h1>

<p align="center">
  <img src="https://img.shields.io/static/v1?label=PHP&message=8.1&color=blue&style=flat-square&logo=php"/>
  <img src="https://img.shields.io/static/v1?label=Laravel&message=10.8&color=red&style=flat-square&logo=laravel"/>
  <img src="https://img.shields.io/static/v1?label=PHPUnit&message=10.1&color=green&style=flat-square&logo=php"/>
</p>

## Sobre

Este é um buscador que consome a API do GitHub para listar os 5 repositórios com mais estrelas de um usuário.

## Tecnologias

-   [PHP](https://www.php.net/downloads)
-   [Composer](https://getcomposer.org/download/)
-   [Laravel](https://laravel.com/docs/8.x/installation)

## Instalação

1. Clone o repositório para sua máquina.

2. Instale as dependências do projeto executando o comando abaixo na pasta raiz:

```
composer install
```

3. Copie o arquivo `.env.example` na raiz do projeto e crie um arquivo `.env` com as configurações do seu ambiente:

```
cp .env.example .env
```

4. Verifique as credenciais de acesso à API do GitHub no arquivo `.env`.

5. Inicie o servidor PHP:

```
php artisan serve
```

6. Acesse o endereço `http://localhost:8000` no navegador para usar a aplicação.

## Uso

1. Digite o nome de um usuário do GitHub na caixa de busca e clique em "Buscar".
2. Serão listados os 5 repositórios do usuário com mais estrelas.
3. Clique no link do repositório para ser redirecionado ao GitHub.

## Testes

Os arquivos de teste estão localizados na pasta `tests/Feature` e `tests/Unit`.
Para executar os testes, execute o comando abaixo na pasta raiz do projeto:

```
php artisan test --testdox
```
