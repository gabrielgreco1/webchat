ZAP DO BIEL

O projeto é um webapp de chat que pode ser acessado por qualquer dispositivo conectado à mesma rede local. Ao abrir a aplicação, os usuários podem inserir um nome de usuário e digitar mensagens no campo de entrada de texto. Quando um usuário envia uma mensagem, ela é exibida na tela de todos os outros usuários conectados à aplicação no momento. Isso permite que todos interajam e conversem de forma instantânea, criando um ambiente de comunicação em tempo real.

-----------------------------------------------------------------------------------------------------------

Ferramentas utilizadas:

HTML, CSS e Javascript;

Flask: Flask é um framework leve para desenvolvimento web em Python. Ele facilita a criação de aplicativos web e APIs, fornecendo uma estrutura para gerenciar rotas, solicitações e respostas HTTP, bem como a renderização de templates.

WebSocket: A tecnologia WebSocket é a peça central do projeto. Ela permite uma conexão persistente e bidirecional entre o servidor e o cliente, tornando possível o envio e recebimento de mensagens em tempo real. Através da API WebSocket no JavaScript, os usuários podem enviar suas mensagens ao servidor, que, por sua vez, encaminha essas mensagens para todos os outros clientes conectados, garantindo que todos vejam as mensagens na tela em tempo real.

-----------------------------------------------------------------------------------------------------------

Basicamente, o projeto utiliza o Flask como framework para gerenciar o servidor e as rotas da aplicação, HTML para a estruturação do conteúdo, CSS para o estilo visual, JavaScript para a interatividade e a tecnologia WebSocket para possibilitar a comunicação em tempo real entre os usuários conectados na mesma rede local. O resultado é um chat funcional que permite a troca instantânea de mensagens entre os dispositivos conectados.
