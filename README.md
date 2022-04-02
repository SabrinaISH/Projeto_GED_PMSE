# Projeto_GED_PMSE
Projeto de gerenciamento eletrônico de documentos da PMSE

O objetivo desse projeto é desenvolver um sistema de gerenciamento eletrônico de documentos para a PMSE. O sistema deve permitir que os usuários realizem o upload dos seus documentos digitalizados e o sistema deve processar o documento digitalizado tranformando o mesmo em um texto. O sistema deve disponibiizar interface amigável para busca desses documentos. 

O que motivou a concepção desse projeto:

  1 - Falta de espaço físico para armazenar a documentação gerada em papel;

  2- Necessidade de transparência no acesso à informação;

  3- Dificuldade em buscar informações antigas;

Premissas

Por se tratar de uma organização que contem dados sigilosos e de extrema importância, foram definidas as seguintes premissas:

  1- Disponibilidade - o sistema deve estar sempre disponível quando os usuários precisarem e as consultas devem ter um tempo de resposta viável.

  2- Confidencialidade - as informações do sistema devem estar protegidas para que somente determinados usuários possam ter acesso a determinadas informações e também    o  deve estar protegido de ataques ciberneticos onde as informações podem ser roubadas.

  3- Integridade - as informações do sistema devem ser armazenadas e exibidas do mesmo modo como foram criados, sem que haja interferência externa para corrompê-las,     comprometê-las ou danificá-las.

  4- Autenticidade - o sistema deve garantir que o usuário que está acessando o sistema e suas informações seja realmente quem ele alega ser.

  5- Não repúdio - O sistema deve conter serviços que possam fornecer prova de integridade e da origem dos dados. Os serviços devem ser capazes de não permitir que a     integridade seja forjada e devem permitir que sejam verificados por terceiros, garantindo que os dados são genuínos e que não podem ser refutados. 

  6- O sistema deve estar integrado ao sistema do RH.

Papéis dentro do sistema:

  1 - Usuário: pode pesquisar documentos (Qualquer pessoa na organização é um usuário).

  2- Funcionário do PMSE: pode pesquisar documentos e incluir documentos pessoais destinados ao RH e/ou para  seu superior direto e/ou para o setor médico.

  3 - Editor: cada setor possui um ou mais editores responsáveis por inserir no sistema documentos antigos. Esses documentos devem ser inputados no sistema através da    digitalização.

  4- Gerente: responsável pela atribuição de funções em seu setor.

  5- Administrador: responsável pelo cadastro de novos gerentes.
  
  Principais funcionalidades do sistema:
  
  1 - Cadastrar gerentes
    
    2- Atribuir funções (perfil de acesso) aos usuários
    
    3- Consultar documentos
      3.1 - Incluir auditoria nos dados consutados
    
    4- Cadastrar documentos
      4.1 - Realizar upload
      4.2 - Processar documentos (transformar o documento digital em texto)
      4.3- Incluir auditoria nos dados incluidos
    
    5- Aprovar documentos
    
    6- Cadastrar biometria
    
    7- Autenticar usuário
    
      7.1  Validar permissoes de acesso
  
   
     
