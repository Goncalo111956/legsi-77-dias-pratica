# Comparação de ferramentas de IA — Dia 1

## Pedido utilizado

Estou a aprender Python e acabei de criar um programa que pede o nome,
o curso e um objetivo ao utilizador.

Explica-me este código linha por linha, sem assumir que já conheço Python.
Depois propõe apenas uma melhoria simples e explica por que motivo é útil.

## ChatGPT

### O que explicou melhor

-

### O que podia melhorar

Podes personalizar o título final usando o nome do utilizador:

print(f"\n--- Projeto 77 Dias de {nome} ---")

Assim, em vez de aparecer apenas:

--- Projeto 77 Dias ---

poderia aparecer:

--- Projeto 77 Dias de Gonçalo ---

Esta melhoria é útil porque torna a resposta mais pessoal e mostra novamente como uma variável pode ser inserida num texto através de uma f-string.

## Claude

### O que explicou melhor

-

### O que podia melhorar

Adicionar uma mensagem de boas-vindas personalizada no final:

pythonprint(f"\nBem-vindo/a, {nome}! Bom trabalho nos próximos 77 dias.")

Porquê é útil? Neste momento o programa parece um formulário frio — recolhe dados e lista-os. Com uma mensagem final que usa o nome da pessoa, o programa dá feedback e parece mais completo. É também um bom exercício para perceberes que podes usar as variáveis em qualquer print(), não apenas naqueles logo a seguir ao input().

## Gemini

### O que explicou melhor

-

### O que podia melhorar

A Melhoria: Usa a função .capitalize() (ou .title()) quando pedires o nome.

nome = input("Qual é o teu nome? ").title()

Por que motivo isto é útil?
Quando os utilizadores preenchem formulários, muitas vezes escrevem à pressa e com letras minúsculas (por exemplo, "tiago"). O .title() é um método que analisa o texto introduzido e transforma automaticamente a primeira letra de cada palavra numa maiúscula ("Tiago"). Assim, quando o teu programa imprimir o resultado final, os dados estarão sempre formatados de forma bonita e profissional, independentemente de como o utilizador os escreveu!

## Conclusão

### Ferramenta que me ajudou mais

Explicação de código- ChatGPT
Melhoria Sugerida- Gemini

### Motivo

-
