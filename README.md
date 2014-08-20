Site do CPDx
-------

Site do CPDx: Ciclo de Palestras para Desenvolvedores. O CPDx é uma iniciativa de funcionários da Superintendência de Tecnologia da Informação da UFBA (STI) para promover a discussão de tecnologias de desenvolvimento de software e tópicos relacionados.


Configuração
------------

O site do CPDx é implementado com a utilização do [Jekyll]. Atualmente ele é hospedado na própria UFBA, mas pode-se, por exemplo hospedar gratuitamente um site/repositório deste tipo no Github através do [Github Pages]. Para implementação, basta ter instalado um interpretador da linguagem [Ruby] e a [gem] do Jekyll.

Recomenda-se a leitura dos links citados para compreensão do processo de criação e publicação do site, assim como do capítulo posterior para organização do ambiente de desenvolvimento.


Organizando Ambiente
------------

Para organização do ambiente de desenvolvimento, recomenda-se utilizar [RVM - Ruby Version Manager]. O RVM utilizará dois arquivos presentes no projeto:

  - _.ruby-version_ que contem a versão do Ruby utilizado. Exemplo: "ruby-2.1.2"
  - _.ruby-gemset_ que contem o nome da gemset utilizada no projeto. Exemplo: "jekyll"

Caso a versão do ruby não esteja instalada, basta rodar no terminal um `rvm install 2.1.2`, por exemplo para instalar o ruby na versão 2.1.2


[RVM - Ruby Version Manager]: https://rvm.io/
[Jekyll]: http://jekyllrb.com/
[Github Pages]: http://pages.github.com/
[Ruby]: https://www.ruby-lang.org/pt/
[gem]: http://rubygems.org/gems/jekyll

