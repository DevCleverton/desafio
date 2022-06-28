<p align="center">
  <img src="https://multiplier.com.br/assets/multiplier.svg" width="320" alt="Nest Logo" />
</p>

# Desafio Front-end Multiplier  

[![Deploy](https://vercel.com/button)](https://desafiofrontpoke.vercel.app/)
<img src="./src/img/prtsc/inicial.png">
<img src="./src/img/prtsc/search.png">
<img src="./src/img/prtsc/card.png">

O intuito deste teste é avaliar seus conhecimentos técnicos de front-end.

O teste consiste em utilizar a API([pokeapi v2](https://pokeapi.co/docsv2/#)) para construção de uma Pokédex.

Este desafio deve ser feito por você em sua casa. Gaste o tempo que você quiser. Mas nos conte o tempo que levou para realizar o desafio.

# Instruções de entrega do desafio

1. Primeiro, faça um fork deste projeto para sua conta no Github (crie uma se você não possuir).
2. Em seguida, implemente o projeto tal qual descrito abaixo, em seu clone local.
3. Por fim, envie via e-mail com o link do desafio, avisando quanto tempo levou para faze-lo.

# Descrição do projeto

Com esta API([pokeapi v2](https://pokeapi.co/docsv2/#)) em mãos, precisamos que você crie uma interface WEB para exibir as informações dos pokémons capturados.

> Não esqueça de ler as informações da documentação da [pokeapi v2](https://pokeapi.co/docsv2/#), armazene dados em cache 

**Sua aplicação DEVE:**

1. Ter um filtro para buscar os pokémons por nome ou número.
2. Adicionar ou capturar, como preferir, novos pokémons a Pokédex que a principio estará vazia.
3. Listar os pokémons que foram adicionados a Pokédex.
4. Mostrar detalhes do personagem adicionados a Pokédex como: 
    - Nome
    - Imagem dando a opção do usuário fazer upload de sua própria imagem, substituindo a que é entregue via API
    - Peso
    - Tamanho
    - Lista de tipos
    - Lista de habilidades
    - Estatísticas de velocidade
    - Defesa
    - Ataque
    - Hp
    - Cada passo de sua evolução
    - Ao clicar em um item da lista de tipos, mostrar todos os pokémons daquele mesmo tipo, inclusive os que ainda não estão adicionados a Pokédex
    - Ao clicar em um item da lista de habilidades mostrar o `short_effect` da mesma
5. Excluir os pokémons que foram adicionados a Pokédex.

**Sua aplicação web NÃO PRECISA:**

1. Lidar com autenticação ou autorização (pontos extras se fizer)
2. Não precisa estar hospedada em nenhum servidor.
3. Lidar com APIs que não seja a recomendada pelo teste.
4. Ser escrita usando algum framework específico (mas não há nada errado em usá-los também, use o que achar melhor).
5. Testes unitarios (pontos extras se fizer)

# Tecnologias que deve estar presentes no desafio

- VueJS
- Bootstrap

**Não necessário mas se tiver será um diferencial**

- Testes Unitarios

# Avaliação

Seu projeto será avaliado de acordo com os seguintes critérios.

1. Sua aplicação preenche os requerimentos básicos?
2. Você documentou a maneira de configurar o ambiente e rodar sua aplicação?
3. Você seguiu as instruções de envio do desafio?
4. Ter uma aparência bonita
5. Altamente responsivo


[![Deploy](https://vercel.com/button)](https://desafiofrontpoke.vercel.app/)
<img src="./src/img/prtsc/inicial.png">
<img src="./src/img/prtsc/search.png">
<img src="./src/img/prtsc/card.png">

## Project setup
```
npm install
```

### Compiles and hot-reloads for development
```
npm run serve
```

### Compiles and minifies for production
```
npm run build
```

### Lints and fixes files
```
### npm run serve

> pokedex@0.1.0 serve
> vue-cli-service serve

 INFO  Starting development server...


 DONE  Compiled successfully in 28775ms                                                                         16:27:13

dev _ Cleverton Rocha

  App running at:
  - Local:   http://localhost:8080/
  - Network: http://_ip 

  Note that the development build is not optimized.
  To create a production build, run npm run build.


### Customize configuration
See [Configuration Reference](https://cli.vuejs.org/config/).
