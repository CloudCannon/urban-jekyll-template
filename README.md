# andersonbosa.me

## Características
* Formulário de Contato
* Páginas pré-construídas
* Componentes pré-estilizados
* Blog com paginação
* Postar páginas de categoria
* Disqus comentários para postagens
* Staff e sistema de autor
* Rodapé configurável
* Feed RSS / Atom
* Tags de SEO
* Google Analytics

## Configuração
 1. Adicione os detalhes do seu site e autor em `_config.yml`.
 2. Adicione suas chaves do Google Analytics e Disqus para `_config.yml`.

## Desenvolva
O Urban foi construído com o [Jekyll](http://jekyllrb.com/) versão 3.3.1, mas também deve suportar versões mais recentes.

Instale as dependências com o [Bundler](http://bundler.io/)

~~~bash
$ bundle install
~~~

Execute `jekyll` comandos através do Bundler para garantir que você esteja usando as versões corretas:

~~~bash
$ bundle exec jekyll serve
~~~

## Edição

O template já está otimizado para adicionar, atualizar e remover páginas, funcionários, conselhos, detalhes da empresa e elementos de rodapé.

## Postagens
* Adicione, atualize ou remova uma postagem na coleção de *Posts* .
* O campo **Autor da equipe** está vinculado aos membros da coleção **Equipe/Staff** .
* As páginas de documentação são organizadas na navegação por categoria, com URLs baseadas no caminho dentro da pasta `_docs`.
* Altere os padrões quando novas postagens forem criadas `_posts/_defaults.md`.

## Formulário de Contato
* Pré-configurado, pode ser usado por exemplo com [FormSpree](https://formspree.io/)).
* Envia e-mail para o endereço listado nos detalhes da empresa.

## Funcionários
* Reutilizado em todo o site para salvar vários locais de edição.
* Adicione `excluded_in_search: true` a qualquer assunto da página da documentação para excluir essa página nos resultados da pesquisa.

## Rodapé
* Exposta como um arquivo de dados para oferecer melhor acesso aos clientes.
* Defina na seção *Data* / *Footer* .

## Detalhes da Companhia
* Reutilizado em todo o site para salvar vários locais de edição.
* Defina na seção *Data* / *Company* .

## Useful links
  (Jekyll CheatSheet)[https://learn.cloudcannon.com/jekyll-cheat-sheet/]
