Este é um projeto de aplicativo Android focado em navegação entre telas utilizando a linguagem Kotlin. O app simula um fluxo onde o usuário 
parte da tela de login para acessar informações como o perfil do um usuário ou a lista de pedidos.

O objetivo dessa prova é utilizar um projeto já existente que começamos com o professor e fazer novas mudanças implementando a lógica de
passagem de parâmetros entre as telas.

- Parâmetros obrigatórios na tela de Perfil:
  Na rota da tela de perfil eu adicionei um placeholder, então quando a pessoa acessar essa tela vai aparecer o nome do usuário. Eu utilizei
  o nome do Cristiano Ronaldo como exemplo, mas caso não tenha um usuário específico cadastrado, vai aparecer o valor padrão "Usuário Genérico".
  
- Passagem de parâmetros opcionais na tela de Pedidos:
  Nesse commit foi a adição do parâmetro do nome que vai aparecer na sua tela de lista de pedidos. Também adicionei um valor padrão "Cliente Genérico"
  caso não tenha um usuário específico definido.

- Inserindo valor ao parâmetro opcional na tela de Pedidos:
  Agora eu apenas adicionei um valor ao parâmetro do Cliente. Utilizei o mesmo nome do Cristiano Ronaldo na lista de pedidos como exemplo.

- Passagem de múltiplos parâmetros:
  Para concluir, com a passagem do parâmetro da idade do usuário, criei um listOf e fiz a tela de perfil receber dois dados ao mesmo tempo.
  Atualizei a interface da PerfilScreen para mostrar uma frase dinâmica ("PERFIL - $nome tem $idade anos") e usei como exemplo o nome do Cristiano Ronaldo e sua idade que é 41 anos.

  Essas 4 etapas foram feitas em apenas 1 commit que é 
