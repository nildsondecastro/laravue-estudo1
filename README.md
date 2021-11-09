## Projeto de Ambientação do Laravel com o Vue.js

## Comandos utilizados

- `laravel new <nome_do_projeto>` 

- `composer require laravel/ui` (desde a versão 6 houve a separação dos assets front para um pacote chamado 'ui')

- `php artisan ui vue` (instala o scaffolding vue)

(pode ser utilizado com outros argumentos como --auth para já incluir as telas de autenticação 'php artisan ui vue --auth')

- `npm install`

- `npm run dev` (gerar build)

## Obtive ERRO

A solução foi:

Limpar o cache do npm, 
Apagar a pasta node_modules, 
Apagar o arquivo package-lock.json,
e executar os comandos: `npm install` e `npm run dev`

DESTA VEZ FUNCIONOU

## Continuando

Alterei o example-component, mas não refletiu a alteração.

Para refletir automaticamente é necessário utilizar o comando:

`npm run watch` (o terminal fica reservado escutando as alterações)

Por algum motivo o Chrome não atualiza os componentes. No firefox funcionou

