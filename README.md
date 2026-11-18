# Tabuada

## Sobre a solução

O programa foi desenvolvido em linguagem C e exibe a tabuada de um número informado pelo usuário, de 1 a 10.

### Como funciona

1. O programa pede que o usuário digite um número inteiro.
2. Um laço `for` repete 10 vezes, com o contador `i` indo de 1 até 10.
3. A cada repetição, o programa exibe a multiplicação do número por `i` e o resultado.

### Recursos utilizados

- Variável do tipo `int` para guardar o número digitado
- Estrutura de repetição `for` para percorrer os multiplicadores de 1 a 10
- `scanf()` para entrada de dados e `printf()` para exibir cada linha da tabuada

## Como compilar e executar

```bash
gcc tabuada.c -o tabuada
./tabuada
```

## Exemplo de execução

```
Digite um numero: 7
7 x 1 = 7
7 x 2 = 14
7 x 3 = 21
7 x 4 = 28
7 x 5 = 35
7 x 6 = 42
7 x 7 = 49
7 x 8 = 56
7 x 9 = 63
7 x 10 = 70
```
