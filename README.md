# git-aula
## Comandos ultilizados pelo Grupo 1 na aula de hoje

### 1°comando-
CREATE TABLE produtos (
id_produto INT PRIMARY KEY AUTO_INCREMENT,
nome VARCHAR (100) NOT NULL,
descricao VARCHAR (150) NOT NULL,
quantidade INT NOT NULL,
valor INT NOT NULL
);

### 2°comando-
CREATE TABLE auditoria_produto (
id_auditoria INT PRIMARY KEY AUTO_INCREMENT,
nome VARCHAR (100) NOT NULL,
descricao VARCHAR (150) NOT NULL,
quantidade INT NOT NULL,
valor INT NOT NULL,
data DATE NOT NULL
);
