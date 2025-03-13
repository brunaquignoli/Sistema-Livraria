# Sistema-Livraria
Sistema de Livraria implementada em Java com comunicação com banco de dados no MySQL.

# main classe
BIBLIOTECA

# atributos
- livros[lista]

# métodos
+ adicionarLivro(livro) 
+ removerLivro(titulo: String) 
+ listarLivros(): void         
+ alugarLivro(titulo: String)  
+ devolverLivro(titulo: String)


LIVRO

# atributos
- livro: String
- autor: String
- genero: String
- classificação: String
- paginas: int
- quantidade: int

# métodos
+ getTitulo(): String
+ getAutor(): String
+ getGenero(): String
+ getClassificacao(): String
+ getPaginas(): int
+ getQuantidade(): int



BancoDeDados
# atributos
- conexão: // códigos
# métodos
+ conectar(): void
+ inserirLivro(livro: String): void
+ removerLivro(livro: String): void
+ buscarLivro(titulo: String): String
+ atualizarQuantidade(titulo: String, quantidade: int): void


# sobre a parte de conexão com Banco de Dados: 
    https://youtu.be/1v4iiTRFymE?si=6JbOW3o2LgxvdguO (vídeo ensinando)
    https://www.devmedia.com.br/jdbc-tutorial/6638 (link sobre o site)

