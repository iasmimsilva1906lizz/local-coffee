Projeto bootstrap 5
tema do projeto
O tema escolhido do projeto foi a cafeteria na qual trabalho, onde recebi permição para ultilizar fotos e publicar o site.
Inclusive fui instruida a continuar o projeto para desenvolver o site oficial da cafeteria.




Estrutura do projeto
Eu escolhi uma forma mais simples de mostrar os produtos que temos na cafeteria, de um jeito que eu acho visualmente intuitivo.

Alem de utilizar as classes do bootstrap eu criei algumas classes no css para mudar a cor de fundo e ajustar as imagens dos cards de menu:
cordefundocaramela: utilizada na navbar e no footer
cordefundolightgray: utilizada no body da pagina (home) e (mais)
cordefundocaramelaclaro: utilizada no body dos cards e no dropdown
card-img-top-ajuste: utilizada para ajustar as imagens dos cards de itens de menu, para não ficarem com tamanhos diferentes
Começando pela primeira pagina :
1- home.html:
  Criei uma header para abrigar a navbar, navbar expand quando chegar na largura para celular ira virar um hamburguer.
 Coloquei os itens de navbar e os links para as próximas páginas  juntamente com o dropdow de menu com outros links para as outras páginas
  Criei uma main e em seguida criei um container para abrigar um carrossel automático, peguei um template no bootstrap, mudei o tempo de troca das imagens, mudei o tamanho das fotos e do carrossel 
Criei uma section para colocar os cards em grid para apresentar os endereços das cafeterias e uma tag a com o link para o maps e adicionei a classe btn para o texto ser abrigado por um botão utilizei a classe col para deixar os card de forma responsiva que em um celular os cards seriam posicionados um abaixo do outro, e em dispositivos maiores eles serem apresentados um ao lado do outro 
Outra section para abrigar a foto e o texto sobre a breve historia do porque a cafeteria surgiu, ultilizando o d-flex para deixar a imagem e o texto um ao lado do outro

2- Itens de dropdown,menu,( Cafés quentes, Cafés gelados e Breakfast).

 O dropdow do menu disponibiliza que o usuario navegue entre 3 paginas 1-cafes quentes 2- cafes gelados 3- breakfast e utilizei o mesmo formato para as tres paginas, entao de forma resumida vou explicar os componentes usados nas paginas 
Primeiro componente que esta presente em todas as paginas é a navbar responsiva
Em seguida o carrossel que foi usado na primeira pagina(home)
E em seguida utilizei o sistema de colunas para colocar 4 cards um ao lado do outro para telas grandes 2 cards para tablets e 1 para celulares. 
utilizei classes para mudar o tamanho dos cards e utilizei a classe que criei para ajustar as imagens para que fiquem todas do mesmo tamanho no card img top 
no card body coloquei breves explicacoes dos produtos 

3- mais (ultima pagina)
utilizei a mesm navbar na header 
na main criei uma section para ultilizar os mesmos cards utilizados na pagina home mas dessa vez para apresentar  os cafés em graos que temos no café 
utilizei classes para mudar o tamanho da imagem e utilizei minhas classes para cor de fundo 

4-footer
por fim em todas as paginas adicionei um footer que criei a partir de colunas de forma responsiva
a footer quando for apresentada em um celular ficara disposta em uma forma unica de coluna
utilizei tambem d-flex para alinhas os botões de link para as redes sociais do café
