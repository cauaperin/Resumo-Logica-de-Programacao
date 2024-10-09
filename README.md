# 👨‍💻| Lógica de Programação 
Lógica de programação é a base sobre a qual se constrói qualquer linguagem de programação. Ela é essencial porque ensina como decompor problemas complexos em partes menores, identificar padrões e aplicar soluções de maneira eficaz. Sem uma boa compreensão da lógica de programação, aprender uma nova linguagem de programação seria como tentar cozinhar um prato gourmet sem saber como usar os ingredientes básicos. Lógica de programação promove pensamento crítico e habilidades de resolução de problemas, que são aplicáveis não apenas na programação, mas em quase todas as áreas da vida

## 🧠| Algoritmos
É um passo a passo lógico, no qual você executa uma sequência de comandos ou instruções para resolver um problema
Exemplo: Acordar, levantar da cama, ir até a cozinha, pegar uma tigela, por o cereal na tigela, colocar o leite sobre o cereal, sentar na cadeira e comer.
Percebe-se como é importante a ordem aqui? Se por acaso nós trocássemos de lugar algumas palavras e agrupasse elas como: ir até a cozinha, levantar da cama e colocar o leite sobre o cereal. Não faria sentido nenhum.

## 📊| Fluxograma
É uma representação visual para colocar em prática um pensamento lógico, eles são ótimos para simplificar e visualizar procedimentos complexos, permitindo identificar gargalos ou melhorias.

exemplo utilizado no site [tldraw](https://www.tldraw.com/)

(https://i.imgur.com/BoEW7u9.png)

## 📦| Variáveis
Variáveis são utilizadas para armazenar valores que podem mudar ao longo da execução de um programa. Pense nelas como caixas que podem guardar diferentes tipos de informações.

### Exemplos de variáveis

| Variável         | Descrição                                                 | Exemplo                      |
|------------------|-----------------------------------------------------------|------------------------------|
| **Inteiro**      | Números inteiros sem ponto decimal                        | `int idade = 25;`            |
| **Flutuante**    | Números com casa decimal                                  | `float altura = 1.75;`       |
| **Caractere**    | Representa um único caractere                             | `char inicial = 'A';`        |
| **String**       | Sequência de caracteres (texto)                           | `string nome = "João";`      |
| **Booleano**     | Valores verdadeiros ou falsos                             | `bool ativo = true;`         |

**(Tenha em mente que os exemplos dados são apenas ilustrações, e a forma como uma variável é declarada depende de qual linguagem de programação você está utilizando)** <br>

**(Lembrando também que nessa tabela estão representadas só algumas das variáveis que mais são utilizadas no dia a dia, existem outros tipos, na documentação de cada linguagem você pode econtrar essas informações)**

Documentações:
- **Python**: [Documentação](https://www.python.org/doc/)

- **Java**: [Documentação](https://docs.oracle.com/en/java/)

- **C#**: [Documentação](https://learn.microsoft.com/en-us/dotnet/csharp/)

- **C++**: [Documentação](https://cplusplus.com/doc/tutorial/)

- **Kotlin**: [Documentaçã](https://kotlinlang.org/docs/home.html)

- **Ruby**: [Documentação](https://www.ruby-lang.org/en/documentation/)

- **Lua**: [Documentação](https://www.lua.org/docs.html)


### Constantes
O que você precisa saber de constantes, é que elas também funcionam como variáveis, porém diferente delas, uma constante possui um valor imutável após sua definição, ou seja, seu valor não pode ser alterado posteriormente no código.

## 🗄️| Vetores e Matrizes
Pense nos vetores como gavetas, onde ao invés de deixar suas coisas espalhadas pelo quarto, você as organiza e as guarda em um só lugar(nesse caso, uma gaveta). 
Matrizes nada mais são do que vários vetores juntos, como usamos o exemplo de gavetas para os vetores, pense nas matrizes como um armário que possuí várias gavetas.
Ambas são muito importante para facilitar a manipulação e acesso eficiente dos dados, melhorando a performance e a organização do código.

**Exemplo:**
No lugar de criarmos muitas variáveis para representar muitos alimentos, podemos fazer só uma matriz chamada `estoque_de_comida` e guardar todos esses valores juntos, segue abaixo um exemplo escrito em **Python** para entender um pouco melhor sobre como uma matriz funciona na prática:

```python
# Criando a matriz
estoque_de_comida = [
    ["balas", "macarrão", "arroz"],
    ["bolacha", "farinha", "tomate"],
    ["pão", "chocolate", "feijão"]
]

# Buscando a comida tomate na matriz
print(estoque_de_comida[1][2])
```
Caso você queira buscar onde está o tomate nessa matriz acessamos a segunda linha`[1]` e a terceira coluna`[2]` da matriz, onde o "tomate" está localizado. 🍅(Lembrando que começamos a contar a partir do 0)

Para ter uma melhor noção veja essa imagem:
(https://i.imgur.com/s33amtS.png)

## 🔁| Estruturas de Controle
As estruturas de controle (condicionais e loops) determinam o fluxo de execução do programa:

Condicionais (if/else): Permitem que o programa tome decisões.

Loops (for/while): Permitem que uma ação seja repetida várias vezes.

## 🏛️| Classes
Uma classe é um molde, um template que define a estrutura e o comportamento de objetos em programação orientada a objetos (OOP). Por exemplo, se você tivesse uma classe Carro, ela poderia ter atributos como cor, marca e ano, e métodos como acelerar e frear.

### Métodos
São funções definidas dentro de uma classe em orientação a objetos. Eles podem acessar e modificar os dados da própria classe, e geralmente operam sobre instâncias dessa classe.

### Propriedades
São atributos de uma classe que encapsulam variáveis, oferecendo uma forma controlada de acessar e modificar dados.

## 🔧| Funções
Funções são blocos de código que executam tarefas específicas e podem ser reutilizadas ao longo do programa. Elas ajudam a organizar e modularizar o código, tornando-o mais legível e fácil de manter.