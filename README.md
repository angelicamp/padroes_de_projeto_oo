## Padrões de Projeto de Software Orientado a Objetos 
Entendendo os conceitos de padrões de projeto de software orientado a objetos e aplicando os conceitos.
_______________________________________________________________________________________________________________
Os Design Patterns, também conhecidos como Padrões de Projeto,  têm o objetivo de tornar componentes reutilizáveis que facilitam a padronização, que permita agilidade para as soluções de problemas recorrentes no desenvolvimento do sistema.<br/>
Existem dois padrões de projetos conhecidos pela engenharia de software que são: padrões **Gang of Four**(*Erich Gamma, Richard Helm, Ralph Johnson e John Vlissides*) e os padrões **GRASP** (*General Responsability Assignment Software Patterns*).
________________________________________________________________________________________________________________
## Padrões Gang of Four (GoF)
Objetivam solucionar problemas comuns de softwares que tenham algum envolvimento a orientação a objetos. São formados por três grupos:<br/>
 ![gof](https://user-images.githubusercontent.com/85784665/136676253-8e3c47fc-a5d8-427a-bbe8-1b11fc0594c1.png) <br/>
* *Escopo‘Classe’ negociam relaçionamentos entre classes e sub-classes. Essas
relações são estabelecidas através de herança. Então são estáticas – fixas em
tempo de compilação.*<br/>
* *Escopo ‘Objeto’ negociam com relações de objetos, que podem mudar em
tempo de execução.*
_________________________________________________________________________________________________________________
## Singleton
Usado quando desejado, que uma classe tenha apenas uma instância na aplicação. A idéia é garantir que apenas um objeto exista,
independente do número de requisições recebidas para criá-lo.<br/>
O construtor da classe fica como **privado** (private), sendo que não pode ser instanciada para fora da própria classe.<br/>
A classe é final, pois não permite a criação de subclasses da própria classe.<br/>
O acesso é permitido através do método que retorna a instância única da classe, ou faz a criação de uma, caso não tenha sido criada.<br/>
![sing](https://user-images.githubusercontent.com/85784665/136676567-752ede10-fd72-4875-846e-9a2fa261424d.png)<br/>
Exemplo: [Singleton](https://github.com/angelicamp/padroes_de_projeto_oo/blob/main/Singleton)
__________________________________________________________________________________________________________________
## Proxy
Permite que o acesso seja controlado por meio de outro objeto, que atua como substituto. Geralmente, usado na programação orientada a aspectos, tendo como objetivo ajudar a separar, encapsular, modularizar métodos e organizar o código de acordo com a importância.<br/>
O objetivo de um proxy é mediar o acesso a um objeto base, agregando-lhe funcionalidades, sem que ele tome conhecimento disso.<br/>![prox](https://user-images.githubusercontent.com/85784665/136677044-e4605d67-a973-47b2-b714-c7dbd7b8947f.png)<br/>
Exemplo: [Proxy](https://github.com/angelicamp/padroes_de_projeto_oo/blob/main/Proxy) 

