### Repositório do Trabalho Prático - Data de Entrega (22/01/2021)

A presente componente de avaliação prática é composta pelo desenvolvimento de um sistema de **Data Warehousing**, bem como um sistema de Business Intelligence para suporte à decisão.

Modo de execução:

 1. Download do CSV (`/Dataset/`)
 3. Criar a base de dados (`/Modelos/ModeloLogico.mwb ou /Modelos/ModeloFisico.sql`) no MySQL Workbench
 5. Correr os scripts (`/Povoamento/scripts.sql`) 
 4. Correr o parser (`/Povoamento/Parser/`) 
   * certificar que em `/Povoamento/Parser/csv/` POSSUI o dataset e em `/Povoamento/Parser/sql/` NÃO EXSTE nenhum ficheiro 
 5. Aceder ao MySQL Workbench, estabelecer conexão à root e efectuar :
   ```sh
   File > Run SQL Script > ficheiro criado pelo parser > default schema : airbnb
   ```
 6. Correr alguns scripts para verificar se tudo correu bem:
   ```sh
   Exemplo: call airbnb.getLocation(13905993);
   ```
  
Link do relatório em desenvolvimento : https://pt.overleaf.com/1653288269cdbczffmqdtx  
