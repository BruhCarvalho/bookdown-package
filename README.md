# bookdown-package
Pacote bookdown em R

É um pacote R de código aberto que facilita a criação de livros, artigos e outros textos longos através do R Markdown. 

CARACTERÍSTICAS:
Permite criar livros/ e-books completos a partir de documentos R Markdown;
É possível gerar saídas em diversos formatos, como HTML, PDF, e Word;
Permite a inclusão de gráficos dinâmicos e aplicativos interativos;
É fácil de aprender e de acrescentar itens como cabeçalhos, citações, figuras, etc;
Oferece suporte para outras linguagens além do R, como C, C ++, Python, etc.;
Pode ser publicado no GitHub, bookdown.org e em qualquer servidor web;
Integrado com o RStudio.

INSTALAÇÃO: 
install.packages("bookdown") Lembrando que se você quiser usar a versão de desenvolvedor, pode instalar o pacote pelo GitHub através do remotes::install_github 
('rstudio/bookdown').

NOVO PROJETO:
Para iniciar um novo projeto com Bookdown através do RStudio, basta ir em: New Project > New Directory > Book project using Bookdown. Um novo diretório será criado com um pequeno modelo de livro, que já estará pronto para ser exportado na versão HTML, bastando para isso acessar, no RStudio: Build Pane > Build Book > bookdown::gitbook
Clique em Build Book> bookdown :: gitbook
Também é possível executar bookdown :: render_book () no console R.

HELP: 
Para dúvidas, você pode usar dois forúns: https://stackoverflow.com/questions/tagged/bookdown+r e https://community.rstudio.com/tags/c/R-Markdown/10/bookdown

CÓDIGO DE CONDUTA:
O projeto de código aberto bookdown possui um Código de Conduta do Colaborador, disponível em https://pkgs.rstudio.com/bookdown/CODE_OF_CONDUCT.html cujos termos são válidos para todos que desejem colaborar com o projeto.
