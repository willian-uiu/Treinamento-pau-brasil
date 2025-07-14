## Planificador de coberturas
É importante para o acompanhamento de vendas e coberturas dos clientes.
### O que é uma cobertura? 
	É a compra de pelo menos 1 produto durante o mês.
	A cobertura é aplicável para qualquer produto ou uma cesta especifica.
	Para cesta de produtos, deverá ser filtrada pela cesta do produto. 
# ETAPAS
## 1. Relatórios [PROMAX](Ferramentas%20necessárias/PROMAX.md)
	base de clientes (PROMAX: 0105070402)
	base de vendas (PROMAX: 030509)
	cesta de produtos (Consultar Vinicius)

## 2. Criar abas dentro do [EXCEL](Ferramentas%20necessárias/EXCEL.md)
1. [Clientes](Abas/Clientes.md)
2. [Vendas](Abas/Vendas.md)
3. [Cesta de Produtos](Abas/Cesta%20de%20produtos.md)
4. [Dados dos Produtos (01.11)](Abas/Dados%20dos%20produtos%20(01.11).md)
5. [Planificador](Abas/Planificador.md)
6. [Painel](Abas/Painel.md)

## 3. Chaves
No nosso planificador, iremos criar uma chave primária: ``FILIAL_PDV`` concatenando os dados da filial e código do cliente. 
	O que é uma chave primária? **A chave primária identifica unicamente cada registro em uma tabela.**
##### FAÇA UMA CHAVE PRIMÁRIA FILIAL_PDV para as duas abas: [Clientes](Abas/Clientes.md) e [Vendas](Abas/Vendas.md) use o operador de concatenação [EXCEL](Ferramentas%20necessárias/EXCEL.md#CONCAT) 
