# O caminho para se tornar um desenvolvedor

   Pra começar, é muito difícil mapear todos os conhecimentos essenciais para desenvolvedores, porém, como recomendação pessoal, deixo aqui aquilo que encontro como essencial para iniciar no caminho da programação, seja você um desenvolvedor front-end, back-end ou devops.

   Antes de qualquer coisa, deixemos claro que existem diversos caminhos a se trilhar, e você precisa estar ciente do que significam os termos front-end e back-end. Não vou explicar isso aqui visto que há muito conteúdo na internet, então coloque em prática a primeira habilidade essencial para um desenvolvedor:
   
   ### Saber "dar um google"
   
   A história por trás do programador gênio que sabe tudo, é um mito, você definitivamente não precisa decorar e saber tudo sobre a linguagem que usa ou até mesmo coisas mais alto-nível no setor. Porém, precisa saber onde procurar e como procurar, plataformas como [Stack Overflow](https://stackoverflow.com/) estão demonstrando há anos que mesmo você tendo zilhões de anos de experiência, ainda podem surgir as dúvidas mais inusitadas, portanto, não tenha medo de pesquisar como inserir um item em uma lista html, pesquisar vai economizar o seu tempo.
   
   ### Trabalho em equipe
   
   Acredito que aqui eu sequer precise dizer muita coisa, sei que como desenvolvedor gostamos de fazer as coisas sozinhos, eu sinceramente penso inúmeras vezes sobre o quanto seria mais fácil se eu trabalhasse sozinho, mas aqui que está o erro, talvez fosse mais fácil, mas sem dúvidas, seria mais demorado. Sozinho um desenvolvedor não chega a lugar nenhum. Pense em Linus Torvalds, o criador do linux, você acha que ele conseguiria criar o linux do jeito que é hoje sozinho? Nem fu%*$@#, o linux kernel sozinho tem mais de 20 milhões de linhas de código. Então, faça um favor a si mesmo e aprenda a trabalhar em equipe, sua carreira vai dar muito mais certo assim. Pesquise sobre projetos open-source e tente contribuir, mesmo que seja com uma coisa quase imperceptível.
   
   ### Aguentar ficar na frente de um computador por um bom tempo
   
   Bom, outra habilidade auto-explicativa, mas apenas complementando, é óbvio que como desenvolvedor você provavelmente vai passar a maior parte do seu tempo em frente ao computador. Porém, tome cuidado, faça exercícios, tenha postura, coma de maneira saudável, tente mudar de ambiente de vez em quando, boa parte do seu tempo sequer precisa ser em frente ao computador, tente variar um pouco, busque escrever pseudo-codigos em papel, e por ai vai. Apenas, tome cuidado.
   
   ### Uso básico do terminal
   
   Entrando agora nas partes mais técnicas, o uso do terminal é muito importante pois melhora significativamente uma das coisas mais buscadas no mundo de hoje: Produtividade. Seja você um usuário Linux, Mac ou Windows, certamente o uso do terminal pode te ajudar. Geralmente eu aconselho o uso de OS Unix-based, a curva de aprendizado parece ser mais tranquila, mas os comandos básicos no powershell do windows também são tranquilos de aprender.
   
   ## Princípios de desenvolvimento
   
   Qualquer um pode escrever um código, mas um bom código? Ai fica bem mais complicado. Em sua carreira, você provavelmente vai encontrar muito código "espaguete", cheio de condicionais toscas, e se você alterar uma variável, bom, adeus ao seu software. Isso costuma acontecer quando os desenvolvedores ou tinham um prazo muito apertado ou tinham pouca experiência. É difícil colocar um software em produção sem experiência, pelo que eu já vi na área, diria que se você tiver menos de mil horas desenvolvendo, isso já pode ser um "problema". Enquanto muitos programadores ainda hoje priorizam um código que "funcione", acredito ser melhor um código que possa ser mantido (onde a manutenção não custaria caro). Portanto, seguem alguns princípios que sugiro que sejam seguidos, conforme o tempo passa, você vai saber melhor quando e onde aplicá-los, por hora, tente lembrar deles sempre que desenvolver:
   
   ### KISS
   
   Com um acrônimo bem legal, KISS ou "Keep it simple, stupid" é um dos princípios mais importantes, um princípio que pode ser aplicado a qualquer área da vida, mas especialmente na arte de escrever um código.

   Começa logo pela definição do escopo do que planejam criar, você pode simplesmente amar video-games, mas não pense que vai conseguir desenvolver o próximo Diablo, primeiro que se você tentar, provavelmente iria estar desmotivado muito antes de conseguir. Portanto, simplifique, quando você achar que simplificou o suficiente, simplifique mais uma vez.
   
   Mesmo depois que você já estiver desenvolvendo, mantenha seu código simples, códigos muito complexos demoram mais pra desenvolver e escrever, é mais propenso a bugs e erros, e muito mais difícil de ser modificado posteriormente. Nas sábias palavras de Antoine de Saint-Exupery, "Perfeição é atingida, não quando não há nada mais a adicionar, mas sim quando não há nada mais para tirar".
   
   ### DRY
   
   DRY ou "Don't repeat yourself" é um dos princípios essenciais para o código limpo. Busca evitar repetição na escrita e na lógica do seu código, quando você notar que está escrevendo sempre a mesma coisa no seu código, lembre-se deste princípio. O oposto desse principio seria o WET code ou "write everything twice" ou, como eu prefiro chamar "waste everyone's time".
   
   Porém, apesar de importante, tome cuidado, vão existir momentos onde escrever todas as coisas apenas uma vez pode ir contra outros princípios aqui listados, priorize sempre código com fácil manutenção e fácil leitura.
   
   ### Refactor, refactor, refactor
   
   Em minhas aulas de cálculo, tive que aprender uma das coisas que mais mudaram minha vida, e que na programação tem grande importância. Você nunca estará certo de primeira, assim como uma questão matemática complexa dificílmente será resolvida na primeira tentativa (e se for, talvez alguma coisa esteja errada), com código também é assim, ele nunca vai estar perfeito logo na primeira escrita, pode parecer, mas a medida que o programa vai crescendo, novas features implementadas podem sofrer limitações devido a este código. Você não precisa reescrever seu código 200 vezes antes de mandar pra produção, mas deve entender que refatorar código, além de saudável (para o programa), é necessário.
   
   ### Clean Code > Clever Code
   
   Deixa seu orgulho de lado e esqueça sobre código "esperto", eu sei, é muito bom saber que algum amigo desenvolvedor sequer entendeu seu código ultra otimizado e curto. Mas isso só serve pra mostrar o quanto você entende de alguma linguagem, não o quanto você é bom como desenvolvedor. O seu nível como desenvolvedor se baseia muito mais no seu trabalho em equipe, código limpo e simples.
   
   ___
   
   Estes são, pra mim, os quatro princípios mais importantes, mas existem muitos outros, vai então uma lista pra você dar uma olhada:
   * Open/Closed
   * Composition > Inheritance
   * Single Responsibility
   * Separation of Concerns
   * YAGNI
   * Avoid Premature Optimization
   
   ## Outras questões técnicas
   
   Fica aqui mais uma lista de assuntos técnicos que vão fazer a diferença na sua carreira:
   * Estrutura de dados e algoritmos
   * Controle de versionamento (Git)
   * Github
   * Licensas
   * Versionamento semântico
   * SSH
   * HTTP/HTTPS
   * Design Patterns
   
   ___
   
   A princípio seria isso, fique a vontade para me indicar coisas a adicionar ou até mesmo remover, estou pronto pra ouvir. Obrigado, até a próxima.
