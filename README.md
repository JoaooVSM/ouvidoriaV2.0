# ouvidoriaV2.0
Projeto Ouvidoria (versão beta).py 2023.1


Observações:

1)No MySQL Wokbench, cria as seguintes tabelas:

create table reclamacoes (
codigo int auto_increment,
reclamacao varchar (1000),
primary key (codigo)

);

create table elogios_sugestoes (
codigo int auto_increment,
elogio_sugestao varchar (1000),
primary key (codigo)

);

2)Trocar a senha do MySQL Workbench, no aquivo main (código pricipal), pela senha do MySQL em uso na hora de rodar o código para estabelecer a conexão entre o Pycharm e o MySQL.
