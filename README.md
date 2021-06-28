# arquitetura-baseada-em-servicos-t1

Olá, aluno(a),

Nesta atividade veremos parte do contexto de SOA na prática! Isto mesmo, consumiremos um Web service REST, por meio de uma RESTful API! Você verá, o quão simples, pode ser isso. Vamos lá!

Para quem é fã da franquia seja dos games, ou mesmo da animação, gostará muito desta atividade. Estamos falando de Pokémon, uma das franquias mais conhecidas da Nintendo. Pois bem, utilizaremos nessa atividade a [**PokéAPI v2**](https://pokeapi.co/). Ela é uma API pública e muito simples de trabalhar.

Antes de iniciarmos, é importante que você entenda como funciona a REST API, em dois simples passos:

1. Em linhas gerais, fazemos um **HTTP request**, por meio do método **GET** ao servidor.
2. O servidor, por sua vez, nos devolverá um **HTTP response**, com um **código de erro**, caso a solicitação apresente algum problema, ou o **código 200 (HTTP success)** com os dados requeridos, que em nosso caso é um **JSON** document.

Nesta API temos o nosso **endpoint** (endereço de request), que é: **https://pokeapi.co/api/v2/{query}** e também nossa **query**, que nada mais é, que nosso **critério** de busca. Trabalharemos nesse exemplo com a busca de um pokémon por nome ou id. Para isso, utilizamos a sintaxe: **pokemon/{id|name}**. Para maiores detalhes, consulte a documentação [**aqui**](https://pokeapi.co/docs/v2).

Com estas informações em mente, implementamos de forma simplificada o consumo da REST API, utilizando uma [**jQuery**](https://jquery.com/) lib. Veja o [**código**](https://assets/code.html) comentado abaixo:

Bom, sua tarefa é a partir do código fornecido, criar uma página web que tenha um **input**, do tipo **text** para receber **nome|id** de pokémons, e um **button** de busca. Quando o usuário realizar a busca, por meio, do response, você deverá imprimir **na página** o **número**, o **nome**, o **tipo** e uma **imagem** que ilustre o pokémon. Caso exista erro, imprima na página, o correspondente **HTTP error**. O layout é livre.

E aí, pronto para o desafio?

Ao terminar compartilhe com seus colegas aqui no fórum o código produzido.

Esta atividade não é pontuada, no entanto, muito importante para o desenvolvimento de seu conhecimento sobre o assunto.

Este fórum estará aberto, entre os dias: DD/MM à DD/MM.

Vamos lá!
