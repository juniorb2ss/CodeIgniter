#CodeIgniter 2.1.3 + Modular Extensions + .htaccess

Para sistemas que precisam de HMVC, este _branch_ é o ideal, pois já conta com o **CodeIgniter 2.1.3** preparado para ser usado com (o melhor) HMVC e ainda possui o `.htaccess` preparado para a remoção do `index.php` como segmento de URL.

##Modular Extensions - HMVC

O melhor sistema para HMVC, [Modular Extensions](https://bitbucket.org/wiredesignz/codeigniter-modular-extensions-hmvc/overview), da [WiredesigNZ](http://wiredesignz.co.nz/), já instalado e pronto para ser usado em sua instalação CI.

Para mais informações, leia o artigo [HMVC no CodeIgniter com Modular Extensions](http://codeigniterbrasil.com/tutoriais/hmvc-no-codeigniter-com-modular-extensions/).

##.htaccess

Arquivo `.htaccess` já preparado para o uso de URLs sem a necessidade do `index.php` como segmento. Faz exceção à regra para o diretório `assets` (que deve ficar na raiz do projeto) e para os arquivos `index.php`, `humans.txt` e `robots.txt` (também na raiz).

Mais a esse respeito no artigo [Dicas básicas de configuração do CodeIgniter](http://codeigniterbrasil.com/dicas/dicas-basicas-configuracao-codeigniter/).

Claro que não são todos os projetos que, necessariamente, precisam contar com esse diretório e arquivos; então, se a regra de exceção não lhe servir, edite o arquivo.  :-)

##Instalação via Sublime Text com Fetch

Você pode clonar o repositório / _branch_ para seu projeto, normalmente; mas, caso precise de mais agilidade e/ou iniciar projetos "em linha de produção", usar o [Sublime Text 2](http://www.sublimetext.com/) com o plugin [Nettuts+ Fetch](http://net.tutsplus.com/articles/news/introducing-nettuts-fetch/) é uma opção a ser considerada.

Simplesmente inclua o seguinte em sua diretiva "packages":

`"CodeIgniter-hmvc": "https://github.com/tarciozemel/CodeIgniter/zipball/modular-extensions-hmvc"`

Então, sempre que precisar iniciar um novo projeto do CodeIgniter já com HMVC, usando Sublime Text com o Nettuts+ Fetch instalado, a solução está aí!  o/
