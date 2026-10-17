# Minerador-de-Livros

Navegando pela internet atrás de um site que tinha livros de graças em Pdf's, encontrei um site diretamente de Moçambique o Kafunda

## O livros.v1.ipynb 
Cria o seu banco de dado com o nome e destino que você informa
E ainda possui um codigo que faz uma varredura na web, como o site do kafunda ao visualizar o livro é por id, foi realizado um loop para ir olhando id por id e ir gravando em um banco de dados em SQLite para que no futuro seja feito uma consulta para encontrar livros, exames, estudos e etc.. o banco de dados lhe da a liberdade de proucurar oque você deseja ver, o sistema de proucura do site não é tão eficiente.
Com o banco você faz a consulta encontra o id do Pdf e ainda tem uma coluna com as informações do download que vem "publicdocs/Aula T2 - LTC (12-Out-21).pdf" ultilizando esse cabeçalho inicial "https://www.kufunda.net/" podemos ir direto pro Pdf, juntos fica o link direto pro PDF (https://www.kufunda.net/publicdocs/Aula T2 - LTC (12-Out-21).pdf) esse por exemplo é um Pdf de *DEMONSTRAÇÕES DAS LEIS DE ÁLGEBRA DE LÓGICA*

## Ja o baixador_kufunda.ipynb
É um codigo que vai percorrer todo o banco fazendo o download para uma pasta desejada, criando assim uma pasta com todos os Pdf's do banco de dados.