# Anotacoes-Java ♨️

Pontos de destaque até o momento:

`javadoc` - o java doc é um tipo de comentário dentro do java que serve para documentar algum método, linha, classe, etc.

`Atalhos` -  
- `psvm`: esse atalho serve pra auto preencher o comando public static void main(String[] args)
- `Ctrl Shift F10`: esse atalho serve para executar o código.
- `Ctrl Alt L`: esse atalho serve para identar o código
- `Ctrl SHIFT /`: esse atalho serve para comentar um bloco de código ou descomentar.
- sout - digitando esse atalho ele já me fornece o System.out.println().
-  Alt + insert - esse atalho serve pra criar os getters e setter dos atributos ou metódos.



`Convencões`: o java possui algumas convenções que são usadas em padrões de código, por exemplo toda classe precisa ser iniciada com letra maiúscula, se for uma palavra composta por exemplo jeancarlosgoes teria que ser da seguinte maneira a classe
Public class JeanCarlosGoes{}, outra convenção é a de variáveis, as variváveis seguem o oposto todas elas devem ser escritas com a primeira palavra em minusculo por exemplo String jeanCarlos = "Nome Completo". 

`Operadores unários`: os operadores unários são operadores que atuam somente em um valor, variável, tenho como exemplo operações de incremento e decremento.

No Java, podemos usar esses operadores **antes ou depois da variável**, e isso muda o comportamento:

- `++variável` → incrementa **antes** de usar.
- `variável++` → usa o valor **antes** e incrementa **depois**.

- Operador após a variável
int contadorA = 0;
int i = contadorA++;
System.out.println(i); --->  0

 - Operador Antes da variável.

int contadorA = 0;
int i = ++contadorA;
System.out.println(i); --->  1

`Arrays` - Dentro do java percebi algumas mudanças consideráveis na forma de manipular array comparado ao js desde a forma de inicialização e declaração de um vetor, a forma de iniciar um array é a seguinte:

- jeito 1 - int[] idades ={12,21,32,56};

- jeito 2 - 
int idades[];
idades = new int[] {12,21,32,56};

- jeito 3 - 
int idades[4];
idades[0] = 12;
idades[1] = 21;
idades[2] = 32;
idades[3] = 56;

for Each - a sintaxe do for each dentro do java também é diferente, seria da seguinte maneira:

for(tipo = valor: nomeDoArray)
{
 //Logíca //

}













