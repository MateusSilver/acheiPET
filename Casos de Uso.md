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
