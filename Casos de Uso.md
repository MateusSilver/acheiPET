# Casos de Uso - AcheiPET

-----
#### Funcionalidade: FG01: Fazer login no sistema acheiPET como usuario

**Cenário**: FG01-C01 Usuário faz login com sucesso no sistema acheiPET
* Dado: Que o usuário tem acesso a página de login do sistema
* Quando: Ele insere os dados de email e/ou usuário e senha
* e: confirma com o botao entrar
* Então: O sistema o redireciona para a página principal

**Cenário**: FG01-C02 Usuario insere credenciais incorretas de login no sistema acheiPET
* Dado: Que o usuário tem acesso a página de login do sistema
* Quando: Ele insere os dados de email e/ou usuário e senha inválidos
* e: confirma com o botao entrar
* Então: O sistema o exibirá uma mensagem de aviso avisando que as credencais estão incorretas

**Cenario**: FG01-C03 Usuario deixa campos de login em branco no sistema acheiPET
* Dado: Que o usuário tem acesso a página de login do sistema
* Quando: Ele  confirma com o botao entrar sem adicionar nada aos campos de login
* Então: O sistema o exibirá uma mensagem de aviso avisando os campos que nao foram preenchidos corretamente

-----
#### Funcionalidade: FG02: Visualizar posts de animais perdidos e achados

**Cenario**: FG02-C01 Usuário Logado no sistema
* Dado: Que o usuario esta logado no sistema,
* Quando: acessar a página Home
* Então: Visualizara uma lista de posts personalizado com base na sua região

**Cenario**: FG02-C02 Usuário nao esta logado no sistema
* Dado: Que o usuário não esta logado no sistema
* Quando: acessar a página Home
* Então: Seré redirecionado para a página de login

-----


#### Funcionalidade FG03a: Criar postagem sobre animal perdido

**Cenario**: FG03a-C01 Usuário preenche dados suficientes
* Dado: que o usuário está na página Home
* e: ativa a funcionalidade de criar um novo post
* Quando: Preenche os dados de animal
* e: Marca como animal perdido
* e: Clicar em postar
* Então: Postagem é adicionada ao feed de postagens local marcado como animal perdido.

**Cenario**: FG03a-C02 Usuário preenche dados insuficientes
* Dado: que o usuário está na página home
* e: ativa a funcionalidade de criar um novo post
* Quando: Preenche os dados de animal incsuficientes
* e: Marca como animal perdido
* e: Clicar em postar
* Então: Postagem é adicionada ao feed de postagens local marcado como animal perdido, estando presente em feed de animais perdidos.

-----
#### Funcionalidade FG03b: Criar postagem sobre animal achado

**Cenario**: FG03b-C01 Usuário preenche dados suficientes
* Dado: que o usuário está na página Home
* e: ativa a funcionalidade de criar um novo post
* Quando: Preenche os dados de animal
* e: Marca como animal achado
* e: Clicar em postar
* Então: Postagem é adicionada ao feed de postagens local marcado como animal achado.

**Cenario**: FG03b-C02 Usuário preenche dados insuficientes
* Dado: que o usuário está na página home
* e: ativa a funcionalidade de criar um novo post
* Quando: Preenche os dados de animal incsuficientes
* e: Marca como animal achado
* e: Clicar em postar
* Então: Postagem é adicionada ao feed de postagens local marcado como animal achado, estando presente em feed de animais achados.

-----
#### Funcionalidade FG04: Responder a postagens

**Cenario**: FG04-C01 Usuario responde postagem 
* Dado: que o usuario clica em uma postagem do feed da pagina home
* e: clica em responder postagem
* Quando preenche uma resposta em texto sobre a postagem
* e: clica em enviar resposta
* Então: a Resposta é enviada para o usuário autor da postagem, aparecendo na lista de notificações


**Cenario**: FG04-C02 Usuario cancela resposta a postagem
* Dado: que o usuario clica na postagem do feed da pagina home
* e: clica em responder postagem
* Quando preenche uma resposta em texto sobre a postagem
* e: clica em cancelar
* Então: ele retorna para o feed da página Home

-----
#### Funcionalidade FG05: Receber notificações sobre respostas

**Cenario**: FG05-C01 Usuario visualiza a notificação
* Dado: que o usuario está logado no sistema
* Quando estiver em uma página qualquer
* Então ele pode ver uma marcação em um sino indicando que ele tem notificações novas

-----
#### Funcionalidade FG06a: Visualizar notificações novas 
**Cenario**: FG06a-C01 Usuario visualiza notificações
* Dado que o usuario está logado no sistema
* Quando abre a aba de notificações
* Então ele consegue visualizar navas notificações acerca de respostas de posts e etc.
* E as marcações de novas visualizações somem

-----
#### Funcionalidade FG06b: Verifica notificações
**Cenario**: FG06b-C01 usuario verifica notificações
* Dado que o usuario está logado no sistema
* Quando abre a aba de notificações
* Então ele consegue visualizar o historico de notificações acerca de respostas de posts e etc.

-----
#### Funcionalidade FG07: abrir conversa sobre animal perdido ou achado
**Cenario**: FG07-C01 usuario abre notificações de respostas de posts
* Dado que o usuario clica em uma resposta
* Então ele abre a janela de conversa com o usuário

-----
#### Funcionalidade FG08: responder conversa sobre animal
**Cenario**: FG08-C01 usuario abre janela de conversa com outro usuario
* Dado que o usuario digita um texto de resposta
* e clica em enviar
* Então a resposta aparecerá em tela e o usuario de destino será notificado


### Funcionalidade FG08: Excluir postagem
