## Manual de uso do CMPaaS portal do desenvolvedor
### Pagina inicial
Exibe as principais API's do portal. Para acessar as demais API's, clique em "GALERIA DE APIS" ou em "VER TODAS AS APIS" <br><br>
<img src="https://raw.githubusercontent.com/lukasg18/imagens-gravitee/master/topAPIMarcado.png" width="100%" height="100%">

### Galeria de APIs
Nesta página vemos todas as API's cadastradas no portal do desenvolvedor. Para visualizar os detalhes de uma API, dê um clique nela. <br> <br>
<img src="https://raw.githubusercontent.com/lukasg18/imagens-gravitee/master/todasAPISMarcado.png" width="100%" height="100%">

### Detalhe da API
Mostra um resumo sobre a API, como: <br>
* A sua versão;
* O endpoint para acessa-la;
* O nome do dono da API;
* A data de quando foi publicada. <br> <br>
<img src="https://raw.githubusercontent.com/lukasg18/imagens-gravitee/master/planoAPImarcado.png" width="100%" height="100%"><br>

Para visualizar a documentação detalhada sobre a API, clique em documentação.

### Planos e assinaturas
O plano de uma api informa o limite de requisições e sua segurança (publica ou privada). Assinatura de uma api somente é requerida para planos com tipo de segurança privado.<br>
Cada api possui um ou mais planos, em geral se parecem com os que seguem:
* Plano limitado: tem como característica principal um limite de 10.000 requisições por dia e que não precisam de assinatura para ser utilizado;
* Planos personalizados: estes podem possuir uma assinatura obrigatória e podem ou não possuir um limite de requisições. <br> <br>
<img src="https://raw.githubusercontent.com/lukasg18/imagens-gravitee/master/DetalhePlano.png" width="100%" height="100%"><br>


### Acessando uma API com plano limitado
Para acessar uma api com plano limitado basta inserir o endpoint, fornecido na página de resumo. Clique em "Overview" e veja os detalhes resumidos da API no cabeçalho da página.

### Criando uma aplicação

Aplicações são necessárias pois permitem que você consiga integrar sua conta a determinadas API's lhe dando acesso a elas, para criá-las, siga os passos abaixo.

Na Pagina inicial, clique no ícone no canto superior direito e faça o login com os dados do acesso cidadão. Uma vez feito o login, clique novamente no ícone do canto superior direito e vá na opção "Aplicações". <br> <br>
<img src="https://raw.githubusercontent.com/lukasg18/imagens-gravitee/master/aplicacao.png" width="100%" height="100%"><br>


Para criar uma nova aplicação, clique no botão "+". <br> <br>
<img src="https://raw.githubusercontent.com/lukasg18/imagens-gravitee/master/NovaAplicacao.png" width="100%" height="100%"><br>


Repare que existe um campo chamado "client ID", este campo é necessário para API’s que requerem autenticação, se este não é seu caso, então provavelmente você está usando o plano limitado, neste caso deixe este campo em branco, caso contrário, solicite esta informação ao administrador do sistema.

