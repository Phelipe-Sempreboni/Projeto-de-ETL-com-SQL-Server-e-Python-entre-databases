# Projeto SQL Server x Python para dados ETL entre databases no SQL Server

---
#### Este projeto criado com base em um (business case) ou (caso de negócio) real, onde, foram utilizas as ferramentas SQL Server e Python para criação de uma ETL entre databases dentro do SQL Server. 

Imagine que temos um database dentro do SQL Server Management Studio que seria o principal, onde este recebe as informações dos sistemas origem/legados da empresa e todos dados ficam alocados nele, por meio de schemas para realizar seus agrupamentos, onde temos ETLs (Extração, Transformação e Carregamentos) de dados por peridiocidade de acordo com a politica da empresa, setor, gerencia, diretoria e demanda dos usuários.

Imagine também que temos setores dentro dessa empresa, como Recursos Humanos (RH), Engenharia (ENG), Meio Ambiente (MA), etc, e cada um desses setores usa algum dado/tabela dessa database principal, onde seria necessário duplicar as informações do database principal para os databases de ramificações, pois, conforme politica da empresa, somente a área de TI e Cyber Security tem acesso e permissão a este database principal. Iremos utilziar como exemplo neste projeto o setor do Recursos Humanos (RH), que está localizado no schema (rh) e será o nosso business case ou caso de negócio para este projeto.

Notar que faremos uma ETL entre databases dentro do SQL Server, porém, este projeto contará desde a criação do database, criação de tabelas, inserção dados até chegar no arquivo Python para auxiliar nessa ETL.

Espero que este projeto ajude de alguma maneira seu processo, seu estudo, trabalho de faculdade ou curso, qualquer coisa só deixar um (ISSUE) no GitHub.

---




