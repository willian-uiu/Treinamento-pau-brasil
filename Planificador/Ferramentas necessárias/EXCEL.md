Ferramenta de manipulação de planilhas e informações para análise de dados.

---- 

### Atalhos do Excel
- **Seleciona a célula:** ``SHIFT + seta``
- **Mover a célula até a última célula com conteúdo:** ``CTRL + seta``
- **Seleciona até ultima célula preenchida com algum conteúdo:** ``CTRL + SHIFT + SETA``
	### Exercício:  _Selecione todas as células da base de cliente, copie e cole numa nova abra dentro do arquivo "planificador" que você criou._
- **Filtrar:** ``CTRL+SHIFT+L``
- **EXPANDIR AS COLUNAS DE ACORDO COM O CONTEÚDO:** ``ATL+C+O+T`` 
- **Cola apenas os valores**: ``alt+c+v+v`` 
- **Copia a formula e também formatação:** ``ctrl+v``
 - **Abre um painel para escolher como você quer colar o conteúdo**: ``CTRL+ALT+V``
### OPERADOR DE CONCATENÇÂO (&)
- Para concatenar("juntar") o conteúdo das células você vai usar a seguinte lógica:
	``=[a célula especifica]&[a outra célula]``
- Você também pode utilizar outro texto entre as células, por exemplo: 
	``=A1&"_"&A2``

### Função de procura e retorno de valores (PROCX):
- PROCX -> ela irá procurar um valor chave dentro de outra planilha.
	#### Lógica:
		=PROCX(VALOR QUE QUERO PROCURAR; COLUNA QUE SERÁ RETORNADA; RESPOSTA CASO NÂO ENCONTRE; MODO DE CORRESPONDENCIA EXATA["0"])

### Bloquear a referencia de uma célula(botão: F4): 
- Ao apertar F4 vai aparecer um cifrão antes da coluna.
- Quando o CIFRÃO($) ficar antes da coluna(LETRA) vai bloquear a coluna. Se ficar antes da linha(NUMERO), vai bloquear a linha. 
- Quando você for copiar e colar essa formula em outra célula, o valor de referencia não vai mudar. 
- Para travar linha ou coluna, coloque o CIFRÃO($) antes da coluna ou da linha. De acordo com o que você deseja. 
	exemplo1: $C4 -> a coluna C está travada mas a linha, não
	exemplo2: C$4 -> a linha 4 está travada mas a coluna, não
	exemplo3: $C$4 -> a coluna C e a linha 4 estão travadas.  

### Contagem por CRITÉRIO(s) (CONT.SES):
	=CONTE.SES(COLUNA DO CRITERIO1; VALOR DO CRITERO1;...)
Pode ser feita para vários critérios.

### Soma de acordo com critérios (SOMASES): 
	=SOMASES(COLUNA A SER SOMADA;INTERVALO DO CRITERIO1;CRITERIO1)"
Também pode ter mais de um critério.

### Para remover dados duplicados:
	Painel superior > dados > selecione toda a coluna dos dados repetidos > remover duplicatas.
![[imagem_removendo_dados_duplicados.png]]