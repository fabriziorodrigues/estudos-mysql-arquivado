-- Criação da tabela

create table cadastro_receita_federal(
	cod_cadastro integer not null auto_increment primary key,
    nome_completo varchar(100) not null,
    numero_cpf varchar(15) not null,
    data_nascimento date not null,
    nome_mae varchar(100) not null,
    salario decimal(10, 2) not null,
    qtd_imoveis integer not null
);

-- Inserção dos dados

insert into cadastro_receita_federal 
(nome_completo, numero_cpf, data_nascimento, nome_mae, salario, qtd_imoveis)
values
('Joãozinho 30', '12345678900', '12-05-1990', 'Mariazinha 15', 5000.34, 10);

insert into cadastro_receita_federal 
(nome_completo, numero_cpf, data_nascimento, nome_mae, salario, qtd_imoveis)
values
('Pedrinho', '12345678991', '01-02-1924', 'Dona Hildegarda', 1234.20, 2);

insert into cadastro_receita_federal 
(nome_completo, numero_cpf, data_nascimento, nome_mae, salario, qtd_imoveis)
values
('Hugo Chaves', '11122233344', '05-20-1947', 'Dona Florinda Mesa', 4440, 4);

insert into cadastro_receita_federal 
(nome_completo, numero_cpf, data_nascimento, nome_mae, salario, qtd_imoveis)
values
('Maria Joaquina', '77788899900', '05-05-1980', 'Joana Darc', 3098.22, 5);

-- Atualização de um registro qualquer

update cadastro_receita_federal
set salario = 3098.33,
	qtd_imoveis = 7
where cod_cadastro = 4;

-- Exclusão de um registro

delete from cadastro_receita_federal
where cod_cadastro = 3;

-- Selecionar os dados da tabela

select salario,
	cod_cadastro,
    nome_completo,
    numero_cpf,
    data_nascimento,
    nome_mae,
    qtd_imoveis
from cadastro_receita_federal;
