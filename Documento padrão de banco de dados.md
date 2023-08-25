bd.0001.01
- banco de dados
- numero do documento
- versão

modelagem de dados
- Listar todos os substantivos
- Listar objetos de significancia (o que precisa ser armazenado)
- Remover as redundancias (caso tenha duas ou mais entidades com a mesma funcionalidade
  escolher a mais representatica e excluir as demais
- Matriz de relacionamento
- MER logico
- Projeto inicial de banco de dados (testar o modelo antes de implementar)
- MER fisico
- criada as estruturas de banco de banco de dados

            +---------------------------------------------------------------------+
            | Entidade        | Representação         | exemplo                   |  
            | Banco de dados  | BD_nome_sobrenome     | BD_ParaDecision           |
            | Tabela          | TBL_Nome_OrdemCriação | TBL_PROPOSICAO_01         |                    
            | Atributo        | AOrdemTabela_nome     | A01_codigo                |
            | View            | VW_nome_OrdemCriação  | VW_TESTE_10               |    
            | Sequencia       | SEQ_nome_OrdemCriação | SEQ_Proposição_01         |  
            | Procedure       | PROC_NomeSobrenome    | PROC_InsereProposição     | 
            | Function        | FUNC_NomeSobrenome    | FuncConsultsProposição    |                    
            | Trigger         | TRI_NomeRegra         | TRI_ProposiçãoFindeSemana |                   
            | Cursor          | CUR_Nome              | CUR_RetornaProposição     |                                       
            +---------------------------------------------------------------------+
