## Modelo de Perguntas Frequentes - FAQ

### Contexto 
O FAQ, também conhecido como Perguntas Frequentes, é a documentação que reúne as dúvidas mais comuns que o usuário pode ter em relação ao seu produto/serviço. Costuma ser o local ao final de uma seção, ou uma página à parte, dedicado em centralizar as perguntas que p

## Exemplo de documentação 

# Perguntas Frequentes (FAQ)

## O que é o Alcance?
O Alcance é o design system voltado para a construção de aplicações web.
Ele fornece orientações sobre como as páginas deve ser construídas,
e inclui um guia de estilo, tokens de design, classes CSS e uma
biblioteca de componentes de interface.

## Quem deve usar o Alcance?
Se você está construindo uma nova aplicação web, que não vá ficar
disponível para o público em geral (no Portal Institucional), você
deve usar o Alcance.

## Posso usar o Alcance com algum framework de front-end?
Você não precisa de nenhum framework de front-end para usar o Alcance,
mas pode usar algum se quiser, como Vue, React e Angular.

## Posso usar o Alcance com alguma biblioteca de componentes?
O Alcance já possui sua própria biblioteca de componentes. O ideal
é usar somente a biblioteca do Alcance. Para usar outra biblioteca
ao mesmo tempo, é preciso ter cuidado para que não haja interferência,
de uma com outra, especialmente em relação à aparência dos
elementos para o usuário final.

## Como faço para saber se o Alcance é compatível com meu back-end?
Pensando em camadas de uma arquitetura de desenvolvimento, o
Alcance está localizado no que podemos chamar de "front do front-end".
O Alcance não depende de nada do back-end e, portanto, não há 
qualquer restrição quanto a isso.

## O Alcance não se comunica com o back-end?
Os componentes do Alcance não se comunicam com o back-end.
A única exceção é o `alc-datatable`. Para os demais componentes, toda
a comunicação com o back-end deve ser implementado pela aplicação.
