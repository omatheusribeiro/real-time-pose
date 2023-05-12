# Detecção de Movimentos Corporais com TensorFlow em tempo real

Este repositório contém uma aplicação em ReactJS que utiliza a biblioteca TensorFlow para capturar movimentos corporais em tempo real, com a ajuda de inteligência artificial.

## Funcionamento

A aplicação utiliza o modelo pré-treinado PoseNet, fornecido pela biblioteca TensorFlow.js, para detectar as poses corporais em tempo real a partir de uma webcam conectada ao dispositivo.

Com base nas poses detectadas, a aplicação utiliza uma rede neural para classificar o movimento como uma das seguintes categorias: agachamento, flexão de braço ou prancha.

A interface da aplicação mostra um feed de vídeo da webcam, juntamente com uma lista dos movimentos realizados pelo usuário e uma contagem de quantas repetições foram realizadas para cada um dos movimentos.

## Instalação e Uso

Para executar a aplicação localmente, siga os seguintes passos:

- Clone este repositório em sua máquina local usando **`git clone https://github.com/omatheusribeiro/real-time-pose`**.

- Navegue até o diretório criado pelo clone do repositório usando **`cd real-time-pose`**.

- Instale as dependências do projeto utilizando **`npm install`**.

- Inicie a aplicação usando npm start.

- Acesse a aplicação em seu navegador, através do endereço **`http://localhost:3000`**.

## Contribuição

Este projeto foi desenvolvido como parte de um trabalho acadêmico e não está sendo mantido ativamente. No entanto, se você encontrar algum problema ou tiver alguma sugestão de melhoria, sinta-se à vontade para abrir uma issue ou enviar um pull request.

## Licença

Este projeto está licenciado sob a Licença MIT - consulte o arquivo LICENSE para obter detalhes.
