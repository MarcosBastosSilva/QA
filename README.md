1)Cenário: Exibição correta da imagem do produto <br>
Dado que o usuário esteja na página de produtos <br>
Quando o usuário visualizar um produto específico <br> 
Então a imagem do produto deve corresponder à descrição do produto e à sua categoria <br>

2)Cenário: Filtros de produtos funcionando corretamente <br>
Dado que o usuário esteja na página de filtragem de produtos <br>
E o usuário selecione um filtro como "Price low to high" <br>
Quando o usuário aplicar o filtro <br>
Então os produtos exibidos devem corresponder à faixa de preço do filtro selecionado <br>

3)Cenário: Correção da exibição do produto ao clicar nas promoções <br>
Dado que o usuário esteja na página inicial <br>
Quando o usuário clicar em um produto de promoção (por exemplo, notebook) <br>
Então a página deve exibir o produto correto relacionado à promoção <br>
Cenário: Funcionalidade de login com credenciais válidas <br>

4)Dado que o usuário tenha uma conta cadastrada no site <br>
E o usuário insira um e-mail e senha válidos na página de login <br>
Quando o usuário clicar no botão "Entrar" <br>
Então o usuário deve ser redirecionado para sua conta <br>

5)Cenário: Erro ao tentar login com credenciais inválidas <br>
Dado que o usuário não tenha uma conta cadastrada no site <br>
E o usuário insira um e-mail e senha inválidos na página de login <br>
Quando o usuário clicar no botão "Entrar" <br>
Então o sistema deve exibir uma mensagem de erro dizendo "Credenciais inválidas" <br>

6)Cenário: Não permitir produtos inválidos no carrinho <br>
Dado que o usuário tenha adicionado um produto ao carrinho <br>
Quando o usuário tentar remover o produto do carrinho <br>
Então o produto deve ser removido e não deve aparecer mais no carrinho <br>

7)Cenário: Preço correto no checkout <br>
Dado que o usuário tenha adicionado três produtos ao carrinho <br>
Quando o usuário for para a página de checkout <br>
Então o preço total no checkout deve corresponder à soma dos preços dos produtos no carrinho <br>

8)Cenário: Formulário de inscrição na newsletter validando e-mail corretamente <br>
Dado que o usuário esteja na seção de inscrição para a newsletter <br>
E o usuário insira um e-mail válido no campo de inscrição <br>
Quando o usuário clicar no botão de "Inscrever" <br>
Então o sistema deve enviar uma confirmação de inscrição para o e-mail fornecido <br>

9)Cenário: Erro ao tentar inserir um nome inválido no cadastro <br>
Dado que o usuário esteja na página de cadastro <br>
E o usuário insira caracteres inválidos no campo "Nome" <br>
Quando o usuário tentar submeter o formulário <br>
Então o sistema deve exibir uma mensagem de erro dizendo "Nome inválido" <br>

10)Cenário: Falha ao tentar excluir uma conta <br>
Dado que o usuário tenha uma conta registrada no site <br>
Quando o usuário tentar excluir sua conta a partir da seção "Configurações" <br>
Então o sistema deve exibir uma mensagem de erro e não permitir que a conta seja excluída <br>


