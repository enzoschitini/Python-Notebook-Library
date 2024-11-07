# Python Notebook Library
This guide introduces the use of Python for data analysis programming, with a focus on code execution. Ideal for improving your workflow.

## Dominando Python: Fundamentos e Práticas Avançadas

<img src="https://raw.githubusercontent.com/enzoschitini/Python-Notebook-Library/refs/heads/main/img/Python%20Notebook%20Library.png" alt="ebac-logo">

---

# **Introdução** | Python Notebook Library
Caderno de **Aula**<br> 
Desenvolvedor [Enzo Schitini](https://enzo-schitini.bubbleapps.io/version-test/)

---

**Introdução:**
A "Python Notebook Library" é uma coleção abrangente de módulos que cobrem os principais aspectos da programação em Python, desde os fundamentos até as práticas avançadas. Ideal tanto para iniciantes quanto para programadores experientes, este material foi projetado para proporcionar uma compreensão profunda da linguagem e suas aplicações. Cada capítulo oferece uma abordagem prática e teórica, permitindo que você desenvolva habilidades essenciais e se prepare para desafios reais no desenvolvimento de software.

**Módulos:**

**1. Variáveis & Tipos de Dados:**  
Neste módulo, você aprenderá a declarar e utilizar variáveis, além de explorar os diferentes tipos de dados que Python oferece. Compreender como escolher o tipo de dado adequado é fundamental para a manipulação eficiente e otimização do seu código.

**2. Estruturas de Dados:**  
Explore as principais estruturas de dados em Python, como listas, tuplas, conjuntos e dicionários. Este módulo ensina a armazenar e organizar dados de maneira eficiente e a realizar operações comuns para resolver problemas de forma eficaz.

**3. Fluxo Condicional & Repetição:**  
Aprenda a controlar o fluxo do seu programa com condicionais e estruturas de repetição. Compreender como tomar decisões e executar blocos de código repetidamente é essencial para criar programas dinâmicos e interativos.

**4. Arquivos & Funções:**  
Este módulo aborda a leitura e escrita de arquivos, além da criação e utilização de funções. Você aprenderá a modularizar seu código para torná-lo mais organizado e reutilizável, e a manipular dados armazenados em arquivos de forma eficiente.

**5. Programação Funcional:**  
Descubra o paradigma da programação funcional em Python, incluindo o uso de funções como objetos de primeira classe, funções lambda e técnicas funcionais para escrever código mais conciso e livre de efeitos colaterais.

**6. Programação Orientada a Objetos:**  
Explore a Programação Orientada a Objetos (POO) para modelar problemas do mundo real em Python. Este módulo cobre conceitos fundamentais como classes, objetos, herança e polimorfismo, ajudando a criar soluções mais estruturadas e reutilizáveis.

**7. Módulos & Pacotes:**  
Aprenda a organizar e reutilizar seu código com módulos e pacotes. Este módulo cobre a criação e importação de módulos, a estrutura de pacotes e o uso de bibliotecas externas para expandir as funcionalidades do seu projeto.

**8. Tratamento de Erros:**  
Entenda como lidar com erros e exceções para garantir que seu programa seja robusto e confiável. Você aprenderá a usar blocos `try`, `except`, `else` e `finally`, além de criar exceções personalizadas para tratar problemas inesperados de forma eficaz.

**9. Scripting:**  
Descubra como utilizar Python para criar scripts que automatizam tarefas e processam dados. Este módulo ensina boas práticas para a criação de scripts, a utilização de argumentos de linha de comando e a criação de scripts executáveis, aumentando sua produtividade e eficiência.

A "Python Notebook Library" oferece uma base sólida em Python e prepara você para enfrentar desafios mais complexos no desenvolvimento de software. Boa leitura e sucesso na sua jornada com Python!

Python é uma das linguagens de programação mais versáteis e amplamente utilizadas no mundo da tecnologia. De scripts simples a sistemas complexos, Python oferece uma gama de ferramentas e técnicas para desenvolver soluções eficientes e elegantes. Este material é projetado para guiá-lo desde os conceitos básicos até técnicas mais avançadas, proporcionando uma compreensão abrangente e prática da linguagem. Se você está começando agora ou deseja aprimorar suas habilidades, este guia é seu caminho para se tornar proficiente em Python.

---
<img src="https://raw.githubusercontent.com/enzoschitini/Python-Notebook-Library/refs/heads/main/img/Vari%C3%A1veis%20%26%20Tipos%20de%20Dados.png" alt="ebac-logo">

---

# **Módulo 01** | Python: Variáveis & Tipos de Dados
Caderno de **Aula**<br> 
Desenvolvedor [Enzo Schitini](https://enzo-schitini.bubbleapps.io/version-test/)

---
# **Tópicos**

<ol type="1">
  <li>Introdução ao Google Colab;</li>
  <li>Variáveis;</li>
  <li>Números;</li>
  <li><i>Strings;</i></li>
  <li>Boleanos.</li>
</ol>
---
# **Aulas**
## 1\. Introdução ao Google Colab
> Ferramenta web autogerênciada de cadernos (*notebooks*).
### **1.1. Ferramenta web** 


*   Crie uma conta Google em [gmail.com](https://gmail.com);
*   Acesse o Google Colab através do endereço [colab.research.google.com](https://colab.research.google.com/).



### **1.2. Autogerênciada** 


*   A Google provisiona uma máquina virtual para você;
*   A máquina virtual dura no máximo 12h.


### **1.3. Cadernos (*notebooks*)** 
Um **caderno** é um documento *web* composto por um conjunto de elementos (células) de texto e código:


*   Células de **texto** podem ser editados com o editor da ferramenta, HTML ou Markdown; 
*   Células de **código** são exclusivamente para a linguagem de programação Python.


print("olá mundo!")
## 2\. Variáveis
### **2.1. Definição** 
Mecanismo de armazenamento volátil de dados, ou seja, dados salvos em pedacinhos da memória RAM do sistema computacional em uso (*notebook*, *mobile*, console de vídeo game, *smartwatch*, etc.).
idade = 30
print(idade)

idade = 27
print(idade)

nome = "andré"
print(nome)
### **2.2. Tipos nativos** 
**Tipos numéricos:** inteiros (`int`) e decimais (`float`):
preco = 1000
tipo_preco = type(preco)

print(preco)
print(tipo_preco)

juros = 0.05
tipo_juros = type(juros)

print(juros)
print(tipo_juros)
**Tipos de texto:** *strings* (`str`):
primeiro_nome = "André"

print(primeiro_nome)
print(type(primeiro_nome))

pais = 'Brasil'

print(pais)
print(type(pais))
**Tipos lógicos:** booleanos (`bool`):
usuario_maior_de_idade = True

print(usuario_maior_de_idade)
print(type(usuario_maior_de_idade))
**Tipo vazio** (`NoneType`):
telefone_fixo = None

print(telefone_fixo)
print(type(telefone_fixo))
### 2.3. Operations with variables
#### Operações com strings
# Concatenação de strings
string1 = "Olá"
string2 = " Mundo!"
string_concatenada = string1 + string2
print(string_concatenada)  # Saída: Olá Mundo!

# Repetição de strings
string = "Python"
string_repetida = string * 3
print(string_repetida)  # Saída: PythonPythonPython

# Fatiamento de strings
string = "Linguagem Python"
substring = string[8:15]
print(substring)  # Saída: Python

# Verificação de strings
string = "Python"
if "Py" in string:
  print("A string contém 'Py'")  # Saída: A string contém 'Py'

# Conversão de strings
numero = 123
string_numero = str(numero)
print(string_numero)  # Saída: 123

# Formatação de strings
nome = "João"
idade = 30
string_formatada = f"Meu nome é {nome} e tenho {idade} anos."
print(string_formatada)  # Saída: Meu nome é João e tenho 30 anos.
#### Operações matemáticas
def calcular(num1, num2, operação):
  if operação == "+":
    return num1 + num2
  elif operação == "-":
    return num1 - num2
  elif operação == "*":
    return num1 * num2
  elif operação == "/":
    if num2 == 0:
      return "Erro: Divisão por zero"
    else:
      return num1 / num2
  else:
    return "Operação inválida"

num1 = 3.0
num2 = 4.0
operação = "+"

resultado = calcular(num1, num2, operação)

print(f"Resultado: {resultado}")
#### Operações com booleanos
a = True
b = False

# Operador AND
print(a and b)  # False

# Operador OR
print(a or b)   # True

# Operador NOT
print(not a)    # False

# Operador XOR
print(a ^ b)    # True
## 3\. Números
### **3.1. Motivação** 
Você precisa calcular o **ticket médio** diário `tkt` do seu restaurante. A métrica é calculada pela soma do valor das vendas `svv` de um mesmo dia dividido pela quantidade de vendas `sqv`, também de um mesmo dia. 

$tkt = svv / sqv$
Esta é a sua planilha:


| Dia   | Valor Total Vendas | Qtd Total Vendas | Ticket Medio |
|-------|--------------------|------------------|-|
| 19/01 | 153.98             | 3                |?|
| 20/01 | 337.01             | 7                |?|
| 23/01 | 295.33             | 5                |?|
Como podemos fazer este cálculo usando o Python?
### **3.2. Definição** 
Armazenam **valores numéricos**: 

*   `10, 37, 500` (inteiros);
*   `0.333, 10.1` (decimais);
*   `1 + 2j` (complexos).


São dos tipos:

*   `int` (inteiros);
*   `float` (decimais);
*   `complex` (complexos).


print(type(37))
print(type(10.1))
print(type(1 + 2j))

### **3.3. Operações** 




As operações dos tipos numéricos são as quatro operações matemáticas fundamentais:

*   `+` (soma);
*   `-` (subtração);
*   `*` (multiplicação);
*   `/` (divisão).

Além de operações mais avançadas:

*   `//` (divisão inteira)
*   `**` (potência ou exponenciação);
*   `%` (resto de divisão).
**Exemplo**: Carrinho de compra de um *e-commerce*.
qtd_items_carrinho_compra = 0

qtd_items_carrinho_compra = qtd_items_carrinho_compra + 1
print(qtd_items_carrinho_compra)

qtd_items_carrinho_compra = qtd_items_carrinho_compra + 1
print(qtd_items_carrinho_compra)
qtd_items_carrinho_compra = 0

qtd_items_carrinho_compra += 1
print(qtd_items_carrinho_compra)

qtd_items_carrinho_compra += 1
print(qtd_items_carrinho_compra)
**Exemplo**: Total a pagar de um produto.
preco = 47
quantidade = 0.250

total_a_pagar = quantidade * preco
print(total_a_pagar)
a = 3
b = 2

c = a / b
print(c)
print(type(c))

d = a // b
print(d)
print(type(d))
### **3.4. Conversão** 
Podemos converter os tipos numéricos entre si utilizando o método nativo `int`, `float` e `complex`:
print(int(3.9))
print(float(10))
print(complex(1))
### **3.5. Revisitando a motivação** 
| Dia   | Valor Total Vendas | Qtd Total Vendas | Ticket Medio |
|-------|--------------------|------------------|-|
| 19/01 | 153.98             | 3                |?|
| 20/01 | 337.01             | 7                |?|
| 23/01 | 295.33             | 5                |?|
Ticket médio diário do dia 19/01.
svv_19 = 153.98
sqv_19 = 3

tkt_19 = svv_19 / sqv_19
print(tkt_19)
Ticket médio diário do dia 20/01.
svv_20 = 337.01
sqv_20 = 7

tkt_20 = svv_20 / sqv_20
print(tkt_20)
Ticket médio diário do dia 23/01.
svv_23 = 295.33
sqv_23 = 5

tkt_23 = svv_23 / sqv_23
print(tkt_23)
Ticket médio
tkt = (tkt_19 + tkt_20 + tkt_23) / 3
print(tkt)
## 4\. *Strings*
### **4.1. Motivação** 
A empresa que você trabalha adquiriu uma *startup* de logística. Você precisa identificar todos endereços que são comum a ambas. Na sua empresa, você armazena a latitude e longitude dos endereços em duas variáveis `lat` e `lon`, já a *startup* adquirida em uma única variável `latlon`.


# sua empresa
lat = '-22.005320'
lon = '-47.891040'

# startup adquirida
latlon = '-22.005320;-47.891040'
Como podemos normalizar a forma com que as latitudes e longitudes são armazenadas para possam ser comparadas?
### **4.2. Definição**
Armazenam **textos**:

*   `c`, `EBAC`, `Andre Perez, 20 anos` (texto)


São do tipo `str`:
nome_aula = 'Aula 04, Módulo 01, Strings'

print(nome_aula)
print(type(nome_aula))
string_vazia = ""

print(string_vazia)
print(type(string_vazia))
### **4.3. Operações** 
As operações de variáveis do tipo *string* são:


*   `+` (concatenação).


**Exemplo:** Nome completo.
nome = 'Andre Marcos'
sobrenome = 'Perez'

apresentacao = 'Olá, meu nome é ' + nome + ' ' + sobrenome + '.'
print(apresentacao)
Uma outra forma de concatenar strings é utilizar operações de formatação:
nome = 'Andre Marcos'
sobrenome = 'Perez'

apresentacao = f'Olá, meu nome é {nome} {sobrenome}.'
print(apresentacao)
Outra operação muito utilizada é a de fatiamento (*slicing*):


**Exemplo**: Informações de email.
email = 'andre.perez@gmail.com'


Fatiamento fixo:

|a|n|d|r|e|.|p|e|r|e|z|@|g|m|a|i|l|.|c|o|m|
|-|-|-|-|-|-|-|-|-|-|-|-|-|-|-|-|-|-|-|-|-|
|0|1|2|3|4|5|6|7|8|9|10|11|12|13|14|15|16|17|18|19|20|


print('0: ' + email[0])
print('11: ' + email[11])
print('-1: ' + email[-1])
print('-2: ' + email[-2])


Fatiamento por intervalo:

|a|n|d|r|e|.|p|e|r|e|z|@|g|m|a|i|l|.|c|o|m|
|-|-|-|-|-|-|-|-|-|-|-|-|-|-|-|-|-|-|-|-|-|
|0|1|2|3|4|5|6|7|8|9|10|11|12|13|14|15|16|17|18|19|20|


email_usuario = email[0:11]
print(email_usuario)
email_provedor = email[12:21]
print(email_provedor)
### **4.4. Métodos** 
São métodos nativos do Python que nos ajudam a trabalhar no dia a dia com *strings*:
endereco = 'Avenida Paulista, 1811, São Paulo, São Paulo, Brasil.'
# maiusculo: string.upper()
print(endereco.upper())
# posicao: string.find(substring)
posicao = endereco.find('Brasil')
print(posicao)
# substituição: string.replace(antigo, novo)
print(endereco.replace('Avenida', 'Av'))
### **4.5. Conversão** 
Podemos converter *strings* em tipos numéricos e vice-versa.
idade = 19
print(type(idade))

idade = str(idade)
print(type(idade))
faturamento = 'R$ 35 mi'
print(faturamento)
print(type(idade))

faturamento = int(faturamento[3:5])
print(faturamento)
print(type(faturamento))
### **4.6. Revisitando a motivação** 
Encontrando a posição do caracter `;` de divisão das *strings* de latitude e longitude da variável da startup:
posicao_char_divisao = latlon.find(';')
print(posicao_char_divisao)
Extraindo a latitude:
lat_startup = latlon[0:posicao_char_divisao]
print(lat_startup)
Extraindo a longitude:
lon_startup = latlon[posicao_char_divisao+1:len(latlon)]
print(lon_startup)
## 5\. Boleanos
### **5.1. Motivação** 


Em *websites* (redes sociais, *e-commerce*, corporativos, etc.) é comum o uso de sistemas de controle de acesso, o famoso *login*. Em geral, nestes sistemas um usuário fornece dois dados: `usuario` e `senha`:
usuario = 'andre.perez'
senha = 'andre123'
Do lado do servidor, o *backend* do *website* tem armazenado os dados de usuário e senha fornecidas pelo usuário no momento do cadastro: `usuario_cadastro` e `senha_cadastro`:
usuario_cadastro = 'andre.perez'
senha_cadastro = 'andre321'
Como comparamos se as *strings* (`usuario`, `usuario_cadastro`) e (`senha`,`senha_cadastro`) são iguais para conceder ou bloquear o acesso do usuário?
### **5.2. Definição** 
Armazenam **valores lógicos**:

*   `True` (verdadeiro);
*   `False` (falso).
verdadeiro = True
print(verdadeiro)
falso = False
print(falso)
São do tipo `bool`.
print(type(True))
São resultados de comparações lógicas. Os operadores de comparação lógica são:

*   `>` (maior);
*   `<` (menor);
*   `==` (igual);
*   `>=` (maior ou igual);
*   `<=` (menor ou igual);
*   `!=` (diferente).


**Exemplo:** Caixa eletrônico
saldo_em_conta = 200
valor_do_saque = 100

pode_executar_saque = valor_do_saque <= saldo_em_conta
print(pode_executar_saque)
**Exemplo:** Cartão de crédito
codigo_de_seguranca = '852'
codigo_de_seguranca_cadastro = '010'

pode_efetuar_pagamento = codigo_de_seguranca == codigo_de_seguranca_cadastro
print(pode_efetuar_pagamento)
### **5.3. Operações**
As operações de variáveis booleanas são: 

* `|` (operador ou)
* `&` (operador e)
* `not` (operador não)


O conjunto de resultados de operações lógicas geralmente é resumido em uma tabela chamada "tabela da verdade":
| A        | B        | | | A OR B   | | A AND B  | | NOT A    |
|----------|----------|-|-|----------|-|----------|-|----------|
| **TRUE** | **TRUE** | | | **TRUE** | | **TRUE** | | FALSE    |
| **TRUE** | FALSE    | | | **TRUE** | | FALSE    | | FALSE    |
| FALSE    | FALSE    | | | FALSE    | | FALSE    | | **TRUE** |
| FALSE    | **TRUE** | | | **TRUE** | | FALSE    | | **TRUE** |
**Exemplo**: Tabela da verdade do operador `|` (ou).
print(True | True)
print(True | False)
print(False | False)
print(False | True)
**Exemplo**: Tabela da verdade do operador `&` (e).
print(True & True)
print(True & False)
print(False & False)
print(False & True)
**Exemplo**: Tabela da verdade do operador `not` (não).
print(not True)
print(not False)
### **5.4. Conversão**
Podemos converter tipos numéricos e *strings* para booleanos através do método nativo `bool`:
idade = 19
tipo_sangue = 'O-'
filhos = 0
telefone_fixo = None
telefone_fixo = ''

print(bool(idade))
print(bool(tipo_sangue))
print(bool(filhos))
print(bool(telefone_fixo))
print(bool(telefone_fixo))
### **5.5. Revisitando a motivação**
Compara se os dados fornecidos pelo usuário são iguais aos dados do cadastro:
usuario_igual = usuario == usuario_cadastro
senha_igual = senha == senha_cadastro

print(usuario_igual)
print(senha_igual)
Decide se concede o acesso:
conceder_acesso = usuario_igual & senha_igual
print(conceder_acesso)
## 6. Operations with data structures
### 6.1.1. Operações com Listas - Parte 01
# Criar uma lista
minha_lista = [1, 2, 3, 4, 5]

# Adicionar um elemento no final da lista
minha_lista.append(6)

# Remover o último elemento da lista
minha_lista.pop()

# Inserir um elemento em uma posição específica
minha_lista.insert(2, 7)

# Remover um elemento específico
minha_lista.remove(3)

# Concatenar duas listas
outra_lista = [8, 9, 10]
lista_combinada = minha_lista + outra_lista

# Ordenar a lista
minha_lista.sort()

# Inverter a lista
minha_lista.reverse()

# Encontrar o índice de um elemento
indice = minha_lista.index(5)

# Contar o número de ocorrências de um elemento
contagem = minha_lista.count(2)

# Verificar se um elemento está na lista
elemento_na_lista = 2 in minha_lista

# Copiar uma lista
copia_da_lista = minha_lista.copy()
### 6.1.2. Operações com Listas - Parte 02
#### Como classificar uma lista python com base na ordem de outra?
lista_de_referência = ['b', 'a', 'c']
lista_a_ordenar = ['ciao', 'aondo', 'bello']

# Ordena a lista_a_ordenar com base na ordem da lista_de_referência
lista_ordenada = sorted(lista_a_ordenar, key=lambda x: lista_de_referência.index(x[0]))

print(lista_ordenada)
lista_de_referência = [1, 2, 3, 4, 5]
lista_a_ordenar = [3, 1, 2]

# Ordena a lista_a_ordenar com base na ordem da lista_de_referência
lista_ordenada = sorted(lista_a_ordenar, key=lambda x: lista_de_referência.index(x))

print(lista_ordenada)
lista_a_ordenar = [3, 1, 4, 2]
lista_de_referência = [2, 1, 3, 4]

# Usa a função zip() para unir as duas listas e depois ordena com base na lista_de_referência
lista_ordinata = [x for _, x in sorted(zip(lista_de_referência, lista_a_ordenar))]

print("Lista ordenada com base na lista de referência:", lista_ordinata)
#### Repetição de elementos
lista = [1, 2, 3, 4, 2, 2, 3, 1, 2]

# Conta o número de vezes que o elemento 2 se repetiu na lista
contegio = lista.count(2)

print("O número de vezes que o elemento 2 se repetiu na lista é:", contegio)
from collections import Counter

lista = [1, 2, 3, 4, 2, 2, 3, 1, 2]

# Conta o número de repetições de cada elemento na lista
conteggio_elementi = Counter(lista)

print("Contagem dos elementos na lista:", conteggio_elementi)
#### Agrupamento
lista1 = [1, 2, 3, 4, 5]
lista2 = [4, 5, 6, 7, 8]

intersecao = list(set(lista1) & set(lista2))

print("Elementos que são a interseção entre as duas listas:", intersecao)
lista1 = [1, 2, 3, 4, 5]
lista2 = [4, 5, 6, 7, 8]

intersecao = list(set(lista1).intersection(lista2))

print("Elementos que são a interseção entre as duas listas:", intersecao)
lista1 = [1, 2, 3, 4, 5]
lista2 = [2, 4, 6]

nova_lista = [x for x in lista1 if x not in lista2]

print("Nova lista após remover os elementos de lista2:", nova_lista)
lista1 = [1, 2, 3, 4, 5]
lista2 = [4, 5, 6, 7, 8]

diferenca_lista1 = list(set(lista1) - set(lista2))
diferenca_lista2 = list(set(lista2) - set(lista1))

print("Elementos diferentes em lista1:", diferenca_lista1)
print("Elementos diferentes em lista2:", diferenca_lista2)
#### For dentro de uma lista
lista_original = [1, 2, 3, 4, 5]

# Usando uma compreensão de lista para dobrar cada elemento
lista_dobrada = [x * 2 for x in lista_original]

print(lista_dobrada)  # Saída: [2, 4, 6, 8, 10]
### 6.2.1. Operações com Dicionários - Parte 01
# Criando um dicionário
meu_dicionario = {"nome": "João", "idade": 30, "cidade": "São Paulo"}

# Acessando valores por chave
nome = meu_dicionario["nome"]
idade = meu_dicionario["idade"]

# Adicionando um novo par chave-valor
meu_dicionario["profissão"] = "Engenheiro"

# Modificando um valor existente
meu_dicionario["idade"] = 31

# Verificando se uma chave existe
if "cidade" in meu_dicionario:
  print("A chave 'cidade' existe")

# Excluindo um par chave-valor
del meu_dicionario["cidade"]

# Excluindo utilizando pop():
meu_dicionario = {'a': 1, 'b': 2, 'c': 3}

# Removendo e retornando o valor associado à chave 'b'
valor_removido = meu_dicionario.pop('b')

print(meu_dicionario)  # Saída: {'a': 1, 'c': 3}
print(valor_removido)  # Saída: 2

# Iterando sobre as chaves
for chave in meu_dicionario:
  print('Iterando sobre as chaves')
  print(chave)

# Iterando sobre os valores
for valor in meu_dicionario.values():
  print('Iterando sobre os valores')
  print(valor)

# Pegue os valores e as chaves
print('Pegue os valores e as chaves')
meu_dicionario = {"a": 1, "b": 2, "c": 3}

# Obter as chaves
chaves = meu_dicionario.keys()
print("Chaves:", chaves)

# Obter os valores
valores = meu_dicionario.values()
print("Valores:", valores)

meu_dicionario = {"a": 1, "b": 2, "c": 3}

# Iterar sobre chaves e valores simultaneamente
for chave, valor in meu_dicionario.items():
    print("Chave:", chave, "| Valor:", valor)


# Iterando sobre os pares chave-valor
for chave, valor in meu_dicionario.items():
  print(f"{chave}: {valor}")

# Modificar um elemento em um dicionário
print('Modificar um elemento em um dicionário')
meu_dicionario = {'a': 1, 'b': 2, 'c': 3}

# Modificando o valor associado à chave 'b'
meu_dicionario['b'] = 42

print(meu_dicionario)  # Saída: {'a': 1, 'b': 42, 'c': 3}


# Copiando um dicionário
novo_dicionario = meu_dicionario.copy()

# Fundindo dois dicionários
dicionario1 = {"a": 1, "b": 2}
dicionario2 = {"c": 3, "d": 4}
dicionario1.update(dicionario2)

# Limpando um dicionário
meu_dicionario.clear()
#### Posição de um elemento

Em um dicionário Python, não há uma noção direta de "posição" de um elemento, porque os dicionários são estruturas de dados sem ordem definida. Em outras palavras, os elementos em um dicionário não têm uma posição fixa como em uma lista ou tupla, onde você pode se referir a um elemento pelo seu índice.

No entanto, você pode encontrar a chave associada a um determinado valor em um dicionário. Aqui está como você pode fazer isso:
meu_dicionario = {'a': 1, 'b': 2, 'c': 3, 'd': 2}

# Encontrar a chave(s) associada(s) ao valor 2
chaves = [chave for chave, valor in meu_dicionario.items() if valor == 2]

print(chaves)  # Saída: ['b', 'd']
### 6.2.2. Operações com Dicionários - Parte 02
#### Como ordenar um dicionário com base nas chaves
# Ordenar com base nas chaves:
meu_dicionario = {'z': 3, 'x': 1, 'y': 2}

# Ordenar o dicionário pelas chaves
dicionario_ordenado_chaves = dict(sorted(meu_dicionario.items()))

print(dicionario_ordenado_chaves)  # Saída: {'x': 1, 'y': 2, 'z': 3}
#### Como ordenar um dicionário com base nos valores
# Ordenar com base nos valores:
meu_dicionario = {'z': 3, 'x': 1, 'y': 2}

# Ordenar o dicionário pelos valores
dicionario_ordenado_valores = dict(sorted(meu_dicionario.items(), key=lambda item: item[1]))

print(dicionario_ordenado_valores)  # Saída: {'x': 1, 'y': 2, 'z': 3}
import collections

meu_dicionario = {'z': 3, 'x': 1, 'y': 2}

# Criar um OrderedDict ordenado pelas chaves
dicionario_ordenado_chaves = collections.OrderedDict(sorted(meu_dicionario.items()))

print(dicionario_ordenado_chaves)  # Saída: OrderedDict([('x', 1), ('y', 2), ('z', 3)])
#### Como ordenar um dicionário com base em uma lista
# Para ordenar um dicionário com base em uma lista

meu_dicionario = {'banana': 3, 'maçã': 1, 'laranja': 2}
ordem_chaves = ['laranja', 'banana', 'maçã']

dicionario_ordenado = {chave: meu_dicionario[chave] for chave in ordem_chaves}
print(dicionario_ordenado)

import collections
dicionario_ordenado = collections.OrderedDict((chave, meu_dicionario[chave]) for chave in ordem_chaves)
print(dicionario_ordenado)
meu_dicionario = {'banana': 3, 'maçã': 1, 'laranja': 2}

# Ordenando o dicionário pelas chaves
dicionario_ordenado = dict(sorted(meu_dicionario.items(), key=lambda item: item[1]))

print(dicionario_ordenado)
meu_dicionario = {'banana': 3, 'maçã': 1, 'laranja': 2}
ordem_chaves = ['laranja', 'banana', 'maçã']

# Ordenando o dicionário com base na lista de chaves usando sorted() e lambda
dicionario_ordenado = dict(sorted(meu_dicionario.items(), key=lambda item: ordem_chaves.index(item[0])))

print(dicionario_ordenado)
#### Interseção de dois ou mais dicionários com base nas chaves
dicionario1 = {'a': 1, 'b': 2, 'c': 3}
dicionario2 = {'b': 4, 'c': 5, 'd': 6}
dicionario3 = {'c': 7, 'd': 8, 'e': 9}

# Encontrando a interseção das chaves dos dicionários
intersecao_chaves = set(dicionario1.keys()) & set(dicionario2.keys()) & set(dicionario3.keys())

# Criando um novo dicionário contendo apenas as chaves em comum e seus valores correspondentes
dicionario_intersecao = {chave: dicionario1[chave] for chave in intersecao_chaves}

print(dicionario_intersecao)
intersecao_chaves = set(dicionario1.keys()) & set(dicionario2.keys()) & set(dicionario3.keys())
print(intersecao_chaves)
#### Interseção de dois ou mais dicionários com base nos valores
from collections import Counter

# Definindo os dicionários
dicionario1 = {'a': 1, 'b': 2, 'c': 3}
dicionario2 = {'b': 2, 'c': 3, 'd': 4}
dicionario3 = {'c': 3, 'd': 4, 'e': 5}

# Convertendo os valores dos dicionários em conjuntos para encontrar a interseção
valores1 = set(dicionario1.values())
valores2 = set(dicionario2.values())
valores3 = set(dicionario3.values())

# Encontrando a interseção dos valores dos dicionários
intersecao_valores = valores1 & valores2 & valores3
print(intersecao_valores)

# Criando um novo dicionário contendo apenas os pares chave-valor com valores em comum
dicionario_intersecao = {chave: valor for chave, valor in dicionario1.items() if valor in intersecao_valores}

print(dicionario_intersecao)
#### Difediferença entre dois ou mais dicionários com base nas chaves
dicionario1 = {'a': 1, 'b': 2, 'c': 3}
dicionario2 = {'b': 4, 'c': 5, 'd': 6}

# Encontrando a diferença das chaves dos dicionários
diferenca_chaves = set(dicionario1.keys()) - set(dicionario2.keys())

print(diferenca_chaves)  # Saída: {'a'}
diferenca_chaves = set(dicionario1.keys()) - set(dicionario2.keys()) - set(dicionario3.keys())
print(diferenca_chaves)
#### Difediferença entre dois ou mais dicionários com base nos valores
dicionario1 = {'a': 1, 'b': 2, 'c': 3}
dicionario2 = {'b': 2, 'c': 4, 'd': 5}

# Encontrando a diferença dos valores dos dicionários
diferenca_valores = set(dicionario1.items()) - set(dicionario2.items())

print(diferenca_valores)  # Saída: {('a', 1), ('c', 3)}
diferenca_valores = set(dicionario1.items()) - set(dicionario2.items()) - set(dicionario3.items())
print(diferenca_valores)
### 6.3. Operações com Tuplas
# Criando uma tupla
tupla = (1, 2, 3, 4, 5)

# Acessando elementos da tupla
print(tupla[0])  # Saída: 1
print(tupla[2:4])  # Saída: (3, 4)

# Concatenando tuplas
tupla1 = (1, 2, 3)
tupla2 = (4, 5, 6)
tupla_concatenada = tupla1 + tupla2
print(tupla_concatenada)  # Saída: (1, 2, 3, 4, 5, 6)

# Repetindo elementos da tupla
tupla_repetida = tupla * 2
print(tupla_repetida)  # Saída: (1, 2, 3, 4, 5, 1, 2, 3, 4, 5)

# Verificando se um elemento está na tupla
print(2 in tupla)  # Saída: True
print(6 in tupla)  # Saída: False

# Encontrando o índice de um elemento
print(tupla.index(3))  # Saída: 2

# Contando a quantidade de vezes que um elemento aparece
print(tupla.count(1))  # Saída: 1
---
# **Conteúdo Extra**


### Documentação Google Colab

 - [Google Colab FAQ](https://research.google.com/colaboratory/faq.html): Perguntas mais frequentes sobre o Google Colab.
### Documentação Python


 - [Tipos Nativos](https://docs.python.org/pt-br/3/library/stdtypes.html): Documentação oficial dos tipos de variáveis nativas da linguagem Python;
 - [Métodos de String](https://www.w3schools.com/python/python_ref_string.asp): Lista de métodos de *strings* com exemplos.
### Cadernos

 - [JupyterLab](https://jupyter.org/): Projeto original de de cadernos;
 - [GCP Notebooks](https://cloud.google.com/ai-platform-notebooks): Solução autogerenciada de cadernos da empresa Google Cloud Platform (GCP);
 - [Azure Notebooks](https://notebooks.azure.com/): Solução autogerenciada de cadernos da empresa Microsoft Azure;
 - [Databricks Notebooks](https://databricks.com/product/collaborative-notebooks): Solução autogerenciada de cadernos da empresa Databricks;
 - [AWS Sagemaker Notebooks](https://aws.amazon.com/pt/sagemaker/): Solução autogerenciada de cadernos da empresa Amazon Web Services (AWS).

linha10 = ['Mas', 'eis', 'que', 'chega', 'a', 'roda', 'viva']

# Imprimindo resposta
imprimindo_resposta = []
total = 0
vez = 0

for palavra in linha10:
    total = total + 1

for palavra in linha10:
    vez = vez + 1
    if vez < total:
     cont = palavra + '-'
     imprimindo_resposta.append(cont)
    else:
       imprimindo_resposta.append(palavra)

print(imprimindo_resposta)
<img src="https://raw.githubusercontent.com/enzoschitini/Python-Notebook-Library/refs/heads/main/img/Estruturas%20de%20Dados.png" alt="ebac-logo">

---

# **Módulo 02** | Python: Estruturas de Dados
Caderno de **Aula**<br> 
Desenvolvedor [Enzo Schitini](https://enzo-schitini.bubbleapps.io/version-test/)

---
# **Tópicos**

<ol type="1">
  <li>Listas;</li>
  <li>Conjuntos;</li>
  <li>Dicionários.</li>
</ol>
---
# **Aulas**
<img src="Group2.png" alt="ebac-logo"> 
## 1\. Listas
### **1.1. Motivação** 
O aplicativo do seu banco registra toda a sua movimentação financeira. O final do dia, o app consolida o saldo final para que você possa controlar sua vida financeira.
dia_11_saldo_inicial = 1000
dia_11_transacao_1 = 243
dia_11_transacao_2 = -798.58
dia_11_transacao_3 = 427.12
dia_11_transacao_4 = -10.91
dia_11_saldo_final = dia_11_saldo_inicial + dia_11_transacao_1 + dia_11_transacao_2 + dia_11_transacao_3 + dia_11_transacao_4
print(dia_11_saldo_final)
Será que exista uma forma melhor de armazenar as transações diárias?
### **1.2. Definição** 
Armazenam sequências mutáveis e ordenadas de valores. São do tipo `list`:

usuario_web = ['André Perez', 'andre.perez', 'andre123', 'andre.perez@gmail.com']

print(usuario_web)
print(type(usuario_web))
idade = 20
saldo_em_conta = 723.15
usuario_loggedin = True

usuario_web = ['André Perez', idade, 'andre.perez', 'andre123', 'andre.perez@gmail.com', saldo_em_conta, usuario_loggedin]

print(usuario_web)
print(type(usuario_web))
### **1.3. Operações** 
As operações da estrutura do tipo *list* são:


*   `+` (concatenação).
**Exemplo**: Fabricantes de *hardware* mobile
fabricantes_mobile_china = ['xiaomi', 'huawei']
fabricantes_mobile_eua = ['apple', 'motorola']
fabricantes_mobile = fabricantes_mobile_china + fabricantes_mobile_eua

print(fabricantes_mobile_china)
print(fabricantes_mobile_eua)
print(fabricantes_mobile)
Outra operação muito utilizada é a de fatiamento (*slicing*), semelhante ao de *strings*:
Fatiamento fixo:
print(f'0: {fabricantes_mobile[0]}')
print(f'-1: {fabricantes_mobile[-1]}')
Fatiamento por intervalo:
fabricantes_mobile_china = fabricantes_mobile[0:2]
fabricantes_mobile_eua = fabricantes_mobile[2:len(fabricantes_mobile)]

print('china: ' + str(fabricantes_mobile_china))
print('eua: ' + str(fabricantes_mobile_eua))

Podemos adicionar elementos a uma posição específica da lista:
print(fabricantes_mobile)
fabricantes_mobile[2] = 'nokia'
print(fabricantes_mobile)
### **1.4. Métodos**
São métodos nativos do Python que nos ajudam a trabalhar no dia a dia com listas.
juros = [0.05, 0.07, 0.02, 0.04, 0.08]
print(juros)
# inserir um elemento sem substituir: list.insert(index, val)
juros.insert(0, 0.10)
print(juros)
# inserir um elemento no fim da lista: list.append(val)
juros.append(0.09)
print(juros)
# remover um elemento pelo valor: list.remove(val)
juros.remove(0.1)
print(juros)
# remover um elemento pelo índice: list.pop(val)
terceiro_juros = juros.pop(2)
print(terceiro_juros)
print(juros)
### **1.5. Conversão**
Podemos converter alguns tipos de variáveis em listas, como *strings*.
email = 'andre.perez@gmail.com'
caracteres_email = list(email)

print(email)
print(caracteres_email)
### **1.6. Revisitando a motivação** 
dia_11_saldo_inicial = 1000
dia_11_transacoes = []

dia_11_transacoes.append(243)
dia_11_transacoes.append(-798.58)
dia_11_transacoes.append(427.12)
dia_11_transacoes.append(-10.91)

print(dia_11_transacoes)
dia_11_saldo_final = dia_11_saldo_inicial + dia_11_transacoes[0] + dia_11_transacoes[1] + dia_11_transacoes[2] + dia_11_transacoes[3]
print(dia_11_saldo_final)
<img src="Group2.png" alt="ebac-logo"> 
## 2\. Conjuntos
### **2.1. Motivação** 
Você trabalha como analista de dados de mídias sociais e precisa descobrir todas as *hashtags* que alcançaram o *top trending* do Twitter durante uma semana. Você já conseguiu as *hashtags* por dia da semana:
hashtags_seg = ['#tiago', '#joao', '#bbb']
hashtags_ter = ['#sarah', '#bbb', '#fiuk']
hashtags_qua = ['#gil', '#thelma', '#lourdes']
hashtags_qui = ['#rafa', '#fora', '#danilo']
hashtags_sex = ['#juliete', '#arthur', '#bbb']
Um simples concateção de listas fará com que a *hashtag* #bbb, entre outras, apareça mais de uma vez.
hashtags_semana = hashtags_seg + hashtags_ter + hashtags_qua + hashtags_qui + hashtags_sex
print(hashtags_semana)
### **2.2. Definição** 
Armazenam sequências imutáveis e desordenadas valores, sem repetição. São do tipo `set`:
frutas = {'banana', 'maca', 'uva', 'uva'}

print(frutas)
print(type(frutas))
### **2.3. Operações** 
As operações da estrutura do tipo *set* são:


*   `-` (diferença).
norte_europa = {'reino unido', 'suecia', 'russia', 'noruega', 'dinamarca'}
escandinavia = {'noruega', 'dinamarca', 'suecia'}
norte_europa_nao_escandivano = norte_europa - escandinavia
print(norte_europa_nao_escandivano)
escandivano_nao_norte_europa = escandinavia - norte_europa
print(escandivano_nao_norte_europa)
### **2.4. Métodos**
São métodos nativos do Python que nos ajudam a trabalhar no dia a dia com conjuntos.
cursos = {'Exatas', 'Humanas', 'Biológicas'}
print(cursos)
# inserir um elemento no conjunto: set.add(val)
cursos.add('Saúde')
print(cursos)
# remover um elemento no conjunto: set.remove(val)
cursos.remove('Saúde')
print(cursos)
### **2.5. Conversão**
Podemos converter conjuntos para lista e vice e versa.
times_paulistas = {'São Paulo', 'Palmeiras', 'Corinthians', 'Santos'}

print(times_paulistas)
print(type(times_paulistas))
print(list(times_paulistas))
print(type(list(times_paulistas)))
### **2.6. Revisitando a motivação** 
print(hashtags_semana)
print(len(hashtags_semana))
hashtags_semana = list(set(hashtags_seg + hashtags_ter + hashtags_qua + hashtags_qui + hashtags_sex))

print(hashtags_semana)
print(len(hashtags_semana))
<img src="Group2.png" alt="ebac-logo"> 
## 3\. Dicionários
### **3.1. Motivação** 
Para se conectar a uma rede wi-fi, você precisa de duas informações: o nome da rede e a senha de acesso. Quando você vai acessar uma nova rede, você encontra uma lista de redes disponíveis: 
wifi_disponiveis = ['rede1', 'cnx_cnx', 'uai-fi', 'r3d3']
print(wifi_disponiveis)
Você consegue identificar quais são os nome de redes e suas respectivas senhas? Talvez uma `list` não seja a melhor opção para armazenar esse tipo de dado.
### **3.2. Definição** 
Armazenam sequências no formato chave-valor. São do tipo `dict`.

brasil = {'capital': 'Brasília', 'idioma': 'Português', 'populacao': 210}

print(brasil)
print(type(brasil))
Não é permite chaves duplicadas.
carro = {
    'marca': 'Volkswagen',
    'modelo': 'Polo',
    'ano': 2021,
    'ano': 2004
}

print(carro)
Podemos criar dicionários compostos:
cadastro = {
    'andre': {
        'nome': 'Andre Perez', 
        'ano_nascimento': 1992, 
        'pais': {
            'pai': {
              'nome': '<nome-do-pai> Perez', 
              'ano_nascimento': 1971
            },
            'mae': {
              'nome': '<nome-da-mae> Perez', 
              'ano_nascimento': 1973
            },
        }
    }
}

print(cadastro)
cadastro['andre']['pais']['mae']['ano_nascimento']
### **3.3. Operações** 
credito = {'123': 750, '789': 980}
Elementos são acessados pela sua chave.
score_123 = credito['123']
score_789 = credito['789']

print(score_123)
print(score_789)
Elementos são atualizados pela sua chave.
credito['123'] = 435
print(credito)
Para adicionar um novo elemento, basta criar um novo elemento chave-valor:
credito['456'] = 1000
print(credito)
### **3.4. Métodos**
São métodos nativos do Python que nos ajudam a trabalhar no dia a dia com dicionários.
artigo = dict(
    titulo='Modulo 02 | Python: Estruturas de Dados',
    corpo='Topicos, Aulas, Listas, Conjuntos, Dicionários, ...',
    total_caracteres=1530
)
# adicionar/atualizar um elemento pelo chave-valor: dict.update(dict)
print(artigo)
artigo.update({'total_caracteres': 7850})
print(artigo)

artigo['total_caracteres'] = 7850
# remover um elemento pelo chave: dict.pop(key)
print(artigo)
total_caracteres = artigo.pop('total_caracteres')
print(artigo)
### **3.5. Conversão**
Podemos converter as chaves e os items de um dicionário em uma lista.
artigo = dict(
    titulo='Modulo 02 | Python: Estruturas de Dados',
    corpo='Topicos, Aulas, Listas, Conjuntos, Dicionários, ...',
    total_caracteres=1530
)
chaves = list(artigo.keys())

print(chaves)
print(type(chaves))
valores = list(artigo.values())

print(valores)
print(type(valores))
### **3.6. Revisitando a motivação** 
wifi_disponiveis = []
rede = {'nome': 'rede1', 'senha': 'cnx_cnx'}
wifi_disponiveis.append(rede)
rede = {'nome': 'uai-fi', 'senha': 'r3d3'}
wifi_disponiveis.append(rede)
print(wifi_disponiveis)
<img src="https://raw.githubusercontent.com/enzoschitini/Python-Notebook-Library/refs/heads/main/img/Fluxo%20Condicional%20%26%20Repeti%C3%A7%C3%A3o.png" alt="ebac-logo">

---

# **Módulo 03** | Python: Fluxo Condicional & Repetição
Caderno de **Aula**<br> 
Desenvolvedor [Enzo Schitini](https://enzo-schitini.bubbleapps.io/version-test/)

---
# **Tópicos**

<ol type="1">
  <li>Estrutura condicional if / else / elif;</li>
  <li>Estrutura condicional try / catch / finally;</li>
  <li>Estrutura de repetição for / in.</li>
</ol>
---
# **Aulas**
<img src="Group2.png" alt="ebac-logo"> 
## 1\. Estrutura condicional if / else / elif
### **1.1. if / else** 
Estrutura de alteração de fluxo lógico do código, avalia um valor booleano ou uma comparação lógica. **Note** a identação do código.
```python
if <booleano / comparação lógica> == True:
  <execute este código>
else:
  <senão execute este código>
```
if False:
  print("Verdadeiro")
else:
  print("Falso")
**Exemplo**: Código de segurança de um cartão de crédito
codigo_de_seguranca = '291'
codigo_de_seguranca_cadastro = '010'

pode_efetuar_pagamento = codigo_de_seguranca == codigo_de_seguranca_cadastro
print(pode_efetuar_pagamento)
if pode_efetuar_pagamento:
  print("Pagamento efetuado")
else:
  print("Erro: Código de segurança inválido")
if codigo_de_seguranca == codigo_de_seguranca_cadastro:
  print("Pagamento efetuado")
else:
  print("Erro: Código de segurança inválido")
**Exemplo**: Código e senha de segurança de um cartão de crédito
codigo_de_seguranca = '852'
codigo_de_seguranca_cadastro = '852'

senha = '7783'
senha_cadastro = '7783'
Revisitando a tabela da verdade:
| CÓDIGO        | SENHA        | | | CÓDIGO OR SENHA   | | CÓDIGO AND SENHA  | | NOT CÓDIGO    |
|----------|----------|-|-|----------|-|----------|-|----------|
| **TRUE** | **TRUE** | | | **TRUE** | | **TRUE** | | FALSE    |
| **TRUE** | FALSE    | | | **TRUE** | | FALSE    | | FALSE    |
| FALSE    | FALSE    | | | FALSE    | | FALSE    | | **TRUE** |
| FALSE    | **TRUE** | | | **TRUE** | | FALSE    | | **TRUE** |
if (codigo_de_seguranca == codigo_de_seguranca_cadastro) & (senha == senha_cadastro):
  print("Pagamento efetuado")
else:
  print("Erro: Pagamento não efetuado")
if (codigo_de_seguranca != codigo_de_seguranca_cadastro) | (senha != senha_cadastro):
  print("Erro: Pagamento não efetuado")
else:
  print("Pagamento efetuado")
### **1.2. if / elif / else**
Podemos também avaliar múltipla condições.
```python
if <1º booleano / 1ª comparação lógica> == True:
  <execute este código se a primeira condição for verdade>
elif <2º booleano / 2ª comparação lógica> == True:
  <execute este código se a segunda condição for verdade>
else:
  <senão execute este código>
```
codigo_de_seguranca = '802'
codigo_de_seguranca_cadastro = '852'

senha = '7703'
senha_cadastro = '7783'
| CÓDIGO        | SENHA        | | | CÓDIGO AND SENHA  | MENSAGEM |
|----------|----------|-|-|----------|-|
| **TRUE** | **TRUE** | | | **TRUE** | Pagamento efetuado |
| **TRUE** | FALSE    | | | FALSE    | Erro: Senha inválida |
| FALSE    | FALSE    | | | FALSE    | Erro: Código de segurança e senha inválidos |
| FALSE    | **TRUE** | | | FALSE    | Erro: Código de segurança inválido |
if (codigo_de_seguranca == codigo_de_seguranca_cadastro) & (senha == senha_cadastro):
  print("Pagamento efetuado")

elif (codigo_de_seguranca != codigo_de_seguranca_cadastro) & (senha == senha_cadastro):
  print("Erro: Código de segurança inválido")

elif (codigo_de_seguranca == codigo_de_seguranca_cadastro) & (senha != senha_cadastro):
  print("Erro: Senha inválida inválida")

else:
  print("Erro: Código de segurança e senha inválidos")
<img src="Group2.png" alt="ebac-logo"> 
## 2\. Estrutura condicional try /except / finally
### **2.1. Exceção** 
Exceções são erros que podem acontecer durante a execução do nosso código.
**Exemplo**: Erro de operações numéricas impossíveis
preco = 132.85
pessoas = 0
#valor_por_pessoa = preco / pessoas
**Exemplo**: Erro por combinações de tipos diferentes
nome = 'Andre Perez'
idade = True
#apresentacao = 'Fala pessoal, meu nome é ' + nome + ' e eu tenho ' + idade + ' anos'
**Exemplo**: Erro de indexação de estrutura de dados
anos = [2019, 2020, 2021]
#ano_atual = anos[3]
cursos = {
    'python': {
        'nome': 'Python para Análise de Dados', 'duracao': 2.5
    }, 
    'sql': {
        'nome': 'SQL para Análise de Dados', 'duracao': 2
    }
}
#curso_atual = cursos['analista']
### **2.2. try / except** 
Estrutura para tratar exceções:
preco = 132.85
pessoas = 2

try:
  valor_por_pessoa = preco / pessoas
  print(valor_por_pessoa)
except ZeroDivisionError:
  print('Número de pessoas inválido. Espera-se um valor maior que 0 e obteve-se um valor igual a ' + str(pessoas))
anos = [2019, 2020, 2021]

try:
  ano_atual = anos[3]
  print(ano_atual)
except Exception:
  print('Lista de anos é menor que o valor escolhido. Espera-se um valor entre 0 e ' + str(len(anos) - 1))
anos = [2019, 2020, 2021]

try:
  ano_atual = anos[3]
  print(ano_atual)
except Exception as exc:
  print('Descrição da exceção: ' + str(exc))
  print('Tipo da exceção: ' + str(type(exc)))
  print('Lista de anos é menor que o valor escolhido. Espera-se um valor entre 0 e ' + str(len(anos) - 1))
anos = [2019, 2020, 2021]

try:
  ano_atual = anos[f]
  print(ano_atual)
except IndexError:
  print('Lista de anos é menor que o valor escolhido. Espera-se um valor entre 0 e ' + str(len(anos) - 1))
except Exception as exc:
  print(exc)
  print("Nome do erro: " + str(type(exc)))
  print('Erro genérico')
### **2.3. try / except / finally** 
nome = 'Andre Perez'
idade = 19

#idade = str(idade)

try:
  apresentacao = 'Fala pessoal, meu nome é ' + nome + ' e eu tenho ' + idade + ' anos'
  print(apresentacao)
except TypeError:
  idade = str(idade)
finally:
  print('Segunda chance')
  apresentacao = 'Fala pessoal, meu nome é ' + nome + ' e eu tenho ' + idade + ' anos'
  print(apresentacao)
### 2.4. Filtrando o nome do erro
# Filtrando il nome dell'errore

anni = [2022, 2023, 2024]

try:
  anno_atuale = anni[6]
  print(anno_atuale)
except Exception as exc:
  # Encontrando a posição
  pisizione_rischio = str(type(exc)).find("'") + 1
  posizione_fine = str(type(exc)).find(">") - 1
  risposta = str(type(exc))[pisizione_rischio:posizione_fine]
  # Imprimindo resposta
  print("L'operazione non può essese eseguita dall'algoritmo!")
  print("Errore:", risposta, "--> descrizione:", str(exc))
### 2.5. Tentativa de executar uma operação que pode gerar uma exceção
try:
    # Tentativo di eseguire un'operazione che potrebbe generare un'eccezione
    x = 1 / 0
except ZeroDivisionError:
    # Cosa fare se si verifica l'eccezione ZeroDivisionError
    print("Errore: divisione per zero!")
try:
    # Tentativo di eseguire un'operazione che potrebbe generare un'eccezione
    lista = [1, 0, 2]
    for x in lista:
        divisione = 4 / x
        print(divisione)
except ZeroDivisionError:
    # Cosa fare se si verifica l'eccezione ZeroDivisionError
    print("Errore: divisione per zero!")
### 2.6. Comando continue
lista = [1, 0, 2]
for x in lista:
    try:
        divisione = 4 / x
        print(divisione)
    except ZeroDivisionError:
        print(f"Errore: 4/{x} divisione per zero!")
        continue
<img src="Group2.png" alt="ebac-logo"> 
## 3\. Estrutura repetição for / in
### **3.1. for / in** 
Estrutura que permite a execução repetida de um bloco de código repetidas vezes.
```python
for variavel_temporaria in coleção:
  <execute este código>
```
### **3.2. for / in / range** 
Estrutura que permite a execução repetida de um bloco de código **n** vezes.
for valor in range(6):
  print(valor)
soma = 0

for valor in range(0, 100000):
  soma = soma + valor
  # print(soma)

print(soma)
for multiplo_dois in range(2, 10, 3):
  print(multiplo_dois)
### **3.3. for / in / list** 
Estrutura que permite a execução de um bloco de código para todos os elementos de uma lista.
frutas = ['maca', 'banana', 'laranja', 'uva', 'pera']

for fruta in frutas:
  print(fruta)
frase = 'Fala pessoal, meu nome é André Perez.'

for caracter in frase:
  if (caracter == 'A') | (caracter == 'z'):
    print(f"A letra '{caracter}' está presente na frase.")
### **3.4. for / in / dict** 
Estrutura que permite a execução de um bloco de código para todos os elementos de um dicionário.
credito = {'123': 750, '456': 812, '789': 980}
for chave, valor in credito.items():
  print(f'Para o documento {chave}, o valor do escore de crédito é {valor}.')
  print('\n')
for chave in credito.keys():
  print(chave)
  print(credito[chave])
  print(f'Para o documento {chave}, o valor do escore de crédito é {credito[chave]}.')
  print('\n')
for valor in credito.values():
  print(valor)
  print(f'O valor do escore de crédito é {valor}, mas não temos mais as chaves :(.')
  print('\n')
### **3.5. break / continue** 
Estrutura que permite a quebra ou o avanço de um laço de repetição.
for i in range(0, 10*10*10*10*10*10):
  print(i)
  if i == 10:
    break
numero = 3

if numero % 2 == 0:
  print(f'O numero {numero} é par')
else:
  print(f'O numero {numero} é impar')
numeros = [361, 553, 194, 13, 510, 33, 135]

for numero in numeros:

  if numero % 2 == 0:
    print(f'O numero {numero} é par')
    break
  else:
    print(f'O numero {numero} é impar')
numeros = [361, 553, 194, 13, 510, 33, 135]

for numero in numeros:

  if numero % 2 == 0:
    print(f'O numero {numero} é par')
    break
  else:
    continue
    print(f'O numero {numero} é impar')
<img src="https://raw.githubusercontent.com/enzoschitini/Python-Notebook-Library/refs/heads/main/img/Arquivos%20%26%20Fun%C3%A7%C3%B5es.png" alt="ebac-logo">

---

# **Módulo 04** | Python: Arquivos & Funções
Caderno de **Aula**<br> 
Desenvolvedor [Enzo Schitini](https://enzo-schitini.bubbleapps.io/version-test/)

---
# **Tópicos**

<ol type="1">
  <li>Leitura;</li>
  <li>Escrita;</li>
  <li>Funções;</li>
  <li>Escopo.</li>
</ol>
---
# **Aulas**
<img src="Group2.png" alt="ebac-logo"> 
## 1\. Leitura
### **1.1. Configuração inicial** 
Vamos utilizar uma função do **Google Colab** para criar arquivos para esse módulo. **Nota**: esse código **não** é do Python e sim da ferramenta.
**Arquivo CSV:** banco.csv
%%writefile banco.csv
age,job,marital,education,default,balance,housing,loan
30,unemployed,married,primary,no,1787,no,no
33,services,married,secondary,no,4789,yes,yes
35,management,single,tertiary,no,1350,yes,no
30,management,married,tertiary,no,1476,yes,yes
59,blue-collar,married,secondary,no,0,yes,no
35,management,single,tertiary,no,747,no,no
36,self-employed,married,tertiary,no,307,yes,no
39,technician,married,secondary,no,147,yes,no
41,entrepreneur,married,tertiary,no,221,yes,no
43,services,married,primary,no,-88,yes,yes
### **1.2. with / open** 
Comando para ler arquivos.

```python
with open(file='<caminho do arquivo>', mode='<modo de leitura>', encoding='<decodificador>') as <apelido>:
  bloco de código
```
Os modos de leitura são:

*   **r**: Abrir o arquivo para leitura (padrão).


### **1.3. read** 
Comando para ler todo o conteúdo de um arquivo.
conteudo = None

with open(file='./banco.csv', mode='r', encoding='utf8') as arquivo:
  conteudo = arquivo.read()

print(conteudo)

# Com o modo 'r' não pode mudar o arquivo
### **1.4. readline** 
Comando para ler o conteúdo de um arquivo uma linha por vez. Recomendado para arquivos grandes, maiores que 100Mb
conteudo = []

with open(file='./banco.csv', mode='r', encoding='utf8') as arquivo:
  linha = arquivo.readline() # lê a primeira linha
  while linha: # Enquando uma condição for verdadeira
    conteudo.append(linha)
    linha = arquivo.readline() # lê uma nova linha, se a linha não existir, salva o valor None

print(conteudo)
for linha in conteudo:
  print(linha)
**Exemplo**: Extraindo os valores da primeira coluna (idade).
idades = []

with open(file='./banco.csv', mode='r', encoding='utf8') as arquivo:
  linha = arquivo.readline() # lê o cabeçalho
  linha = arquivo.readline() # lê a primeira linha
  while linha:
    linha_separada = linha.split(sep=',') # quebra a string nas virgulas e salva os resultados em uma lista
    idade = linha_separada[0] # seleciona o primeiro elemento da lista
    idade = int(idade) # converte o valor de string para integer (inteiro)
    idades.append(idade) # salva o valor na lista de idades
    linha = arquivo.readline() # lê uma nova linha, se a linha não existir, salva o valor None

print(idades)
<img src="Group2.png" alt="ebac-logo"> 
## 2\. Escrita
### **2.1. with / open** 
Comando para ler/escrever arquivos.

```python
with open(file='<caminho do arquivo do arquivo>', mode='<modo de leitura/escrita>', encoding='<decodificador>') as <apelido>:
  bloco de código
```
Os modos de leitura são:

*   **r**: Abrir o arquivo para leitura (padrão);
*   **w**: Abrir o arquivo para escrita (sobreescreve o arquivo original).
*   **a**: Abrir o arquivo para acrescentar (não sobreescreve o arquivo original)


### **2.2. write** 
Comando para escrever em um arquivo, se o arquivo não existir, ele será criado.
- Modo de escrita (w).
with open(file='idades.csv', mode='w', encoding='utf8') as fp:
  linha = 'idade' + '\n'
  fp.write(linha)
  for idade in idades:
    linha = str(idade) + '\n'
    fp.write(linha)
 - Modo de acréscimo (a).
with open(file='idades.csv', mode='a', encoding='utf8') as fp:
  for idade in idades:
    linha = str(idade + 100) + '\n'
    fp.write(linha)
**Exemplo**: Copiando um arquivo com uma extensão diferente.
%%writefile banco-texto.txt
age,job,marital,education,default,balance,housing,loan
30,unemployed,married,primary,no,1787,no,no
33,services,married,secondary,no,4789,yes,yes
35,management,single,tertiary,no,1350,yes,no
30,management,married,tertiary,no,1476,yes,yes
59,blue-collar,married,secondary,no,0,yes,no
35,management,single,tertiary,no,747,no,no
36,self-employed,married,tertiary,no,307,yes,no
39,technician,married,secondary,no,147,yes,no
41,entrepreneur,married,tertiary,no,221,yes,no
43,services,married,primary,no,-88,yes,yes
with open(file='./banco-texto.txt', mode='r', encoding='utf8') as leitura:
  with open(file='./banco-csv.csv', mode='w', encoding='utf8') as escrita:
    linha = leitura.readline()
    while linha:
      escrita.write(linha)
      linha = leitura.readline()
<img src="Group2.png" alt="ebac-logo"> 
## 3\. Funções
### **3.1. Motivação** 
Você trabalha na bolsa de valores e precisa simular o retorno de um investimento para diversos cenários:
valor_inicial, taxa_juros_anual, anos = 1000.00, 0.05, 10

valor_final = valor_inicial
for ano in range(1, anos+1):
  valor_final = valor_final * (1 + taxa_juros_anual)
valor_final = round(valor_final, 2)
print(f'Para um valor inicial de R$ {valor_inicial} e uma taxa de juros anual de {taxa_juros_anual}, em {anos} anos você terá R$ {valor_final}') 

valor_inicial, taxa_juros_anual, anos = 1020.00, 0.03, 10

valor_final = valor_inicial
for ano in range(1, anos+1):
  valor_final = valor_final * (1 + taxa_juros_anual)
valor_final = round(valor_final, 2)
print(f'Para um valor inicial de R$ {valor_inicial} e uma taxa de juros anual de {taxa_juros_anual}, em {anos} anos você terá R$ {valor_final}') 
Como podemos fazer para reaproveitar o código e evitar repetições?
##### **Round** 
# Round

valor = 10 / 4
valor = round(valor, 0)
print(valor)
### **3.2. Definição** 
Um bloco de código que só executado quando chamado.
```python
def <nome>(<param 1>, <param 2>, ...):
  bloco de código
  return <valor de retorno>
```

```python
var = <nome da funcao>(<param 1>, <param 2>, ...)
```
def imprime(mensagem: str):
  print(mensagem)
texto = 'Fala pessoal, meu nome é André Perez!'
imprime(mensagem=texto)
### **3.3. Retorno** 
Toda função retorna pelo menos um valor, se não específicado, retorna o valor nulo.
def maiusculo(texto: str) -> str:
  text_maiusculo = texto.upper()
  return text_maiusculo

# "-> str" tipo do retorno
nome = 'André Perez'
print(nome)

nome_maiusculo = maiusculo(texto=nome)
print(nome_maiusculo)
def extrair_usuario_email_provedor(email: str) -> (str, str):
  email_separado = email.split(sep='@')
  usuario = email_separado[0]
  provedor = email_separado[1]
  return usuario, provedor
email = 'andre.perez@gmail.com'
usuario, provedor = extrair_usuario_email_provedor(email=email)
print(usuario)
print(provedor)
### **3.3. Parâmetros** 
Parâmetros são os valores que a passamos na chamada da função.
 - Função sem parâmetro:
def pi() -> float:
  return 3.14159265359
pi = pi()
print(pi)
def imprime_pi() -> None:
  print(3.14159265359)
  return None
imprime_pi()
 - Função com parâmetro:
def escreve_arquivo_csv(nome: str, cabecalho: str, conteudos: list) -> bool:

  try: 

    with open(file=nome, mode='w', encoding='utf8') as fp:
      linha = cabecalho + '\n'
      fp.write(linha)
      for conteudo in conteudos:
        linha = str(conteudo) + '\n'
        fp.write(linha)

  except Exception as exc:
    
    print(exc)
    return False

  return True
nome = 'idades-funcao-erro.csv'
cabecalho = 'idade'
conteudos = [30, 33, 35, 30, 59, 35, 36, 39, 41, 43]
#conteudos = 10

escreveu_com_sucesso = escreve_arquivo_csv(nome=nome, cabecalho=cabecalho, conteudos=conteudos)
print(escreveu_com_sucesso)
### **3.4. Revisitando a motivação** 
def juros_compostos_anual(valor_inicial: float, taxa_juros_anual: float, anos: int) -> float:
  valor_final = valor_inicial
  for ano in range(1, anos+1):
    valor_final = valor_final * (1 + taxa_juros_anual)
  valor_final = round(valor_final, 2)
  print(f'Para um valor inicial de R$ {valor_inicial} e uma taxa de juros anual de {taxa_juros_anual}, em {anos} anos você terá R$ {valor_final}') 
  return valor_final

valor_inicial, taxa_juros_anual, anos = 1000.00, 0.05, 10
valor_final = juros_compostos_anual(valor_inicial=valor_inicial, taxa_juros_anual=taxa_juros_anual, anos=anos)

valor_inicial, taxa_juros_anual, anos = 1020.00, 0.03, 10
valor_final = juros_compostos_anual(valor_inicial=valor_inicial, taxa_juros_anual=taxa_juros_anual, anos=anos) 
<img src="Group2.png" alt="ebac-logo"> 
## 4\. Escopo
### **4.1. Definição** 
Define o ciclo de vida de uma variável.
 - Escopo de função.
def soma_lista(numeros: list) -> int:
  s = 0
  for numero in numeros:
    s = s + numero
  return s
soma = soma_lista(numeros=[2] * 20)
print(soma)
#print(s) # Quando a função terminou a variavel "S" ficou vazia
 - Escopo de estrutura condicional / repetição.
if True:
  x = 100
else:
  w = 50

print(x)
<img src="https://raw.githubusercontent.com/enzoschitini/Python-Notebook-Library/refs/heads/main/img/Programa%C3%A7%C3%A3o%20Funcional.png" alt="ebac-logo">

---

# **Módulo 05** | Python: Programação Funcional
Caderno de **Aula**<br> 
Desenvolvedor [Enzo Schitini](https://enzo-schitini.bubbleapps.io/version-test/)

---
# **Tópicos**

<ol type="1">
  <li>Função lambda;</li>
  <li>Função map;</li>
  <li>Função filter;</li>
  <li>Função reduce.</li>
</ol>
---
# **Aulas**
## 0\. Paradigmas de Programação
Estilos de programação.

1.   Imperativa;
2.   Funcional;
3.   Orientada a objetos.


O Python é uma linguagem [multi-paradigma](https://en.wikipedia.org/wiki/Python_(programming_language)).


![Screenshot from 2021-03-29 22-42-04.png](data:image/png;base64,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)
Este módulo é sobre **programação funcional**, que é o estilo que busca manipular dados com muitas e pequenas funções.
<img src="Group2.png" alt="ebac-logo"> 
## 1\. Função lambda
### **1.1. Definição** 
Função anônima (sem nome) com bloco de código super enxuto e que pode ser salva em uma variável. Em geral é utilizada com outros métodos funcionais como `map`, `filter`, e `reduce`.
```python
variavel = lambda params: expressão
```
**Exemplo**: Função `lambda` para extrair provedor de e-mail.
extrair_provedor_email = lambda email: email.split(sep='@')[-1]
email = 'andre.perez@gmail.com'
print(email)

provedor_email = extrair_provedor_email(email)
print(provedor_email)
**Exemplo**: Função `lamba` com estruturas condicionais.
numero_e_par = lambda numero: True if numero % 2 == 0 else False
numeros = range(0, 10)
for numero in numeros:
  if numero_e_par(numero) == True:
    print(f'O número {numero} é par!')
### **1.2. Função de alta ordem** 
São funções que recebem outras funções para parâmetro ou retornam outra função.
**Exemplo**: Juros compostos dinâmico.
 - Definição.
def retorno(juros: float):
  return lambda investimento: investimento * (1 + juros)
 - Instanciação.
retorno_5_porcento = retorno(juros=0.05)
retorno_10_porcento = retorno(juros=0.10)
valor_final = retorno_5_porcento(investimento=1000)
print(valor_final)

valor_final = retorno_10_porcento(investimento=1000)
print(valor_final)
 - Uso.
anos = 10
valor_inicial = 1000
valor_final = valor_inicial

for ano in range(1, anos+1):
  valor_final = retorno_5_porcento(investimento=valor_final)

valor_final = round(valor_final, 2)
print(valor_final)
anos = 10
valor_inicial = 1000
valor_final = valor_inicial

for ano in range(1, anos+1):
  valor_final = retorno_10_porcento(investimento=valor_final)

valor_final = round(valor_final, 2)
print(valor_final)
<img src="Group2.png" alt="ebac-logo"> 
## 2\. Função map
### **2.1. Definição** 
Aplica uma função em todos os elementos de uma coleção (`list`, `dict`, etc.) e retorna **todos** os elementos transformados.
```python
variavel = map(função, coleção)
```
numeros = [1, 2, 3]

numeros_ao_cubo = map(lambda num: num ** 3, numeros)

print(list(numeros_ao_cubo))
### **2.2. Função de alta ordem** 
**Exemplo**: Função `lambda` para extrair provedor de e-mail (1 parâmetro).
emails = ['andre.perez@gmail.com', 'andre.perez@live.com', 'andre.perez@yahoo.com']
extrair_provedor_email = lambda email: email.split(sep='@')[-1]
provedores = []
for email in emails:
  provedor = extrair_provedor_email(email)
  provedores.append(provedor)

print(provedores)
provedores = map(extrair_provedor_email, emails)
print(provedores)
provedores = list(map(extrair_provedor_email, emails))
print(provedores)
provedores = map(lambda email: email.split(sep='@')[-1], emails)
...
print(list(provedores))
- **Exemplo**: Investimento (Mais de 1 parâmetros).
anos = [10, 10, 10]
taxas_juros = [0.05, 0.10, 0.15]
valores_iniciais = [1000, 1000, 1000]

def retorno(valor_inicial: float, taxa_juros: float, anos: int) -> float:
  valor_final = valor_inicial
  for ano in range(1,anos+1):
    valor_final = valor_final * (1+taxa_juros)
  return round(valor_final, 2)

cenarios = list(map(retorno, valores_iniciais, taxas_juros, anos))
print(cenarios)
<img src="Group2.png" alt="ebac-logo"> 
## 3\. Função filter
### **3.1. Definição** 
Aplica uma função lógica (que retorna um booleano) em todos os elementos de uma coleção (`list`, `dict`, etc.) e retorna **apenas** aqueles que resultaram em verdadeiro (`True`).
```python
variavel = filter(função, coleção)
```
numeros = [1, 2, 3]

numeros_par = filter(lambda num: num % 2 == 0, numeros)

print(list(numeros_par))
### **3.2. Função de alta ordem** 
**Exemplo**: Função `lambda` para extrair provedor de e-mail.
emails = ['andre.perez@gmail.com', 'andre.perez@live.com', 'andre.perez@yahoo.com']
provedor_da_google = lambda email: 'gmail' in email
emails_google = []
for email in emails:
  if provedor_da_google(email) == True:
    emails_google.append(email)

print(emails_google)
emails_google = filter(provedor_da_google, emails)
print(emails_google)
emails_google = list(filter(provedor_da_google, emails))
print(emails_google)
emails_google = filter(lambda email: 'gmail' in email, emails)
...
print(list(emails_google))
<img src="Group2.png" alt="ebac-logo"> 
## 4\. Função reduce
### **4.1. Definição** 
Aplica uma função a todos os elemento de uma coleção, dois a dois, e retorna **apenas** um elemento.
```python
variavel = reduce(função, coleção)
```
numeros = [1, 2, 3]
from functools import reduce

soma = reduce(lambda x, y: x + y, numeros)
print(soma)
### **4.2. Função de alta ordem** 
**Exemplo**: Encontrar maior número em uma lista.
def maior_entre(primeiro: int, segundo: int) -> int:
  return primeiro if primeiro >= segundo else segundo

primeiro = 11
segundo = 11

print(maior_entre(primeiro=primeiro, segundo=segundo))
from random import random

print(random())
from random import random

numeros = [round(100 * random()) for _ in range(0, 100)]
print(numeros)
from random import random

def soma(v1:int) -> int:
    return v1 + 5

numeros = [(soma(3)) for _ in range(0, 100)]
print(numeros)
maior_numero = reduce(maior_entre, numeros)
print(maior_numero)
maior_numero = reduce(lambda primeiro, segundo: primeiro if primeiro >= segundo else segundo, numeros)
print(maior_numero)
### **4.3. Compossibilidade** 
**Exemplo**: Combinação de métodos funcionais.
from random import random

numeros = [round(100 * random()) for _ in range(0, 100)]
print(numeros)
 - Eleve os números ao quadrado.
numeros_ao_quadrado = map(lambda numero: numero ** 2, numeros)
 - Filtra os números ímpares.
numeros_impares = filter(lambda numero: numero % 2 != 0, numeros_ao_quadrado)
 - Soma todos os números.
soma_numeros = reduce(lambda x, y: x + y, numeros_impares)
print(soma_numeros)
 - Todos os métodos de uma vez.
soma_numeros = reduce(lambda x, y: x + y, filter(lambda numero: numero % 2 != 0, map(lambda numero: numero ** 2, numeros)))
print(soma_numeros)
### PROGRAMAS
print("Ok")
def ok():
    print("Nome")

o = [ok() for _ in range(0, 5)]
<img src="https://raw.githubusercontent.com/enzoschitini/Python-Notebook-Library/refs/heads/main/img/Programa%C3%A7%C3%A3o%20Orientada%20a%20Objetos.png" alt="ebac-logo">

---

# **Módulo 06** | Python: Programação Orientada a Objetos
Caderno de **Aula**<br> 
Desenvolvedor [Enzo Schitini](https://enzo-schitini.bubbleapps.io/version-test/)

---
# **Tópicos**

<ol type="1">
  <li>Um pouco de teoria;</li>
  <li>Classes;</li>
  <li>Objetos;</li>
  <li>Herança.</li>
</ol>
---
# **Aulas**
## 0\. Paradigmas de Programação
Estilos de programação.

1.   Imperativa;
2.   Funcional;
3.   Orientada a objetos.


O Python é uma linguagem [multi-paradigma](https://en.wikipedia.org/wiki/Python_(programming_language)).


![Screenshot from 2021-03-29 22-42-04.png](data:image/png;base64,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)
## 1\. Um pouco de teoria
### **1.1. Classe** 
Uma representação de um elemento, real ou não. Uma receita para criar objetos (instâncias). 
<br>
**Exemplo**: pessoa.
### **1.2. Objeto** 
Uma instancia de uma classe. Dá vida a receita (classe). 
<br>
**Exemplo**: André é um instância da classe pessoa.
### **1.3. Herança** 
Uma especialização da classe. 
<br>
**Exemplo**: estudante é um tipo especial de pessoa.


## 2\. Classes
### **2.1. Definição** 
Uma classe é uma receita para criação de objetos.
```python
class NomeClasse(object):

  def __init__(self, params):
    self.atributo1 = ...
    self.atributo2 = ...

  def metodo1(self, params):
    ...

  def metodo2(self, params):
    ...
```
class Pessoa(object):

  def __init__(self):
    pass
### **2.2. Atributos** 
Representam as caracteristicas da classe.
class Pessoa(object):

  def __init__(self, nome: str, idade: int, documento: str):
    self.nome = nome
    self.idade = idade
    self.documento = documento
### **2.3. Métodos** 
Representam as ações da classe.
from time import sleep

class Pessoa(object):
  
  def __init__(self, nome: str, idade: int, documento: str = None):
    self.nome = nome
    self.idade = idade
    self.documento = documento

  def dormir(self, horas: int) -> None:
    for hora in range(1,horas+1):
      print(f'Dormindo por {hora} horas')
      sleep(1)

  def falar(self, texto: str) -> None:
    print(texto)

  def __str__(self) -> str:
    return f'{self.nome}, {self.idade} anos e documento numero {self.documento}'
## 3\. Objetos
### **3.1. Definição** 
Uma objeto é uma instância de uma classe.
```python
class NomeClasse(object):
  ...

objeto = NomeClasse()

objeto.atributo
objeto.metodo()
```
andre = Pessoa(nome='Andre Perez', idade=30, documento='123')
maria = Pessoa(nome='Maria Perez', idade=56, documento='456')
pedro = Pessoa(nome='Pedro Perez', idade=8)
### **3.2. Manipulação** 
 - Atributos
print(andre.nome)
def maior_de_idade(idade: int) -> bool:
  return idade >= 18

if maior_de_idade(idade=andre.idade):
  print(f'{andre.nome} é maior de idade')
score_credito = {'123': 750, '456': 812, '789': 327}

score = score_credito[andre.documento]
print(score)
 - Métodos
andre.dormir(horas=8)
andre.falar(texto='Olá pessoal!')
print(andre)
type(andre)
### **3.3. Exemplos** 
 - Tudo no Python é um objeto!
tipos = [type(10), type(1.1), type('EBAC'), type(True), type(None), type([1, 2, 3]), type({1, 2, 3}), type({'janeiro': 1}), type(lambda x: x)]
for tipo in tipos:
  print(tipo)
nome = 'Andre Perez'
print(nome.upper())
juros = [0.02, 0.07, 0.15]
print(juros.pop(1))
 - Classe Arquivo CSV
class ArquivoCSV(object):

  def __init__(self, arquivo: str):
    self.arquivo = arquivo
    self.conteudo = self._extrair_conteudo()
    self.colunas = self._extrair_nome_colunas()

  def _extrair_conteudo(self):
    conteudo = None
    with open(file=self.arquivo, mode='r', encoding='utf8') as arquivo:
      conteudo = arquivo.readlines()
    return conteudo

  def _extrair_nome_colunas(self):
    return self.conteudo[0].strip().split(sep=',')

  def extrair_coluna(self, indice_coluna: str):
    coluna = list()
    for linha in self.conteudo:
      conteudo_linha = linha.strip().split(sep=',')
      coluna.append(conteudo_linha[indice_coluna])
    coluna.pop(0)
    return coluna
#### Função `strip() com split()`
# Exemplo 1: Removendo espaços em branco
fruta = " banana "
print(fruta.strip())  # Saída: "banana"

# Exemplo 2: Removendo caracteres específicos
fruta = ",,,,,rrttgg.....banana....rrr"
print(fruta.strip(",.grt"))  # Saída: "banana"

# Exemplo: Removendo espaços em branco e dividindo uma string
frase = " O gato pulou sobre o muro "
palavras = frase.strip().split()
print(palavras)  # Saída: ['O', 'gato', 'pulou', 'sobre', 'o', 'muro']
%%writefile banco.csv
age,job,marital,education,default,balance,housing,loan
30,unemployed,married,primary,no,1787,no,no
33,services,married,secondary,no,4789,yes,yes
35,management,single,tertiary,no,1350,yes,no
30,management,married,tertiary,no,1476,yes,yes
59,blue-collar,married,secondary,no,0,yes,no
35,management,single,tertiary,no,747,no,no
36,self-employed,married,tertiary,no,307,yes,no
39,technician,married,secondary,no,147,yes,no
41,entrepreneur,married,tertiary,no,221,yes,no
43,services,married,primary,no,-88,yes,yes
arquivo_banco = ArquivoCSV(arquivo='./banco.csv')
cont = arquivo_banco._extrair_conteudo()
print(cont)
print(arquivo_banco.colunas)
 - Extraindo a coluna de `job`


job = arquivo_banco.extrair_coluna(indice_coluna=1)
print(job)
 - Extraindo a coluna de `education`


education = arquivo_banco.extrair_coluna(indice_coluna=3)
print(education)
## 4\. Herança
### **4.1. Definição** 
Todo estudante é uma pessoa mas nem toda pessoa é um estudante. Por isso usamos as `Heranças` para que os estudandes possam compartilhar as caracteristicas das pessoas.
Uma especialização da classe.
```python
class NomeClasse(object):

  def __init__(self, params):
    ...

class NomeClasseEspecializada(NomeClasse):

  def __init__(self, params):
    super().__init__(self, params)
    self.atributo3 = ...
    self.atributo4 = ...

  def metodo3(self, params):
    ...

  def metodo4(self, params):
    ...
```
Repetindo a definição da classe `Pessoa`:
from time import sleep

class Pessoa(object):

  def __init__(self, nome: str, idade: int, documento: str=None):
    self.nome = nome
    self.idade = idade
    self.documento = documento

  def dormir(self, horas: int) -> None:
    for hora in range(1,horas+1):
      print(f'Dormindo por {hora} horas')
      sleep(1)

  def falar(self, texto: str) -> None:
    print(texto)

  def __str__(self) -> str:
    return f'{self.nome}, {self.idade} anos e documento numero {self.documento}'
Criando a classe `Universidade`
class Universidade(object):

  def __init__(self, nome: str):
    self.nome = nome
Especializando a classe `Pessoa` na classe `Estudante`:
class Estudante(Pessoa):

  def __init__(self, nome: str, idade: int, documento: str, universidade: Universidade):

    super().__init__(nome=nome, idade=idade, documento=documento)
    self.universidade = universidade
### **4.2. Manipulação** 
usp = Universidade(nome='Universidade de São Paulo')
andre = Estudante(nome='Andre Perez', idade=30, documento='123', universidade=usp)
print(andre)
print(andre.universidade.nome)
<img src="https://raw.githubusercontent.com/enzoschitini/Python-Notebook-Library/refs/heads/main/img/M%C3%B3dulos%20%26%20Pacotes.png" alt="ebac-logo">

---

# **Módulo 07** | Python: Módulos & Pacotes
Caderno de **Aula**<br> 
Desenvolvedor [Enzo Schitini](https://enzo-schitini.bubbleapps.io/version-test/)

---
# **Tópicos**

<ol type="1">
  <li>from / import / as;</li>
  <li>Módulo;</li>
  <li>Pacote;</li>
  <li>Baixando pacotes.</li>
</ol>
---
# **Aulas**
## 1\. from / import / as
Os módulos nativos do Python podem ser encontrados neste [link](https://docs.python.org/3/py-modindex.html).
### **1.1. import** 
**Exemplo:** `random`
import random
escolha = random.choice([1, 2, 3])
print(escolha)
numero_aleatorio = random.random() # entre [0,1)
print(numero_aleatorio)
**Exemplo:** `math`
import math
potencia = math.pow(10, 10)
print(potencia)
num = math.ceil(10.1)
print(num)
print(math.pi)
### **1.2. from, import** 
**Exemplo:** `time`
from time import time
print(time())
sleep(5)
from time import time, sleep

sleep(5)
### **1.3. from, import, as** 
**Exemplo:** `datetime`
from datetime import datetime as dt
print(dt.now())
print(dt.now().day)
print(dt.now().year)
## 2\. Módulos
### **2.1. Motivação** 
 - Classe Arquivo CSV
class ArquivoCSV(object):

  def __init__(self, arquivo: str):
    self.arquivo = arquivo
    self.conteudo = self._extrair_conteudo()
    self.colunas = self._extrair_nome_colunas()

  def _extrair_conteudo(self):
    conteudo = None
    with open(file=self.arquivo, mode='r', encoding='utf8') as arquivo:
      conteudo = arquivo.readlines()
    return conteudo

  def _extrair_nome_colunas(self):
    return self.conteudo[0].strip().split(sep=',')

  def extrair_coluna(self, indice_coluna: str):
    coluna = list()
    for linha in self.conteudo:
      conteudo_linha = linha.strip().split(sep=',')
      coluna.append(conteudo_linha[indice_coluna])
    coluna.pop(0)
    return coluna
 - Arquivo banco.csv
%%writefile banco.csv
age,job,marital,education,default,balance,housing,loan
30,unemployed,married,primary,no,1787,no,no
33,services,married,secondary,no,4789,yes,yes
35,management,single,tertiary,no,1350,yes,no
30,management,married,tertiary,no,1476,yes,yes
59,blue-collar,married,secondary,no,0,yes,no
35,management,single,tertiary,no,747,no,no
36,self-employed,married,tertiary,no,307,yes,no
39,technician,married,secondary,no,147,yes,no
41,entrepreneur,married,tertiary,no,221,yes,no
43,services,married,primary,no,-88,yes,yes
arquivo_banco = ArquivoCSV(arquivo='./banco.csv')
 - Extraindo a coluna de `education`


education = arquivo_banco.extrair_coluna(indice_coluna=3)
print(education)
### **2.2. Definição** 
Vamos criar um módulo (arquivo) com o nome `arquivo_csv.py` com o código da classe `ArquivoCSV`.
### **2.3. Revisitando a motivação** 
Vamos importar a classe `ArquivoCSV` do módulo (arquivo) `arquivo_csv.py`.
%%writefile arquivo_csv.py

class ArquivoCSV(object):

    def __init__(self, arquivo: str):
        self.arquivo = arquivo
        self.conteudo = self._extrair_conteudo()
        self.colunas = self._extrair_nome_colunas()

    def _extrair_conteudo(self):
        with open(file=self.arquivo, mode='r', encoding='utf8') as arquivo:
            return arquivo.readlines()

    def _extrair_nome_colunas(self):
        return self.conteudo[0].strip().split(sep=',')

    def extrair_coluna(self, indice_coluna: int):
        coluna = []
        for linha in self.conteudo[1:]:
            conteudo_linha = linha.strip().split(sep=',')
            coluna.append(conteudo_linha[indice_coluna])
        return coluna

    def soma(self, num):
        return num + 1
from arquivo_csv import ArquivoCSV

arquivo_banco_modulo = ArquivoCSV(arquivo='./banco.csv')
education = arquivo_banco_modulo.extrair_coluna(indice_coluna=3)
print(education)
soma = arquivo_banco_modulo.soma(num=2)
## 3\. Pacotes
### **3.1. Motivação** 
 - Classe Arquivo Texto
class ArquivoTXT(object):

  def __init__(self, arquivo: str):
    self.arquivo = arquivo
    self.conteudo = self._extrair_conteudo()

  def _extrair_conteudo(self):
    conteudo = None
    with open(file=self.arquivo, mode='r', encoding='utf8') as arquivo:
      conteudo = arquivo.readlines()
    return conteudo

  def extrair_linha(self, numero_linha: int):
    return self.conteudo[numero_linha-1]
 - Arquivo noticia.txt
%%writefile noticia.txt
Egito cobra quase US$ 1 bi para liberar navio que bloqueou Canal de Suez
Segundo autoridades, valor será utilizado para recompor as perdas provocados pelo encalhamento da embarcação de quase 400 metros
arquivo_noticia = ArquivoTXT(arquivo='./noticia.txt')
titulo = arquivo_noticia.extrair_linha(numero_linha=1)
print(titulo)
### **3.2. Definição** 
Vamos criar um módulo (arquivo) com o nome `arquivo_txt.py` com o código da classe `ArquivoTXT`.
Vamos criar um pacote (pasta) com o nome arquivo e mover os módulos (arquivos) `arquivo_csv.py` e `arquivo_txt.py` para ela.
### **3.3. Revisitando a motivação** 
from arquivo_csv import ArquivoCSV
#from arquivo_csv import ArquivoTXT
arquivo_banco_pacote = ArquivoCSV(arquivo='./banco.csv')
#arquivo_noticia_pacote = ArquivoTXT(arquivo='./noticia.txt')
education = arquivo_banco_modulo.extrair_coluna(indice_coluna=3)
print(education)
titulo = arquivo_noticia.extrair_linha(numero_linha=1)
print(titulo)
## 4\. Baixando pacotes
### **4.1. PyPI** 
Repositório oficial de pacotes Python ([link](https://pypi.org/)).
### **4.2. PIP** 
Ferramenta oficial para instalar pacotes Python armazenados no PyPI.
 - Instalando pacotes: `pip install <pacote>==<versão>`
#!pip install requests==2.25.1
 - Listando pacotes: `pip freeze`
#!pip freeze
 - Removendo pacotes: `pip uninstall <pacote>`
### **4.3. Requests** 
Pacote para interação com o protocolo web HTTP ([link](https://pypi.org/project/requests/)).
**Exemplo:** Extrair a taxa CDI do site da B3.
import requests
from requests.exceptions import ConnectionError, Timeout, RequestException

url = 'https://www2.cetip.com.br/ConsultarTaxaDi/ConsultarTaxaDICetip.aspx'

try:
    response = requests.get(url, timeout=10)
    response.raise_for_status()  # Check if the request was successful
    print(response.text)
except ConnectionError:
    print("Connection Error: Unable to connect to the server.")
except Timeout:
    print("Timeout Error: The request timed out.")
except RequestException as e:
    print(f"An error occurred: {e}")

#print(f'status code: {response.status_code}')
#print(response.text)
"""import json

data = json.loads(response.text)
print(data)"""
"""cdi = None

for key, value in data.items():
  if key == 'taxa':
    cdi = value.replace(',', '.')
    cdi = float(cdi)

print(cdi)"""
<img src="https://raw.githubusercontent.com/enzoschitini/Python-Notebook-Library/refs/heads/main/img/Tratamento%20de%20Erros.png" alt="ebac-logo">

---

# **Módulo 08** | Python: Tratamento de Erros
Caderno de **Aula**<br> 
Desenvolvedor [Enzo Schitini](https://enzo-schitini.bubbleapps.io/version-test/)

---
# **Tópicos**

<ol type="1">
  <li>Tipos de erros;</li>
  <li>Erros de sintaxe;</li>
  <li>Erros em tempo de execução.</li>
</ol>
---
# **Aulas**
## 1\. Tipos de erros
### **1.1. Definição** 
 - **Erros de sintaxe**: erros que ocorrem durante a escrita do código.
"""idade = 19

if idade > 18
  return True"""
 - **Erros em tempo de execução**: erros que ocorrem durante a execução do código.
Erros de uso incorreto de tipos de dados.
#print(1/0)
Erros de lógica.
i = 0
while True:
  ... # bloco de código
  i += 1
  if i > 10:
    break
## 2\. Erros de sintaxe
### **2.1. Definição** 
São erros que ocorrem durante a escrita do código. O trecho do código **não é** executado.
carrinho_compras = [{'id': 3184, 'preco': 37.65, 'qtd': 10}, {'id': 1203, 'preco': 81.20, 'qtd': 2}, {'id': 8921, 'preco': 15.90, 'qtd': 2}]
**Exemplo**: Esquecer o 'dois pontos' `:` no final de estruturas de condição, repetição, etc.
"""for produto in carrinho_compras
  ..."""
**Exemplo**: Condição lógica no `else` da estrutura de decisão `if-elif-else`.
"""for produto in carrinho_compras:
  if produto['id'] == 3184:
    ...
  else produto['id'] == 1203:
    ..."""
### **2.2. Manipulação** 
## 3\. Erros em tempo de execução
### **3.1. Motivação** 
Você trabalha como analista de dados em uma empresa de telecomunicações. Você precisa fazer uma análise para o time de vendas do quanto a empresa vai receber este mês. Diariamente você recebe do time de engenharia os dados.
%%writefile telecom.csv
customerID,PaymentMethod,MonthlyCharges,TotalCharges,Churn
7010-BRBUU,Credit card (automatic),24.1,1734.65,No
9688-YGXVR,Credit card (automatic),88.15,3973.2,No
9286-DOJGF,Bank transfer (automatic),74.95,2869.85,Yes
6994-KERXL,Electronic check,55.9,238.5,No
2181-UAESM,Electronic check,53.45,119.5,No
4312-GVYNH,Bank transfer (automatic),49.85,3370.2,No
2495-KZNFB,Electronic check,90.65,2989.6,No
4367-NHWMM,Mailed check,24.9,24.9,No
8898-KASCD,Mailed check,35.55,1309.15,No
from functools import reduce

def processar_faturas(nome_arquivo: str):

  faturas = []

  with open(file=nome_arquivo, mode='r', encoding='utf8') as arquivo:
    linha = arquivo.readline()
    linha = arquivo.readline()
    while linha:
      fatura = float(linha.strip().split(sep=',')[-3])
      faturas.append(fatura)
      linha = arquivo.readline()

  total_a_pagar = reduce(lambda x, y: x + y, faturas)
  total_a_pagar = round(total_a_pagar, 2)

  return total_a_pagar
total_a_pagar = processar_faturas(nome_arquivo='./telecom.csv')
print(total_a_pagar)
Em um certo dia, você recebe uma base de dados com a coluna de faturas trocada pela de meios de pagamento.
%%writefile telecom.csv
customerID,MonthlyCharges,PaymentMethod,TotalCharges,Churn
7010-BRBUU,24.1,Credit card (automatic),1734.65,No
9688-YGXVR,88.15,Credit card (automatic),3973.2,No
9286-DOJGF,74.95,Bank transfer (automatic),2869.85,Yes
6994-KERXL,55.9,Electronic check,238.5,No
2181-UAESM,53.45,Electronic check,119.5,No
4312-GVYNH,49.85,Bank transfer (automatic),3370.2,No
2495-KZNFB,90.65,Electronic check,2989.6,No
4367-NHWMM,24.9,Mailed check,24.9,No
8898-KASCD,35.55,Mailed check,1309.15,No
### **3.2. Definição** 
São erros que ocorrem durante a execução do código. O trecho do código **é** executado até o erro 'estourar'.
Erros por uso incorreto de tipos de dados. 'Estoura' exceção. Podem ser manipulados ou passados para frente (`raise`).
 - **Exemplo**: Erro de operações numéricas impossíveis
preco = 132.85
pessoas = 0
#valor_por_pessoa = preco / pessoas
 - **Exemplo**: Erro por combinações de tipos diferentes
nome = 'Andre Perez'
idade = True
#apresentacao = 'Fala pessoal, meu nome é ' + nome + ' e eu tenho ' + idade + ' anos'
 - **Exemplo**: Erro de indexação de estrutura de dados
anos = [2019, 2020, 2021]
"""ano_atual = anos[3]
print(ano_atual)"""
cursos = {
    'python': {
        'nome': 'Python para Análise de Dados', 'duracao': 2.5
    }, 
    'sql': {
        'nome': 'SQL para Análise de Dados', 'duracao': 2
    }
}
curso_atual = cursos['python']
print(curso_atual)
curso_atual = cursos['sql']
print(curso_atual)
"""curso_atual = cursos['analista']
print(curso_atual)"""
**Erros de lógica**. Não 'estoura' exceção. A melhor forma de analise é usar a função `print` para verificar resultados intermediários.
   * **Exemplo**: Loops infinitos.

controle = 0
while True:
  ...
  controle += 1
  if controle > 10:
    break
"""s = []
while True:
  s = s + (['CURSO DE PYTHON PARA ANALISE DE DADOS DA EBAC'] * (1000 * 1000 * 1000))"""
 - **Exemplo**: Limites de coleções.
carrinho_compras = [{'id': 3184, 'preco': 37.65, 'qtd': 10}, {'id': 1203, 'preco': 81.20, 'qtd': 2}, {'id': 8921, 'preco': 15.90, 'qtd': 2}]
valor_total = 0
for indice in range(1, len(carrinho_compras)):
  valor_total += carrinho_compras[indice]['preco'] * carrinho_compras[indice]['qtd']

valor_total = round(valor_total, 2)
print(valor_total)
valor_total = 0
for produto in carrinho_compras:
  valor_total += produto['preco'] * produto['qtd']

valor_total = round(valor_total, 2)
print(valor_total)
valor_total = 0
for indice in range(1, len(carrinho_compras)):
  print(carrinho_compras[indice])
  valor_total += carrinho_compras[indice]['preco'] * carrinho_compras[indice]['qtd']

valor_total = round(valor_total, 2)
print(valor_total)
### **3.3. Manipulação** 
 - Manipular o erro com a estrutura `try-catch-finally-else`.
anos = [2019, 2020, 2021]
anos = {2019, 2020, 2021}

try:
  ano_atual = anos[3]
  print(ano_atual)
except IndexError:
  print('Lista de anos é menor que o valor escolhido. Espera-se um valor entre 0 e ' + str(len(anos) - 1))
except Exception as exc:
  print(exc)
 - Passar o erro para frente com a estrutura `raise`.
"""anos = [2019, 2020, 2021]
# anos = {2019, 2020, 2021}

try:
  ano_atual = anos[3]
  print(ano_atual)
except IndexError as exc:
  raise Exception('Lista de anos é menor que o valor escolhido. Espera-se um valor entre 0 e ' + str(len(anos) - 1))
except Exception as exc:
  raise exc"""
### **3.4. Revisitando a motivação** 
faturas = []

with open(file='./telecom.csv', mode='r', encoding='utf8') as arquivo:
  linha = arquivo.readline()
  linha = arquivo.readline()
  while linha:
    try:
      fatura = float(linha.strip().split(sep=',')[-3])
    except ValueError:
      print('Falha ao processar as faturas! Abortando o processamento.')
      break
    else:
      faturas.append(fatura)
    linha = arquivo.readline()

print(faturas)
from functools import reduce

def processar_faturas(nome_arquivo: str):

  faturas = []

  with open(file=nome_arquivo, mode='r', encoding='utf8') as arquivo:
    linha = arquivo.readline()
    linha = arquivo.readline()
    while linha:
      try:
        fatura = float(linha.strip().split(sep=',')[-3])
      except ValueError as exc:
        raise ValueError(f'Falha ao processar as faturas devido ao seguinte erro: "{exc}"')
      else:
        faturas.append(fatura)
      linha = arquivo.readline()

  total_a_pagar = reduce(lambda x, y: x + y, faturas)
  total_a_pagar = round(total_a_pagar, 2)

  return total_a_pagar
try:
  total_a_pagar = processar_faturas(nome_arquivo='./telecom.csv')
except Exception as exc:
  print(exc)
else:
  print(total_a_pagar)
<img src="https://raw.githubusercontent.com/enzoschitini/Python-Notebook-Library/refs/heads/main/img/Scripting.png" alt="ebac-logo">

---

# **Módulo 09** | Python: Scripting
Caderno de **Aula**<br> 
Desenvolvedor [Enzo Schitini](https://enzo-schitini.bubbleapps.io/version-test/)

---
# **Tópicos**

<ol type="1">
  <li>Instalando o Python na própria máquina;</li>
  <li>Executando código Python no terminal;</li>
  <li>Criando arquivos de script Python.</li>
</ol>
---
# **Aulas**
## 1\. Instalando o Python na própria máquina
### **1.1. Google Colab** 
Python e o PIP já vem instalado na máquina virtual provisionada.
**Exemplo:** Conferir a versão do Python via Python.
import platform
print(platform.python_version())
print(platform.system())
**Exemplo:** Conferir a versão do Python via Bash (linguagem nativa do Linux).
!python -V
**Exemplo:** Conferir a versão do PIP via Bash (linguagem nativa do Linux).
!pip -V
### **1.2. Máquina Local** 
Verifique se você já tem o Python e o PIP instalado na sua máquina. Para verificar a instalação, abrir o terminal (windows `cmd` ou linux/macos `terminal`) e executar o seguinte comando.
```shell
python -V
pip -V
```
Se não o tiver instalado, acessar o site oficial do Python ([link](https://www.python.org/)) e instalar o software para o seu sistema operacional. Um excelente tutorial se encontra neste [link](https://realpython.com/installing-python/). Para verificar a instalação, abrir o terminal (windows `cmd` ou linux/mcos `terminal`) e executar o seguinte comando.
```shell
python -V
pip -V
```
## 2\. Executando código Python no terminal
### **2.1. Google Colab** 
O software do Python já vem "aberto" para ser utilizado.
from datetime import datetime

print(datetime.now().year)
### **2.2. Máquina Local** 


1.   Criar uma pasta (sugestão);
2.   Abrir o terminal nesta pasta (windows `shift + right click` ou linux/macos `right click`);
3.   Executar o seguinte comando:

```shell
python
```

Para 'sair' do Python, basta fechar o terminal ou digitar o seguinte código:

```shell
quit()
```
## 3\. Criando arquivos de script Python
### **3.1. Google Colab** 
1. Criar um arquivo de *script* com a extensão `py` seguindo as boas práticas do PEP 8 ([link](https://www.python.org/dev/peps/pep-0008/));
2. Executar com o seguinte comando:

```shell
!python arquivo.py
```
**Exemplo:** *Script* para extrair a taxa CDI do site da B3.
"""import os
import json
from datetime import datetime

import requests

URL = 'https://www2.cetip.com.br/ConsultarTaxaDi/ConsultarTaxaDICetip.aspx'

# Criando a variável data e hora 

data_e_hora = datetime.now()
data = datetime.strftime(data_e_hora, '%Y/%m/%d')
hora = datetime.strftime(data_e_hora, '%H:%M:%S')

# Captando a taxa CDI do site da B3

try:
  response = requests.get(URL)
  response.raise_for_status()
except requests.HTTPError as exc:
  print("Dado não encontrado, continuando.")
  cdi = None
except Exception as exc:
  print("Erro, parando a execução.")
  raise exc
else:
  dado = json.loads(response.text)
  cdi = float(dado['taxa'].replace(',', '.'))

# Verificando se o arquivo "taxa-cdi.csv" existe

if os.path.exists('./taxa-cdi.csv') == False:

  with open(file='./taxa-cdi.csv', mode='w', encoding='utf8') as fp:
    fp.write('data,hora,taxa\n')

# Salvando dados no arquivo "taxa-cdi.csv"

with open(file='./taxa-cdi.csv', mode='a', encoding='utf8') as fp:
  fp.write(f'{data},{hora},{cdi}\n')

print("Sucesso")"""
Vamos criar o arquivo de *script* `extrair-cdi.py`.
#!python extrair-cdi.py
**Exemplo:** Script com argumentos.
from sys import argv

print(argv)
print(type(argv))
Vamos criar o arquivo de *script* `args.py`.
#!python args.py
**Exemplo:** *Script* para gerar um grafico da taxa CDI do site da B3.
"""import csv
from sys import argv

import seaborn as sns

# Extraindo as colunas hora e taxa

horas = []
taxas = []

with open(file='./taxa-cdi.csv', mode='r', encoding='utf8') as fp:
  linha = fp.readline()
  linha = fp.readline()
  while linha:
    linha_separada = linha.split(sep=',')
    hora = linha_separada[1]
    horas.append(hora)
    taxa = float(linha_separada[2])
    taxas.append(taxa)
    linha = fp.readline()

# Salvando no grafico

grafico = sns.lineplot(x=horas, y=taxas)
grafico.get_figure().savefig(f"{argv[1]}.png")"""
Vamos criar o arquivo de *script* `cdi-grafico.py`.
#!python cdi-grafico.py 'dia-10'
### **3.2. Máquina Local** 
Mesma dinâmica!
### **3.3. Ferramenta de Desenvolvimento Local** 
As IDEs (Integrated Development Environment) são ferramentas completas de desenvolvimento de código em software.

*   **PyCharm** da JetBrains ([link](https://www.jetbrains.com/));
*   **Visual Studio Code** da Microsoft ([link](https://code.visualstudio.com/)).

##

<p align="center">
  Enzo Schitini
</p>

<p align="center">
  Data Scientist & Data Analyst • SQL • Expert Bubble.io • UX & UI @ Scituffy creator
</p>