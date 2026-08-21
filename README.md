 Como utilizar o MySQL

 Começando!

Primeiramente, acesse o **Xampp Control Panel**, e clique na opção para acessar o **MySQL** e clique 'Start'.
Se feito corretamente, o texto 'MySql' irá ficar de cor verde.
Após isso, aperte no botão "Shell" para abrir o prompt de comando .

Logo em seguida, digite mysql -u root para se conectar.

 Comandos

 [!IMPORTANTE!]
 Nunca esqueça de usar o ';' no fim de cada comando.

 Create database ( nome )
Gera um novo banco de dados, servindo como ponto de partida para a estruturação das informações.

Show databases
Lista todas as bases de dados disponíveis no sistema

 Use ( Nome do Database )
Define a base de dados ativa que receberá as alterações ou a criação de novas estruturas.

### CREATE TABLE (NOME) ( Outros comandos )
Cria uma tabela no banco de dados para iniciar o armazenamento de dados com base nas regras estabelecidas, aplicando tipos de dados específicos:
INT valores numéricos;
VARCHAR ( ): valores escritos, o () representa o limite de caracteres;
TEXT: também registra caracteres mas em maior quantidade;
DATE: Registra datas e horas;
BOOLEAN( ou TINYINT ): Verdadeiro ou falso.
 Desc (databese)
Exibe a estrutura e as colunas de uma tabela previamente configurada.

 Insert into ( database )
Adiciona um novo registro na tabela respeitando os tipos e restrições configurados.

 Select
Realiza buscas em dados já cadastrados, exigindo a especificação dos critérios desejados:
Select  From ( tabela ): o consulta todas as colunas;
(EXEMPLO)
SELECT  FROM formulas;
Select ( dado ) From ( tabela ): tem que ser escrito com 'Where  (infromação ) = colocação' para funcionar justamente para consultar algo especifico.
(EXEMPLO)
SELECT info FROM arquivo
WHERE pasta = 1;
Update
Modifica ou atualiza uma informação específica (o uso da cláusula WHERE é indispensável).
(EXEMPLO)
UPDATE alunos
SET responsavel = 'Luna'
WHERE matricula = 4
 Delete
Remove registros ou linhas de acordo com a condição informada.
DELETE FROM info WHERE pasta = 1;
