# Projeto bot organizado de Arquivos.

Este código é um organizador de arquivos que automatiza a tarefa de classificar e agrupar arquivos com base em suas extensões. Aqui está como ele funciona:

- Alteração do Diretório de Trabalho:
Primeiro, o código muda o diretório de trabalho atual para a pasta especificada (C:\Users\marin\Downloads). Isso garante que todas as operações subsequentes sejam realizadas nesse diretório.



- Listagem de Arquivos e Conversão para Minúsculas:
Em seguida, ele cria uma lista chamada lista_arquivos contendo os nomes em minúsculas de todos os arquivos no diretório atual. Isso ajuda a evitar problemas de sensibilidade a maiúsculas e minúsculas.


- Obtenção de Extensões de Arquivo Únicas:
O código cria um conjunto chamado lista_tipos, que contém extensões de arquivo únicas (sem o ponto) a partir da lista de arquivos. Por exemplo, se houver arquivos com as extensões .txt, .jpg e .pdf, ele criará pastas separadas para cada uma dessas extensões.


- Criação de Subdiretórios para Cada Extensão de Arquivo:
O próximo passo é verificar se um diretório com o mesmo nome da extensão de arquivo já existe. Se não existir, o código cria um novo diretório com esse nome. Por exemplo, se houver arquivos .txt, ele criará uma pasta chamada “txt”.


- Movimentação dos Arquivos para os Subdiretórios Correspondentes:
Finalmente, o código percorre a lista de arquivos e move cada arquivo para o subdiretório correspondente com base na extensão. Por exemplo, um arquivo chamado “documento.txt” será movido para a pasta “txt”.


Resultado: Após a execução desse código, você terá uma estrutura organizada de pastas, onde cada pasta representa uma extensão de arquivo específica. Isso facilita a localização e gerenciamento dos seus arquivos.

