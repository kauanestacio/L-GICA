#EXPLICAÇÃO

char estado1, estado2;: Armazenam uma letra que representa o estado da cidade (por exemplo, 'A', 'B', etc.).

char codigo1[4], codigo2[4];: Guardam o código da carta de cada cidade, com até 3 caracteres mais o terminador de string '\0'.

char nome1[50], nome2[50];: Armazenam o nome da cidade de cada carta, com até 49 caracteres mais o terminador '\0'.

int pop1, pop2;: Guardam a população de cada cidade.

float area1, area2;: Guardam a área de cada cidade em quilômetros quadrados.

float pib1, pib2;: Guardam o PIB (Produto Interno Bruto) de cada cidade.

int pontos1, pontos2;: Guardam o número de pontos turísticos de cada cidade. 



Se a população da primeira cidade for maior, a primeira carta vence.

Se a população da segunda cidade for maior, a segunda carta vence.

Se as populações forem iguais, ocorre um empate.  


O programa calcula:

Densidade Populacional: população / área
PIB per Capita: PIB / população 

O programa exibe:

Os dados das duas cidades.

O resultado da comparação baseado na população.

