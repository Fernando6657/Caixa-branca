# Caixa-branca
o codigo contem 4 erros sendo eles: (tambem estão comentados no codigo)
1.injeção de SQL (1 erro de segurança):
Construção de SQL diretamente com valores do usuário (login e senha), o que deixa o código vulnerável a ataques de injeção de SQL.

2.Vazamento de Recursos (2 erros de gerenciamento de recursos):
O Statement não é fechado.
O ResultSet não é fechado.
Bloco catch Vazio (1 erro de tratamento de erros):

3.O bloco catch está vazio, então os erros não são registrados ou tratados.

4.Driver e String de Conexão Desatualizados (1 erro de compatibilidade):
Uso de um driver JDBC antigo (com.mysql.Driver) e uma string de conexão que pode não ser compatível com versões modernas do MySQL.
