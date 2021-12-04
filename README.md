# Markdown

## Aprendendo markdown

---




Estou aprendendo linguagem **Markdown** no _*Curso em Video*_ de **Git e GitHub**

## Colocando coisas em __Negrito__:

Para colocar algum conteúdo em negrito você pode usar duas formas: 

~~~
__Conteúdo Aqui__
**Conteúdo Aqui2**
~~~

### Ficará assim:
__Conteúdo Aqui__

**Conteúdo Aqui2**

---

## Colocando coisas em *Itálico*:

Para colocar algum conteúdo em itálico nós também temos duas formas:
~~~
*Conteúdo Aqui*
_Conteúdo Aqui2_
~~~

### Ficara assim:
*Conteúdo Aqui*

_Conteúdo Aqui2_

Da mesma forma que Negrito, os simbolos são * e _ Só que ao invés de usar dois ** e __ Você usa somente um * e _

---

## Riscar Palavra:
Para riscar uma palavra basta colocar seu conteúdo ~~ aqui ~~
~~~
~~Conteúdo~~
~~~

---

## Títulos 

~~~
# Título1
## Título2
### Título3
~~~

Quanto mais # tiver, menor é o tamanho da fonte.

### Ficará assim:
# Título1
## Título2
### Título#

---

## Colocando Traço

Para colocar uma linha grande como essa acima que divide os tópicos, temos duas formas de utilizá-la:
~~~
Primeira forma é três sinais de menos:  ---
Segunda forma é três asterisco: ***
~~~
### Ficará assim:
---


## Misturando Configurações:
Também podemos misturar configurações 
~~~
__*Conteúdo*__ escreve em negrito e no formato itálico
~~~

### Ficará assim:
__*Conteúdo*__ 

---

## Listas

### Listas numeradas:

Não importa  a numeração, contanto que eu siga o padrão de colocar um numero e ponto e em seguida dar um espaço e digitar o conteúdo. Assim:   **5.** espaço **CONTEÚDO** 
~~~
1. conteúdoA
034. conteúdoB
453. conteúdoC
4. conteúdoD
~~~

### Ficará assim:

1. conteúdoA
034. conteúdoB
453. conteúdoC
4. conteúdoD

Ele já converte o número para a ordem certa e de forma crescente.

---

## Subitem
~~~

1. Teste1
2. Teste2
3. Teste3
   1. Teste3.1
   2. Teste3.2
   3. Teste3.3
4. Teste4
5. Teste5
   1. Teste5.1
   2. Teste5.2
~~~

Para criar um subitem dentre de um item, você tem que dar 3 espaços para "indentar" o conteúdo e colocar **número e ponto junto**, dar um *espaço* e ai sim digitar seu subitem.

### Ficará assim:

1. Teste1
2. Teste2
3. Teste3
   1. Teste3.1
   2. Teste3.2
   3. Teste3.3
4. Teste4
5. Teste5
   1. Teste5.1
   2. Teste5.2

---
## Lista Demarcada:

~~~
* Teste1
* Teste2
* Teste3 
   * Teste3.1
   * Teste3.2
* Teste4
* Teste5
   * Teste5.1
   * Teste5.2
~~~

Você pode seguir o mesmo exemplo do subitem e dar três espaços para indentar seu conteúdp demarcado, basta usar o asterico ao invés de números.

### Ficará assim:

* Teste1
* Teste2
* Teste3 
   * Teste3.1
   * Teste3.2
* Teste4
* Teste5
   * Teste5.1
   * Teste5.2
   
--- 

## Lista de Tarefas

Para criar uma lista de tarefas basta você usar o sinal de menos - e dar um  espaço, abrir colchetes com um espaço dentro e dar mais um espaço, e só ai sim escrever seu conteúdo.

Para Marcar uma tarefa como concluída basta colcoar um x dentro dos colchetes 
~~~
- [x] Criar Página Pricipal
- [ ] Criar a Página da Loja
- [ ] Finalizar o Projeto
~~~

Exemplo:
- [x] Criar Página Pricipal
- [ ] Criar a Página da Loja
- [ ] Finalizar o Projeto

  

## Usando tabela:

Para montar uma tabela, basta seguir esse formato. Caso queira mais de três colunas é só seguir o mesmo exemplo e adicionar **|** para o nome na parte de cima e **|---**  para o conteúdo e criar suas coisas colocando dentro desse limite  __*conteudo*__.
~~~~
nome|nome|nome
---|---|---
1|conteudo1|conteudo1
2|conteudo2|conteudo2
3|conteudo3|conteudo3
~~~~

### **Ficará assim:**


nome|nome|nome
---|---|---
1|conteudo1|conteudo1
2|conteudo2|conteudo2
3|conteudo3|conteudo3

### Outro exemplo:
~~~

Numero| Nome | Nota
---|---|---
1|Gustavo|9
2|Pedro|7
3|Maria|7.5
4|Julio|8.5

~~~

Numero| Nome | Nota
---|---|---
1|Gustavo|9
2|Pedro|7
3|Maria|7.5
4|Julio|8.5

### Mais um exemplo:

~~~
Numero|Anime|Avaliação
---|---|---
1|Tokyo Ghoul|9.5
2|Hunter x Hunter|9
3|Dragon Ball (Super)|10
4|Shingeki no kyojin|9
~~~

Numero|Anime|Avaliação
---|---|---
1|Tokyo Ghoul|9.5
2|Hunter x Hunter|9
3|Dragon Ball (Super)|10
4|Shingeki no kyojin|9

---
## Colocar Comando de Códigos

Para colocar algum comando formatado, use duas crases e coloque seu conteúdo dentro.
~~~
`document.getElementById()`
~~~

### Ficará assim:

`document.getElementById()`

#### Também podemos colocar um trecho de código, basta usar três crases ao invés de uma ao abrir e fechar seu conteúdo.
~~~
```
num = int(input('Qual seu numero?'))
if num % 2 == 0 
    print(f'O número ${num} é PAR
else:
    print(f'O número ${num} é ÍMPAR
```
~~~


### Ficará assim:


```
num = int(input('Qual seu numero?'))
if num % 2 == 0 
    print(f'O número ${num} é PAR
else:
    print(f'O número ${num} é ÍMPAR
```


## Colocar Emoji 😄 
 Para colocar um emoji basta colocar dois pontos e o nome do emoji
 Caso não saiba os nomes, há o respositório com os emojis [aqui](https://github.com/ikatyang/emoji-cheat-sheet) criado pela [@ikatyang](https://github.com/ikatyang)

~~~
Olá, pequeno gafanhoto :hand 
Saldando :smile 
~~~
### Então, ficará assim:

Olá, pequeno gafanhoto ✋
Saldando 😸

## Manual Markdown do Curso de Git e GitHub

O [*Gustavo Guanabara*](https://github.com/gustavoguanabara) criou um pdf com os comandos do **markdown** e para acessar é só [clicar aqui](https://github.com/gustavoguanabara/git-github/blob/master/manuais-PDF/guia-markdown.pdf)
