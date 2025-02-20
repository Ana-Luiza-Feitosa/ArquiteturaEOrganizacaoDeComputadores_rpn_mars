

# **TOPO DA PILHA**

---

## **Utilização de Estruturas de Dados do Tipo Pilha para a Implementação de uma Calculadora de Notação Polonesa Reversa no Simulador MARS**

**Unidade Curricular**  
> Arquitetura e Organização de Computadores   
> Docente Responsável: Denise Stringhini  
> Semestre Vigente: 2024/2
<br>


**Discentes**
> Ana Luiza Antonio Feitosa RA: 168517    
> Julia Souza Belmonte Lopes RA: 168906  
> Marcella Fernandes Moraes RA: 170982  
> Pedro Francisco Mariano Zuazo RA: 169063  

---

## **1. Introdução**
O projeto consiste na implementação de uma **Calculadora de Notação Polonesa Reversa (NPR)** utilizando estruturas de dados do tipo pilha em Assembly MIPS no simulador MARS.  

A **Notação Polonesa Reversa** (ou RPN - Reverse Polish Notation) é uma forma de representação de **expressões matemáticas** onde os **operadores vêm depois dos operandos**, eliminando a necessidade de parênteses e facilitando a avaliação de expressões matemáticas.  A calculadora é capaz de realizar operações aritméticas básicas como adição, subtração, multiplicação e divisão. O programa funciona armazenando os números em uma pilha, onde os operandos são empilhados e os operadores retiram os valores necessários para realizar os cálculos.  

**Operações Implementadas:**
- **Adição (+)**
- **Subtração (-)**
- **Multiplicação (*)**
- **Divisão (/)**

Além disso, o programa também **detecta e trata erros** como: **divisão por zero, expressões inválidas e pilha vazia**.

---

## **2. Objetivo**
O objetivo deste projeto é **demonstrar a aplicação de estruturas de dados do tipo pilha** em **Assembly MIPS** para resolver problemas matemáticos de forma eficiente. 

---

## **3. Estrutura do Programa**

### **3.1 Funcionamento**
O funcionamento da calculadora baseia-se na **manipulação de uma pilha**:
1. **Operandos** são empilhados sequencialmente.
2. Quando um **operador** é encontrado, os valores necessários são retirados da pilha.
3. A **operação é realizada** e o resultado é empilhado novamente.
4. O processo se repete até que a expressão seja totalmente resolvida.

### **3.2 Implementação**
A implementação foi realizada utilizando **Assembly MIPS** no **simulador MARS**, explorando os seguintes conceitos:
- Uso da **pilha (Stack Pointer - $sp)** para armazenamento e recuperação de operandos.
- Manipulação de **registradores** para realização das operações matemáticas.
- Entrada e saída de **dados através do software MARS**.

📂 **Acesse o código:**
[Calculadora de Notação Polonesa Reversa](implementacao_calculadora_rpn.asm)

---

## **4. Breve Explicação e Demonstração**
Para uma entender mais sobre a implementação e funcionamento da **calculadora**, assista ao vídeo explicativo no link abaixo:  
 **🔗 Acesse o vídeo: [Vídeo de Explicação](www.youtube.com)**

---

## **5. Conclusão**
O projeto demonstrou a **eficiência do uso de pilhas** na resolução de **expressões matemáticas** através da **Notação Polonesa Reversa**. 

A implementação em **Assembly MIPS** proporcionou uma compreensão mais aprofundada sobre **manipulação de strings, implementação da pilha na memória, e execução de operações matemáticas em um ambiente de baixo nível** e funcionamento do **simulador MARS**.

Esse estudo reforça a importância das **estruturas de dados** na resolução de **problemas computacionais complexos**.

---
