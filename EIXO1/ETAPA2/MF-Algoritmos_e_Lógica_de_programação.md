# MICROFUNDAMENTO: ALGORITMOS E LÓGICA DE PROGRAMAÇÃO

##  UNIDADE 1: LÓGICA DE PROGRAMAÇÃO E ESTRUTURA DE CONTROLE, FUNÇÕES E PROCIDMENTOS
Durante o Microfundamento de algoritmos e lógica de programação a linguagem utiliza nos exemplo será o C#, da Microsoft.

### TEMA 1: Introdução à programação
#### Conceito de Algoritmo
Objetivo dessa sessão é compreender conceito básico por trás da programação de computadores, o algoritmo.

#
> **Algoritmo** é a descrição de uam **sequência de passos** que deve ser seguida para **realização de uma tarefa**.

Para melhor definição de algoritmos para o meu computacional podemos dizer quê:
> **Algoritmo** é uma **sequência finita de instruções** ou operações cuja execução, em tempo finito, **resolve um problema computacional**

Estruturas básicas de um algoritmo

- Estrutura sequêncial;
- Estrutura condicional;
- Estrutura de repetição

Conteúdo adicionais
[Youtube - O que é Algoritmo](https://www.youtube.com/watch?v=iEVLDKOLgQk)

#### VARIÁVEIS
 Variáveis armazenam valores e dados em endereços de memória RAM. Estes dados armazenads em variáveis podem terem sido geradas pelo próprio programa ou inseridos pelo usuário.

 Tipos de dados:

 - Simples
    - Númericos
        - Inteiros: Valos númericos sem decimal (0, -2., 47, 58, 123220, -34235)
        - Reais/Ponto Fluente (double em C#): valores números negativos ou positivos com casas decimais (0.12, -45.17, 3.14159, 0.000001, 2)
    - Não numéricos
        - Lógico/Booleano: Possuí dois valores verdadeiro ou falso (True or False)
        - Caractere/String: Sequência de caracteres ("Av. Amazonas", )
- Estruturados
    - Arranjos
        - Vetores
        - Matrizes
    - Arquivos

**Identificadores de variáveis**

Ao invés de informar endereços de memória, utilizamos indicadores ou seja nomes. Tás nomes precisam ser únicos e dependando da liguanguem de programação, alguns nomes são válidos ou não.

Abaixos nomes característas válidas para declaração de variáveis em C#:

- Podem contes LETRAS, DÍGITOS, UNDERSCORE E caracteres UNICODE;
- Obrigatoriamente deve começar com LETRA ou UNDERSCORE;
- **Não podem conter** ESPAÇOS ou caracteres especiais (?, !, -);
- Não podem usar [palavras chaves da liguagem](https://learn.microsoft.com/pt-br/dotnet/csharp/language-reference/keywords/)
- C# faz diferenciação entre letras MAIÚSCULAS e minúsculas (idades é diferenter de Idade ou IDADE etc)

- **Nomes válidos**: i, j, FRUTA, salario, a12, i23ER21, nomealuno
- **Nomes inválidos**: 1, 25, nome-fruta, 5JOSE, A$1, nome aluno

Apesar de algumas combinações de letras e números sejam válidos, é importe utilizar nomes que façam sentido com o dado armezenado.

**Exemplo de algoritmo***

Variáveis com nomes inapropriados
```C#
static void Main(string[] args)
{
    int a, b, c;
    a = int.Parse(Console.ReadLine());
    b = 1;
    for (c = 2; c <= a; c++)
        b = b * c;
    Console.Write(b);
    Console.ReadKey();
}
```

Variáveis com nomes apropriados

```C#
static void Main(string[] args)
{
    // Programa para calcular o fatorial de um número
    int Numero, Fatorial, Contador;
    Console.Write("Informe um número: ");
    Numero = int.Parse(Console.ReadLine());
    Fatorial = 1;
    for (Contador = 2; Contador <= Numero; Contador++)
        Fatorial = Fatorial * Contador;
    Console.Write("Fatorial de "+Numero+" = "+ Fatorial);
    Console.ReadKey();
}
```
**Declaração de variáveis**

```C#
// Exemplo 1
static void Main(string[] args)
{
    int idade;
    int numero;
    double altura;
    double peso;
    double salario;
    string nomePai;
    string rua;
    string bairro;
    string dtNasc;
    bool temCasa;
}
// Exemplo 2
static void Main(string[] args)
{
    int idade, numero;
    double altura, peso, salario;
    string nomePai, rua, bairro, dtNasc;
    bool temCasa;
}
```

#### ESTRUTURA SEQUENCIAL - ETAPAS DE UM ALGORITMO E O OPERADOR DE ATRUIBUIÇÃO

Não basta apenas executar os comandos do programa, é necessário definar as etapas de forma sequencial de cima para baixo na ordem correta.

Etapas de um algoritmo

 1. Entrada de dados (informados pelo usuário)
 2. Processamento (cálculos)
 3. Saída de dados (exebição dos resultados)



/ Entrada de dados / ------->  / Processamento /   -------->  / Saída de dados/


**ATRIBUIÇAO DE VALORES EM VARIÁVEIS**


Valores em variáveis podem receber valores fixos, valores de outra variável, ou resultafdos de uma expressão aritmética ou booleana.

```C#
// Exemplo 1
using System;
 class MainClass {
    public static void Main (string[] args){
        int idade;
        double altura, peso, copiaPeso, IMC;
        string nome;
        bool temCNH;

        idade = 23;
        altura = 1.76;
        peso = 78.9;
        nome = "Jão da Silva";
        temCNH = true;
        copiaPeso = peso;
        IMC = peso / (altura * altura)
    }
 }
```


```C#
// Exemplo 2
using System;

class MainClass{
    public static void Main (string[] args) {
        int idade = 23;
        double altura = 1.76, peso = 78.9;
        string nome = "Jão da Silva";
        bool temCNHE = true;

        copiaPeso = peso;
        IMC = peso / (altura * altura)
    }
}
```

***SAÍDA DE DADOS**

Em C# para imprimir informações na tela como a função print() do python temos:

- Console.Write() _O cursor permanece na mesma linha_


- Console.WriteLine() _Cursor pula próxima linha, como se tivesse preechinado a tecla enter_

```Console.Write("Mensagem"); ```

```Console.Write(VAR);```

```Console.Write("Mesagem 1 " +VAR1+" Mensagem2 "+VAR2 );```

Exemplo de manupulação de saída de dados


```C#
using System;

class MainClass {
    public static avoid Main (string[] args) {
        int idade = 27;
        string nome = "João Silva";

        // Concatenação
        Console.WriteLine("Meu nome é "+nome+" e tenho "+idade+" anos de idade.");
        // PlaceHolder
        Console.WriteLine("Meu nome é {0} e tenho {1} anos de idade.", nome, idade);
        // Interpolação
        Console.WriteLine("Meu nome é {nome} e tenho {idade} anos de idade");

        Console.ReadKey();
    }
}
```

***ENTRADA DE DADOS**

O comando ``` VAR = Console.ReadLine()``` é utilizado para receber _input_ de dados do usuário. O dado digitado precisar ser coerente com o tipo da variável, ou seja, se a VAR for do tipo _**int**_ outro tipo de dado não será aceito.

- Lendo valores inteiros

```C#
variavel = int.Parse(Console.ReadLine());

variavel = Convert.ToInt32(ConsoleReadLine());
```

- Lendo texto

```C#
variavel = Console.ReadLine();
```

- Lendo valores booleanos

```C#
variavel = bool.Parse(Console.ReadLine());
```

Exemplo de entrada de dados

```C#
// Exemplo 1
using System;

class MainClass {
    public static void Main (string[] args) {
        int n1, n2; f
        double n3, n4;
        float n5;
        string s;
        bool b1, b2;
        // Leitura de Inteiros
        Console.Write("Digit um número inteiro: ");
        n1 = int.Parse(Console.ReadLine());
        n2 = Convert.ToInt32(Console.ReadLine());

        // Leitura de valores ponto-flutuante
        Console.Write("Digite um nuúmero real/flutuante: ");
        n3 = double.Parse(Console.ReadLine());
        Console.Write("Digite outro número real: ");
        n4 = Convert.ToDouble(Console.ReadLine());
        Console.Write("Digite mais um número real: ");
        n5 = float.Parse(Console.ReadLine());

        // Leitura de valor booleano
        Console.Write("Digite um booleano (Digite true ou false): ");
        b1 = bool.Parse(Console.ReadLine);
        Console.ReadKey();
    }
}
```

```C#
// Exemplo 2
using System;

class MainClass {
    public static void Main (string[] args) {
        int n1, n2, soma;
        double media;
        //Entrada de dados
        Console.Write("Digite um número; ");
        n1 = int.Parse(Console.ReadLine());
        Console.Write("Digite outro número: ");
        n2 - int.Parse(Console.ReadLine());
        // Processamento / Cálculo
        soma = n1 + n2;
        media = some / 2;
        // Saída de Dados
        Console.WriteLine("Soma = "+some);
        Console.WriteLine("Media = "+media);
        
    }
}