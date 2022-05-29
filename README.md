# DockerApp_Back_N2B2

API utilizada para chamada dos métodos de inserção, remoção e retorno de images e contaieners com funcionamento integrado junto ao front-end disponibilizado através do link: https://github.com/PedroCarvalhoKnok/DockerApp_SR_N2B2.

## Utilização
Executar o arquivo endpoints.py para disponibilzação da API do Docker através da URL: http://127.0.0.1:5000

## Endpoints disponíveis:
/images
/containers

## Métodos

### Images
get: retorna todas os containers presentes no Docker.
Parametros: Não possui parametros.

delete: deleta um ou todos os containers do docker.
Parametros: idContainer
Se não for passado o parametro idContainer, todas os containers serão deletadas.

post: Realiza a criação de um container.
Parametros: name, image

### Images
get: retorna todas as images presentes no Docker.
Parametros: Não possui parametros.

delete: deleta uma ou todas as images do docker.
Parametros: idImage
Se não for passado o parametro idImage, todas as images serão deletadas.

post: Realiza o pull de uma image.
Parametros: imageName
