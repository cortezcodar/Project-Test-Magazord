# Sistema de Contatos

Este é um sistema de contatos simples desenvolvido em PHP utilizando o framework Laravel. Com ele, você pode adicionar, editar e excluir pessoas, bem como adicionar e excluir contatos vinculados a essas pessoas.

## Tabela de Conteúdos

- [Tecnologias Utilizadas](#tecnologias-utilizadas)
- [Requisitos](#requisitos)
- [Configuração do Projeto](#configuração-do-projeto)
- [Estrutura de Diretórios](#estrutura-de-diretórios)
- [Como Executar](#como-executar)Como Executar
- [Funcionalidades](#funcionalidades)
- [Licença](#licença)
- [Autor](#autor)

# Tecnologias Utilizadas

Back-End: PHP 8.1.12 com Laravel.

Front-End: HTML, CSS.

Banco de Dados: MySQL 8.0.31.

Gerenciador de Pacotes: Composer 2.4.4

Recomenda-se o uso de [VSCode](https://code.visualstudio.com/) como ambiente de desenvolvimento.

## Requisitos

Certifique-se de que o seu ambiente atenda aos seguintes requisitos antes de executar o projeto:

-   PHP 8.1.12 ou uma versão mais recente
-   Composer 2.4.4 ou uma versão mais recente
-   MySQL 8.0.31 ou uma versão mais recente

Recomenda-se o uso do VSCode como ambiente de desenvolvimento.

## Configuração do Projeto

Siga os passos abaixo para configurar o projeto em seu ambiente:

1. Clone este repositório:

   ```shell
   git clone https://github.com/cortezcodar/Project-Test-Magazord
   cd seu-repositorio

2. Abra a pasta do projeto no VSCode.

3. Crie um novo arquivo chamado `.env` na pasta do projeto.

4. Copie o conteúdo do arquivo `.env.example` e cole-o no arquivo `.env` que você acabou de criar.

5. Abra o terminal no VSCode e navegue até a pasta do projeto usando o comando:


```json
cd SeuDiretorio/Project-Test-Magazord-PHP
```
## Como Executar

6. Execute o comando para instalar as dependências do Composer:

```
composer install

```

7. Gere uma chave de aplicativo Laravel com o comando:

```
php artisan key:generate
```

8. Execute as migrações do banco de dados com o comando:

```
php artisan migrate### Obrigado por visitar meu repositório!

```

9. Inicie o servidor de desenvolvimento com o comando:

```
php artisan serve
```

## Estrutura de Diretórios

Aqui está uma breve descrição de cada pasta na estrutura de diretórios do projeto:

- `app/`: Contém os arquivos relacionados à lógica da aplicação, como controladores, modelos e outros.
- `bootstrap/`: Contém os arquivos relacionados à inicialização da aplicação.
- `config/`: Contém arquivos de configuração da aplicação, onde você pode definir variáveis de ambiente, configurações de banco de dados, etc.
- `database/`: Contém migrações e sementes para o banco de dados.
- `public/`: É a pasta pública da aplicação, onde você pode colocar arquivos acessíveis ao público, como imagens, CSS, JavaScript, etc.
- `resources/`: Contém recursos, como arquivos Blade para as views, arquivos SASS ou LESS para estilos, etc.
- `routes/`: Define as rotas da aplicação.
- `tests/`: Contém testes automatizados para a aplicação.
- `.editorconfig`: Configuração do editor de código para manter a consistência na formatação.
- `.env.example`: Modelo de arquivo de ambiente. Copie para `.env` e configure suas variáveis de ambiente.
- `.gitattributes`: Arquivo de configuração do Git.
- `.gitignore`: Lista de arquivos e pastas a serem ignorados pelo Git.
- `README.md`: Este arquivo que você está lendo.
- `composer.json` e `composer.lock`: Arquivos relacionados às dependências do Composer.
- `package.json`: Arquivo de configuração das dependências JavaScript.
- `phpunit.xml`: Configuração para execução de testes.
- `vite.config.js`: Configuração do Vite (se você estiver usando esta ferramenta).

## Funcionalidades

`Consulta de Pessoas`: Os usuários podem visualizar uma lista de pessoas cadastradas no sistema.

`Cadastro de Pessoas`: Os usuários podem adicionar novas pessoas ao sistema, fornecendo nome e CPF.

`Edição de Pessoas`: Os usuários podem editar informações de pessoas existentes.

`Exclusão de Pessoas`: Os usuários podem excluir registros de pessoas.

`Consulta de Contatos`: Os usuários podem visualizar uma lista de contatos vinculados às pessoas.

`Cadastro de Contatos`: Os usuários podem adicionar novos contatos e vinculá-los a uma pessoa.

`Edição de Contatos`: Os usuários podem editar informações de contatos existentes.

`Exclusão de Contatos`: Os usuários podem excluir registros de contatos.## Tabela de Conteúdos


### Desenvolvimento

Este projeto foi desenvolvido utilizando o framework Laravel, que segue o padrão MVC (Model-View-Como ExecutarController) para uma organização eficiente do código.

O back-end foi construído em PHP, com a utilização do Composer como gerenciador de pacotes para facilitar a gestão das dependências.

O front-end foi desenvolvido com HTML e CSS básico para uma interface simples e amigável.

### Autor

Desenvolvido por Reinaldo Flaviano


### Obrigado por visitar meu repositório!



