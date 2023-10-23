Algoritmo MatrizRetangular
inicio do Algoritmo
    Var
        mat: vetor[1..2, 1..3] de inteiro
        i: inteiro
        j: inteiro
    escreva ("digite i")
    leia (i)
    escreva ("digite j")
    leia (j)
    i ← 1
    j ← 1
    Enquanto(i <= 2) faça
        <j ← 1 // resetar j para a coluna 1 a cada nova linha>
        Enquanto j <= 3 faça
            mat[i,j]←1 // preencher o elemento atual com 1
            j←j + 1
        Fim_enquanto
        i ← i + 1
        Fim_enquanto

Fim_algoritmo
