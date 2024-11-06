# API-classificacao-de-sentimento
Criacao de uma API contendo um  modelo de classificacao onde separa o texto em dois grupos:Positivo e Negativo.Utilizando um dataset do Kaggle com 1 milhao de tweets em ingles

# 1-Pré-Processamento

![image](https://github.com/user-attachments/assets/f1fe50eb-88bc-47a6-a465-6c96a0554470)
![image](https://github.com/user-attachments/assets/be43674a-301e-444c-af80-41942b3bbbdb)
![image](https://github.com/user-attachments/assets/191c6f3f-f456-45ee-a40d-9da4c93a8156)

-->Comecaremos a mexer nos textos,comecando com a remocao de caracteres indevidos e desnecessarios

![image](https://github.com/user-attachments/assets/63253c71-b6f6-4dbc-a01a-43dfe046b5dc)
![image](https://github.com/user-attachments/assets/ac8989ac-16de-4622-b2a4-9d666578dc82)
![image](https://github.com/user-attachments/assets/d2856152-f7ff-4026-a976-c9c79e4441d6)

-->Agora,iremos remover as stop words(palavras que nao agregam sentido,nem positivo ou negativo) com a criacao de uma nova coluna ['clean_text'] 
![image](https://github.com/user-attachments/assets/86b7ed21-eb10-45dd-a57c-4ddfb8dd176e)
![image](https://github.com/user-attachments/assets/587cf15b-f9c5-4e98-a094-8ffa2e9995b0)
![image](https://github.com/user-attachments/assets/54dda82f-60be-45c1-b394-5e1d535b1b0a)

-->Agora temos o dataset pronto e limpo para a criacao do modelo!

# 2-Analise e insights 

Criando uma coluna com a largura dos tweets
![image](https://github.com/user-attachments/assets/62200628-59b1-4d07-8023-6d9fc0b18f37)
![image](https://github.com/user-attachments/assets/1d503363-09d6-4598-9d76-86c120c54673)
![image](https://github.com/user-attachments/assets/3eed1977-c669-4c74-9cef-53d1990b0184)
![image](https://github.com/user-attachments/assets/905f3ebc-10f6-4d56-8327-5db28f6811a3)

Percebemos que a largura dos tweets sao semelhantes em ambas classes
Vamos criar uma WordCloud com as palavras que mais aparecem

![image](https://github.com/user-attachments/assets/c343af31-3a8b-4079-ae2c-c18841c4094c)
![image](https://github.com/user-attachments/assets/9616c0a5-dd36-429f-acfc-618b885a4d0c)
![image](https://github.com/user-attachments/assets/40e10654-3973-479f-a85a-2968588dd0ef)
![image](https://github.com/user-attachments/assets/542bd5c4-7745-4e2c-b545-ed32cbc7d9ea)

# 3-Criacao Do Modelo
![image](https://github.com/user-attachments/assets/6fd64b9f-4305-4edd-b331-67af23d1e1ea)
![image](https://github.com/user-attachments/assets/7ae5cbec-70cb-4cc0-8b14-925d6e175e68)

->MODELAGEM

![image](https://github.com/user-attachments/assets/911cc1f1-22ea-412e-af35-59b1e754a26c)
![image](https://github.com/user-attachments/assets/8a07375e-6cbc-4ecd-a15c-fed2eceb9270)
![image](https://github.com/user-attachments/assets/73e1d74c-6a31-41eb-9831-90e1eba62bdd)
![image](https://github.com/user-attachments/assets/e881ba8b-8cfc-4db6-97eb-891eb9631bd4)
![image](https://github.com/user-attachments/assets/3c87c1e5-1ef9-4443-8bbc-5364bc52a388)
![image](https://github.com/user-attachments/assets/980963b9-f4eb-4cbe-8c51-26d57d5f895d)
![image](https://github.com/user-attachments/assets/040a7988-e14d-4541-8640-3e7d6fb7302b)
![image](https://github.com/user-attachments/assets/7a356f1a-d50f-4e89-a9ea-b19efbed1d59)
![image](https://github.com/user-attachments/assets/28925f7a-75e1-4381-b85b-f038930f99a7)
-->Agora temos o modelo pronto,iremos criar a API

# 4-API
Já no vscode:
![image](https://github.com/user-attachments/assets/37cf053a-f98a-44f9-90e5-7d8796b1aee1)
![image](https://github.com/user-attachments/assets/1f1f1cc1-6afe-4b7f-9415-abbbb9316fd0)
![image](https://github.com/user-attachments/assets/bf52b467-4634-48fd-a48c-be5be3f84ad5)

E a API esta pronta pra usos diversos.Obrigado pela atencao!!









