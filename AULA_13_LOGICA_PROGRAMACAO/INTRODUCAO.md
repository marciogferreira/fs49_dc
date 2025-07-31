# 📘 Introdução à Lógica de Programação

Este material tem como objetivo apresentar os conceitos básicos da lógica de programação, que são fundamentais para aprender qualquer linguagem de programação.

---

## 📌 O que é Lógica de Programação?

Lógica de programação é a técnica de escrever instruções (ou algoritmos) de forma clara e estruturada para que um computador consiga entender e executar tarefas. Ela segue uma sequência de **entrada**, **processamento** e **saída** de dados.

---

## 🔁 Ciclo Básico: Entrada, Processamento e Saída

1. **Entrada:** Onde os dados são fornecidos ao programa, geralmente pelo usuário ou por arquivos.

   * Exemplo: o usuário digita um número no teclado.

2. **Processamento:** Onde os dados de entrada são manipulados para gerar um resultado.

   * Exemplo: somar dois números fornecidos pelo usuário.

3. **Saída:** Onde o resultado do processamento é mostrado.

   * Exemplo: exibir o resultado da soma na tela.

```python
# Exemplo em Python
numero1 = int(input("Digite o primeiro número: "))   # Entrada
numero2 = int(input("Digite o segundo número: "))    # Entrada
soma = numero1 + numero2                             # Processamento
print("A soma é:", soma)                             # Saída
```

---

## 💾 Variáveis e Tipos de Dados

### 🔸 Variáveis

São espaços na memória do computador usados para armazenar dados temporariamente durante a execução do programa.

```python
nome = "Maria"  # variável chamada 'nome' armazena a string "Maria"
```

### 🔸 Tipos de Dados Comuns

| Tipo    | Exemplo         | Descrição                          |
| ------- | --------------- | ---------------------------------- |
| `int`   | `10`            | Números inteiros                   |
| `float` | `3.14`          | Números decimais (ponto flutuante) |
| `str`   | `"texto"`       | Texto (cadeia de caracteres)       |
| `bool`  | `True`, `False` | Valores booleanos (lógico)         |

---

## ➕ Operadores Aritméticos

Utilizados para realizar operações matemáticas.

| Operador | Descrição        | Exemplo (`a = 10`, `b = 3`) | Resultado |
| -------- | ---------------- | --------------------------- | --------- |
| `+`      | Adição           | `a + b`                     | `13`      |
| `-`      | Subtração        | `a - b`                     | `7`       |
| `*`      | Multiplicação    | `a * b`                     | `30`      |
| `/`      | Divisão          | `a / b`                     | `3.33`    |
| `//`     | Divisão inteira  | `a // b`                    | `3`       |
| `%`      | Resto da divisão | `a % b`                     | `1`       |
| `**`     | Exponenciação    | `a ** b`                    | `1000`    |

---

## ⚖️ Operadores de Comparação (Relacionais)

Utilizados para comparar valores. O resultado sempre será `True` ou `False`.

| Operador | Descrição        | Exemplo (`a = 10`, `b = 3`) | Resultado |
| -------- | ---------------- | --------------------------- | --------- |
| `==`     | Igual a          | `a == b`                    | `False`   |
| `!=`     | Diferente de     | `a != b`                    | `True`    |
| `>`      | Maior que        | `a > b`                     | `True`    |
| `<`      | Menor que        | `a < b`                     | `False`   |
| `>=`     | Maior ou igual a | `a >= b`                    | `True`    |
| `<=`     | Menor ou igual a | `a <= b`                    | `False`   |

---

## ✅ Exemplo Completo

```python
# Solicita dois números ao usuário
num1 = float(input("Digite o primeiro número: "))
num2 = float(input("Digite o segundo número: "))

# Processa a média
media = (num1 + num2) / 2

# Verifica se a média é maior que 7
if media >= 7:
    print("Aprovado com média:", media)
else:
    print("Reprovado com média:", media)
```

---

## 📚 Conclusão

Esses são os primeiros passos para entender como os programas funcionam. Com o domínio de variáveis, tipos de dados, operadores e a lógica de entrada-processamento-saída, você estará preparado para resolver diversos problemas computacionais de forma estruturada.