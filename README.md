Este é um projeto simples em Laravel que demonstra um CRUD (Create, Read, Update, Delete) para gerenciar livros.

## Pré-requisitos

- PHP >= 7.4
- Composer
- Node.js (para compilar assets CSS/JS, opcional)

## Instalação

1. Clone o repositório:

```bash
git clone https://github.com/daniellopesjp/crud-laravel.git
```

2. Navegue até o diretório do projeto:

```bash
cd crud-laravel
```

3. Instale as dependências do Composer:

```bash
composer install
```

4. Copie o arquivo de ambiente de exemplo e configure-o com suas informações de banco de dados:

```bash
cp .env.example .env
```

5. Gere a chave de aplicativo:

```bash
php artisan key:generate
```

6. Execute as migrações do banco de dados para criar as tabelas necessárias:

```bash
php artisan migrate
```

## Uso

7. Inicie o servidor de desenvolvimento:

```bash
php artisan serve
```

8. Acesse o aplicativo em seu navegador usando o endereço local gerado pelo servidor de desenvolvimento (por padrão, http://localhost:8000).

## Nota

Se você deseja adicionar, editar ou excluir livros, primeiro você precisa criar um usuário e fazer login. Isso é feito automaticamente após a instalação das migrações.

## Contribuição

Contribuições são bem-vindas! Sinta-se à vontade para enviar pull requests ou abrir issues.

## Licença

Este projeto está licenciado sob a [Licença MIT](https://opensource.org/licenses/MIT).

