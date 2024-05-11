# Imersao_IA
Foi proposto pela Alura desenvolver um projeto de integração com as ferramentas da Google de Inteligencia Artificial.

>>> JOGO ENCONTRE SEU AMIGO

Neste JOGO, com a ajuda da IA, será criada uma lista com 10 pontos turisticos no mundo de forma totalmente aleatória.
Simulando que uma pessoa irá percorrer estes 10 lugares um em cada dia, o jogador vai precisar encontrar este amigo visitando cada lugar.
A idéia foi inspirada em um clássico "Onde no mundo esta Carmen Sandiego ?". 

Bom jogo.


>>> COMO ESTE JOGO FOI CRIADO ?

Foi utilizado o ambiente do Google AI Studio para a codificação e o COLAB para execução.

Basta reproduzir passo a passo para cria-lo novamente, ou modifica-lo.

[CMD] preciso de ajuda em um projeto pyton
[CMD] response = model.generate_content("Liste 5 cidades do mundo que possuem aeroportos internacionais, apenas os nomes listados separados por virgula")
[CMD] gere o codigo para pegar a resposta desta chamada e guardar em uma variavel indexada
[CMD] adicione no codigo uma chamada "response = model.generate_content("Liste o nome de um museu, um time de futebol e um lugar turistico apenas com os nomes separados por virgula") para cada cidade que foi recebida anteriormente e armazene em uma nova variavel indexada
[CMD] um amigo vai viajar pelo mundo percorrendo estas cidades. em cada cidade ele vai parar e conhecer 2 lugares que estão nesta lista. assim, ele vai percorrer até 10 lugares diferentes, sendo que de cada cidade ele vai para outra que não visitou anteriormente ainda.
[CMD] agora adicione ao programa o código que sorteie estes 10 pontos seguindo esta regra da viagem e armaze a lista dos lugares para visitar 
[CMD] adicione na tabela de lugares a visitar o nome da cidade
[CMD] vamos criar um jogo tipo "encontre o seu amigo" usando a lista dos lugares que ele vai visitar. Neste jogo, vamos ter apenas 10 tentativas para encontrar o amigo, pois, cada tentativa seria 1 dos lugares que o amigo vai visitar na ordem definida. O jogo vai mostrar para o jogador qual o nome da primeira cidade que o amigo esta visitando. O jogo deve listar para o jogador as 3 alternativas de lugares possiveis de cada cidade que o amigo esta visitando e perguntar para o jogador qual alternativa ele escolheria para procurar o amigo. O  jogo então vai comparar se a resposta esta de acordo com a ordem que temos armazenada dos lugares que o amigo vai percorrer. Se ele acertar o jogo termina e mostra a mensagem de "Parabéns você econtrou com seu amigo e vai continuar a viagem", caso contrário, o jogo deve mostrar que "Infelizmente vocês não se econtraram ainda, amanhã talvez encontre com seu amigo", e assim simular que passou mais um dia e continuar a fazer a pergunta para o jogador agora com o próximo lugar que o amigo esta visitando. 
