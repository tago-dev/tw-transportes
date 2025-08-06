# TreinaWeb Transportes

Este projeto é um estudo baseado nos cursos da TreinaWeb, focado no desenvolvimento de uma aplicação web para gerenciamento de transportes.

## Sobre o Projeto

O objetivo deste projeto é praticar conceitos de desenvolvimento web utilizando o framework Laravel, incluindo autenticação, rotas, controllers, migrations, seeders e integração com frontend moderno (Vite, TailwindCSS).

## Tecnologias Utilizadas

-   PHP (Laravel)
-   SQLite
-   TailwindCSS
-   Vite
-   JavaScript

## Requisitos

-   PHP >= 8.1
-   Composer
-   Node.js e npm

## Instalação

1. Clone o repositório:
    ```bash
    git clone https://github.com/tago-dev/tw-transportes.git
    cd tw-transportes
    ```
2. Instale as dependências PHP:
    ```bash
    composer install
    ```
3. Instale as dependências do Node.js:
    ```bash
    npm install
    ```
4. Copie o arquivo de ambiente e configure conforme necessário:
    ```bash
    cp .env.example .env
    php artisan key:generate
    ```
5. Execute as migrações e seeders:
    ```bash
    php artisan migrate --seed
    ```
6. Inicie o servidor de desenvolvimento:
    ```bash
    php artisan serve
    ```

## Scripts Úteis

-   `npm run dev` — Inicia o Vite em modo desenvolvimento.
-   `npm run build` — Gera os arquivos otimizados para produção.

## Estrutura do Projeto

-   `app/` — Código principal da aplicação (Controllers, Models, Providers)
-   `routes/` — Definição das rotas
-   `resources/views/` — Templates Blade
-   `public/` — Arquivos públicos (imagens, index.php)
-   `database/` — Migrations, seeders e banco SQLite

## Licença

Projeto de estudo — sem fins comerciais.
