# Máquina de Turing

Esta pasta contém anotações e exercícios sobre máquinas de Turing.

## Tópicos

- Definição formal de Máquina de Turing
- Variantes de Máquinas de Turing
- Computabilidade
- Tese de Church-Turing
- Problemas decidíveis e indecidíveis

## Definição formal da Máquina de Turing

Formalmente a Máquina de Turing é definida por: $$(Q, \Sigma, \Gamma, \delta, q_0, q_{aceita}, q_{rejeita})$$ onde:

$$Q$$ = Conjunto de estados

$$\Sigma$$ = Alfabeto de entrada

$$\\Gamma$$ = Alfabeto da fita, com símbolo de vazio

$$\delta$$ = Função de transição ($$Q \times \Gamma \to Q \times \Gamma \times {E,D}$$)

$$q_0$$ = É o estado inicial

$$q_{aceita}$$ = É o estado de aceitação

$$q_{rejeita}$$ = É o estado de rejeição

## Referências

- [Simulador da Máquina de Turing](http://turingmachine.io)
