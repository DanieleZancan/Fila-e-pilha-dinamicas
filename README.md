# Fila-e-pilha-dinamicas

Atividade MAPA da matéria Estrutura de Dados I do curso de Graduação de Engenharia de Software (finalizado na data de 07/07/2023)

Criação de um programa na linguagem C para ler as entradas, armazená-las e removê-las das estruturas de Fila e Pilha Dinâmicas, seguindo os seguintes critérios e instruções:

"O DNA (ácido desoxirribonucleico) é um tipo de ácido nucleico que armazena a informação genética da grande maioria dos seres vivos. Essa molécula é formada por nucleotídeos e apresenta, geralmente, a forma de uma dupla-hélice. As bases nitrogenadas estão classificadas em dois grupos: as pirimidinas e purinas. Citosina (C), timina (T) e uracila (U) são pirimidinas, enquanto a adenina (A) e a guanina (G) são purinas. Das bases nitrogenadas citadas, apenas a uracila não é observada no DNA." 

<img src="https://sistemasead.unicesumar.edu.br/flex/amfphp/services/Portal/ImagemQuestionario2/QUE_160621_528887_1.png">

Figura 1: Ligações entre os nucleotídeos e a complementaridade das bases nitrogenadas. Fonte: Brasil escola. 


Com base no contexto da genética abordado acima, você deve construir um algoritmo em linguagem C utilizando os conceitos de FILA DINÂMICA e de PILHA DINÂMICA.

Para que este algoritmo funcione de acordo com o contexto apresentado, você deve:

1 - Ler a entrada de DNA com n caracteres compostos por uma sequência de nucleotídeos (A C T G) e armazená-los em uma estrutura de FILA DINÂMICA. \
2 - Ao concluir a entrada, você deve remover a sequência da fila para a dupla fita do DNA convertendo a sequência de nucleotídeos (T G A C) e armazená-los em uma estrutura de PILHA DINÂMICA. \
3 - Faça a impressão de ambas as estruturas.

Vale ressaltar, que a sequência de nucleotídeos é uma cadeia de caracteres (strings). Leal & Oliveira (2022), em Algoritmos e Lógica de Programação II, ressalta que um tripo string em C é um vetor do tipo char e que ao final da string é armazenado o ‘\0’, por isso é sempre necessário declarar uma string com uma posição a mais do que o número de caracteres que desejamos armazenar.

Quanto as estruturas utilizadas na solução do problema, segundo Oliveira & Pereira (2019), a pilha é uma das estruturas mais simples e mais versáteis dentre as utilizadas na computação, onde os dados são inseridos e removidos no seu topo (LIFO – Last In, Firts Out), enquanto as filas, embora sejam também estruturas muito utilizadas, possuem particularidades fazem com seu funcionamento seja um pouco menos simples do que o das pilhas, pois usam o conceito FIFO (First In, First Out), ou seja, o primeiro que entra é o primeiro que sai. 

Para solucionar o problema apresentado é fundamental desenvolver as seguintes funções de cada estrutura: 

Inserir na fila \
Excluir da fila \
Imprimir a fila \
Inserir na pilha \
Imprimir a pilha

Exemplo:

Fila: ACTTGACCGTTA \
Pilha: TAACGGTCAAGT
