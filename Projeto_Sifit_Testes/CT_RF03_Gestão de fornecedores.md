Cenário 03: Gestão de fornecedores

Caso de Teste 01: ADICIONE NOVO FORNECEDOR  COM DADOS VÁLIDOS.

| ID | DESCRIÇÃO |
| --- |
| C03-CT01 || O sistema deve permitir o cadastro de um fornecedor com dados válidos. |

| PRÉ-CONDIÇÕES |
| --- |
| O fornecedor deve estar logado e ter acesso ao sistema |

| PASSOS |
| --- |
| DADO que o usuário esteja logado no sistema SIFIT. |
| E acesse a área de gestão de fornecedores. |
| QUANDO selecionar a opção de cadastrar um novo fornecedor. |
| E preencher todos os campos obrigatórios com dados válidos. |
| E clicar no botão de salvar ou cadastrar. |
| ENTÃO o sistema deverá cadastrar o fornecedor. |
| E apresentar uma confirmação de sucesso. |
| E exibir o fornecedor cadastrado na listagem. |

| CRITÉRIOS DE PROTEÇÃO |
| ---- |
| O sistema deve validar os dados obrigatórios do fornecedor antes de permitir o cadastro. |



