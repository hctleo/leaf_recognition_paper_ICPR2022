# leaf_recognition_paper_ICPR2022
Implementações utilizadas em artigo submetido ao ICPR2022 sobre classificação de plantas baseado em suas folhas.

Foram utilizadas quatro bases de dados largamente difundidas na literatura: MEW2012, Flavia, Swedish e leaf.

Na fase de extração de atributos, fez-se:

1. Conversão das imagens originais para tons de cinza;
2. Limiarização de Otsu;
3. Aplicação de duas operações morfológicas básicas;
4. Extração dos atributos de textura;
5. Operação bitwiseand para combinação das imagens P/B e limiarizada;
6. Extração dos atributos de forma;
7. Alocação dos atributos em um arquivo '.txt'.

Na fase de classificação, utilizou-se quatro classificadores: MLP, Árvore de Decição, kNN e Naive Bayes Gaussiano.
