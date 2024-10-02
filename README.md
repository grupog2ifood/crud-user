# como fazer crud em python e mysql usando flask

Criação do CRUD em Python: com  flask e html para interface web.

tuturial simple de:
como fazer crud em python e mysql usando flask

# requisitos:
Python3: 3.10 +

pip

mysql-connector-python

BD: MySQL 8.3

navegador web

vscode ou outro editor


# linux
1:sudo apt update
sudo apt install python3

2:sudo apt install mysql-server

# windowns

1: Link para baixar python: https://python.org.br/instalacao-windows/

2: mysql: link 1: https://www.alura.com.br/artigos/mysql-do-download-e-instalacao-ate-sua-primeira-tabela

link para baixar mysql: https://dev.mysql.com/downloads/installer/


# Pip 
instalation:

sudo apt install python3-pip
1: pip install flask
2: pip install mysql-connector-python


# criar bd e tabela

- no prompt / cmd:
5: mysql -u root -p

CREATE DATABASE usuarios;
USE usuarios;
CREATE TABLE restaurantes (
id INT AUTO_INCREMENT PRIMARY KEY,
nome VARCHAR(100) NOT NULL,
cnpj VARCHAR(20) NOT NULL,
telefone VARCHAR(100) NOT NULL,
email VARCHAR(100) NOT NULL
);


# utilização do bootstrap

# npm init -y

# npm install bootstrap




