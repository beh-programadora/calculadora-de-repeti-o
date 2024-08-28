# Calculadora Interativa

Este projeto é uma calculadora simples em Python que permite ao usuário realizar operações aritméticas básicas (+, -, *, /) entre dois números. O usuário pode continuar realizando cálculos até decidir encerrar o programa digitando 'sair'.

## Objetivo

O objetivo deste projeto é criar uma calculadora que:
1. Permita ao usuário inserir dois números e uma operação aritmética.
2. Realize a operação solicitada e exiba o resultado.
3. Permita ao usuário continuar realizando operações até que escolha encerrar o programa.

## Código

O código funciona da seguinte maneira:
1. Solicita ao usuário dois números e a operação desejada.
2. Realiza a operação aritmética com base na entrada do usuário.
3. Exibe o resultado da operação.
4. Permite ao usuário encerrar o programa digitando 'sair'.

```python
while True: 
    
    # leitura dos números e operação
    numero1 = float(input("Digite o primeiro número: "))
    numero2 = float(input("Digite o segundo número: "))
    operacao = input("Digite a operação (+,-,*,/) ou 'sair' para encerrar: ")

    # verificação para encerrar o loop
    if operacao == 'sair':
        break

    # realização da operação
    if operacao == '+':
        resultado = numero1 + numero2
    elif operacao == '-':
        resultado = numero1 - numero2
    elif operacao == '*':
        resultado = numero1 * numero2
    elif operacao == '/':
        if numero2 != 0:
            resultado = numero1 / numero2
        else:
            resultado = "Erro: divisão por zero"
    else:
        resultado = "Operação inválida"

    # exibição do resultado
    print(f"Resultado: {resultado}")
Como Executar
1. Certifique-se de ter o Python instalado em seu sistema.

2. Salve o código acima em um arquivo chamado calculadora.py.

3. Execute o código usando o seguinte comando:
python calculadora.py

Memória atualizada
Aqui estão os arquivos README, .gitignore e o enunciado para o seu projeto de cálculo com opções de operação e encerramento:

README.md
markdown
Copiar código
# Calculadora Interativa

Este projeto é uma calculadora simples em Python que permite ao usuário realizar operações aritméticas básicas (+, -, *, /) entre dois números. O usuário pode continuar realizando cálculos até decidir encerrar o programa digitando 'sair'.

## Objetivo

O objetivo deste projeto é criar uma calculadora que:
1. Permita ao usuário inserir dois números e uma operação aritmética.
2. Realize a operação solicitada e exiba o resultado.
3. Permita ao usuário continuar realizando operações até que escolha encerrar o programa.

## Código

O código funciona da seguinte maneira:
1. Solicita ao usuário dois números e a operação desejada.
2. Realiza a operação aritmética com base na entrada do usuário.
3. Exibe o resultado da operação.
4. Permite ao usuário encerrar o programa digitando 'sair'.

```python
while True: 
    
    # leitura dos números e operação
    numero1 = float(input("Digite o primeiro número: "))
    numero2 = float(input("Digite o segundo número: "))
    operacao = input("Digite a operação (+,-,*,/) ou 'sair' para encerrar: ")

    # verificação para encerrar o loop
    if operacao == 'sair':
        break

    # realização da operação
    if operacao == '+':
        resultado = numero1 + numero2
    elif operacao == '-':
        resultado = numero1 - numero2
    elif operacao == '*':
        resultado = numero1 * numero2
    elif operacao == '/':
        if numero2 != 0:
            resultado = numero1 / numero2
        else:
            resultado = "Erro: divisão por zero"
    else:
        resultado = "Operação inválida"

    # exibição do resultado
    print(f"Resultado: {resultado}")
Como Executar
Certifique-se de ter o Python instalado em seu sistema.

Salve o código acima em um arquivo chamado calculadora.py.

Execute o código usando o seguinte comando:

bash
Copiar código
python calculadora.py
Contribuição
Sinta-se à vontade para fazer sugestões ou melhorias. Se encontrar um problema ou tiver uma ideia para aprimorar o projeto, por favor, abra uma issue ou envie um pull request.

Licença
Este projeto está licenciado sob a Licença MIT - veja o arquivo LICENSE para mais detalhes.
