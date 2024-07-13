# Projeto_Final_Pipeline_de_Dados_do_Telegram

Desenvolvimento do projeto de Pipeline de dados do Telegram, desde sua criação até automação com bot no Telegram e coleta/tratativa de dados.

Foi construído um pipeline de dados que ingere, processa, armazena e expõe mensagens de um grupo do Telegram para que profissionais de dados possam realizar análises. 
A arquitetura proposta é dividida em duas: transacional, no Telegram, onde os dados são produzidos, e analítica, na Amazon Web Services (AWS), onde os dados são analisados.

Neste projeto foram criados no AWS - Amazon Web Service: 

Criado buckets no AWS S3;
Criado uma funções no AWS Lambda;
Criado uma API web no AWS API Gateway;
Configurado o webhook da API de bots do Telegram.
