# fake-moulinnete
Testes que talvez funcionem corretamente para as listas da 42

Nessa aquivo criamos testes que tentam checar as mesmas coisas que a Moulinette checa. Atenção, isso foi feito por outros campers e não é um programa oficial.

Existem 2 tipos de teste. Um deles tem que ser compilado exercício por exercício, outro testa a lista inteira de uma vez (precisa que todas as funções estejam definidas, mesmo que não façam nada).

Para executar os testes da lista inteira compile da seguinte forma:
(para rodar o `all.c` você precisa ter todas as funções da lista criadas)

```bash
$ gcc -Wall -Wextra -Werror $(find -type f -name "*.c") all.c [flags adicionais]
```

Para testar um arquivo por vez, é assim:

```bash
$ gcc -Wall -Wextra -Werror [seu arquivo] [ex**.c] [flags adicionais]
```
