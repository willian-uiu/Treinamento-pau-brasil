## Planificador de coberturas
É importante para o acompanhamento de vendas e coberturas dos clientes.
### O que é uma cobertura? 
	É a compra de pelo menos 1 produto durante o mês.
	A cobertura é aplicável para qualquer produto ou uma cesta especifica.
	Para cesta de produtos, deverá ser filtrada pela cesta do produto. 
# ETAPAS
## 1. Relatórios [[PROMAX]]
	base de clientes (PROMAX: 0105070402)
	base de vendas (PROMAX: 030509)
	cesta de produtos (Consultar Vinicius)

## 2. Criar abas dentro do [[EXCEL]]
1. "[[Clientes]]"
2. "[[Vendas]]"
3. "[[Cesta de produtos]]"
4. "[[Dados dos produtos (01.11)]]"
5. "[[Planificador]]"
6. "[[Painel]]"

## 3. Chaves
No nosso planificador, iremos criar uma chave primária: ``FILIAL_PDV`` concatenando os dados da filial e código do cliente. 
	O que é uma chave primária? **A chave primária identifica unicamente cada registro em uma tabela.**
##### FAÇA UMA CHAVE PRIMÁRIA FILIAL_PDV para as duas abas: [[Clientes]] e [[Vendas]] use o operador de concatenação [[EXCEL#OPERADOR DE CONCATENÇÂO (&)]]


