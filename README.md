# Compiladores: CBR

Trabalho para a disciplina de compiladores.

Acadêmico (Autor): [José A. Q. C. Gomes `@JoseComparotto`](https://github.com/JoseComparotto)

Professor: [Sidney Maldonado `@SidneyMaldonado`](https://github.com/SidneyMaldonado)

Universidade: Uniderp Matriz - Campo Grande, MS

Curso: Engenharia da Computação

Perído: 2023.1 - 3º Semestre

## Estrutura de Diretórios

```plain
📦 
├─ alfabeto.txt     // Alfabeto: caracteres existentes na linguagem 
├─ dicionario.txt   // Dicionário: palavras reservadas da linguagem
├─ ebnf.txt         // Gramática: Notação EBNF da linguagem
├─ exemplo.txt      // Código-fonte de exemplo em CBR
├─ exemplo.java     // Código-fonte de exemplo compilado para Java
├─ expressoes.txt   // Expressões da gramática em RegExps
└─ src
   ├─ AnalisadorLexico.java
   ├─ AnalisadorSemantico.java
   ├─ AnalisadorSintatico.java
   ├─ Compilador.java
   ├─ GeradorByteCode.java
   ├─ LerArquivo.java
   └─ main.java               // Classe principal Java
```

## Alfabeto

`abcdefghijklmnopqrsetuvwxyz0123456789-+.*/><=!(){}:; ,%"&`

## Dicionário

| Palavra   | Descrição |
|-----------|-----------|
| `ler`     | Comando de entrada
| `imprimir`| Comando de saída
| `para`    | Estrutura de repetição
| `de`      | Valor inicial para repetição
| `ate`     | Valor final pra repetição
| `faca`    | Iníio do escopo de repetição
| `fimpara` | Fim do escopo de repecição
| `se`      | Estrutura condicional
| `entao`   | Iníio do escopo condicional
| `senao`   | Escopo de exceção
| `fimse`   | Fim do escopo condicional
| `=`       | Operador de atribuíção
| `inteiro` | Tipo de variavel para números inteiros
| `texto`   | Tipo de variavel para cadeias de caracteres
| `real`    | Tipo de variavel para números reais
| `logico`  | Tipo de variavel para valores lógicos
| `e`       | Operador lógico 'e'
| `ou`      | Operador lógico 'ou' 
| `nao`     | Operador lógico de negação 
| `>`       | Operador 'maior que'
| `<`       | Operador 'menor que'
| `>=`      | Operador 'maior ou igual a'
| `<=`      | Operador 'menor ou igual a'
| `=`       | Operador 'igual a'
| `!`       | Operador 'diferente de'
| `;`       | Final de comando

## Exemplo

Código-fonte de exemplo da linguagem `CBR`:

<https://github.com/JoseComparotto/cbr/blob/ef0f5e1c9a9f9a722e0bfc4899024402b19be23b/exemplo.txt#L1-L23>

Código-fonte correspondente na linguagem `Java`:

<https://github.com/JoseComparotto/cbr/blob/ef0f5e1c9a9f9a722e0bfc4899024402b19be23b/exemplo.java#L1-L29>
