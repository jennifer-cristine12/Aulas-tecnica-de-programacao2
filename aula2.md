Processo de desenvolvimento de software

- definição

       -analise de sistema
  
       -analise de requesitos

- construção

        -projeto
 
       -codificação
 
       -teste
 
       -implantação
  
              -metodo
              -logica ParaConsistente
              -Evidencia
              -extrair contradição



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
    
       -banco de dados
  
              -entidades
  
              -atributos
  
              -relacionamento
  
              -tipos de dados
  
              -constraints

- aplicação

   - BD

          -relacional
          -mer - logico
          -mer - fisico
          -script
          -tabelas
          -procedures

~~~~SQL

create table if not EXISTS conta(
     nr_banco int(3),
     nr_conta varchar(5),
    primary key(nr_banco,nr_conta)
    );
SELECT * from conta;

~~~~
       

   - software

            -orientação a objetos
            -metodos de padronização
            -design patterns
             -MVC
             -DAO
Fases
- definição de grupos
- definição dos especialistas
- Método fabio de modelagem de dados

          -passo 1: listar todos os subtantivos
                -problema
                -proposição
          -passo 2: listar todos os objetos, significados ao negocio
                -problema
                -proposição
          -passo 3: eliminar as redundancias
                -problema
          -passo 4: matriz de relacionamento
                  +------------------------------------------+
                  |      /     | curso   | aluno  | professor|  
                  |  curso     |    -    | contem | contem   |
                  |  aluno     | cursa   |   -    |    -     |                    
                  |  professor | contido |  -     |    -     |                                              
                  +------------------------------------------+
            -perguntar: de que forma a entidade a se relaciona com a entidade b
- minimização
  
         -maior certeza e menor incerteza
         
- certeza
  
       - λ
       - grau de evidencia
       - grau de certeza
         - favoravel
                -viabilidade
         - desavoravel
                -duvida

  
- incerteza
