# CineStar - Aplicação Web em PHP

## Descrição

<p>O MovieStar é uma aplicação web em PHP que permite que os amantes do cinema explorem, avaliem, comentem e compartilhem informações sobre os filmes mais recentes.
A aplicação é construída com PHP, MySQL, Bootstrap e jQuery, proporcionando uma experiência envolvente aos usuários. Além disso,
os usuários têm a capacidade de personalizar seus perfis, adicionar filmes à coleção, realizar login e pesquisar filmes por nome.</p>

## Recursos

* Últimos Lançamentos: Visualize os filmes mais recentes, com detalhes, avaliações e comentários dos usuários.

* Categorias de Filmes: Filmes são categorizados por gênero, facilitando a busca de filmes de interesse.

* Avaliações de Usuários: Os usuários registrados podem deixar avaliações e classificações para os filmes, tornando a aplicação uma comunidade de entusiastas de cinema.

* Comentários: Além de avaliações, os usuários podem deixar comentários sobre os filmes, compartilhando suas opiniões com outros membros da comunidade.

* Perfil do Usuário: Personalize seu perfil com informações e uma imagem de perfil.

* Login e Registro: Os usuários podem realizar login para uma experiência completa, com acesso a recursos adicionais.

* Pesquisa de Filmes: Pesquise filmes por nome para encontrar seus títulos favoritos.

* Alteração de Senha: Os usuários podem alterar suas senhas para manter suas contas seguras.

## Requisitos

* PHP 7.x ou superior
* Banco de dados MySQL
* Bootstrap (CSS e JS)
* jQuery

## Instalação
 1. Clone o repositório no seu ambiente local ou servidor.

```bash
   git clone https://github.com/seunome/MovieStar.git
```

2. Crie um banco de dados MySQL para a aplicação.

```sql
CREATE DATABASE moviestar;
```

3. Importe o arquivo SQL fornecido para criar as tabelas e adicionar os dados iniciais.
```bash
mysql -u seu_usuario -p moviestar < database.sql
```

4. Atualize as configurações de conexão com o banco de dados no arquivo `config.php` para corresponder às suas credenciais.

```php
// config.php

$DB_HOST = 'localhost';
$DB_NAME = 'moviestar';
$DB_USER = 'seu_usuario_db';
$DB_PASSWORD = 'sua_senha_db';
```

5. Certifique-se de que um servidor web (por exemplo, Apache) está configurado para servir a aplicação.
6. Acesse a aplicação por meio de seu navegador.

## Uso
* Visite a página inicial para explorar os filmes mais recentes e suas categorias.
* Explore diferentes categorias de filmes.
* Realize login ou registre-se como um novo usuário para acessar recursos adicionais, como personalizar seu perfil, adicionar avaliações, classificações e comentários.
* Utilize a pesquisa de filmes para encontrar seus filmes favoritos por nome.

## Estrutura de Diretórios
* `templates/`: Contém modelos de cabeçalho e rodapé usados em toda a aplicação.
* `dao/`: Arquivos de Objetos de Acesso a Dados para operações no banco de dados.
* `assets/`: Arquivos de CSS, JavaScript e imagens.
* `index.php`: O ponto de entrada principal da aplicação.
* `config.php`: Arquivo de configuração do banco de dados.


## Créditos
<p>Este projeto foi desenvolvido por Milton Andrade.</p>



