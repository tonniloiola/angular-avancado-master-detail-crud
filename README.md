#### _Documentações / Referências:_

* [GIT](https://git-scm.com/doc)
* [CSS](https://developer.mozilla.org/pt-BR/docs/Web/CSS)
* [HTML](https://developer.mozilla.org/pt-BR/docs/Web/HTML)
* [Angular](https://angular.io/docs)
* [TypeSrcipt](https://www.typescriptlang.org/docs/home.html)

#### _Observações:_
* Projeto Angular
- Registro de Usuarios
- Login 
- Controle de rotas 
- Forms reactive


#### _

* Tela de _"Login"_ onde a autenticação deve ser realizada através de e-mail e senha, esta deve ser
a primeria tela de acesso ao sistema desde que o usuário não esteja autenticado no sistema;

* Tela de _"Ainda não sou usuário"_ a mesma deve conter 2 perfis (ADMINISTRADOR e VISITANTE), 
o primeiro usuário a se cadastrar nessa tela deve-se tornar de formar automática um ADMINISTRADOR, 
e os demais de forma automática um VISITANTE, esta tela deve estar acessível juntamente com a tela de  _"Login"_ 
e deve conter os seguintes campos como obrigatórios para o cadastro, Nome, E-mail, Senha, Confirmar senha. 
O cadastro só deve ser realizado se o campo E-mail for válido e único dentre os já cadastrados, e Senha e 
Confirmar senha forem idênticos.

* Tela de _"Manutenção de usuário"_ esta deve ser a tela inicial do sistema desde que o usuário esteja autenticado 
no sistema, a mesma deve conter os campos Nome, E-mail, Telefone, Cep, Endereço e Perfil(ADMINISTRADOR ou VISITANTE), 
Status(ATIVO ou INATIVO) e uma listagem de usuários que foram cadastrados através da tela de _"Ainda não sou usuário"_
para possíveis edições e correções. Obs: usuário logado no sistema com o perfil ADMINISTRADOR 
poderá: Alterar o Perfil e Status de qualquer outro usuário, o sistema deverá garantir que dentre as alterações exista
ao menos 1 usuário com o perfil ADMINISTRADOR e que o campo E-mail seja exibido mas nunca alterado. Usuário com perfil
VISITANTE, poderá visualizar na listagem apenas o seu cadastro e poderá editar apenas o seu cadastro onde o sistema
deve garantir que o e-mail e perfil sejam exibido mas não alterado, e demais campos ficam passíveis de alterações.

* Tela de _"Relatório"_ esta deve ser uma tela de relatório, onde este relatório consiste apenas em apresentar a
quantidade de usuários cadastrados através da tela _"Ainda não sou usuário"_ a mesma deve possuir um filtro de
Status(ATIVO ou INATIVO), onde o usuário poderá selecionar apenas um Status ou ambos os Status para serem filtrados
os valores e apresentados na tela. Obs: o acesso a esta tela fica restrito apenas a usuários logados que possuir o
Perfil ADMINISTRADOR;




