Projeto para a disciplina Matemática Aplicada a TADS.

Pacote Bookdown em R.

CARACTERÍSTICAS:
É um pacote R de código aberto que auxilia na criação de livros, e-books e outros textos longos completos com R Markdown;
Permite produzir saídas em diversos formatos, tais como HTML, PDF, e Word;
Permite incluir gráficos dinâmicos e aplicativos interativos;
Trabalha com uma linguagem de marcação fácil de aprender e de acrescentar itens como cabeçalhos, citações, figuras, e outros;
Além do R, oferece suporte para outras linguagens, tais como C, C ++, Python, etc.;
Pode ser publicado no GitHub, bookdown.org e em qualquer servidor web;
Integrado com o IDE RStudio.

INSTALAÇÃO:
install.packages("bookdown") Se você desejar usar a versão de desenvolvedor, é possível instalar o pacote a partir do GitHub através do remotes :: install_github ('rstudio/bookdown')

USABILIDADE: 
Para criar o projeto, basta ir em New Project > New Directory > Book project using Bookdown. Será criado um novo diretório com um pequeno modelo de livro como exemlo, que estará pronto para ser exportado em HTML através do: Build Pane > Build Book > bookdown::gitbook 

DÚVIDAS: 
Para dúvidas, você pode usar os fóruns: https://stackoverflow.com/questions/tagged/bookdown+r e https://community.rstudio.com/tags/c/R-Markdown/10/bookdown
Também é poessível acessar um manual em https://pkgs.rstudio.com/bookdown/articles/bookdown.html

CÓDIGO DE CONDUTA:
O projeto de código aberto Bookdown estabelece alguns termos de conduta que devem ser aceitos e seguidos por quem desejar colaborar, que está disponível em https://pkgs.rstudio.com/bookdown/CODE_OF_CONDUCT.html
