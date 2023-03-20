## 🚀 Inicialização de ambiente
Para configurar e inicializar o ambiente de desenvolvimento do servidor, é necessário ter instalado o **[Node](https://nodejs.org/en/ "Node")** (> v16.0.0), juntamente com o npm (> v8.0.0).

Na pasta raíz do diretório, execute os scripts abaixo:

    // Instalação de dependências
    npm install
	// ou
	yarn install

Agora, para fazer o build do PWA, execute o seguinte script:

	ng build

Uma vez que a build foi realizada, o diretório dist/ deve ter sido criado no seu projeto. Para executar o PWA que foi gerado, execute o comando:

	 npx serve dist/cadastro-seguros/

Assim,  o PWA deve estar disponível em `http://localhost:3000` _(ou no host e porta informados no console)_.

<br>