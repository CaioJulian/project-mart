# Project Mart

Projeto utilizando as stacks: Nuxt.js (web), e Laravel (API). 

link do site demonstrativo: https://projectmart.mrtsolutions.com.br

## Front-end
O projeto Nuxt pode ser acessado no link: https://github.com/caiojulian/project-front-nuxt

Instalação do projeto web:

Clonar o repositório.
```bash
$ git clone https://github.com/caiojulian/project-front-nuxt.git
```
Copiar o .env.
```bash
$ cp .env.example .env
```
Instalar as dependências.
```bash
$ yarn install
```
Realizar o build e iniciar o serviço.
```bash
$ yarn build
$ yarn start
```
## Back-end
O projeto Laravel pode ser acessado no link: https://github.com/caiojulian/project-back-laravel

Instalação da API:

Clonar o repositório.
```bash
$ git clone https://github.com/caiojulian/project-back-laravel.git
```
Instalar as dependências.
```bash
$ composer install
```
Copiar o .env, e depois inserir as credenciais do banco de dados.
```bash
$ cp .env.example .env
```
Depois de inserir as credenciais do banco de dados no .env, e realizar a migração.
```bash
$ php artisan migrate
```
Gerar a chave do projeto.  
```bash
$ php artisan key:generate
```
Iniciar o serviço.
```bash
$ php artisan serve
```
