def conectar_banco():
    return mysql.connector.connect(
        host = "localhost", #ou o endereço do seu banco de dados 
        user = "root", #seu usuario
        password = "quintafeira" #o nome do banco de dados
    )
