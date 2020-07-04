## Desenvolvedor-front

Este projeto serve como um exame prático para testar a capacidade e habilidade de novos candidatos
a Desenvolvedores do Grupo Saga, o mesmo servirá como uma prova básica para análise de conhecimento
do candidato em: Html, CSS, TypeScript, Git e Lógica em programação.   

#### _Documentações / Referências:_

* [GIT](https://git-scm.com/doc)
* [CSS](https://developer.mozilla.org/pt-BR/docs/Web/CSS)
* [HTML](https://developer.mozilla.org/pt-BR/docs/Web/HTML)
* [Angular](https://angular.io/docs)
* [TypeSrcipt](https://www.typescriptlang.org/docs/home.html)
* [IndexedDB](https://developer.mozilla.org/pt-BR/docs/Web/API/IndexedDB_API)
* [Material](https://material.angular.io/)
* [PrimeNG](https://www.primefaces.org/primeng/)

#### _Observações:_
* Utilize de boas práticas e procure limitar-se apenas ao que se encontra no tópico _Documentações / Referências_, com
exceção para Material e PrimeNG que caso o candidato achar necessário poderá adotar apenas HTML e CSS para o
desenvolvimento de suas Telas.

* Para o armazenamento dos dados deverá ser utilizado o IndexedDB ou similar suportado por pelomenos o Navegador 
da Web Google Chrome.

* O tempo limite para entrega se dá por 5 dias, contando á partir do e-mail enviado para o candidato, o mesmo
deverá criar uma branch com o seu nome, e o término se da após a solicitação de Pull request de sua Branch para a Master. 

#### _O que devo fazer?_

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




