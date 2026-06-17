Trabalho - Estruturas Avançadas de Árvores

Trabalho feito por:
- Arthur Hartman
- Bryan Mateus Peres
- Hamilton Pacheco da Costa

Introdução: 
As árvores são estruturas de dados muito utilizadas na computação para organizar informações de forma hierárquica. Durante o estudo das Árvores Binárias de Busca (BST), percebe-se que elas podem perder desempenho quando ficam desbalanceadas. Por esse motivo surgiram outras estruturas capazes de manter a árvore mais organizada e eficiente. 
Neste trabalho serão apresentados os conceitos das árvores AVL Rubro-Negra e N-ária, além das principais operações de balanceamento utilizadas nessas estruturas. 


Parte 1 – Tipos de Árvores 

- Árvore AVL 
Conceito: 
A árvore AVL é uma árvore binária de busca que possui balanceamento automático. Ela foi criada para evitar que a árvore cresça mais para um lado do que para o outro, o que poderia prejudicar o desempenho das operações. 

Características: 
. Possui no máximo dois filhos por nó. 
. Mantém a diferença de altura entre as subárvores em no máximo 1. 
. Utiliza rotações para corrigir desequilíbrios. 
. Mantém operações de busca eficientes. 

Vantagens: 
. Excelente desempenho para buscas. 
. Altura da árvore permanece controlada. 
. Menor risco de degradação para casos extremos. 

Desvantagens: 
. Inserções e remoções exigem verificações adicionais. 
. Pode realizar várias rotações para manter o balanceamento. 
. Implementação mais trabalhosa que uma BST comum. 

Exemplo: 
Antes do balanceamento: 

     30 
     / 
    20 
   / 
  10  

Depois da rotação: 

     20 
     /  \ 
   10    30 
 

- Árvore Rubro-Negra 
Conceito: 
A árvore Rubro-Negra também é uma árvore binária de busca balanceada. A diferença é que ela utiliza nós coloridos em vermelho e preto para controlar o balanceamento da estrutura. 

Regras de Coloração: 
. Todo nó é vermelho ou preto. 
. A raiz deve ser preta. 
. Um nó vermelho não pode possuir filho vermelho. 
. Todos os caminhos da raiz até as folhas devem ter a mesma quantidade de nós pretos. 

Vantagens: 
. Necessita de menos rotações do que uma AVL. 
. Inserções e remoções costumam ser rápidas. 
. Muito utilizada em bibliotecas e sistemas reais. 

Desvantagens: 
. Mais difícil de implementar. 
. O balanceamento não é tão rígido quanto o da AVL. 

Exemplo: 

        20(P) 
        /     \ 
     10(V)   30(V) 
 
P = Preto 
V = Vermelho 


- Árvore N-ária 
Conceito:
Uma árvore N-ária é uma estrutura em que cada nó pode possuir vários filhos. Diferentemente das árvores binárias, não existe a limitação de apenas dois filhos. 

Diferenças em relação às árvores binárias: 
A principal diferença é a quantidade de filhos permitida por nó. Enquanto uma árvore binária permite apenas dois, uma árvore N-ária pode possuir quantos forem necessários de acordo com sua implementação. 

Vantagens:
. Representa hierarquias de forma mais natural. 
. Facilita a organização de estruturas complexas. 
. Pode reduzir a profundidade da árvore. 

Desvantagens: 
. Consome mais memória. 
. Algumas operações podem ser mais complexas. 

Exemplo: 

             Raiz 
         /      |      \ 
      A         B       C 
    /   \               | 
   D     E              F 
 

Aplicações Práticas: 
. Sistemas de arquivos. 
. Estrutura de diretórios. 
. Menus de programas. 
. XML e HTML. 
. Organogramas empresariais. 

 
