# 🐍 Lógica de Programação com Python: Conteúdo das Aulas

## 1. Revisão de Lógica de Programação
*   **Algoritmos**: Sequência lógica finita de passos para a resolução de um problema.
*   **Variáveis e Tipos de Dados**: Armazenamento de informações na memória.
    *   *Tipos básicos*: Inteiro (`int`), Decimal (`float`), Texto (`str`) e Booleano (`bool`).
*   **Operadores Lógicos e Aritméticos**:
    *   *Aritméticos*: `+`, `-`, `*`, `/`, `%` (resto), `//` (divisão inteira), `**` (potência).
    *   *Relacionais*: `==`, `!=`, `>`, `<`, `>=`, `<=`.
    *   *Lógicos*: `and` (E), `or` (OU), `not` (NÃO).

---

## 2. Princípios de Clean Code (Código Limpo)
*   **Nomes Significativos**: Variáveis e funções devem revelar sua intenção (ex: usar `total_vendas` em vez de `tv` ou `x`).
*   **Regra do Escoteiro**: Deixe o código sempre mais limpo do que como você o encontrou.
*   **Funções Pequenas**: Cada função deve fazer apenas uma coisa, e fazê-la bem.
*   **Comentários Necessários**: O código deve ser autoexplicativo; use comentários apenas para explicar o *porquê*, nunca o *o que* o código faz.
*   **Padrão PEP 8**: Seguir as diretrizes oficiais de estilo para código Python (ex: uso correto de indentação com 4 espaços e caixas de texto).

---

## 3. Estruturas e Comandos em Geral (Sintaxe Python)

### Entrada e Saída de Dados
*   `print()`: Exibe informações no console (saída).
*   `input()`: Captura dados digitados pelo usuário (entrada como string).

### Estruturas Condicionais
*   `if`: Executa um bloco de código se a condição for verdadeira.
*   `elif`: Abreviação de *else if*, testa uma nova condição caso a anterior seja falsa.
*   `else`: Executa um bloco de código se todas as condições anteriores forem falsas.

### Estruturas de Repetição (Loops)
*   `while`: Repete o bloco de código enquanto a condição permanecer verdadeira.
*   `for`: Percorre itens de uma sequência (como uma lista ou um intervalo numérico).
*   `range()`: Gera uma sequência de números para controle do loop `for`.
*   `break`: Interrompe e sai imediatamente do loop.
*   `continue`: Pula a iteração atual e vai para a próxima execução do loop.

### Estruturas de Dados Compostas
*   **Listas** `[]`: Coleções de itens ordenadas e mutáveis.
*   **Tuplas** `()`: Coleções ordenadas e imutáveis (não podem ser alteradas).
*   **Dicionários** `{key: value}`: Coleções não ordenadas de pares chave-valor.

### Definição de Funções
*   `def`: Comando utilizado para declarar uma função ou bloco de código reutilizável.
*   `return`: Finaliza a execução da função e retorna um valor para quem a chamou.
