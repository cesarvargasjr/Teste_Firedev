### Descrição da minha resolução do desafio

Inicialmente eu organizei o projeto por componentes e views, comecei pelo componente "Menu", e para definir as funcionalidades dos botões eu utilizei o "react-router-dom" no componente "Content" para mostrar o conteúdo desejado após clicar em um dos botões. Neste meu componente "Content" eu chamei as minha views "Animes, Mangas e Favoritos" para exibir o conteúdo de cada um na tela.

Realizei o consumo da API [Kitsu](https://kitsu.docs.apiary.io) através do "axios", além disso, criei mais dois componentes(Card, Modal), no meu "Card" é exibido as imagens e os títulos dos Animes e Mangas em sequência como se fosse um catálago de filmes e séries. O meu componente "Modal" era usado para exibir as informações mais detalhadas de cada um. Defini propriedades para cada item presente na descrição mais detalhada dos Animes/Mangas, dessa forma, na minha view após chamar meu componente "Modal" eu chamei as minhas props recebendo os dados da API.

Layout do projeto no [Figma](https://www.figma.com/file/DoHcQ1PKnpYoj6kAYiKI2Q/Teste?node-id=0%3A1).

##

### Tecnologias

- React
- JSX
- CSS Modularizado

##

### Para executar o projeto

Execute em seu terminal os seguintes comandos:

### `npm i`
Para instalar o "Node_Modules".

### `npm start`
Após executar os comandos abra [http://localhost:3000](http://localhost:3000) para visualizar em seu navegador o projeto.

##

### Printscreen do projeto

![image](https://user-images.githubusercontent.com/72532360/150251057-3a4d74ff-3cc1-4d0d-abf8-2dc306aea26e.png)

![image](https://user-images.githubusercontent.com/72532360/150251248-2aba7999-7241-4ce3-a946-be3441bef133.png)
