<!-- Título -->
# Atributos de Visibilidade

***Conteúdo da Aula:***

No exemplo anterior, nós podemos esconder o atributo saldo da classe conta-corrente modificando o seu atributo de visibilidade.

Os atributos de visibilidade definem o nível de acesso dos atributos e métodos de uma classe com relação à outras classes e objetos.

Nós temos de maneira geral três atributos de visibilidade nas linguagens orientadas a objetos.

Mas, nesta altura, vamos abordar somente dois destes três atributos:

* `Public`:
  * Atributos e métodos declarados como públicos podem ser chamados, acessados e modificados por objetos da própria classe e também por objetos externos, sendo da mesma classe ou não;

* `Private`:
  * Atributos e métodos declarados como privados não podem ser chamados, acessados ou modificados por objetos externos, sendo eles da mesma classe ou não;
  * Somente o próprio objeto pode modificar os atributos que são privados, assim como somente o próprio objeto pode invocar os métodos que são declarados como privados.

No caso do nosso atributo saldo da classe conta-corrente, se quiséssemos o encapsular, o correto seria nós o declararmos como sendo um atributo privado.

Já os métodos sacar e depositar deveriam ser públicos, para que os demais objetos pudessem invocar estes métodos.

<!-- Informações -->
## &#8505; Informações

![Visitors](https://api.visitorbadge.io/api/visitors?path=Devsgeeknerd%2Fcla-atr-vis-enc-log-ori-obj-com-bas&label=Visitantes&labelColor=%23700070&labelStyle=none&countColor=%23000fff&style=plastic&color=%23ffffff "Total de Visitantes")
&nbsp;
![Followers](https://img.shields.io/github/followers/Devsgeeknerd?style=p&label=Seguidores&labelColor=800080&color=000fff "Total de Seguidores")
&nbsp;
![Watchers](https://img.shields.io/github/watchers/Devsgeeknerd/cla-atr-vis-enc-log-ori-obj-com-bas?style=p&label=Observadores&labelColor=800080&color=000fff "Total de Observadores")
&nbsp;
![Stars](https://img.shields.io/github/stars/Devsgeeknerd/cla-atr-vis-enc-log-ori-obj-com-bas?style=p&label=Estrelas&labelColor=800080&color=000fff "Total de Estrelas")
&nbsp;
![Forks](https://img.shields.io/github/forks/Devsgeeknerd/cla-atr-vis-enc-log-ori-obj-com-bas?style=p&label=Bifurcações&labelColor=800080&color=000fff "Total de Bifurcações")
&nbsp;
![Repo Size](https://img.shields.io/github/repo-size/Devsgeeknerd/cla-atr-vis-enc-log-ori-obj-com-bas?style=p&label=Tamanho&labelColor=800080&color=000fff "Tamanho do Repositório")
&nbsp;
![License](https://img.shields.io/github/license/Devsgeeknerd/cla-atr-vis-enc-log-ori-obj-com-bas?style=p&label=Licença&labelColor=800080&color=000fff "Licença do Repositório")
