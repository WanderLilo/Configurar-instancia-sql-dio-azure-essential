# Desafio DIO - Azure Essential 

## Configurando uma instância de banco de dados no azure 

1 - No menu lateral esquerdo, selecione Banco de Dados SQL

2 - Clique em Criar

3 - Na seção detalhes do projeto, informe Assinatura e Grupo de Recursos

4 - Na seção detalhes do banco de dados, informe:
  - Nome do banco de dados  
  - Servidor, caso ainda nao tenha um crie um novo

    Na criação do servidor informe:
      - Nome do servidor
      - Localização
      - Tipo de Autentiçação (Sql, Microsoft Entra ou ambos)

5 - Na seção Redundancia de Armazenamento de Backup, selecione uma das opções:  
  - Armazenamento de backup com redundância local  
  - Armazenamento de backup com redundância de zona  
  - Armazenamento de backup com redundância de geográfica

[**Para mais detalhes, consulte a documentação oficial**] (https://learn.microsoft.com/pt-br/azure/azure-sql/managed-instance/instance-create-quickstart?view=azuresql&tabs=azure-portal)
