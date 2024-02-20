# Azure Cognitive Search: Utilizando AI Search para indexação e consulta de Dados

## Criação de Serviços

Dentro do Azure, criaremos 3 serviços:
1. Serviços cognitivos
2. Contas de armazenamento
3. Pesquisa de IA

Após criados os 3, acessaremos a nossa conta de armazenamento.

## Configuração de Contas de Armazenamento

Na conta de armazenamento, faremos o seguinte:
1. Selecionaremos a opção configurações.
2. Habilitaremos a opção permitir acesso anônimo ao Blob.

Em seguida, faremos o seguinte:
1. Selecionaremos a opção contêiner.
2. Daremos um nome a ele.
3. Selecionaremos a opção Conteiner (acesso de leitura anônimo para contêiners e blobs).
4. Clicaremos na opção criar.

Após criar, selecionaremos o nosso contêiner e o alimentaremos com arquivos que contenham textos.

## Conexão com a Base de Dados

Com isso, iremos até o serviço Pesquisa de IA, selecionaremos o serviço que criamos, vamos na opção importar dados e selecionaremos nosso contêiner.

Após a conexão com a nossa base de dados, vamos na opção explorar pesquisa.

Com isso, podemos pesquisar por palavras-chave, locais, sentimentos, nomes, entre outros.

## Possibilidades

Acredito que esse método de pesquisa poderia ser inserído no próprio "search" dos diretório do windows. De-repente até com um alternador para pesquisar por nomes de documentos ou por documentos que contenham conteúdo conforme digitado.

## Insight

Acredito que o módulo "Azure Cognitive Search: Utilizando AI Search para indexação e consulta de Dados" do curso, ensina que é possível criarmos uma base dados com arquivos, e que a partir de um serviço podemos pesquisar por palavras-chave, locais, sentimentos, nomes, entre outros, informações que contenham nesses arquivos.
