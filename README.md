## Desafio front-end

# Objetivo

Você deve desenvolver uma aplicação web que funcione como uma plataforma
simplificada de blog pessoal. Essa aplicação deve obter informações como autores,
publicações e metadados através de APIs HTTP e exibir as informações relevantes no
browser do usuário.

# Instruções

## Tecnologias

Sua aplicação deve ser escrita em React, Vue.js ou Angular. O processo de
construção do ​ _bundle_ deve ser feito usando Webpack. Para a entrega, alguns scripts
devem estar disponíveis para execução via ​ _npm​_. São eles:

● npm start - ​Inicia o servidor de desenvolvimento (sugestão: usar o
_webpack-dev-server​_ )

● npm test​ - ​Executa o conjunto de testes disponível na aplicação

● npm build​ -​ Cria o ​ _bundle​_ para publicação

## Interface

Não existem requisitos específicos com relação ao comportamento da interface, e a
criação de uma interface visualmente agradável também faz parte do desafio.
Queremos ver as suas habilidades com CSS em ação, e portanto ​ **não é permitido o
uso de UI frameworks** (como Bootstrap ou ​Material-UI​). A utilização de
_pre-processors_ e ​ _post-processors_ para CSS é liberada, desde que esteja
completamente integrada com o Webpack.

## Funcionalidades

As funcionalidades esperadas da sua aplicação são listadas abaixo.
**Lista de publicações:** a aplicação deve buscar um conjunto de publicações e
metadados através de uma API HTTP. Cada publicação deve ser exibida no browser
em conjunto com as seguintes informações: título, corpo da publicação, nome do
autor e data de publicação.
**Sumário de publicações:** o usuário deve ter acesso a uma lista com os títulos das
publicações mais recentes.
**Filtro por autor:** deve ser possível ao usuário filtrar as publicações disponíveis, de
forma que apenas sejam visíveis as publicações de autores selecionados no filtro.
**Ordenar publicações:** a aplicação deve permitir selecionar a ordem de exibição das
publicações (crescente ou decrescente), de acordo com a data em que a mesma foi
publicada.

### APIs HTTP

Para obter os dados necessários, a aplicação deve utilizar as APIs listadas abaixo.

● Publicações: ​http://www.mocky.io/v2/5be5e3fa2f000082000fc3f

● Autores: ​http://www.mocky.io/v2/5be5e3ae2f00005b000fc3f

### Exemplos

Listamos alguns exemplos de blogs disponíveis na Internet que podem ser
consultados. Os itens aqui listados devem ser utilizados apenas para fins de
contextualização, e podem ou não conter todas as funcionalidades apresentadas
como requisito do seu desafio.

● The Clean Code Blog: https://blog.cleancoder.com

● The JavaScript Playground: https://javascriptplayground.com

● Code Simplicity: https://www.codesimplicity.com

# Critérios de avaliação

O resultado será avaliado com base na qualidade interna do código (boas práticas de
programação) e organização do projeto, no desempenho da aplicação final e no
projeto da interface.
Caso algum item do enunciado não possa ser cumprido por dificuldades técnicas,
inclua na entrega final um arquivo README justificando o motivo e explicando
como a dificuldade foi contornada, bem como instruções detalhadas para a
execução da aplicação caso não seja possível seguir o procedimento através dos
scripts npm descritos acima (npm start e npm build).

# Entrega

Deve ser entregue um arquivo compactado contendo todo o código fonte da
aplicação através do endereço de e-mail pelo qual você recebeu esse desafio.
