# Desafio Machine Learning

Configuração do Workspace do Azure Machine Learning

## Para começar a utilizar o Azure Machine Learning, é necessário provisionar um Workspace do Azure Machine Learning em sua assinatura do Azure. Aqui está como eu fiz isso:

### Acesso o portal do Azure:

- ⚡ Acessei o portal do Azure em https://portal.azure.com utilizando minhas credenciais da Microsoft.

- ⚡ Criei um recurso do Azure Machine Learning:

* Selecionei "+ Criar um recurso" e pesquisei por "Machine Learning".

- ⚡ Em seguida, criei um novo recurso do Azure Machine Learning com as seguintes configurações:

* Assinatura: Escolhi minha assinatura do Azure.

* Grupo de recursos: Criei um novo grupo de recursos.

* Nome: Digitei um nome único para o meu workspace.

* Região: Selecionei a região geográfica mais próxima.

* Conta de armazenamento: Anotei a nova conta de armazenamento padrão que seria criada para o workspace.

* Vault de chaves: Anotei o novo vault de chaves padrão que seria criado para o workspace.

* Insights da aplicação: Anotei o novo recurso de insights da aplicação padrão que seria criado para o workspace.

* Registro de contêiner: Optei por "Nenhum" (um seria criado automaticamente na primeira vez que eu implantasse um modelo em um contêiner).

Depois, selecionei "Revisar + criar" e, em seguida, "Criar". Esperei até que o workspace fosse criado (isso pode levar alguns minutos) e depois acessei o recurso implantado.

- ⚡ Acessei o Azure Machine Learning studio:

* Iniciei o Azure Machine Learning studio (ou abri uma nova guia do navegador e acessei https://ml.azure.com).
Fiz login no Azure Machine Learning studio utilizando minha conta da Microsoft e fechei quaisquer mensagens que foram exibidas.

- ⚡ Visualizei o meu workspace:

No Azure Machine Learning studio, visualizei o workspace recém-criado e, em seguida, selecionei o workspace que acabei de criar.
