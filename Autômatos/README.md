# Autômatos

Esta pasta contém anotações e exercícios sobre autômatos.

## Tópicos

- Autômatos Finitos Determinísticos (AFD)
- Autômatos Finitos Não-Determinísticos (AFND)
- Autômatos com Pilha
- Equivalência entre autômatos e gramáticas

## Autômatos Finitos Determinísticos (AFD)

Os AFDs são quintuplas definidas formalmente por: $$(Q, \Sigma, \delta, q_0, q_{aceita})$$ onde:

$$Q$$ = Conjunto finito de estados

$$\Sigma$$ = Alfabeto

$$\delta$$ = Função de transição ($$Q \times \Sigma \to Q$$)

$$q_0$$ = Estado inicial

$$q_{aceita}$$ = Estado de aceitação

## Autômatos com Pilha

O autômato com pilha é uma sextupla definida formalmente por: $$(Q, \Sigma, \Gamma, \delta, q_0, F)$$ onde:

$$Q$$ = Conjunto finito de estados
$$\Sigma$$ = Alfabeto de entrada
$$\Gamma$$ = Alfabeto da pilha
$$\delta$$ = Função de transição
$$q_0$$ = Estado inicial
$$F$$ = Conjunto de estados de aceitação

## Referências

- Introdução a Teoria da Computação - Sipser - II Edição
