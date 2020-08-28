

### Escopo

Criar uma aplicação de forma a exibir uma listagem das streams com mais espectadores da plataforma
[Twitch](https://twitch.tv).

### Escopo técnico

Você deverá criar uma tela, contendo três componentes:

* A lista de streams com mais espectadores da plataforma
* Um campo para busca de streams por nome do streamer, ou título da stream;
* Um filtro para ordenação, pelos seguintes atributos:
  * Quantidade de espectadores
  * Título
  * Duração da stream

Além disso, você deverá implementar as seguintes regras:
* Quando um critério para busca ou filtro for inserido/alterado, a listagem deverá se atualizar de acordo.
* A listagem deverá conter as seguintes informações:
  * Nome do streamer
  * Título da stream
  * Quantidade de espectadores
  * Duração da stream, em formato humanamente legível
* Opcionalmente, a listagem pode conter:
  * O nome do jogo sendo jogado
  * A miniatura contendo um contexto visual da stream
    * Esta miniatura é fornecida pela própria API.
* Quando nenhum critério de busca for inserido, a listagem deverá conter as 20 streams com mais espectadores na plataforma, de forma decrescente.

Você pode obter a lista de streams a partir [desta API](https://dev.twitch.tv/docs/api/reference#get-streams). Você deverá criar um token de acesso para utilizá-la. Para isso, utilize a documentação [fornecida pela Twitch](https://dev.twitch.tv/docs/authentication).

### Requisitos

Você deverá utilizar um dos seguintes frameworks:
* AngularJS
* Angular
* Vue.JS
* React

Você possui toda a liberdade de utilizar quaisquer outras ferramentas (Webpack, Parcel, etc.) ou toolkits (Bootstrap, Material, etc.) que desejar, de forma a facilitar o desenvolvimento da aplicação proposta.
