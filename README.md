# Livraria: um app em CakePHP em PT-BR

PPT do Curso: https://docs.google.com/presentation/d/1N30RcEOx484jz38Tr6gS3EHC0dBRaTUPN61T50dpcOU/edit?usp=sharing


# Contém todos os tipos de associações: 


- hasOne (1..1): Funcionário tem uma Habilitação
- hasMany (1..*): Editora tem muitos Livros
- belongsTo (*..1): Livros pertencem a uma Editora
- belongsToMany (*..*): Livros têm muitos Autores e Autores têm muitos Livros.


Associações especiais:


- auto Relacionamento: Funcionário tem gerente Gerente (Funcionário).
- belongsToMany (through): Pedido tem muitos Livros (através de ItemPedido).
- árvore: Gênero tem nós filhos, irmãos e pais.
