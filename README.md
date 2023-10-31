# Criando NoSQL-MongoDB (V.5.0.22)

1 - Crie uma pasta no diretório C:\ chamada de "data" e dentro dela outra chamada "db", caminho completo: c:\data\db.

2 - Após instalado abra um prompt de comando e digite os comandos: "cd C:\Program Files\MongoDB\Server\5.0\bin" e "mongod --dbpath c:\data\db" e aguarde sua execução.

3 - Digite o comnando: "mongo" para entrar dentro do prompt do próprio mongo.

4 - Digite "" para ver os bancos cadastrados.

## Criando ou excluindo bancos
Dica: utilize o comando "show databases" para verificar o progresso.

5 - Dentro do prompt do banco, use o comando: "use teste" para criar um banco de dados teste, automaticamente ele irá mudar para este banco. 
##### OBS: Se não houver um banco chamado de teste ele irá cirar um novo e ainda assim ele não criará esse banco, a menos que tenha uma coleção dentro dele, então, vamos criar uma.

6 - Para criar uma coleção digite: "db.colecao_teste.insertOne({ chave1: "valor1", })" e use o comando "show collections" para verificar se tudo ocorreu bem.

7 - Agora que o banco "teste" foi criado com sucesso, garanta que voce está no banco certo para exclui-lo, digite "use teste" e depois "db.dropDatabase()"
