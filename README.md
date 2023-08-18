Processo de desenvolvimento de software

- definição

       -analise de sistema
  
       -analise de requesitos

- construção

        -projeto
 
       -codificação
 
       -teste
 
       -implantação

- manutenção

      -Entendimento
   
      -Modificação
   
      -revalidação

Qual fase nós estamos

- engenharia de sistema

       -levantamento de requesitos

- analise

       -o que fazer?
  
       -banco de dados
  
       -entidades
  
       -atributos
  
       -relacionamento
  
       -tipos de dados



- projeto

        -como fazer?

- aplicação

   - BD

          -relacional
          -mer - logico
          -mer - fisico
          -script

~~~~SQL

create table if not EXISTS conta(
     nr_banco int(3),
     nr_conta varchar(5),
    primary key(nr_banco,nr_conta)
    );
SELECT * from conta;

~~~~
       -tabelas
       -procedures

   - software

            -orientação a objetos
            -metodos de padronização
            -design patterns
             -MVC
             -DAO
