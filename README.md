# Comando de Terminal (Sistema Operacional)
---
Lista 

# Comandos e suas funções


Mysql -u root: Conecta ao servidor de banco de dados utilizando o usuário administrador chamado root.

SHOW DATABASES;: Lista todos os bancos de dados existentes no servidor atual.

DROP DATABASE escola_db;: Apaga permanentemente o banco de dados chamado escola_db e todos os dados/tabelas contidos nele.

CREATE DATABASE escola_db;: Cria um novo banco de dados vazio com o nome escola_db.

USE escola_db;: Seleciona o banco de dados escola_db como o ativo na sessão, para que os comandos seguintes sejam executados dentro dele.

CREATE TABLE alunos(...): Cria a tabela chamada alunos especificando suas colunas e os tipos de dados de cada uma:
matricula INT: Números inteiros.
nome VARCHAR(50): Texto de até 50 caracteres.

cpf VARCHAR(11): Texto de até 11 caracteres.

SHOW TABLES;: Exibe todas as tabelas criadas no banco de dados atualmente selecionado (escola_db).

DESC alunos; (ou DESCRIBE): Exibe a estrutura técnica da tabela alunos (colunas, tipos de dados, se aceita valores nulos, chaves e valores padrão).

INSERT INTO alunos (...) VALUES (...);: Insere um novo registro (linha) com os dados descritos dentro do banco de dados na tabela alunos.

SELECT * FROM alunos;: Consulta e exibe todas as colunas (*) e todas as linhas cadastradas na tabela alunos.

# Passo a Passo (UPDATE) 
 select nome from alunos where matricula = 1;
+---------------+
| nome          |
+---------------+
| Jos? Da Silva |
+---------------+
1 row in set (0.002 sec)

MariaDB [escola_db]> select nome from alunos where matricula = 2;
+--------------+
| nome         |
+--------------+
| Stella Maria |
+--------------+
1 row in set (0.001 sec)

MariaDB [escola_db]> select nome from alunos where matricula = 3;
+------------+
| nome       |
+------------+
| Davi Lucca |
+------------+
1 row in set (0.001 sec)

MariaDB [escola_db]> select nome from alunos where matricula = 4;
+-------------------+
| nome              |
+-------------------+
| Valdirene Antonia |
+-------------------+
1 row in set (0.001 sec)

MariaDB [escola_db]> select nome from alunos where matricula = 5;
+-----------------+
| nome            |
+-----------------+
| Sergio Henrique |
+-----------------+
1 row in set (0.001 sec)

MariaDB [escola_db]> select nome from alunos where matricula = 6;
+---------------+
| nome          |
+---------------+
| Maria Clarice |
+---------------+
1 row in set (0.001 sec)

# O que é o MySQL 
É um SGBD (Sistema Gerenciador de Banco de Dados).

MySQL não fala português e só entende (executa e escuta) comandos na linguagem SQL.

Ele previne corrupção de dados, controla acessos e otimiza a velocidade. 

Responsável por gerenciar a entrada e saída de dados. 

# Instalação básica (MySQL)

1. Download- baixar o instalador oficial (windows) no site da ORACLE.

2. Pacote- Escolher a opção Developer Default (inclui o painel visual).

3. A chave Mestra (desenvolvimento)- definir a senha do usuário root.

4. Acesso (fim)- Abrir o MySQL nossa área de trabalho virtual.

# Minha opinião sobre o conteúdo

Primeiramente, gostei de trabalhar com esse conteúdo que particularmente achei (tive a impressão) que seria muito difícil mas ao contrario disso 
achei tranquilo, gostei de montar tabelas, decorei os códigos rápido tanto que eu coloquei uns 8 nomes para fazer e ver dando certo, 
sentimento muito bom (totalmente satisfatório).
Por fim, vale muito a pena aprender a usar.
