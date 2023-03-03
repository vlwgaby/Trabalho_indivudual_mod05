# Trabalho_indivudual_mod05

Caderno da Saúde
A proposta da nossa aplicação é permitir e facilitar que qualquer pessoa possa registrar informações em um 'bloco de notas' voltado para a área da saúde.

Além das notas criadas, nossa aplicação ainda permite que o usuário crie um perfil com o seu 'nome', 'gênero', 'data de nascimento', 'peso', 'altura' e 'tipo sanguíneo'. Também é inserido no perfil o 'IMC', que é gerado automaticamente com base nos dados inseridos.

A ideia é que a aplicação auxilie no registro de consultas agendadas, horário de remédios, controle de medicamentos, cronograma de vacinação, e muito mais!

Nossa API é composta por 4 entidades

Entidades
'usuários'
'notas'
'perguntas'
'comunicados'
Entidades
ENTIDADE_USUÁRIOS

ENTIDADE_NOTAS

ENTIDADE_PERGUNTAS

ENTIDADE_COMUNICADOS



## Rotas CRUD

### [ 1 ] <em>usuários</em>

| Método | Rota | Descrição |
| ------ | ----- | ----------- |
| **`GET`** | **/usuários** | Retorna a usuários. |
|  **`GET`** | **/usuários/id** | Retorna usuários. |
|  **`POST`** | **/usuários** | Criar.usuários  |
|  **`PUT`** | **/usuários/id** | Altera os dados de usuários.
|  **`DELETE`** | **/usuários/id** | Remove os usuários.
  
### [ 2 ] <em>Notas</em>

| Método | Rota | Descrição |
| ------ | ----- | ----------- |
|  **`GET`** | **/ notas** | Retorna  notas. |
|  **`GET`** | **/notas/id** | Retorna  notas. |
|  **`POST`** | **/notas** | Criar  notas.  |
|  **`PUT`** | **/ notas/id** | Altera  notas.
|  **`DELETE`** | **/ notas/id** | Remove notas.
  
  
### [ 3 ] <em>Perguntas</em>

| Método | Rota | Descrição |
| ------ | ----- | ----------- |
|  **`GET`** | **/Pasta de perguntas** | Retorna perguntas. |
|  **`GET`** | **/Pasta de perguntas/id** | Retorna perguntas. |
|  **`POST`** | **/Pasta de perguntas** | Criar uma nova Pasta de perguntas.  |
|  **`PUT`** | **/Pasta de perguntas/id** | Altera os dados das perguntas.
|  **`DELETE`** | **/Pasta de perguntas/id** | Remove as perguntas.


### [ 4 ] <em>comunicados</em>

| Método | Rota | Descrição |
| ------ | ----- | ----------- |
|  **`GET`** | **/comunicados:** | Retorna todos os  comunicados. |
|  **`GET`** | **/comunicados:/id** |  Retorna a comunicados. |
|  **`POST`** | **/comunicados:** | Cria comunicados.  |
|  **`PUT`** | **/comunicados:/id** | Altera comunicados.
|  **`DELETE`** | **/comunicados:/id** | Remove comunicados.
  
