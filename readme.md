# Projeto MVC do dia 22/05/2025

Explique com suas palavras o papel de cada camada da arquitetura MVC usada neste projeto.
Como o Model, o Controller e a View interagem entre si?
Na arquitetura MVC, o Model cuida da lógica dos dados e da comunicação com o banco de dados, o View exibe as informações para o usuário usando HTML, e o Controller age como intermediário, recebendo as requisições da View, processando com a ajuda do Model e devolvendo uma resposta. Eles interagem em um fluxo onde o usuário aciona o Controller, que consulta ou atualiza dados no Model e retorna uma resposta visual através da View.

Como ocorre o envio e o recebimento de dados no formato JSON neste projeto?
Cite uma rota que responde em JSON e explique seu funcionamento.
O envio e recebimento de dados em JSON ocorre nas rotas da API, onde o cliente (navegador ou outro serviço) faz requisições HTTP e o servidor responde com dados em formato JSON. Por exemplo, a rota GET /api/usuarios busca todos os usuários no banco de dados com Usuario.findAll() e retorna a lista em JSON usando res.json(usuarios).

Qual a importância de usar HTML básico com formulários e tabelas para organizar e manipular dados no navegador?
Por que esse tipo de estrutura ainda é útil em projetos back-end com Node.js?
HTML básico com formulários e tabelas é essencial para organizar, visualizar e manipular dados diretamente no navegador de forma simples e funcional. Mesmo em projetos back-end com Node.js, essa estrutura é útil porque permite testes rápidos, protótipos funcionais e interação com o servidor sem precisar de frameworks complexos no frontend.
