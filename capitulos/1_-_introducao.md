# 1 - Introdução

## 1. O que é?

O React é um projeto open-source criado pelo Facebook. Ele é um biblioteca JavaScript utilizada para a criação de componentes UI reutilizáveis. Não se pode comparar o React a outras bibliotecas como Angular pois enquanto o angular é uma biblioteca MVC (Model-View-Controller) o React é apenas o V (View).


Como define __Cassio de Souza Antonio__ em seu livro intitulado de “Pró React”:
> “React é um motor para construir “User Interfaces” compostas utilizando JavaScript e (opcionalmente) XML”.

## 2. Quem usa?
 
Só para citar algumas empresas que utilizam o react: Netflix, Airbnb, Instagram e o próprio Facebook.

## 3. Por que?
Uma das grandes vantagens de se utilizar o React é a performance. Diferente de outras bibliotecas que manipulam diretamente o dom - o que é um dos maiores gargalos em lentidão de sistemas web - o React não faz isso. Ele possui o que é chamado de Virtual DOM que nada mais é que um DOM que fica em memória onde de tempos em tempos ele faz um DIF (tira a diferença) entre o DOM e esse Virtual DOM e ai sim aplica as alterações. React não faz manipulação direta do DOM.

Além disso o ele utiliza o JSX, que nada mais é que JavaScript com XML (veremos isso logo).
