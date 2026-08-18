Funcionalidades do Back-End — José Fazendas
1- Login
Rota: /login
O sistema vai receber o e-mail e a senha do usuário para verificar se ele possui uma conta.
Regra de negócio: O usuário só poderá entrar se o e-mail e a senha estiverem corretos.
2- Cadastro de usuário
Rota: /cadastrarUsuario
Essa função será responsável por cadastrar novos usuários no sistema.
Regra de negócio: Não será permitido cadastrar mais de uma pessoa com o mesmo CPF ou e-mail.
3- Visualizar os leilões
Rota: /leiloes
Essa função vai mostrar os galos que estão disponíveis para participar dos leilões.
Regra de negócio: O usuário só poderá dar lance nos leilões que ainda estiverem abertos.
4- Dar lance
Rota: /darLance
Essa função vai receber o usuário, o galo escolhido e o valor que ele deseja oferecer.
Regra de negócio: O novo lance precisa ser maior que o lance atual. Se o valor for menor ou igual, o sistema não aceitará o lance.
Quando o lance for registrado, o site também deverá reproduzir um barulho de galo.
5- Encerrar leilão
Rota: /encerrarLeilao
Essa função será usada para finalizar um leilão quando o tempo determinado acabar.
Regra de negócio: Depois que o leilão for encerrado, não será possível fazer novos lances. O usuário que tiver dado o maior lance será considerado o vencedor.
6- Pagamento
Rota: /pagamento
Essa função será responsável pelo pagamento do galo que foi arrematado.
Regra de negócio: O sistema deverá aceitar pagamento por PIX ou cartão. O pagamento precisa ser aprovado para finalizar a compra.
7- Cadastrar galo
Rota: /cadastrarGalo
Essa função permitirá que o administrador coloque um novo galo no sistema para participar de um leilão.
Regra de negócio: O administrador deverá informar os dados necessários do galo e definir o valor inicial do leilão.
8- Segurança
O sistema deverá controlar o acesso dos usuários.
Regra de negócio: Somente usuários logados poderão fazer lances e realizar pagamentos. Apenas o administrador poderá cadastrar novos galos e gerenciar os leilões.
Resumo
O Back-End será responsável por receber as informações do site, verificar as regras do leilão, salvar os dados no banco de dados e controlar os usuários, lances e pagamentos.

