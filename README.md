# Setup - Docker (Laravel 8 | 9)

Livewire é um framework Full-Stack para o Laravel, que torna o processo de desenvolvimento de interface dinâmica e incomparavelmente simples.

### Instalação
Clonar Projeto
```sh
https://github.com/ezedhoit/setup-docker
```

Acessar o projeto
```sh
cd setup-laravel
```

Subir os containers do projeto
```sh
docker-compose up -d
```

Acessar o container
```sh
docker-compose exec setup-docker bash
```

Instalar as dependências do projeto
```sh
composer install

Acessar o projeto
[http://localhost:8001](http://localhost:8001)