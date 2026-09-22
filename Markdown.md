# Aula de Markdown
O Markdown é uma linguagem de marcação que simplifica a leitura de um código em relação ao HTML.

## Comandos básicos

Para criar títulos, usamos
# # para título de nível 1
## ## para título de nível 2
### ### para título de nível 3

### Negrito, itálico, tachado

Para colocar uma palavra ou frase em __negrito__ basta colocar 2 * ou 2 _ antes e depois.

Para colocar uma palavra ou frase em _itálico_ basta colocar 1 * ou 1 _ antes e depois.

Para colocar uma palavra ou frase ~~taxado~~ basta colocar 2 ~ antes e depois.

Também tem como misturar o estilo __~~*como esse*~~__.

### Listas Numeradas

Para criar uma lista numerada, basta iniciar com 1. que ele cria a lista. 
Para dar continuidade, pode ir colocando em ordem, 2., 3., etc ou digitar qualquer número que ele irá ordenar sempre corretamente.

1. Primeiro item com 1.
0. Segundo item com 0.
8. Terceiro item com 8.

Veja que, desde que inicie a lista com o número que deseja que inicie, ele dará continuidade a partir da numeração inicial.

Há também a lista de segundo nível, bastando dar 3 espaços:

1. Lista de primeiro nível começando com 1..
   1. Primeiro item da lista de segundo nível
   2. Segundo item da lista de segundo nível
2. Segundo item da lista de primeiro nível.
   1. Primeiro item 
   2. Segundo item

### Listas Demarcadas

Para uma lista demarcada, basta cada item iniciar com *

* Primeiro item
* Segundo item
* Terceiro item

Também temos as listas demarcadas de segundo nível, bastando dar 3 espaços e *

* Primeiro item nível 1
   * Primeiro item segundo nivel
   * Segundo item segundo nivel
* Segundo item nivel 1

### Lista de tarefas

Para uma lista de tarefas, iniciar com - [] e o item. Para marcar o item, basta fazer - [x].

- [ ] Item 1
- [ ] Item 2
- [x] Item marcado

### Linha

Para adicionar uma linha, basta dar 3 - no inicio da linha
---

 ### Comando e linha de códigos

 Para representar um comando basta colocar o comando emtre crases.

 __Exemplo:__ 
 `print()`
 `int(input())`

Já um código, só colocar 3 crases no início e 3 crases no final.

__Exemplo:__

```
from rich import print


class Funcionario:
    #Atributos de Classe
    empresa = "Virtual Telecom"
    def __init__(self, nome, setor, cargo):
        self.nome = nome
        self.setor = setor
        self.cargo = cargo


    def apresentar(self):
        return (f':handshake: Olá, me nome é [bright_blue]{self.nome}[/], sou [bright_green]{self.cargo}[/]'
                f' e do setor [yellow2]{self.setor}[/] na empresa {Funcionario.empresa}. :waving_hand:')
```

### Emojis

Para adicionar mogis, é bem fácil. Somente compiar o código unicode do emoji entre ::.

Um repositório muito bom do Github com códigos de emoji estão [aqui](https://github.com/ikatyang/emoji-cheat-sheet).

__Exemplos:__
:smiling_face_with_three_hearts:
:clap:
:raised_hands:

### Quote

Para criar um quote basta iniciar a frase com >

> Que horas são???