# Curso_SSIS

1- Criando pacote "Conectores" (Excel -> SQL Server)

  + Arquivo original salvo para Excel 2007 (xls) por incopatibilidade 32/64bits do arquivo original.

  + Utilizado Provedor: OLE DB Nativo\Driver for SQL Server

2- Realizado ETL (Planilha Marketing / PRODUTO)
  + Produto_ID
  + Modelo_Produto
  + Marca_Produto  
  + Ano_Produto
  + Preco_Produto

3- Realizado Loop de Truncate nas tabelas
  + Incluido script SQL (Control Flow) => 'Limpar Tabelas'

4- Dividindo Fluxo de Dados
  + Utlizado a tarefa 'divisao condicional' (conditional split)

5- Realizado ETL (Planilha Marketing / CLIENTE)
  + Cliente_ID
  + CPF_Cliente
  + PreNome_Cliente
  + SobreNome_Cliente
  + Estado_Cliente
  + Cidade_Cliente
  + Data_Nascimento_Cliente
  + Salario_Cliente
  + Score_Cliente
  + Categoria_Trabalho_Cliente
  + Email_Cliente
  + Ultimo_Telefone_Cliente

6- Realizado ETL (Planilha Marketing / VENDAS)
