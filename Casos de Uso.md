# Casos de Uso - AcheiPET

-----
#### Funcionalidade: FG01: Fazer login no sistema acheiPET como usuario

**Cenário**: FG01-C01 Usuário faz login com sucesso no sistema acheiPET
* Dado: Que o usuário tem acesso a página de login do sistema
* Quando: Ele insere os dados de email e/ou usuário e senha
* e: confirma com o botao entrar
* Então: O sistema o redireciona para a página principal

-----
#### Funcionalidade: FG02: Fazer login no sistema acheiPET como usuario

**Cenário**: FG01-C02 Usuario insere credenciais incorretas de login no sistema acheiPET
* Dado: Que o usuário tem acesso a página de login do sistema
* Quando: Ele insere os dados de email e/ou usuário e senha inválidos
* e: confirma com o botao entrar
* Então: O sistema o exibirá uma mensagem de aviso avisando que as credencais estão incorretas

-----
#### Funcionalidade: FG03: Fazer login no sistema acheiPET como usuario

**Cenario**: FG01-C03 Usuario deixa campos de login em branco no sistema acheiPET
* Dado: Que o usuário tem acesso a página de login do sistema
* Quando: Ele  confirma com o botao entrar sem adicionar nada aos campos de login
* Então: O sistema o exibirá uma mensagem de aviso avisando os campos que nao foram preenchidos corretamente

-----
